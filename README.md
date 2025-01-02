# HR Management System Overview

This HR Management system is designed to manage various HR functions efficiently. The system has two main roles: **Admin** and **Employee**.  

- **Admin Role**: Responsible for managing events, leave requests, employees, and payroll (under development).  
- **Employee Role**: Enables employees to manage their history, request leaves, update details, and check events.

---

## Features

### Admin Side  
- **Create and Delete Event**: Admins can create new events and delete existing ones.  
- **Accept or Reject Leave**: Admins can accept or reject leave requests made by employees.  
- **Add and Delete Employee**: Admins can add new employees to the system and delete existing ones.  
- **Add Payroll**: *(Under Development)* Manage payroll for employees.  

### Employee Side  
- **Add History**: Employees can add personal history records.  
- **Add Leave Request**: Employees can submit leave requests for admin review.  
- **Update Details**: Employees can update their personal details.  
- **Check Events**: Employees can view events created by the admin.

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
