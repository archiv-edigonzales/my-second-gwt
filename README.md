# my-second-gwt

```
mvn archetype:generate \
   -DarchetypeGroupId=net.ltgt.gwt.archetypes \
   -DarchetypeVersion=LATEST \
   -DarchetypeArtifactId=modular-webapp \
   -DinteractiveMode=false \
   -DgroupId=me -DartifactId=my-second-gwt -Dversion=HEAD-SNAPSHOT
```

```
mvn gwt:codeserver -pl *-client -am
mvn jetty:run -pl *-server -am -Denv=dev
```

localhost:8080
