# Online Retail Customer Segmentation

![Wavy_Tech-15_Single-04](https://user-images.githubusercontent.com/123230589/216259370-2d7fbc35-9c73-4e1e-8444-13909cab31f5.jpg)

**Introduction**\
This project provides a framework for online retail businesses to segment their customer base based on purchase history and demographic information. By dividing customers into different groups, businesses can better understand their target audience and create tailored marketing campaigns that resonate with each group.

**DataFrame Info**\
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

**Feature	Description**
1. InvoiceNo	  : Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a    cancellation.
2. StockCode	  : Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
3. Description :	Product (item) name. Nominal.
4. Quantity    :	The quantities of each product (item) per transaction. Numeric.
5. InvoiceDate	:Invoice Date and time. Numeric, the day and time when each transaction was generated.
6. UnitPrice	  :Unit price. Numeric, Product price per unit in sterling.
7. CustomerID	: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
8. Country	    :Country name. Nominal, the name of the country where each customer resides.

**Requirements**
1. Python 3.x
2. Pandas
3. Scikit-learn
4. Matplotlib

**Usage**
1. Clone or download this repository
2. Download the sample customer data file retail_customers.csv
3. Open the segmentation.py file and update the file path for the customer data on line 10 to match the location of your data file.
4. Run the script by executing python segmentation.py in your terminal

**Customization**
1. Feature selection: In addition to the provided features, businesses may want to consider other features such as customer age, gender, or purchase frequency.

2. Segmentation method: The project uses K-means clustering and hierarchical clustering to segment customers. However, businesses may want to consider other segmentation methods such as  principal component analysis (PCA), or decision trees.

3. Number of segments: The project uses the elbow method to determine the optimal number of segments. However, businesses may want to consider other methods such as silhouette analysis or domain knowledge to determine the number of segments.

4. Marketing strategy: Once customers are segmented, businesses can create tailored marketing campaigns for each group. The project provides a basic analysis of each segment's characteristics, but businesses may want to further customize their marketing strategy based on their products, services, and goals.

**Conclusion**

Customer segmentation is a powerful tool for businesses to better understand their target audience and create tailored marketing campaigns. By segmenting customers based on purchase history and demographic information, businesses can identify patterns, preferences, and behaviors that can inform their marketing strategy. This project provides a basic framework for customer segmentation using K-means clustering and the elbow method. However, businesses can customize the segmentation process based on their specific needs and goals.
