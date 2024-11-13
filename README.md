## EventPlanner
Event Planner is a responsive system providing clients with customized event management packages for different occasions. It includes features such as payment processing, delivery status tracking, and additional functionalities. Developed using HTML, CSS, JS, JAVA, and MYSQL, it offers a seamless experience for both clients and organizers..

### Event Planner Website
### Introducation
The **Event Planner Website** provides a platform for the A.S.H. Events company to connect with clients, enabling them to plan and book event services efficiently. The system is divided into two main interfaces:
- **Customer Interface**: Users can book venues, catering, and multimedia services through either pre-defined or customized packages.
- **Employee Interface**: Employees can manage records, process orders, and work with vendors digitally.
This platform digitalizes the firm's operations, streamlining the planning process and enhancing efficiency.

### Project Summary
**Project Title**: Event Planner Website  
**Project Type**: Web Application  
**Frontend**: HTML, CSS, JavaScript  
**Backend**: Java  
**Database**: MySQL  

### Features
- **Admin Features**:
  - Manage and oversee employee and customer records.
  - Track orders, payments, and vendor management.

- **Employee Features**:
  - Manage event details, customer information, and vendor assignments.
  - Process orders and update order statuses.

- **Customer Features**:
  - Browse and book event services (venue, catering, multimedia).
  - Customize or choose from pre-defined event packages.
  - Track order status and manage payments.

### Installation
1. **Prerequisites**:
   - Install MySQL for database management.
   - Install a compatible Java Development Kit (JDK).
   - Ensure an appropriate IDE (e.g., Eclipse) is installed if needed for editing and running Java files.

2. **Database Setup**:
   - Import `EventPlannerDB.sql` from the `/db` folder to set up the database in MySQL.

3. **Configuration**:
   - Configure database connection settings in the application files (update MySQL credentials as needed).

4. **Running the Application**:
   - Compile and run the Java files in your IDE or from the command line.
   - Access the application through the local server setup in your environment.

### Usage
1. **Admin Login**:
   - Admins can access all sections to manage customers, employees, and oversee events.

2. **Employee Login**:
   - Employees can log in to manage event details, track orders, and handle customer queries.

3. **Customer Login**:
   - Customers can browse available packages, book services, customize orders, and track event status.

### Project Structure
Event-Planner-Website/ ├── src/ │ ├── pages/ │ │ ├── Home.html │ │ ├── Login.html │ │ ├── ... │ ├── backend/ │ │ ├── EventPlanner.java │ │ └── ... │ └── ... ├── db/ │ └── EventPlannerDB.sql ├── assets/ │ ├── css/ │ ├── images/ │ └── ... ├── docs/ │ ├── UseCaseDiagram.pdf │ ├── ClassDiagram.pdf │ └── ERDiagram.pdf ├── tests/ │ └── UnitTests.java ├── README.md └── LICENSE


### Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Java
- **Database**: MySQL
- **Development Environment**: Windows 10, IDE (e.g., Eclipse)

### Database Schema
The database includes tables such as:
- **Admin**: Stores administrator credentials and personal details.
- **Customer**: Holds customer information and event preferences.
- **Decoration**: Includes decoration types and budgets.
- **Order**: Tracks each booking and associated services.
- **Payment**: Stores payment details and statuses.

For detailed database structure, refer to the `/docs/ERDiagram.pdf` file.

### Screenshots
Provide screenshots for key parts of the application:
- **Home Page**: Main page for login and service navigation.
- **Customer Dashboard**: Booking options and order tracking.
- **Employee Dashboard**: Manage events, customers, and orders.
- **Admin Dashboard**: Full system overview.

### Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push the branch (`git push origin feature-branch`).
5. Open a Pull Request.

### License
This project is licensed under the MIT License.
