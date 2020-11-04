# Data-Science-Capstone
Capstone project

![alt text](https://mediad.publicbroadcasting.net/p/wkar/files/styles/x_large/public/201307/Ty-Cobb-1913-NPC.jpeg)

In this project I worked Baseball player data from kaggle. After getting it I found an updated version on another website, with a complete list of what each category was.

First, I worked with the "primary" data set, the list of all players, and most of their personal stats. This didn't include many stats that one might be interested in, such as what they did on the field. So, I looked at some of the other datasets. First though, I got a couple things I thought might be useful out of it, such as how long each of the players played the game, and how they were when they started playing.



I also plotted several zip codes in Denver, to get a good look at the housing crisis. I felt I should avoid it, so I picked a spot where most places were in recovery from it, early 2012.

I then melted the data, and observed that a few zip codes didn't have complete data. I figured this was because they recently came into existence. There were a couple of those on the Denver graph as well. Since there were only 6, out of over 500, it seemed reasonable to just drop them. Anyway, there may not be enough data to work with when predicting.

I then used a seasonal model to plot one zipcode and seperate the factors to confirm that there was a seasonal component, so I was right to use SARIMAX rather than ignoring the seasonal data.

I made a QQ plot to check for normalization.

Then I calculated the RMSE for Redmond. Perhaps not the goal of the project, but it's in the area. Also the ROI for Reno, somehwat disappointing.

Eventually I chose 10 zipcodes based on their 4 year ROI, and checked each of them for RMSE, ultimately picking 5 that happen to be close to Seattle.







![alt text](https://ibb.co/k8MQvkx)




![alt text](https://media1.britannica.com/eb-media/62/82562-004-E63B7741.jpg)