# Matplotlib-Challenge

#Files:

[Mouse_metadata.csv](https://github.com/Kaileycar/matplotlib-challenge/files/11640188/Mouse_metadata.csv)
[Study_results.csv](https://github.com/Kaileycar/matplotlib-challenge/files/11640189/Study_results.csv)

# Overview:
I read in my csv files and worked on grouping, merging, finding statistic values, and finding correlation / line regression of the data. I then wrote an analysis of my findings and compared the drug regimens used to the drug regimen of Capomulin to see how they compared. 

# Helpful Sites:

https://www.geeksforgeeks.org/find-duplicate-rows-in-a-dataframe-based-on-all-or-selected-columns/: duplicated function
https://stackoverflow.com/questions/40874935/subsetting-duplicate-rows-in-python: duplicate function
Both of these websites helped me figure out how to use the 'duplicated' function in order to get the Mouse ID with duplicated timepoints.


https://www.geeksforgeeks.org/python-pandas-dataframe-drop_duplicates/: I used this website to help me figure out the 'drop duplicates' function while trying to generate my summary statistics. I tried using the drop duplicates to find each drug regimen, but kept coming up with erros. I finally decided to scrap this approach and look for a new one.


https://www.statology.org/pandas-drop-rows-that-contain-string/: I used this website trying to figure out how drop the Mouse ID 'g989'. It talked about using the function 'str.contains' to drop a string value in a column. Again, I came up with errors trying this method so ultimatley I went with the method of '!=" to drop that Mouse ID from the column.


https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.agg.html: This website helped me with the optional cell of using the 'agg method' to find the mean, median, variance, standard deviation, and sem of the tumor volume per drug regimen.


https://matplotlib.org/3.1.1/gallery/statistics/boxplot.html: I used this website to figure out how to chnage the marker size and color of the outlier in the boxplot.
