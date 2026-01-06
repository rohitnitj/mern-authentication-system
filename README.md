# MERN Authentication System 🔐

A complete authentication system built using the MERN stack with secure JWT authentication, email verification, and password reset functionality.

## 🚀 Features
- User Signup & Login
- JWT-based Authentication
- Email Verification using OTP
- Forgot / Reset Password
- Protected Routes
- Secure HTTP-only Cookies
- Toast Notifications

## 🛠 Tech Stack
- **Frontend:** React.js, Axios, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Auth:** JWT, bcrypt
- **Email:** Nodemailer

## ⚙️ Environment Variables

Create a `.env` file inside `server/`:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
EMAIL_USER=your_email
EMAIL_PASS=your_password
CLIENT_URL=http://localhost:5173
