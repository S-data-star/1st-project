# Fraud Detection

### Dashboard Link : [fraud_detection.csv](https://github.com/user-attachments/files/20439460/fraud_detection.csv)

## Problem Statement

Our fraud detection dashboard helps organizations gain insights into customer behavior and identify potential fraud, enabling them to enhance security and build trust. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area.
Our analysis uncovered three key insights:

1. Fraudulent transactions (5% of total) had higher average values.
2. Certain merchants and devices were more vulnerable to fraud.
3. Data visualization helped pinpoint high-risk transaction. 



### Steps followed 

- Step 1 : Transform data into Power BI query, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "transaction column ",amount column ","merchants column", "device type and label column".
- Step 3 : In the report view, under the view tab, theme was selected.
- Step 4 : Since the data contains transaction id and label. Dax measure was used to calculate the following "total transaction","fraud count", not fraud count","fraud rate","fraud average rate","fraud mean","fraud median","fraud min" and "fraud max".
- Step 5 : Card visuals  were added for nine fields named "total transaction","fraud count","not fraud count", "fraud average rate", "fraud mean", "fraud median","fraud min" and "fraud max".
- Step 6 : Clustered column chart was added to compare and constrast fraud vs non fraud transactions,highlighting the key differences.
- Step 7 : A Area chart was created with X-axis "transaction amount(binned into groups)".Y-axis "count of transaction id" to help in illustrating the distribution of transaction amount and identify patterns
- Step 8 : A Bar chart was added to visualize the fraud rate by merchants type, providing insight into which merchant categories were most susceptible to fradulent activity.
- Step 9 : A Bar chart was added to visualized the fraud rate by device type, revealing which device were most vulnerable to fradulent transactions.

screenshot of powerbi dashboard:

![Power BI Dashboard](https://user-images.githubusercontent.com/1234567/abcdefg-yourimage.png)

