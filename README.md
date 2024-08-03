# cannabis-retail-trends
This project is analyzing trends in Cannabis retail sales from 1/14/2023 to 6/30/2024


## Introduction
### Original Dataset

https://catalog.data.gov/dataset/cannabis-retail-sales-by-week-ending 

### Changes Being performed
### Installation



## Step-by-Step
### Updating Visuals
Inserted the data into a table
Conditional Formatting for error (present with Mode formula, as no mode exists for the column)
Added Retail Sale and Products Sold difference columns *=ABS([@[Adult-Use Products Sold]]-[@[Medical Products Sold]])*

### Tables and Graphs

Created a new Table at the bottom of the Data table for Mean, Median, Mode, Standard Deviation, Variance for each column

| Measure              | Formula              |
|----------------------|----------------------|
| Mean                 | =AVERAGE(B2:B95)    |
| Median               | =MEDIAN(B2:B95)     |
| Mode                 | =MODE.SNGL(B2:B95)  |
| Standard Deviation   | =STDEV.P(B2:B95)    |
| Variance             | =VAR.P(B2:B95)      |


Created a Line Chart for Retail Sales, Products Sold, and Average Product Prices to look at seasonal trends. For forecrasting, a linear trend line was added to show the direction of growth for products.


Created a Pivot Table


## Contact
Email: hansel.sob@gmail.com




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->