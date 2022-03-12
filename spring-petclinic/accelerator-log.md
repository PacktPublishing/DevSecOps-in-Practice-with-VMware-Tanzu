# Accelerator Log

## Options
```json
{
  "deploymentType" : "workload",
  "projectName" : "spring-petclinic"
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
┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Exclude)
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug .editorconfig matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .github/workflows/maven-build.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE.txt matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug build.gradle.skip matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug docker-compose.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/DEPLOYING.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/deployment.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/service.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug readme.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug settings.gradle.skip matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle-suppressions.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/PetClinicApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/BaseEntity.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/NamedEntity.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/Person.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/package-info.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Owner.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Pet.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetRepository.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetType.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetValidator.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/VisitController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CacheConfiguration.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CrashController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Specialty.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vet.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vets.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/Visit.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/VisitRepository.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-mysql.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-postgres.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/banner.txt matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/data.sql matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/schema.sql matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/data.sql matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/schema.sql matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/data.sql matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/petclinic_db_setup_mysql.txt matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/schema.sql matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/user.sql matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/data.sql matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/petclinic_db_setup_postgres.txt matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/schema.sql matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_de.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_en.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_es.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/css/petclinic.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.eot matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.ttf matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.woff matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.eot matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.ttf matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.woff matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/favicon.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/pets.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/platform-bg.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow-mobile.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-pivotal-logo.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/error.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/inputField.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/layout.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/selectField.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/createOrUpdateOwnerForm.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/findOwners.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownerDetails.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownersList.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdatePetForm.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdateVisitForm.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/vets/vetList.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/welcome.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/header.scss matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/petclinic.scss matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/responsive.scss matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/typography.scss matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/PetclinicIntegrationTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/model/ValidatorTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/OwnerControllerTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetControllerTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetTypeFormatterTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/VisitControllerTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/ClinicServiceTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/EntityUtils.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/system/CrashControllerTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetControllerTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┗ Debug src/test/jmeter/petclinic_test_plan.jmx matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**]
┃ ┃ ┃ ┃ ┃ Debug .editorconfig didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug .github/workflows/maven-build.yml matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE.txt didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug build.gradle.skip matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug docker-compose.yml didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/DEPLOYING.md matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/Tiltfile matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/deployment.yaml matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/service.yaml matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug readme.md matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug settings.gradle.skip matched [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle-suppressions.xml didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle.xml didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/PetClinicApplication.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/BaseEntity.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/NamedEntity.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/Person.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/package-info.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Owner.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Pet.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetController.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetRepository.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetType.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetValidator.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/VisitController.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CacheConfiguration.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CrashController.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Specialty.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vet.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetController.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vets.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/Visit.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/VisitRepository.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-mysql.properties didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-postgres.properties didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/banner.txt didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/data.sql didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/schema.sql didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/data.sql didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/schema.sql didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/data.sql didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/petclinic_db_setup_mysql.txt didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/schema.sql didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/user.sql didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/data.sql didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/petclinic_db_setup_postgres.txt didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/schema.sql didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages.properties didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_de.properties didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_en.properties didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_es.properties didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/css/petclinic.css didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.eot didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.svg didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.ttf didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.woff didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.eot didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.svg didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.ttf didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.woff didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/favicon.png didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/pets.png didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/platform-bg.png didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow-mobile.png didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow.png didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-pivotal-logo.png didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/error.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/inputField.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/layout.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/selectField.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/createOrUpdateOwnerForm.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/findOwners.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownerDetails.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownersList.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdatePetForm.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdateVisitForm.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/vets/vetList.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/welcome.html didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/header.scss didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/petclinic.scss didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/responsive.scss didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/typography.scss didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/PetclinicIntegrationTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/model/ValidatorTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/OwnerControllerTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetControllerTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetTypeFormatterTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/VisitControllerTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/ClinicServiceTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/EntityUtils.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/system/CrashControllerTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetControllerTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetTests.java didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┗ ┗ Debug src/test/jmeter/petclinic_test_plan.jmx didn't match [pom.xml, readme.md, kubernetes/**, catalog/*.yaml, .github/**, build.gradle*, settings.gradle*, gradlew*, gradle/**] -> included
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ Debug .editorconfig didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .github/workflows/maven-build.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE.txt didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug build.gradle.skip didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug docker-compose.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/DEPLOYING.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/Tiltfile didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/deployment.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/service.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ Debug readme.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug settings.gradle.skip didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle-suppressions.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/PetClinicApplication.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/BaseEntity.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/NamedEntity.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/Person.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/package-info.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Owner.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Pet.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetRepository.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetType.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetValidator.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/VisitController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CacheConfiguration.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CrashController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Specialty.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vet.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vets.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/Visit.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/VisitRepository.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-mysql.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-postgres.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/banner.txt didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/data.sql didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/schema.sql didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/data.sql didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/schema.sql didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/data.sql didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/petclinic_db_setup_mysql.txt didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/schema.sql didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/user.sql didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/data.sql didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/petclinic_db_setup_postgres.txt didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/schema.sql didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_de.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_en.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_es.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/css/petclinic.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.eot didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.svg didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.ttf didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.woff didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.eot didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.svg didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.ttf didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.woff didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/favicon.png didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/pets.png didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/platform-bg.png didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow-mobile.png didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow.png didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-pivotal-logo.png didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/error.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/inputField.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/layout.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/selectField.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/createOrUpdateOwnerForm.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/findOwners.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownerDetails.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownersList.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdatePetForm.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdateVisitForm.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/vets/vetList.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/welcome.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/header.scss didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/petclinic.scss didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/responsive.scss didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/typography.scss didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/PetclinicIntegrationTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/model/ValidatorTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/OwnerControllerTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetControllerTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetTypeFormatterTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/VisitControllerTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/ClinicServiceTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/EntityUtils.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/system/CrashControllerTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetControllerTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug src/test/jmeter/petclinic_test_plan.jmx didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [spring-petclinic->spring-petclinic]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'k8s-simple') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'k8s-simple') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [kubernetes/tap/workload.yaml]
┃ ┃ ┃ ┃ ┃ Debug .editorconfig didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .github/workflows/maven-build.yml didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE.txt didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug build.gradle.skip didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug docker-compose.yml didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/DEPLOYING.md didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/Tiltfile didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/deployment.yaml didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/service.yaml didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml matched [kubernetes/tap/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug readme.md didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug settings.gradle.skip didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle-suppressions.xml didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle.xml didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/PetClinicApplication.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/BaseEntity.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/NamedEntity.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/Person.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/package-info.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Owner.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Pet.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetController.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetRepository.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetType.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetValidator.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/VisitController.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CacheConfiguration.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CrashController.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Specialty.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vet.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetController.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vets.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/Visit.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/VisitRepository.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-mysql.properties didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-postgres.properties didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/banner.txt didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/data.sql didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/schema.sql didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/data.sql didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/schema.sql didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/data.sql didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/petclinic_db_setup_mysql.txt didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/schema.sql didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/user.sql didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/data.sql didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/petclinic_db_setup_postgres.txt didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/schema.sql didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages.properties didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_de.properties didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_en.properties didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_es.properties didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/css/petclinic.css didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.eot didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.svg didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.ttf didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.woff didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.eot didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.svg didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.ttf didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.woff didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/favicon.png didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/pets.png didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/platform-bg.png didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow-mobile.png didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow.png didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-pivotal-logo.png didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/error.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/inputField.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/layout.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/selectField.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/createOrUpdateOwnerForm.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/findOwners.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownerDetails.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownersList.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdatePetForm.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdateVisitForm.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/vets/vetList.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/welcome.html didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/header.scss didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/petclinic.scss didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/responsive.scss didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/typography.scss didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/PetclinicIntegrationTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/model/ValidatorTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/OwnerControllerTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetControllerTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetTypeFormatterTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/VisitControllerTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/ClinicServiceTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/EntityUtils.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/system/CrashControllerTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetControllerTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetTests.java didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug src/test/jmeter/petclinic_test_plan.jmx didn't match [kubernetes/tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [: spring-petclinic->: spring-petclinic]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[1].transformations[1] (RewritePath)
┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'kubernetes/tap/workload.yaml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yaml, folder=kubernetes/tap/, filename=workload.yaml, g0=kubernetes/tap/workload.yaml, g1=kubernetes/tap/, g2=workload.yaml, g3=workload.yaml, g4=.yaml} and was rewritten to 'config/workload.yaml'
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[5].<combo> (Chain)
┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ Debug .editorconfig didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .github/workflows/maven-build.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE.txt didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug build.gradle.skip didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug docker-compose.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/DEPLOYING.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/Tiltfile didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/deployment.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/service.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug readme.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug settings.gradle.skip didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle-suppressions.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/PetClinicApplication.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/BaseEntity.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/NamedEntity.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/Person.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/package-info.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Owner.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Pet.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetRepository.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetType.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetValidator.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/VisitController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CacheConfiguration.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CrashController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Specialty.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vet.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vets.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/Visit.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/VisitRepository.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-mysql.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-postgres.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/banner.txt didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/data.sql didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/schema.sql didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/data.sql didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/schema.sql didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/data.sql didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/petclinic_db_setup_mysql.txt didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/schema.sql didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/user.sql didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/data.sql didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/petclinic_db_setup_postgres.txt didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/schema.sql didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_de.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_en.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_es.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/css/petclinic.css didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.eot didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.svg didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.ttf didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.woff didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.eot didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.svg didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.ttf didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.woff didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/favicon.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/pets.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/platform-bg.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow-mobile.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-pivotal-logo.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/error.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/inputField.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/layout.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/selectField.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/createOrUpdateOwnerForm.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/findOwners.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownerDetails.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownersList.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdatePetForm.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdateVisitForm.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/vets/vetList.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/welcome.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/header.scss didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/petclinic.scss didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/responsive.scss didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/scss/typography.scss didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/PetclinicIntegrationTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/model/ValidatorTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/OwnerControllerTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetControllerTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetTypeFormatterTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/VisitControllerTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/ClinicServiceTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/EntityUtils.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/system/CrashControllerTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetControllerTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetTests.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug src/test/jmeter/petclinic_test_plan.jmx didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [spring-petclinic->spring-petclinic]
┃ ┃ ┃ ┏ README (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(Append))
┃ ┃ ┃ ┃ README.merge (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ README.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ ┃ README.merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [readme.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .editorconfig didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .github/workflows/maven-build.yml didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE.txt didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle.skip didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yml didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/DEPLOYING.md didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/Tiltfile didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/deployment.yaml didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/service.yaml didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug readme.md matched [readme.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle.skip didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle-suppressions.xml didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle.xml didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/PetClinicApplication.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/BaseEntity.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/NamedEntity.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/Person.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/package-info.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Owner.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Pet.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetController.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetRepository.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetType.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetValidator.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/VisitController.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CacheConfiguration.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CrashController.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Specialty.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vet.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetController.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vets.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/Visit.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/VisitRepository.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-mysql.properties didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-postgres.properties didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/banner.txt didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/data.sql didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/schema.sql didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/data.sql didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/schema.sql didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/data.sql didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/petclinic_db_setup_mysql.txt didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/schema.sql didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/user.sql didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/data.sql didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/petclinic_db_setup_postgres.txt didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/schema.sql didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages.properties didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_de.properties didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_en.properties didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_es.properties didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/css/petclinic.css didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.eot didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.svg didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.ttf didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.woff didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.eot didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.svg didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.ttf didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.woff didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/favicon.png didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/pets.png didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/platform-bg.png didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow-mobile.png didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow.png didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-pivotal-logo.png didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/error.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/inputField.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/layout.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/selectField.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/createOrUpdateOwnerForm.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/findOwners.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownerDetails.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownersList.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdatePetForm.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdateVisitForm.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/vets/vetList.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/welcome.html didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/scss/header.scss didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/scss/petclinic.scss didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/scss/responsive.scss didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/scss/typography.scss didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/PetclinicIntegrationTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/model/ValidatorTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/OwnerControllerTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetControllerTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetTypeFormatterTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/VisitControllerTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/ClinicServiceTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/EntityUtils.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/system/CrashControllerTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetControllerTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetTests.java didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/jmeter/petclinic_test_plan.jmx didn't match [readme.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[0].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[0].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [## Running petclinic locally->## Running petclinic...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'k8s-simple') evaluated to false
┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ ┃ README.merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [kubernetes/tap/DEPLOYING.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .editorconfig didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .github/workflows/maven-build.yml didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE.txt didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle.skip didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug docker-compose.yml didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/DEPLOYING.md didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/Tiltfile didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/deployment.yaml didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/k8s/service.yaml didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md matched [kubernetes/tap/DEPLOYING.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug readme.md didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle.skip didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle-suppressions.xml didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/checkstyle/nohttp-checkstyle.xml didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/PetClinicApplication.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/BaseEntity.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/NamedEntity.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/Person.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/model/package-info.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Owner.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/Pet.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetController.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetRepository.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetType.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetTypeFormatter.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/PetValidator.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/owner/VisitController.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CacheConfiguration.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/CrashController.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Specialty.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vet.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetController.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/vet/Vets.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/Visit.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/springframework/samples/petclinic/visit/VisitRepository.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-mysql.properties didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-postgres.properties didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/banner.txt didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/data.sql didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/h2/schema.sql didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/data.sql didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/hsqldb/schema.sql didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/data.sql didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/petclinic_db_setup_mysql.txt didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/schema.sql didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/mysql/user.sql didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/data.sql didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/petclinic_db_setup_postgres.txt didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/db/postgres/schema.sql didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages.properties didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_de.properties didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_en.properties didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/messages/messages_es.properties didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/css/petclinic.css didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.eot didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.svg didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.ttf didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/montserrat-webfont.woff didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.eot didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.svg didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.ttf didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/fonts/varela_round-webfont.woff didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/favicon.png didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/pets.png didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/platform-bg.png didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow-mobile.png didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-logo-dataflow.png didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/resources/images/spring-pivotal-logo.png didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/error.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/inputField.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/layout.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/fragments/selectField.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/createOrUpdateOwnerForm.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/findOwners.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownerDetails.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/owners/ownersList.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdatePetForm.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/pets/createOrUpdateVisitForm.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/vets/vetList.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/welcome.html didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/scss/header.scss didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/scss/petclinic.scss didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/scss/responsive.scss didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/scss/typography.scss didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/PetclinicIntegrationTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/model/ValidatorTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/OwnerControllerTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetControllerTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/PetTypeFormatterTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/owner/VisitControllerTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/ClinicServiceTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/service/EntityUtils.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/system/CrashControllerTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetControllerTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/springframework/samples/petclinic/vet/VetTests.java didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/jmeter/petclinic_test_plan.jmx didn't match [kubernetes/tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[2].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[2].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [spring-petclinic->spring-petclinic]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[2].<combo>.transformations[1].transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗ Debug Path 'kubernetes/tap/DEPLOYING.md' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.md, folder=kubernetes/tap/, filename=DEPLOYING.md, g0=kubernetes/tap/DEPLOYING.md, g1=kubernetes/tap/, g2=DEPLOYING.md, g3=DEPLOYING.md, g4=.md} and was rewritten to 'readme.md'
┃ ┃ ┃ ┃ ┏ README.merge.transformations[1] (UniquePath)
┃ ┃ ┗ ┗ ┗ Debug Multiple representations for path 'readme.md', will concatenate them together
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
