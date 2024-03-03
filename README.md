
# Attendance Management System with Image Capture

## Introduction

This Attendance Management System is a web application designed to allow managers to create a roster for staff and enable staff members to mark their attendance by capturing an image using a webcam. The system is built with Django and uses Bootstrap for a minimalistic frontend.

## Features

- **Authentication & Authorization:** Separate roles for Manager and Staff with secure login.
- **Roster Management:** Managers can add staff members, set shifts, and view the complete roster.
- **Attendance Management:** Staff members can view shifts and mark attendance with an image capture.
- **Responsive Design:** User-friendly interface that is responsive on both desktop and mobile devices.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8 or newer
- pip and virtualenv

## Setup

To set up the Attendance Management System, follow these steps:

1. **Clone the repository**

   ```
   git clone https://github.com/sachnaror/attendence_system.git
   cd attendance_System
   ```

2. **Create and activate a virtual environment**

   ```
   virtualenv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**

   ```
   pip install -r requirements.txt
   ```

4. **Apply migrations**

   ```
   python manage.py migrate
   ```

5. **Collect static files** (if necessary)

   ```
   python manage.py collectstatic
   ```

## Running the Application

To run the Attendance Management System, execute:

```
python manage.py runserver
```

Access the web application by navigating to `http://127.0.0.1:8000/` in your web browser.

## Usage

- **Manager Role:** Login as a manager to create and manage the roster, add new staff members, and view attendance records.
- **Staff Role:** Login as a staff member to view assigned shifts and mark attendance by capturing an image using the webcam.

## Contributing

Contributions to the Attendance Management System are welcome. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature_branch_name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the original branch: `git push origin feature_branch_name`.
5. Create the pull request.
