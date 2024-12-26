# Simple To-Do List Application

This is a lightweight to-do list web application built using **Flask**, **Jinja2**, **HTML**, and **Bootstrap**. It allows users to add, view, and delete tasks with an intuitive interface.

---

## Features

- **Add Tasks**: Easily add new tasks with a description.  
- **Edit Tasks**: Edit all tasks in a simple, clean layout.  
- **Delete Tasks**: Remove completed or unwanted tasks with a single click.  
- **Responsive Design**: Uses Bootstrap to ensure compatibility across different screen sizes.  

---

## Technology Stack

- **Backend**: Flask (Python)  
- **Frontend**: HTML, Jinja2, and Bootstrap  
- **Database**: SQLite (default for simplicity, but can be swapped with any preferred database)  

---

## Setup Instructions

### Prerequisites
1. Install **Python** (3.7 or later).  
2. Install **Git** to clone the repository.  

### Installation
1. Clone this repository:  
   ```bash
   git clone https://github.com/SauravBasu10/todo.github.io.git   
   ```

2. Create and activate a virtual environment:  
   ```bash
   python -m venv venv  
   source venv/bin/activate    # For Linux/Mac  
   venv\Scripts\activateps1       # For Windows  
   ```

3. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt  
   ```

4. Run the Flask application:  
   ```bash
   py app.py
   ```

5. Open your browser and navigate to `http://127.0.0.1:8000/`.  

---

## Directory Structure

```  
simple-todo-list/  
│  
├── static/             # Static files (CSS, JavaScript)  
├── templates/          # HTML templates (Jinja2)  
├── app.py              # Main Flask application  
├── requirements.txt    # Python dependencies  
├── README.md           # Project documentation  
└── instance/database.db         # SQLite database file (auto-created)  
```

---

## Screenshots
 ### Homepage
 ![Homepage](https://github.com/Sauravbasu10/todo.github.io/blob/main/screenshots/image2.png)

 ### My todos list
![My To-Dos List](https://github.com/Sauravbasu10/todo.github.io/blob/main/screenshots/image3.png)

### Update todo
![Update todo](https://github.com/Sauravbasu10/todo.github.io/blob/main/screenshots/image1.png)