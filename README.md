# Project Management Tool

A collaborative **Project Management Tool** built with **Django**.  
This project is inspired by tools like **Trello** and **Asana**, where users can create projects, manage tasks, assign work to team members, and communicate through comments.

---

## Features

- User authentication (Login / Logout / Register)
- Create and manage group projects
- Add team members to projects
- Create, update, and delete tasks
- Assign tasks to users
- Task status management (To Do, In Progress, Done)
- Comment system for communication inside tasks
- Admin panel for managing users, projects, tasks, and comments
- Structured Django app-based architecture

---

## Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite
- **Version Control:** Git & GitHub

---

## Project Structure

```bash
Project-Management-Tool/
│
├── comments/
├── notifications/
├── pmtool/
├── projects/
├── tasks/
├── users/
├── manage.py
├── db.sqlite3
└── README.md
Main Modules
1. Users

Handles user authentication and user-related features.

2. Projects

Allows users to:

create projects
manage project details
collaborate with team members
3. Tasks

Handles:

task creation
task assignment
task tracking
task status updates
4. Comments

Allows users to communicate inside tasks by posting comments.

5. Notifications

Will be used to show alerts such as:

new task assigned
comment added
project updates
Planned Workflow
User registers or logs in
User creates a project
User adds tasks to the project
Tasks can be assigned to project members
Team members update task progress
Users comment inside tasks for communication
Notifications keep users updated
Future Improvements
Drag and drop task board like Trello
Real-time notifications using WebSockets
File attachments in tasks
Due dates and priority labels
Dashboard analytics
Search and filters
Better UI with Bootstrap cards and responsive design
How to Run This Project Locally
1. Clone the repository
git clone https://github.com/your-username/Project-Management-Tool.git
cd Project-Management-Tool
2. Create virtual environment
python -m venv venv
3. Activate virtual environment
On Windows
venv\Scripts\activate
On Mac/Linux
source venv/bin/activate
4. Install Django
pip install django
5. Run migrations
python manage.py migrate
6. Create superuser (optional)
python manage.py createsuperuser
7. Run the development server
python manage.py runserver
8. Open in browser
http://127.0.0.1:8000/
Current Status

This project is currently under development.
Basic Django project setup and GitHub integration have been completed, and the next steps include building:

authentication system
project creation module
task board
comment system
notifications
Learning Goals of This Project

This project is being built to practice and strengthen concepts of:

Django project structure
Models, Views, Templates
Authentication system
CRUD operations
Database relationships
Team collaboration system design
Git and GitHub workflow
Author

Husna Ali
Computer Science Student | Aspiring Software Developer

GitHub: husnamuhammadali
