# Stock Market Education and Analysis Platform

A complete full-stack stock market learning platform with market dashboards, quizzes, user progress tracking, blog content, admin management, and an OpenAI-powered chatbot assistant.

## Stack

- Frontend: React + Vite + React Router + Recharts + Framer Motion
- Backend: Node.js + Express + MongoDB + JWT
- AI: OpenAI Chat Completions API
- Market data: Alpha Vantage by default with a Yahoo Finance compatible service fallback layer

## Project Structure

- `frontend/` React application
- `backend/` Express API

## Quick Start

1. Install dependencies:

```bash
npm install
```

2. Create environment files:

- Copy `backend/.env.example` to `backend/.env`
- Copy `frontend/.env.example` to `frontend/.env`

3. Run development mode:

```bash
npm run dev
```

## Core Features

- JWT authentication with protected routes
- Course modules from beginner to advanced
- Quiz engine and score tracking
- Blog and news content
- Live stock dashboard with charts and quote search
- AI chatbot with persistent per-user history
- User dashboard with progress, badges, scores, and notifications
- Admin content management endpoints and UI
- Dark mode and responsive layout

## Environment Variables

See `backend/.env.example` and `frontend/.env.example`.
