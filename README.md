# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


Code Review AI Assistant - README

📌 Overview
This project is a Code Review AI Assistant that helps developers get instant, expert-level feedback on their code. It uses Google's Gemini AI to analyze code and provide detailed suggestions for improvement based on best practices.

✨ Key Features
AI-Powered Code Review: Get professional code reviews instantly

Multi-Language Support: Works with various programming languages

Detailed Feedback: Identifies issues and suggests improvements

Interactive UI: Clean interface with code editor and review panel

3D Visual Effects: Modern UI with subtle 3D transformations

🛠️ Tech Stack
Frontend: React.js with Prism.js for code highlighting

Backend: Node.js/Express.js

AI: Google Gemini API (gemini-2.0-flash model)

Styling: CSS with 3D transformations and gradients

🚀 How It Works
Frontend (React App)
Code Editor: Built with react-simple-code-editor

Syntax Highlighting: Uses prismjs for colored code

Markdown Display: Shows AI responses with react-markdown

3D Effects: CSS transforms create depth illusion

Backend (Node.js/Express)
Receives code from frontend

Sends it to Google Gemini AI

Returns the AI's review to frontend

AI Service
Uses 7+ years expert system prompt for code review

Checks for:

Code quality

Best practices

Performance issues

Security risks

Readability

Provides fixes with examples

🔧 Setup Instructions
Install dependencies:

bash
npm install
Environment Variables:

Create .env file with:

text
google_gemini_key=YOUR_API_KEY
Run the app:

bash
npm run dev
🌟 Project Structure
text
├── client/               # Frontend React app
│   ├── App.jsx           # Main component
│   ├── App.css           # 3D styling
│   └── ...              
├── server/               # Backend
│   ├── controller/       # Route handlers
│   ├── routes/           # API endpoints
│   ├── services/         # AI integration
│   └── app.js            # Express setup
💡 Usage
Write/paste code in the left panel

Click "Review" button

Get professional feedback in the right panel

📌 Important Notes
AI Prompt: Carefully designed system instruction in ai.service.js

Error Handling: Basic validation for empty code

CORS: Enabled for development

Responsive: Works on mobile devices

🚀 Future Improvements
Add user authentication

Support for code snippets saving

Multiple AI model options

Dark/light mode toggle
