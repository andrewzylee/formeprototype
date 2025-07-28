# Formé

> An app that integrates your calendar to give you 1-3 prompts a day to move you toward a health/wellness goal

## Overview

Formé bridges the gap between wellness data and actionable steps by providing context-aware wellness nudges that fit seamlessly into your existing schedule. Instead of generic advice, Formé delivers personalized prompts like: "You've got 18 minutes free between meetings. Here's a breathwork prompt to reduce cortisol - right now."

## Target Audience

Busy working women (28-45) who value wellness but struggle with time constraints and decision fatigue.

## Key Features

- **Calendar-Aware Smart Timing**: Detects free slots and matches them with appropriate wellness prompts
- **Goal-Based Personalization**: Tailored prompts based on wellness focus (Sleep, Energy, Focus, Stress, Body)
- **Non-Generic Prompts**: Specific, actionable guidance rather than vague advice
- **Trust-First Privacy**: Minimal calendar data access with clear transparency

## Tech Stack

- **Frontend**: Next.js with React, TypeScript, shadcn/ui
- **Backend**: Firebase Functions, Vercel API Routes
- **Database**: Firestore (user data) + Supabase (content library)
- **Calendar**: Google Calendar API (OAuth 2.0)
- **Push Notifications**: Firebase Cloud Messaging

## Project Structure

```
/Forme/
├── frontend/          # Next.js web application
├── backend/           # Serverless functions and API
├── content/           # Wellness prompts and static content
├── infrastructure/    # Cloud service configurations
├── scripts/           # Utility scripts
└── docs/             # Project documentation
```

## Quick Start

### Prerequisites
- Node.js 18+
- npm or pnpm
- Firebase CLI
- Supabase CLI

### Development Setup

1. **Clone and install dependencies**
   ```bash
   git clone [repository-url]
   cd Forme
   npm install
   ```

2. **Start development server**
   ```bash
   npm run dev
   ```

3. **Environment Setup**
   Copy `.env.example` files in each workspace and configure with your API keys.

## Development

- `npm run dev` - Start frontend development server
- `npm run build` - Build all workspaces
- `npm run lint` - Run linting across all workspaces
- `npm run test` - Run tests across all workspaces

## Color Palette

- **Lavender**: Calming accent color
- **Sage Green**: Natural, grounding tones
- **Sand**: Warm, neutral base
- **Rounded corners**: 12-16px radius for soft, approachable UI

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for development guidelines.

## License

MIT - See [LICENSE](./LICENSE) for details. 