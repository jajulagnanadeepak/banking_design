# Deployment Guide

## Local Development

Start backend

```
cd backend
npm install
npm run build
npm start
```

Start frontend

```
cd frontend
npm install
npm start
```

## Docker Deployment

Build containers

```
docker-compose up --build
```

## Future Deployment

Planned deployment architecture:

Frontend → Load Balancer → Kubernetes → Backend → PostgreSQL
