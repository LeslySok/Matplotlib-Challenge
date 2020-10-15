# Matplotlib-Challenge
The Power of Plots

 I've taken what I've learned about Python Matplotlib and applied it to this real-world situation and dataset:

![](Images/Laboratory.jpg)


This challenge is for Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. I've been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.


I started this analysis, by checking the data for any mouse ID with duplicate time points and removed any data associated with that mouse ID.

Using the cleaned data a summary statistics table was generated consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.


![](Images/summarystatistictable.png)



A bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows  the number of total mice for each treatment regimen throughout the course of the study.


![](Images/NumberofMiceperTreatment.png)



A pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.


 ![](Images/MalevsFemaleMousePopulation.png)


I've Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.


Using Matplotlib, a box and whisker plot was generated of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.


![](Images/FInalTumorVolumeperRegimen.png)


I selected mouse 'b128' that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.


![](Images/Mouseb128TreatmentwithCapomulin.png)


A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.


![](Images/MouseWeightvsAverageTumorVolume.png)


Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.


![](Images/MouseWeightvsAverageTumorVolumeP2.png)



