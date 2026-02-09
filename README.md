# Simple maven-project

# Tools and Technology Used
- JDK11
- MAVEN3.8
- Git
- WSL Linux
- VS Code Editor


# Commands Used to Automate Maven Project
 $mvn archetype:generate \
  -DgroupId=xyz.shrutideep.project \
  -DartifactId=maven-project \
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -DinteractiveMode=false


#  This creates a standard Maven project structure as

# maven-project
 |__src/
 |    |_main/java
 |    |     |_xyz/shrutideep/project/app.java
 |    |
 |    |_test/java
 |          |_xyz/shrutideep/project/apptest.java
 |
 |__pom.xml



# Build the project using Maven tool
 $cd maven-project/
 $mvn clean install

#Post Build Success check for Jar/war files in target/ subdirectory


 


