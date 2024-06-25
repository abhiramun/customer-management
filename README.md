Introduction
Welcome to the Customer Management System (CMS) project! This system is designed to help businesses manage their customers efficiently. 
With features tailored for both checkers and makers, it provides a seamless experience for customer data management.

Setup Instructions
To get started with the CMS project, follow these simple setup instructions:

Activate Virtual Environment:

Navigate to the project directory in your terminal or command prompt.
Activate the virtual environment by running the appropriate command based on your operating system and shell:

- Windows Command Prompt:
  customer_managementenv\Scripts\Activate

- Windows PowerShell:
  customer_managementenv\Scripts\Activate.ps1

Run the Project:

Once the virtual environment is activated, run the Django project by executing:
Copy code
py manage.py runserver

Accounts
The CMS project comes with predefined accounts for both checkers and makers:

- Checkers
  Username: checker1, Password: Demo@2001
  Username: checker2, Password: Demo@2001
- Makers

  Under Checker 1:
- Username: maker1, Password: Demo@2001
- Username: maker2, Password: Demo@2001

  Under Checker 2:
- Username: maker3, Password: Demo@2001
- Username: maker4, Password: Demo@2001

Demo Customers
The CMS project includes demo customers with sample photos and resumes already added to the system, allowing you to explore its features immediately.

Project Structure
The project directory follows a standard Django structure, including:

accounts/: Contains views, templates, and migrations related to user accounts.
customer_data/: Contains views, templates, and migrations for customer data management.
static/: Contains static files such as CSS, JavaScript, and images.
manage.py: Django's command-line utility for managing the project.

