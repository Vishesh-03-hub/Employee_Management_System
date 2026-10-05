# Employee Management System 

A responsive Employee Management System built with **React.js, JavaScript, Tailwind CSS, and Vite**. The application provides separate Admin and Employee dashboards with authentication, task assignment, task tracking, and role-based functionality.

## 🚀 Features

* 🔐 **Role-Based Authentication** – Separate access for Admin and Employee users.
* 👨‍💼 **Admin Dashboard** – Manage employees and monitor task progress.
* 👨‍💻 **Employee Dashboard** – View assigned tasks and track task status.
* 📋 **Task Management** – Create, assign, and manage employee tasks.
* 📊 **Task Statistics** – Display task counts based on their current status.
* 💾 **Persistent Login** – Maintains login sessions using browser Local Storage.
* ⚛️ **Reusable Components** – Modular React components for improved maintainability.
* 📱 **Responsive UI** – Styled using Tailwind CSS for responsive layouts.

## 🛠️ Tech Stack

| Technology        | Usage                              |
| ----------------- | ---------------------------------- |
| React.js          | Frontend UI development            |
| JavaScript        | Application logic                  |
| Tailwind CSS      | Styling and responsive design      |
| Vite              | Development and build tooling      |
| React Context API | Global state management            |
| Local Storage     | Authentication/session persistence |
| Git & GitHub      | Version control                    |

## 🏗️ Application Structure

```text
Employee_Management_System/
│
├── public/
├── src/
│   ├── components/
│   │   ├── AdminDashboard/
│   │   ├── EmployeeDashboard/
│   │   ├── other/
│   │   └── TaskList/
│   │
│   ├── context/
│   │   └── AuthProvider.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## 🔑 Authentication

The application supports two user roles:

### Admin

* Login as an administrator
* Access the Admin Dashboard
* Create and assign tasks
* Monitor employee task statistics

### Employee

* Login as an employee
* Access the Employee Dashboard
* View assigned tasks
* Track task status

Authentication state is managed using **React Context API**, while Local Storage is used to persist user session data across page reloads.

## 📋 Task Management

Administrators can create tasks by providing information such as:

* Task title
* Task description
* Due date
* Assigned employee
* Task category

Employees can then view their assigned tasks and track their progress through different task statuses.

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Vishesh-03-hub/Employee_Management_System.git
```

### 2. Navigate to the project

```bash
cd Employee_Management_System
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

### 5. Open the application

Vite will provide a local development URL, typically:

```text
http://localhost:5173
```

## 📸 Application Workflow

```text
                ┌─────────────────┐
                │     Login       │
                └────────┬────────┘
                         │
              ┌──────────┴──────────┐
              │                     │
          Admin Login          Employee Login
              │                     │
              ▼                     ▼
      ┌───────────────┐      ┌───────────────┐
      │ Admin         │      │ Employee      │
      │ Dashboard     │      │ Dashboard     │
      └───────┬───────┘      └───────┬───────┘
              │                       │
              ▼                       ▼
       Create & Assign           View Tasks
           Tasks                     │
              │                       ▼
              └──────────────► Track Status
```

## 🎯 Project Highlights

* Component-based architecture using React.js
* Centralized authentication state with Context API
* Role-based dashboard rendering
* Persistent authentication using Local Storage
* Responsive interface using Tailwind CSS
* Task creation and employee assignment workflow
* Reusable and maintainable React components

## 🔮 Future Improvements

* Backend integration with Spring Boot
* MySQL/MongoDB database integration
* JWT-based authentication
* REST API integration
* Employee CRUD operations
* Task editing and deletion
* Deployment using Vercel or Netlify
* Automated testing

## 👨‍💻 Author

**Vishesh Gupta**

B.Tech – Artificial Intelligence & Data Science

GitHub: [Vishesh-03-hub](https://github.com/Vishesh-03-hub)

## 📄 License

This project is intended for educational and portfolio purposes.
