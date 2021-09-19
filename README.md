# Stock-Analysis
## Overview of Project
### Purpose
For this project I was tasked with refactoring code that would go through and analyse stock data. The starting code was created to just be able to run through a limeted number of stock data. The main task was to refactor this code so it could run through large amounts of stock data in a reasonable amount of time. This code will help the client to be able to analyse stock performance through the years.
## Results
### Analysis of Code
For this analysis I had to write code that would go to a certain worksheet based on the year input by the user and run through the data to output the stock performance for that year. To do this I had to create multiple arrays to put the total volume of stock, the starting price and the ending price. Then loop through each row of data adding up the total volume and figuring out which row is the start of that specific ticker and wich is the last. To do this I used for loops with nested If then statements. Doing this outputted the ticker name, the total daily volume and return percentage. I then had to have it output how long it took the program to run. Based on the output of the time it took to run the original code was faster with around .06 seconds for both years whereas the refactored took around .08 seconds for both years.

![alt text](https://github.com/Cdonovan87/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017.png)
![alt text](https://github.com/Cdonovan87/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018.png)


### Analysis of Stock Data
 After running this code for both years I was able to see how each stock faired from 2017 to 2018. Based on the returning data it seems that a majority of the stocks did not fair well in 2018 compared to 2017. In 2017 the majority of the different stocks had decent total daily volumes and had a return percentage in the green. Then in 2018 the reverse happened, The majority of the stock that were in the green ended up with a red return percentage and the two that were red in 2017 ended up in the green. Looking at the data it could be infered that the main reason this happened was that a lot of these stocks had a huge increase of total daily volume, example 35 thousand up to 100 thousand. Also some had a decrease in total volume which could also have lead to this return drop. The only two that were green in 2018 had a large increase in their total daily volume, which could have lead to the positive return percentage. Overall it seems the majority of these stocks did not fair well from 2017 to 2018.

## Summary
### Advantages and Disadvantages of Refactoring
Refactoring code can be a very advantages practice. Refactoring code allows a person to streamline their code so it can execute faster thus allowing for more things to be analysed. It also allows for a person to take code that runs well and make it bea able to handle more data, as was a main goal of this project. Sometimes refactoring may allow for your code to handle more data but it can slow it down compared to the original, as seen with the code for this project. Refactoring the original code in this project allowed for it to be able to take in and run through more data at a decent speed but it was not faster than the original code.
