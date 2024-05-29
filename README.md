# Note App

A simple note-taking application built with Django and JavaScript.

## Description

The Note App allows users to create, edit, and delete notes directly from the web interface. The notes are stored locally in the browser using `localStorage`.

## Installation

To set up the project locally, follow these steps:

 **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/note-app.git
Navigate to the project directory:
cd note-app

Create and activate a virtual environment:
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

Install the required dependencies:
pip install -r requirements.txt

Apply the migrations:
python manage.py migrate
Run the development server:
python manage.py runserver

  **Usage
Open your web browser and navigate to http://127.0.0.1:8000/.
To add a note, click the + button.
To delete a note, double-click on the note and confirm the deletion.
Notes are saved automatically in the browser's local storage.

  **Features
Add New Notes: Click the + button to add a new note.
Edit Notes: Click on an existing note to edit its content.
Delete Notes: Double-click on a note to delete it with a confirmation dialog.
Local Storage: Notes are saved in the browser's local storage, ensuring persistence across sessions.

Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Thanks to Django and JavaScript for making development easier.
Inspired by various online tutorials and resources.
bash


### .gitignore

To avoid uploading unnecessary files like your virtual environment or local database, create a `.gitignore` file in your project root with the following content:

```gitignore
# Virtual environment
env/
.venv/

# Django stuff:
*.log
*.pot
*.pyc
__pycache__/
db.sqlite3
media

# Static files
staticfiles/
static/

# IDEs and editors
.vscode/
.idea/
*.swp

# MacOS
.DS_Store
