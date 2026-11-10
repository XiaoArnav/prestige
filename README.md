# Prestige 🫀

> Real-time human-sensing application powered by the [Presage SmartSpectra SDK](https://smartspectra.presagetech.com/docs).
> Built for the [Presage SmartSpectra SDK Challenge on DEV](https://dev.to/challenges/presage-2026-11-04).

## Overview

Prestige is an adaptive experience responding to live physiological signals captured through an ordinary camera using Presage Technologies' SmartSpectra SDK (including pulse, respiration, heart rate variability, and facial micro-expressions).

## Prerequisites

- Node.js (v18+ recommended)
- A webcam / camera feed
- Presage API Key (from [Presage Physiology Portal](https://physiology.presagetech.com/auth/register))

## Getting Started

```bash
# Clone the repository
git clone https://github.com/XiaoArnav/prestige.git
cd prestige

# Install dependencies (once set up)
npm install

# Run the app
npm run dev
```

## Data Handling & Privacy

In strict accordance with the challenge rules:
- **No Covert Surveillance**: Camera capture is opt-in, clearly indicated with visible status indicators.
- **No Clinical Diagnosis**: This project does not provide medical diagnosis, treatment, or clinical recommendations.
- **Privacy First**: Raw video frames are processed locally/client-side and never stored or shared without user consent.

## License

MIT
