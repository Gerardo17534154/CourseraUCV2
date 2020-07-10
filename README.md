# CourseraUCV2
Course Project 2
Initial Steps

Step 1: Load R Packages

library(dplyr)
library(ggplot2)
library(scales)
library(data.table)

Step 2: Data input

NEI <- readRDS("summarySCC_PM25.rds")
SCC <- readRDS("Source_Classification_Code.rds")

Step 3: Initial data exploration for analysis

head(NEI)

str(NEI)

After this steps, the answers....
