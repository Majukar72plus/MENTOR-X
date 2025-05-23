# Career Guidance Web Application

A full-stack career guidance platform built with the MERN stack (MongoDB, Express.js, React, Node.js). This application helps users assess their interests, take career quizzes, and receive personalized career recommendations based on their skills and preferences.

## 🌟 Features

- 🔐 User Registration and Login (with JWT Authentication)
- 📊 Career Assessment Quiz
- 🎯 Personalized Career Recommendations
- 📚 Career Information Database (roles, qualifications, salaries, etc.)
- 📝 Admin Dashboard for managing quizzes and career data
- 📈 Progress Tracking and Saved Recommendations
- 📧 Contact Form / Feedback System

## 🧰 Tech Stack

**Frontend:**
- React.js
- Redux (if used)
- Tailwind CSS / Bootstrap / Material UI (based on your UI choice)

**Backend:**
- Node.js
- Express.js
- MongoDB (with Mongoose ORM)
- JWT for authentication

**Other Tools:**
- Axios for API calls
- bcrypt for password hashing
- dotenv for environment variables
- CORS, Helmet for backend security

## 🏗️ Project Structure

client/ # React frontend
├── src/
│ ├── components/
│ ├── pages/
│ ├── services/
│ └── App.js

server/ # Node + Express backend
├── controllers/
├── models/
├── routes/
├── middleware/
└── server.js

## 🚀 Getting Started

### Prerequisites
- Node.js and npm
- MongoDB installed locally or a MongoDB Atlas URI

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/career-guidance-app.git
cd career-guidance-app
Install server dependencies:

cd server
npm install
Set up environment variables:

Create a .env file inside the server/ folder with:


PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start the server:


npm run dev
Install client dependencies:

cd ../client
npm install
Start the client:

bash
npm start
🔒 Authentication
Secure login/signup using hashed passwords (bcrypt)

JWT tokens for session handling

📊 Career Quiz Module
Series of multiple-choice questions

Calculates career fit scores based on answers

Uses a rules-based or weighted scoring algorithm

📄 API Endpoints
POST /api/auth/register – User signup

POST /api/auth/login – User login

GET /api/careers – Get list of career paths

POST /api/quiz/submit – Submit quiz results

(Expand this list based on your app)

📸 Screenshots
(Add images of your UI/UX here)

📚 Future Scope
AI-based recommendation engine (using ML models)

Resume builder and interview preparation resources

Chatbot career advisor

Integration with LinkedIn APIs for job tracking

🙌 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.