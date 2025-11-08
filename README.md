# Super-Messenger-Social-Media-App

This project is a social media application with messaging capabilities, developed in Java.

## Key Features & Benefits

*   **User Accounts:** Users can create and manage their profiles.
*   **Messaging:** Real-time communication between users.
*   **Profile Customization:** Users can set their username, password, and bio.
*   **Database Integration:** Persistent storage of user data and messages.

## Prerequisites & Dependencies

*   **Java Development Kit (JDK):** Ensure you have a compatible JDK installed (e.g., JDK 8 or later).
*   **Integrated Development Environment (IDE):** (Recommended) An IDE like IntelliJ IDEA or Eclipse for development and debugging.
*   **Database:** A database system (potentially for future implementation depending on the Database.java file content.  Assuming an SQL database for example: MySQL, PostgreSQL, etc.)

## Installation & Setup Instructions

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/Aryan-Rakshit/Super-Messenger-Social-Media-App-.git
    cd Super-Messenger-Social-Media-App-
    ```

2.  **Import Project into IDE:**

    *   Open your chosen IDE.
    *   Import the project as an existing Java project (e.g., from existing sources in IntelliJ IDEA).
    *   Ensure all the source files are recognized correctly.

3.  **Database Setup (If Applicable):**

    *   If a database system is used, install and configure your chosen database server (e.g., MySQL).
    *   Create a database schema for the application.
    *   Update the `Database.java` file with the correct database connection details (URL, username, password).  This step depends on the actual database implementation in that file.

4.  **Build the Project:**

    *   Use your IDE to build the project.  This compiles the Java source files into class files.

5.  **Run the Server:**

    *   Execute the `Server.java` file to start the server component of the application.
    *   Note the server's IP address and port number (likely configured within `Server.java`).

6.  **Run the Client:**

    *   Execute the `Client.java` file to start a client instance.
    *   Provide the server's IP address and port number when prompted.
    *   You can run multiple client instances to simulate different users.

## Usage Examples & API Documentation

The project consists of several key classes. Here's a summary of some of the prominent classes and their methods, based on the provided `README.md` content:

### User

Represents a user in the social media application.

*   `String getUsername();`: Returns the username of the user.
*   `String getPassword();`: Returns the password of the user.
*   `String getBio();`: Returns the user's bio information.
*   `int getUniqueID();`: Returns the unique ID of the user.
*   `void setUsername(String username);`: Sets the username of the user.
*   `void setPassword(String password);`: Sets the password of the user.
    *   `...` (The original README truncated this)

### Chat 

### Message

###  Database  

### Interfaces and other information
Classes like IClient, IServer, IChat, IMessage, IUser, and IUserDatabase represent Interfaces which define behavior.

*   **Server Port:**  The server's port number can be configured in the `Server.java` file.
*   **Database Connection:** The database connection details (URL, username, password) are configured in the `Database.java` file (If implemented).

## Contributing Guidelines

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Implement your changes.
4.  Write unit tests for your code.
5.  Commit your changes with descriptive commit messages.
6.  Push your branch to your forked repository.
7.  Submit a pull request.

## License Information

License not specified. All rights reserved unless otherwise stated.
