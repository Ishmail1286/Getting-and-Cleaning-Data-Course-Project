# Getting-and-Cleaning-Data-Course-Project
ReadMe
# Getting-Cleaning-Data-Project
Coursera Data Science Specialization Course 
Course Project

## Project Description
This project is an exercise in getting and cleaning data. 
The project uses data from the UCI, Repository: Human Activity Recognition Using Smartphones. Data site: [Description here.] (http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones). Data for the project can be downloaded here: (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).

### Data Processing Script: run_analysis.R
The R script run_analysis.R reads the data files and combines them into one full data file.  Important variable values are renamed from numbers to meaningful names. The full set of variables is reduced to a subset that involve means and standard deviations. Variable names are changed to conform with R's prototype variable names and to be descriptive.

### Tidy Data Output: tidyDataset.txt
The data is then grouped by subject and activity, and summarized by each variable's mean. The end result is a tidy data set, conforming to Hadley Wickham's tidy data principles. The tidy data set is written to the file tidy.txt.

### Data Processing Description and Variable Names: CodeBook.txt
The file (CodeBook.txt) describes the processing steps and variables used in run_analysis.R and supplements the README.txt included in the original downloaded archive.
