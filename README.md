![banner_for_project](https://github.com/Nikostrik/my-taxi-service/assets/32684997/654c83c5-3566-4814-b13f-382789680976)
## 📝 Project description: 

```
It's a small web-application which contain an authentication, registration and other CRUD operations.
```
## 🎯 Features: 

* Register as a driver;
* Authentication like a driver;
* Display list of all drivers;
* Display list of all cars;
* Display list of all manufacturers;
* Display all cars of the current driver;
* Create/remove a car;
* Create/remove a driver;
* Create/remove a manufacture;
* Add car to driver;
## 📂 Structure:

* Controller: Servlet classes responsible for HTTP requests and responses; 
* DAO: Data Access Object interfaces with implementations
* Exception: Custom exceptions used in the application
* Filter: Filter responsible for authentication in project;
* Lib: Annotation for object initialization and custom injector;
* Model: Objects for project; 
* Service: All functions of project;
* Util: Connections to DB which using in DAO;
* Resources: Contains script for create DB and configuration file for logs;
* WEB-INF: All configurations for Servlets;
* Views: JSP pages and CSS file;
## 💻 Technology: 

* Java `v.11`
* JSTL `v.1.2`
* Javax Servlet `v.4.0.1`
* Log4j `v.2.14.1`
* Maven `v.3.8.0`
* MySQL `v.8.0.22`
* Tomcat `v.9.0.50`
* JDBC `v 8.0.22`
* JSP
## ⚙ Installation:

Make sure your Java version from `11` to higher ([download](https://www.oracle.com/java/technologies/downloads/#java20)). You also need to download tomcat ([9 version](https://tomcat.apache.org/download-90.cgi)).
After downloading all the necessary technologies, you need to configure tomcat in the development environment to run the web application.
To do this, select `Edit configurations`, find Tomcat Local and choose your version. The last step is tap on `Run`

