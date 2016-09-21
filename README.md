# projects

Project files for the labs in the Coursera [Statistics with R](https://www.coursera.org/specializations/statistics) specialization.

## Software Requirements

**Install R and RStudio:**

First, you will need to install R and RStudio. R is the name of the programming language itself and RStudio is a convenient interface.

 - Install R: Go to https://cran.r-project.org/ and follow the link for your operating system.
 - Install RStudio: Go to https://www.rstudio.com/products/rstudio/download/ and click on the installer link for your operating system.

NOTE: If you already have R and RStudio installed, you should still visit these links to confirm that you have the most recent versions of these software. The most recent version of R can be found on The R Project for Statistical Computing page and the most recent version of RStudio can be found on the Download RStudio page. Please install the most recent versions before proceeding.

**Install R packages:**

Install and load devtools:

We will use the devtools package to install the statsr package associated with this course. We need to install and load this package. Launch RStudio, and the following commands in the Console:

```
install.packages("devtools")
library(devtools)
```

Install all other packages:

Now we can install the rest of the packages we will use in the projects. Type the following commands in the Console as well:

```
install.packages("dplyr")
install.packages("ggplot2")
install.packages("GGally")
install.packages("BAS")
install_github("StatsWithR/statsr")
```

## Table of Content

**P1: Introduction to Probability and Data**
- Explanatory data analysis based on Behavioral Risk Factor Surveillance System (BRFSS) 2013 dataset. Health care coverage ratio, flu shot in the past 12 months ratio, and percentage distribution of Body Mass Index (BMI) classes were examined in this project.

**P2: Inferential Statistics**
  - Explanatory data analysis and inference based on General Social Survey (GSS) 1972-2014 dataset. Mother’s average age at first birth in 2011 for the United States according to the GSS dataset is compared againts the one according to “The World Factbook” by CIA.

**P3: Linear Regression and Modeling**
  - Exploratory data analysis and multiple linear regression modeling for movie data. The data set is comprised of 651 randomly sampled movies produced and released before 2016. Based on the regression model, prediction is made on popularity of a new movie that is not in the sample. Uncertainty around this prediction is quantified with confidence interval.

**P4: Bayesian Statistics**
  - Exploratory data analysis and bayesian modeling for movie data. The data set is comprised of 651 randomly sampled movies produced and released before 2016. Based on the bayesian model, prediction is made on popularity of a new movie that is not in the sample. Uncertainty around this prediction is quantified with credible interval. Bayesian Model Averaging approach is also explored in this project.

**P5: Capstone Project**
  - More details coming soon.