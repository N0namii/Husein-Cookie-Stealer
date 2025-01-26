# Husein-Cookie-Stealer
This script is designed to extract and collect sensitive browser data such as saved passwords and cookies from multiple browsers (Chrome, Firefox, Edge, Opera, Vivaldi, Brave), package the information into a ZIP archive, and send it to a Telegram bot.


Features
Extracts saved passwords from Chrome, Firefox, Opera, Vivaldi, Brave, and Edge browsers.
Retrieves cookies from Chrome, Firefox, and Edge browsers.
Packages the collected data into a ZIP archive.
Sends the data via Telegram bot for remote access.
Supported Browsers
Google Chrome
Mozilla Firefox
Microsoft Edge
Opera
Vivaldi
Brave
Setup
Install dependencies:

Make sure you have the required libraries installed. You can install them via pip:

bash
Копировать
pip install pywin32 requests pycryptodome
Telegram Bot Configuration:

Create a Telegram bot using BotFather.
Replace the bot_token and chat_id in the script with your bot’s token and chat ID where you want to receive the data.
How to Use
Clone or download the repository.

Run the script on a Windows machine with the browsers installed.

The script will:

Extract passwords and cookies from the browsers.
Save them in the output folder.
Create a ZIP file containing the collected data.
Send a notification and the ZIP file to your Telegram chat.
To execute the script:

bash
Копировать
python husein.py
Important Notes
This script is for educational purposes only.
Using this script to access or extract data from someone else's browsers without permission is illegal and unethical.
Ensure you have the proper authorization before running the script on any machine.
Disclaimer
By using this tool, you assume full responsibility for its use. The author is not responsible for any damage or legal consequences resulting from the use of this script.
