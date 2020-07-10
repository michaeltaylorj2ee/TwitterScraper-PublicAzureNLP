README

Description: 

Workers’ compensation fraud occurs when someone willfully makes a false statement or conceals information in order to receive workers’ compensation benefits or prevents someone from receiving benefits to which they might be entitled. 

When employees submit fraudulent workman's compensation claims, it costs the agency and taxpaying citizens billions of dollars each year.

The Social Media Recon bot will investigate a specified twitter profile for cases of fraud.

The bot has been constructed with multiple different technologies. 

The stack consists of 4 major parts:
-The Python Twitter extraction script
-IBM watson sentiment analysis
-Microsoft Azure Image Vision
-UiPath Robots


The workflow is composed of a few main sequences.
-Prompt the user for input
-Scrape the twitter handle
-Analyze each tweet using AI
-then Finally save and email the report

INSTRUCTIONS:

Prereq: https://github.com/taspinar/twitterscraper
Install python (Ensure python is included in system path)
Then run this command on a command prompt:
pip install twitterscraper

After installing the twitterscraper tool, Open the Main file and run it in UiPath. 

Fill out the required fields in the Form and let the bot run.

Note: The twitter scraper can take a long time if there are a lot of tweet for a selected date range. For a demo, use just a few days worth of tweets.