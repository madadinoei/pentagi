# Project Deployment Guide

## Prerequisites
- Docker
- Docker Compose

## Getting Started

Follow these steps in order to start the services:

### 1. Start Services
Run the following commands in your terminal:
```bash
# Start Graphiti
docker compose -f docker-compose-graphiti.yml up -d

# Start Observability
docker compose -f docker-compose-observability.yml up -d

# Start Langfuse
docker compose -f docker-compose-langfuse.yml up -d

# Start Main Application
docker compose -f docker-compose.yml up -d
