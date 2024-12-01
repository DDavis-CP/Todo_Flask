# Welcome To To-Do Checklist App
**Flask App**

## Overview

This project is a To-Do List web application built using Flask. It allows users to add, edit, and delete tasks.

## Setup Instructions

### Prerequisites

- Python 3.7+
- Flask 3.0.3
- Pip (Python package installer)

### Installation

1. **Clone the Repository**
```bash
   git clone https://github.com/yourusername/todo-list-flask-app.git

   cd todo-list-flask-app
```

2.  **Create and Run Activate Virtual Enviroment**
```bash
   python -m venv venv

   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
```

3. **Install Dependencies**
```bash
   pip install -r requirements.txt
```

### Running The Project

1. **Set The Flask Enviroment Variables**
```bash
   export FLASK_APP = app.py
   export FLASK_ENV = development

```
   ### On Windows
```bash
   set FLASK_APP=todo.py
   set FLASK_ENV=development
```

2. **Run The Flask App**
```bash
   flask run
```

3. **Access The App**
```bash
Open your web browser and navigate to `http://127.0.0.1:5000`
```

 To enhance the user interface, icons have been added to buttons by including images in the static files. Resizing issues were addressed by hardcoding the height and width of the icons.

## Report
###Design and Coding Choices
1. Flask Framework: Chosen for its simplicity and ease of use.
2. Icons for Buttons: Icons were added to buttons to make the interface more intuitive. The icons were resized by hardcoding their dimensions in the HTML to ensure consistent appearance across different devices.
3. Static Folder: All static files, including icons and CSS, are stored in the static folder.
## Challenges Faced
1. Icon Resizing: Initially, there were issues with the icons not displaying correctly. This was resolved by hardcoding the height and width attributes in the HTML.
2. Environment Setup: Ensuring all dependencies were correctly installed and compatible was challenging but resolved by using a virtual environment.
Lessons Learned
3. Handling Static Files: Learned the importance of organizing and properly referencing static files in a Flask project.
4. Debugging UI Issues: Gained experience in troubleshooting and resolving UI issues related to icon sizing.
5. Flask Best Practices: Improved understanding of best practices for setting up and running Flask applications, including the use of environment variables and virtual environments.