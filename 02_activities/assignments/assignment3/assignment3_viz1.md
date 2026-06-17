Original data link:https://open.toronto.ca/dataset/motor-vehicle-collisions-involving-killed-or-seriously-injured-persons/

> What software did you use to create your data visualization?
I used Python under VSCode, the pandas library for data cleaning and analysis and matplotlib for creating the data visualization.

> Who is your intended audience?
The intended audience is the general public.
    
> What information or message are you trying to convey with your visualization?
The main message is to show which road surface conditions were most common during 2025 collision events. More than 81% of the collisions occurred on dry road surfaces, suggesting collision events were not directly associated with poor road surface conditions.
    
> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
Findability: I used a descriptive title: “Condition of the Road Surface at the Time of Collision in 2025.”
Accessibility: I used a horizontal bar chart instead of a pie chart, because bar lengths are easier to compare. I also added axis labels, counts, and percentages beside each bar.
Reusability: I kept the code simple and used clear variable names
    
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
I ensured reproducibility by using Python code to complete every step. Since pandas and matplotlib are reproducible library tools, another person can run the same code with the same dataset and generate the same visualization. If the tool were not reproducible, it would be harder to verify the results or recreate the same chart accurately.
    
> How did you ensure that your data visualization is accessible?
I made the visualization accessible by using a horizontal bar chart with clear labels and readable text. I included both the number of collisions and the percentage, so viewers do not need to estimate values from the bars alone. I also avoided relying on color, which makes the chart easier to understand for people with color vision differences.  
    
> Who are the individuals and communities who might be impacted by your visualization?
It may affect communities concerned about traffic safety and road maintenance. Since more than 81% of collision events in 2025 occurred on dry roads, it suggests that collision prevention should not focus only on poor weather or road surface conditions.
    
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
I selected only the road surface condition variable and the number of collision events because my goal was to compare how frequently each surface condition occurred during collisions. This selection avoids unnecessary complexity and ensured the main message was clear.

> What ‘underwater labour’ contributed to your final data visualization product?
'Underwater labour' included data cleaning (2025 unique events), grouping and counting the road surface conditions, calculating percentages for better interpretation, refining labels and adjusting layout for readability, and debugging code issues such as figure saving.