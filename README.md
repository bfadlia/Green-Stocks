# Stockmarket Analysis

## Overview of Project

### Purpose
This project helps our friend Steve analyze Green stocks for his parents. After giving him a VBA file that can successfully analyze a dozen stocks, we want to refactor the code to ensure it performs efficiently and fast with thousands of stocks and measure the performance of the new code. 


## Results

The original code is in module 1 and the refasctored is in module 2 in the VBA script

The results of the refactored project were as follows:
- For 2017:
  - ![IMAGE_DESCRIPTION](/resources/VBA_Challenge_2017.png)
- For 2018
  - ![IMAGE_DESCRIPTION](/resources/VBA_Challenge_2018.png)
- The refactored code runs more than five times faster than the original code
- Most stocks analyzed did well in 2017 and most did poorly in 2018
## Summary
Analyzing the effect of using the refactored code:
- In general, using refactored code is very common in software development. The problem you are trying to solve must have been considered and tackled by many before you and if others work is available and well documented saves you a lot of time to start with their libraries and genric code and tailor it to your specific problem compared to writing everything you need from scratch. The only disadvantage is it takes some work and knowledge to know where to find trusted source of code to start with or misunderstanding deifferences between what they solved and what you are trying to solve.
- In the particular case of this original and refactored scripts, the original script had two nested loops repeating the looping through the entire records by the number of stocks thre are dedicating. The refactored script loops through the entire records only once so it's no surprise that the program ran more than 5 times faster with the refactored code. We can now be confident that this code will scale well when we have many more stocks.

