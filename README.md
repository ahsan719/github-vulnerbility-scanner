# 🛡️ Github Repo Vulnerabilty Scanner

## Overview

**Github Repo Vulnerabilty Scanner** is a powerful GitHub repository vulnerability scanner and AI-based recommendation system. It integrates Trivy for deep scanning of repositories and utilizes LLM (LLaMA 3) via the Groq API to generate insightful and professional recommendations on detected vulnerabilities.

> ⚡ Scan, Detect, and Remediate vulnerabilities — in one go!

---

## 🚀 Features

- ✅ GitHub Repository Verification (public or private)
- 🔍 Clone and scan repositories using **Trivy**
- 📂 Detect:
  - Vulnerabilities
  - Secrets
  - Misconfigurations
  - License issues
    AI-Powered Report Generator using **LLaMA 3 (Groq)**
    Downloadable reports (Trivy raw + AI analysis)
    AI Suggests:
  - Top 3 Critical Vulnerabilities
  - Remediation Steps
  - Known Exploits & Attack Techniques
- 📈 Tracks scan statistics per project
- 🌐 Clean Gradio UI with theme customization

---

## 🛠️ Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/ahsan719/github-vulnerbility-scanner.git
cd github-vulnerbility-scanner
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Install Trivy (if not installed)

Follow the instructions at:  
🔗 https://aquasecurity.github.io/trivy/v0.37.0/installation/

### 4. Run the App

```bash
python3 app.py
```

This will launch a Gradio web interface for interaction.

### 🔐 GitHub Token (Optional)

To scan private repositories or avoid GitHub API rate limits, generate a Personal Access Token and paste it in the UI.

---


---

## 📦 Requirements

- Python 3.8+
- Trivy
- Python Packages:
  - requests
  - gradio
  - uuid
  - re
  - subprocess

Install them using:

```bash
pip install -r requirements.txt
```
## 👨‍💻 Contributing

1. Fork this repo  
2. Create your feature branch:  
   ```bash
   git checkout -b feature/my-feature
   ```
3. Commit your changes:  
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:  
   ```bash
   git push origin feature/my-feature
   ```
5. Open a Pull Request

---

