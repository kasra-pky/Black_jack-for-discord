# Discord Blackjack Bot

A fun and interactive Discord bot that allows users to play Blackjack with friends in a Discord server. The bot supports multiplayer gameplay, tracks player XP in an Excel file, and includes a user-friendly Tkinter GUI for entering the bot token.

## Features
- **Multiplayer Blackjack**: Start a game with the `/bj` command, allowing multiple players to join and play together.
- **Game Mechanics**: Supports all standard Blackjack rules, including:
  - **Hit**: Draw another card.
  - **Stand**: End your turn.
  - **Double Down**: Double your bet and take one more card (available on first two cards).
  - **Split**: Split a pair of same-value cards into two hands.
  - **Insurance**: Protect against a dealer's potential blackjack when their upcard is an Ace.
- **XP System**: Players earn XP based on game outcomes (3 XP for Blackjack, 2 XP for a win, 4 XP for successful insurance). Top players are displayed with `/bjrank`.
- **Interactive UI**: Uses Discord buttons for gameplay actions (Join, Start, Hit, Stand, etc.).
- **Tkinter GUI**: A simple graphical interface for entering the bot token, with connection status indicators:
  - "Waiting..." (gray) when connecting.
  - "Connected" (green) on successful connection.
  - "Connection Failed" (red) if the token is invalid, with automatic program closure after 5 seconds.
- **Commands**:
  - `/bj`: Start a new Blackjack game.
  - `/bjhelp`: Display game instructions and rules.
  - `/bjrank`: Show the top 10 players based on XP.

## Requirements
- nothing
- just run bj3.exe

**Create a Discord Bot and Obtain Its Token: Follow these steps to create a bot and get its token:**


Go to the Discord Developer Portal.https://discord.com/developers/applications

Click New Application, give it a name (e.g., "Blackjack Bot"), and click Create.
In the left menu, select Bot and click Add Bot, then confirm by clicking Yes, do it!.
Under the Token section, click Copy Token. Important: Keep this token private and never share it publicly.
In the Bot settings, enable the following Privileged Gateway Intents:
Presence Intent
Server Members Intent
Message Content Intent
Save changes.
Invite the Bot to Your Server:
In the Developer Portal, go to the OAuth2 > URL Generator section.
Select the bot scope and the applications.commands scope.
Under Bot Permissions, grant the following permissions:
Send Messages
Embed Links
Use Slash Commands
Copy the generated URL, paste it into your browser, and select your server to invite the bot.

## Note: 
- Be sure to give your bot invitation link to a chatbot like chat gpt and write in the prompt "This is a Discord bot invitation link. Change this link to apply permission 8, i.e. admin streamer."
