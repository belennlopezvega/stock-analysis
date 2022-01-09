# Stock Analysis

## Overview of Stock Analysis

### Purpose

The purpose of this analysis is to help Steve analyze through the stock market dataset for the years 2017 and 2018 as he gathers information to help his parents make an investment decision. In addition, we also want to refactor the original code created to make it more efficient and functional. We'll use the Timer tool to see how fast our new refactored code is able to gather the data requested.

## Results

![This is an image](https://github.com/belennlopezvega/stock-analysis/blob/main/VBA_Challenge_2017.png)

![This is an image](https://github.com/belennlopezvega/stock-analysis/blob/main/VBA_Challenge_2018.png)

#### Stock Comparison
The two images above show the difference in return for 12 energy stocks in the years 2017 and 2018. In 2017 all but one stock show a positive return. In comparison, in 2018 most of the stock show a negative return on investment, with only 2 displaying a positive return. Within both years, it's safe to say ENPH not only shows positive returns in the two years, but also comes in at a fairly high percentage return.

#### Code Comparison and Execution Time

![This is an image](https://github.com/belennlopezvega/stock-analysis/blob/main/Refactored%20Code.png)

The image above shows a snippet of the refactored code used in the analysis. The code shows a minimal risk for mistakes to happen or be missed if the data were to switch as everything is streamlined and variables and indexes are created to eliminate the use of magic numbers. This new code proved to be more efficient compared to the original code as the below picture shows. 

![This is an image](https://github.com/belennlopezvega/stock-analysis/blob/main/Original%20Code%20Timer%202017%20and%202018.png)

These two timer screenshots above were taken using the original code before it was refactored and made more efficient. Although both ran fast in retrospect, there is still a clear distinction in which code ran faster.


## Summary

When it comes to refactoring code, the advantages profoundly outweight the disadvantages. Although it may take longer to assign variables and indexes, it would save time in case of changes which are likely to happen. Even if no further changes are made, that code can then be used and recycled to solve a different question, or run a different analysis. Overall, it leaves very little room for mistakes and magic numbers, and can be beneficial for future use. 






