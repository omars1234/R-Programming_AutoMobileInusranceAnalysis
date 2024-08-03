# *Auto Mobile Insurance Analysis Using R-Programming Language*

## *Overview*

*This project aims to segment customers based on their purchasing behavior using clustering algorithms in R. The goal is to identify distinct customer groups to tailor marketing strategies effectively.*


## *Table of Contents*

*Installation*  
*Data*  
*Usage*  
*Project Structure*  
*Results*  

## *Installation*  
*To run this project, you need to have R installed on your machine. Additionally, install the required libraries by running the following commands:*

```bash
library(tidyverse)
library(skimr)
library(dplyr)
library(gridExtra)
library(patchwork)
library(effectsize)
library(coin)
library(rstatix)
library(car)
library(dunn.test)
library(nortest)
library(ggstatsplot)
library(FSA)
library(ggplot2)
library(FactoMineR)
library(psych)
```

## *Data*  
*The dataset used for this project contains AutoMobile Insurance data. It includes the following columns:*


*veh_value : The AutoMobile sum insured*

*exposure : earned exposures*

*clm : claims Incurrence  0:No ,1:yes*

*numclaims : number of claims frequency*

*claimcst0 :  Incurred claims cost*

*veh_body : BUS,SEDAN,COUPE,HBACK...etc.*

*veh_age : 1,2,3,4*

*gender : F : Female , M : male*

*area : A,B,C,D,E,F*

*agecat : 1,2,3,4,5,6*



You can download the dataset from here.



## *Usage*

*Clone the repository:*


```bash

```

## *Project Structure*


```bash
customer-segmentation/
├── Data/
│   └── data_car.csv
├── src/
│   ├── data_preprocessing.R
│   ├── clustering.R
│   ├── visualization.R
│   └── main.R
├── output/
│   └── clustering_results.png
├── README.md
```

* *data/: Contains the dataset.*

* *src/: Contains R scripts for data preprocessing,*

* *clustering, and visualization.*

* *output/: Contains the results of the analysis.*

* *README.md: Project documentation.*


## *Results*

The clustering analysis identified three distinct customer segments. The results are visualized in the output/clustering_results.png file. Each segment represents customers with similar purchasing behaviors, which can help in creating targeted marketing strategies.










									