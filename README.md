Finance Management System
This project is a Finance Management System built with Python and Django. It allows users to securely log in, register, and manage their finances by tracking bank accounts, essential and non-essential expenses, and generating financial reports in PDF format.

Features
User Authentication: Secure user login and registration system with password encryption.
Bank Account Management: Users can register their bank accounts and manage the balance.
Add or remove funds from bank accounts.
Track multiple bank accounts at once.
Expense Management: Categorize expenses into essential and non-essential categories.
Account Statement: Generate PDF statements showing transactions for a selected period (7 to 30 days).
Financial Dashboard: Overview of the user's bank account balances and recent transactions.
Transaction History: View detailed history of transactions for each bank account.
Technology Stack
Backend: Python, Django
Frontend: HTML, CSS, JavaScript (Django templates for views)
Database: SQLite (configured in Django settings)
Libraries/Tools:
Django: Web framework for Python
JWT Authentication: For secure user authentication
Installation
Prerequisites
Python 3.10 or higher
Django 3.x or higher
SQLite (default database in Django)
Steps to Install
Clone the Repository
Clone the project to your local machine:

bash
Copiar
git clone https://github.com/yourusername/finance-management.git
cd finance-management
Set Up Virtual Environment
Create a virtual environment to manage dependencies:

bash
Copiar
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Install Dependencies
Install the necessary dependencies from requirements.txt:

bash
Copiar
pip install -r requirements.txt
Apply Migrations
Apply database migrations to create tables and set up the SQLite database:

bash
Copiar
python manage.py migrate
Create Superuser
Create a superuser to access the Django admin panel:

bash
Copiar
python manage.py createsuperuser
Run the Server
Start the Django development server:

bash
Copiar
python manage.py runserver
Access the Application
Open your browser and go to http://localhost:127.0.0.1:8000. to access the application.
