# REST API Endpoints

[![N|Solid](https://i0.wp.com/flixtel.in/wp-content/uploads/2018/02/cropped-mpls-new-1.png?resize=150%2C150)](https://www.upgrad.com/)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/BradPrit09/Quora-Demo.git)

In this project, we worked on developing REST API endpoints of various functionalities required for a website (similar to Quora) from scratch. In order to observe the functionality of the endpoints, we w used the Swagger user interface and store the data in the PostgreSQL database. Also, the project has to be implemented using Java Persistence API (JPA).

 
# New Features!
The following API endpoints are  implemented in respective classes:
  - signup - "/user/signup" This endpoint is used to register a new user in the Quora Application.
  - signin - "/user/signin" This endpoint is used for user authentication. 
  - signout - "/user/signout" This endpoint is used to sign out from the Quora Application
  - userProfile - "/userprofile/{userId}" This endpoint is used to get the details of any user in the Quora Application
  - userDelete - "/admin/user/{userId}" This endpoint is used to delete a user from the Quora Application. Only an admin is authorized
  - createQuestion - "/question/create" This endpoint is used to create question for an logged in user
  - editQuestion - "/question/edit/{questionId}" This endpoint is used for editing a question by a logged in user
  - deleteQuestion - "/question/delete/{questionId}" This endpoint is used for deleting a question by a question owner or admin
  - getAllQuestionsByUser - "/all/{userId}" This endpoint is used all question by a user
  


You can also:
  - Alter a question in the Quora Application which will be shown to all the users. Any user can access this endpoint.
  - Fetch all the questions that have been posted in the application by any user
  - Fetch all the questions posed by a specific user.Any user can access this endpoint.
  - Create answer to question and fetch it all or in a specified way as per user.



> The overall goal of this project is to see the implementation of API Endpoints.


### Tech

Quora API uses a number of open source projects to work properly:

* [IntelliJ IDEA](https://www.jetbrains.com/idea/) or for development.
* [Java](https://www.java.com/en/download/)
* [Git](https://git-scm.com/downloads)


And of course Quora API itself is open source with a [public repository](https://github.com/BradPrit09/Quora-Demo/) on GitHub.

### Installation

This project  requires [Maven](https://maven.apache.org/)  v3.4+ to run and we need [postgresql.jar](https://jdbc.postgresql.org/download.html) driver which needs to be added to the dependency of the project.



```sh
 1.Import the project in Intellij idea using option "Checkout from Version Control"

 2.Select git as the option

 3.Use the URL https://github.com/BradPrit09/Quora-Demo to clone the repository on your local machine

 4.Once the project gets imported in you local workspace, you need to add the jar file postgresql in your classpath.

 5.right click on the postgresql jar file and select "Add to library"

 6.Then goto Application.yaml and for the Postgresql driver select suggesstion in red and select add to classpath

    This will add the file to classpath.

7.Goto file QuoraApiApplication, right click and run it as a Java application. 
```




### Development

Want to contribute? Great!
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands after changes are made from local repository.

First Tab:
```sh
$ git init
```

Second Tab:
```sh
$ git add .
```

 Third:
```sh
$ git commit -m "Message For Commit Done"
```
Fouth:
```sh
$ git push origin patch
```

### Todos

 - Write MORE Tests
 

License
----
Apache 2.0




**Free Software, Hell Yeah!**

