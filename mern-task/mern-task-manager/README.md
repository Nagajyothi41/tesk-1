
# MERN Task Manager

## Features
- Create tasks
- Update tasks
- Delete tasks
- Filter by completed/pending

## Tech Stack
- MongoDB
- Express.js
- React.js
- Node.js

## Run Without Docker

### Backend
```bash
cd backend
npm install
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm start
```

## Run With Docker
```bash
docker-compose up --build
```

## API Endpoints
- GET /api/tasks
- POST /api/tasks
- PUT /api/tasks/:id
- DELETE /api/tasks/:id
