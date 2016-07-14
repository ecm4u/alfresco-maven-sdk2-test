# Alfresco 5.0 Maven SDK 2.0 Test Project

## Building

    mvn clean test packge

## Deployment

    $ cp alfresco-maven-sdk2-test/component-a-repo-jar/target/component-a-repo-jar-1.0-SNAPSHOT.jar \
        modules/platform
    $ cp alfresco-maven-sdk2-test/component-a-share-jar/target/component-a-share-jar-1.0-SNAPSHOT.jar \
        modules/share

## Test it

Open [http://localhost:8080/alfresco/service/ecm4u/helloworld](http://localhost:8080/alfresco/service/ecm4u/helloworld). It should print `Hello World`.

Open [http://localhost:8080/share/page/ecmstuff/helloworld-dashlet](http://localhost:8080/share/page/ecmstuff/helloworld-dashlet). It should print `Custom Dashlet Example\nHello world!`.

Add the `Hello World Aikau Dashlet` to your Share dashboard. It should be displayed like this:

![screenshot of dashlet](https://raw.githubusercontent.com/ecm4u/alfresco-maven-sdk2/tes/master/images/custom-dashlet-exmaple.png)


## Links

* https://docs.alfresco.com/community/concepts/dev-extensions-packaging-techniques-jar-files.html

## License

GNU GPL v2
