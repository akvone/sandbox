# Why this project does exist?

The main purpose of the `sandbox` project is to give a starting point with an existing code base to play with different
frameworks, libraries, and technologies.

# Prerequisites

* Maven
* JDK v8 (v11 for some modules)

Installed Docker is desirable but is not required 

# Credentials

Most services uses `sandbox`/`sandbox` as user/password pairs

# Modules
## Sandbox modules:
* [kotlin sandbox](sandboxes/kotlin)
* [spring-boot sandbox](sandboxes/spring-boot)
* [spring-cloud sandbox](sandboxes/spring-cloud)
* [spring-boot-postgresql sandbox](sandboxes/spring-boot-postgresql)
* [spring-boot-security sandbox](sandboxes/spring-boot-security)
  
## Other modules
* infrastructure - useful scripts and docker-compose.yaml files
    * kubernetes
    * [monitoring](infrastructure/monitoring)
* maven-parents - sandbox modules use them
* shared
    * shared-resources
    * shared-utils
