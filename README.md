# Restful-Explore-California-App
It is a simple web service that creates tours, tour packages and ratings for those tours for customers. 
This is spring based microservice. It is restful web service that has endpoints to allow POST, GET, PUT, PATCH and DELETE 
requests. The tours are loaded from a JSON file. The controllers handle request to create tours, packages, rating and comments
for customers. The domain objects are created as JPA entities and an embedded h2 in memory relational database. 

Postman (https://www.getpostman.com/ ) can be used to make these api requests to the deployed service.
All dependencies are in the maven pom.xml file, take note of the dependencies versioning. 
It was deployed with the embedded tomcat database in the IntelliJ Ide. 
