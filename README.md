1. Overview of the Dataset
The Excel file contains multiple sheets related to retail sales and some unrelated student performance data. The primary focus is on retail transactions, customer demographics, and aggregated sales insights.
Key Sheets

Sheet 1 & 3: Pivot tables summarizing sales by Gender vs Product Category and Generation vs Product Category.
Sheet 4: Detailed transaction-level dataset with fields such as:

Transaction ID, Date, Day/Month/Year
Customer demographics: Gender, Generation, Age
Product details: Category, Quantity, Price per Unit
Financial metrics: Total Sales, Commission (2023 & 2024)


Sheet 5: Sample transaction summary with concatenated fields.



2. Data Volume and Structure

Transactions: 1,000 rows of retail data.
Product Categories: Beauty, Clothing, Electronics.
Customer Segmentation: Gender (Male/Female), Generation (Adult, Young Adult, Senior).
Time Frame: Primarily 2023, with some entries for early 2024.


3. Key Insights from Pivot Tables
Gender vs Product Category (Sheet 1)

<img width="489" height="355" alt="image" src="https://github.com/user-attachments/assets/537c841c-af79-416b-a1d6-73bb8cb159bf" />










Sales distribution:

Beauty: Female (0.1641), Male (0.1506)
Clothing: Female (0.1782), Male (0.1629)
Electronics: Female (0.1683), Male (0.1758)
<img width="475" height="194" alt="image" src="https://github.com/user-attachments/assets/04dba21b-e68b-436c-80d1-707eae6d4840" />


Overall: Female contributes ~51%, Male ~49% of total sales.

Generation vs Product Category (Sheet 3)

<img width="621" height="375" alt="image" src="https://github.com/user-attachments/assets/d2fd151f-1634-431a-9ba1-db224fe8fb81" />


Adults dominate sales across all categories:

<img width="563" height="174" alt="image" src="https://github.com/user-attachments/assets/495d14c1-eb12-4435-b110-48f44f3649b3" />



Beauty: 102,115 vs Young Adults: 41,400
Clothing: 109,430 vs Young Adults: 46,150
Electronics: 121,300 vs Young Adults: 35,605

Total Sales: Adults = 332,845; Young Adults = 123,155.


4. Transaction-Level Observations

<img width="683" height="275" alt="image" src="https://github.com/user-attachments/assets/9495bdbe-f146-4650-863c-4fc0887ea93d" />

High-value transactions often involve Electronics (up to $2,000 per transaction).
Beauty products range from $25 to $500 per unit.
Clothing shows wide price variation ($25–$500 per unit).
Commission rates vary by year and product category.


5. Aggregate Metrics

Total Sales (All Products): $456,000.
Category Contribution:

Beauty: $143,515
Clothing: $155,580
Electronics: $156,905


Gender Split:

Female: ~$233,558
Male: ~$222,442


