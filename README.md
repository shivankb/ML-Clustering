# Online Retail Customer Segmentation

![c;uster (2)](https://user-images.githubusercontent.com/121177364/221419257-a2513b5d-0810-43e3-9bf2-273e88316637.png)

## Introduction
This project provides a framework for online retail businesses to segment their customer base based on purchase history and demographic information. By dividing customers into different groups, businesses can better understand their target audience and create tailored marketing campaigns that resonate with each group.

## DataFrame Info
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Feature Description

    * InvoiceNo : Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
    * StockCode : Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
    * Description : Product (item) name. Nominal.
    * Quantity : The quantities of each product (item) per transaction. Numeric.
    * InvoiceDate :Invoice Date and time. Numeric, the day and time when each transaction was generated.
    * UnitPrice :Unit price. Numeric, Product price per unit in sterling.
    * CustomerID : Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
    * Country :Country name. Nominal, the name of the country where each customer resides.

## Requirements

    * Python 3.x
    * Pandas
    * Scikit-learn
    * Matplotlib

## Usage

    * Clone or download this repository
    * Download the sample customer data file retail_customers.csv
    * Open the segmentation.py file and update the file path for the customer data on line 10 to match the location of your data file.
    * Run the script by executing python segmentation.py in your terminal

## Customization

    * Feature selection: In addition to the provided features, businesses may want to consider other features such as customer age, gender, or purchase frequency.

    * Segmentation method: The project uses K-means clustering and hierarchical clustering to segment customers. However, businesses may want to consider other segmentation methods such as principal component analysis (PCA), or decision trees.

    * Number of segments: The project uses the elbow method to determine the optimal number of segments. However, businesses may want to consider other methods such as silhouette analysis or domain knowledge to determine the number of segments.

    * Marketing strategy: Once customers are segmented, businesses can create tailored marketing campaigns for each group. The project provides a basic analysis of each segment's characteristics, but businesses may want to further customize their marketing strategy based on their products, services, and goals.

## Conclusion

Customer segmentation is a powerful tool for businesses to better understand their target audience and create tailored marketing campaigns. By segmenting customers based on purchase history and demographic information, businesses can identify patterns, preferences, and behaviors that can inform their marketing strategy. This project provides a basic framework for customer segmentation using K-means clustering and the elbow method. However, businesses can customize the segmentation process based on their specific needs and goals.
