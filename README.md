# User_Valuation
This project seeks to value users using the RFMQ model to find the most valuable users for an e-commerce website. 
The data for this project can be found at: https://www.kaggle.com/code/sarahm/customer-segmentation-using-rfm-analysis/input
My RFMQ model uses the recency, Frequency, Monetary and Quantity aaspects to value the customers. These metrics are assigned weights, with greater weights assigned to frequency and monetary aspects with weights of 1 and 0.6 for quantity and recency.



The first bit is loading the csv data into a pandas Dataframe. Using the read_csv file method. afterwhich we then describe the data using the quantity column to better  understand the unique items bought by customers and their volume quantities.
