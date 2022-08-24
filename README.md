# **Stock-Analysis Challenge**

## Overview
 
 The purpose of this project is to help Steve find the stock information he needs more effectively. Initially, we helped Steve find reports for a specific stock, but now he wants details for the whole stock market.  We will do this by altering our original work and eliminating or changing inefficient code.
 
## Results
The results with our original code and our new(optimized) code are the same. However, our original code is not optimized for effieciency.

<kbd>![image](https://user-images.githubusercontent.com/110706169/186510038-acad28bd-bf11-4fd0-8e92-243bf26b9a70.png)</kbd>
<kbd>![image](https://user-images.githubusercontent.com/110706169/186509936-de7c2502-95a7-4bc7-81a4-f47ff5edf0c3.png)</kbd>


The images below show the time it took for our **original** code to run using nested *for* loops to iterate through our entire data over and over.


<kbd>![ogc2017](https://user-images.githubusercontent.com/110706169/186511420-9157e006-61c9-4f74-942a-d295cda4c25f.png)</kbd>
<kbd>![ogc2018](https://user-images.githubusercontent.com/110706169/186511830-d94462b0-8464-4825-b926-0508d8956dc4.png)</kbd>

 In our new code our goal was to iterate through an entire *for* loop only **once** to significantly reduce the time required to run the code. To accomplish this we declared three arrays to hold our data for its respective ticker.
 
 <kbd>![image](https://user-images.githubusercontent.com/110706169/186516331-edffde53-5db4-4869-a705-6e429547b7cc.png)</kbd>
 
  Instead of iterating through the entire data for each ticker, we used <kbd>![image](https://user-images.githubusercontent.com/110706169/186521670-f5a04d5b-73db-4568-b042-854b643b626f.png)</kbd> as our parameter for the arrays in our *for* loop to change ticker as soon as it is reached in the data. Thus, reducing the number of iterations and time needed to run the code significantly as shown below.


 
<kbd>![VBA_Challenge_2017](https://user-images.githubusercontent.com/110706169/186509576-7ac006e1-ca14-447c-beb5-ec6e255f5a63.png)</kbd>
<kbd>![VBA_Challenge_2018](https://user-images.githubusercontent.com/110706169/186509586-fbdc1794-13ed-4cd1-959c-7f31b3d255d3.png)</kbd>

## Summary

Refactoring code 
