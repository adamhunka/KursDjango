# Django Blog Application

A simple blog application built with Django that allows users to create, publish, and manage blog posts.

## Features

- User authentication and authorization
- Create and edit blog posts
- Publish and manage posts
- View published posts
- Simple and clean interface

## Project Structure

```
.
├── blog/                 # Main blog application
├── mysite/              # Project configuration
├── manage.py            # Django management script
└── db.sqlite3           # SQLite database
```

## Requirements

- Python 3.x
- Django
- SQLite

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Create and activate a virtual environment:
```bash
python -m venv myvenv
source myvenv/bin/activate  # On Windows: myvenv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Create a superuser:
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

## Usage

1. Access the admin panel at `http://127.0.0.1:8000/admin/`
2. Log in with your superuser credentials
3. Create and manage blog posts through the admin interface
4. View published posts on the main blog page

## Models

The application includes the following main model:

- `Post`: Represents a blog post with fields for:
  - Author (User)
  - Title
  - Text content
  - Creation date
  - Publication date

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is open source and available under the MIT License. 