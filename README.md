# Quote API (FastAPI + Docker)

## Run Locally (with Docker)
```bash
docker build -t quote-api .
docker run -d -p 8000:8000 quote-api
```

## Test the API
- http://localhost:8000/
- http://localhost:8000/quote

- # 🚀 Quote API - Dockerized FastAPI App

This is a simple FastAPI-based quote API that returns a quote via REST endpoints.  
The entire app is dockerized using a custom Dockerfile and runs on port `8000`.

---

## 📦 Tech Stack

- Python 3
- FastAPI
- Docker

---

## 🚀 Run Locally with Docker

```bash
# Clone the repo
git clone https://github.com/Ashish-Sharma54/Quote-API-Dockerized-FastAPI-App-.git
cd Quote-API-Dockerized-FastAPI-App-

# Build Docker image
docker build -t quote-api .

# Run the container
docker run -d -p 8000:8000 quote-api

