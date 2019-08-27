#A simple Slackbot that displays random inspiring techie quotes and jokes for developers/designers ⚡️ 

This bot is powered by the original inspireNuggets Chrome Browser Extension quotes and Chuck Norris Jokes API by Bolaji Ayodeji

#Setup

Install dependencies
npm install
npm start
Create a bot in Slack and generate and include your OAuth bot token

# Add this in your .env
BOT_TOKEN=YOUR_OWN_BOT_TOKEN
const bot = new SlackBot({
    token: `${process.env.BOT_TOKEN}`,
    name: 'YOUR_OWN_APP_NAME'
})
