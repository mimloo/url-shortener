# Mimloo Campaign Link Builder
 
Internal tool for creating tracked campaign URLs with clean short links via [Short.io](https://short.io).
 
## Setup
 
1. Enable GitHub Pages on this repo (Settings → Pages → Source: `main`, folder: `/ (root)`)
2. Open the deployed page
3. Click ⚙ → enter your Short.io API key and custom domain (e.g. `link.mimloo.com`)
4. Start building links
 
## How it works
 
Fill in the UTM fields → hit **Create Short Link** → copy the clean URL. Shopify picks up the UTM params automatically in Analytics.
 
API key is stored in your browser's localStorage — never committed to the repo.
 
## Tip
 
Scope your Short.io API key to **create links only** for extra safety.
