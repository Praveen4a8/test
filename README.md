# Basic Python Project

A minimal Flask app with Docker support.

## Run locally

```bash
pip install -r requirements.txt
python app.py
```

## Run with Docker

```bash
docker build -t basic-python-app .
docker run -p 5000:5000 basic-python-app
```

Visit http://localhost:5000
