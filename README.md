# SpringMVCCRUDSimple
* CRUD (Create, Read, Update and Delete) application is the most important application for creating any project. It provides an idea to     develop a large project. In spring MVC, we can develop a simple CRUD application.
* CRUD is an acronym for CREATE, READ, UPDATE and DELETE which are basic functions of persistent storage. CRUD operations can use forms or   an interface view to retrieve and return data from a database.

## Choose Correct/Latest Architecture based Web Application Development Approach
There are some approaches given below to apply for Web Application Development

Using JSP
---------

Using MVC 
---------
--- Advantages---
  1. using mvc we can separate presentation , business and its data handling logics through different layers.
	2. we don't require to write business logics in jsp here. jsp is used to represent the presentation part only
     through view of mvc architecture.
	3. mvc application is model ,view and controller based architecture to develop web applications so here view
     for presentation part, model for data handling and controller to pass the control between them.
	4. here we can separate business logic from its presentation logic through DAO or ORM supports.  
   -----Disadvantages-----
   1) Increased complexity
   2) Need multiple programmers
   3) Knowledge on multiple technologies is required.
   4) Developer have knowledge of client side code and html code.

## Create Application with CRUD Implementation
In this article we will create applications for personal records management with the following technologies:
* Java Servlets and Java Server Pages (JSP)
* JSP Standard Tag Library (JSTL)
* Java Database Connectivity (JDBC)

The following tools can be used for the development:
* Eclipse IDE for Java EE Developers (one of the newer versions is recommended)
* Apache Tomcat ver 8.5
