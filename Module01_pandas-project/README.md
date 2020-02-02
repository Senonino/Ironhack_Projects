![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Project: Data Cleaning and Manipulation with Pandas

## Overview

The goal of this project is to show some of the things I have learned about data wrangling, cleaning, and manipulation with Pandas. For this project, I will start with this messy data set [Shark Attack](https://www.kaggle.com/teajay/global-shark-attacks/version/1). I will start by importing it, then use my data wrangling skills to clean it up as much as possible, prepare it to be analyzed, and then export it as a clean CSV data file.

---

## Technical Requirements

The technical requirements for this project are as follows:

* The dataset is a significantly messy data set. I will be apply the different cleaning and manipulation techniques I have learned so far.
* first step is importing the data using Pandas.
* Then Examining the data for potential issues.
* The end result is a Jupyter Notebook that shows the steps I took and the code I used to clean and transform the dataset.
* Export a clean CSV version of your data using Pandas.

## Final results

The following is included in my project02 Github repo for this chapter.

* **A cleaned CSV data file** containing the results of my data wrangling work.
* **A Jupyter Notebook (data-wrangling.ipynb)** containing all Python code and commands used in the importing, cleaning, manipulation, and exporting of my dataset.
* **A ``README.md`` file** containing a detailed explanation of the process followed in the importing, cleaning, manipulation, and exporting.

## Steps followed in this project

* ** import all needed modules
    #droping the year, Unnamed: 22 and Unnamed: 23 columns cos Year columns is contained in the Date column and the Unnamed: 22 and Unnamed: 23 are practically empty.

* ** load dataset

* ** Check the dateset and validate the content

* ** drop unneeded columns

* ** change columns names to proper names

* ** change M and F in the sex column to Male and Female

* ** make Age column proper int
	#force to numeric type
	#replace nan with 0's
	#cast type "int" instead of "int"

* ** make Time column proper time
	#remove all non-numeric characters
	#add the ":"
	#replace nan's with 0's
	#cast date time type to the column(not working in this case)

* ** make Date column proper date
	#remove all non-numeric characters
	#replace nsn's with 0's
	#cast date time type to the column(not working in this case)

* ** remove wronge wordings in the Name column

* ** switch the "'" to "m" in the Species column and remove the nan's

* ** Droping the rows with nan's in them

* ** export file

## Useful Resources

* [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
* [Pandas Tutorials](https://pandas.pydata.org/pandas-docs/stable/tutorials.html)
* [StackOverflow Pandas Questions](https://stackoverflow.com/questions/tagged/pandas)
* [Awesome Public Data Sets](https://github.com/awesomedata/awesome-public-datasets)
* [Kaggle Data Sets](https://www.kaggle.com/datasets)
