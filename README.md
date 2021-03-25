# maven-archetype-quickstart

This project provides an up to date maven-archetype-quickstart. The artifact has been pushed to [Maven Central Repository](https://search.maven.org/artifact/com.github.ywchang/maven-archetype-quickstart). So you can just use this archetype without the need to clone and pull down the codes.

## Highlight

* JDK 1.8
* junit 5

## How to use

```shell script
mvn archetype:generate \
  -DinteractiveMode=false \
  -DarchetypeGroupId=com.github.ywchang \
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -DarchetypeVersion=1.1 \
  -DgroupId=<Group Id> \
  -DartifactId=<Artifact Id> \
  -Dversion=1.0-SNAPSHOT
``` 

## The archetype catalog

* maven.compiler.source = 1.8
* maven.compiler.target = 1.8
* testImplementation 'org.junit.jupiter:junit-jupiter-engine:5.7.1'
* testImplementation 'org.junit.jupiter:junit-jupiter-params:5.7.1'
