# Quiz Master Frontend

A gamified quiz generator frontend built with React, TypeScript, and Tailwind CSS. Features a Duolingo-style interface with progress tracking, achievements, and audio feedback.

## Features

- 🎮 Gamified learning experience with XP, streaks, and achievements
- 🎨 Beautiful, responsive UI with animations
- 🔊 Audio feedback for correct/incorrect answers
- 📊 Progress tracking and statistics
- 🎯 5 difficulty levels per quiz topic
- 🌟 Modern React with TypeScript

## Tech Stack

- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + Shadcn/ui components
- **Animations**: Framer Motion
- **State Management**: TanStack Query
- **Forms**: React Hook Form + Zod validation
- **Routing**: Wouter

## Setup

1. Install dependencies:
```bash
npm install
```

2. Set up environment variables:
```bash
# Create .env file
VITE_API_URL=http://localhost:8000  # Your FastAPI backend URL
```

3. Start development server:
```bash
npm run dev
```

## Backend Connection

This frontend connects to the FastAPI backend. Update the API URL in `src/lib/queryClient.ts` to point to your backend deployment.

## Deployment

Build for production:
```bash
npm run build
```

Deploy the `dist` folder to any static hosting service like Vercel, Netlify, or GitHub Pages.