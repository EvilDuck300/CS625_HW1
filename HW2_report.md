# Homework 2: 
**Name:** Aamr Ibrahim  
**HW Number:** HW2  
**Class:** CS 625 - Data Visualization  
**Due Date:** Feburary, 9 , 2025


## Step 1: Remove "Gross" and Remove blank/missleading values
![Step 1](image-6.png)


## Step 2: Setted the "Rating" , "Votes" column cells to 0 
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


## Step 3: Clean the "Year" column

# To clean the values in the dataset these are the commands:
![alt text](image-14.jpg)
This is the result:
Part 1:
![alt text](image-15.jpg)
Part 2:
![alt text](image-17.jpg)

![alt text](image-16.jpg)


![alt text](image-18.jpg)

I created a column called startYear
![alt text](image-19.jpg)

And it converted to a Numeric Expression for startYear column:
![alt text](image-20.jpg)


I created a column called endYear
![alt text](image-21.jpg)
Here is the exaplanation for the code:
 m =  re.match(r'(\d{4})[-–]?(\d{4})?', value):  This line uses the re.match() function to look for some pattern at the beginning  of the string value. The regular expression  r'(\d{4})[-–]?(\d{4})?' is used to recognize something that looks like a year.   (\d{4}) it matches the exact 4 digits, this is usually the year.  [-–]? It  matches either a hyphen (-) or an en-dash (–) if there is one between  the two groups of digits. The? makes this part of the regex optional.   (\d{4})? It matches a second set of 4 digits, this is also optional.  return  int(m.group(2)) if m and m.group(2) else  int(m.group(1)) if m else None:  This line uses a conditional expression to return the right value depending on  the result of the regex match.  If the match is successful (m), it checks to see  if the second captured group (m.group(2)) is there (that is, if the second  set of digits is present). If it does, it returns that value as an integer.  If  the second group doesn’t exist but the match is successful (m), it returns the first captured group  (m.group(1)) as an integer.  If there is no match (m is  None), the function returns None.

And it converted to a Numeric Expression for endYear column:
![alt text](image-22.jpg)



































