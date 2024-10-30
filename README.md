PyStackFlow
Brief Project Description
PyStackFlow is a Django-based web application designed to serve as an educational assessment dashboard. This app processes and visualises student performance data in a clear, interactive interface, making it easier for educators to track and analyse progress across different subjects or assignments.

Setup Instructions
Clone the Repository

bash
Copy code
git clone git@github.com:colinjsheehan/01_PyStackFlow.git
cd 01_PyStackFlow
Create a Virtual Environment

bash
Copy code
python3 -m venv venv
Activate the Virtual Environment

On macOS/Linux:
bash
Copy code
source venv/bin/activate
On Windows:
bash
Copy code
.\venv\Scripts\activate
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Run Migrations

bash
Copy code
python manage.py migrate
Start the Development Server

bash
Copy code
python manage.py runserver
Visit http://127.0.0.1:8000 in your browser to access the application.

Requirements
Python Version: 3.12
Django Version: 5.1.2