# 🎓DATA CLEANING PROJECT IN EXCEL🎓

Small project oriented toward reviewing the process of cleaning and preparing data from a dataset in CSV format. To do so, a "dirty" dataset has been used in order to make the task more difficult and support learning.

The dataset contains retail sales information with the following main variables:
• Transaction ID
• Customer ID
• Category
• Item
• Payment Method
• Location
• Discount Applied
• Quantity
• Price Per Unit
• Total Spent
• Transaction Date

Once the data were redistributed into a pivot table, I found the following errors:
1) Inconsistent texts with spaces, uppercase and lowercase letters.
2) Negative quantities or zeros.
3) Numbers in text format.
4) Missing values.
5) Total calculations that did not match.
6) Dates assigned to incorrect formats.

To solve this, I used the following processes:
1) Removal of extra spaces using the function ESPACIOS () and normalization of letters with the function NOMPROPIO ().
2) Handling of erroneous values in the columns Quantity ≤ 0 and Price ≤ 0. Both transformed into empty spaces.
3) Conversion of numeric text with the function VALOR () and error avoidance with the function SI.ERROR ().
4) Recalculate total revenue (Quantity * Price Per Unit) and manage inconsistent operations.
5) Finally, handling invalid dates and changing their format to short date.

Although it should not be done, I wanted to keep the entire process carried out as an evolution of the project in order to observe the process performed. Therefore, the secondary auxiliary columns that should have been removed at the end have been kept.
In summary, the project aimed to clean and prepare the dataset for subsequent analysis. Finally, all that remains is to thank you for reading this far.

Best regards.

GPx-E
