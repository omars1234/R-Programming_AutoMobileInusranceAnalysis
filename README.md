# *Auto Mobile Insurance Analysis Using R-Programming Language*

## *Author*

- [@Omar Soub](https://github.com/omars1234)


## *Overview*

*On this Project ,we will use R-Programming Language in order to conduct inferential analysis to analyse the data as much as we can to help decision making*


* *To access the project online on Rpubs Web ,Click on the below link*

  [*AutoMobilePricesAnalysis-http://rpubs.com/omars/1207895*](http://rpubs.com/omars/1208635)  
  
  

  ------------------------------------------------------------------

  ![Logo](src/AutoinsuranceLogo.png)

  ------------------------------------------------------------------ 

  


## *Table of Contents*

*  *Installation*  
*  *Data*  
*  *Usage*  
*  *Project Structure*  
*  *Results*  


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
https://github.com/omars1234/R-Programming_AutoMobileInusranceAnalysis.git
```

## *Project Structure*


```bash
customer-segmentation/
├── Data/
│   └── data_car.csv
├── src/
│   ├── AutoInsurance_R.Rmd
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


[![rpubs](src/rpubslogo.png)](http://rpubs.com/omars/1208635)


***👩‍💻  Still under proccess...***








