# Python 3 interval discord bot

Interval discord bot that sends custom messages to select discord server's channel at a defined time interval.


## DEPENDENCIES

``
apt-get install python3
``

``
apt-get -y install python3-pip
``

``
python3 -m pip install discord.py==0.16.12
``

## HOW TO USE

- Go to https://discordapp.com/developers/applications/
- Create an application
- Go to 'Bot' section of discordapp.com/developers portal from the menu and add new bot
- Get a bot token and add it to TOKEN value inside intervalbot.py file
- Go to 'Auth' section of discordapp.com/developers portal and mark the checkbox 'bot' to generate an invite link for your new bot. 
- Visit that generated link to invite your bot to your Discord server.
- INSIDE DISCORD APP: right click on your Discord server's channel where you want the messages to display and then add it as a value for CHANNEL in the intervalbot.py file.

## HOW TO RUN

# python3 intervalbot.py