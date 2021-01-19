# tasks

Simple app to manage your daily tasks.

## Libraries used
- Spring Boot 2.4.1 - IoC and DI
- Gradle 6.7.1 - dependency management
- Lombok 1.18.16 - simplifying code
- mysql-connector-java 8.0.22 - connection to MySQL db

## Features
CRUD operations (HTTP requests):
- GET getTasks - returns collection of all tasks
- GET getTask - returns single task pointed with parameter id
- POST createTasks - adds task to db, id is incremented automatically, body must be passed in JSON
- PUT updateTask - overwrites pointed task with data passed in body
- DELETE deleteTask - deletes task pointed with parameter id

## Future of project
I'm planning to develop this app according to Kanban system. 
Tasks will be divided in three sections: "To do, "In progress" and "Done".
User will be able to change the status of each task. 
