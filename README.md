# TAXI SERVICE
![alt text](https://i.pinimg.com/564x/27/fa/42/27fa42ae145066611271b9ad58c99f4d.jpg)
#### It's a simple web app that shows logic managing for taxi service. In this app you can :
- Create drivers, cars, manufacturers;
- Delete drivers, cars, manufacturers;
- Add new driver to car;
- Get information about all cars belonging to the driver;
- Get information about all cars in our taxi service;
- Get information about all drivers;
- Get information about all manufacturers;

#### _The project is based on N-architecture and SOLID principles. There are 3 layers: CONTROLLERS, SERVICE, and DAO. Also, this app allows access only to authorized drivers and provides the ability to register new ones._

## TECHNOLOGIES:
- Apache Tomcat
- MySQL
- JDBC
- Servlet
- JSTL
- JSP
- HTML, CSS
- Maven
- Maven Checkstyle Plugin

## SETUP
1. Configure Apache Tomcat ->
2. Install MySQL and MySQL Workbench ->
3. Create a schema and all tables by using the script from resources/init_db.sql in MySQL Workbench ->
4. In the /util/ConnectionUtil.java change the URL, USERNAME and PASSWORD values to the ones you specified when installing MySQL, also change JDBC_DRIVER (for example "com.mysql.cj.jdbc.Driver") ->
5. If you want to have information about log into your app.log file change the file path to your absolute path ->
Run application✨