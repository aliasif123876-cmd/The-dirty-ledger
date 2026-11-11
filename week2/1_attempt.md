# 1. Initial Data Diagnosis and Planned Decisions

I am working with the dataset called teaching_prices_messy.csv. This dataset has 97 rows and 6 columns. The columns are date, item, city, price, unit and data_label. My goal in this step is to find any data‑quality problems before I change the original dataset.

I looked at the dataset. Found several problems. First the price column has one missing value. That missing price could change any calculations or analysis. Second some prices include commas, for example 1,250. These commas could cause formatting and type problems. Third there is a high price of 9,999. Fourth the dataset has a duplicate record. Fifth some item names use capital letters, like Oil B and oil b. Finally the price column is stored as text not as numbers, which could stop me from doing math or statistics.

Before I use AI I chose how to fix each problem. I will. Flag the missing price instead of replacing it with zero because zero is a real price. I will check prices that have commas and correct them so that all prices look the same. I will look into the 9,999 price of deleting it right away because an unusual value might still be correct. I will remove the duplicate record so that I do not count the observation twice. I will standardise item names to make them consistent. I will change the price column from text to a type so that I can do calculations and analysis.

My cleaning plan is to keep the dataset intact and do all cleaning on a copy. I will not delete rows just because they look odd. Every change or removal will have evidence. Will be recorded in the cleaning log. I will also compare the dataset with the cleaned dataset to see how many rows, missing values and data types have changed.

Overall the first look at the dataset shows data‑quality problems that could hurt the reliability of any analysis. My approach is to look at each problem one, by one and decide based on evidence not just change the data automatically. This will keep the cleaned dataset accurate, consistent and reliable.
