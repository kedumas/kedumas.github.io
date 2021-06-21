---
layout: post
title: NHL API Project
---
## Process
The process I follwoed was to call each API endpoint individually. This was so that I could troubleshoot errors as they came up but it did not affect the working API calls. 
Then these base API calls were placed in the wrapper with an if else flow to go through each of the possible base function calls. The only exception with this was the first, 
franchise information, as it had all of the team names, abbreviations and ID numbers already and so it was used to map out which team was being queried.

I then selected a few different functions to call and use for all the tables and plots. I ended up creating several contingency tables, summary tables and plots. As I was going 
through this, I created new variables as I needed. Most of the new variables that were made were creating larger bins to categorize continuous data. The other variables that 
were created were percentages so that the regular season could be compared to the post-season.

I think that the most interesting finding I has was found in a boxplot. The boxplot was to compare the win percentages between the regular season and post-season. I thought it
was interesting that there was at least one team that got to the post-season and yet didn't have a single win in the post-season.

## Challenges
I think the biggest challenge I had was when I encountered html in four of the variables. These variables needed to be parsed and then ended up getting split manually. It was 
so challenging because I hadn't really encountered html before and it also needed to get processed twice using the xml2 package before splitting the resulting string based on the 
repeats seen. The logic for the most part wasn't too difficult, and I try to use select to filter occasionally, but overall that was the most difficult.

## Going Forward
If I were to do this project over from scratch, or if I wanted to find different endpoints, I would probably take more time looking at the types of outputs. I feel like if I 
understood the outputs better, that it would be a lot easier to modify and manipulate the data. 

## Links
https://kedumas.github.io/ST558-Project-1/

https://github.com/kedumas/ST558-Project-1
