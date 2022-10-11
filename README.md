# SQL-TO-R
connecting data base from sql to r
read.csv(data file) # code on R
query <- read.csv(data file)
library(DBI)
library(dplyr)
library(dbplyr)
library(odbc)
subset(df, ( data variable), select=c(data$category))
dbGetQuery()
