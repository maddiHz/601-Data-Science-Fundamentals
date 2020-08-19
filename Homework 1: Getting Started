# Hertz_DSF_HW1.R
# Script for HW 1
#
# mh 08.06.2020

# This stuff is my header. I should always make sure scripts start with a header

# Now set the working directory so R knows where to look/save my files
# I'm using Dropbox to stay organized and store/backup my files in the cloud
setwd("/Users/MaddisMac/Dropbox/Data_Science_Fundamentals_601_SU2020")

# The tidyverse package is already installed in R
# But I need to load it into this R session with library()
library(tidyverse)

# =-=-=-=-=-=-=-=-=-=-=-=-
# Review the basics
# =-=-=-=-=-=-=-=-=-=-=-=-

# The assignment operator "<-" stores objects in the environment
hello <- paste("Hello World!")

# Cool, now I can see it in the environment over there ->
# Now when I type hello, R "pastes" the line of text that says "Hello World!"
hello

# =-=-=-=-=-=-=-=-=-=-=-=-=-
# Reading in Data
# =-=-=-=-=-=-=-=-=-=-=-=-=-

# I'm working with the Congressional Hearings dataset
# It's a csv file so I use read_csv to read it into R
Congressional_Hearings <- read_csv("legislative_hearings.csv")

# R can find the file because it's in my working directory!

# It created an object called Congressional_Hearings
# Now I can see Congressional_Hearings in the environment too
# It has 100254 observations of 36 variables

# I don't need to specify the delimiter because I'm using read_csv
# read_csv reads in a header row by default

# R gave me some warnings (in red) when I opened the dataset
# But I don't need to worry about them just yet

# I can check that R read the headers correctly and preview the first few rows 
# with head()
head(Congressional_Hearings)

# I successfully opened my dataset in R and saved my code as an R script
# Fantastic! Next, more data exploration
