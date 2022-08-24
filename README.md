# Stocks-analysis VBA Challenge 2
Overview of Project: Explain the purpose of this analysis
  
The purpose of the analysis was to evaluate 12 different stocks performances in 2017 & 2018 and to refactor existing code to improve computing speed. The stock performance was measured by rate or return, and volume sold during the year. The primary goal being to assist in the selection of high performing stocks and improve computing speed using for loops, conditions, arrays, and variables.


#  Results: Using images and examples of your code, compare the stock performance between 2017 and 2018

Code was refactored to improve computing speed, by decreasing the number of times the arrays where iterated through. The result was a substantial ~ 8x drop in computing time for both data sets 2017 & 2018.  
![2017 time](https://user-images.githubusercontent.com/111164518/186428185-3bf36fe4-16a3-4825-b8d6-d5c0c2a7ffab.PNG)
![2018 time](https://user-images.githubusercontent.com/111164518/186428211-50858007-db02-41d9-a4ea-659f9131b498.PNG)

2017 was a much better year for returns of this set of stocks than 2018. The only two stocks to have positive returns in the two years are ENPH and RUN. The stock with the largest yearly return was DQ with 199.4% return. 

![stockcomp](https://user-images.githubusercontent.com/111164518/186431264-11e493dd-8dda-46e0-9612-f234ad05d2bf.PNG)

# Summary: advantages and disadvantages of refactoring code

In general refactoring code is an advantageous process overall. Through an iterative process it allows more streamlined and efficient code to be developed, improving computing time and results of the code. It does have a few drawbacks including the time resources to go back over already functioning code and the possibility of breaking the program and having to fix / debug it. 
For the refactoring process of this code, it was in some ways advantageous. It has less iterations in the loop resulting in quicker processing time. However, I ran into a bunch of syntax and compiling errors while refactoring the code often forgetting to close a loop or leaving a letter off a variable. 
