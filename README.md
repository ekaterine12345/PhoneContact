# PhoneContact

**PhoneContact** is a Java-based project that provides basic CRUD (Create, Read, Update, Delete) functionality for managing user contact information. 
The project utilizes the Java Persistence API (JPA) for database operations and includes methods for saving, updating, deleting, and retrieving user records.

## Features

- **Add a User**: Save new user contact information to the database.
- **Update a User**: Modify existing user contact details.
- **Delete a User**: Remove a user record from the database.
- **Retrieve All Users**: Fetch all user records from the database.
- **Find User by ID**: Get specific user details using their unique ID.

## Technologies Used

- **Java 8+**
- **Java Persistence API (JPA)**
- **Relational Database** (configured via `persistence.xml`)
- **Maven** (optional, for dependency management)

## Prerequisites

- A configured relational database.
- Proper JPA configuration in the `persistence.xml` file with a persistence unit named `test_jdbc`.
