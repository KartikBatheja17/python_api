Django API for Managing Apps
This project is a simple Django-based API for managing app details. It allows adding, retrieving, and deleting app records from the database.

Setup Instructions

1. Download and Extract the Project

    Download the provided project ZIP file.
    Extract the contents of the ZIP file to a folder on your computer.

2. Create and Activate a Virtual Environment

    Open a command prompt and navigate to the project folder. Create a virtual environment by running:
    python -m venv venv

    Activate the virtual environment:
    venv\Scripts\activate

3. Install Dependencies

    Inside the project folder, install the required dependencies using below command:
    pip install -r requirements.txt 

4. Set Up the Database

    Run the following commands to create the necessary database tables:
    python manage.py makemigrations
    python manage.py migrate

5. Start the Development Server

    Run the server using:
    python manage.py runserver