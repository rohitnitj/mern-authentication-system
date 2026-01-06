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

## 📸 Screenshots


### 🔐 Login Page
<img width="1906" height="900" alt="image" src="https://github.com/user-attachments/assets/3fc02a71-299e-4f38-90e6-7ce8b943253d" />

### 📝 Register Page
<img width="1896" height="904" alt="image" src="https://github.com/user-attachments/assets/ea18d2f6-ff2b-4053-a38d-994c8385507d" />

### 📧 Email OTP Verification
<img width="1896" height="899" alt="image" src="https://github.com/user-attachments/assets/0daa3351-1afc-4294-af2f-3aad34155e26" />

### 🔁 Reset Password
<img width="1892" height="889" alt="image" src="https://github.com/user-attachments/assets/bcd7ca46-21eb-4f6d-904a-7e1ee805bb7e" />
<img width="1902" height="893" alt="image" src="https://github.com/user-attachments/assets/401805b5-ee3f-432d-981d-85517a35e26f" />
<img width="1908" height="903" alt="image" src="https://github.com/user-attachments/assets/d7bdd0c5-4352-4711-b517-01e94cc6b4bd" />


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
