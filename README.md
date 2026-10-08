# 🤖 Automated Resume-Based Job Application System

<p align="center">
  <b>AI-powered resume analysis, job matching and browser automation for job applications.</b>
</p>

<p align="center">
  <a href="https://github.com/saicharan-017/Automated-Resume-Based-Job-Application-System">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-Web%20App-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-Automation-43B02A?style=for-the-badge&logo=selenium&logoColor=white" />
</p>

## 📌 Overview

This project explores an automated job-application workflow built around a candidate's resume. It combines resume text extraction, role selection, job search and browser automation to reduce repetitive application work.

The repository contains experiments and implementation work around automated application flows, including support for Easy Apply-style forms and AI-assisted responses.

## 🎯 Problem

Applying to many jobs manually is repetitive:

```text
Resume → Search Jobs → Open Job → Fill Form → Upload Resume → Answer Questions → Submit
```

The goal of this project is to automate as much of that repetitive workflow as practical while keeping the candidate in control of authentication and sensitive actions.

## 💡 How It Works

```text
                Resume PDF
                    │
                    ▼
              Resume Parsing
                    │
                    ▼
          Role / Job Information
                    │
                    ▼
             Job Search
                    │
                    ▼
            Browser Automation
                    │
        ┌───────────┴───────────┐
        ▼                       ▼
   Resume Upload          Form Questions
                                │
                                ▼
                           Gemini API
                                │
                                ▼
                         Application Flow
```

## ✨ Key Features

- 📄 PDF resume text extraction
- 🤖 AI-assisted job-role detection
- 🔎 Job search using role and location
- 🌐 Selenium-based browser automation
- 📝 Automated form-field handling
- 📎 Resume upload handling
- 🧠 Gemini-assisted question answering
- 🔁 Multi-step application wizard handling
- 🧪 Experimental support for Easy Apply-style application flows

## 🛠️ Technology Stack

| Area | Technology |
|---|---|
| Language | Python |
| Web Framework | Flask |
| Resume Parsing | pdfminer.six |
| Browser Automation | Selenium |
| Driver Management | webdriver-manager |
| AI | Google Gemini API |
| Frontend | HTML / CSS / Jinja templates |

## 📂 Repository Structure

```text
Automated-Resume-Based-Job-Application-System/
│
├── AutoJob_Profile/
├── Easy Apply possibilities/
├── .gitignore
├── LICENSE
├── README.md
└── ...
```

The repository also contains implementation artifacts and prototypes related to the automation workflow.

## ⚙️ Setup

### 1. Clone the repository

```bash
git clone https://github.com/saicharan-017/Automated-Resume-Based-Job-Application-System.git
cd Automated-Resume-Based-Job-Application-System
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

Install the required packages used by the implementation. Keep API keys and personal information outside source control.

### 4. Configure AI credentials

Use an environment variable or local configuration for your Gemini API key. **Never commit real API keys, passwords or personal credentials.**

## ▶️ Running the Application

The Flask-based components can be started from the application entry point:

```bash
python app.py
```

Then open the local Flask address shown in the terminal.

## 🔐 Authentication & Safety

Browser automation for job platforms can interact with real accounts and applications. Use this project responsibly.

- Log in manually where required.
- Review applications before submission.
- Respect the website's Terms of Service.
- Do not store passwords or session credentials in the repository.
- Do not commit API keys or private personal data.

## 🧪 Project Status

This is an active experimental project. Automation flows on third-party job platforms can change when their UI or policies change, so selectors and workflows may require maintenance.

## 🔮 Future Improvements

- Resume-to-job semantic matching
- Match-score based filtering
- Better question classification
- Platform-independent job adapters
- Application history and analytics
- Safer human-in-the-loop submission
- Improved configuration management
- Automated tests for parsing and matching components

## 👨‍💻 Author

**Sai Charan**

[GitHub](https://github.com/saicharan-017)
