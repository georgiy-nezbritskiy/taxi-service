![](https://prnt.sc/7idzdIvpkMcM)
# :rotating_light: 	:rotating_light: 	:rotating_light:
# :raised_hand_with_fingers_splayed: **About**

This application is a simplified version of the taxi service. It allows driver registration, adding a car, adding a driver to a specific car

# :shinto_shrine: **Features**

- registration a new driver
- create, update, delete cars, drivers, manufacturers
- display all information about cars, drivers, manufacturers, cars of current drivers
- log in/ log out

# :spiral_notepad: **Project structure**

## The project has 3-Tier Architecture

1 DAO
 - all database work takes place here (CRUD methods)
2 SERVICE
 - all business login takes place here
3 CONTROLLER
 - all communication between the client and the server takes place here

# :tornado: **Technologies:**

- Java 11
- JDBC
- Maven
- JSP
- MySQL
- Tomcat

# :pencil2: **What needs to be done to start the project?**

- Fork this repository
- Clone the repository to your PC
- Create all tables in your database from the file init_db.sql
- Edit ConnectionUtil.class - set the necessary parameters:

```
    private static final String URL = "URL";
    private static final String USERNAME = "USERNAME";
    private static final String PASSWORD = "PASSWORD";
    private static final String JDBC_DRIVER = "JDBC_DRIVER";
```

- Install [Tomcat](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/)
- Add Tomcat server to configuration
- Run project