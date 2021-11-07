# Kickstarting with Excel

## Overview of Project

### Purpose: 
 
 - In a short length of time, Louise's play "Fever" came close to reaching its fundraising target. She now wants to know how various campaigns fared in terms of their debut dates and financial targets. I have been tasked to analyze the data for her. The purpose of this analysis is to figure out the outcomes of campaigns depending on their launch dates and financial ambitions.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

 - Using [Kickstarter_Challenge.xlsx](https://github.com/Sebjet24/kickstarter-analysis/files/7492646/Kickstarter_Challenge.xlsx), I created a PivotTable to visualize the Theater outcomes for the columns of "successful", "failed," and "canceled" based on launch date. I then created from the PivotTable a line graph to easily see the shifts in outcome based on month: ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/91230277/140241616-309c1694-78f6-4268-8672-b91b0e7bad28.png)

### Analysis of Outcomes Based on Goals

 - To better understand the outcomes based on goals, I created a new sheet that consisted of a column separating goal dollar amount:
<img width="187" alt="image" src="https://user-images.githubusercontent.com/91230277/140522686-1d28396b-cfc7-4d2b-9523-06439aec123c.png"> 
I then created columns and functions for Number Successful,	Number Failed,	Number Canceled,	Total Projects,	Percentage Successful,	Percentage Failed, and	Percentage Canceled:
<img width="922" alt="image" src="https://user-images.githubusercontent.com/91230277/140523019-87a709b8-8505-4f83-8604-fa62521e4281.png">
Finally, I took the percentage columns and created another line graph that gave me a good look as to what were the outcomes based on goals:

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/91230277/140524461-1e58dc8a-4abc-46ff-86f4-6817a26525b2.png)


### Challenges and Difficulties Encountered

 - The main difficulty I ecountered was figuring out where I made mistakes in my code. Specifically, it was difficult for me to ascertain that I forgot to add the equal symbol in my functions for distinguishing the dollar amount rows. i.e.:
<img width="1065" alt="image" src="https://user-images.githubusercontent.com/91230277/140525219-57c8d4a3-0c7d-4508-aefa-df344c2829e5.png">
Missing this symbol actually made for a drastic change in the results, but once I realized what was happening, it was smooth sailing from then on.

## Results

- Two conclusions I drew about the Outcomes based on Launch Date is one, there were far more succesful Theater outcomes when the launch date was in May than failures. I assume this is because it is the beginning of the summer for most and people are more free to donate. And two, there are almost no canceled kickstarters.

- What I conclude about the Outcomes based on Goals is that just like Theater Outcomes based on launch date there is no cancellations for kick starters. Every single kickstater either pulled out and failed or was succesful and stayed. 

- Some of the limitations of these datasets are they don't account for year to year on the monthly graph. They take all years and add them together for each month. So there could have been some outliers that shifted the data substantially. Another limitation is the theater plays that were asking to be funded could just not have been promoted very well to the viewers at the time. Meaning, there could have been plays that were just awfully promoted and then once again would have created some outliers. Despite these limitations though we can still make some strong assumtions about plays that failed and plays that were succesful.

- Some other possible tables and/or graphs that we could create would be success and failure based off of the title and description. This could also help us see some of the reasons some plays failed and some didn't. I also think creating a graph based on succesful titles may help when promoting a play. A good title definately helps bring in at least viewers of the kickstarter projects. 
