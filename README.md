# This is a clone of https://github.com/nanuchi/my-project
## Purpose: I am using nanuchi's Java program to learn how to configure a CI/CD pipeline.

##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
