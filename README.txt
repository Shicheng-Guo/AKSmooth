AKSmooth
========

Ajusted local kernel smoothing for low-coverage bisulfite sequencing data.


1. INSTALL

# git clone from my github: https://github.com/Shicheng-Guo/AKSmooth.git

cd /home/shg047/software/
git clone https://github.com/Shicheng-Guo/AKSmooth.git
cd /home/shg047/software/AKSmooth/R

2. USAGE

# After installation one can reload the AKSmooth package.
source(AKSmooth.R)

3. Example

cd /home/shg047/software/
git clone https://github.com/Shicheng-Guo/AKSmooth.git
cd /home/shg047/software/AKSmooth/R
source(AKSmooth.R)
load("./data/bn1chr1.rda")
data <- bn1chr1
fitChr21gau <- AKSmooth(data, 30, "Gaussian")

Note: fitChr21gau is the fitted methylation levels

4. Update:

1, Change the format of input as the classic bedgraph format
2, Test the senstivity and Specificity
3, Compared with HMM model



