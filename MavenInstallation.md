# Install Maven on Ubuntu OS.
    apt update
    apt install maven -y

### Validate the installation
    mvn --version

### Create a quick Start project
   
    #Run the below command to create a archetype
    
     mvn archetype:generate 
     
     # Provide groupid ( I am taking com.raman) artifactid ( I am taking myproj) 
     It will create a directory src and pom.xml file
     
     # Try below commands
     
     mvn compile # To compile the code and create target folder
     
     mvn clean # To clean Target folder
     
     mvn package # To create jar/war file in target folder.
     
     java -cp /target/myproj-1.0-SNAPSHOT.jar com.raman.App # To run the jar file
     
     
     
     
     
    
