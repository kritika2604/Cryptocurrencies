<img width="373" alt="image" src="https://user-images.githubusercontent.com/94858846/167768627-591b8067-c5d7-4dd7-902f-35ea320d5d48.png">

# Cryptocurrencies ##Unsupervised machine learning


## Purpose:

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, this analysis is done to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data available is not ideal, so it needs to be processed to fit the machine learning models. Since there is no known output, unsupervised learning is used. The cryptocurrencies will be grouped using a clustering algorithmand and data visualizations will be made to share findings with the board.

## Resources:
**Data**: [Crypto data](https://github.com/kritika2604/Cryptocurrencies/tree/main/Resources) </br>
**Softwares**: Jupyter Notebook, Python(Libraries: Scikit-learn, Pandas, Plotly)

## Overview of the Analysis:
Following analyses were performed: 

1: Preprocessing the Data for PCA </br>
2: Reducing Data Dimensions Using PCA </br>
3: Clustering Cryptocurrencies Using K-means </br>
4: Visualizing Cryptocurrencies Results </br>

## Results of analyses: 
    
|**1. Preprocessing the Data for PCA**  |  |
| ------------- | ----------------------- |
| Null values are handled  | <img width="282" alt="image" src="https://user-images.githubusercontent.com/94858846/167759610-a29ad2c1-783a-4f49-bb0c-13329aa59bbc.png">  |
| Only numerical data is used  | <img width="327" alt="image" src="https://user-images.githubusercontent.com/94858846/167759929-7ee5057a-ec7e-40bf-8273-99d421ca96d3.png">  |
| Values are scaled  | <img width="251" alt="image" src="https://user-images.githubusercontent.com/94858846/167760260-0ea469fc-6662-4455-94f9-3ab7e929ad6c.png">  |
| **2. Reducing Data Dimensions Using PCA** |  |
| PCA model initialized  | <img width="232" alt="image" src="https://user-images.githubusercontent.com/94858846/167760830-4661c1ae-ee7e-4a4a-b0e3-5c1ac8616a2f.png">  |
| **3. Clustering Cryptocurrencies using K-means** |  |
| Initialize the K Starting Centroids </br> The elbow curve shows the value of k=4 | <img width="554" alt="image" src="https://user-images.githubusercontent.com/94858846/167764084-85f64f55-962c-445c-a195-f3d18c3881e0.png"> <img width="491" alt="image" src="https://user-images.githubusercontent.com/94858846/167766138-dab4c927-2374-4570-9e9c-53831c882473.png">
|  Initialize, fit and predict | <img width="269" alt="image" src="https://user-images.githubusercontent.com/94858846/167765424-adec488f-9f4e-4637-9cfc-4309d5980398.png">
| **4. Visualizing Cryptocurrencies Results** |  |
| 3d scatter plot | <img width="478" alt="image" src="https://user-images.githubusercontent.com/94858846/167766519-b34367ac-88ee-4af9-a30a-c769bfb4879c.png"> |
| Scatter plot | <img width="430" alt="image" src="https://user-images.githubusercontent.com/94858846/167767011-7db64780-cbfa-4c59-8248-cc6aca5886ae.png">
 
 
 ## Summary: 
 A total of 533 cryptocurrencies were being filtered out. Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.
