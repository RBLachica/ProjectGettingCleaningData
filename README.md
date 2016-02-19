

##GETTING AND CLEANING DATA

##INTRODUCTION
The repository contains course project for the course "Getting and Cleaning data" as part of the Data Science specialization. 
Below are the notes from the original dataset. 

##ABOUT THE RAW DATA
The features unlabeled and can be found in the x_test.txt. The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file. The same holds for the training set.

##ABOUT THE SCRIPT AND TIDY DATASET 
I created a script called run_analysis.R which will merge the test and training sets together. Prerequisites for this script:

    (1)The UCI HAR dataset must be extracted and
    (2)The UCI HAR dataset must be availble in a directory called "UCI HAR Dataset"

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.

##ABOUT THE COOK BOOK
The CodeBook.md file explains the transformations performed and the resulting data and variables.
