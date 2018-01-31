## Simple RESTful Controller 
This controller is a basic form of providing RESTful service.

This is a Spring Boot project.

### Installation
1. Just clone/download and open as a new Maven project in your STS or Eclipse.
2. Compile and run application.
3. Use the following URL in your browser to get JSON data over HTML:
```
localhost:8080/books
```

### JSON data
```
[{"id":1,"name":"Spring Boot","author":"James Smith"}]
```
The data is hardcoded in 
```
simple-rest-service/src/main/java/com/gorbich/springboot/basics/springbootdemo/BooksController.java
```