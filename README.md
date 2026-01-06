# MERN Authentication System 🔐

A complete authentication system built using the **MERN stack**, featuring secure JWT-based authentication, email verification using OTP, and password reset functionality.

This project demonstrates real-world authentication workflows commonly used in production-grade web applications.

---

## 🚀 Features

- User Registration & Login
- JWT-based Authentication
- Email Verification using OTP
- Forgot Password & Reset Password
- Protected Routes
- Secure HTTP-only Cookies
- Form Validation & Error Handling
- Toast Notifications for better UX

---

## 🛠 Tech Stack

### Frontend
- React.js
- Axios
- React Router
- Vite

### Backend
- Node.js
- Express.js
- MongoDB
- JWT (JSON Web Tokens)
- bcrypt
- Nodemailer

---

## ⚙️ Environment Variables

Create a `.env` file inside the `server/` directory and add:

PORT=5000  
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_jwt_secret  
EMAIL_USER=your_email_address  
EMAIL_PASS=your_email_password  
CLIENT_URL=http://localhost:5173  

⚠️ **Important:** Never commit the `.env` file to GitHub.

---

## 🧑‍💻 Installation & Setup

### Backend
cd server  
npm install  
npm run dev  

### Frontend
cd client  
npm install  
npm run dev  

- Frontend runs on: http://localhost:5173  
- Backend runs on: http://localhost:5000  

---

## 📁 Project Structure

```text
mern-auth/
├── client/        # React frontend
├── server/        # Node.js + Express backend
├── .gitignore
└── README.md
```


## 📌 Future Improvements

- OAuth Authentication (Google / GitHub)
- Refresh Tokens
- Rate Limiting
- Role-based Authorization
- Docker & Production Deployment

---

## 👤 Author

Rohit Kumar  
B.Tech, Computer Science & Engineering  
NIT Jalandhar  

---

## ⭐ Support

If you find this project helpful, please consider giving it a ⭐ on GitHub.
