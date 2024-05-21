# Market Segmentation 

## Introduction
This project focuses on creating a market segmentation model for the finance sector using a Decision Tree classifier. The goal is to classify customers for loan approval by transforming unsupervised data into supervised data through clustering. By leveraging customer features and details, the model can segment the market and assist in making informed loan approval decisions.

## Objectives
1. **Clean the Data**: Prepare the dataset by removing inconsistencies.
2. **Exploratory Data Analysis**: Visualize and understand the data.
3. **Kernel Density Estimation Plot (KDE)**: Analyze the distribution of variables.
4. **Distribution Plot**: Visualize the distribution and central tendency of data points.
5. **Correlation Matrix**: Identify relationships between variables.
6. **Dimensionality Reduction**: Reduce data dimensions using Principal Component Analysis (PCA).
7. **Hyperparameter Tuning**: Optimize the number of clusters using the Elbow method.
8. **Clustering Model**: Apply K-means clustering to segment customers.
9. **One-Hot Encoding**: Encode clusters into the dataset as target variables.
10. **Training and Testing Data Split**: Divide data into training and testing sets.
11. **Build Decision Tree Model**: Develop a Decision Tree classifier to segment customers.
12. **Market Segmentation web application Creation**: Deploy a web application for real-time customer classification.

## Description

### Data Wrangling
- **Task**: Remove null values and ensure all variables have the correct data types.
- **Outcome**: A clean and consistent dataset ready for analysis.

### Exploratory Data Analysis
- **Task**: Create visualizations to understand data distributions, relationships, and variability.
- **Outcome**: Comprehensive visual insights into customer data and behaviors.

### Kernel Density Estimation Plot
- **Task**: Use KDE to show the distribution of variables with continuous curves, highlighting skewness and distribution points.
- **Outcome**: Visual representation of data distributions, aiding in the identification of multiple distribution points.

<img src=https://github.com/kamaliravi31/Market-Segmentation/blob/main/images/KDE.png>

### Distribution Plot
- **Task**: Display data distribution along with histograms to highlight central tendencies and variability.
- **Outcome**: Clear visualization of data distribution, showing purchase frequency peaks and median central tendency.

 <img src=https://github.com/kamaliravi31/Market-Segmentation/blob/main/images/distribution.png> 

### Correlation Matrix
- **Task**: Visualize the correlation between variables to identify positive, negative, or no relationships.
- **Outcome**: Insight into variable relationships, guiding further analysis and model building.

  <img src=https://github.com/kamaliravi31/Market-Segmentation/blob/main/images/correlation%20matrix.png>

### Dimensionality Reduction
- **Task**: Apply PCA to convert the dataset into a 2-dimensional data frame.
- **Outcome**: Reduced dimensional data that retains essential information for clustering.

### Hyperparameter Tuning
- **Task**: Use the Elbow method to determine the optimal number of clusters.
- **Outcome**: Identification of 4 significant clusters for customer segmentation.

<img src=https://github.com/kamaliravi31/Market-Segmentation/blob/main/images/hyperparameter_tuning.png>


### K-Means Clustering
- **Task**: Segment the dataset into 4 clusters using the K-means clustering algorithm.
- **Outcome**: Defined customer segments that can be used as target variables for classification.

  <img src=https://github.com/kamaliravi31/Market-Segmentation/blob/main/images/k-means.png>

### One-Hot Encoding
- **Task**: Encode the 4 clusters into the dataset as additional binary variables.
- **Outcome**: Transformation of the unsupervised dataset into a supervised dataset ready for classification.

  <img src=https://github.com/kamaliravi31/Market-Segmentation/blob/main/images/count.png>

### Train and Test Split
- **Task**: Split the data into 80% training data and 20% testing data, with independent variables as X and dependent variables as y.
- **Outcome**: Prepared datasets for model training and evaluation.

### Build Decision Tree Model
- **Task**: Develop a Decision Tree classifier to classify customers into the 4 clusters.
- **Outcome**: A trained Decision Tree model that classifies customers, with Cluster 1 being ideal for loan approval and Cluster 4 being high-risk.

### Evaluation Metrics
- **Task**: Evaluate the model using classification reports and accuracy scores.
- **Outcome**: Achieved an accuracy of 94%, indicating strong model performance.

  <img src=https://github.com/kamaliravi31/Market-Segmentation/blob/main/images/metrics.png>



### Deployment of the Web Application
- **Task**: Deploy the classification model as a web application for real-time customer classification.
- **Outcome**: An accessible tool for loan approvers to make informed decisions, with potential use cases in various market segmentation scenarios.

  <img src=https://github.com/kamaliravi31/Market-Segmentation/blob/main/images/web%20app.png>

   <img src=https://github.com/kamaliravi31/Market-Segmentation/blob/main/images/result.png>

## Conclusion
This project successfully developed a market segmentation model using a Decision Tree classifier, achieving an accuracy of 94%. The model's deployment as a web application provides a practical tool for loan approval decisions, demonstrating significant potential for broader market segmentation and customer classification applications in the finance sector and beyond.
