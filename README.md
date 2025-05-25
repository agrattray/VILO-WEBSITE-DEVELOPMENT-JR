
# Vilo Design - Final Lead Form System

## What's Included
- Fully working contact form
- Stores leads in Upstash Redis
- Queues background tasks with Upstash Queue
- Sends email using Resend
- Includes .env.example and package.json

## Setup Steps
1. Create a `.env.local` from `.env.example` and add your actual keys
2. Run `npm install` to install all dependencies
3. Run `npm run dev` to start the dev server
4. Deploy to Vercel and add the same env vars in the project settings
