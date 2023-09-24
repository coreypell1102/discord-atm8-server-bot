# Welcome To my Discord Server Admin Bot Series! #

This is just one of my discord bots that are used to manage ec2 instances remotely through the use of a discord bot!

For this specific code, the bot is managing an ec2 instance running an ATM8 modded minecraft server



# Setup #

For the setup up you will need node.js and npm installed
Simply follow the commands below to get set up

1. mkdir /opt/atm8 && cd /opt/atm8

2. git clone https://github.com/coreypell1102/discord-amt8-server-bot.git
   
3. mv discord-atm8-server-bot/* ./ && rm -rf discord-atm8-server-bot
   
4. run 'npm install' to install dependencies
   
5. mv server/atm8.service /ect/systemd/system
   
6. systemctl deamon-reload
   
7. systemctl enable atm8
   
8. systemctl start atm8



# Bot Commands #

1. !start-atm8 - Starts the ATM8 Minecraft Server

2. !stop-atm8 - Stops the ATM8 Minecraft Server

3. !restart-atm8 - Restarts the ATM8 Minecraft Server

4. !status-atm8 - Returns the state of the ATM8 Minecraft Server

5. !help-atm8 - Lists available commands

