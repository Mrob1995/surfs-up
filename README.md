# surfs-up
Querying a database via sqlalchemy

## Analysis
Given a pool of weather information for Hawaii in the form of a sqlite file, I was tasked with querying the simulated database using sqlalchemy, and then manipulate the information using pandas. I found sqlalchemy to be an absolute joy to work with. By all means it has its own ins and outs to learn, but the ability to switch your database platform without having to go in and modify your scripts seems spectacularly convenient. 

##Summary
When analyzing the months of June and December for both temperature and precipitation, we quickly find the somewhat predictable outcome that June is slightly hotter, and noticeably dryer. I opted to analyze the two equally. It struck me as odd that the initial instructions were just for a temperature in December, rather than both temperature and precipitation. In particular, because the difference in precipitation was the far more noticeable change between the two tables. 
