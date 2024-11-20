# Flask URL Shortener

A simple URL shortener web application built with Flask. This project demonstrates the use of Flask for web development, SQLite for database management, and Hashids for generating unique shortened URLs.

## Features

- Shorten any URL with ease.
- Redirect shortened URLs to their original destination.
- View statistics for all shortened URLs, including:
  - Number of clicks.
  - Date and time of creation.
  - Original and shortened URLs.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Python 3.7 or higher
- Pip (Python package manager)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/saipraneeth-yamagani/FLASK-PROJECT-1.git
   cd FLASK-PROJECT-1


### Project Structure
``graphql
Copy code
FLASK-PROJECT-1/
│
├── app.py              # Main Flask application
├── database.db         # SQLite database file (auto-created)
├── templates/
│   ├── index.html      # Template for URL shortening
│   └── stats.html      # Template for statistics
├── static/             # Optional: For static assets like CSS or JS
└── README.md           # Project documentation
