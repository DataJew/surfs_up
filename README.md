# Surfs Up

## Project Summary and Background
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## What You're Creating

> This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:

1. ***Deliverable 1***: Determine the Summary Statistics for June
2. ***Deliverable 2***: Determine the Summary Statistics for December
3. ***Deliverable 3***: A written report for the statistical analysis [`README.md`](https://github.com/DataJew/surfs_up). 


## Deliverable 1:  Determine the Summary Statistics for June
Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

### Deliverable Requirements:
You will earn a perfect score for Deliverable 1 by completing all requirements below:

1. A working query is written to retrieve the June temperatures from the `date` column of the `Measurement` table.
2. The temperatures are added to a list.
3. The list of temperatures is converted to a Pandas DataFrame.
4. Summary statistics are generated for the DataFrame.


### Deliverable 2: Determine the Summary Statistics for December.
Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of December. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

### Deliverable Requirements:
You will earn a perfect score for Deliverable 2 by completing all requirements below:

1. A working query is written to retrieve the December temperatures from the `date` column of the `Measurement` table.
2. The temperatures are added to a list.
3. The list of temperatures is converted to a Pandas DataFrame.
4. Summary statistics are generated for the DataFrame


## Deliverable 3: A written report for the statistical analysis
For this part of the Challenge, write a report that describes the key differences in weather between June and December and two recommendations for further analysis.

### The analysis should contain the following:

1. **Overview of the analysis:** Using Python, Pandas functions and methods, and SQLAlchemy, we’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of June. We'll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics. Once our dataframe is created we are able to get our summary statistics by using the `df.describe()` code and method. 

2. **Results:** Data Provided gave us a visibility that on months of June and December, our location had a total Temps of:

**June Temps - Analysis and Result**
* Count of 1700 
* Mean of 74.94 
* Std of 3.26 
* Min of 64.00 
* 25% of 73.00 
* 50% of 75.00
* 75% of 77.00
* Max of 85.00


**June Temps - Report**
> Image with `Jupyter Notebook` & `Python` Code below.
![name-of-you-image](https://github.com/DataJew/surfs_up/blob/main/Resources/images/June_df_describe.png)

**December Temps - Analysis and Result**
* Count of 1517 
* Mean of 71.04 
* Std of 3.75
* Min of 56.00 
* 25% of 69.00 
* 50% of 71.00
* 75% of 74.00
* Max of 83.00


**December Temps - Report**
> Image with `Jupyter Notebook` & `Python` Code below.
![name-of-you-image](https://github.com/DataJew/surfs_up/blob/main/Resources/images/June_df_describe.png)

3. **Summary:** 

    We can observe the standard deviation is 3.25 in June and 3.75 in December, a 0.5 difference between both seasons.
 
    In addition, current data provides attributes such precipitation and others, with two queries performing weather data for June and December that helps valudate business decisions such as location and materials.
