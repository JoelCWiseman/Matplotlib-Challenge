# Matplotlib-Challenge

In this challenge you will find a summarication of the data from multiple studies in Mice of the range of experimental treatments for tumors. Care was taken to ensure that any duplicates were accounted for a removed from the reported data set to avoid potential 
double reporting of data for that subject, which would skew the results.

Upon initial review out of the 10 potential treatments, 2 appear to be promising for further research given their ability to reduce tumor growth. The successful treatments are Capomulin and Ramicane, they both produced the lowest tumor volumes throughout the 
trials, as well as producing the lowest final max tumor volume. That said, they do both have potential outliners (2 for Capomulin, 1 for Ramicane) that we would need to look into. Having said that I have called out a specific subject below "L509", who after 
day 20 of treatment with Capomulin had a significant drop in tumor volume.

One other set of data to point out is visible in the last chart of this set that provides a scatter view of the mouses weight(g) vs. average tumor volume and takes into account the r-value. With an r-value of 0.84, there appears to be a strong correlation 
between mouse weight and the volume of the tumor.

Code for this challenge, as well as sources for trouble shooting errors came from in class examples, https://matplotlib.org/2.0.2/examples/index.html and https://matplotlib.org/stable/api/pyplot_summary.html. 
Additionalally my copy of Python for Data Analysis: Data Wrangling with pandas, NumPy, and Jupyter 3rd Editiion by Wes McKinney (https://wesmckinney.com/book/), proved to be a valuable resource as well.
