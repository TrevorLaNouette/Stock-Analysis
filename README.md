# **VBA Stock-Analysis**
## stock-analysis bootcamp Challenge

## Overview of Project

-Our friend Steve was happy with the workbook we made for him that could analyze a set of stock market data and output information such as annual % return and total daily volume based on the stock’s ticker. He wanted us to continue refactor our code so that it will work as well with thousands of stocks rather than just the 12 he gave us. So to do this we need to make it run more efficiently.

## Results and Analysis

-The biggest part of refactoring this code was to set a dimension for the outputs as variable that would be the smallest file size possible. These outputs were tickerVolume, tickerEndingPrice, and tickerStartingPrice. I was also able to set a dimension for the tickerindex to reference each individual ticker.

-View the code below

![Code Visual P1](https://user-images.githubusercontent.com/82718969/123469191-56175300-d5b8-11eb-95c9-83ee3a7b67a0.png)

![Code Visual P2](https://user-images.githubusercontent.com/82718969/123469290-72b38b00-d5b8-11eb-895d-0736b89e033a.png)



## **Time to run before refactoring was approximately ¾ of a second.** 

<img width="298" alt="VBA_Challenge_2017 Non-Refactored" src="https://user-images.githubusercontent.com/82718969/123469358-9080f000-d5b8-11eb-97f9-72e4074301dd.png">

<img width="299" alt="VBA_Challenge_2018  Non-Refactored" src="https://user-images.githubusercontent.com/82718969/123469413-a0003900-d5b8-11eb-8890-b13ee37919c3.png">




## Time to run after refactoring was approximately 1/7 of a second. **That's almost 5x faster!!!**

<img width="292" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/82718969/123469486-b7d7bd00-d5b8-11eb-87d8-30d10fcc4d97.png">

<img width="329" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/82718969/123469511-c1612500-d5b8-11eb-8ad3-42f70abbcaa4.png">


# Summary
## Advantages Vs. Disadvantages of Refactoring
-Advantages of Refactoring a code are that you can take time to clean up the code to make it more efficient as well as give it a cleaner overall look. You can specify dimensions precisely after you have a working code as you will see the bits needed for each variable. In this case it made the code more versatile as it could be used with a much higher volume of data with only slight tweaks to the code itself. Disadvantages would be that it takes a lot of time to refactor a code and may cause other errors to occur which will require tweaking. I spent many hours rearranging this code as new error messages were popping up as I ran it. So in order to refactor you must have the time necessary to do so. Another disadvantage of refactoring could be that you make the code too specific to the data it is analyzing while attempting to make it more efficient. In efforts it may become less scalable to other data sets when trying to make it more efficient. The code may require substantial tweaking depending on the specifics of the new data.

## Original vs Refactored
-In this challenge the original code ran accurately and in a relatively short amount of time. It would have been effective for smaller sets of data and took less time to design. The refactored code however is more efficient and versatile as it ran at approximately 5x speed and could be used with larger data sets.
