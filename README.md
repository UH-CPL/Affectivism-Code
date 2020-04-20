# Affectivism-Manifesto
This repository contains the R scripts(Rmd) to analyze, and generate the plots for the "Affectivism-Manifesto" project.

## Getting Started
#### Prerequisites
* R and RStudio
* Required packages: dplyr, ggplot2, scales, zoo, ggpubr, and lubridate
#### Installing R Packages
Packages are available on CRAN and can be installed using a simple call to ```install.packages()```:
```
install.packages('PackageName')
```

## Script Set
1. Growth of the Emotion(EM) publications:
     - yearlyPublicationPubMed.rmd
          * The script does the following things:
            * Read the timeline_Emotions.csv and timeline_behavior.csv files
            * Keep only data for 1980-2018
            * Calculate the EM percentages
            * Run the regression model
            * Draw the Yearly Publication barplot and Regression plot and save as pubMedyearlyPlot.png
