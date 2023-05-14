<h1 align = "center"> Instagram Design </h1>

<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.0.5-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>
This project is a Managing User data built using Spring Boot with Java.

---

## Framework Used
* Spring Boot

---

## Language Used
* Java

---

>## Data flow
 The application is built using the SpringBoot framework and consists of four layers: DTO, model, service, and repository.-

* **DTO** -The DTO layer consists of classes that are used to transfer data between different layers of the application
* **Controller** - The controller layer handles the HTTP requests, translates the JSON parameter to object, and authenticates the request and transfer it to the business (service) layer. In short, it consists of views i.e., frontend part.
* **Service** -The business layer handles all the business logic. It consists of service classes and uses services provided by data access layers.
* **Repository** - This layer mainatains the h2-database thing on which CRUD operations are performed
* **Model** - This layer consists basically the class level things- the various classes required for the project and these classes consists the attributes to be stored.

>## API Documentation
The API endpoints will be available at http://localhost:8080.

## Dependencies
The following dependencies are required to run the project:

* Spring Boot Dev Tools
* Spring Web
* Spring Data JPA
* MySQL Driver
* Lombok
* Validation
* Swagger

<br>


## Data Model

The Job data model is defined in the Job class, which has the following attributes:
<br>

* User Model
```
Id : integer
firstName : string
lastName : string
age : integer
email : string
password : string
phoneNumber : string
```

* Post Model
```
postId = Long
createdDate : Timestamp
updatedDate : Timestamp
postData : String
@ManyToOne
user : User

```

* Authentication Token
```
tokenId : Long
token : string
tokenCreationDate : LocalDate
@OneToOne 
user : User
```




>## Project Summary
This project includes the basic design of the backend of Instagram, including user and post models, and API endpoints for user authentication and post creation/retrieval. Further improvements can be made to include additional features such as comment and like functionality.

## Author

👤 **Pooja Gurnule**

* GitHub: [Pooja Gurnule](https://github.com/poojagurnule)

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page]("url").

---

## Show your support

Give a ⭐️ if this project helped you!

---

## 📝 License

Copyright © 2023 [Pooja Gurnule](https://github.com/poojagurnule).<br />
