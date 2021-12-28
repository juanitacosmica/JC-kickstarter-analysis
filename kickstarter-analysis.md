# Kickstarting with Excel

## Overview of Project
The Kickstarter project is a set of data collected in order to review the outcomes of different categories of Art Performances kickstarter projects per country.
### Purpose
To determine if any given kickstarter project was succesful, failed or canceled based on Goals vs Pledge
## Analysis and Challenges

![Overview of the Analysis PIVOT TABLES](/assets/images/overview _of_the_analysis.png)

![Overview of the Analysis LOOKUPS](/assets/images/overview _of_the_analysis_V2.png)

The analysis was performed mainly through the use of:
- Pivot Tables, 
- Graphs, and,
- LOOKUPS.

Eventhough there were no real challenges from a technical perspective, if the data was not as clean and straight forward, challenges with the LOOKUPS could have been presented; furthermore, to draw better conclusions, it was necessary to calculate *statistical measures*, for example, averages and other percentages. 

It was also imperative to understand well the use of each graph IAW the available data, to be represented and analyzed.


### Analysis of Outcomes Based on Launch Date

![Theatre Outcomes based on Launch Date](/assets/images/Outcome_Based_on_Launch_Date.png)

**Conclusion 1** The Outcomes Based on Launch Date for Theatre, shows May (at 111) with the larger number of Succesful whereas in December (at 37) went closer to those Failed (at 35). May is the month were Succesful kickstarter projects start dicreasing, and eventhough between September (at 59)  and October (at 65) it tends to increase, it goes down  in December to almost reach the number of Failed.

**Conclusion 2** The Failed are between 31 and 52 throughout the year (average at 41), below the average number of Succesful Theatre projects (at 70).

### Analysis of Outcomes Based on Goals

![Plays Outcomes vs Goals](/assets/images/Outcomes_vs_Goals.png)

**Conclusion 1**  The higher the Goal the higher the probability for the Play to Fail. 

**Conclusion 2**  51% of the Plays had a goal between 1,000$ and 4,999$; 73% of them was Succesful and 27% Failed. 

**Conclusion 3** 92% of the Plays are mainly amongst the first 4 Goal ranges (Less than 1,000 and 15,000$).

### Challenges and Difficulties Encountered

![Plays Outcomes vs Goals V2](/assets/images/Outcomes_vs_Goals_V2.png)

A line graph is not appropiate to analyze this data as each point has its own behaviour, this is not a trend, a bar graph will show the numbers clearer; from the previous line graph, it could only be concluded that failed and successful plays are mirroring each other. The Highlighted in the image above, allowed to draw the conclusion from 1 to 3 in the previous section.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

![All Outcomes based on Launch Date](/assets/images/Outcome_Based_on_Launch_Date.png)

*Conclusion 1*

The Outcomes Based on Launch Date for all Theatre, shows May (at 111) with the larger number of Succesful whereas in December (at 37) went closer to those Failed (at 35). May is the month were Succesful kickstarter projects start dicreasing, and eventhough between September (at 59)  and October (at 65) it tends to increase, it goes down  in December to almost reach the number of Failed.

*Conclusion 2*

The Failed are between 31 and 52 throughout the year (average at 41), below the average number of Succesful Theatre projects (at 70).


- What can you conclude about the Outcomes based on Goals?

Overall data showed that for higher Goals, the probability for the kickstarters to fail increased. For example, 51% of total Plays had a goal between 1,000$ and 4,999$; 73% of them was Succesful and 27% Failed.

- What are some limitations of this dataset?

  1. Under what factors the goal and the pledge was set? By knowing this variable, with maybe more historical data, it will become easier to make a decision.
  2. Provide more context as to how the data was collected and what factors keyd in for the sample.


- What are some other possible tables and/or graphs that we could create?
  1. Percentages per Goal ranges for All Categories
  2. Pie charts with the distribution of goals and pledge per country to see if there is an impact based on region
  3. Calcs of outliers will permit to clean the sampled data, *this has to factor in the requirements taken into account when the data was collected, a context is always required when performing data analysis*.
