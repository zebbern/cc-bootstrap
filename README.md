# Simple Flask Website

A basic Flask web application with homepage and login functionality.

## Features

- Homepage with "Hello, World!" message
- User login system with session management
- Responsive design with CSS styling
- Docker support for easy deployment

## Quick Start

### Using Docker (Recommended)

1. Build and run with docker-compose:
```bash
docker-compose up --build
```

2. Visit http://localhost:5000

### Local Development

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python app.py
```

3. Visit http://localhost:5000

## Login Credentials

- Username: `admin`
- Password: `password123`

## Project Structure

```
.
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── Dockerfile            # Docker configuration
├── docker-compose.yml    # Docker Compose configuration
├── .dockerignore         # Docker ignore file
└── templates/            # HTML templates
    ├── base.html         # Base template
    ├── index.html        # Homepage
    └── login.html        # Login page
```