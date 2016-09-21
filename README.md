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