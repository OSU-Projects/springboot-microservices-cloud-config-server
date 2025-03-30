# springboot-microservices-cloud-config-server
This server repository is for configure all client microservices configurations(application.properties)

**Spring-cloud-config-server service**
**Dependencies:** config server, dev tools
Here in server microservice add a property as spring.cloud.config.server.git.uri=file:///C:/Users/saiku/Videos/Springboot-Projects/microservices/git-local-repo

And also @Enableconfig server in main class.

So that server can control all client microservices configuration files.
