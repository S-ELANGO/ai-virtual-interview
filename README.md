# 🚀 AI Virtual Interview

An **AI-powered virtual interview platform** where users upload their resumes, answer AI-generated questions via an avatar, and receive a sharable scorecard at the end.  

This project is being built as part of my **Final Year Computer Science Project**.  
The goal is to demonstrate skills in **AI, Machine Learning, React, Firebase, and Full-Stack Development**.  

---

## 📅 Day 1 – Progress

✅ Setup React + TypeScript + Vite  
✅ Added TailwindCSS for styling  
✅ Initial project structure committed  
✅ Simple homepage displaying project title  

---

## 🛠 Tech Stack (Planned)

### Frontend
- **React + TypeScript (Vite)** → UI framework
- **TailwindCSS** → styling
- **shadcn/ui** → components (later)

### Backend / Auth / DB
- **Firebase Authentication** → login/signup (Google/GitHub)
- **Firebase Firestore** → store user info + interview results
- **Firebase Hosting** → free hosting (`.web.app` domain)

### AI/ML
- **Google Gemini API (free tier)** → generate interview questions
- **Hugging Face Free Models** → fallback for resume-based Qs
- **Avatar (Web Speech API / Three.js)** → ask questions

### Extras
- GitHub (version control)  
- Vercel (CI/CD from GitHub, optional)  
- Markdown docs + diagrams for reporting  

---

## 📂 Folder Structure (Day 1)
ai-virtual-interview/
└── frontend/
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── tsconfig.json
├── src/
│ ├── App.tsx # Clean starting point
│ ├── index.css # Tailwind styles
│ └── main.tsx
└── node_modules/

