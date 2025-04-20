# Edu Master - Enhanced Student Management System
This is an enhanced Student Management System built with Python (Django), featuring additional functionalities like Fee Management.

## Features of this Project

### A. Admin Users Can
1. See Overall Summary Charts of Students Performance, Staffs Performances, Courses, Subjects, Leave, etc.
2. Manage Staffs (Add, Update and Delete)
3. Manage Students (Add, Update and Delete)
4. Manage Course (Add, Update and Delete)
5. Manage Subjects (Add, Update and Delete)
6. Manage Sessions (Add, Update and Delete)
7. Manage Fee Structure and Student Payments
8. View Student Attendance
9. Review and Reply Student/Staff Feedback
10. Review (Approve/Reject) Student/Staff Leave

### B. Staff/Teachers Can
1. See the Overall Summary Charts related to their students, their subjects, leave status, etc.
2. Take/Update Students Attendance
3. Add/Update Result
4. View Student Fee Status
5. Apply for Leave
6. Send Feedback to HOD

### C. Students Can
1. See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
2. View Attendance
3. View Result
4. View Fee Status and Payment History
5. Apply for Leave
6. Send Feedback to HOD

## Installation and Setup

### Pre-Requisites:
1. Python 3.x
2. pip (Package Manager)
3. Virtual Environment

### Installation Steps:

1. Create and activate virtual environment:
```bash
python -m venv venv
source venv/scripts/activate  # For Windows
source venv/bin/activate      # For Mac/Linux
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Configure environment variables in .env file:
```
DEBUG=True
SECRET_KEY=your-secret-key
ALLOWED_HOSTS=localhost,127.0.0.1
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Create superuser:
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

### Default Login Credentials

**Admin Account**
- Email: admin@gmail.com
- Password: admin

**Staff Account**
- Email: staff@gmail.com
- Password: staff

**Student Account**
- Email: student@gmail.com
- Password: student

## Custom Features Added

1. **Fee Management System**
   - Set up fee structure for different courses
   - Track student payments
   - Generate payment receipts
   - View payment history
   - Payment status dashboard

2. **Enhanced UI/UX**
   - Modern interface design
   - Responsive dashboard
   - Improved navigation

## Deployment
The application is deployed on Render and can be accessed at your-app-specific-url.onrender.com

