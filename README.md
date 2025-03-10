# Fake Review Detection - Assignment 2  

## Introduction  

This project aims to detect fake reviews by analyzing ratings and review text to identify anomalies, helping customers make informed purchase decisions. The analysis is based on a subset of the **Amazon Reviews 2023 Dataset**, specifically the **Appliance** category and its metadata.  

Since the dataset lacks labels indicating whether a review is fake or genuine, **unsupervised machine learning techniques** were used to uncover patterns. Key methodologies include:  

- **K-Means Clustering** to group similar reviews based on text and rating behavior.  
- **Latent Dirichlet Allocation (LDA)** to identify hidden topics in reviews.  
- **Sentiment Analysis** to detect anomalies in user sentiments.  

Additionally, I explored whether there is a correlation between **fake reviews and product prices** to understand potential fraudulent behaviors.  

