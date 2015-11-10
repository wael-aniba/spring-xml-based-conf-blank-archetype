Example Spring XML CONF BASED PROJECT - Spring IOC - Spring MVC - Spring AOP
============================

The application how to integrate spring IOC, spring AOP and spring MVC. The project is based on xml configuration.

Requirements
------------
* [Java Platform (JDK) 7](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [Apache Maven 3.x](http://maven.apache.org/)
* [Apache tomcat 7 or later]
* [Mysql ]

Quick start
-----------
1. See domainContext.xml and adapt the default configuration.
   See spring-app-web/pom.xml and configure server port.
   define a user in tomcat (username, pass: admin,admin) with role "manager-script" to
   enable deployment on server.
2. Run from eclipse as maven build without specifying any goal since the 
   default goal is configured in the parent pom.xml file.
3. You can start coding ...