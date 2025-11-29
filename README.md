# NEXTGEN MINDS — Master’s Research Project Portfolio

This repository contains the official portfolio website for the **NEXTGEN MINDS** Master's Research Project.  
The site includes all required academic sections such as Executive Summary, Problem Context, Research, Architecture, ER Diagrams, Data Flow, Dashboard Insights, and Appendix resources.

---

## 📌 Live Portfolio Website
[https://rajeshbhukya29.github.io/NextGenMinds_Portfolio/](https://rajeshbhukya29-dot.github.io/NextGenMinds_Portfolio/)

## 📌 Live NEXTGEN MINDS Application
https://rajeshbhukya29-dot.github.io/Nextgenminds_12/

---

## 1. Project Overview

Students often struggle to understand which jobs match their skills, what to learn next, and how their education connects to the real job market. Employers also find it difficult to identify job-ready talent among fresh graduates.

**NEXTGEN MINDS** solves this problem by providing:
- Skill-based job matching  
- Personalized insights  
- Interactive dashboards  
- Upskilling recommendations  
- A clean data-driven architecture built using everyday tools  

The system is lightweight, scalable, and suitable for academic institutions and students.

---

## 2. Technology Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS, JavaScript (GitHub Pages) |
| Backend | Google Apps Script Web App |
| Database | Google Sheets (Students, Jobs, Employers, Contacts) |
| Dashboards | Google Sheets Charts & Performance Analytics |
| Hosting | GitHub Pages |

---

## 3. Key Features

- Student Registration & Login  
- Employer Job Posting Dataset  
- Dynamic Jobs Page (from Google Sheets)  
- Skill-Based Job Matching  
- Performance Dashboard (skills, demand, match %)  
- Upskilling Recommendations  
- Contact Form  
- Clean thematic UI (Glass Hero + White Professional Sections)

---

## 4. Data Model (Google Sheets Structure)

### Students Sheet
- user_id  
- first_name  
- last_name  
- email  
- city  
- education_level  
- experience_years  
- skills  
- preferred_role  
- created_at  

### Jobs Sheet
- job_id  
- employer_user_id  
- company_name  
- job_title  
- job_type  
- location  
- min_exp  
- max_exp  
- skills_required  
- required_edu  
- created_at  
- status  

### Employers Sheet
- employer_user_id  
- company_name  
- email  
- password  
- created_at  

### Contacts Sheet
- name  
- email  
- subject  
- message  
- created_at  

---

## 5. Architecture Summary

The system uses a 3-layer structure:

### Presentation Layer
- GitHub Pages (HTML/CSS/JS)

### Application Layer
- Google Apps Script Web App  
- Handles POST/GET, validation, sheet writes, job loading

### Data Layer
- Google Sheets  
- Stores 1000+ synthetic records for testing  

Included diagrams inside portfolio website:
- Enterprise Architecture Diagram  
- ER Diagram  
- Data Flow Diagram  

---

## 6. Dashboard & Insights

The performance dashboard shows:
- Skill demand  
- Match rate by experience  
- Missing skills  
- Popular job categories  
- Recommended learning paths  

Access dashboard:
https://rajeshbhukya29-dot.github.io/Nextgenminds_12/performance.html

---

## 7. Team Members

- **Rajesh Bhukya** — Project Manager / Lead Developer  
- **Rajesh Bandari** — Business Analyst  
- **Srija Bakshi** — Technical Architect  
- **Saathwika Sunkari** — Compliance & Research Officer  
- **Haripriya** — IT Solutions Analyst  

---

## 8. Repository Structure

NextGenMinds_Portfolio/
│
├── index.html
├── style-portfolio.css
├── images/
│ ├── logo.png
│ ├── team-rajesh-bhukya.jpg
│ ├── team-rajesh-bandari.jpg
│ ├── team-saathwika-sunkari.jpg
│ ├── team-srija-bakshi.jpg
│ └── team-haripriya.jpg
└── README.md


---

## 9. Academic Purpose

This portfolio website is built for:

- Master’s Research Project Submission  
- Final Presentation  
- Academic Evaluation  
- Long-term resume and LinkedIn portfolio use  

---

## 10. Contact

For questions or collaborative opportunities:  
**Email:** rajeshbhukya230@gmail.com

---


