# Yoga Classes Management System

## Requirements

- node:20
- python:3.12

## Installation

1. Go to `frontend` and create a `.env`:

    ```dotenv
    VITE_SERVER_URL=http://localhost:5000
    ```

1. In the same folder, run:

    ```bash
    npm install
    ```

1. Go to `backend` and create a `.env`:

    ```dotenv
    FLASK_HOST=0.0.0.0
    FLASK_PORT=5000
    MONGODB_CONNECTION_STRING=your-mongodb-connection-string
    ```

1. In the same folder, run:

    ```bash
    python -m venv venv
    venv/Scripts/activate  # source venv/bin/activate for Unix-based OSes
    pip install -r requirements.txt
    ```

## Usage

1. Go to `backend` and run:

    ```bash
    .venv/Scripts/activate
    python src/server.py
    ```

1. Go to `frontend` and run:

    ```bash
    npm run dev
    ```

1. Go to `localhost:3000` to access the site.
