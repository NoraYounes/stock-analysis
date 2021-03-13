# Stock Analysis 

##Overview of Project

Our clients, Steve's parents have invested all their money in DAQO New Energy Corp (DQ), a company that manufactures silicone wafers for solar panels. Steve wanted to help his parents diversify their investments through analyzing green energy stocks including DQ's stocks. The first stage of the research focused on developing a code to analyze a dozen green energy stocks for 2017 and 2018. Steve would like to expand his research to include the entire stock market over the last few years, however the code will need to be refactored to run efficiently on larger datasets. 

###Purpose

The purpose of this project is to refactor the code to loop through all the green energy stocks data more efficiently. 

##Results

###Code Refactoring

####Original Code

The original code used a nested for loop to loop through all the tickers and generate the total volume and yearly return as shown in the image below. 
![VBA_Challenge_Original_Code](https://user-images.githubusercontent.com/78664640/111036535-a691e880-83ed-11eb-8cd0-536f9fe8c23e.png)

####Refactored Code

The refactored code replaced the nested for loop with a for loop through all the tickers and generate the total volume and yearly return as shown in the image below.
![VBA_Challenge_Refactored_Code](https://user-images.githubusercontent.com/78664640/111036553-b6113180-83ed-11eb-91f0-f79ec961d6ac.png)

###Script Execution Times

The images below show that the original script ran the code in about 0.50 seconds for both 2017 and 2018, while the refactored script ran the code in about 0.12 seconds for both 2017 and 2018. This clearly demonstrates that the refactored code has a faster execution time than the original code.

![VBA_Challenge_2017_Original](https://user-images.githubusercontent.com/78664640/111036726-af36ee80-83ee-11eb-9739-e3f4ba13e0d1.png)

![VBA_Challenge_2017](https://user-images.githubusercontent.com/78664640/111036766-e2797d80-83ee-11eb-8fd1-5bb3ee23fbbc.png)

![VBA_Challenge_2018](https://user-images.githubusercontent.com/78664640/111036793-1a80c080-83ef-11eb-9a42-6dcd7726d5cf.png)

![VBA_Challenge_2018_Original](https://user-images.githubusercontent.com/78664640/111036776-f624e400-83ee-11eb-96d0-3f184d5e8bc0.png)

###Stock Performance

In 2017, all the stocks except TERP had a positive rate of return with DQ having the highest rate of return at 199.4%. 

![VBA_Challenge_2017_Stock_Performance](https://user-images.githubusercontent.com/78664640/111036854-66336a00-83ef-11eb-8f95-1b388bb79d9f.png)

In 2018, all the stocks except ENPH and RUN had a negative rate of return, with DQ experiencing the highest loss at -62.6%. 

![VBA_Challenge_2018_Stock_Performance](https://user-images.githubusercontent.com/78664640/111036860-6e8ba500-83ef-11eb-91cb-543b627a63b7.png)

##Summary 

###Advantages

Refactoring code can help improve the code design by identifying code smells and decrease the execution time of the code. For the stock analysis, the refactored code increased efficiency of the code by using a for loop instead of a nested for loop which ran the for loop once instead of once for the outer for loop then again for the inner for loop.

###Disadvantages

A few of the disadvantages of refactoring is that it can be time-consuming to optimize code and it could generate more lines of code to manage as it requires breaking code into smaller and more abstract code to enhance its application (Heusser, 2020). For the stock analysis, refactoring the code required additional time to optimize the code, which was possible for this analysis project, but it may not alway be possible for tighter project deadlines.  

##References

Heusser, M. (2020, May 26). Refactor vs. rewrite: Deciding what to do with problem software. Retrieved from https://searchapparchitecture.techtarget.com/tip/Refactor-vs-rewrite-Deciding-what-to-do-with-problem-software. 





