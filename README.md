# stock-analysis
Green Stocks Analysis

## Overview:
During module 2, we had dived into core concepts of VBA by exploring the financial data of green energy stocks to suggest Steve’s parents a profitable stock portfolio. Analysis started with studying the performance of a particular ticker (DQ), measuring its daily activity and yearly return. The purpose of this analysis is to refactor the line code used to examine mentioned stocks, demonstrate a better code performance, and ensure it runs faster

### Analysis and Results
To calculate the stocks daily and yearly activity, loops and conditions were required to lookup or loop through all the rows in the data and calculate total ticker volumes by selecting the corresponding starting price and ticker ending price. A tickerIndex was set equal to zero before iterating over all the rows, had the totalvolumes also equal to zero and  then access the output arrays: tickerVolumes, tickerStartingPrices, and tickerEndingPrices to finally run the code faster

 



 


During 2017, the yearly activity of most of the green tickers was positive. Stocks DQ, SEDG, FSLR and ENPH showed an outstanding performance by summarizing their movement with over 100% yearly return however yearly return of TERP ended up with a negative performance by 7.21%
 

Unfortunately, the same tickers, also analyzed during 2017 fall in their performance considerably in 2018. DQ, SEDG, FSLR and ENPH that outstand thanks to their incredible activity, showed a negative outcome by falling more than 70%.Only ENPH kept a positive revenue, nevertheless with a decline of 63% on return. 
 




On the other hand, the code created for running an analysis on 2017 all stocks performance was:





s from 2017 







	And the code for running an analysis on 2018 all stocks performance was:	














### Summary
Refactoring a script, it VBA could be a rewarding practice when the additions to the line code improves its performance and update the outcomes from our study. It reduces the time of crafting a solution for a problem or planning a new code for summing up new on a code however it becomes tricky when while refactoring the variables doesn’t accomplish their purpose. For instance, this analysis cannot demonstrate how efficient the code could be after refactoring due to a “9” error message on the statements to increase volume values for the tickers, as shown below: 




 



Furthermore, when refactoring a script, refactoring is a great tool, less time consuming and easy to use as the variables are already set however when they don’t seem to fit. The solutions become a nightmare! 
![image](https://user-images.githubusercontent.com/86804185/125226316-dcad7f00-e29e-11eb-815d-9b6758878dd1.png)
