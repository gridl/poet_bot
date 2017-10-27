# poet_bot

Building a Telegram bot which recommends poems based on input strings.

# Data

I have scraped the 500 most popular poems from a dedicated website (see 'poems_scrape.ipynb'). The results are in 'poems_collection.csv', with columns labelled as author, title, text. Text contains <br\/> elements to improve aestherics when prited out (<br\/> -> \n).

# Bot usage

If you want to talk to PoetBot:
1) Create a Telegram account on your phone. 2) Search for @VioletsAreBlueBot. 3) Chat with the bot :) 4) Note that I run the bot locally, hence it will reply to you only if my server is running.

If you want to run the bot:
1) Create a Telegram account on your phone. 2) Connect to BotFather. 3) Create a bot with a given name. 4) Save your token. 5) Download the code from this repo to your local machine. 6) Replace your token in bot.py 7) Run 'python3 bot.py'. 8) Find your new bot on Telegram from @username 9) Have a chat :) 

# License
Released under version 2.0 of the [Apache License].

[Apache license]: http://www.apache.org/licenses/LICENSE-2.0
