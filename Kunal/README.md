The **main_program_final.ipynb** includes several code blocks with the objective of 
A) Converting the cleaned csv files into pandas dataframes and 
B) Creation of several algorithms for calculating key metrices which the analysis is based on

Code blocks were parameterized such that it could be used for different recession periods analysed in this project.

# 1) Import key libraries: 
These include `pandas`, `numpy`, `pathlib`, `hvplot`. (`matplotlib` is not essential to the running of the program
# 2) Code blocks 2 - 4: Import csv data files and perform initial manipulations, concate the final datasets, rename variables for future steps
In this step code for the Gold index data conversion had to be differentiated from others due to difference in base csv file structure
# 3) Algorithm 1 (Code block 5): Calculates a correlation matrix for all the indices included in the analysis
This simply uses pandas correlation function
# 4) Algorithm 2 (Code block 6): Visualization  
This code block was used to create several visualizations. The team finally settled on scatter plot charts and a line chart to show time series performance of all the sectors
# 5) Algorithm 3 (Code block 7): Index steepest decline
Calculates the steepest decline for each index during the recession period (using the period high and period low)
# 6) Algorithm 4 (Code block 8): Index overall decline
Calculates the overall decline for each index during the recession period (using recession start date and end date)
# 7) Algorithm 5 (Code block 9): Days to recovery
Identifies the date when a given index reaches the pre-recession levels and using the post recession end date calculates the days & months to recovery