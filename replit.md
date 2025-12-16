# Winamp Clone - Classic Player

## Overview
A standalone classic Winamp-style music player built with Vite + Svelte using the webamp library. This project recreates the authentic Windows XP Winamp experience and is designed for easy integration into other SvelteKit applications.

## Current State
- Fully functional Winamp player with classic skin
- Main player, equalizer, and playlist windows
- Sample playlist with multiple tracks
- Draggable windows
- Volume, play/pause, stop, next/previous controls

## Project Structure
```
/
├── index.html          # Main HTML entry point
├── package.json        # Dependencies and scripts
├── vite.config.js      # Vite configuration
├── svelte.config.js    # Svelte configuration
├── src/
│   ├── main.js         # App entry point
│   ├── App.svelte      # Main app component
│   └── lib/
│       └── WebampPlayer.svelte  # Webamp player component
└── INTEGRATION_GUIDE.md         # Guide for SvelteKit integration
```

## Key Dependencies
- webamp: ^2.2.0 - The Winamp 2 reimplementation library
- vite: ^5.4.2 - Build tool
- svelte: ^4.2.18 - Component framework

## Running the Project
```bash
npm run dev    # Development server on port 5000
npm run build  # Production build
```

## Integration Notes
See INTEGRATION_GUIDE.md for step-by-step instructions on integrating this player into a SvelteKit Windows XP themed portfolio.
