# To-Do List Application

This is a simple to-do list application built with Django.

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/todo_project.git
    cd todo_project
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```sh
    pip install django
    ```

4. Apply migrations:
    ```sh
    python manage.py migrate
    ```

5. Run the development server:
    ```sh
    python manage.py runserver
    ```

6. Open your browser and go to `http://127.0.0.1:8000` to see the application.

## Features

- Add new tasks.
- View a list of tasks.
