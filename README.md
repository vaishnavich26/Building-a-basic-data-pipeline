# Building-a-basic-data-pipeline


![download](https://github.com/user-attachments/assets/f6e64ce9-e811-4555-872c-5c774c00b83d)


This project is focused on creating a basic data pipeline to analyze the supply and demand patterns around public holidays for Walmart, the largest retail store in the United States. By the end of 2022, Walmart’s e-commerce segment reached an impressive $80 billion in sales, accounting for 13% of the company's total sales. Given that public holidays like the Super Bowl, Labor Day, Thanksgiving, and Christmas significantly impact these sales, my project aimed to delve into these variations.

The project involved working with two key data sources: a grocery_sales table stored in a PostgreSQL database and a extra_data.parquet file containing complementary data. The grocery_sales table included features such as store IDs, sales dates, and weekly sales figures. The extra_data file provided additional context, including whether the sales week contained a public holiday, the prevailing temperature, fuel prices, CPI, unemployment rates, promotional markdowns, store department numbers, store size, and store type.

I merged and cleaned the data, transforming it into a clean_data DataFrame with columns like Store_ID, Month, Dept, IsHoliday, Weekly_Sales, CPI, and Unemployment. Following this, I conducted a preliminary analysis of the monthly sales, which I stored in an agg_data DataFrame, summarizing the average weekly sales by month.

Finally, I saved both the clean_data and agg_data as CSV files for further analysis and reporting. Throughout this project, I utilized pandas to efficiently manage and analyze the data.
