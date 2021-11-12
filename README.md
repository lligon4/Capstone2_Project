# Predicting Major League Baseball Pitch Type

Major League Baseball (MLB) is possibly the most sophisticated sports organization in the world when it comes to data analysis for the sport. While descriptive statistics have always been a source of performance measurement for players in the MLB, modern day technology introduced an “arms race” of data analysis to the sport. As of 2015, all 30 MLB teams have their stadiums equipped with Statcast infrastructure. Statcast is a camera based, highly accurate tool that measures player movements and athletic abilities. 

Statcast has greatly increased the amount of information available for evaluating player performance in the MLB. The scope of this project is to focus on pitch-level data to better predict what type of pitch a batter should expect. When armed with a confident expectation of a specific pitch, this greatly increases the batter’s chances of getting on base compared to uncertainty in the impending pitch type. Pitched ball speeds can vary greatly and accurately predicting the pitch type associated with speed will benefit the batter and offense.

Statcast data is available to the public and made easily accessible with the Python package pybaseball. With the help of MLB statcast and pybaseball, the information required to predict pitches should be available in the source data. As a batter in the MLB, the problem of uncertainty in future pitch types is one that has traditionally been solved with intuition or player intelligence. Now, we aim to arm the batter with a statistically supported expectation of pitch type.

## Problem Statement

As Hank Aaron once said, “Guessing what the pitcher is going to throw is 80 percent of being a successful hitter. The other 20 percent is just execution.” The core event that occurs in the sport of baseball is a pitch of the baseball from pitcher to batter. The pitcher is trying to throw a pitch that does not result in the batter getting on base while the batter aims to accomplish exactly that. All methods of getting on base require a pitch. Understanding the nature of pitches can benefit both the pitcher and batter. From the batter’s view, predicting pitch type will increase the likelihood of success with knowledge of pitch speed and location. 




