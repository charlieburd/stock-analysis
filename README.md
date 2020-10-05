# Module 2 - Stock Analysis

## Overview of Project

#### Analyze 12 stocks, defined by their ticker, by looking at their total trade volume and return for 2017 and 2018. Then create a refactored VBA script that will run the analysis in a less time. 


## Results

#### Stock Analysis:

#### Of the 12 stocks analyzed 2017 saw a much better year for growth, with 11 of the 12 stocks having a positive return. TERP had the worst return of -7.21% and DQ had the best return of 199.45%. In 2018 only 2 of the 12 stocks saw a positive return. DQ has the worst return of -62.60% and RUN has the best return of 83.95%

#### VBA Analysis:

#### I was unable to create an improved VBA script that reduced the time to run the macro. I believe I was not able to figure out how to include the Index portion of the module, I wasn’t familiar with that it was asking, and all google searches resulted in using Index as a function. The module could run without error, but I did not give me the outputs I wanted. Additionally, it took scientifically longer. Going from 0.45 seconds to run to 23.71 second to run for 2018.

#### **Pre-refactoring**

![stacked_launch_outcomes](https://github.com/charlieburd/stock-analysis/blob/master/VBA_2017.png)


![stacked_launch_outcomes](https://github.com/charlieburd/stock-analysis/blob/master/VBA_2018.png)

#### **Refactored**

![stacked_launch_outcomes](https://github.com/charlieburd/stock-analysis/blob/master/VBA_2017_refactored.png)

![stacked_launch_outcomes](https://github.com/charlieburd/stock-analysis/blob/master/VBA_2018_refactored.png)

## Summary

#### Refectoring, if done property, can make your script more organized. The script can take a shorter time to run. I believe it also should allow the code too encompass more data, so it will not need to be changed or customize if the data is changed. For example, if you added another stock ticker you would just have to expand your array. However, it does require more effort to get to that point and allow more room for mistakes.
#### In my instance, refactoring rendered  the original script useless and it took longer to run. The computer would also freeze for able 1minute each time I tried to test the new code. While it should in theory organize the code, the became more complicated and harder to follow. For me, there was no advantage to refactoring because it was done incorrectly.










