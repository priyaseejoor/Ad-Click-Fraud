# Ad-Click-Fraud
Copyright 2020 All rights reserved Google Slides
Data set:
https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/data

Fraud risk occurs everywhere, but for companies that advertise online, click fraud can happen at a massive volume, resulting in wasted money and false click data. Cpc for short or other known as cost per click, is a pay per click advertising metric and model that determines the price you pay for each individual click through, in your ad campaigns. 

The great thing about CPC is you’re only charged when someone clicks your ad, so in theory, if your ad doesn’t get many clicks, you’ll benefit from getting thousands of impressions/views for free. However on the opposing end if you’re getting thousands of clicks that are bots your online advertising budget could run out, before you are even able to get any real conversions from actual people clicking on your ad. 

TalkingData is China’s largest independent big data service platform, that covers over 70% of active mobile devices nationwide. They handle 3 billion clicks per day, of which 90% are potentially fraudulent. Their approach to flag ad fraud is to look at ip addresses who produce a lot of clicks, but never end up downloading the app.

My objective today is to actually test this data to see if rate of fraud is affected by time of day or not. 

Ho: rate of fraud at night = rate of fraud during the day
Ha: rate of fraud at night ≠ rate of fraud during the day
