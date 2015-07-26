This is a repository for written for the Course Project in Coursera course through Johns Hopkins University.

find all project-related materials in the UCI HAR Dataset directory : http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Download and Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, say C:\Desktop\R\

Put run_analysis.R into C:\Desktop\R\UCI HAR Dataset\

In RStudio: setwd("C:\\Desktop\\R\\UCI HAR Dataset\\"), followed by: source("run_analysis.R")

Use data <- read.table("data_set_with_the_averages.txt") to read the data. Then, type View(data) to view the data.
It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. 


