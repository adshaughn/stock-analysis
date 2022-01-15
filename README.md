### Description

This repo contains an analysis of selected stocks in 2017 and 2018, comparing rates of return and trading volumes, to allow for more informed investing decisions.

## Overview

The client requested an analysis of stocks in the years 2017 and 2018 to better inform investing decisions. The clients' portfolio originally only consisted of Dairy Queen ("DQ"), for personal reasons. For the sake of diversifying their portfolio, additional companies were brought into the analysis.

Additionally, new code was used to improve its effeciency when running in the macro.

## Results

First of all, let's look at the performance of the stocks in question

![2017_Stocks_Analysis](/resources/2017_results.png)

![2018_Stocks_Analysis](resources/2018_results.png)

In comparing these two years, we can see that 2018 showed declines for the majority of stocks in our portfolio. However, this was not universal, as ENPH and RUN showed gains, while DQ showed losses. While this is far from ideal, it shows that diversifying from just DQ allowed the portfolio to mitigate some of those losses, in comparison to if DQ was the only stock in the portfolio.

Diving deeper into the underlying code of the analysis, we can see significant improvements in run times between the original code for 2018 and the new code.

![2018_Run_Time_Original](resources/2018_run_time_old_code.png)

![2018_Run_Time_New](resources/2018_run_time_new_code.png)

## Summary

While refactoring code can be a tedious endeavor, it is often essential to ensure that programs are not so resource-intensive as to preclude them from running, or slowing down other processes on shared hardware. While this analysis only looked at 12 stocks, with the primary dataset containing approximately 3000 lines, improving the code as it is now allows it to be significantly more scaleable. In this specific case, refactoring the code allowed it to run faster, saving time.


