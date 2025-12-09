# movie-mangement-syestem-
# Movie Management System

A full-stack movie management system built with **Node.js, Express, MongoDB** for the backend and **React, Vite, Tailwind CSS** for the frontend.  
Allows users to **add, edit, view, and list movies**. Supports file uploads and API-based operations.

---

## 🚀 Features

- Add new movies with details and poster images
- Edit existing movie information
- View detailed movie pages
- List all movies
- Backend: RESTful APIs with Node.js, Express, MongoDB
- Frontend: React with Vite, Tailwind CSS
- File uploads using Multer
- CORS enabled for cross-origin requests
- Axios for API communication

---

## 🛠️ Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose ODM
- Multer for file uploads
- CORS for cross-origin requests

### Frontend
- React with React Router
- Vite for fast development
- Tailwind CSS for styling
- Axios for API calls

---
movie-management-system/
├── backend/
│ ├── configs/
│ │ └── db.js
│ ├── controllers/
│ │ └── controllers.js
│ ├── middleware/
│ │ └── upload.js
│ ├── models/
│ │ └── movie.model.js
│ ├── router/
│ │ └── routes.js
│ ├── utils/
│ │ └── toArray.js
│ ├── uploads/
│ ├── app.js
│ ├── server.js
│ └── package.json
└── frontend/
├── src/
│ ├── components/
│ │ └── MovieForm.jsx
│ ├── pages/
│ │ ├── AddMoviePage.jsx
│ │ ├── EditMoviePage.jsx
│ │ ├── MovieDetailsPage.jsx
│ │ └── MovieList.jsx
│ ├── services/
│ │ └── api.js
│ ├── App.jsx
│ ├── index.css
│ └── main.jsx
├── index.html
├── package.json
└── vite.config.js

## 📁 Project Structure

