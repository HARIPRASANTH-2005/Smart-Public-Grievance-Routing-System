# 🏛️ Smart Public Grievance Routing System

An **AI-Powered Smart Governance Automation Platform** that digitally manages citizen complaints by automatically analyzing, routing, and tracking public grievances using workflow automation and Large Language Models.

Developed as a real-world **e-Governance automation solution** demonstrating intelligent public service management.

---

## 🚀 Project Overview

The **Smart Public Grievance Routing System** automates the complete lifecycle of citizen complaints:

* Citizens submit grievances through an online government-style portal.
* AI automatically converts raw complaints into formal government letters.
* Complaints are intelligently routed to the appropriate department.
* Departments receive automated email notifications.
* Complaint status is tracked using a centralized database.
* Citizens receive resolution notifications automatically.

This system minimizes manual intervention and improves transparency and response efficiency in public administration.

---

## 🌐 Live Demo (Portfolio Version)

🔗 **Demo Portal**
https://hariprasanth-2005.github.io/Smart-Public-Grievance-Routing-System/

> ⚠️ Public version runs in **Demo Mode** for security reasons.
> Backend automation, credentials, and live webhooks are intentionally disabled.

---

## 🛠️ Technology Stack

### Automation Platform

* **n8n Workflow Automation**

### Artificial Intelligence

* **Groq LLM**
* AI Agent for automated complaint letter generation

### Frontend

* HTML5
* CSS3
* Responsive Government Portal UI
* JavaScript (Demo submission handling)

### Database

* Google Sheets (Complaint tracking system)

### Communication

* Gmail API for departmental alerts & citizen notifications

### Logic Processing

* JavaScript nodes for:

  * Complaint ID generation
  * Date calculation
  * Workflow routing

---

## ⚙️ System Architecture

Citizen Portal
⬇
Webhook Trigger
⬇
AI Complaint Generation
⬇
Department Routing Engine
⬇
Email Notification System
⬇
Google Sheets Tracking
⬇
Resolution Notification

---

## 📂 Project Structure

```
Smart-Public-Grievance-Routing-System
│
├── README.md
│
├── frontend/
│   └── index.html
│
└── workflows/
    ├── Smart Public Grievance Routing System.json
    └── Complaint Resolution Notification.json
```

---

## 🔄 Workflow Explanation

### 1️⃣ Grievance Routing Workflow

* Receives citizen complaint via webhook.
* AI generates formal complaint letter.
* Unique Complaint ID automatically created.
* Complaint routed using department-based logic.
* Official email sent to concerned authority.

### 2️⃣ Complaint Resolution Workflow

* Monitors complaint status from database.
* Detects completed grievances.
* Automatically sends resolution notification email to citizen.

---

## 🔐 Security & Privacy

This repository follows secure open-source practices:

* ✅ Webhook URLs removed
* ✅ API keys excluded
* ✅ OAuth credentials not exported
* ✅ Personal email addresses removed
* ✅ No real citizen data stored
* ✅ Demo frontend without backend exposure

---

## 📖 How to Run Locally

1. Install **n8n**
   https://docs.n8n.io/getting-started/installation/

2. Import workflow JSON files.

3. Configure:

   * Gmail credentials
   * Google Sheets connection
   * Groq API access

4. Update webhook URL inside:

   ```
   frontend/index.html
   ```

5. Activate workflows in n8n.

---

## 🎯 Use Cases

* Smart City Governance
* Municipal Complaint Systems
* Digital Public Administration
* Citizen Service Automation
* Government Workflow Digitization

---

## 🚧 Future Enhancements

* Complaint tracking dashboard
* SMS notifications
* Department login portal
* Analytics & reporting system
* Mobile application integration
* Role-based access control

---

## 👨‍💻 Author

**Hari Prasanth S**

🎓 B.Sc Computer Science  
PSG College of Arts and Science  

🎓 BS in Data Science and Applications  
Indian Institute of Technology Madras (Online Degree)

🔗 GitHub: https://github.com/HARIPRASANTH-2005

## ⭐ Support

If you found this project useful:

⭐ Star this repository
🍴 Fork the project
📢 Share feedback

---

## 📜 License

This project is developed for **educational and research purposes**.
