# Research Collaboration Platform "SciSync"

[logo](https://www.canva.com/design/DAF5fIVmypM/b3-p_-P7mvbd2-_q4oXbRQ/edit?utm_content=DAF5fIVmypM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

The Research Collaboration Platform "SciSync" is a web-based platform designed to facilitate collaboration among researchers, allowing them to share their work, find collaborators, and receive feedback online.

## Installation

To install and run this project, you need to have Python 3, PostgreSQL, and Node.js installed on your machine.
- Clone this repository using `git clone https://github.com/lulu994/research_collaboration_platform.git`
- Navigate to the `backend` directory and create a virtual environment using `python -m venv env`
- Activate the virtual environment using `env\Scripts\activate` on Windows or `source env/bin/activate` on Linux or Mac
- Install the required dependencies using `pip install -r requirements.txt`
- Navigate to the `frontend` directory and install the required dependencies using `npm install`
- Start the backend server using `python manage.py runserver`
- Start the frontend server using `npm start`
- Visit `http://127.0.0.1:8000/` to view the web app.

## Usage

To use this web app, you need to create an account and log in. You can then create, edit, and delete your research projects, and invite other researchers to collaborate. You can also upload and download research files, and communicate with your collaborators using the chat feature.

Here are some screenshots of the web app:

!Home page
!Project page

You can also watch this demo video to see the web app in action:

!Demo video

## Features

- User authentication and authorization
  * Users can sign up, log in, and log out
  * Users can edit their profile and change their password
  * Users can only access their own projects and the projects they are invited to
- Project management
  * Users can create, edit, and delete their projects
  * Users can invite other users to collaborate on their projects
  * Users can accept or decline collaboration requests
- File uploading and downloading
  * Users can upload and download research files to their projects
  * Users can view the file details and history
  * Users can delete the files they uploaded
- Chat functionality
  * Users can chat with their collaborators in real-time
  * Users can send text, emoji, and file messages
  * Users can see the online status and typing indicator of their collaborators

## Technologies Used

- **Backend:**
  - Django: Web framework for building the backend.
  - Django REST Framework: Facilitates building RESTful APIs.

- **Frontend:**
  - React: JavaScript library for building the user interface.

- **Database:**
  - PostgreSQL: A powerful, open-source relational database.

- **Authentication:**
  - JWT (JSON Web Tokens): Secure authentication mechanism.

- **File Storage:**
  - Amazon S3: Cloud storage service for storing uploaded files

## Credits

+ This project was inspired by ResearchGate, a social networking site for scientists and researchers.
