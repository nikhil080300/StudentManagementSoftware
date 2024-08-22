# Django Student Management System (beta)

A simple Student Management System using Python (Django) for educational purposes.

## Features

### Admin
1. Summary Charts: Students, Staff, Courses, Subjects, Leave, etc.
2. Manage: Staff, Students, Courses, Subjects, Sessions.
3. View: Attendance.
4. Feedback: Review and reply.
5. Leave: Approve/Reject.

### Staff/Teachers
1. Summary Charts: Students, subjects, leave status.
2. Manage: Attendance, Results.
3. Apply for Leave, Send Feedback.

### Students
1. Summary Charts: Attendance, subjects, leave status.
2. View: Attendance, Results.
3. Apply for Leave, Send Feedback.

## Installation

### Pre-Requisites
- Install Git: [git-scm.com](https://git-scm.com/)
- Install Python: [python.org/downloads](https://www.python.org/downloads/)
- Install Pip: [pip.pypa.io](https://pip.pypa.io/en/stable/installing/)

### Steps
1. Create a folder for the project.
2. Create and activate a virtual environment:
   - Install: `pip install virtualenv`
   - Create: `python -m venv venv` (Windows) | `python3 -m venv venv` (Mac)
   - Activate: `source venv/scripts/activate` (Windows) | `source venv/bin/activate` (Mac)
3. Clone the project:
   ```bash
   git clone https://github.com/nikhil080300/StudentManagementSoftware.git
   cd StudentManagementSoftware


*Alternative to Pip is Homebrew*


**4. Install Requirements from 'requirements.txt'**
```python
$  pip install -r requirements.txt
```

**5. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Add [‘*’]. 
```python
ALLOWED_HOSTS = ['*']
```


**6. Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```

**7. Login Credentials**

Create Super User (HOD)
```
$  python manage.py createsuperuser
```
Then Add Email, Username and Password

**or Use Default Credentials**

*For HOD /SuperAdmin*
Email: admin@gmail.com
Password: admin

*For Staff*
Email: staff@gmail.com
Password: staff

*For Student*
Email: student@gmail.com
Password: student


