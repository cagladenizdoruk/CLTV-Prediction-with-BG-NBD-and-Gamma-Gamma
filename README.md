# Customer Lifetime Value Prediction with BG-NBD and Gamma-Gamma
![cltv](https://user-images.githubusercontent.com/84645968/217646538-88eafe99-a743-4bab-9d55-5e492859d218.png)
## Business Problem
FLO, an online shoe store, wants to segment its customers and determine marketing strategies according to these segments.
## Dataset 
#### 13  Feature | 19.945  Observation | 2.7MB
| Feature | Definition |
| --- | --- |
| master_id | Unique number for each customer |
| order_channel | Channel of the shopping platform is used (Android, ios, Desktop, Mobile) |
| last_order_channel | The channel where the most recent purchase was made |
| first_order_date | Date of the customer's first purchase |
| last_order_date | Customer's last purchase date |
| last_order_date_online | The date of the last purchase made by the customer on the online platform |
| last_order_date_offline | The date of the last purchase made by the customer on the offline platform |
| order_num_total_ever_online | The total number of purchases made by the customer on the online platform |
| order_num_total_ever_offline | The total number of purchases made by the customer offline platform |
| customer_value_total_ever_offline | The total fee paid by the customer for offline shopping |
| customer_value_total_ever_online | The total fee paid by the customer for their online shopping |
| interested_in_categories_12 | A list of categories the customer has shopped in the last 12 months |
## Requirements
```
lifetimes==0.11.3
pandas==1.3.4
session_info==1.0.0
sklearn==0.24.2
```
## Author
[Çağla Deniz Doruk](https://github.com/cagladenizdoruk)
