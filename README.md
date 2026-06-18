# D2C Customer Churn Intelligence - Part 2
## Objective
This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis and develops targeted retention strategies for different customer groups.

## Files Included
* rfm_segmentation.ipynb
* segments.csv
* retention_strategy.md
* manual_review_cases.md
* requirements.txt

## Methodology
### RFM Analysis
The following features were created:
* Recency: Days since the customer's last purchase
* Frequency: Number of purchases before the snapshot date
* Monetary: Total spending before the snapshot date

### Additional Behavioral Signals
To improve segmentation quality, the following features were incorporated:
* ticket_count
* sessions_30d
* campaign_clicks_30d

### Customer Segments
The following segments were created:
* Champions
* Loyal Customers
* Potential Loyalists
* At Risk
* Dormant

## Outputs
* Customer segment assignments
* Segment distribution analysis
* Retention recommendations
* Manual review cases

## How to Run
Install dependencies:
pip install -r requirements.txt
Open and execute:
rfm_segmentation.ipynb
## Author

Vani Tyagi
