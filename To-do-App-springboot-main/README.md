# Todo Spring Boot Application
![image](https://github.com/user-attachments/assets/fbcb50f1-a2c4-43a8-9b07-18bd7a3910a3)

This is a simple Todo application built using Spring Boot. It allows users to manage a list of todo items with features like creating, updating, viewing, and deleting tasks. The application uses a MySQL database for persistent storage.

## Features

- Create a new todo item
- View all todo items
- Update an existing todo item
- Delete a todo item

## Technologies Used

- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- MySQL
- JSP

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven
- MySQL

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/todo-springboot.git
   cd todo-springboot


src
├── main
│   ├── java
│   │   └── com
│   │       └── example
│   │           └── todo
│   │               ├── controller
│   │               │   └── TodoController.java
│   │               ├── model
│   │               │   └── Todo.java
│   │               ├── repository
│   │               │   └── TodoRepository.java
│   │               └── TodoApplication.java
│   ├── resources
│   │   ├── static
│   │   ├── templates
│   │   └── application.properties
│   └── webapp
│       └── WEB-INF
│           └── jsp
│               ├── index.jsp
│               ├── create.jsp
│               └── edit.jsp
└── test
    └── java
        └── com
            └── example
                └── todo
                    └── TodoApplicationTests.java




