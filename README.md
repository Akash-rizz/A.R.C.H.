# A.R.C.H. — Autonomous Reasoning & Command Hub

A complete no-API-key static 3D command-center website designed to run on GitHub Pages.

## What this build includes

- Real Three.js/WebGL 3D space interface
- Central A.R.C.H. core with orbiting modules
- CHAT, CODE, PROJECTS, TASKS, MEMORY, TOOLS, RESEARCH and ANDROID modules
- Touch/mouse 3D navigation
- Mobile-first glass HUD
- Local command router
- Safe calculator
- Local date/time
- Browser-local memory using localStorage
- Voice input when the browser supports SpeechRecognition
- Runtime/session indicators
- No server
- No API key
- No database
- No login
- No paid service required

## Important

This is a genuinely working local command hub, but it is **not pretending to be a cloud LLM**. Without an AI model/backend, it cannot produce unrestricted generative answers like ChatGPT.

The site loads Three.js from jsDelivr, so the 3D engine needs an internet connection. The application itself does not need an API key.

## GitHub Pages

1. Create a new **public** GitHub repository.
2. Upload `index.html`.
3. Open **Settings → Pages**.
4. Under the publishing/source option, choose the `main` branch and `/ (root)`.
5. Save and wait for GitHub Pages to publish.

You can also rename `index.html` only if you understand that GitHub Pages needs an entry page at the published root.

## Example commands

help
calculate 25*18
time
date
remember I like astronomy
memories
forget all
status
open code
open memory

## Future upgrade path

A real generative agent can be connected later through:
- a secure backend/model provider, or
- a genuinely local on-device/browser model where the target phone can handle it.

Do not put a private API key directly into a public GitHub Pages JavaScript file.
