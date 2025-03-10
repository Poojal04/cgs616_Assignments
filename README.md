# Search Engine Bias - Assignment 1  

## Introduction  

Many assume that search engines provide **neutral and unbiased results** due to the belief that algorithms operate impartially. However, this is not entirely true, as search engines often reflect **societal prejudices, political influences, or economic interests**. For instance, former U.S. President **Donald Trump** accused Google of bias, claiming it prioritized negative news about him. Google denied this, stating that its algorithms emphasize **relevance over ideology**.  

Bias in search results is especially significant in **controversial topics** or areas with **historical inequalities**. Personalization techniques, such as Google’s **"filter bubble,"** further restrict the diversity of viewpoints users encounter, subtly shaping opinions through **"nudging."**  

Another critical concern is **gender bias** in search results. Many queries related to professions or industries, such as **cricket**, disproportionately highlight **male-centric narratives**, marginalizing women's contributions. Examining these biases helps us understand how digital tools may unintentionally **reinforce societal inequalities**.  

# Fake Review Detection - Assignment 2  

## Introduction  

This project aims to detect fake reviews by analyzing ratings and review text to identify anomalies, helping customers make informed purchase decisions. The analysis is based on a subset of the **Amazon Reviews 2023 Dataset**, specifically the **Appliance** category and its metadata.  

Since the dataset lacks labels indicating whether a review is fake or genuine, **unsupervised machine learning techniques** were used to uncover patterns. Key methodologies include:  

- **K-Means Clustering** to group similar reviews based on text and rating behavior.  
- **Latent Dirichlet Allocation (LDA)** to identify hidden topics in reviews.  
- **Sentiment Analysis** to detect anomalies in user sentiments.  

Additionally, I explored whether there is a correlation between **fake reviews and product prices** to understand potential fraudulent behaviors.  

