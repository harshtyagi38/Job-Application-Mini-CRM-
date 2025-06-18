📌 Job Application Tracker (Mini CRM)
🎯 Objective
A lightweight CRM-style system that helps users efficiently track and manage their job applications. This app supports core features like job tracking, filtering, real-time notifications, and user authentication, offering both applicants and admins the tools to stay organized during the job hunt.

🧩 Core Features
🔐 User Authentication
Secure login/signup using JWT.

Two user roles:

Applicant Panel – Manage personal job applications.

Admin Panel (optional) – View and manage all user data (admin privileges).

📝 Job Entry CRUD
Create and manage job applications with the following fields:

Company, Role, Status, Applied Date, Notes

Application status options:

Applied, Interview, Offer, Rejected, Accepted

Full CRUD support:

Add, edit, delete, and view application details.

📋 List View with Filters
View all job applications in a list or card format.

Filter applications by status.

Sort applications by applied date.

🛠 Backend
RESTful API for all core operations (built with Node.js/Express or similar).

Database support:

PostgreSQL or MongoDB for storing application data.

💻 Frontend
Responsive user interface with a clean and intuitive design.

Job entry forms with input validation (required fields, date formats, etc.).

Displays job applications using cards or tables for easy readability.

🔔 Real-Time Notifications
Get notified in real-time (email or in-app panel) on job status changes or updates.

🚀 Getting Started
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/job-application-tracker.git
cd job-application-tracker
Install backend dependencies:

bash
Copy
Edit
cd backend
npm install
Configure .env for backend (DB credentials, JWT secret, etc.).

Install frontend dependencies:

bash
Copy
Edit
cd frontend
npm install
Run both servers:

bash
Copy
Edit
# Backend
npm run dev

# Frontend (in a new terminal)
npm start
🔧 Tech Stack
Frontend: React / Vue / Angular (choose one)

Backend: Node.js + Express

Database: PostgreSQL or MongoDB

Authentication: JWT

Notifications: Nodemailer / Socket.io (for real-time features)

✅ Future Improvements
Admin analytics dashboard

Export job application data

Job reminder notifications

OAuth (Google/LinkedIn) login support
