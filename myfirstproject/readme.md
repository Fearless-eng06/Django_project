# SkyCHAT

SkyCHAT is a [Django](https://www.djangoproject.com/) project designed to create a messaging platform similar to Whatsapp.

## Installation

1. First, clone the repository to your computer:

    ```
    git clone https://github.com/your_username/Django_project.git
    ```

2. Navigate to the project directory:

    ```
    cd SkyCHAT
    ```

3. Install dependencies from the requirements.txt file:

    ```
    pip install -r requirements.txt
    ```

4. Run migrations to create the database:

    ```
    python manage.py migrate
    ```

5. Start the Django development server:

    ```
    python manage.py runserver
    ```

6. Open your browser and go to http://127.0.0.1:8000/ to start using the application.

## Features

- **User Registration and Authentication**: Users can register and log in to the system to start messaging.
- **Message Exchange**: Registered users can send and receive messages from other users.
- **Group Chats**: Ability to create group chats for communication among multiple users simultaneously.
- **User Profiles**: Each user has their own profile where they can manage their settings and information about themselves.

## License

This project is licensed under the [MIT License](LICENSE).