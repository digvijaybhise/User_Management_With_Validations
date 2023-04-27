<center>
<h1> USER MANAGEMENT SYSTEM WITH VALIDATIONS </h1>
</center>
<center>
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.0.5-brightgreen.svg" />
</a>
</center>
This project is a User management system with validations built using Spring Boot with Java.

---

## Framework Used
* Spring Boot

---

## Language Used
* Java

---

## Data Model

The user data model is defined in the User class, which has the following attributes:
```
UserId : Unique identifies fir each user
username : User Name of the user
DateOfBirth : Date of Birth of the user
email : email id of the user
Phone Number : Phone number of the user
Date : Date when user added or updated
Time : Time when user added or updated
```

---

## Data Flow

```
The user sends a request to the application through the API endpoints.
```
<center>
<font color="blue">
&#8595;</font>
<center>

```
The API receives the request and sends it to the appropriate controller method.
```
<center>
<font color="blue">
&#8595;</font>
<center>

```
The controller method makes a call to the method in service class.
```
<center>
<font color="blue">
&#8595;</font>
<center>

```
The method in service class builds logic and retrieves or modifies data, which is in turn given to controller class
```

<center>
<font color="blue">
&#8595;</font>
<center>

```
The controller method returns a response to the API.
```
<center>
<font color="blue">
&#8595;</font>
<center>

```
The API sends the response back to the user.
```

---

## Functions used :-

### API Endpoints :-


* PostMapping: /addUser
```
In database we add a new user given through API.
```

* GetMapping: /getAll
```
This endpoint gives us the data of all users stored in our data baase
```

* GetMapping: "getUser/{userid}"
```
This endpoint returns data of specific user based on userid through API
```

* PutMapping
```
In database we update a user by userid given through API.
```

* DeleteMapping
```
In database we delete a user by userid given through API.
```

---

## Data structure Used
* ArrayList
```
We have used Hashmap data structure as a database to implement Operations 
```
---

## Project Summary
The User Management System with Validations is a Spring Boot project written in Java that enables basic functionality for managing users. This project is built using the Spring Boot framework. The project uses ArrayList as the data structure to store and manage user data.
