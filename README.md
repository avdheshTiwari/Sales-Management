# Sales Management System

This is a **Sales Management System** built using **Java, JSP, and Servlets** for the back-end, and **HTML, CSS, and Bootstrap** for the front-end. The system allows businesses to efficiently manage their sales processes, including product management, customer management, and sales tracking.

### Features:
- **Product Management:** Add, edit, and delete products from the inventory.
- **Customer Management:** Manage customer details and track purchase histories.
- **Sales Tracking:** Monitor and record sales transactions.
- **User Authentication:** Secure login and registration for sales staff.
- **Responsive Design:** Front-end built using Bootstrap for a mobile-friendly experience.
  
### Technologies Used:
- **Java, JSP, Servlets:** For back-end development and business logic.
- **HTML, CSS, Bootstrap:** For designing the user interface.
- **SQL:** For database management and storage.
- **Apache Tomcat:** As the web server.

### Required JAR Files:
- **MySQL Connector JAR:** For connecting the application to the MySQL database.
  - [Download Link](https://dev.mysql.com/downloads/connector/j/)
- **Servlet API JAR:** To handle HTTP requests and responses.
  - This is typically included in the **Apache Tomcat** server, but if you need it separately, you can add it from [Maven Central](https://mvnrepository.com/artifact/javax.servlet/servlet-api).
- **JSTL JAR:** For JSP tag libraries to handle dynamic content.
  - [Download Link](https://mvnrepository.com/artifact/javax.servlet/jstl)

### How to Run:
1. Clone the repository.
2. Set up the database using the provided SQL scripts.
3. Add the required JAR files (e.g., **mysql-connector.jar**, **servlet-api.jar**, **jstl.jar**) to the `lib` folder or set up Maven dependencies if you're using Maven.
4. Configure the project in your favorite IDE (Eclipse, IntelliJ) and deploy on Apache Tomcat.
5. Access the web application from your browser.

### Future Enhancements:
- Integration of analytics for sales reporting.
- Role-based access control for different levels of users.
- API integration for third-party services.



