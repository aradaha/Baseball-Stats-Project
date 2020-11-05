# Data-Science-Capstone
Capstone project

![alt text](https://github.com/aradaha/Data-Science-Capstone/blob/main/Pictures/1880.gif)

In this project I worked Baseball player data from kaggle. After getting it I found an updated version on another website, with a complete list of what each category was.

First, I worked with the "primary" data set, the list of all players, and most of their personal stats. This didn't include many stats that one might be interested in, such as what they did on the field. So, I looked at some of the other datasets. First though, I got a couple things I thought might be useful out of it, such as how long each of the players played the game, and how they were when they started playing.

The first thing I decided was worth plotting was the amount of awards given out by year. as it turns out, not very many were given out prior to 1910, the year the MVP award was started being given out. Prior to that, most of the awards were for being the best in three categories.

![alt text](https://github.com/aradaha/Data-Science-Capstone/blob/main/Pictures/Awards2.gif)


I needed to unmelt the data in several cases, because the main data set had one row for each player, whereas most of the rest had a row for each player and year, giving several dataframes over one hundred thousand entries.

Generally I divided one stat by another to get statistics that weren't automatically given to me, for example, batting average is something commonly used to evaluate players, but it was not specifically included - only the number of at bats and the number of hits.


![alt text](https://github.com/aradaha/Data-Science-Capstone/blob/main/Pictures/Batting.gif)

I decided to seperate the pitchers from the rest of the players in order to evaluate them based on the stats specific to them, and because I figure that generally other fielders are relatively interchangable.


![alt text](https://github.com/aradaha/Data-Science-Capstone/blob/main/Pictures/BabeRuth.gif)