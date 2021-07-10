---
layout: post
title: Bike Share Project
---
## The Project
In this project, we were to use two multiple regression models, a random forest model and a boosted tree model to try and determine either the number of casual, 
registered or total number of bike share riders. The data was read in, then the appropriate variables were converted to factors before being explored. A correlation 
plot of the non-factor variables was created, along with plots and tables looking at different raltionships with the three different rider types data. It was 
determined by my partner and I that we were most interested in the total number of riders and not the registered or casual numbers. 

With the variables that looked like they may have a relationship with the total number of riders, the four models were fit and then used on the trianing data.
The root mean squared error (RMSE) was calculated and the model with the lowest RMSE was determined. This is listed at the bottom of each report. 

## The Process
The first thing we did was to talk. My partner was the first one listed and so she created the repo. I then read in the data and we both worked on the plots and tables. 
My partner was faster than me to start exploring the data and so I worked on filling in where I saw she hadn't made a plot or table  for a relationship I thought was 
important. I approached my plots as wanting to use several of the techniques we covered and to make pretty and informative plots. 

Once we had explored the data, we started on the models. Again, my partner was slightly ahead of me and so I made sure that I didn't use the same models that she did. I 
chose to not model any interactions and instead I just used season, temperature and the year. I used the same model for both the multiple linear regression and the 
boosted tree. We set the seed before each model, to ensure that the comparison between the four different models was as fair as possible. 

## Questions  
### What would you do differently?  
Honestly, not too much. For the most part, this project went smoothly. My partner and I communicated well and we both worked on a lot. I think the approach of using a 
single day before automating the whole week was a really good suggestion. When working on something complex, I like to break it down into an easier or less complicated 
task and add complexity to it before jumping in head first. I think if I were to do this project again on my own, I would probably use more regression techniques but 
only on a single model.

### What was the most difficult part for you?  
Working as a team in GitHub. There were a couple times when both of us were working on the project and my partner would push before I could get a chance to and then I'd have
to figure out how to do my updates. I ended up just copying my code into another window, deleting the local file for the project and pulling from GitHub so I'd have the 
updated version that I could then push back. I would add this to what I would do differently as I would look into how my partner and I could have our own branches to 
push and pull so that these inconveniences wouldn't happen again.

### What are your big take-aways from this project?  
Automaing reports is easier than it looks, but that you have to be careful in how you do it so that everything matches. I feel like it would have been really easy for us to 
accidently change the day, especially since they were just listed numerically 0-6 in the originial dataset. I also took away that it's easier than I had thought to work on 
a coding project with someone, but I definitely need to change the way I use GitHub if there's more than two people in my group.

## Links  
[Project Pages](https://sjung7nc.github.io/group13-project2/)

[Project Repo](https://github.com/sjung7nc/group13-project2)
