# Jabber Backend

This project is the backend for the Jabber social media application. It is implemented in Java and provides the necessary features to support user management, message posting, and liking messages.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [License](#license)


## Features

- User registration and authentication
- Create, read, update, and delete messages
- Like and unlike messages

## Requirements

- Java 8 or higher
- A database (e.g., MySQL, PostgreSQL)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/jabber-backend.git
    cd jabber-backend
    ```

2. **Set up the database:**
   - Create a database and configure the connection in `src/JabberDatabase.java`.

3. **Compile the project:**
    ```bash
    javac -d bin src/**/*.java
    ```

4. **Run the application:**
    ```bash
    java -cp bin Server
    ```

## License

This project is licensed under the MIT License.

---

Thank you for checking out the Jabber Backend project!
