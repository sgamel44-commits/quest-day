# ✨ Quest Day

A gamified daily todo tracker with XP, sticker packs, streaks, and daily prize stickers.

## Features
- 📋 Build custom daily task categories with XP values
- ⚡ XP bar + rank system (Rookie → GOAT)
- 🎁 Sticker packs that unlock as you hit goals (Dino, Crystal Cave, NYC, Seattle, Denver, Flowers, Ocean, Foodie, Animals, Streak)
- 🫧 Blob collection — earns every 3 tasks
- 🏆 Daily big sticker (blurred teaser → unlocks on max XP)
- 🔥 Streak tracking
- 📅 History log
- 💾 Save/restore via encoded save code
- 🗂️ Task templates

## Hosting on Netlify (via GitHub)

1. Push this folder to a GitHub repo
2. Go to [netlify.com](https://app.netlify.com)
3. Click **Add new site → Import an existing project**
4. Connect GitHub → select your repo
5. Build settings: leave blank (no build command, publish directory = `/`)
6. Click **Deploy site**

Done! You'll get a free `yoursite.netlify.app` URL.

## Local development

Just open `index.html` in any browser — no build step needed.

## Saving progress

Since this is a single HTML file, progress saves to your **browser's localStorage** automatically.  
Use the **💾 save** button in the Stickers page to generate a save code you can paste into any browser to restore your collection.
