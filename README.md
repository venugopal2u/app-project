# Python Docker Application

A simple Flask application containerized with Docker.

## Setup

1. Build the Docker image:
```bash
docker build -t python-app .
```

2. Run the container:
```bash
docker run -p 5000:5000 python-app
```

3. Access the application at `http://localhost:5000`

## Development

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python app.py
```