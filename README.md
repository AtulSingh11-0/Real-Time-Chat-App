# Real-Time-Chat-App using Django Channels 

## Project Overview

This Real-time Chat App is built with Django Channels and Daphne, providing users with a seamless and interactive real-time communication experience. The frontend is designed using Bootstrap, HTML, and CSS for a responsive and user-friendly interface.

## Features

- Real-time chat functionality
- User authentication and authorization
- Multi-room support
- online P2P video call

## Technologies Used

- Django
- Django Channels
- Daphne (ASGI server)
- Bootstrap
- HTML, CSS, JavaScript

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/realtime-chat-app.git
```

2. Navigate to the project directory:

```bash
cd Real-Time-Chat-App
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Apply database migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

5. Start the Daphne server with runserver Command:

```bash
python manage.py runserver
```

6. Open your web browser and go to [http://localhost:8000/](http://localhost:8000/) to access the app.

## Configuration

### Database Configuration

Update the database configuration in the `settings.py` file.

```python
# settings.py

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / "db.sqlite3",
    }
}
```

## Usage

1. Create a superuser account:

```bash
python manage.py createsuperuser
```

2. Run the Daphne server:

```bash
python manage.py runserver
```

3. Open your web browser and go to [http://localhost:8000/admin/](http://localhost:8000/admin/) to log in with the superuser credentials.

4. Create chat rooms and manage users through the Django admin interface.

5. Open multiple browser tabs to simulate different users and start chatting in real-time.

## Acknowledgments

- Special thanks to the Django and Django Channels communities for their excellent documentation and support.

---
