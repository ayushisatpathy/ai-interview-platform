# 🚀 AI Interview Platform

An AI-powered full-stack web application that helps candidates prepare for job interviews by analyzing their resume, self-description, and target job description to generate personalized interview preparation reports.

Using **Google Gemini AI**, the platform evaluates profile-job compatibility, identifies skill gaps, generates technical and behavioral interview questions, and creates a structured preparation roadmap.

---
🌐 Live Demo

Frontend (Vercel):https://ai-interview-platform-lilac-ten.vercel.app/
## ✨ Features

- 🔐 Secure JWT Authentication
- 👤 User Registration & Login
- 📄 Resume Upload (PDF)
- 📑 Automatic Resume Text Extraction
- 💼 Job Description Analysis
- 🤖 AI-Powered Interview Report Generation
- 📊 Match Score Between Resume & Job Description
- 💻 Personalized Technical Interview Questions
- 🗣️ Behavioral Interview Questions
- 📚 Skill Gap Analysis
- 📝 Customized Preparation Plan
- 📂 View Previous Interview Reports
- 🚪 Logout Functionality
- 📱 Responsive User Interface

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router
- SCSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Multer
- PDF-Parse
- Google Gemini API
- Zod

### Database
- MongoDB Atlas

### Tools
- Git & GitHub
- Postman
- VS Code

---

## 🏗️ Project Structure

```
AI-Interview-Platform
│
├── Frontend
│   ├── public
│   ├── src
│   └── package.json
│
├── Backend
│   ├── src
│   │   ├── controllers
│   │   ├── middleware
│   │   ├── models
│   │   ├── routes
│   │   ├── services
│   │   └── utils
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/ayushisatpathy/ai-interview-platform.git
```

### Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file inside the Backend folder:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_gemini_api_key
CLIENT_URL=http://localhost:5173
```

Start the backend:

```bash
npm start
```

---

### Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

---

## 🚀 How It Works

1. Register or log in to the platform.
2. Upload your resume in PDF format.
3. Enter a short self-description.
4. Paste the job description of your target role.
5. The backend extracts resume content.
6. Gemini AI analyzes your profile against the job description.
7. A personalized interview report is generated including:
   - Match Score
   - Technical Questions
   - Behavioral Questions
   - Skill Gaps
   - Preparation Roadmap
8. Reports are stored securely and can be accessed later.

---

## 📌 Environment Variables

| Variable | Description |
|----------|-------------|
| `MONGO_URI` | MongoDB Atlas connection string |
| `JWT_SECRET` | Secret key for JWT authentication |
| `GEMINI_API_KEY` | Google Gemini API key |
| `CLIENT_URL` | Frontend URL |

---

## 🔮 Future Enhancements

- 🎙️ AI Voice Mock Interviews
- 📈 ATS Resume Score
- 🧠 Company-Specific Interview Preparation
- 📹 Video Interview Simulation
- 🌙 Dark Mode
- 📊 Interview Analytics Dashboard
- 📧 Email Verification & Password Reset

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 👩‍💻 Author

**Ayushi Satpathy**

- GitHub: https://github.com/ayushisatpathy
- LinkedIn: www.linkedin.com/in/ayushi-satpathy-0389b0305

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star!
