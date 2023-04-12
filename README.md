# PapayaCoders_Telegram_Chatgpt_Bot
#First clone Repo
# Have Node install in System min V-9
# Now Change Config/default.json Token and Key
# After that Run Command

Support for both browserless (official, unofficial) and browser-based APIs
Support for both private and group chats
Work in privacy mode (the bot can only see specific messages)
Bot access control based on user and group IDs
Reset chat thread and refresh session with command
Queue messages to avoid rate limit
Typing indicator, Markdown formatting, ...
Cloudflare bypassing and CAPTCHA automation (for the browser-based API)
Customize bot identity and behavior (by setting api.official.systemMessage)
User-friendly logging

Start the server
Option 1: Node
To get started, follow these steps:

Clone this project.
Create local.json under the config/ folder. You can copy the config/default.json as a template.
Modify the local.json following the instructions in the file. The settings in local.json will override the default settings in default.json.
Set api.type to official if you want to use the browserless official API. Then provide your OpenAI API Key and other settings. You can refer to this for more details. Note that this will cost your credits.
Set api.type to unofficial if you want to use the browserless unofficial API. Then provide your OpenAI access token (how to get your access token?) and other settings. You can refer to this for more details.
Set api.type to browser if you want to use the browser-based API (not recommended). Then provide the OpenAI / Google / Microsoft credentials and other settings. You can refer to this and this for more details. Make sure you have a Chromium-based browser installed.
Then you can start the bot with:

pnpm install
pnpm build && pnpm start

Credits
ChatGPT API: Node.js client for the unofficial ChatGPT API.
ChatGPT: ChatGPT API for Python.
Node.js Telegram Bot API: Telegram Bot API for NodeJS.
🤖️ chatbot-telegram: Yet another telegram ChatGPT bot.
