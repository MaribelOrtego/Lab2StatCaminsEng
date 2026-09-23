# Lab2StatCaminsEng
StatCamins Lab2 package. English version

# First steps to activate the tutorial

## Let's install the packages that we need. Installation is only done once. Package will be installed for next tutorials

install.packages("learnr")
install.packages("devtools")

## We activate the package (once per sessio if needed)
library("learnr")
library("devtools")

## Download the tutorial from the repository:

## Updated instruction. Careful! From R 4.6. it asks for Rtools/Xcode
pak::pak("MaribelOrtego/Lab2StatCaminsEng")
## Deprecated instruction. Still works
#devtools::install_github("MaribelOrtego/Lab2StatCaminsEng")

## Execute the tutorial:
learnr::run_tutorial("Lab2StatCaminsEng", "Lab2StatCaminsEng")

### And now follow the tutorial. ( Always follow the Next Page buttons) 
