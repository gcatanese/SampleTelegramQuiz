# SampleTelegramQuiz
Sample of Telegram Quiz in Python

Find here the source code of the [Creating a Telegram Chatbot Quiz with Python](https://towardsdatascience.com/creating-a-telegram-chatbot-quiz-with-python-711a43c0c424) 
article.

![Alt text](splash.png?raw=true "World Capitals Quiz")

### Table of Contents 
  * [Setup](#setup)
  * [Run on Local](#run-on-local)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


## Setup

Clone the repository

```
git clone https://github.com/gcatanese/SampleTelegramQuiz.git
```

Create and *.env* file in the same folder as *app.py*. The *.env* file defines the environment variables.  

* TELEGRAM_TOKEN={your Telegram token} [here]


## Run on Local
Run the application
```
cd telegram_bot
python telegram_bot.py
```
Access the bot via the deeplink `https://t.me/{bot_username}` and start chatting

**Note**: the chatbot runs in Polling mode

