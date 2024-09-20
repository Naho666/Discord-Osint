# Discord-Osint
created by naho



This tool is designed to gather Open Source Intelligence (OSINT) from Discord user profiles and their connected accounts. It leverages the Discord API and various other platform APIs to collect and organize information.

# Features

Retrieve Discord user profile information
Gather data from connected accounts (Steam, GitHub, YouTube, Spotify, Twitter, Twitch, PlayStation)
Extract emails and links from user bios
Collect usernames, friends lists, and miscellaneous information from various platforms
Export data in both TXT and JSON formats


# Usage
To use the tool, run the script with the following command:

python script_name.py  [options]
Arguments:
discord_user_id: The Discord ID of the user to scrape (required)
Options:
-f, --file: The file name to export to (default: "data")
-t, --token: The Discord token to use for authentication
-o: Output file (can be .json or .txt)
Example
python discord_osint.py 123456789 -o output.txt -t "your_discord_token_here"


# Disclaimer
This tool is for educational and research purposes only. Ensure you have the necessary permissions and comply with the terms of service of all platforms before using this tool. The authors are not responsible for any misuse or damage caused by this tool.
