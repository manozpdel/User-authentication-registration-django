## User Authentication and Registration using Django

This repository provides a simple Django project for user authentication and registration. It includes functionalities such as login, registration, and a basic dashboard page.

## Features

- **Virtual Environment Setup**: The repository includes instructions for setting up a virtual environment to isolate dependencies.

- **Project Creation**: It guides users through creating a Django project named "my_project".

- **App Creation**: Instructions are provided for creating a Django app named "myapp".

- **HTML Templates**: The repository contains HTML templates for login, registration, and the dashboard pages, along with an index.html file containing login and registration buttons.

- **Login Page**: Users can log in securely using their credentials.

- **Registration Page**: New users can register for an account by providing necessary details like username, email, and password.

- **Dashboard**: After logging in, users are redirected to a dashboard page where they are greeted with a welcome message and their username.

- **Logout Functionality**: Users can log out of their accounts securely using the provided logout button.

## Structure

The project follows a modular structure with separate directories for templates, static files (CSS and JavaScript), views, and forms, making it easy to maintain and extend the application.

## Installation

1. Clone the repository:

    ```
    git clone <repo-url>
    ```

2. Navigate to the project directory:

    ```
    cd my_project
    ```

3. Create a virtual environment:

    ```
    python3 -m venv env
    ```

4. Activate the virtual environment:

    - For Windows:

        ```
        env\Scripts\activate
        ```

    - For macOS/Linux:

        ```
        source env/bin/activate
        ```


## Usage

1. Start the Django development server:

    ```
    python manage.py runserver
    ```

2. Open your web browser and go to `http://localhost:8000/` to access the application.

3. Click on the "Login" button to access the login page.

4. If you're a new user, click on the "Register" button to create an account.

5. After logging in or registering, you will be redirected to the dashboard page where you can see a welcome message along with your username.

6. To log out, simply click on the "Logout" button.

### Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

