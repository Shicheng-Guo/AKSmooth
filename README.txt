AKSmooth
========

Ajusted local kernel smoothing for low-coverage bisulfite sequencing data.


1. INSTALL

# Download and unzip this file, and run the following codes in R:

install.packages("devtools") 
library(devtools)

# Find the directory where AKSmooth-master file is located and set the following new working directory.
setwd("./AKSmooth-master") 

# Load the package into memory
load_all()

# Install the package 
install()

2. USAGE

# After installation one can reload the AKSmooth package.
library(AKSmooth)

3. Example
git clone 

load("./data/bn1chr1.rda")
data <- bn1chr1
fitChr21gau <- AKSmooth(data, 30, "Gaussian")

4. Update:

1, Change the format of input as the classic bedgraph format
2, Test the senstivity and Specificity
3, Compared with HMM model



