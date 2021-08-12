## Research Question

How does road trip length affect winnning in the NBA? 

## Summary

A road trip is any stretch of away games immediately following a home game. The length of the road trip is the number of games played during the road trip. Road trips are further discussed in the collecting and sorting data.ipynb, and my results are stored in the analysis and visualizations.ipynb. 

I also tracked the cumulative distance traveled during a road trip. This is the total distance traveled during a road trip. For example, the cumulative distance traveled during the 76ers first 3 game road trip of the 2018-2019 season was against the Grizzlies, the Heat, and the Magic, so the cumulative distance of that road trip is the distance between Philly and Memphis, plus the distance between Memphis and Miami, plus the distance between Miami and Orlando, which comes out to 3155 km. 

## Hypothesis

The longer a team spends on the road, the less they win. My logic was that fatigue would cause teams to struggle. 


## Conclusion 

There is a statistically significant rise in win percentage after the first 4 games of a road trip. I do not yet have an explanation for why this is. 


## Secondary Goals

Besides the main goal of answering the research question, I also wanted to find idiosyncrasies in the data. For example, did you know the longest roadtrip in the 2010s belong to the Clippers at 11 games, and the 76ers at over 13,000 km travelled? 

## Further Questions 

1. Why does win percentage rise after the first 4 games of a road trip? 

2. Jetlag is said to be worse when traveling east. Do teams that travel east have a lower win percentage than teams travelling west? 

## Organization

collecting and sorting data.ipynb - Where I compile all of the data I use in the analysis and visualizations.ipynb. The data is saved in the following folders: Games, CompleteData, and TeamTravelDistVsWinning.

Games - Contains the schedules for each season.

TeamTravelDistVsWinning - Contains a csv for each team in a given year. Each csv records, for each game, the length of the current road trip (0 for home games), distance traveled (0 for home games), and whether or not the team won. 

CompleteData - Contains a single csv with all of the data from the files in the TeamTravelDistVsWinning folder. All games from the perspective of the home team are removed, and the data is sorted by distance and then by length of road trip. 

analysis and visualizations.ipynb - I analyze the data, explore possible trends and idiosyncracies, then determine whether the possible trends are statistically significant, and finally provide a few visualizations of the data. 