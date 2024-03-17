# Project Title

Exploring the Evaluation of Factors Affecting Coffee Quality

## Project Introduction

Coffee is globally beloved for its rich flavor and stimulating properties, but its quality can vary based on factors like origin, altitude, and processing methods. To understand these influences, our project aims to analyze a dataset containing coffee characteristics such as origin, altitude, harvest year, aroma, flavor, and acidity. Utilizing a Generalized Linear Model (GLM), we seek to uncover the relationships between these features and the classification of coffee quality as either good or poor.

## Project Functionality

### Data Preprocessing

Convert data types, primarily including converting quality classification variables into binary form (good quality as 1, poor quality as 0), converting harvest year into categorical variables; remove missing values; and remove outliers with altitude greater than 8848 meters.

### Data Visualisation

Create boxplots of aroma, flavour, and acidity, as well as Category_two_defects and Altitude_mean_meters, to explore the characteristics of coffee beans, then draw a bar chart to investigate whether there is any relationship between coffee quality and the year of harvest. Finally, discuss the correlation between variables.

### Principal Component Analysis

Perform principal component analysis on the three variables exhibiting significant multicollinearity to obtain the loading matrix and scree plot, then select the first principal component as the variable for the model.

### Creating Model

Building GLM model and analyzing its results.

## Installation

To execute the core functionalities of this project, make sure you have the required R libraries installed.

```{r}
library(ggplot2)
library(readr)
library(tidyverse)
library(knitr)
library(stringr)
library(jtools)
library(GGally)
library(gridExtra)
library(factoextra)
```

You can install these libraries by executing the following commands in R:

```{r}
install.packages("ggplot2")
install.packages("readr")
install.packages("tidyverse")
install.packages("knitr")
install.packages("stringr")
install.packages("jtools")
install.packages("GGally")
install.packages("gridExtra")
install.packages("factoextra")

```

Once the libraries are installed, you can proceed to open Group_13_Analysis.qmd and commence running our project.

## Authors

**Shuyin Chen, Xuran Wang, Yingying Zhuo, Yunfei Chen, Yuxuan Li**
