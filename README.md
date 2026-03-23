# VisionAid JARVIS

> Free AI-powered visual assistant for visually impaired people.
> No API key. No cost. No account needed.

Features:
- Real-time object detection (80+ objects, COCO-SSD + TensorFlow.js)
- GPS turn-by-turn voice navigation (OpenStreetMap + OSRM — free)
- ASL sign language — full A-Z, both hands (MediaPipe)
- JARVIS AI assistant — smart local engine, no API needed
- Continuous voice input and text-to-speech
- Real-time obstacle warnings

Everything runs in the browser. No server. No API keys. Completely free.

---

## Deploy to Vercel (3 minutes, zero cost)

### Option A — GitHub + Vercel (recommended)

Step 1 — Push to GitHub
1. Create a free account at github.com
2. Click New repository — name it visionaid-jarvis
3. Upload all files from this folder (drag and drop on GitHub)
4. Click Commit changes

Step 2 — Deploy on Vercel
1. Go to vercel.com — sign up free with your GitHub account
2. Click Add New > Project
3. Select your visionaid-jarvis repository
4. Click Deploy

Done! Live in 60 seconds at https://visionaid-jarvis.vercel.app
No environment variables. No API keys. Nothing else to configure.

---

### Option B — Netlify Drop (fastest)
1. Go to netlify.com/drop
2. Drag the public/index.html file onto the page
3. Your app is instantly live

---

## Cost breakdown

- Vercel hosting: FREE (Hobby plan)
- TensorFlow.js + COCO-SSD: FREE (open source)
- MediaPipe Hands: FREE (open source, Google)
- OpenStreetMap + OSRM routing: FREE (open source)
- Web Speech API: FREE (built into browser)
- JARVIS AI responses: FREE (runs locally in browser)
- Total: $0.00

---

## Local development

  cd public
  python -m http.server 8080
  # Open http://localhost:8080

Built for accessibility. Designed for independence. Free forever.
