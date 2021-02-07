Reflection - Milestone 4
================
Cheuk Ho, Hazel Jiang, Anita Li, Ivy Zhang
06/02/2021

In this milestone, we further improved and re-implemented our dashboard with Python 
by incorporating the improvement ideas we had from previous milestones, feedbacks from TA and peer reviews. 
We decided to go with Python due to the following reasons: 
1) There are issues with plot title for subplot in R which required us to restructure our key factor plots, the most critical part of the dashboard.
2) There are less documentations online for R regarding dash_core_components.
3) The built-in interactivity of ggplotly function can be distracting and less user friendly. We want to keep our key plots clear and concise.

We successfully implemented the feature of showing the attrition proportion at a total level when
users first open our dashboard. It's a reoccurring feedback from TA and peer and we have been wanting to implemented this
feature since milestone 1. Although we did not add an \`total\` option in the
filter, the same result is reached by using multi selection for the drop-downs. 
Users can now remove the default value in the drop-downs and pick the interested segment 
when they want to shift from the total level to the interested segment. 

Base on feedback from peer, we improved the storyline of our dashboard by adding overall and key segment attrition rate cards 
on the top of our dashboard. We decided to only use cards because cards deliver 
information in a more straightforward and concise manner. It allows the users to see the difference 
between the key segments, the department and gender more easily. Our group found this suggestion very valuable. While we have been keeping the dashboard clear and concise, the suggestion reminds us that it's crucial to first give an overall picture on the overall and key segment attrition rate before drilling down into the factors.

Finally, we also made several cosmetic edits for better visualization for our app. 
We adjusted the layout & margin between components of the dashboard and update sidebar format. 
We also use more suitable and comfortable colour tone for the plots (i.e., blue and red for yes and no).
The $ unit is added back to the \`Monthly Income\` plot.  

So far, we believe our app is easy to use and very informative as well. Our app fully served the business objective in providing users a
very clear overview onto the overall and key segment attrition rate. Then it allows users to look into the key factors that drive attrition. 
The app also has the capability of filtering the key attrition factors by `Department`, `Gender`
and `Age` to get a better understanding and make plans accordingly.

Overall, we improved our app quite a bit this week. However, there is still
room for further improvement. We still wish to add two blank plots that allow users to choose the numerical or categorical factors 
they want to explore as value added component on top of our original plan to allow more flexibility. 
While we do not have enough time to implement this in this milestone, we will look into this feature in the future.
