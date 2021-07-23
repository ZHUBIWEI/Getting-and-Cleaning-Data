# Getting-and-Cleaning-Data

1. Unzip the data from link https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename unzipped folder to dataset.
2. The run_analysis.R file should be placed in folder one level above from dataset folder.
3. Set your working directory to the folder where is run_analysis.R and the dataset folder.
4. Use source("run_analysis.R") to run the script.
5. Script creates 2 files. First file is named final_data.txt and contains merged data set. File tidy_data.txt contains tidy data with means for each subject and each activity across all variables.
6. You can use read.table("tidy_data.txt") to read tidy data into R.
