# FitFlow Redesign

FitFlow Redesign is the technology and architecture proposal prepared for  
**IT3060 – Human Computer Interaction | Lab Exercise 05**.

The system is designed to support Android, iOS, and Web platforms with high performance, secure health-data handling, real-time features, and AI-based personalization.

## Proposed Technology Stack

- Frontend: Flutter
- Core Backend: NestJS / TypeScript
- AI Service: FastAPI / Python
- Database: PostgreSQL
- Cache: Redis
- Authentication: AWS Cognito
- Realtime: NestJS WebSockets
- Object Storage: AWS S3 or equivalent

## Main Features

- Personalized workout recommendations
- Nutrition tracking
- Fitness progress tracking
- Social sharing
- Real-time updates
- Secure authentication and authorization

## Repository Structure

- `frontend/` – Flutter application
- `backend/` – NestJS backend API
- `ai-service/` – FastAPI AI/recommendation service
- `docs/` – Technology comparisons, decision matrix, architecture and ADR

## Documentation

The `docs/` directory contains:

- Frontend technology comparison
- Backend, database and authentication comparison
- Weighted technology decision matrix
- High-level system architecture
- Architecture Decision Record (ADR)

## Security

FitFlow is designed with:

- Secure authentication
- Role-based authorization
- TLS encrypted communication
- Secure health-data handling
- Data minimization
- Audit logging
- GDPR/HIPAA-related security considerations
