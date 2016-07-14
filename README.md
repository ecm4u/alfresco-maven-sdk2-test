# Alfresco 5.0 Maven SDK 2.0 Test Project

## Building

    mvn clean test packge

## Deployment

    cp alfresco-maven-sdk2-test/component-a-repo-jar/target/component-a-repo-jar-1.0-SNAPSHOT.jar modules/platform

## Test it

Open http://localhost:8080/alfresco/service/ecm4u/helloworld. It should print `Hello World`.

## Links

* https://docs.alfresco.com/community/concepts/dev-extensions-packaging-techniques-jar-files.html

## License

GNU GPL v2
