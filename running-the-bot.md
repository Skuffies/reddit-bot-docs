---
description: Running the bot.
---
# Running the bot

## Before we run the bot

Make sure you have everything setup properly in [configuring.md](configuring.md). Screwing up is gonna take a while to fix.

## Running the actual bot

Now we can run the bot.

Type `python main.py` (or `python3 main.py`) in your terminal. (make sure it is the correct folder eg: RedditVideoBotMaker).

![rtb](<.gitbook/assets/image (8) (1) (1).png>)

You should see something like this. This indicates that you have done everything correctly.

Now each and every time you wish to produce an automated video like this one, all you have to do is run `python3 main.py` (or `python main.py`) from the terminal (like this time, without any installation procedures) and the bot will pick the top posts from your favorite subreddit and produce you a high quality video ready for YouTube Shorts and TikTok. You can also dive into the code and make an infinite loop. Do note though that if you have any errors we will not be able to assist you.

Some things to keep in mind are that the background video (the parkour/rocket league gameplay) is one hour long, **do not delete this**. The bot essentially picks two random points in the clip that is 60 seconds long and pastes it in as the background of the video. If the 60 minute clip is deleted, then it will need to re-download the clip.

Once your video is processed, you should be able to view it! To view it check out [this page](viewing-the-video.md)
