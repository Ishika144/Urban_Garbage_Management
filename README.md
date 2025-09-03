# Urban Garbage Management System

## 📌 Project Overview
The **Urban Garbage Management System** is a web-based platform that helps streamline waste management and complaint handling.  
It allows citizens to raise complaints, municipality officers to assign tasks, and workers to update the status of garbage collection.  
The system improves transparency, reduces manual effort, and ensures accountability.

---

## 🚀 Features
- **Multi-role Login System**  
  - Government  
  - Municipality Officer  
  - Worker  
  - Public (citizens)  
- **Complaint Management**  
  - Citizens can register complaints with details.  
  - Officers assign tasks to workers.  
  - Workers update complaint status in real-time.  
- **Dashboards**  
  - Separate dashboards for each role.  
  - Task tracking and progress monitoring.  
- **Transparency & Efficiency**  
  - Real-time updates reduce manual tracking by ~60%.  
  - Secure role-based access to data.  

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  
- **Platform:** Localhost (XAMPP)  

---

## 📂 Database Design
**Tables:**
1. `users` – stores login info (username, password, role).  
2. `complaints` – stores complaint details, status, assigned worker.  
3. `tasks` – task assignments and updates.  

---

## ⚙️ Installation & Setup
1. Install **XAMPP** or any local server.  
2. Clone this project folder into the `htdocs` directory.  
3. Import the provided SQL file into **phpMyAdmin**.  
4. Start Apache and MySQL from XAMPP Control Panel.  
5. Open the project in your browser:  
