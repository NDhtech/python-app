# Python Status Service

A lightweight Python Flask service that exposes basic status and health endpoints.

## Endpoints

### GET /
Returns application metadata.

### GET /health
Health check endpoint.

## Environment Variables

| Variable     | Description                 | Default        |
|--------------|-----------------------------|----------------|
| APP_NAME     | Application name            | python-status-service |
| APP_ENV      | Runtime environment         | development    |
| APP_VERSION  | Application version         | 1.0.0          |
| PORT         | Port the app listens on     | 5000           |

## Running Locally

```bash
pip install -r requirements.txt
python app.py

