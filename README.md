<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your app (TEST)

This repository contains everything you need to run the app locally and deploy to the TEST environment.

## Deploy target

- **Environment:** TEST
- Set `GEMINI_API_KEY` and `APP_URL` for your TEST deployment (see `.env.example`).

## Run Locally

**Prerequisites:** Node.js

1. Install dependencies:
   `npm install`
2. Create a local `.env` file from `.env.example` and set your keys:

   Copy the example:

   ```bash
   cp .env.example .env
   ```

   Edit `.env` and set `GEMINI_API_KEY` (and `APP_URL` if needed):

   ```env
   GEMINI_API_KEY=your_real_gemini_api_key_here
   APP_URL=http://your-test-app.example.com
   ```

   Note: `.env` is ignored by git by default.
3. Run the app:
   `npm run dev`
