# OpenAPI Tanzu Application Accelerator




## Overview
This accelerator takes as input an OpenAPI 3.0 spec 
and returns a project that will create an API server 
from that spec and serve an instance of SwaggerUI
you can use to test out the API.


`./gradlew openApiGenerate`

`mvn spring-boot:run`

*open browser to http://localhost:8080*

Due to limitations in the OpenAPI Gradle plugin and
to keep things simple, the Gradle task generates the
API application in-place, and then you can use
Maven to run the application.

A good example OpenAPI 3.0 spec can be found on the 
OpenAPI Github:
https://raw.githubusercontent.com/openapitools/openapi-generator/master/modules/openapi-generator/src/test/resources/3_0/petstore.yaml

