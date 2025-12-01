# SWENG 861: Weekly Assignment Scaffold

This is the official starter repository for the **Weekly Learning Scaffold** in **SWENG 861: Software Construction**.

You will build upon this repository cumulatively from Week 1 through Week 6, evolving it from a basic skeleton into a secured, containerized, and observable application.

## 📂 Repository Structure

The repository is organized to support the separation of concerns required in later modules:

/
├── backend/            # Contains the "Metrics Code" (e.g., /metrics endpoint) 
├── frontend/           
├── .github/            
├── docker/             # Docker Compose files to spin up Grafana/Prometheus
├── observability/      # Configuration files (prometheus.yml, grafana-dashboards.json)
└── README.md

🚀 Getting Started
You have two ways to start your project. Method 1 is recommended if available.

Method 1: Use This Template (Recommended)
Click the green "Use this template" button at the top right of this page.

Select "Create a new repository".

Owner: Select your personal account.


Repository Name: You MUST use the following naming convention: sweng861-crud-<yourPSUid> (Example: sweng861-crud-xyz123)

Visibility: Set to Private (unless instructed otherwise).

Click Create repository.

Method 2: Manual Clone
If the template button is not visible, follow these steps locally:

1. Clone this starter repository:

Bash

git clone [https://github.com/psu-sweng/sweng861-weekly-starter.git](https://github.com/psu-sweng/sweng861-weekly-starter.git)

2. Rename the folder to match the course convention:

Bash
mv sweng861-weekly-starter sweng861-crud-<yourPSUid>

3. Re-initialize Git (This creates a fresh history for your project):

Bash

cd sweng861-crud-<yourPSUid>
rm -rf .git       # Windows: rmdir /s /q .git
git init
Create your own repository on GitHub named sweng861-crud-<yourPSUid>.

Link and Push:

Bash

git remote add origin [https://github.com/](https://github.com/)<your-username>/sweng861-crud-<yourPSUid>.git
git add .
git commit -m "Initial commit from starter scaffold"
git push -u origin main
🛠 Prerequisites
To successfully complete the weekly assignments, ensure you have the following installed:

Git

Docker Desktop (for database and containerization labs)

Node.js (LTS version) or Python/Java/.NET SDK (depending on your chosen backend stack)

VS Code (or your preferred IDE)

📝 Student Info
Please update this section after cloning.

Name: [Your Name]

PSU Email: [Your Email]

Project Description: [Briefly describe your chosen domain, e.g., Task Manager, Ticket System]

This repository is for academic use in SWENG 861. Please do not commit API keys or secrets.
