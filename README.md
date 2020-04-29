# Pymaceuticals

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Data
Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

<img src="images/summary_statistics.png">


## Plots
Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of data points for each treatment regimen.

<img src="images/bar_plot_pandas.png"> <img src="images/bar_plot_pyplot.png">


Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

<img src="images/pie_chart_pandas.png"> <img src="images/pie_chart_pyplot.png">


Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

<img src="images/quartiles_outliers.png">


Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot.

<img src="images/boxplot.png">


Generate a line plot of time point versus tumor volume for a single mouse treated with Capomulin.

<img src="images/line_plot_capomulin.png">


Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen. Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

<img src="images/scatter_plot_capomulin.png">


## Conclusions
1) Ramicane and Capomulin were the only two drugs that reduced the tumor sizes. They were the only two drugs with average final tumor volume less than the starting tumor volume (45 mm3) for each mouse. The rest of the drugs just slowed the tumor growths down or were ineffective. 
2) The heavier the mouse the more likely they will have a larger tumor volume. Sex of the mouse did not matter since the data was split evenly between genders.
3) Data might be slightly skewed for Ramican and Capomulin because those two drugs had more data points than the rest of the drugs.
