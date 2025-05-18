# CampusGriev - Student Complaint Management System

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Flask](https://img.shields.io/badge/flask-2.0+-lightgrey.svg)
![Azure](https://img.shields.io/badge/Azure-Cloud-orange)
![License](https://img.shields.io/badge/license-MIT-green)

A cloud-based complaint management system for educational institutions, built with Flask and Microsoft Azure services.

## 🌟 Features

- **Student Portal**
  - Submit complaints with attachments (images/docs)
  - Track complaint status in real-time
  - Receive email notifications

- **Admin Dashboard**
  - View and manage all complaints
  - Assign complaints to staff
  - Update resolution status

- **Cloud Integration**
  - Azure Blob Storage for file uploads
  - Azure SQL Database for complaint data
  - Azure Logic Apps for email automation
  - Application Insights for monitoring

## 🛠 Tech Stack

**Frontend:**  
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=flat&logo=bootstrap&logoColor=white)

**Backend:**  
![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=flat&logo=flask&logoColor=white)

**Database & Storage:**  
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=flat&logo=microsoft%20sql%20server&logoColor=white)
![Azure Blob Storage](https://img.shields.io/badge/Azure_Blob_Storage-0089D6?style=flat&logo=microsoft-azure&logoColor=white)

**DevOps:**  
![Azure Logic Apps](https://img.shields.io/badge/Azure_Logic_Apps-0089D6?style=flat&logo=microsoft-azure&logoColor=white)
![Application Insights](https://img.shields.io/badge/Application_Insights-0089D6?style=flat&logo=microsoft-azure&logoColor=white)

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Azure account (for cloud services)
- Git

### Installation
1. Clone the repository
```bash
git clone https://github.com/GulamHasan01/CampusGriev---Student-Complaint-Management-System.git
cd CampusGriev---Student-Complaint-Management-System
````
2.Install dependencies
````
pip install -r requirements.txt
````
3.Set up environment variables
Create a .env file based on .env.example:
````
AZURE_STORAGE_CONNECTION_STRING="your_azure_blob_connection_string"
AZURE_SQL_CONN_STRING="your_sql_db_connection_string"
LOGIC_APP_WEBHOOK_URL="your_logic_app_trigger_url"
APPINSIGHTS_CONNECTION_STRING="your_app_insights_connection_string"
````
## 🌐 Live Deployment

The application is deployed on **Azure App Services** and can be accessed at:  
🔗 [https://6604193gulamhasang1-fcbkgjg4g7h3ebck.centralindia-01.azurewebsites.net](https://6604193gulamhasang1-fcbkgjg4g7h3ebck.centralindia-01.azurewebsites.net)

### Deployment Details:
- **Service:** Azure Web Apps
- **Region:** Central India
- **Runtime Stack:** Python 3.8
- **CI/CD:** GitHub Actions (optional - add if used)
