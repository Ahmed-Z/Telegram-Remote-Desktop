# Telegram-Remote-Desktop
This program is used to remotely control your PC from your Telegram app. <b> Please use this responsibly </b>.
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
This program in meant to be running on the PC you want to control remotly.

`git clone https://github.com/Ahmed-Z/Telegram-Remote-Desktop`<br>
`cd Telegram-Remote-Desktop` <br><br>
After downloading you have to install dependencies:<br>
`pip3 install -r requirements.txt`

<h3>Configuration</h3>
You need to create a bot via BotFather using the Telegram app to get the access token and the chat id.

```
{
    "TOKEN":YOUR TOKEN,
    "CHAT_ID": YOUR CHAT ID
}
```
