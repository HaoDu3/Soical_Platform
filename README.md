# Social Web Application

A comprehensive social web application developed using Django, jQuery, and SQLite. The application includes user authentication, RESTful APIs, and dynamic frontend interactions to provide a seamless user experience.

## Description

The Social Web Application is designed to offer a platform for social interaction, where users can register, log in, post updates, and interact with other users. The backend is powered by Django, handling the core functionality and user data, while the frontend utilizes jQuery for dynamic content updates. SQLite is used for efficient data management.

## Features

- **User Authentication**: Secure user login and registration using Django's built-in user management system.
- **RESTful APIs**: Developed with Django to facilitate seamless communication between the frontend and backend.
- **Efficient Data Management**: Optimized SQLite queries for performance and scalability.
- **Dynamic Frontend**: Enhanced interactivity using jQuery, allowing for dynamic content updates and improved user experience.

## Technologies Used

- **Backend**:
  - Django
  - SQLite

- **Frontend**:
  - jQuery


## Installation

### Prerequisites

- Python

### Backend

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/social-web-app.git
    ```
2. Navigate to the backend directory:
    ```bash
    cd social-web-app/backend
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set up environment variables:
    Create a `.env` file in the backend directory and add your environment variables:
    ```env
    SECRET_KEY=your_secret_key
    DATABASE_URL=sqlite:///db.sqlite3
    ```

5. Run migrations:
    ```bash
    python manage.py migrate
    ```

6. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```

7. Start the backend server:
    ```bash
    python manage.py runserver
    ```

