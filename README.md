# Bot-for-Excess
A bot made for the Twitch Streamer Excess on Twitch.
Discord Bot
A simple Discord bot built with Discord.js and the Twitch API.

This code is for a Discord bot that listens for member updates and checks if a user's account creation date matches the current date. If it does, the bot assigns the "Birthday" role to the user for 24 hours.

The code sets up a client using the Discord.js library and specifies the required intents for the bot to work. The "ready" event is listened for and when the bot is ready, it logs in the console.

The "guildMemberUpdate" event is also listened for, and whenever a member updates, the bot checks if the old and new members are not bots, then it looks for the "Birthday" role. If the user's account creation date matches the current date, the bot assigns the "Birthday" role to the user and removes it after 24 hours.

Finally, the bot logs in to Discord using the provided token.

Features
Fetch the status of a Twitch user
Send a message to Discord when the Twitch user goes online
Requirements
Node.js v12+
Discord account and a Discord bot token
Twitch API client ID
Setup
Clone this repository
Run npm install to install dependencies
Copy .env.example to .env and fill in the values for DISCORD_TOKEN and TWITCH_CLIENT_ID
Start the bot with npm start
Usage
Type !twitch in a Discord channel to check the status of the Twitch user
Contributions
Contributions are welcome! If you find a bug or have an idea for a new feature, feel free to open an issue or submit a pull request.
