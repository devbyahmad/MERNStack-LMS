 🎓 Learning Management System (LMS)

A full-stack **Learning Management System** (LMS) built using the **MERN** stack (MongoDB, Express.js, React, Node.js). This platform allows students and instructors to manage courses, enrollments, content delivery, and communication in real-time.

---

## 🚀 Features

- 👤 User Authentication (JWT-based)
- 🧑‍🏫 Instructor & Student Roles
- 📚 Course Creation & Enrollment
- 🎥 Video Lessons & Resources
- 💬 Real-time Chat Support
- ☁️ Cloudinary for media uploads
- 📧 Email notifications via Gmail SMTP

---

## 🖼️ Screenshots

### 🔐 Login Page
![Login](./screenshots/login.png)

### 📚 Course Dashboard
![Dashboard](./screenshots/dashboard.png)

### 🎥 Course Video Player
![Video](./screenshots/video.png)

---

## 📁 Folder Structure

your-project/
│
├── backend/ # Express.js + MongoDB API
│ └── .env
│
├── frontend/ # React client
│ └── .env
│
├── screenshots/ # App preview images
│
└── README.md

yaml
Copy
Edit

---

## ⚙️ Technologies Used

- **Frontend**: React, Vite, Axios, TailwindCSS
- **Backend**: Node.js, Express, Mongoose
- **Database**: MongoDB Atlas
- **Media**: Cloudinary API
- **Auth**: JSON Web Token (JWT)
- **Email**: Nodemailer with Gmail SMTP

---

## 🔧 Installation & Setup

### 📦 Clone Repository

```bash
git clone https://github.com/your-username/lms-mern.git
cd lms-mern
🛠 Backend Setup
bash
Copy
Edit
cd backend
npm install
🔑 Create .env file inside backend/:
env
Copy
Edit
PORT=8080
FRONTEND_URL=http://localhost:5173

MONGO_URI=mongodb+srv://dummyUser:dummyPass@cluster0.mongodb.net/lms
JWT_SECRET=dummy_jwt_secret_123456
JWT_EXPIRE=24h

CLOUD_NAME=dummy_cloud
API_KEY=1234567890123
API_SECRET=dummy_cloud_secret

GMAIL_ID=dummyemail@example.com
APP_PASSWORD=dummyapppassword
bash
Copy
Edit
npm start
🌐 Frontend Setup
bash
Copy
Edit
cd ../frontend
npm install
🔑 Create .env file inside frontend/:
env
Copy
Edit
VITE_BACKEND_URL=http://localhost:8080
bash
Copy
Edit
npm run dev
🚨 Environment Files
Both frontend/.env and backend/.env should be included locally but ignored in Git:

.gitignore (both frontend & backend)
bash
Copy
Edit
node_modules/
.env
✅ How to Use
Create an account as a student or instructor.

Instructors can:

Create courses

Upload videos/resources

Students can:

Enroll in courses

Watch lessons

Chat with instructors

All media is hosted on Cloudinary, and email updates are sent via Gmail.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.

📃 License
MIT

📧 Contact
Developer: [Your Name]
📩 Email: youremail@example.com
🌐 GitHub: github.com/your-username

yaml
Copy
Edit

---

### 📌 Reminder

To make this README fully functional:

- Replace all dummy credentials with real ones in local `.env` files (never push them).
- Replace screenshot names and paths if needed.
- Replace `your-username`, repo links, and contact info with yours.

Let me know if you want a PDF version of this README or a sample `LICENSE` file.
