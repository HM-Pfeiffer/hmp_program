# MySite Django Project

This is a Django-based web application that includes a `polls` app and is configured to run with Docker and PostgreSQL.

## Features

- **Django Framework**: Built using Django 4.0.1.
- **PostgreSQL Database**: Configured to use PostgreSQL as the database backend.
- **Dockerized**: Includes Docker and Docker Compose setup for easy deployment.
- **Polls App**: A simple app with a basic view to display a welcome message.

## Prerequisites

- Docker and Docker Compose installed on your system.
- Python 3.9 or higher (if running locally without Docker).

## Setup Instructions

### Using Docker

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd mysite

2. Build and start the containers:

3. Access the application:

- Web app: http://localhost:8000
- Admin panel: http://localhost:8000/admin
- pgAdmin: http://localhost:5433

## Running Locally

1. Install dependencies:
```
pip install -r requirements.txt
```

2. Set up the database:

- Update .env with your database credentials.
- Apply migrations:
```
python manage.py migrate
```


3. Start the development server:
```
python manage.py runserver
```

4. Access the application at http://localhost:8000.

## Environment Variables

The project uses a .env file to manage sensitive information. Example variables include:

* DB_NAME
* DB_USER
* DB_PASSWORD
* DB_HOST
* DB_PORT

