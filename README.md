Stock Market Prediction Project




Overview


This project focuses on analyzing stock market data using both supervised and unsupervised learning techniques. 
The dataset is taken from the Kaggle Huge Stock Market Dataset, and it aims to predict stock prices (Close) and cluster different data points based on stock features.

Algorithms Used

Supervised Learning

Linear Regression: Linear Regression was chosen to predict the Close prices of stocks based on features such as volume, open price, and others.

Evaluation: I used metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE) to assess the model’s performance.

Results:

MSE: 0.0336

MAE: 0.1358
These values indicate that the Linear Regression model performs fairly well with small errors in predictions.

Unsupervised Learning

K-Means Clustering: K-Means was employed to group stocks into different clusters based on feature similarity.

I used Principal Component Analysis (PCA) to reduce dimensionality before applying K-Means.

The Elbow Method helped determine the optimal number of clusters (3 in this case).

Final Results

Through this project, it was found that the Linear Regression model provides good accuracy for predicting stock prices, while K-Means clustering helped in effectively segmenting stocks into clusters.
The supervised model demonstrated strong predictive power, making it more suitable for this specific dataset.

The unsupervised K-Means algorithm worked well in clustering but might not capture complex patterns for a time-series-based stock dataset as effectively as supervised methods.
This showcases that the dataset is better suited for predictive tasks (supervised learning) than for clustering (unsupervised learning).

Link to Kaggle Notebook

You can find the full project and code implementation on Kaggle: [Kaggle Notebook Link](https://www.kaggle.com/code/hasan1000/gaih-mlproject)
