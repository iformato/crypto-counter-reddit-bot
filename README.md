# crypto-counter-reddit-bot
**Introduction**

The crypto counter reddit bot is a bot that serves to count the amount of comments that include the terms "bitcoin," "ethereum," and "dogecoin" over the period of a day, accumulating them in seperate counters. The bot can be summoned at any point by saying "crypto!stats" in a reddit comment, and it will provide its current counter data. At midnight the bot places the date and count into a dictionary and writes said dictionary into crypto_data.txt file. Then the counter resets to zero where it starts the count from the beginning. 

Upon the reddit bot's data being inputted into the file, the twitter bot will then access the file at 00:01 and tweet out the results. 


**Technologies**

The bot was programmed in python 3.10. The reddit bot was built utilizing the praw library, while the twitter bot utilized tweepy. 


**To Use**

In addition to python 3.10 the program would require that you install both the praw library for the reddit bot and the tweepy library for the twitter bot. 
