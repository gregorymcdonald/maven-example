# **Maven Example**
**Author**: Greg McDonald  

## Run Instructions
Run command: `mvn clean compile`   
Then run command: `java -cp target/classes/ example.App`

**OR**

Run command: `mvn clean package`   
Then run command: `java -jar target/maven-example-1.0-SNAPSHOT.jar`  
**Note**: When the main class name if modified, the maven-jar-plugin in the POM must be updated to reflect this name change.

**Reference**: http://www.tutorialspoint.com/maven/
