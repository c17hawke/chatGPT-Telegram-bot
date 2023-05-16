# chatGPT-Telegram-bot: How to build powerful chatbots with ChatGPT API, Python, and Telegram

This repository contains the code and resources for a tutorial on `Building Powerful Chatbots with ChatGPT API, Python, and Telegram`. The tutorial is based on a youtube video by @c17hawke, which you can watch here: 

## Tutorial is available on YouTube [Click on the following thumbnail]-
[![Watch the video](https://img.youtube.com/vi/JhzlzVehXVo/maxresdefault.jpg)](https://www.youtube.com/watch?v=JhzlzVehXVo)

## What you will learn

In this tutorial, you will learn how to:

- Set up your project environment and install the required libraries
- Create your own Telegram bot and obtain the BOT TOKEN
- Use aiogram library to handle Telegram bot interactions
- Use openai library to access ChatGPT API and generate realistic responses
- Integrate ChatGPT with Telegram bot to create engaging conversations

## Prerequisites

To follow this tutorial, you will need:

- Python 3.7 or higher
- A Telegram account and a smartphone
- An OpenAI account and an API key

## How to run the code

1. Clone this repository or download the zip file
2. Create a virtual environment and activate it
3. Install the dependencies using `pip install -r requirements.txt`
    > Or alternatively to the above two steps you can run `init_setup.sh` by running the following command in your terminal-
    ```bash
    bash init_setup.sh
    ```
4. Create a `.env` file in the root directory and add your OpenAI API key and Telegram BOT TOKEN [refered as TOKEN here] as follows:

```ini
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TOKEN=xxxxxxxxxx:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

5. Run `python src/chatgpt.py` to start the bot
6. Open Telegram and search for your bot username
7. Start a conversation with your bot and enjoy!

## Feedback and support

If you have any questions, suggestions, or feedback, please feel free to raise issue in this repository or leave a comment on my blog: https://medium.com/@c17hawke/1cb9c03e7ca2

If you liked this tutorial, please star this repository and subscribe to my youtube channel for more Python programming videos. Thank you!