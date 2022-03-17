# **Challenge 1 Analysis**

## Project Overview
Louise, a producer, asked us to analyze a set of data regarding a number of productions in the works. She wanted to know where she would find success, and the data provided gave us insights on where to find it. We compared the various projects she has going, some of which are live, and some of which are set to go but not yet begun. We compared them based on when they were set to go live, how much funding they required, and how many goals were met.

## Analysis and Challenges
### Analysis 
We analyzed the success rates of donations based on the required funding amount and when the productions were set to launch. We subdivided the data into categories and focused on theater productions in general and plays specifically. We then observed trends in the performance of the campaigns throughout the year and created charts and graphs to illustrate the performance of her endeavors. We plotted the outcomes of the theater campaigns based on their launch dates.   

### Challenges
One of the challenges we faced using this data set was that the dates for the funding deadlines and when they were launches were provided in Epoch time, which we had to convert to to a MM/DD/YY format we could read. In order to do that, we used the Excel function `=(((I30/60)/60)/24)+DATE(1970,1,1)`. Another adjustment necessary was dividing the category and subcategory column into two columns so we could further narrow down the categories we could consider. Another possible challenge which could provide further insight for Louise is that there are various countries represented. One country might have a much stronger interest in musicals than plays, but in our analysis of *Outcomes Based on Goals* we considered plays across all nations, where perhaps further dividing that data between countries could give us a better idea of where to best deploy Louises resources. 

## Results
### Outcomes Based on Launch Date
We discovered theater productions of all types were most successful in the summer months of May through July, with distinctly higher success rates than the other months of the year, particularly May and June. However, overall theater productions were more successful than they were unsuccessful. We did discover that December is the least desirable month to launch a theater production. ![This is an image](https://github.com/BartBachrach/Kickstarter-Analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

### Outcomes Based on Goals
The majority of campaigns for plays lie between the funding goal range $0-$9999, with many more campaigns overall successful than not. More specifically, the $1000-$4999 funding goal range was the most successful in the *plays* subcategory. Plays with a funding goal of $50,000 or more failed significantly more often than they succeeded. One reason the $1000-$4999 range performed the way it did was because potential donors can conceive of their contribution making a difference, and the goal is easier to atain than a $50,000+ fundraising goal. 



