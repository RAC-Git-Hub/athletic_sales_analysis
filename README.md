# athletic_sales_analysis
## The Challenge
This project involves analyzing sales data over a two year preiod of athletic wear sold in the U.S. The scope of this project includes determining which retailers had the greatest total sales for athletic wear, and determining which retailers sold the most women's athletic footwear. Lastly, this project also determines which day and week had the highest sales for women's athletic footwear.
## Getting Started
Before starting this assignment, make sure the user has a GitHub account, and 
also VS Code or similar IDE that can run Python 3.10 installed on the user's
computer. Then take the following steps:
>*   Create a new repository for this project called "athletic_sales_analysis". 
>    **Do not add this homework assignment to an existing repository.**
>*   Clone the new repository to your computer.
>*   Push these changes to GitHub or GitLab.
>## Challenge Instructions
>The starter code provided includes all the steps necessary to complete this challenge.
>### Combine and Clean the Data
>1. Import the two CSV files, athletic_sales_2020.csv and athletic_sales_2021.
>csv , and read them into
>DataFrames.
>2. Check that the columns in the two DataFrames have similar names and data types.
>3. Combine the two DataFrames by the rows using an inner join, and reset the
>index.
>4. After combining the DataFrames, do the following:
>   - Check if there are any null values.
>   - Check each column’s data type.
>   - Convert the "invoice_date" column to a datetime data type.
>   - Confirm that the data type has been changed.
>### Determine which Region Sold the Most Products
>1. Use either the groupby or pivot_table function to create a multi-index DataFrame with the "region", "state", and
>"city" columns.
>2. Rename the aggregated column to reflect the aggregation of the data in the >column.
>3. Sort the results in ascending order to show the top five regions, including
>the state and city that have the greatest number of products sold. Your final table should look like
>the following image:
>
>![Photo_5_001](https://github.com/RAC-Git-Hub/athletic_sales_analysis/blob/183ca985317c289673a0fc9993cdc191952c79c5/Photo_5_001.png)
>
>### Determine which Region had the Most Sales
>1. Use either the groupby or pivot_table function to create a multi-index DataFrame with the "region",
>"state", and
>"city" columns.
>2. Rename the aggregated column to reflect the aggregation of the data in the column.
>3. Sort the results in ascending order to show the top five regions, including the state and city that
>generated the most sales. Your final table should look like the following image:
>
>![Photo_5_002](https://github.com/RAC-Git-Hub/athletic_sales_analysis/blob/183ca985317c289673a0fc9993cdc191952c79c5/Photo_5_002.png)
>
>### Determine which Retailer had the Most Sales
>1. Use either the groupby or pivot_table function to create a multi-index DataFrame with the
>"retailer", "region", "state", and "city" columns.
>2. Rename the aggregated column to reflect the aggregation of the data in the column.
>3. Sort the results in ascending order to show the top five retailers along with their region, state,
>and city that generated the most sales. Your final table should look like the following image:
>
>![Photo_5_003](https://github.com/RAC-Git-Hub/athletic_sales_analysis/blob/183ca985317c289673a0fc9993cdc191952c79c5/Photo_5_003.png)
>
>### Determine which Retailer Sold the Most Women's Athletic Footwear
>1. Filter the combined DataFrame to create a DataFrame with only women's athletic footwear sales data.
>2. Use either the groupby or pivot_table function to create a multi-index DataFrame with the
>"retailer", "region", "state", and "city" columns.
>3. Rename the aggregated column to reflect the aggregation of the data in the column.
>4. Sort the results in ascending order to show the top five retailers along with their region, state,
>and city that sold the most women's athletic footwear. Your final table should look like the following
>image:
>
>![Photo_5_004](https://github.com/RAC-Git-Hub/athletic_sales_analysis/blob/183ca985317c289673a0fc9993cdc191952c79c5/Photo_5_004.png)
>
>### Determine the Day with the Most Women's Athletic Footwear Sales
>1. Create a pivot table with the "invoice_date" column as the index and the "total_sales" column as the
>values parameter.
>2. Rename the aggregated column to reflect the aggregation of the data in the column.
>3. Apply the resample function to the pivot table, place the data into daily bins, and get the total
>sales for each day.
>4. Sort the resampled DataFrame in ascending order to show the top 10 days that generated the most
>women's athletic footwear sales. Your final table should look like the following image:
>
>![Photo_5_005](https://github.com/RAC-Git-Hub/athletic_sales_analysis/blob/183ca985317c289673a0fc9993cdc191952c79c5/Photo_5_005.png)
>
>### Determine the Week with the Most Women's Athletic Footwear Sales
>1. Apply resample to the pivot table above, place the data into weekly bins, and get the total sales
>for each week.
>2. Sort the resampled DataFrame in ascending order to show the top 10 weeks that generated the most
>women's athletic footwear sales. Your final table should look like the following image:
>
>![Photo_5_006](https://github.com/RAC-Git-Hub/athletic_sales_analysis/blob/183ca985317c289673a0fc9993cdc191952c79c5/Photo_5_006.png)
>
## Sources
The starter codes were obtained in November 2023 from the instructional staff of
the OSU AI Bootcamp and were generated by edX Boot Camps LLC.
## Collaborators
Although this project was done individually, the skillset used to complete this 
assignment is a culmination of knowledge learned in the classroom setting which
includes lecture materials, example programming from instructors, interactive
dialogue in group settings among fellow students, independent internet research,
and some general programming guidance from sources such as CoPilot and ChatGPT. 