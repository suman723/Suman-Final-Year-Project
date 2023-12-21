# Note: Gitlab doesn't render plotly and html. So I am using nbviewer to display the notebooks. Please access it through this link to view rendered notebook
# Link for notebook- Marathon_performance_Data_Analysis
https://nbviewer.org/urls/csgitlab.ucd.ie/sumanshil/marathon-notebooks/-/raw/main/Marathon_performance_Data_Analysis.ipynb

# link for notebook- Cluster Analysis of groups and comparision

https://nbviewer.org/urls/csgitlab.ucd.ie/sumanshil/marathon-notebooks/-/raw/main/Cluster_Analysis_of_groups_and_comparision.ipynb

# Marathon Completion Time Prediction Project

This project focuses on predicting the completion time of marathon runners using various features, including cardiac cost, heart rate, pace difference, and time spent in different zones. The objective is to develop a model that accurately predicts the marathon completion time based on these factors.

## Introduction

Marathons are long-distance running events that require careful training and pacing strategies. The completion time of a marathon is influenced by several factors, including an individual's fitness level, cardiovascular health, and pacing strategy during the race. This project aims to leverage machine learning techniques to predict the marathon completion time based on a set of input variables.

## Data Cleaning and Preprocessing

Before building the prediction model, the dataset underwent a thorough cleaning and preprocessing phase. This involved handling missing values, removing outliers, and standardizing the data for consistency. The cleaned dataset was then split into training and testing sets to evaluate the model's performance.

## Exploratory Data Analysis

An exploratory data analysis (EDA) was conducted to gain insights into the relationships between the predictor variables and the marathon completion time. Visualizations, such as scatter plots, histograms, and correlation matrices, were used to identify patterns and correlations in the data. This analysis provided a better understanding of the dataset and helped in feature selection for the prediction model.

## Zone-wise Analysis

Marathon runners typically train in different heart rate zones to improve their endurance and performance. A zone-wise analysis was performed to examine the distribution of cardiac cost, heart rate, pace difference, and time spent in each zone. This analysis helped identify any significant differences or trends among the zones and their impact on the marathon completion time.

## Slow Group Zone-wise Analysis

The slow group of marathon runners was specifically analyzed to understand the relationship between pace difference and heart rate in this group. Scatter plots and regression lines were used to visualize the correlation and identify any potential outliers or anomalies.

## Medium Group Zone-wise Analysis

Similarly, the medium group of marathon runners was analyzed to explore the relationship between pace difference and heart rate in this category. Scatter plots and regression lines were used to assess the correlation and draw conclusions about the pacing strategy and its impact on the completion time.

## Fast Group Zone-wise Analysis

The fast group of marathon runners was also analyzed to examine the relationship between pace difference and heart rate. By visualizing the data and calculating relevant statistics, insights were gained into the pacing strategy and performance of this group.

## Clustering

Clustering analysis was performed to identify distinct groups or clusters within the dataset based on the given features. This analysis helps in understanding the similarities and differences between different runners and their marathon completion times. The K-means algorithm was used for clustering, and the optimal number of clusters was determined using techniques such as the elbow method or silhouette analysis.

## XGBoost Model

To predict the marathon completion time, an XGBoost model was employed. XGBoost is a powerful machine learning algorithm known for its ability to handle complex datasets and deliver accurate predictions. The model was trained using the cleaned dataset and the selected features identified during the exploratory data analysis.

## Hyperparameters

The XGBoost model's hyperparameters were fine-tuned using a clustering objective function to optimize the model's performance. Different combinations of hyperparameters were tested, and the clustering results were evaluated to identify the best parameter settings.

## Prediction Results

The trained XGBoost model was used to predict the marathon completion time for the testing dataset. The predictions were compared with the actual completion time to evaluate the model's accuracy and performance. Various evaluation metrics, such as mean absolute error and root mean squared error, were calculated to assess the model's predictive power.

## Conclusion

This project demonstrates the application of machine learning techniques in predicting the marathon completion time based on various factors. By analyzing and modeling the dataset, valuable insights can be gained to guide athletes in their training and pacing strategies. The developed model can be utilized to provide personalized predictions for individual runners, enabling them to set realistic goals and optimize their performance in future marathons.

## Note: Please access the notebook through this link provided above to view rendered notebook, this will show all the results.
## Alternatively html file of both notebook is provided, can be downloaded to see the results. 