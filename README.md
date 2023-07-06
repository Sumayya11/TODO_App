# TODO_App

This is a simple Todo application built using Flask framework and following the 3-tier architecture pattern. The application allows users to create, view, update, and delete their todo items.

## ARCHITECTURE
The application follows a 3-tier architecture pattern, separating the concerns into three layers: presentation, application, and data.

## 1) Presentation Layer:
This layer handles the user interface and user interactions. It consists of the Flask web framework, HTML templates, and CSS stylesheets. Users can interact with the application through their web browsers.
## 2) Application Layer:
This layer contains the business logic and application-specific rules. It is responsible for processing user requests, performing validations, and managing data flow between the presentation and data layers. The Flask framework handles the routing and request handling, while the application layer handles the logic.
## 3) Data Layer: 
This layer deals with data storage and retrieval. In this application, SQLite is used as the database system. The data layer interacts with the database through the use of an ORM (Object-Relational Mapping) library, such as SQLAlchemy.

## Prerequisites
   - Python 3.x installed
   - Flask framework
   - SQLAlchemy library

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please create an issue or submit a pull request.
