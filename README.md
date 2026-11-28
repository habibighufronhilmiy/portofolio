# Portofolio — Habibi Ghufron Hilmiy

Personal portfolio site for Habibi Ghufron Hilmiy, a full-stack developer. Static HTML, CSS, and JavaScript with a canvas background, served from GitHub Pages or any static host.

## Projects

| Project | Description | AI integration |
| --- | --- | --- |
| **SiagaKU** | Flood risk and family readiness platform for DKI Jakarta (IT RUSH 2026) | AI risk explanations, RAG chatbot over official guidelines, AI photo verification for flood reports, multi-provider AI router (Gemini + Groq) |
| **Laravel Coffee Shop** | Coffee shop ordering and management system with admin and cashier panels | — |
| **SEKECAM** | Electronic complaint and aspiration system for sub-district offices | AI verification of complaint text and photos with Groq, with manual fallback |
| **S-Meals** | Flutter app for daily nutrition and meal budget tracking | AI nutrition chat, food-photo and label analysis, AI meal plans from ingredients |

## Structure

```
index.html          # Single-page site (markup, styles, scripts)
assets/images/      # Project, certificate, and achievement images
```

## Run locally

Open `index.html` directly, or serve the folder:

```bash
npx serve .
```

## Deploy

Push to `main`; the site is static and can be hosted on GitHub Pages, Vercel, or Netlify without a build step.

## Security

This repo contains no API keys or secrets. AI features in the listed projects run server-side or through a proxy; credentials are stored as environment variables/secrets, never in client code or this repository.
