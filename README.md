# 📄 CVipher – AI Resume Analyzer

CVipher is an AI-powered web app that helps job seekers analyze, score, and improve their resumes for specific job applications.
It combines ATS scoring, AI feedback, and a visual dashboard to provide clear, actionable insights into how well a CV matches a job description.

---

## ✨ Key Features

> 🔐 Authentication – Secure login via Puter.js before accessing features.
>
> 📂 Upload CV – Drag & drop PDF upload with instant preview.
>
> 🖼️ Resume Conversion – Converts PDFs into images for quick in-app preview.
> 
> 📊 ATS Scoring – Automated ATS score (0–100) with icons and gradients.
> 
> 🧠 AI Feedback – Personalized suggestions across:
>    - Tone & Style
> - Content
> - Structure
> - Skills
> 
> 📑 Resume Cards – Visual dashboard of all past submissions with score highlights.
> 
> 📋 Detailed Review Page – Side-by-side PDF/image preview + AI feedback breakdown.
> 
> 🧹 Data Management – Optional wipe route to clear stored files and feedback.

---

## 🛠️ Tech Stack

> Frontend: React, React Router, TypeScript

> Styling: TailwindCSS

> Infra / Services: Puter.js
> for:
> 
> - Authentication
> 
> - File system (resume upload, storage, retrieval)
> - KV store (saving feedback + resume metadata)
> - AI API (resume analysis + suggestions)
> - PDF Processing: pdfjs-dist@5.3.93
> (for PDF → image conversion)

---

## Routes Overview

> /auth → login / logout page

> / → dashboard with uploaded resumes

> /upload → upload CV + job description form

> /resume/:id → detailed feedback page (ATS score + AI insights)

> /wipe → developer utility route to clear app data

---

## 🚀 Getting Started
> 1. Clone the Repository  
   `git clone https://github.com/AtharvaP555/CVipher-CV_Analyzer.git`
   `cd CVipher-CV_Analyzer`

> 2. Install Dependencies  
   `npm install`

> 3. Run Dev Server  
   `npm run dev`

App will be available at:
👉 http://localhost:5173

---

## ⚙️ Configuration

### Ensure pdfjs-dist is installed at the correct version:

> `npm uninstall pdfjs-dist`  
> `npm install pdfjs-dist@5.3.93`

---

## 📸 Demo Flow

> Login → Authenticate with Puter.

> Upload → Select your CV + enter job details.

> Analysis → File uploads, ATS score + AI feedback generated.

> Review → View detailed feedback across Tone, Content, Structure, Skills.

> Track → All resumes stored in dashboard with preview cards.

---

## 📌 Roadmap

- Multi-resume comparison (side-by-side).

- Export AI feedback as PDF/Docx.

- Advanced ATS keyword optimization.

- UI improvements: dark mode + interactive charts.

- More models & AI explanation capabilities.

---

## 🤝 Contributing

Contributions are welcome! To contribute:

> 1. Fork the repo
> 
> 2. Create a feature branch (git checkout -b feature/my-feature)
> 
> 3. Commit changes (git commit -m "Add new feature")
>
> 4. Push to branch (git push origin feature/my-feature)
>
> 5. Open a Pull Request 🎉

---

## 📄 License

MIT License © 2025 AtharvaP555