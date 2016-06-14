# maven_version_test


Creating projects using 
mvn archetype:generate -Dfilter=maven-archetype

org.apache.maven.archetypes:maven-archetype-quickstart
Define value for property 'groupId': : com.devtests.maven-version-test
Define value for property 'artifactId': : simpleone
Define value for property 'version': 1.0-SNAPSHOT: 1.0.1
Define value for property 'package': com.devtests.maven-version-test:
Confirm properties configuration:
groupId: com.devtests.maven-version-test
artifactId: simpleone
version: 1.0.1


org.apache.maven.archetypes:maven-archetype-webapp
Define value for property 'groupId': : com.devtests.maven-version-test
Define value for property 'artifactId': : webone
Define value for property 'version': 1.0-SNAPSHOT: 1.0.0
Define value for property 'package': com.devtests.maven-version-test:
Confirm properties configuration:
groupId: com.devtests.maven-version-test
artifactId: webone
version: 1.0.0

Experiment with:
$ mvn archetype:generate -DgroupId=com.mkyong.core -DartifactId=ProjectName
	-DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
mvn archetype:generate -DgroupId=com.mkyong.web -DartifactId=ProjectName
	-DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false