# Homework 4: 
**Name:** Aamr Ibrahim  
**HW Number:** HW4 

**Class:** CS 625 - Data Visualization  
**Due Date:** March 16, 2025

# Selected DataSet: Dataset 2
Table 358. U.S. Water Withdrawals Per Day by End Use 

# Q1:  Show how the amount of water withdrawals attributed to the public supply has changed over time.

## Chart (Time Series Line Chart): 
[Scroll down until you  find "Q1: Visulization" text](https://colab.research.google.com/drive/1AT0JNd9OtWWG55N3dJUEox4YPCo0mFf9?authuser=1#scrollTo=uB-bi98m1IS7)

## Idiom/Mark/Encode

| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| year | key, ordered | Outer horizontal spatial region (x-axis) |
| Public Supply | value, quantitative | Vertical position on a common scale (y-axis)
Visualiztion Choice:
 * This visualization uses a line chart for this because it is very effective in showing trends over time.  The x-axis is the years and the y-axis is public water withdrawals in billion gallons. It is  easy to see increases, decreases and the general trend in water use from a line chart.

  Insights Gained: 
  * Public water supply withdrawals have been increasing with the population and development of  infrastructure. There is a noticeable upward trend from 1950 to 2005.

  Design Decisions & Customizations:
   * To reinforce the idea of water, blue was chosen while data points are used to represent clearly the values  for each year. Gridlines were included to help structure the information.


# Q2: Which of the end uses has contributed the most to the growth over time?

## Chart 2(Categorical Bar Chart):
[Scroll down until you  find "Q2: Visulization" text](<https://colab.research.google.com/drive/1AT0JNd9OtWWG55N3dJUEox4YPCo0mFf9?authuser=1#scrollTo=uB-bi98m1IS7)>)


Idiom: Grouped Bar Chart / Mark: Bar
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| Water Use Category | Categorical | Categorical axis (x-axis) |
| Growth Amount | Value, quantitative | Vertical position (y-axis) |
| Category Type | Categorical | Color hue

Visualiztion Choice:
  * A bar chart was used because it is a simple way to compare the growth of water use across  different categories. Each bar represents a certain end use and the height of the bar represents the growth in  water withdrawals over time.

Insights Gained:
 * Thermo-electric power grew the most, increasing by 14 billion gallons per year over the  time period modeled, while public supply and aquaculture also increased significantly. At the same time,  the irrigation and self-supplied industrial uses decreased which points to changes in water usage allocations.


 Design Decisions & Customizations:
 * Distinct colors were used for each category to enhance visual differentiation, while bars were sorted in descending order to highlight the largest changes. Axis labels were adjusted for improved readability.
