# Green Energy Stock Analysis

## Overview
### Purpose
This project is aimed to analyze how much daily volumes each stock earned in toal and their growth of return in the selected year. Througout the use of VBA, the project will present how refactoring will reduce run time and preserve accuracy of the result. After refactorization, we need to determine how will this process reduce processing time and more efficient on algorithms.

### Background
Steve loves the workbook you prepared for him. At the click of a button, he can analyze an entire dataset. Now, to do a little more research for his parents, he wants to expand the dataset to include the entire stock market over the last few years. Although your code works well for a dozen stocks, it might not work as well for thousands of stocks. And if it does, it may take a long time to execute.

## Results
Both macros used for loops in order to analyze the total daily volume of each stock and their growth in percentages. The original macro uses nested for loops to perform calculation and insertion of corresponding data. The refactored macro uses array to store values calculated and reads data from stores arrays to fill the cells. In the year of 2017, most stocks are having positive growth return while TERP having a decrease of 7.2%. DQ in this year having increased almost doubled in return. In the year of 2018, most stocks are having negative growth in return while ENPH and RUN boith having positive growth in return.
<br>

#### Macro After Refactorization
![new]()
#### Stock Analysis of 2017 Data
![2017_new](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/VBA_Challenge_2017.png)
#### Stock Analysis of 2018 Data
![2018_new](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/VBA_Challenge_2018.png)

## Summary
In general, refasctoriong of the code will make the program more efficient. Refactoring code will make them become less complex and more easy to read with documentations, code with refactorization are often easy to maintain. The most imperative disadvantag of refactorization is time, redisign of an algorithm is time consuming. Sometims you will lost track of what you are doing during the process.
The true difference between the two is that nested loops have longer run time than normal loops in algorithm because they have multiple readings and calculations. Storing values into array and read from the array does not require large amount of calculations therefore will signififantly reduce run time of a script. Both method present same results however having huge gap in run time.
#### Macro Before Refactorization
![prev]()
#### Result of Macro Before Refactorization
![2017_prev](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/2017_prev.png)
![2018_prev](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/2018_prev.png)
