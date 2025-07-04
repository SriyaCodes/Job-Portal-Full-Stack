# 💼 Job Portal - Fullstack Web Application

A modern fullstack Job Portal where employers can post jobs and candidates can browse, apply, and track applications. This project uses **Clerk** for authentication, **Cloudinary** for media storage, and **MongoDB** as the database.

## 🌐 Live Demo

🚀 **Frontend:** [https://job-portal-full-stack-client-rho.vercel.app](https://job-portal-full-stack-client-rho.vercel.app)  
🛠 **Backend API:** [https://job-portal-full-stack-server-lac.vercel.app/](https://job-portal-full-stack-server-lac.vercel.app/)  

## 🚀 Features

- 🔐 Clerk Authentication
  - Secure login/signup with Clerk (Email/Password, Social Logins)
  - User roles (Employer / Job Seeker)
- 🧑‍💼 Employer Tools
  - Post, edit, delete jobs
  - Upload company logo via Cloudinary
  - View applicants for each job
- 👩‍💻 Candidate Tools
  - Search and filter jobs by category, location, level
  - Apply to jobs and upload resume
  - Track application history
- 🔔 Webhooks
  - Handle Clerk events (user created, deleted, etc.)
  - Optional: Cloudinary upload hooks (e.g., processing complete)
- 🖼️ Cloudinary Integration
  - Upload and manage images (logos, resumes, etc.)
- 🌍 Responsive UI for desktop and mobile


## 🛠️ Tech Stack

### Frontend:
- React.js (with Vite or Create React App)
- Clerk React SDK
- Tailwind CSS 

### Backend:
- Node.js
- Express.js
- MongoDB with Mongoose
- Clerk Webhooks 
- Cloudinary 

