## 📌 Overview
The **Vasanta Group Intranet** is a web-based internal system designed to support daily employee activities. It provides features such as document approval, SOP management, dashboards for data monitoring, and integration with the IFCA system.

## 🚀 Key Features
- **Dashboard** → Overview of data and activities.
- **Common Setup & API IFCA** → Provides system configuration and integration with IFCA APIs. 
- **Online Approval** → Document approvals (PO, IOM, Sales).  
- **Document Management** → Manage SOPs and internal documents.
- **Project Management** → Supports planning and monitoring of company projects.
- **Launching System** → Facilitates the launch process for new projects or products.
- **Commission** → Facilitates the launch process for new projects or products.  
- **IFCA Reports** → Reporting integrated with the IFCA system.  

## 🔐 Access & Login
Access to the intranet is provided using the existing company email account. Once employees receive the account from HR, intranet and IFCA access are immediately active.

## 🛠️ Tech Stack
- **Frontend**: Html,Css, Javascript 
- **Backend**: PHP: yii2 Framework 
- **API**: IFCA Integration  
- **Database**: Microsoft SQL server 

## 📂 Repository Structure
```
common/
    config/              contains shared configurations
    mail/                contains view files for e-mails
    models/              contains model classes used in both backend and frontend
    tests/               contains tests for common classes    

console/
    config/              contains console configurations
    controllers/         contains console controllers (commands)
    migrations/          contains database migrations
    models/              contains console-specific model classes
    runtime/             contains files generated during runtime

backend/
    assets/              contains application assets such as JavaScript and CSS
    config/              contains backend configurations
    controllers/         contains Web controller classes
    models/              contains backend-specific model classes
    runtime/             contains files generated during runtime
    tests/               contains tests for backend application    
    views/               contains view files for the Web application
    web/                 contains the entry script and Web resources

frontend/
    assets/              contains application assets such as JavaScript and CSS
    config/              contains frontend configurations
    controllers/         contains Web controller classes
    models/              contains frontend-specific model classes
    runtime/             contains files generated during runtime
    tests/               contains tests for frontend application
    views/               contains view files for the Web application
    web/                 contains the entry script and Web resources
    widgets/             contains frontend widgets

vendor/                  contains dependent 3rd-party packages
environments/            contains environment-based overrides
``` 


## 📞 Contact
For technical questions or system access, please contact the Vasanta Group IT team
ict.dept@vasanta.co.id.
