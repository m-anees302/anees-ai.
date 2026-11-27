# ANEES AI

A responsive AI chat interface built with HTML, CSS and JavaScript, plus a small Node.js backend that keeps your API key private.

## What works
- Real AI replies through the backend
- Multiple conversations saved in this browser
- New chat, chat history and clear current chat
- Copy AI responses
- Dark/light theme and settings
- Prompt suggestions, typing indicator and mobile sidebar

## Run it

You need Node.js installed on your computer.

1. Extract the ZIP and open a terminal in this folder.
2. Install dependencies:

   ```bash
   npm install
   ```

3. Make a copy of `.env.example` named `.env`.
4. Open `.env` and replace `your_api_key_here` with your own OpenAI API key. Keep this file private.
5. Start the app:

   ```bash
   npm start
   ```

6. Open **http://localhost:3000** in your browser.

## Important security notes
- Do not put your API key in `app.js`, `index.html`, or any frontend file.
- Do not upload your `.env` file or share it publicly.
- For a public deployment, host the Node backend on a server, set `OPENAI_API_KEY` in the host's environment-variable settings, and serve the frontend from that same app/domain.
- Add authentication, rate limiting and usage limits before opening a public service to everyone. The starter project is intended for local development.

## Customise
- Change colours and layout in `style.css`.
- Change the welcome text and branding in `index.html`.
- Change the assistant's behaviour and model in `server.js` / `.env`.
