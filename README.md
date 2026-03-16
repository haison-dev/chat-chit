# realtime-chat

Realtime chat application with friend requests, direct and group messaging, and modern UI components.

<div style="display: flex; gap: 10px;">
  <img width="49%" src="https://github.com/user-attachments/assets/08400f08-3f19-496f-b56f-8e054c3788a4" />
  <img width="49%" src="https://github.com/user-attachments/assets/76c10ea3-af74-4674-a7be-99c2a036c0ba" />
</div>



## Overview
`realtime-chat` is a full‑stack real‑time messaging app that supports user authentication, friend requests, direct conversations, group chats, and live presence updates. The frontend is built with React + Vite, while the backend uses Node.js with Socket.IO and MongoDB.

## Features
- Real‑time messaging via Socket.IO
- Direct and group conversations
- Friend request workflow (send / receive / accept / decline)
- User search and profiles
- Responsive UI with Radix UI + Tailwind CSS
- Message history and infinite scroll

## Tech Stack
**Frontend**
- React, TypeScript, Vite
- Zustand for state management
- Radix UI + Tailwind CSS

**Backend**
- Node.js, Express
- Socket.IO
- MongoDB (Mongoose)

## Project Structure
```
backend/    # API, socket server, database models
frontend/   # React app
```

## Getting Started
### Prerequisites
- Node.js 20+
- MongoDB running locally or via a hosted instance

### Setup
1. Install dependencies
```
cd backend
npm install

cd ../frontend
npm install
```

2. Configure environment variables
Create a `.env` file in `backend/` with your MongoDB connection string and required secrets.

3. Run the app
```
# backend
cd backend
npm run dev

# frontend
cd ../frontend
npm run dev
```

## Scripts
**Backend**
- `npm run dev` – start API + socket server

**Frontend**
- `npm run dev` – start Vite dev server
- `npm run build` – build for production
- `npm run preview` – preview production build

## Roadmap
- Message reactions and editing
- File uploads
- Read receipts

## License
MIT
