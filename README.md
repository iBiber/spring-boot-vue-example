# spring-boot-vue-example
An example project how to serve a vue application with spring-boot which is build with maven.

To build and run the project, you need to install:
* At least a Java 8 JDK
* Maven

You can build the project with:  
`mvn clean install` or  
`mvn clean install -DskipTests` if you don't want to execute the tests.

Then you can start the spring-boot service with:  
`java -jar .\spring-boot-service\target\spring-boot-service-1.0-SNAPSHOT-exec.jar`

After the service has been started, you can access the Vue-App with this link:  
http://localhost:8080/ui/index.html
