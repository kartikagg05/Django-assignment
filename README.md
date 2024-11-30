# Django-assignment
Gas Utility Service Management System
Overview
The Gas Utility Service Management System is a Django-based web application designed to streamline customer service requests for a utility company. The platform features a user-friendly interface to manage customer service requests, along with an intuitive admin panel for easy backend operations.

Features
Admin Panel
Manage and monitor service requests efficiently with Django's built-in admin interface.

Service Request Creation
Customers can submit their service requests with relevant details and optional file attachments.

Service Request Listing
Admins can view all service requests, including their current statuses, in a neatly formatted list.

Technical Stack
Backend Framework: Django (Python)
Database: SQLite (can be configured for PostgreSQL/MySQL)
Frontend: HTML, CSS, Django templates
Other Tools: Django Admin Panel, File Upload Support
Installation
Follow these steps to set up the project locally:

Clone the repository:

bash
Copy code
git clone <repository-url>
cd gas-utility-service
Create a virtual environment:

bash
Copy code
python -m venv env
source env/bin/activate  # For Linux/Mac
env\Scripts\activate     # For Windows
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Apply database migrations:

bash
Copy code
python manage.py migrate
Run the server:

bash
Copy code
python manage.py runserver
Access the application at http://127.0.0.1:8000/.

How to Use
1. Admin Access
Navigate to http://127.0.0.1:8000/admin/.
Log in with your admin credentials.
Manage users and service requests through the admin interface.
2. Service Requests
Create Request: Customers can submit their requests at /customer_service/create/.
View Requests: Admins can see a consolidated list at /customer_service/list/.
