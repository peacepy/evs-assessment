# Quantum University — Secure Examination Portal

A modern, secure, and fully dynamic online examination system built with **HTML, CSS, JavaScript** and powered by **Google Apps Script** as the backend.

[Exam Portal Preview](https://peacepy.github.io/evs-assessment)

## ✨ Features

### Student Side
- Secure Student Login
- Password change on first login
- Dynamic quiz dashboard
- Full-screen anti-cheat enabled exam environment
- Real-time question palette with status tracking
- Timer with auto-submit
- Tab switching / window blur detection (auto-submit + violation flag)
- Detailed result analysis

### Admin Panel
- Separate Admin Login
- **CRUD Operations**:
  - Add / View Students
  - Create / Manage Quizzes
  - Add / Edit Questions
  - View & Reset Student Results
- Search functionality
- Clean dark modern UI

### Backend
- Google Apps Script Web App
- Multiple Google Sheets as database:
  - `Students`
  - `Quizzes`
  - `Questions`
  - `Results`

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Google Apps Script (JavaScript)
- **Database**: Google Sheets
- **Styling**: Custom Dark Theme with glassmorphism effects
- **Deployment**: GitHub + Google Apps Script Web App

## 📁 Project Structure

```bash
quantum-exam-portal/
├── index.html                 # Main frontend file
├── Code.gs                    # Google Apps Script backend
├── data.json                  # (Optional) Backup static data
├── README.md
└── assets/                    # (Optional) images, logos
