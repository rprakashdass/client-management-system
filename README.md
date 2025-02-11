# Client Management System

The Client Management System is a web-based application designed to streamline the management of client information and interactions. This system provides a user-friendly interface for efficiently handling client data, tracking project statuses, and maintaining comprehensive client records.

![Screenshot (4)](https://github.com/user-attachments/assets/96298f17-2d2b-44b8-8ebb-fae6f6526d33)

## Features

- **Client Information Management**: Add, edit, and delete client details, ensuring up-to-date records.
- **Project Tracking**: Monitor the status of client projects, categorizing them as 'In Progress' or 'Closed'.
- **User Authentication**: Secure login and registration for staff members to manage client data.
- **Recent Activities**: View a history of recent client interactions and updates.
- **Data Export**: Export client data to Excel for reporting and analysis.

## Installation

To set up the Client Management System locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rprakashdass/client-management-system.git
   cd client-management-system
   ```

2. **Set Up the Database**:
   - Create a MySQL database named `client_db`.
   - Import the provided `client_db.sql` file to set up the necessary tables:
     ```bash
     mysql -u your_username -p client_db < client_db.sql
     ```

3. **Configure the Application**:
   - Ensure your server environment supports PHP and MySQL.
   - Place the application files in your server's root directory (e.g., `htdocs` for XAMPP).

4. **Start the Application**:
   - Access the application through your web browser:
     ```
     http://localhost/client-management-system/
     ```

## Usage

- **Staff Registration**: Navigate to the registration page to create a new staff account.
- **Staff Login**: Use your credentials to log in and access the dashboard.
- **Dashboard**: View and manage client information, update project statuses, and export data as needed.

