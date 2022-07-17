# Analysis-Of-Airplane-Crashes-From-1908-to-2009
This Project is my capstone project to signify my completion of the #30DaysOfLearning Bootcamp. I have learnt a lot from the boot camp and I hope this project shows how far I've come.

----
# Project Objective
The aim of this analysis is to gain insights from the data provided and see the information that can be deduced and the recommendations that can be given.

----
# Data Source
The dataset used for this analysis was collected from kaggle. The link to the dataset is https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908

----
# Data Transformation
The dataset contained a lot of columns that were not useful to the analysis. Those columns were removed in the Power Query Editor. Also, colums that were mostly empty were also removed. Example, was the 'Time' column, a definite time of crash was not recorded for most of the crashes, and sp leaving the column would just add moise to the dataset. The 'Date' column was given the datatype of text, and a lot of the entries returned an error message when I tried to change the datatype. I noticed that this was because the the date format was in the mm/dd/yyyy format and power query could not read the inputs. I solved this problem by going to the regional settings and setting my Locale for Import to the Unted States which is one of the countries that uses that particular ate format. I also added an index column to the table for easy analysis. Finally, I cleaned all columns with number datatype by replacing the empty rows with 0, and removing entries with error. Below is a preview of the table when I was done cleaning. <br/>
<img src="https://github.com/Ipseity-169/Analysis-Of-Airplane-Crashes-From-1908-to-2009/blob/main/Airplane%20Crashes%20images/Preview(01).png" height="400" width="400">
<img src="https://github.com/Ipseity-169/Analysis-Of-Airplane-Crashes-From-1908-to-2009/blob/main/Airplane%20Crashes%20images/Preiew(02).png" height="400" width="400">
<br/>
<a href="https://github.com/Ipseity-169/Analysis-Of-Airplane-Crashes-From-1908-to-2009/blob/main/Airplane_Crashes_and_Fatalities_Since_1908%5B1%5D.csv">This is the link to get the raw CSV file </a>

----
# Data Analysis
On Anayzing the data set, the following information was gotten:
<h3>The Trend of Airplane crashes from 1908 to 2009</h3>
<img src="https://github.com/Ipseity-169/Analysis-Of-Airplane-Crashes-From-1908-to-2009/blob/main/Airplane%20Crashes%20images/TrendOverYears.jpg" width="400" height="400">
</br>

<h3>The Total Count of Crashes, Fatalities, and Survivors</h3>
<img src ="https://github.com/Ipseity-169/Analysis-Of-Airplane-Crashes-From-1908-to-2009/blob/main/Airplane%20Crashes%20images/CountOfCrashesFatalitiesAndSurvivors.jpg" height="400 width="400">
</br>

<h3>Months with the Highest Airplane Crashes Occurence</h3>
<img src="https://github.com/Ipseity-169/Analysis-Of-Airplane-Crashes-From-1908-to-2009/blob/main/Airplane%20Crashes%20images/MonthsWithHihestCrashes.jpg" height="400" width="400">
</br>

<h3>Plane types with the Highest Recorded Crashes</h3>
<img src="https://github.com/Ipseity-169/Analysis-Of-Airplane-Crashes-From-1908-to-2009/blob/main/Airplane%20Crashes%20images/PlanesWithHighestNumberOfAccident.jpg" width="400" height="400">
</br>

<h3> Airplane Operators with the Highest Recorded Crashes</h3>
<img src="https://github.com/Ipseity-169/Analysis-Of-Airplane-Crashes-From-1908-to-2009/blob/main/Airplane%20Crashes%20images/OperatorsWithHighestCrashes.jpg" height="400" width="400">
</br>

----
# Insight Gained from the Analysis
<h3>Below are the insights gained from this analysis</h3>
<img src="https://github.com/Ipseity-169/Analysis-Of-Airplane-Crashes-From-1908-to-2009/blob/main/Airplane%20Crashes%20images/InsightGained.jpg" height="400" width="500">
</br>
<a


