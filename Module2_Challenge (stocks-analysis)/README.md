# Green Energy Stock Analysis

## Overview
This project is aimed to analyze how much daily volumes each stock earned in toal and their growth of return in the selected year. Througout the use of VBA, the project will present how refactoring will reduce run time and preserve accuracy of the result.

## Results
Both macros used for loops in order to analyze the total daily volume of each stock and their growth in percentages. The original macro uses nested for loops to perform calculation and insertion of corresponding data. The refactored macro uses array to store values calculated and reads data from stores arrays to fill the cells. In the year of 2017, most stocks are having positive growth return while TERP having a decrease of 7.2%. DQ in this year having increased almost doubled in return. In the year of 2018, most stocks are having negative growth in return while ENPH and RUN boith having positive growth in return.
<br>

#### Macro After Refactorization
![new](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/Macro_New.png)
#### Stock Analysis of 2017 Data
![2017_new](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/VBA_Challenge_2017.png)
#### Stock Analysis of 2018 Data
![2018_new](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/VBA_Challenge_2018.png)

## Summary
The true difference between the two is that nested loops have longer run time than normal loops in algorithm because they have multiple readings and calculations. Storing values into array and read from the array does not require large amount of calculations therefore will signififantly reduce run time of a script. Both method present same results however having huge gap in run time. (Images below shows the difference in run time before and after refactorization of the macro)
#### Macro Before Refactorization
![prev](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/Macro_Prev.png)
#### Result of Macro Before Refactorization
![2017_prev](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/2017_prev.png)
![2018_prev](https://github.com/WilliamBHW/UT-DATA-BOOT-CAMP/blob/main/Module2_Challenge%20(stocks-analysis)/Resources/2018_prev.png)
