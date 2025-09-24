# Solvio – Job Finder

Solvio is a modern job discovery platform designed to simplify the hiring process for both job seekers and employers. With a user-friendly interface, smart search features, and advanced filtering options, Solvio helps candidates find jobs that match their skills and career goals — while providing employers with tools to post jobs, manage applicants, and hire efficiently.

---

## Features

-  **Job Search & Filter:** Find jobs by role, location, skills, and salary.  
-  **Role-based Authentication:** Secure login for job seekers and recruiters.  
-  **Employer Dashboard:** Manage job postings, view applicants, and shortlist candidates.  
-  **Cloud Integration:** Secure file storage for resumes and documents using Cloudinary.  

---

## 🛠️ Tech Stack

### Frontend:
- React.js  
- Tailwind CSS  
- Axios  

### Backend:
- Node.js / Express.js  
- MongoDB (via Mongoose)  
- REST APIs  

### Additional Tools:
- Git & GitHub  
- Cloudinary  
- JWT Authentication  

---

## 📁 Project Structure
├── backend/ # Express backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── services/
│ └── server.js
├── frontend/ # React frontend
├── .gitignore
├── README.md
└── package.json


## Environment Variables

Before running the project, create a `.env` file inside the `backend/` directory with the following variables:

```env
PORT=
JWT_SECRET=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
DATABASE_CONNECTION_URL=
