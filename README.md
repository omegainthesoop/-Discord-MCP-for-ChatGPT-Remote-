#🧠 Discord MCP for ChatGPT (Remote)

Run your Discord companion 24/7 without needing your laptop.

This repo converts a local MCP Discord server into a remote MCP server compatible with ChatGPT's MCP beta.

##✨ Requirements

Discord account

GitHub account

Railway account

ChatGPT MCP access

##🤖 Step 1 — Create a Discord Bot

Go to:

https://discord.com/developers/applications

Click New Application

Name it

Go to Bot

Click Add Bot

Copy the Bot Token

##🔑 Enable Intents

Enable:

Server Members Intent

Message Content Intent

##🔗 Invite Bot to Server

Go to:

OAuth2 → URL Generator

Scopes:

bot

Permissions:

Send Messages
Read Messages/View Channels

Invite the bot to your server.

##🚀 Step 2 — Deploy to Railway

Go to:

https://railway.app

New Project

Deploy from GitHub

Select this repo

##🔐 Add Environment Variables

Railway → Variables:

DISCORD_TOKEN=your_token_here

##🌐 Step 3 — Get MCP Endpoint

After deploy:

https://your-app.up.railway.app/sse

##🧩 Step 4 — Connect in ChatGPT

ChatGPT → New MCP App:

Server URL:

https://your-app.up.railway.app/sse

Authentication:

None

Done.

Your companion is now online 24/7 in Discord
No laptop required.
