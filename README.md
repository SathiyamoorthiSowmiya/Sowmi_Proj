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

---

## Installation

### Backend (Node.js)  
1. Navigate to the server directory:  
   ```bash
   cd server
2.Install dependencies:
npm install
3.Set up the database:
Configure your database settings in config/database.js.

Run migrations and seeders if necessary:
npx sequelize-cli db:migrate  
npx sequelize-cli db:seed:all

4.Start the server:
npm start

Frontend (React)
1.Navigate to the client directory
cd client
2.Install dependencies
npm install
3.Configure environment variables:
Create a .env file in the root directory of your client project and add necessary environment variables (e.g., API endpoint for the backend).
4.Start the development server
npm run dev



