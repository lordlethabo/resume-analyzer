# 🧠 Resume Analyzer – AI-Powered Skill Matching Tool

**Resume Analyzer** is a smart, cloud-powered web app that allows users to upload resumes (PDF or TXT), instantly analyze the content using AI, extract key skills, and receive personalized recommendations to improve their job-readiness.

---

## 🚀 Live Demo
🔗 [Try the live app on Firebase Hosting](https://resume-analyzer-5b815.web.app)

---

## ✨ Features

- 🔍 **Client-side PDF parsing** using `pdf.js`
- 🧠 **AI-powered skill extraction** and keyword matching
- ☁️ **Firebase Integration** (Storage + Hosting)
- 🌙 **Dark mode toggle** with smooth transitions
- 🎯 **Admin-only AWS Textract toggle** for OCR parsing (via Lambda)
- 📊 (Coming soon) Skill gap dashboard with role-based recommendations

---

## 🧑‍💻 Tech Stack

| Area         | Technology / Service                  |
|--------------|----------------------------------------|
| Frontend     | HTML, TailwindCSS, JavaScript (ES6)    |
| OCR Parsing  | pdf.js (default), AWS Textract (optional) |
| File Storage | Firebase Storage                       |
| Hosting      | Firebase Hosting                       |
| Backend (OCR) | AWS Lambda + S3 + IAM                 |
| CI/CD        | GitHub + Firebase CLI / GitHub Actions |

---

## 🛠 How to Set Up Locally

### 1. Clone the Repository

```bash
git clone https://github.com/lordlethabo/resume-analyzer.git
cd resume-analyzer
