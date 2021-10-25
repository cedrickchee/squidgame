# Red Light, Green Light

![https://github.com/cedrickchee/squidgame/actions](https://github.com/cedrickchee/squidgame/workflows/CI/badge.svg)

Red Light, Green Light is a traditional Korean children's game, popularised by the Squid Game TV series.

This project is the digital remake of the game - a 2D-multiplayer game that you can just play in your desktop or mobile browser.

## Tech Stack

The plan:

- UI (frontend): core game logic develop using engine from the [Rust gamedev](https://gamedev.rs/) and glue together using TypeScript and WebAssembly
- Server (backend): Frontend talks to a simple WebSocket server running at the Edge (global CDN) such as Fly.io/Cloudflare Workers/Lambda/Cloud Run.

## Ideas

- Angry Birds 2 by Rovio - the game that went viral and reached 10 mil users in around three days.
