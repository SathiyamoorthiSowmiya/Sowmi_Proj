HR Management System
Overview
This HR Management system is designed to manage various HR functions efficiently. The system has two main roles: Admin and Employee. The Admin side is responsible for managing events, leave requests, employees, and payroll (the payroll functionality is under development). The Employee side allows employees to manage their history, request leaves, update their details, and check events.

Features
Admin Side
Create and Delete Event: Admins can create new events and delete existing ones.
Accept or Reject Leave: Admins have the authority to accept or reject leave requests made by employees.
Add and Delete Employee: Admins can add new employees to the system and delete existing ones.
Add Payroll: This feature is under development and will allow admins to manage payroll for employees.

Employee Side
Add History: Employees can add personal history records.
Add Leave Request: Employees can submit leave requests which are then reviewed by the admin.
Update Details: Employees can update their personal details.
Check Events: Employees can view events created by the admin.
Installation
Backend (Node.js)
Navigate to the server directory:

cd server
Install dependencies:

npm install
Set up the database:

Configure your database settings in config/database.js.
Run migrations and seeders if necessary:
npx sequelize-cli db:migrate
npx sequelize-cli db:seed:all
Start the server:

npm start
Frontend (React)
Navigate to the client directory:

cd client
Install dependencies:

npm install
Configure environment variables:

Create a .env file in the root directory of your client project and add necessary environment variables, such as the API endpoint for your backend server.
Start the development server:

npm run dev
Getting Started
To get started with the application, follow the steps below:

1. Register an Admin Account
 you can register an admin account to access the administrative features of the application.

2.Register an Employee Account
You can register an employee account to access the employee portal and utilize features designed for managing your tasks, viewing schedules, and accessing work-related resources.

3. Access the Admin Dashboard
After registering the admin account, you can log in using the credentials you provided during registration. Once logged in, you will have access to the admin dashboard, where you can manage employees, training modules, and other administrative tasks.

4. Create Employee Accounts
From the admin dashboard, you can create employee accounts by providing the necessary details such as name, email, department, etc. These accounts will be used by employees to access their profiles and training modules.

5. Employee Login
Employees can log in to the system using the credentials provided by the admin. They can access their profiles, view assigned training modules, mark modules as completed, and perform other tasks related to their training.

Usage
Admin Interface
Login: Admins log in using their credentials.
Dashboard: Access the admin dashboard to manage the system.
Events Management:
Create Event: Fill in the event details and save.
Delete Event: Select an event to delete from the list.
Leave Management:
Review leave requests and either accept or reject them.
Employee Management:
Add Employee: Fill in the employee details and save.
Delete Employee: Select an employee to delete from the list.
Payroll Management: (Upcoming feature)
Will allow admins to add and manage payroll information (Still in progress).
Employee Interface
Login: Employees log in using their credentials.
Dashboard: Access the employee dashboard to manage personal information and requests.
History Management:
Add History: Fill in the history details and save.
Leave Requests:
Add Leave Request: Fill in the leave request details and submit.
Update Personal Details:
Update any personal details and save changes.
Events:
View the list of events created by the admin.

Demo credentials:
Email: demo.employee@example.com
Password: Demo@123
