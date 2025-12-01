# SWENG 861: Weekly Assignment Scaffold

This is the official starter repository for the **Weekly Learning Scaffold** in **SWENG 861: Software Construction**.

In this course, you will build a "Bring Your Own Domain" (BYOD) application cumulatively from Week 1 through Week 6. You will use this repository to evolve your project from a basic API into a secured, containerized, and observable system.

## 📂 Repository Structure

The repository is organized to support the engineering patterns required in each module:

```text
/
├── backend/            # Weeks 1-3 & 5: API, Database, Auth Middleware, and Unit Tests
├── frontend/           # Week 4: Single Page Application (React/Angular/Vue)
├── .github/            # Week 6: CI/CD Pipeline Configurations
├── docker/             # Week 6: Dockerfiles & Compose (App + Monitoring Stack)
├── observability/      # Week 6: Prometheus configs, Dashboard JSONs, or Screenshots
└── README.md           # Project documentation

---

### File 2: Canvas Assignment Page Content
**Filename:** `Canvas_Deliverable_I.md`
*(Use this content to create the assignment page in your LMS)*

```markdown
# Course Project – Deliverable I: Proposal & Checkpoint
**Due: End of Week 2**

## Overview
This assignment serves as the **Project Proposal and Checkpoint** for your Capstone.
Its purpose is to ensure you have selected a viable project, defined a reasonable scope, and set up your foundational infrastructure before you begin heavy development.

### ⚠️ Repository Strategy
Please note that you will maintain **two separate repositories** this semester:
1.  **Weekly Scaffold Repo:** Used for Weeks 1–6 assignments (`sweng861-crud-<id>`).
2.  **Capstone Repo:** Used for this Course Project (`sweng861-capstone-<id>`).

## What to Submit
You must submit **two items**:
1.  **A Proposal Document** (PDF or Word).
2.  **A GitHub Repository Link** (for the Capstone).

---

## Part 1: The Proposal Document
Create a 1–2 page document that answers the following questions. This is your roadmap for the semester.

### 1. Project Category & Title
* **Category:** Choose one: Web App, Mobile App, IoT/Robotics, Data Analytics, or AI/ML.
* **Domain:** Which "Campus Project" did you choose? (e.g., "Project C: Campus Ride") or are you using BYOD?

### 2. Problem & Users
* **Problem Statement:** What problem are you solving? (1 paragraph)
* **Target Users:** Who is this for? (e.g., "University students needing safe transport").

### 3. Core Features
* **Must-Have Features:** List 3-4 features required for the MVP (e.g., "User Login," "Book a ride," "View history").
* **Nice-to-Have Features:** List 1-2 features you might add later (e.g., "Dark Mode," "Live map tracking").

### 4. Architecture & Tech Stack
* **Architecture Sketch:** A simple description or diagram of how it works.
    * *Example:* React Frontend → Python API → PostgreSQL Database.
* **Tech Stack:** List the specific tools you plan to use.
    * *Languages:* (e.g., Python, Java, JavaScript)
    * *Frameworks:* (e.g., Spring Boot, Flask, React)
    * *Data:* (e.g., MySQL, MongoDB, CSV files)

---

## Part 2: The GitHub Repository (Capstone)
You must initialize the **new** version control repository where your Capstone project will live.

* **Do not** use the `sweng861-weekly-starter` code for this. This project should start fresh to match your specific domain.
* **Create a Public (or Shared) Repository:** Create a new repo on GitHub.
* **Naming Convention:** `sweng861-capstone-<yourPSUid>`
* **Add a README.md:** The file should currently contain:
    * Your Project Title.
    * A 2-3 sentence description of what the project does.
    * Your Name.
* **Add a .gitignore:** Ensure your repo is configured to ignore system files and secrets (`.env`, `api_keys`).

---

## Grading Criteria (Pass/Fail Checkpoint)
This deliverable is graded on **completeness and viability**.

* **Scope Check:** Is the project too simple (e.g., "Hello World") or too complex (e.g., "Clone of Uber")?
* **Clarity:** Is the architecture clearly defined?
* **Setup:** Does the GitHub link work and is it distinct from your weekly assignment repo?

**Note on AI Policy:**
You may use AI tools to help brainstorm ideas or draft this proposal, but you must own the final scope.
