# Matplotlib Challenge - The Power of Plots

## Background

**What good is data without a good plot to tell the story?**

Pymaceuticals Inc., is a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

![Lab](/images/lab.gif)

## Accomplishments

### Tasks

1. Before beginning the analysis, *check* the data for any mouse ID with **duplicate time points** and remove any data associated with that mouse ID.

2. Use the *cleaned data* for the remaining steps.

3. Generate a **summary statistics** table consisting of the **mean, median, variance, standard deviation, and SEM** of the *tumor volume for each drug regimen*.

4. Generate a *bar plot* using both **Pandas's DataFrame.plot()** and **Matplotlib's pyplot** that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

5. Generate a *pie plot* using both **Pandas's DataFrame.plot()** and **Matplotlib's pyplot** that shows the distribution of female or male mice in the study.

6. Calculate the *final tumor volume* of each mouse across four of the most promising treatment regimens: **Capomulin, Ramicane, Infubinol, and Ceftamin**. Calculate the *quartiles and IQR* and quantitatively determine if there are any potential outliers across all four treatment regimens.

7. Using **Matplotlib**, generate a *box and whisker plot* of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

8. Select **a mouse** that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

9. Generate a *scatter plot* of tumor volume versus mouse weight for the Capomulin treatment regimen.

10. Calculate the *correlation coefficient and linear regression model* between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

## Results

* The population of males and female are equally distributed among the mice in the research.

* Capomulin and Ramicane are the drug regimens with the most observations, and both have proven to be the most successful at tumor reduction.

* The average tumor volume and weight of mice have a close relationship.

[Pymaceuticals](/Pymaceuticals/pymaceuticals_starter.ipynb)