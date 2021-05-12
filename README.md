# Affectivism-Dataset
This repository contains the R scripts(Rmd) to analyze, and generate the plots for the "Affectivism-Dataset" project.

## Getting Started
#### Prerequisites
* R and RStudio
* Required packages: dplyr, ggplot2, scales, zoo, ggpubr, png, jpeg,and lubridate
#### Installing R Packages
Packages are available on CRAN and can be installed using a simple call to ```install.packages()```:
```
install.packages('PackageName')
```
#### Dataset requirement:
* Download the dataset from https://osf.io/2ktnv/
* Save the data files in Data folder 

## Script Set
1. **Paper Ready combined plot**
     - final_single_plot.rmd
         * The script does the following things:
            * Budget of NIMH on Affective research
              * Read the NIMH_emoVSnonemo.csv file
              * Keep only data for 1985-2018
              * Run the regression model
              * Draw a barplot for NIMH funding 
            * Growth of the Emotion(EM) publications: 
              * Read the timeline_Emotions.csv and timeline_behavior.csv files
              * Keep only data for 1980-2018
              * Calculate the EM percentages
              * Run the regression model
              * Draw the Yearly Publication barplot
            * Penetration of affectivism in key areas of Psychology since 1980
              * Read all the timeline files related to Attention, Decision Making, Memory, and Perception
              * Keep only data for 1980-2018
              * Calculate the EM percentages
              * Draw the Yearly publication bar plots for Attention, Decision Making, Memory, and Perception  
            * Finally, save as full_figure_affective_research.jpg file 
            
               
