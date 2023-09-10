# ACT_SAT_Analysis

### The problem that this study aims to address is identifying trends from ACT and SAT test datasets collected in 2017 and 2018. This kind of research is important because it may lead to policy change, which will improve student test scores. 

### Data Exploration, and Analysis
#### There was no missing data in any of the datasets used in this study and minimal data cleaning was required. All four datasets included data from every state in the United States. In 2017, the average state participation rate for the SAT was 39% and the average total score was 1126. In 2018, the average participation rate was 45% and average score was 1120. I used a scatterplot to the relationship between total SAT score and participation rate and a linear relationship is observed both years. As a state's participation rate increases, the total score decreases. To confirm the effect of these variables on one another I plotted a correlation heatmap and confirmed that participation rate had a correlation of -0.87 in 2017 and -0.76 in 2018 with total score. These are very strong correlations and support what I previously discussed, but should not be viewed as causation. The ACT datasets were consistent with the findings from the SAT datasets. As a states ACT participation rate increased, the average composite score descreased. 

### Visualizations
#### For each dataset I use the folium library to plot choropleth maps of the participation rate and average score by state. It can be observed that states with high participation rates also has lower average total SAT and ACT scores.  

### Conclusions and Recommendations
#### The SAT and ACT data reviewed above show a remarkably strong relationship between total score participation and rate for both the SAT and ACT exams. As the participation rate increases in a given state, the average score steadily decreases. I recommend that states invest more in preparing students for these exams. One way is to create a new class that is devoted to teaching the information contained within these exams to ensure students are adequately prepared. Further research is required to understand what drives the high test scores of the students in states with low participation rates.

