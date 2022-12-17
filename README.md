# INFS692
Data Science with R

**There is a problem initialize the h2o on chunck 13 on Dec 16th, which does not allow me to knit the pdf. So, Model1 report is based on the first version which did not convert the Institution to categorical variables. Model1 markdown file is updates which has the categorical value conversion set**

## The final submission is in the final project folder
### There are three models: 
1. Model1 with stacking
3. Model2 with DNN
4. Model3 with K-means, hierarchy and model-based

#### Model 1 libraries:
library(tidymodels)<br>
library(plyr)<br>
library(caret)<br>
library(caretEnsemble)<br>
library(readr)<br>
library(ggplot2)<br>
library(tidyverse)<br>
library(rpart)       # for fitting decision trees<br>
library(ipred)       # for fitting bagged decision trees<br>
library(pROC)<br>
library(h2o)<br>
library(ggcorrplot)<br>
library(ROCR)<br>
library(recipes)<br>
remotes::install_github("kforthman/caretStack")<br>

#### Model 2 libraries:
library(tensorflow)<br>
library(keras)<br>
library(caret)<br>

#### Model 3 libraries:
library(dplyr)<br>
library(factoextra)<br>
library(cluster)<br>
library(mclust)<br>

**There are alternative visualizations and approaches written in the code file**<br>
**Uncomment the cells to show the results**<br>
**Some printed are too long, so delete the invisible() function to check the whole results**<br>
