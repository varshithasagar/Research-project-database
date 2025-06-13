# 📊 Research Project Database

This project is a simple SQL database system to manage research projects, employees, managers, and funding agencies.

## 🗃️ Schema Overview

- **Employee**: Stores employee info (SSN, name, salary).
- **FundingAgency**: Stores agency name and address.
- **Project**: Contains project name, duration, budget.
- **Project_Manager**: One manager per project (who is also an employee).
- **Employee_Project**: Tracks which employees work on which projects (many-to-many).

## 📝 Sample Data

Includes example entries for:
- 3 Employees
- 3 Projects
- 3 Funding Agencies
- Project managers and their assignments

## 🚀 Features

- One project → One agency  
- One project → One manager  
- Employee ↔ Project: Many-to-many  
- Managers are employees  

