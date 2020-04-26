# Customer-Analytics-in-Python
I use various Data Science and machine learning techniques to analyze customer data using STP framework. 

Segmentation.ipynb : I perform correlation estimates, standardise the data, use segmentation, hierarchical clustering, k-means, PCA techniques with a lot of visualizations such as heatmaps, clusters, dendrograms, scatter plots to segment and understand customer data.

Purchase Analytics Descriptive Analysis.ipynb : In this notebook, I have used the segmentation model to divide customers into segments and gain insights about their shopping habits. I have done exploratory data analysis. I have answered questions like how often people go shopping, how much money do they spend, how often do they buy a product relative to their store visits. I created dummy variables for the required features. I have answered questions like which brand is preferred by each segment, what are the reasons for their selection. I have also come up with ideas to improve the sales of a brand. I also analyzed different segments based on revenue. 

Purchase Analytics Predictive Analysis.ipynb : I have caluclated price elasticity of purchase probability and quantity, purchase probability by segments, purchase probability with and without promotion, price elasticity with and without promotion, own and cross price elasticities by segment and analyzed brand choice by customers and customers segments.

Deep Learning.ipynb : The deep learning model predicts if a customer is going to make a purchase again from the audiobook company. I balanced the dataset, preprocessed the data, outlined the model, trained and tested it.

The file segmentation data.csv is the dataset used to build the segmentation model (Customer Analytics Segmentation.ipynb).

The file segmentation data legend.xlsx contains the legend of what each column means in the segmentation data.csv file.

The file purchase data.csv is the dataset used for descriptive analysis of Purchase Analytics (Purchase Analytics Descriptive Analysis.ipynb). It contains purchase data of 500 individuals at a grocery store on a dialy basis for 2 years. For simplification, I focused only on the purchase of chocolate candy bars.

The file purchase data legend.xlsx contains the legend of what each column means in the purchase data.csv file.

The file Audiobooks_data.csv doesn't contain any column headers as we don't want any text in training the model. So, to understand the dataset, column names have been provided in the column_names_audiobooks.txt file. The data represents two years worth of engagement. Another 6 months of data was gathered to see if the user actually made another purchase (to construct the Targets column).

The file New_Audiobooks_Data.csv is used for prediction using our model. The Predicting on New Data section of Deep Learning.ipynb teaches you how to preprocess entirely new data and predict on them.
