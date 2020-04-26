# Mapping Tweets - Lab 2 Analysis

<B>Process & Data Collection - </b>
In order to obtain the data needed for the map I used the tweepy program and the crawler template provided and then modified the crawler to reference my own Twitter Developer account. Next, I chose to filter tweets by keyword. I started by filtering by the keyword ['stayhome'], but I found that I was not getting enough data, even over a five minute period. So I looked up the language to include a second keyword, finding that I could filter by two keywords I then ran the code again using the keywords ['stayhome','quarantine']. I also modified the time period that I would collect data to 1200 (20 minutes), so that I would have plenty of data.
Using this data I was able to create the simple maps that you see below.

<b>Map Analysis</b>
This first map shows the tweets that were collected using the filter keywords 'stayhome' and 'quarantine', without accounting for any additional locational filters, such as coordinates. I was interested in reducing the filter to just include the U.S. but I could not get both filters to operate at the same time without getting erros from the crawler program. At any rate, the map below show how the individuals tweeting about quartine and isolation are distributed around the globe.

<img src="/img/lab2_map_matthewjackson.png">
A quick look at this map shows us that the majority of accounts tweeting about quartine are located in the U.S. and in Japan. This large distribution of tweets from the U.S. is not unexpected to me, as the U.S. continues to surge in COVID-19 cases measures to keep the general public isolated have also further implemented. The surprising data to me was the amount of tweets coming out of Japan. However, a quick look at the most recent news out of Japan does show that the local qovernment has implemented a self-quarantine of all U.S. travelers for 14 days. This may be contributing to the amount of tweets in the area using these keywords.

At this point it would be good to acknowledge some situational factors that affected the distribution of tweets seen at the gobal scale. I ran the crawler program at approximatley 10:20 pm PST. Because of this, we can not expect to see a large amount of tweets being collected from europe, as it would be very early in the morning for most accounts to be tweeting. So, knowing this we can write off the lack of tweets seen in europe. If we wanted to give adequate weight to all areas of the globe we would need to have a much longer amount of time to get different windows of activity from around the globe.

In addition to the global map, I also include here a map of the U.S. for a more localized analysis.

<img src="/img/lab2_mapzoom_matthewjackson.png">

Here we see that quite a bit of the distrbution is clumped up into areas that correspond to metropolitan areas. We can quite clearly see the Bay Area, L.A., San Diego, New York, Boston, Chicago, New Orleans, Houston, San Antonio, and Seattle. Each of these areas is represetned by more than one tweet matching our keywords in the 20 minute time period that we observed.
I think that this is to be expected, not just because there may be more tweeter users in urban areas, but also because the most strictly enforced quarantines are seen in metropolitan areas due to the higher density and capacity for spread through increased interactions. This might explain why metro areas have a higher amount of people tweeting about the quarantine, since they may have their lives much more impacted by the ramifications of quarantine than their rural counterparts.
