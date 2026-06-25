# Employee Management System (EMS)

A React-based Employee Management System that allows Admins and Employees to manage and track tasks efficiently.

##  Features

### Admin Features
- Admin Dashboard
- Create New Tasks
- Assign Tasks to Employees
- View All Tasks
- Track Task Status

### Employee Features
- Employee Dashboard
- Accept Assigned Tasks
- Complete Tasks
- Mark Tasks as Failed
- View Task Details

##  Project Structure

```
ems-main
│
├── public
├── src
│   ├── assets
│   ├── components
│   │   ├── Auth
│   │   ├── Dashboard
│   │   │   ├── AdminDashboard.jsx
│   │   │   └── EmployeeDashboard.jsx
│   │   ├── other
│   │   │   ├── AllTask.jsx
│   │   │   ├── CreateTask.jsx
│   │   │   ├── Header.jsx
│   │   │   └── TaskListNumbers.jsx
│   │   └── TaskList
│   │       ├── AcceptTask.jsx
│   │       ├── CompleteTask.jsx
│   │       └── FailedTask.jsx
│   └── App.jsx
│
├── package.json
└── README.md
```

##  Tech Stack

- React.js
- JavaScript (ES6+)
- HTML5
- CSS3
- Vite / React Build Tools

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/ems-main.git
```

2. Navigate to the project directory

```bash
cd ems-main
```

3. Install dependencies

```bash
npm install
```

4. Start the development server

```bash
npm run dev
```

5. Open your browser and visit

```text
http://localhost:5173
```

##  Login Roles

### Admin
- Create and assign tasks
- Monitor employee performance
- View task statistics

### Employee
- View assigned tasks
- Accept tasks
- Complete tasks
- Update task status

## 📸 Screenshots

Add screenshots of:
- Login Page
- Admin Dashboard
- Employee Dashboard
- Task Management Page

##  Future Improvements

- Backend Integration
- Database Support
- Authentication with JWT
- Real-time Notifications
- Task Deadlines & Reminders
- Dark Mode

##  Contributing

Contributions are welcome. Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

---

Made with ❤️ using React.js
