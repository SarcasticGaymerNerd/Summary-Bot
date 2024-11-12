# Discord Chat Summarization Bot

This is a simple Discord bot that reads messages from a specified channel and generates a summary of those messages for a selected date and time range.

## Features

- Summarizes messages in a Discord channel based on user-defined date and time range.
- Easy to set up and use with minimal configuration.

## Prerequisites

Before you begin, ensure you have the following:

- Python 3.6 or higher installed on your machine.
- A Discord account and a server where you can add your bot.
- The `discord.py` library installed.

## Installation

1. **Clone the repository** (if applicable):
   ```bash
   git clone https://github.com/SarcasticGaymerNerd/Summary-Bot.git
   cd discord-chat-summarization-bot
   ```

2. **Install the required library**:
   ```bash
   pip install discord.py
   ```

3. **Set up your Discord bot**:
   - Go to the [Discord Developer Portal](https://discord.com/developers/applications).
   - Create a new application and add a bot to it.
   - Copy the bot token for later use.
   - Ensure your bot has the necessary permissions to read messages in the channel.

## Usage

1. **Edit the script**:
   - Open the script file and replace `'YOUR_BOT_TOKEN'` with your actual Discord bot token.

2. **Run the bot**:
   ```bash
   python your_script_name.py
   ```

3. **Use the summarize command**:
   In your Discord channel, type the following command to summarize messages:
   ```
   !summarize YYYY-MM-DD HH:MM YYYY-MM-DD HH:MM
   ```
   Replace the date and time with your desired range. For example:
   ```
   !summarize 2023-10-01 12:00 2023-10-01 14:00
   ```

## Example

If you want to summarize messages sent between 12:00 and 14:00 on October 1, 2023, you would type:
