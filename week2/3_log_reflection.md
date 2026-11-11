# 3. Cleaning Log and Reflection

## 3.1 Evaluation of AI-Generated Code

After the data‑quality problems were identified in the dataset AI was employed to produce Python code that would aid the cleaning process. The produced code was examined closely to decide if each proposed action fit the dataset. The aim was not to accept every AI suggestion but to assess the code using evidence and the initial diagnosis.

The idea to change the price column into values was accepted because the original column was stored as text, which made calculations hard. The removal of commas from prices was also accepted because commas were acting as thousands separators. The suggestion to standardise item names was accepted because inconsistent capitalization could cause the same item to be seen as categories.

The removal of duplicate records was also accepted because duplicate observations could hurt the accuracy of the analysis.. The suggestion to replace missing prices with zero was rejected because zero would mean a real price instead of an unknown value. Instead the missing price was. Flagged for further investigation.

Likewise the high price of 9,999 was not automatically removed. Even though it looked odd there was not evidence to say it was wrong. Therefore it was flagged for investigation instead of being excluded from the dataset.

## 3.2 Cleaning Log

During the cleaning process several changes were made to improve the quality and consistency of the dataset. The original dataset was kept intact. A separate copy was created for cleaning. The price column was turned into values after fixing its formatting. Inconsistent item names were standardised and exact duplicate records were removed.

The missing price was. Flagged without replacing it with zero. The high price of 9,999 was also flagged instead of deleted. These choices were made to avoid losing useful information or adding wrong values into the dataset.

The cleaning process was recorded with Python. Before‑and‑after comparisons were used to look at changes in the datasets structure missing values, duplicate records and data types.

## 3.3 Before-and-After Verification

The original dataset had 97 rows and 6 columns. After the cleaning process exact duplicate records were removed price formatting was fixed and inconsistent item names were standardised. The price column was turned into a data type.

The missing price was. Flagged, while the unusually high price was also kept for further investigation. These comparisons helped confirm that the cleaning actions tackled the identified problems without dropping observations.

## 3.4 Reflection

One key difference between my decisions and AIs suggestions was how missing and unusual values were handled. AI‑generated solutions can sometimes propose replacing missing values or removing observations without thinking about the datasets context. I decided that these values should be investigated and flagged of automatically changed or deleted.

I believe this approach had support from the available evidence because an unusual value does not automatically mean it is wrong. Likewise replacing a missing price with zero could create results. Working with AI helped me see how Python can make data cleaning faster. Reviewing its suggestions was equally important.

If I had worked alone I might have missed some formatting inconsistencies, data type problems or duplicate records. AI helped spot. Fix these issues more quickly.. This assignment showed that AI‑generated code still needs human judgement, verification and critical thinking.

## 3.5

Overall this assignment showed how important data quality and careful use of AI are in data analysis. Cleaning a dataset is not about removing errors or making the data look neat. It needs understanding the observations spotting problems and making choices that are backed by evidence. The experience showed that AI can be a tool for writing Python code but the final responsibility, for checking and approving cleaning decisions stays with the analyst.
