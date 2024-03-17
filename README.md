# 🏘Exploring Household Dynamics in the Philippines

## 🏡Introduction

> 📌The household setup in the Philippines presents a blend of traditional and modern structures. This analysis aims to **find the factors that contribute to the number of individuals residing in a single household**.  Understanding these dynamics helps shaping social policies, economic assistance programs, and urban planning.

## 🏠Data Description
- **Total.Household.Income** – Annual household income (in Philippine peso) 
- **Region** – The region of the Philippines which you have data for 
- **Total.Food.Expenditure** – Annual expenditure by the household on food (in Philippine peso) 
- **Household.Head.Sex** – Head of the households sex 
- **Household.Head.Age** – Head of the households age (in years) 
- **Type.of.Household** – Relationship between the group of people living in the house 
- **Total.Number.of.Family.members** – Number of people living in the house 
- **House.Floor.Area** – Floor area of the house (in square meter) 
- **House.Age** – Age of the building (in years) 
- **Number.of.bedrooms** – Number of bedrooms in the house Electricity – Does the house have electricity? (1=Yes, 0=No)


## 🤖Method

We use Generalized linear model (GLM) to tackle the research question: "Which household related variables influence the number of people living in a household". The models we use in this research are Gauss GLM and Poisson GLM.

## 💻Installation
To use this package, you need to have R and Rstdio installed on your system along with the following dependencies:

- MASS
- tidyverse
- moderndive
- gapminder
- sjPlot
- stats
- jtools
- gt
- GGally
- gridExtra


```r
install.package(MASS)
install.package(tidyverse)
install.package(moderndive)
install.package(gapminder)
install.package(sjPlot)
install.package(stats)
install.package(jtools)
install.package(gt)
install.package(GGally)
install.package(gridExtra)
```



## 📝Conclusion
After model selection, we figure out that the variables that contribute to the number of individuals residing in a single household:
- `Total.Household. Income`
- `Total.Food. Expenditure`
- `Household.Head. Sex`
- `Household.Head. Age`
- `House. Age`
- `Electrivity`
- `Type.of. House` in `Single`


