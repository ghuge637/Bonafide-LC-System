# Bonafide-LC-System

🎓 CertiDesk — Bona-fide & Leaving Certificate Generation System

🌐 Live Demo:
🔗 https://certidesk.gt.tc/

📌 Overview

CertiDesk is a web-based automation system designed to digitize and streamline the process of generating Bona-fide and Leaving Certificates in educational institutions.

Traditional certificate workflows rely heavily on paperwork and manual approvals, which cause delays and inefficiencies. This system provides a centralized platform where students can apply online, departments can approve requests digitally, and certificates are generated automatically. 

copyright_ppt

❗ Problem Statement
Educational institutions often face major issues while handling certificate requests:
Manual paperwork and slow processing
Lack of transparency in approval flow
Difficulty tracking application status
Higher chances of human error
CertiDesk solves this by introducing a structured digital workflow for certificate requests and approvals. 


🎯 Objectives
Automate certificate request submission
Streamline approval workflow
Ensure transparency for students
Generate certificates digitally
Maintain centralized records
Improve institutional efficiency 


🧠 System Architecture

Student Portal
       ↓
   Web Interface
       ↓
   PHP Backend
       ↓
    MySQL Database
       ↓
Multi-Desk Approval System
       ↓
Certificate Generator
       ↓
Distribution Section



👥 User Roles
👨‍🎓 Student
Login using PRN number
Apply for Bona-fide / Leaving Certificat
Track application status
View approval progress

👨‍💼 Staff / Departments
View incoming requests
Approve / Reject applications
Add rejection remarks
Generate and print certificates

🔄 Workflow
📄 Bona-fide Certificate Process
Student logs into portal.
Selects reason and submits request.
Request stored in database.
Staff reviews request.
Status changes:
Pending
Approved
Rejected
Completed
Approved requests generate printable certificates. 


📜 Leaving Certificate Process (Multi-Desk Workflow)
Leaving Certificate follows a structured approval chain involving multiple departments:
Student Section
Scholarship Section
Accounts Section
Library Section
Placement Department
Workshop Department
Computer HOD
AIDS HOD
Mechanical HOD
E&TC HOD
Principal Approval
Distribution Section (Final Issue)
Each desk can:
View request
Accept or reject
Add rejection reason
If rejected, the application returns for correction and restarts from the same stage instead of starting over. 


⚙️ Tech Stack
Frontend
HTML
CSS
JavaScript
Backend
PHP
Database
MySQL
Deployment

Hosted at: https://certidesk.gt.tc/

🗄️ Database Operations
The system mainly uses:
INSERT → Store new requests
SELECT → Fetch application data
UPDATE → Change status and desk flow
DELETE → Remove completed entries
TRIGGERS → Move records to history tables automatically 


🖥️ Key Features
Centralized login system
Session-based authentication
Real-time status tracking
Multi-level department approvals
Filter requests by status
Auto-generated certificates
Printable documents
History tracking
