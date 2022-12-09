SOURCE_IMAGE = os.getenv("SOURCE_IMAGE", default='harbor-tanzu.eng.vmware.com/workloads/hugo-staff-health-app')
LOCAL_PATH = os.getenv("LOCAL_PATH", default='local-path')
NAMESPACE = os.getenv("NAMESPACE", default='default')

k8s_custom_deploy(
    'hugo-staff-health-app',
    apply_cmd="tanzu apps workload apply -f config/workload.yaml --live-update" +
        " --local-path " + LOCAL_PATH +
        " --source-image " + SOURCE_IMAGE +
        " --namespace " + NAMESPACE +
        " --yes >/dev/null" +
        " && kubectl get workload hugo-staff-health-app --namespace " + NAMESPACE + " -o yaml",
    delete_cmd="tanzu apps workload delete -f config/workload.yaml --namespace " + NAMESPACE + " --yes" ,
    deps=['pom.xml', './target/classes'],
    container_selector='workload',
    live_update=[
        sync('./target/classes', '/workspace/BOOT-INF/classes')
    ]
)

k8s_resource('hugo-staff-health-app', port_forwards=["8080:8080"],
    extra_pod_selectors=[{'serving.knative.dev/service': 'hugo-staff-health-app'}])

allow_k8s_contexts('tap')
