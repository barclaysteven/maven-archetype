# maven-archetype

Custom Maven archetype for Java Projects using testng

## Instructions for creating project from archetype

After changes have been made to the archetype run:

```
mvn install
```

Then using the following command to create the new project:

```
mvn archetype:generate \
  -DarchetypeGroupId=local.barclays \
  -DarchetypeArtifactId=archetype-playground \
  -DarchetypeVersion=1.0 \
  -DgroupId=<group-id> \
  -DartifactId=<artifact-id>
```
