# javaee8-essentials-archetype

This is a quickstart maven archetype for creating greenfield Java EE 8 projects.

## To use it we can execute the following commands:

1. clone the project for you local machine:

```
git clone git@github.com:jlmc/javaee8-essentials-archetype.git
```


2. we can clone this project, and execute the maven command:

```
mvn install
```

This command will create the archetype in your local repository


2. After the previous step we are able to create a project using this archetype 

```
mvn archetype:generate \
 -DarchetypeGroupId=org.costajlmpp \
 -DarchetypeArtifactId=javaee8-essentials-archetype \
 -DarchetypeVersion=0.0.1 \
 -DgroupId=<your groupId> \
 -DartifactId=<your artifactId>
```
