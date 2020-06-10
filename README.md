## Sample Apllication with Spring Boot

### Demonstration
This modules demonstrates 
- API Layer (Controller Layer)
- Service Layer
- Data Access Layer
 (on the basis of Spring Boot ) 

### Build
- clone this project on your working directory
- Implement Maven Lifecycle intall
- Then, 
bash
 ```
$ cd target
$ java -jar demo-0.0.1-SNAPSHOT.jar
```

- now you can access localhost:8080/api/v1/person

### Data Base Config
- create db called "demodb" at postgreSQL on port 5432:5432
- create user called "postgres" and create role which has all previleges.
- by setting up tom-cat server, automatically the entire file will be migrated.
- If you want to change db setting, please change `application.yml` 
to get further info to make use of this module.
