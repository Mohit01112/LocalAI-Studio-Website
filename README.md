# LocalAI Studio Website

Official website for **LocalAI Studio**, a Windows desktop application for discovering local AI runtimes, finding installed language models, and chatting with local AI models.

🌐 **Live Website:** https://localai-studio-website.onrender.com/  
💻 **Desktop App:** Download the application from the website and install it on your Windows desktop.  
🔗 **Main Application Repository:** https://github.com/Mohit01112/LocalAI-studio

## About

This repository contains the Flask-powered landing page for LocalAI Studio. It introduces the desktop application, highlights its key features, explains how to get started, and provides a download link for the Windows installer.

### Tech Stack

- **Python** and **Flask** — web application
- **HTML** — page structure
- **CSS** — styling and responsive layout
- **Gunicorn** — production WSGI server

## Features

- Product landing page for LocalAI Studio
- Overview of local AI runtime detection and installed model discovery
- Information about chatting with local AI models
- Download call-to-action for the Windows desktop application
- Link to the main application GitHub repository
- Responsive dark-themed design

## Project Structure

```text
LocalAI-Studio-Website/
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── templates/
│   └── index.html
└── static/
    └── style.css
```

## Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Mohit01112/LocalAI-Studio-Website.git
cd LocalAI-Studio-Website
```

### 2. Create and activate a virtual environment (recommended)

**Windows PowerShell**
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

**macOS / Linux**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the development server

```bash
python app.py
```

Open http://127.0.0.1:5000/ in your browser.

## Deployment

The website is deployed on Render.

- **Build command:** `pip install -r requirements.txt`
- **Start command:** `gunicorn app:app`

**Live URL:** https://localai-studio-website.onrender.com/

## Download the Desktop Application

Visit the [LocalAI Studio website](https://localai-studio-website.onrender.com/), download the Windows installer, install it, and use LocalAI Studio directly on your desktop.

For application source code and updates, visit the [main GitHub repository](https://github.com/Mohit01112/LocalAI-studio).

## Author

**Mohit Jadhav**

- GitHub: https://github.com/Mohit01112
- LinkedIn: https://www.linkedin.com/in/mohit-jadhav-49734427b/

## License

No license has been specified for this repository yet.
