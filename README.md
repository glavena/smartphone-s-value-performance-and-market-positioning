# smartphone-s-value-performance-and-market-positioning
Often times people mistake the price of a phone with its value and often confuse its rating to mean better performance, welp this project helps uncover that. Is it really true?
## 📂DATASET
I downlaoded this data from Kaggle and the link to this data is [Real World Smartphone's Dataset](https://www.kaggle.com/datasets/abhijitdahatonde/real-world-smartphones-dataset) by Abhijit Dahatonde.This data set consists of 47 smartphone brands, 980 smartphone models, their ratings and prices and most importantly their specs i.e RAM,internal storage, Camera, network, etc. As people in the data analytics field we all have the undetsnding that data collected must be cleaned.

## TECHNIQUE USED
1. Data sourcing - from Kaggle
2. Data Cleaning - Power Query
3. Data manipulation and validation - Excel
4. Data analysis- Pivot Tables
5. Data visualization - Excel charts
6. Data reporting/sharing - Power Point

## 🔨 METHODOLOGY
### DATA SOURCING
As I have noted above I did source this data from Abhijit Dahatonde [Real World Smartphone's Dataset](https://www.kaggle.com/datasets/abhijitdahatonde/real-world-smartphones-dataset).It consists of 22 columns and 980 entries.

### DATA CLEANING
The data had was missing : 101 avg_rating,20 Processor Brands, 6 number of cores, 42 processor speed, 11 battery capacities,211 fast charging, 14 os, and 5 primary camera a total of 410 blanks. 

##### DECISION: 
Retained all the rows with the missing data, filled them with the median of the respctive columns. I couldn't compromise the data integrity by cutting off 42% of the dataset.

### DATA MANIPULATION
Added Brand_status column, to check whether a brand is Ultra Premium, Premium, Affordable or Bronze. These was based on their pricing.I also added the rating column, extra high rating, high rating, medium rating and low rating based on the avg_rating. I also added the Value for money column and performance column.

✨ Bronze Brands are anything around $ 9,000 and $ 15,000

🔥Affordable brands cost between $16,000 and $ 25000

🪙Premium brands cost between $ 26,000 and $ 77,000 

💎 Ultra Premium Brand cost are from $77,500 upwards 

Low rating is anything below avg_rating of 7.5
Medium rating is between 7.5 and 7.9 avg_rating
High rating is between 7.9 and 8.4 avg_rating
Extra high rating is above 8.4 avg_rating

Performance rate = Summation of (normalized specs * weight) 

Feature	Weight (%) :- Processor speed	25%, RAM	20%, Battery capacity	20%, Fast charging watts	10%, Internal storage	10%, Number of cores	10%, Refresh rate	5%

Value for money = Performance rate/price

### DATA ANALYSIS
Used Pivot tables to find the top 10 brands with most models, average price of the brands , the brand status spread, the ratings spread, the avaerage rating across brands and the average performance rate.

### DATA VISUALIZATION
Using excel charts iwas able to come up with a 12 chart dashboard tha is pretty detailed on everything tha is importnat . [SMARTPHONE OVERVIEW DASHBOARD](<img width="3395" height="1372" alt="image" src="https://github.com/user-attachments/assets/c28a6abf-2489-4748-ad7d-ef82a3ceb71b" />)

