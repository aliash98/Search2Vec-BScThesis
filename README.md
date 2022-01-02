# Personalized Search2Vec

My Thesis Subject:
Implementation of an effective personalized retrieval method for search engines based on the contents of queries and the background of users‘ behavior

Abstract:
Given a query as an input, retrieving and ranking items is critically important in e-commerce platforms. My project aims to propose and develop an effective personalized embedding-based retrieval method from scratch (with TensorFlow), to enhance users' experience. The main idea comes from Word2Vec, an NLP algorithm that has been broadened to Search2Vec for recommendation usages. Influenced by methods introduced in "Scalable Semantic Matching of Queries to Ads in Sponsored Search Advertising" by Mihajlo Grbovic et al., which is also known as "Search2Vec", this code learns the embedding space of search queries and available products (or product categories). Training a neural network based on the mentioned algorithms produces an embedding space that can effectively place related queries and items near each other. Moreover, user clustering, based on users' history of clicks, has been employed to personalize the results of our ranking method. Two datasets, one obtained from torob.ir (one of the largest Persian online shops), and the other from AOL (publicly available on Kaggle), are being used for experimenting.

Guide for Directories:

Exploratory Data Analysis (EDA) analysis is available on the Search2Vec.ipynb.

The skip-gram is implemented with Tensorflow, Pandas, and NumPy.

Normalized Discounted Cumulative Gain (nDCG) and Mean Reciprocal Rank (MRR) is used to test the model.

