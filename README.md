course-project-GCD
===============

Getting and Cleaning Data - Course Project

This project cleans and summarizes data from a larger dataset obtained from:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones#


Contents of this repository:

1.  run_analysis.R - The single R script used to generate a dataset output file "tidydata.txt"
2.  tidydata.txt - 83 variable, 180 observation output file in comma-separated value format
3.  CODEBOOK.md - codebook describing the contents of output dataset "tidydata.txt"
4.  downloaded data file and folder if script previously run (see below)

Procedure to run:

1. Set working directory in R
2. Execute run_analysis.R
3. The script will download this input data file set if it does not exist in the directory:

        getdata-projectfiles-UCI HAR Dataset.zip
        
4. The script will unzip this file into this folder:

        UCI HAR Dataset
        
5. The script will generate the output data set file

        tidydata.txt
        

        
