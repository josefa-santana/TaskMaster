# TaskMaster
A full-stack task management application powered by a Flask RESTful backend and a vanilla JavaScript frontend using AJAX for seamless user interactions.


# Flask TaskMaster Web Application

A full-stack, responsive task management application designed to help users organize their daily tasks efficiently. The project features a clean dashboard, dynamic interactions, and a persistent backend built with Python and Flask.

---

## Features

- **Full CRUD Functionality:** Create, Read, Update, and Delete tasks.
- **Dynamic Task Tracking:** Mark tasks as complete or incomplete with a single click. The UI updates instantly without page reloads.
- **Interactive Dashboard:** At-a-glance view of key statistics:
    - Total tasks
    - Number of completed tasks
    - Number of open tasks
    - Current date display
- **AJAX-Powered:** User actions like completing a task are handled asynchronously using the JavaScript `fetch` API, providing a smooth and modern user experience.
- **Persistent Storage:** All tasks and their statuses are saved to a database, ensuring data is never lost on page refresh.

---

## Built With

This project was built using the following technologies:

- **Backend:**
    - [Python 3](https://www.python.org/)
    - [Flask](https://flask.palletsprojects.com/)
    - [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/) (for database interaction)
    - [Jinja2](https://jinja.palletsprojects.com/) (for templating)

- **Frontend:**
    - HTML5
    - CSS3 (with Flexbox for responsive layout)
    - Vanilla JavaScript (ES6+)

- **Database:**
    - SQLite

---

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Python 3 and `pip` installed on your system.
- python3
- pip

### Installation

1.  **Clone the repository**
    ```sh
    git clone https://github.com/josefa-santana/TaskMaster.git
    ```
2.  **Navigate to the project directory**
    ```sh
    cd TaskMaster
    ```
3.  **Create and activate a virtual environment**
    - On macOS/Linux:
      ```sh
      python3 -m venv venv
      source venv/bin/activate
      ```
    - On Windows:
      ```sh
      python -m venv venv
      .\venv\Scripts\activate
      ```
4.  **Install the required packages**
    ```sh
    pip install -r requirements.txt
    ```
5.  **Run the application**
    ```sh
    flask run
    ```
    The application will be available at `http://127.0.0.1:5000`.

---

## Future Improvements

- [ ] Implement full user authentication (Register/Login).
- [ ] Add due dates and priority levels to tasks.
- [ ] Introduce task categories or tags for better organization.
- [ ] Add a search functionality to filter tasks.
