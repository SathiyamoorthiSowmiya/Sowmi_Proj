# 🌐 HR Management System 

This HR Management system is designed to manage various HR functions efficiently. The system has two main roles: **Admin** and **Employee**.  

- 👩‍💼 **Admin Role**: Responsible for managing events, leave requests, employees, and payroll .  
- 👨‍💻 **Employee Role**: Enables employees to manage their history, request leaves, update details, and check events.

## 🚀 Live Demo

- **Frontend deployed with Netlify**: ()  
- **Backend deployed with Render.com**: ()


## ✨ Features

### 👩‍💼 Admin Side  

- 📅 **Create and Delete Event**: Admins can create new events and delete existing ones.  
- ✅❌**Accept or Reject Leave**: Admins can accept or reject leave requests made by employees.  
- 👥 **Add and Delete Employee**: Admins can add new employees to the system and delete existing ones.  
- 💰 **Add Payroll**: Manage payroll for employees.  

### 👩‍💼 Employee Side

- 📜 **Add History**: Employees can add personal history records.
- 📝**Add Leave Request**: Employees can submit leave requests for admin review.
-  ✏️ **Update Details**: Employees can update their personal details.
-  📆 **Check Events**: Employees can view events created by the admin.
 
## 📥 Installation

### 📦 Backend (Node.js)  
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

### 🖥️ Frontend (React)  
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

## 🚀 Getting Started

1. 📧 **Register an Admin Account**:
   
    Register an admin account to access the administrative features of the application.  

2. **👥Register an Employee Account**:
   
   Register an employee account to access the employee portal and utilize features designed for managing tasks, viewing schedules, and accessing work-related resources.  


## ⚡ Usage

### Admin Interface  
- 🔐 **Login**: Admins log in using their credentials.  
- 📊 **Dashboard**: Access the admin dashboard to manage the system.  
- ** 📅 Events Management**:  
  - Create Event: Fill in the event details and save.  
  -  Delete Event: Select an event to delete from the list.  
- **📝Leave Management**:  
  - Review leave requests and either ✅ accept or ❌ reject them.  
- **👥Employee Management**:  
  - Add Employee: Fill in the employee details and save.
  - Delete Employee: Select an employee to delete from the list.
    
- **💰Payroll Management**:
     - Will allow admins to add and manage payroll information.  

### 👩‍💻 Employee Interface  
- **🔐Login**: Employees log in using their credentials.  
- **📊Dashboard**: Access the employee dashboard to manage personal information and requests.
  
- **History Management**: Add History: Fill in the history details and save.  
- **📝Leave Requests**: Add Leave Request: Fill in the leave request details and submit.  
- **✏️Update Personal Details**: Update any personal details and save changes.  
- **📆Events**: View the list of events created by the admin.  


## 📧 Demo Credentials

Use the following demo credentials to explore the application: 

  👩‍💼 Admin side
- **📩Email**:  user87@gmail.com, test03@gmail.com
- **🔑Password**:098765, test03

 👩‍💻 Employee side
  - **📩Email**: user78@gmail.com, test30@gmail.com
- **🔑Password**: 123456, test30

- 2️⃣ Backend Setup (Node + Express)

   Go to backend folder:

   cd backend

  Install dependencies:

  npm install

  Start the backend server:

  # For development (with nodemon)
  npm run dev

  # or normal run
  npm start

  3️⃣ Frontend Setup (React + Vite)

  Go to frontend folder:

  cd frontend
  
 Install dependencies:

 npm install

 Start the frontend dev server:

 npm run dev

 🚀 Getting Started (Flow)
1️⃣ Register User

Open frontend in browser: http://localhost:5173

Go to Register page.

Create a User account by choosing role = user.

Login using that account.

You will be redirected to User Dashboard.

2️⃣ Place Order as User

From dashboard click “Place Order”.

Choose dishes (use + / - to set quantity).

Enter Delivery Address.

Check order summary (Subtotal + GST + Delivery).

Click Place Order.

You will see a success toast → “Admin will review”.

You can view your own orders under “My Orders” page.

3️⃣ Create Admin User

You can create an admin in two ways:

Option A – From frontend Register

Open Register page.

Choose role = admin.

Login with that account at /admin/login (if you created separate route)
or normal login and get redirected to admin dashboard according to role.

Option B – Using Postman / MongoDB directly

Insert a user document with role: "admin" in users collection.

4️⃣ Use Admin Panel

Login as Admin.

You’ll see Admin Dashboard:

Total orders

Pending

Delivered

Dark mode toggle

Click “View All Orders” → /admin/orders

In Admin Orders page:

View all user orders list.

Search by user name / email.

Filter by status (pending / accepted / on-the-way / delivered / rejected).

Click an order card → popup modal shows:

User

Address

Items + quantity + price

Total amount

Status update buttons:

From pending:

✅ Approve → changes to accepted

❌ Reject → changes to rejected

From accepted:

🚚 Mark On-the-way

From on-the-way:

📦 Mark Delivered

⚡ Usage Summary
🧑‍🍳 User Interface

🔐 Login / Register

📊 Dashboard with greeting + dark toggle

🍽️ Place Order page:

Static menu with images, desc, price, veg/non-veg

Veg / Non-veg filter

Quantity controls

Automatic total calculation

📜 My Orders:

List of your orders with current status

👩‍💼 Admin Interface

🔐 Admin Login

📊 Admin Dashboard (stats + dark UI)

🧾 Orders List with search + filter

🪟 Order detail modal

✅ Status updates for each order

📧 Demo Credentials (Example – change to your real values)

After you create these users in your DB, mention them here.

👨‍💻 User

Email: user@test.com
Password: 123456


👩‍💼 Admin

Email: admin@test.com
Password: 123456

🛡️ Security

Passwords stored as hashed using bcryptjs.

Auth handled using JWT tokens.

Role-based access:

Only admin can access admin routes.

Normal users cannot hit admin protected APIs.

🎯 Future Enhancements

✅ Dynamic products from database (Admin can add/edit dishes)

✅ Coupon / discount support

✅ Online payment gateway integration

✅ Real-time tracking (map integration)

✅ Notifications (email / SMS) on order updates

👨‍💻 Developer

Sowmiya S
MERN Stack Developer
  



