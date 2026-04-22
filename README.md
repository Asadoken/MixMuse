# MixMuse 🎛️

MixMuse is an AI-powered DJ app that transforms your personal music library into professional-quality DJ sets and mashups — no experience required.

Connect your Spotify or Apple Music account, choose a vibe, and let the AI handle beatmatching, harmonic mixing, energy flow, and transitions. From 10-minute warm-ups to 1-hour festival sets, MixMuse makes anyone feel like a DJ.

## Features

- **AI DJ Set Generator** — builds full sets from your liked songs, playlists, or recently played tracks, optimised by BPM, key, energy, mood, and genre
- **Mashup Lab** — pick 2–4 tracks and get an AI compatibility score, then generate mashup concepts with vocal/instrumental blending suggestions
- **Smart Transitions** — beatmatching, harmonic mixing, EQ fades, loop blends, hard drops, and vocal blending
- **Mix Modes** — House Party, Late Night Drive, Gym, Chill Sunset, Afro Mix, Amapiano, R&B Slow Jam, Festival Set, Surprise Me
- **Set Lengths** — 10, 30, 45, or 60 minutes
- **Live Deck Preview** — animated waveform, BPM arc, track order, key info, and transition map
- **AI Chat** — ask MixMuse AI anything about your mix, mashup compatibility, or music theory
- **Library** — save sets, mashups, and exports; view your taste profile and top genres

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript (mobile-first, dark-mode UI)
- **AI:** Anthropic Claude API (`claude-sonnet-4-20250514`) for real-time DJ advice and mashup analysis
- **Music Data:** Spotify Web API and Apple Music API for library import and track metadata
- **Audio Intelligence:** BPM detection, key analysis, energy mapping, and structure detection (intro/chorus/outro)

## Getting Started

1. Clone the repository
```bash
   git clone https://github.com/your-username/mixmuse.git
   cd mixmuse
```

2. Add your API keys to a `.env` file
