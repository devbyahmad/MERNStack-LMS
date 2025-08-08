# 🎓 Learning Management System (LMS)

A full-stack LMS web app using the **MERN stack** (MongoDB, Express.js, React, Node.js). It supports student/instructor roles, course management, video content, and real-time chat.

---

## ⚙️ Features

- User authentication (JWT)
- Instructor & student roles
- Course creation & enrollment
- Video uploads (Cloudinary)
- Real-time chat
- Email notifications (Gmail SMTP)

---

## 📸 Screenshots

![Home](./ScreenShots/Home.png)
![ourses](./ScreenShots/Courses.png)
![Payment Done](./ScreenShots/Payment.png)

---

## 📁 Project Structure

/backend -> Express API + MongoDB
/frontend -> React app (Vite)
/screenshots -> App previews

Backend Setup
cd backend
npm install

Create .env inside backend/:
PORT=8080
FRONTEND_URL=http://localhost:5173
MONGO_URI=mongodb+srv://user:pass@cluster.mongodb.net/lms
JWT_SECRET=dummy_secret
JWT_EXPIRE=24h
CLOUD_NAME=your_cloud_name
API_KEY=cloudinary_key
API_SECRET=cloudinary_secret
GMAIL_ID=youremail@gmail.com
APP_PASSWORD=gmail_app_password  

npm start

 Frontend Setup

 cd ../frontend
npm install

📝 Notes
Ignore .env and node_modules in .gitignore

Screenshots go in /screenshots and are used in README

Keep secrets safe – never commit .env

🛠 Built With
React + Vite

Node.js + Express

MongoDB + Mongoose

Cloudinary

Nodemailer

Socket.io (for chat)
