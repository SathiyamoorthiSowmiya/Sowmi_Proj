# HR Management System Overview

This HR Management system is designed to manage various HR functions efficiently. The system has two main roles: **Admin** and **Employee**.  

- **Admin Role**: Responsible for managing events, leave requests, employees, and payroll (under development).  
- **Employee Role**: Enables employees to manage their history, request leaves, update details, and check events.

## Live Demo

- **Frontend deployed with Netlify**: [https://hrmsphere.netlify.app/](https://hrmsphere.netlify.app/)  
- **Backend deployed with Render.com**: [https://sowmi-proj.onrender.com/](https://sowmi-proj.onrender.com/)
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

- # HR Management System Overview

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
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Set up the database:  
   - Configure your database settings in `config/database.js`.  
   - Run migrations and seeders if necessary:  
     ```bash
     npx sequelize-cli db:migrate  
     npx sequelize-cli db:seed:all
     ```  
4. Start the server:  
   ```bash
   npm start
   ```  

### Frontend (React)  
1. Navigate to the client directory:  
   ```bash
   cd client
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Configure environment variables:  
   - Create a `.env` file in the root directory of your client project and add necessary environment variables (e.g., API endpoint for the backend).  
4. Start the development server:  
   ```bash
   npm run dev
   ```  

---

## Getting Started

1. **Register an Admin Account**:  
   Register an admin account to access the administrative features of the application.  

2. **Register an Employee Account**:  
   Register an employee account to access the employee portal and utilize features designed for managing tasks, viewing schedules, and accessing work-related resources.  

---

## Usage

### Admin Interface  
- **Login**: Admins log in using their credentials.  
- **Dashboard**: Access the admin dashboard to manage the system.  
- **Events Management**:  
  - Create Event: Fill in the event details and save.  
  - Delete Event: Select an event to delete from the list.  
- **Leave Management**:  
  - Review leave requests and either accept or reject them.  
- **Employee Management**:  
  - Add Employee: Fill in the employee details and save.  
  - Delete Employee: Select an employee to delete from the list.  
- **Payroll Management**: *(Upcoming Feature)* Will allow admins to add and manage payroll information.  

### Employee Interface  
- **Login**: Employees log in using their credentials.  
- **Dashboard**: Access the employee dashboard to manage personal information and requests.  
- **History Management**:  
  - Add History: Fill in the history details and save.  
- **Leave Requests**:  
  - Add Leave Request: Fill in the leave request details and submit.  
- **Update Personal Details**: Update any personal details and save changes.  
- **Events**: View the list of events created by the admin.  

---

## Demo Credentials

Use the following demo credentials to explore the application:  
  Admin side
- **Email**:  user87@gmail.com, test03@gmail.com
- **Password**:098765, test03

  Employee side
  - **Email**: user78@gmail.com, test30@gmail.com
- **Password**: 123456, test30
  



