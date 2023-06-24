# Java-User-Auth
User Authentication in Java using JSP, Servlet and MySQL

# User Authentication Project

This project implements a user authentication system using JSP, Servlets, MySQL, and MySQL Connector. It provides a simple web application that allows users to register, login, and access protected resources.

## Technologies Used

- Java
- JSP (JavaServer Pages)
- Servlets
- MySQL
- MySQL Connector
- Eclipse IDE
- Apache Tomcat v10.1.0 Server

## Prerequisites

Before running the project, ensure that you have the following software installed on your system:

- Java Development Kit (JDK)
- Eclipse IDE (or any other Java IDE)
- Apache Tomcat Server

## Project Setup

1. Clone or download the project to your local machine.
2. Open Eclipse IDE.
3. Select **File -> Open Projects from File System**.
4. Browse and select the project directory.
5. Click **Finish** to import the project into Eclipse.
6. Configure Apache Tomcat Server in Eclipse:
   - Open the **Servers** view in Eclipse (Window -> Show View -> Servers).
   - Right-click in the Servers view and select **New -> Server**.
   - Choose the installed Apache Tomcat v10.1.0 Server from the list.
   - Click **Next** and browse to the Tomcat installation directory.
   - Click **Finish** to add the server to Eclipse.
7. Set up the MySQL database:
   - Install and configure MySQL on your machine if not already done.
   - Create a new database for the project.
   - Update the database connection details in the `src/com/auth/UserDao.java` & in `src/com/auth/LoginDao.java` file with your MySQL credentials and database name.
8. Build the project:
   - Clean and build the project to resolve any dependencies.
   - Make sure there are no compilation errors in the project.
9. Deploy the project to Tomcat Server:
   - Right-click on the project in Eclipse and select **Run As -> Run on Server**.
   - Choose the configured Tomcat Server and click **Finish**.
   - The project will be deployed to the Tomcat Server.
10. Access the application:
    - Open a web browser.
    - Enter the URL `(http://localhost:8082/UserAuth/index.jsp)` to access the application.
    - You should see the home page of the user authentication system.
    
## Usage

- Register a new user:
  - Click on the **Register** link on the home page.
  - Fill in the registration form with the required details.
  - Click **Submit** to register a new user.
- Login as a registered user:
  - Enter the registered username and password on the login page.
  - Click **Login** to authenticate the user.
- Access protected resources:
  - After successful login, you will be redirected to the protected resources page.
  - You can access the protected resources as an authenticated user.
- Logout:
  - Click on the **Logout** link to log out of the application.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

