# Telegram-Remote-Desktop
This program is used to remotely control your PC from your Telegram app. <b> Please use this responsibly </b>.<br>
Full blogpost [here](https://ahmed-z.github.io/the-blog/Control-your-Windows-computer-using-Telegram).
<p align="center">
  <img src="https://github.com/Ahmed-Z/Telegram-Remote-Desktop/blob/master/telegram-final-product.png" style="height:600px;" >
</p>

# Features

* Check screen status (Locked or unlocked).
* Lock screen.
* Take screenshots.
* Paste clipboard.
* List running processes.
* Kill running processes.
* Open URL in computer browser.
* Navigate file system.
* Execute system commands.
* Download files from computer.
* Put computer in sleep mode.

# Installation
This program in meant to be running on the PC you want to control remotely.

`git clone https://github.com/Ahmed-Z/Telegram-Remote-Desktop`<br>
`cd Telegram-Remote-Desktop` <br><br>
After downloading you have to install dependencies:<br>
`pip3 install -r requirements.txt`

<h3>Configuration</h3>

You need to create a bot via BotFather using the Telegram app to get the access token and the chat id.<br>

You need to create `auth.json` file containing your access token and the chat id.

```
{
    "TOKEN":YOUR TOKEN,
    "CHAT_ID": YOUR CHAT ID
}
```
**IMPORTANT** | for security reasons you need to insert your telegram username in `telegram-remote-desktop.py` in the line: <br>
`if update.message.chat["username"] != "YOUR_USERNAME":` <br>
Only the the account of the specified username is able to use the bot.
