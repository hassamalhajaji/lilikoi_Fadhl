## Lilikoi is a novel tool for personalized pathway analysis of metabolomics data. 

## Installation

To install all the required packages without overwriting your installed packages, you can run the below lines:

list.of.packages <- c("ggplot2", "caret","dplyr ","pathifier","RWeka","infotheo","pROC","reshape2")
new.packages <- list.of.packages[!(list.of.packages %in% installed.packages()[,"Package"])]
if(length(new.packages)) install.packages(new.packages)


if you have problem with installing Rweka as it requirtes Java, you can reconfiguring R from the command line by runing the below line:
R CMD javareconf
https://gist.github.com/mmulvahill/ddd75eb352979cc922bae001505833cb

# Example Code

