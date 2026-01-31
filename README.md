# AI Voice Assistant Agent

A complete live AI voice assistant with real-time speech-to-speech conversation.

## Features

- **Real-time voice chat** — Speak and get instant voice responses
- **Natural interruptions** — Talk over the assistant anytime
- **Live transcript** — See your conversation in real time
- **Modern UI** — Clean, responsive design with status indicators

## Quick Start

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Add your OpenAI API key**
   ```bash
   cp .env.example .env
   ```
   Edit `.env` and add: `OPENAI_API_KEY=sk-your-key`

3. **Run locally**
   ```bash
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173)

## Deploy (Live Link)

### Vercel
```bash
npm i -g vercel
vercel
```
Add `OPENAI_API_KEY` in Vercel dashboard → Settings → Environment Variables.

### Render
1. Push to GitHub
2. Go to [render.com](https://render.com) → New Web Service
3. Connect repo, add `OPENAI_API_KEY`, deploy

## Tech Stack

- **OpenAI Realtime API** — GPT-4o voice model
- **OpenAI Agents SDK** — RealtimeSession, WebRTC
- **Vite + TypeScript** — Frontend
- **Express** — Backend token generation
