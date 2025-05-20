# 🎓 Campus Complaint Management System

A full-stack web application designed to streamline the process of lodging, tracking, and resolving complaints within a college campus environment. Built using **Flask** and integrated with **Microsoft Azure services** for secure deployment and monitoring.

## 🚀 Features

- 🧑‍🎓 Student portal to submit and view complaints
- 🧑‍💼 Admin dashboard to review and update complaint statuses
- 📊 Complaint categorization by type and status
- 📥 File uploads with Azure Blob Storage
- 🔐 Secure login with Azure Entra ID (formerly Azure AD)
- 📈 Monitoring and diagnostics via Azure Application Insights
- ⚙️ CI/CD using Azure DevOps Pipelines

---

## 🛠️ Tech Stack

### Backend
- **Flask (Python)**
- Azure SQL Database
- Azure Blob Storage
- Azure Entra ID Authentication

### Frontend
- HTML5, CSS3, JavaScript
- Jinja2 Templating

### DevOps & Cloud
- Azure App Service
- Azure DevOps Pipelines
- Azure Logic Apps
- Azure Application Insights

---

## 📂 Project Structure

```bash
.
├── app.py                        # Main Flask app
├── requirements.txt             # Dependencies
├── templates/                   # HTML templates
│   ├── admin_dashboard.html
│   ├── student_dashboard.html
│   └── submit_complaint.html
├── static/                      # Static files (CSS, JS)
└── README.md
