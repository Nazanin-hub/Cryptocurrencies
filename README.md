# Cryptocurrencies

## Project Overview

Help Martha who is a senior manager for the Advisory Services Team at Accountability Accounting to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for their new investment. Since the data is not ideal and there is no known output for that, I used unsupervised 
machine learning models based on the following methods:

  - Preprocessing the Data for PCA
  - Reducing Data Dimensions Using PCA
  - Clustering Cryptocurrencies Using K-means
  - Visualizing Cryptocurrencies Results

## Resources

- Data Source: crypto_data.csv

- Software: Python 3.8.3, Anaconda Navigator 1.9.6, Jupyter Notebook 6.0.3


## Results

### Reducing the dimensions of the X DataFrame to three principal components using Principal Component Analysis (PCA) algorithm


  ![PCA](https://user-images.githubusercontent.com/71282697/107097165-30341200-67c1-11eb-8c7b-3ed6e31074d1.png)
  
  
### Creating an elbow curve to find the best value for K using K-means algorithm


  ![Elbow curve](https://user-images.githubusercontent.com/71282697/107097382-af294a80-67c1-11eb-80e6-3c864bc3835a.png)
  
  
### running the K-means algorithm to predict the K(K=4) clusters for the cryptocurrencies’ data


 ![run the K-means](https://user-images.githubusercontent.com/71282697/107097654-573f1380-67c2-11eb-8303-f086f2251b8c.png)
 
 
 ### Visualizing the distinct groups that correspond to the three principal components
 
 
 
 ![3D scatter plot](https://user-images.githubusercontent.com/71282697/107097811-af761580-67c2-11eb-8e3e-473edad9b731.png)
 
 
 
 ### Creating a table with all the currently tradable cryptocurrencies
 
 
 ![tradable cryptocurrencies](https://user-images.githubusercontent.com/71282697/107097954-f06e2a00-67c2-11eb-8b7d-88a9d8210e81.png)
 
 
 ### Creating a scatter plot with x="TotalCoinsMined", y="TotalCoinSupply", and by="Class"
 
 
![hvplot scatter plot](https://user-images.githubusercontent.com/71282697/107098231-9b7ee380-67c3-11eb-9465-d97d7e2b6054.png)



