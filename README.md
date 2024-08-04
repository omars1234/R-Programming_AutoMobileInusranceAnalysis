# *Auto Mobile Insurance Analysis Using R-Programming Language*

***👩‍💻  Still under proccess...***

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

*Out of 67856 risk , we have 4624 with positive claims claims*

*Gender*
* *female had more claim percentage than males*

* *after applying pearson chisq test we found there is no significant difference between genders in respect of claims*

*area*
* *area A has the highest number of claims with '31%'  percentage* 

* *area F has the lowest number  of claims with '6.1%' percentage*

* *after applying pearson chisq test we found there is significant difference between areas in respect of claims*

*Age Category*  

* *Age Category 2 and 4 have  the highest number of claims with '24%' percentage for each -'noting that both categories has the highest count of total agecat observations'-*  

 * *Age Category 6  has the lowest number  of claims with '7.9%' percentage*    

 * *after applying pearson chisq test we found there is significant difference between Age Categories in respect of claims*

*Vehicle Age*
* *Vehicle Age 3 has highest number of claims with '29%' percentage-'noting that it has the highest count of total Vehicle Age categories observations'-*  

* *Vehicle Age 1 has the lowest number  of claims with '18%' percentage*   

* *after applying pearson chisq test we found there is significant difference between Vehicle Ages in respect of claims*


*veh_body*

* *Sedan veh_body  has highest number of claims with '32%' percentage-'noting that it has the highest count of total veh_body observations'-* 

* *convt and RDSTR veh_body has the lowest number  of claims with less than '0.1%' percentage*


### *Inferential Analysis :*

*The Anderson-Darling normality test (p-value < 0.05) indicates non-normal distribution*

*==> Given these results, We will be using non-parametric statistical tests*

*A.1 Mann-Whitney U Test on claimcst0 against gender :*

* *statistically there is significant difference in the data distribution between genders*

* *The wilcox_effsize test showed that the effect size= .0315 and the indicating small effect size*

* *leveneTest indicates that the variances are significantly different across the groups*

* *Post-hoc Power Analysis : The power of the test is 0.3277674,This means there is a 32.77% chance of detecting a true effect*

*B.1 kruskal.test on claims against area :*

* *statistically there is significant difference in the data distribution between areas*

* *he kruskal_effsize test showed that the effect size (epsilon_squared)= 0.004680724 and the indicating small effect size*

* *leveneTest indicates that the variances are significantly different across the groups*

* *Post-hoc Power Analysis : The power of the test is 0.966717,This means there is a 96% chance of detecting a true effect*


*B.2 kruskal.test on claims against veh_body*

* *statistically there is no significant difference in the data distribution between veh_body*

*B.3 kruskal.test on claims against age category*

* *statistically there is significant difference in the data distribution between agecat*

* *The kruskal_effsize test showed that the effect size (epsilon_squared)= 0.001320641 and the indicating small effect size*

* *leveneTest indicates that the variances are significantly different across the groups*

* *Post-hoc Power Analysis : The power of the test is 0.4397375,This means there is a 43.9% chance of detecting a true effect*


*B.4 kruskal.test on claims against number of claims*

* *statistically there is significant difference in the data distribution between numclaims*

* *The kruskal_effsize test showed that the effect size (epsilon_squared)= 0.0337713 and the indicating small effect size*

* *leveneTest indicates that the variances are not significantly different across the groups*

* *Post-hoc Power Analysis : The power of the test is 1,This means there is a 100% chance of detecting a true effect.*

*B.5 kruskal.test on claims against veh_age*

* *statistically there is significant difference in the data distribution between veh_age*

* *he kruskal_effsize test showed that the effect size (epsilon_squared)= 0.003391443 and the indicating small effect size*

* *leveneTest indicates that the variances are not significantly different across the groups*

* *Post-hoc Power Analysis : The power of the test is 0.92,This means there is a 92% chance of detecting a true effect*













-------------------------










[![rpubs](src/rpubslogo.png)](http://rpubs.com/omars/1208635)


***👩‍💻  Still under proccess...***








