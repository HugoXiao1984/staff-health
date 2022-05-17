# Accelerator Log

## Options
```json
{
  "projectName" : "hugo-staff-health-app",
  "repositoryPrefix" : "dev.local"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Exclude)
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**/*]
┃ ┃ ┃ ┃ ┃ Debug .mvn/1 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug accelerator-log.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/README.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/catalog-info.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/components/backstage.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/add-docs.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/components/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/add-docs.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/backstage-domain.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/add-docs.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-org.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-team.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-user.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/backstage-system.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/add-docs.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog-info.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/README.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/catalog-info.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/redis-server.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/sh-appserver.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/sh-db.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/sh-ui.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-web/sh-web.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/add-docs.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-architecture.png matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-ui.png matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/cloudapps-domain.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/dev-dept.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/it-dept.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/org.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-a-group.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-b-group.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/sh-db-resource.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/sh-system.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┗ Debug workflows/code-scan.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**]
┃ ┃ ┃ ┃ ┃ Debug .mvn/1 didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug accelerator-log.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/README.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/catalog-info.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/components/backstage.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/add-docs.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/components/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/add-docs.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/backstage-domain.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/add-docs.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-org.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-team.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-user.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/backstage-system.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/add-docs.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog-info.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/README.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/catalog-info.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/redis-server.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/sh-appserver.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/sh-db.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/sh-ui.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-web/sh-web.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/add-docs.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-architecture.png didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-ui.png didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/cloudapps-domain.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/dev-dept.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/it-dept.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/org.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-a-group.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-b-group.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/sh-db-resource.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/sh-system.yaml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┗ ┗ Debug workflows/code-scan.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, .github/workflows/**] -> included
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [config/*.yaml, Tiltfile]
┃ ┃ ┃ ┃ ┃ Debug .mvn/1 didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [config/*.yaml, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ Debug accelerator-log.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/README.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/catalog-info.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/backstage.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/add-docs.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/add-docs.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/backstage-domain.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/add-docs.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-org.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-team.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-user.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/backstage-system.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/add-docs.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog-info.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/README.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/catalog-info.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/redis-server.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/sh-appserver.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/sh-db.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/sh-ui.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-web/sh-web.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/add-docs.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-architecture.png didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-ui.png didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/cloudapps-domain.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/dev-dept.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/it-dept.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/org.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-a-group.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-b-group.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/sh-db-resource.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/docs/index.md didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/mkdocs.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/sh-system.yaml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┗ Debug workflows/code-scan.yml didn't match [config/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [tanzu-java-web-app->hugo-staff-health-ap...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[1] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [your-registry.io/project->dev.local]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ Debug .mvn/1 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug accelerator-log.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/backstage.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/add-docs.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/add-docs.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/backstage-domain.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/add-docs.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-org.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-team.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-user.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/backstage-system.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/add-docs.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/redis-server.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/sh-appserver.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/sh-db.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/sh-ui.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-web/sh-web.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/add-docs.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-architecture.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-ui.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/cloudapps-domain.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/dev-dept.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/it-dept.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/org.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-a-group.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-b-group.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/sh-db-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/sh-system.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┗ Debug workflows/code-scan.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [tanzu-java-web-app->hugo-staff-health-ap...(truncated)]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ Debug .mvn/1 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug accelerator-log.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/README.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/catalog-info.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/backstage.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/add-docs.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/components/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/add-docs.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/backstage-domain.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/add-docs.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/domains/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-org.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-team.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/groups/default-user.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/backstage-system.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/add-docs.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug backstage/systems/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog-info.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/README.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/catalog-info.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/redis-server/redis-server.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-appserver/sh-appserver.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-db/sh-db.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-ui/sh-ui.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/components/sh-web/sh-web.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/add-docs.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-architecture.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/images/yelb-ui.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/cloudapps-domain.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/domains/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/dev-dept.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/it-dept.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/org.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-a-group.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/groups/team-b-group.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/resources/sh-db-resource.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug sh-catalog/systems/sh-system.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug workflows/code-scan.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [tanzu-java-web-app->hugo-staff-health-ap...(truncated)]
┃ ┃ ┗ ┗ ┗ ╺ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[1].transformations[1] (RewritePath)
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
