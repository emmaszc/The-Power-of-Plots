# The Power of Plots

## Background and Tasks

This project analyzes a hypothetical pharmaceutical study. In the study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of "Pymaceuticals'" drug of interest, Capomulin, versus the other treatment regimens. 

The tasks were as follows:

* Before beginning the analysis, the data was checked for duplicate mice and duplicates were removed that were associated with that mouse ID.

* A summary statistics table was generated consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* A bar plot was generated using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of mice per time point for each treatment regimen throughout the course of the study.

* A pie plot was generated using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

* The final tumor volume was calculated of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. The quartiles and IQR were calculated and outliers were determined.

* Using Matplotlib, I generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* Generated a line plot of time point versus tumor volume for a single mouse treated with Capomulin.

* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotted the linear regression model on top of the previous scatter plot.

