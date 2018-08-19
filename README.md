# IP Sender Telegram Bot
Send your IP public address via a telegram bot.
## What is it used for?
Think you have dynamic IP and you are running a VNC Sever on your computer(Or SSH Server). You need your IP every time you reboot the router. This application will send your IP every time you request it.
### Prerequirements
- [This library](https://github.com/HirbodBehnam/Telegram.Bot)
- Visual Studio 2017
- .Net Framework 4.5
### Install

1. Download the project and build it.
2. Go [here](https://t.me/BotFather) and create new bot.
3. Run the application and enter the Token you got from BotFather
4. In settings menu, open password hasher and create a password. Copy the hashed string.
5. Enter the hashed string into Hashed Password textbox.
6. Choose a name for your PC
7. Click Start Bot

Now the bot will listen for inputs. Send `[PC Name] [Password]` to bot to receive your IP.