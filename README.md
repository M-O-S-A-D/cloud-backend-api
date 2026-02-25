# Cloud Backend API

## Overview
The Cloud Backend API acts as the central control plane of the Smart Surveillance System.

It processes incoming edge events, stores metadata and embeddings, provides search capabilities, and exposes secure endpoints for the administrative dashboard.

## Core Responsibilities
- Authentication & authorization
- Event ingestion
- Face embedding storage and indexing
- Search & filtering APIs
- Identity tracking
- Audit logging
- Admin management endpoints

## Why This Service Exists
This service centralizes system intelligence and enables:

- Horizontal scalability
- High availability
- Secure role-based access control
- Fast event retrieval
- Integration with cloud-native services

It decouples business logic from both edge processing and frontend presentation.

## Technology Stack
- Python (FastAPI) or Node.js
- PostgreSQL (RDS)
- Redis (caching)
- OpenSearch / Elasticsearch
- AWS S3 (media storage)
- Docker

## Deployment
- AWS ECS / EC2 / Lambda
- Load balanced architecture
- Auto-scaling enabled

## Future Improvements
- Real-time event streaming (WebSockets)
- Advanced analytics pipelines
- Multi-tenant support
