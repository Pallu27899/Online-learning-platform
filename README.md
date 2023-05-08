# Online-learning-platform 📚

This is an online learning platform that allows users to enroll and learn courses, add those to their wishlist, and manage the entire application. The platform has modes of operation: USER, and PROFESSOR.

# Features 📚

PROFESSOR Mode: Check available user list and courses, add new courses and chapters, enroll in courses, view and edit professor profile details, and view various statistics on the professor dashboard.

USER Mode: Enroll in courses, view and edit user profile details, view available courses and wishlist, and view various statistics on the user dashboard.


# Usage 📚
To use the platform, follow these steps:

Register for a new account or log in with an existing account.
Select your desired mode of operation (ADMIN, USER, or PROFESSOR).
Perform the necessary actions based on your mode of operation (see Features section).
Log out of the platform when finished.

# Installation & Run 📚
Before running the API server, you should update the database config inside the application.properties file.

Update the port number, username and password as per your local database config. server.port=8080

spring.datasource.url=jdbc:mysql://localhost:3306/learningsystem spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver spring.datasource.username=mysql username spring.datasource.password=YourPassword spring.jpa.hibernate.ddl-auto=update

API Root Endpoint https://localhost:8080/

# Tech Stacks:📚

* Java
* Spring Boot
* Maven
* Lombok
* MySql
* SpringData Jpa
* Hibernate

# Contributors 

 [Pallavi Bobale](https://github.com/Pallu27899)
