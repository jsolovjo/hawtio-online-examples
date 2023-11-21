# Hawtio-Enabled Camel Quarkus Example

This sample application shows how to make it hawtio-enabled with Camel Quarkus. Once deployed on OpenShift/Kubernetes, it will be discovered by Hawtio Online.

## How to run

Run in development mode with:

```console
mvn compile quarkus:dev
```

Or build the project and execute the runnable JAR:

```console
mvn package && java -jar target/quarkus-app/quarkus-run.jar
```

Hawtio is available at <http://localhost:8080/hawtio>.

By default, authentication is enabled with username `hawtio` & password `hawtio`.
This can be customized together with some of the other Hawtio configuration options by editing
[src/main/resources/application.properties](./src/main/resources/application.properties).