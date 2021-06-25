# **VBA Stock-Analysis**
## stock-analysis bootcamp Challenge

## Overview of Project

-Our friend Steve was happy with the workbook we made for him that could analyze a set of stock market data and output information such as annual % return and total daily volume based on the stock’s ticker. He wanted us to continue refactor our code so that it will work as well with thousands of stocks rather than just the 12 he gave us. So to do this we need to make it run more efficiently.

## Results

-The biggest part of refactoring this code was to set a dimension for the outputs as variable that would be the smallest file size possible. These outputs were tickerVolume, tickerEndingPrice, and tickerStartingPrice. I was also able to set a dimension for the tickerindex to reference each individual ticker.

-View the code below
(insert Code Pt1 and 2)

## Results- The results of this yielded approximately 3x increase in speed to run the macro. The time to run the macro before refactoring was approximately ¾ of a second 
(Insert 2017 & 2018 Non-Refactored)
-The time to run the macro after refactoring was approximately 1/4 of a second (Insert 2017 & 2018 )

## Summary
# Advantages Vs. Disadvantages of Refactoring
-Advantages of Refactoring a code are that you can take time to clean up the code to make it more efficient as well as give it a cleaner overall look. You can specify dimensions precisely after you have a working code as you will see the bits needed for each variable. In this case it made the code more versatile as it could be used with a much higher volume of data with only slight tweaks to the code itself. Disadvantages would be that it takes a lot of time to refactor a code and may cause other errors to occur which will require tweaking. I spent many hours rearranging this code as new error messages were popping up as I ran it. So in order to refactor you must have the time necessary to do so. Another disadvantage of refactoring could be that you make the code too specific to the data it is analyzing while attempting to make it more efficient. In efforts it may become less scalable to other data sets when trying to make it more efficient. The code may require substantial tweaking depending on the specifics of the new data.

## Original vs Refactored
-In this challenge the original code ran accurately and in a relatively short amount of time. It would have been effective for smaller sets of data and took less time to design. The refactored code however is more efficient and versatile as it ran at approximately 3x speed and could be used with larger data sets.
