# Homework 2: 
**Name:** Aamr Ibrahim  
**HW Number:** HW2  
**Class:** CS 625 - Data Visualization  
**Due Date:** Feburary, 9 , 2025


Step 1: Remove "Gross" and Remove blank/missleading values
![Step 1](image-6.png)


Step 2: Setted the "Rating" , "Votes" column cells to 0 
Rating Column:
![alt text](image-5.png)
Then set the blank values with N/A:

For the Votes i have replaced the commas from numbers using this GREL command:
value.replace(",", "")
![alt text](image-7.png)
Now i will be setting the Vote column cells to 0 
![alt text](image-8.png)
Edit Cells -> Common Transforms -> To number
![alt text](image-9.jpg)

Then also for RunTime Columns:
![alt text](image-10.jpg)
![alt text](image-11.jpg)
And it already tranformed as a number

Step 3: Remove any roman numerical number or string-only number

![alt text](image-12.jpg)
![alt text](image-13.jpg)
















