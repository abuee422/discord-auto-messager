# Discord Message Sender

This Python script allows you to send a list of messages to a Discord channel at specified intervals using the Discord Token.

## Get your discord token:

first Login your discord account and Inspect(F12) GO to console tab type:
```allow pasting```
then paste this:
```bash
(
    webpackChunkdiscord_app.push(
        [
            [''],
            {},
            e => {
                m=[];
                for(let c in e.c)
                    m.push(e.c[c])
            }
        ]
    ),
    m
).find(
    m => m?.exports?.default?.getToken !== void 0
).exports.default.getToken()
```
get discord token and save token without ''

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/abuee422/discord-auto-messager.git
    ```
    ```bash
    cd discord-auto-messager
    ```
2. Replace your sentences in file:
    ```bash
    nano sentences.txt
    ```
    Example sentences.txt file:
    ```
    Hello, Discord!
    This is an automated message.
    Have a great day!
    ```
    **Note: You can get sentences from Chatgpt or Groq**
3. Install Prerequisites:
    ```bash
    pip install requests
    ```
4. Run script:
    ```bash
    python3 main.py
    ```
## What is channel id?
Go to the channel where you want the bot to be active and copy last part of url.

![image](https://github.com/user-attachments/assets/5a516d29-2de4-476c-85f4-2ae1e5128412)


