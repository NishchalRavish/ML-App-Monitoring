# ML App Monitoring

This repository contains an ML application designed for continuous monitoring using Grafana, Prometheus, and FastAPI. The project leverages Docker to containerize the services and facilitate easy deployment and management of the ML Application.

## Features

- **FastAPI**: Serves the ML application and provides endpoints for metrics.
- **Prometheus**: Collects and stores metrics from the FastAPI application.
- **Grafana**: Visualizes the metrics collected by Prometheus, providing insightful dashboards.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Docker
- Docker Compose

### Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/NishchalRavish/ML-App-Monitoring.git
   cd ML-App-Monitoring

# Usage

After running `docker-compose up`, you can access the services as follows:

- **FastAPI Application**: [http://localhost:8005](http://localhost:8005)
- **Prometheus Dashboard**: [http://localhost:9090](http://localhost:9090)
- **Grafana Dashboard**: [http://localhost:3000](http://localhost:3000)

## Stopping the Application

To stop the application, use:

```bash
docker-compose down

