This maven quickstart is used to generate a skeleton plugin for Kafka Connect. 

```
mvn archetype:generate -DarchetypeGroupId=io.confluent.maven -DarchetypeArtifactId=kafka-connect-quickstart -DarchetypeVersion=0.10.0.0 
```

```
mvn archetype:generate -DarchetypeGroupId=io.confluent.maven -DarchetypeArtifactId=kafka-connect-quickstart -DarchetypeVersion=0.10.0.0 -Dpackage=io.confluent.examples -DgroupId=io.confluent.examples -DartifactId=testconnect -DpackageName=io.confluent.examples -Dversion=1.0-SNAPSHOT
```
