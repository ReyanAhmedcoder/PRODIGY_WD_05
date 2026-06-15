# SkyRead — Weather Dashboard

A responsive weather dashboard built as a static web page.

## Overview

- Single-page weather UI powered by Open-Meteo for demo mode.
- Supports location search, local geolocation, unit toggle, and dynamic weather themes.
- Includes animated sky, weather effects, and a modern glassmorphism layout.

## Usage

1. Open `index.html` in your browser.
2. For full OpenWeatherMap support, replace `YOUR_API_KEY_HERE` with your API key in `index.html`.

## Files

- `index.html` — main application and styles in a single file.
- `package.json` — project metadata and optional start script.
- `.gitignore` — ignores local and Node.js artifacts.

## Run locally

- Open `index.html` directly in a browser.
- Or run `npm install -g http-server` and then `npx http-server .` from this folder.
## Deploy to Vercel

This project is configured for static deployment on Vercel using `vercel.json`.

- `vercel.json` defines the static build and routes all traffic to `index.html`.
- `.vercelignore` excludes local files and packages from deployment.
- `package.json` includes optional `start` / `serve` scripts for local preview.

To deploy:

1. Run `vercel` in the repo root.
2. Confirm the project settings when prompted.
3. Visit the Vercel dashboard or the generated deployment URL.
