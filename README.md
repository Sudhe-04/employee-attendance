Sudheksha K

Kongu Engineering college

# ShiftLog - Employee Attendance System 🏢

A modern, full-stack employee attendance tracking system with role-based access control for Employees and Managers.

## 🚀 Features

### Employee Features
- ✅ Register/Login with JWT authentication
- ⏰ Check-in/Check-out with automatic status detection (Present/Late/Half-day)
- 📊 View personal attendance history with calendar view
- 📈 Monthly summary with statistics
- 🎯 Dashboard with real-time stats

### Manager Features
- 👥 View all employees' attendance
- 🔍 Filter by employee, date, and status
- 📅 Team calendar view
- 📄 Export attendance reports to CSV
- 📊 Comprehensive dashboard with charts and analytics

## 🛠️ Tech Stack

### Backend
- Node.js & Express.js
- MongoDB with Mongoose
- JWT Authentication
- bcryptjs for password hashing

### Frontend
- React 18
- Zustand for state management
- React Router v6
- Tailwind CSS
- Axios
- Recharts for data visualization
- Lucide React for icons

## 📁 Project Structure

```
employee-attendance/
├── client/                     # Frontend application
│   ├── public/                 # Public assets
│   └── src/                    # Source files
│       ├── components/          # Reusable components
│       ├── pages/               # Page components
│       ├── App.jsx              # Main app component
│       └── index.jsx            # Entry point
└── server/                     # Backend application
    ├── config/                 # Configuration files
    ├── controllers/            # Request handlers
    ├── middleware/             # Custom middleware
    ├── models/                 # Database models
    ├── routes/                 # API routes
    ├── .env                    # Environment variables
    ├── server.js               # Entry point
    └── package.json            # Backend dependencies
```

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- MongoDB (local or Atlas)
- Git

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/employee-attendance.git
   cd employee-attendance
   ```

2. Install dependencies

   For the client:

   ```bash
   cd client
   npm install
   ```

   For the server:

   ```bash
   cd server
   npm install
   ```

3. Set up environment variables

   Copy the example environment file and update the values:

   ```bash
   cd server
   cp .env.example .env
   ```

   Update the `.env` file with your MongoDB connection string and JWT secret.

4. Run the application

   For development (client and server):

   ```bash
   npm run dev
   ```

   For production (client and server):

   ```bash
   npm run build
   npm start
   ```

## Usage

- Access the application in your browser at `http://localhost:3000`
- Register a new account or log in with an existing account
- Employees can check in/out and view their attendance history
- Managers can view and manage all employees' attendance

## 🔐 Demo Credentials

### Manager Account
- Email: `manager@company.com`
- Password: `password123`

### Employee Accounts
- Email: `sudhe@company.com` | Password: `password123`
- Email: `hema@company.com` | Password: `password123`
- Email: `carol@company.com` | Password: `password123`
- Email: `david@company.com` | Password: `password123`

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch for your feature or bugfix
3. Make your changes and commit them
4. Push your branch and create a pull request

Please ensure your code follows the existing style and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
