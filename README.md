# crypto-counter-reddit-bot
**Introduction**

The crypto counter reddit bot is a bot that serves to count the amount of comments that include the terms "bitcoin," "ethereum," and "dogecoin" over the period of a day, accumulating them in seperate counters. The bot can be summoned at any point by saying "crypto!stats" in a reddit comment, and it will provide its current counter data. At midnight the bot places the date and count into a dictionary and writes said dictionary into crypto_data.txt file. Then the counter resets to zero until next midnight. 


**Technologies**

The bot was programmed in python 3.10 utilizing primarily the praw package. 


**To Use**

All you need outside of python is to install praw.
