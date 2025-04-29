
# School Database Management System

This project is a **Role-Based School Management System** developed using **Django**, aimed at streamlining school operations by providing tailored access to **Admins**, **Teachers**, and **Parents**. The system is designed with a focus on modularity, automation, and user-friendly dashboards.

## Key Features

- **Role-Based Access Control**:  
  Provides distinct dashboards and features for Admins, Teachers, and Parents.
  
- **Automated Core Operations**:  
  Implements reusable modules for:
  - Grade calculation
  - Attendance updates
  - Invoice generation

- **Trigger-Based Automation**:  
  Backend triggers are integrated to:
  - Automate email confirmations
  - Update the library catalog dynamically

- **Clean, Responsive Dashboards**:  
  Designed with **HTML/CSS** for a seamless user experience across roles.

## Modules and Functionality

- **Reusable Modules**:  
  Modular design with reusable components such as `functions.py`, `triggers.py`, and `roles.py` to handle core operations efficiently.

- **Views for Essential Features**:  
  - Student Marks Overview  
  - Library Catalog Management  
  - Invoice Summaries  

- **Notifications & Logging**:  
  Automates notifications for important events like attendance logs and grade updates.

## Technologies Used

- **Backend**: Django, Python, SQLite  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: SQLite  

## Skills Learned

- Django Framework for Web Development  
- Modular Programming with Python  
- Frontend Design with HTML/CSS/JavaScript  
- Database Management with SQLite  
- Automation with Backend Triggers  

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/jigs1188/school-database-mangement-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd school-database-mangement-project
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the development server:
   ```bash
   python manage.py runserver
   ```
5. Open your browser and go to `http://127.0.0.1:8000/` to explore the system.
