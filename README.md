# PDF Management System

This repository contains the source code and files for the PDF Management System. It is a web application that allows users to manage their PDF files effectively. The system includes features such as login and registration, file uploads, file management, user profile management, and more.

## Features

The PDF Management System includes the following features:

- **Login and Registration Page:** Users can create an account or log in to an existing account.
- **Home/Dashboard Page:** Users are presented with a dashboard that provides an overview of their uploaded files.
- **Displays Count of Total Uploaded Files:** The dashboard displays the count of total uploaded files.
- **List of Uploaded Files:** The dashboard lists all the uploaded files.
- **Download File:** Users can download files from the system.
- **Get Share Link:** The system provides a shareable link for each file.
- **Uploads:**
  - **Add New File:** Users can add new files to the system.
  - **List All Files:** All the uploaded files are listed for easy management.
  - **Update File Details:** Users can update file details.
  - **Delete File Details:** Users can delete file details.
- **Profile:**
  - **Update Profile Details:** Users can update their profile details.
  - **Update Account Password:** Users can update their account password.
- **Logout:** Users can securely log out of their account.

## Installation Guide

Follow the steps below to install and run the PDF Management System on your local machine:

1. Install Python and Django if they are not already installed on your system.
2. Clone this repository or download the source code as a ZIP file and extract it to your desired location.
3. Open a terminal or command prompt and navigate to the project directory.
4. Install the required dependencies by running the following command:
````
pip install -r requirements.txt
````
5. Perform the database migrations by running the following command:
````
python manage.py migrate
````
6. Start the development server with the following command:
````
python manage.py runserver
````
7. Open a web browser and access the application at `http://localhost:8000`.

## Access Information

Use the following login credentials to access the PDF Management System:

- **SuperUser**
- Username: admin
- Password: admin123

- **Sample User**
- Username: shobh-user
- Password: jaipur1234

Feel free to explore and test the features of the PDF Management System using the provided accounts.

Please note that this information is provided for demonstration purposes, and it is recommended to change the passwords and create new user accounts for production environments.

For any issues or questions, please open an issue on the repository or contact shobhitgupta966@gmail.com

Enjoy using the PDF Management System!
