Exploratory Data Analysis Project 1 README and Code Book
========================================================

Data File Download, Extraction and Reduction
--------------------------------------------------------

**Source URL:**

    http://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip 

**Destination Directory:**

    G:/R_WorkingDirectory.d/ExploratoryDataAnalysis.d/Project1.d/dat.d/exdata_data_household_power_consumption
    
**Data File Name and Size:**

    household_power_consumption.txt *133 Mbytes*
    20070201.20070202.household_power_consumption.txt *0.365 Mbytes*
    
**Download and Extraction Methods:**

    Downloaded with IE Web Browser,
    Unzipped with With Windows Utilities

**Download Date And Time:** 

    2014-07-12 19:45 UTC
    
**Data Reduction Method for the Dates 2007-02-01 and 2007-02-02**


    *Utilized cygwin unix bash utilities:*

    cat household_power_consumption.txt | grep Date\; > 20070201.20070202.household_power_consumption.txt
    
    cat household_power_consumption.txt | grep "1/2/2007" | grep -v "21/2" | grep -v "11/2" >> 20070201.20070202.household_power_consumption.txt
    
    cat household_power_consumption.txt | grep "1/2/2007" | grep -v "22/2" | grep -v "12/2" >> 20070201.20070202.household_power_consumption.txt

    


