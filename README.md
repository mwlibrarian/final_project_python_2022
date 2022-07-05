#Final project: Python for Data Analytics: Spring 2022

#https://colab.research.google.com/drive/1o5LVOGESf2W1mxKRr1RSWEe35ipUff91?usp=sharing

#I found my data set at https://data.norfolk.gov/Education/Library-Circulation-Statistics/e68x-a47n per the website 
#“This dataset contains information about circulation (checkouts) by item type for each Norfolk Public Library branch location by month.” I decided to 
#examine the various DVD collections to include movies that patrons can download as well. My goal was to take a slice of all the data for those collections 
#and match them across each location where patrons were checking out items. Thus, I had to do some investigation into the structure of the Norfolk Public 
#Library system (https://www.norfolkpubliclibrary.org/about-npl/hours-locations ) in order to decide how I was going to approach cleaning my data (combining 
#data points and eliminating data points) before I could start to use the data.

#While I was sorting and sifting through the data; I used the internet a lot in order to solve my various errors with creating code. The websites that I 
#visited most frequently were as follows:
#•	https://www.python-graph-gallery.com/stacked-area-plot/  
#•	https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.replace.html  
#•	https://realpython.com/python-counter/ 
#•	https://datacarpentry.org/python-ecology-lesson/03-index-slice-subset/
#•	https://pythonexamples.org/pandas-dataframe-sort-by-column/ 
#•	https://towardsdatascience.com/data-grouping-in-python-d64f1203f8d3 
#•	https://pythonguides.com/category/python-tutorials/matplotlib/ 

#During my exploration of Matplotlib and my dataframes, I tried several different types of graphs such as Scatter plots, Line charts, Histogram charts, 
#Bar charts, and Violin plots which were the most fun to plot. Sadly, most of my plotting and therefore my graphs were underwhelming. 
#Ultimately, I spent most of my time resifting, resorting, and slicing the data into more manageable pieces so that I could attempt to illicit a finding. 
#I do believe that I more than likely left a lot of good data on the “cutting room floor” but I tried. Not surprising to me was the finding that circulation
#of DVDs and even the use of downloaded movies took a nose dive across all the Norfolk Public Library. (I am a librarian by trade and worked in a public 
#library during the same timeframes covered by the “Year” data points within the dataset. I know firsthand how library item use were impacted here in the 
#Capital District of NY and I was curious to see if a southern state would show less deviation.)
