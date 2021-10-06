Data Cleaning
By Moamen Mohasseb
The Business Problem
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.
Step 1: Business and Data Understanding
1.	which City to open a new store?
Factors to choose specific city like population density, total families …etc.
2.	What is the predicted yearly sales for this city?
Factors to predict city with highest yearly sales like other stores sales , population density … etc.
Step 2: Building the Training Set
We consolidating the data at the city level sum and average
column	sum	average
Total Pawdacity Sales	3773304.00	343027.64
Population Density	62.80	5.71
Total Families	62652.79	5695.71
Households with Under 18	34064.00	3096.73
Land Area	33071.38	3006.49
Census Population	213862.00	19442.00

Step 3: Dealing with Outlier

There are two City with outliers in the training set : Cheyenne and Gilette. I have decided to remove Cheyenne because it has outliers in “Total Pawdacity Sales” due to large “Population Density”  as we can see in the  below chart .for “Gillette” I will keep it by reduce “Total Pawdacity Sales”  to the upper fence 466776 .






 
