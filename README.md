# Customer-Segmentation-by-RFM-Model-Analysis-for-an-E-commerce-Retail-Chain-with-SQL-Google-BigQuery-
This is the Repo of Business case study of Customer Segmentation by RFM Model Analysis for an E-commerce Retail Chain with SQL(Google BigQuery)

## Problem Statement: 
A company in the e-commerce sector wants to segment its customers and determine their marketing strategies according to these segments. For that need to perform a RFM analysis for a chain of retail stores that sells a lot of different items and categories.

## Various Terminology Explanation:
1.	Customer Segmentation: 
Customer segmentation involves grouping of existing and potential customer based on shared characteristics.
Shared characteristics used for segmentation such as: Demographics, Behavioral, Psycho-graphic, Geographic, Firmographic segmentation.

2.	RFM Clustering Model: 

•	It mainly built from understanding the customer purchase behavior.
•	RFM stands for Recency, Frequency, and Monetary Value.
•	RFM helps the company understand the customer’s characteristics based on their historical transactions.
•	To extract information about their buying behavior, we need to analyze the RFM factor.
•	Recency: How recently a customer has made a purchase, either in months, days or weeks depending on your market’s typical purchase cycle?
•	Frequency: How often a customer makes a purchase, typically measured over the twelve months leading up to each customer’s last purchase?
•	Monetary Value: How much money a customer spends on purchase, either in-total or on-average over the same twelve month period?
•	Methodology:
   Calculate RFM score for each customer by grouping the score for R, F & M (1 for lowest & 5 Highest score)
Column profiling of Retail store Data-Set:
●	InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
●	StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
●	Description: Product (item) name. Nominal.
●	Quantity: The quantities of each product (item) per transaction. Numeric.
●	InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
●	UnitPrice: Unit price. Numeric, Product price per unit in sterling.
●	CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
●	Country: Country name. Nominal, the name of the country where each customer resides.

## Column profiling of Retail store Data-Set
 
The RFM Segmentation can be executed using these five steps:
1.	Data processing
2.	Compute for recency, frequency, and monetary values per customer
3.	Determine quantiles for each RFM metric
4.	Assign scores for each RFM metric
5.	Define the RFM segments using the scores in step 4
