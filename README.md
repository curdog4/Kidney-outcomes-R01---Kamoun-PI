# Kidney-outcomes-R01---Kamoun-PI

8-1-2024: "HLA lab data extraction template.V2.0.Rmd" uploaded. This includes changes to allow for fuzzy matching between HistoTrac and the TIEDI data: 1. Matching recipients based on name and last 4 digits of SSN and 2. matching donors based on name.

5-10-2024: "HLA lab data extraction template.V1.5.Rmd" uploaded. This R code contains changes to how SSO results are captured from the Fusion server.

Instructions and code for extracting and formatting data to send to Penn. The R scripts are designed to be run in RStudio.

This repository contains several files and folders:

1. The "HLA lab data extraction overview" file contains an overview of the entire data extraction process.
2. The "TIEDI - UNOS" folder contains a file with instructions of how to download reports from TIEDI, and an R script for combining and formatting them for this project.
3. The "LIS extraction" folder contains instructions for setting up connections to HistoTrac and Fusion servers on a Windows computer, and contains an R script for extracting and formatting data for sending to Penn. Note the R script is a template only, and will absolutely not be plug-and-play. This script contains many comments to guide the user on each step.
4. The "Data schema" file contains info on the data and format of the files to be sent to Penn.
5. The "Example data" folder contains examples of tables to be sent to Penn.
