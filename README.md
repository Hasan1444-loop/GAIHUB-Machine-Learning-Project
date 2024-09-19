
Stock Market Prediction Project




Overview


This project focuses on analyzing stock market data using both supervised and unsupervised learning techniques. 
The dataset is taken from the Kaggle Huge Stock Market Dataset, and it aims to predict stock prices (Close) and cluster different data points based on stock features.

Algorithms Used

Supervised Learning

Linear Regression: Linear Regression was chosen to predict the Close prices of stocks based on features such as volume, open price, and others.
![Ekran görüntüsü 2024-09-19 195657](https://github.com/user-attachments/assets/fe8b9801-fa68-4dae-b18b-5132bb03897b)

Evaluation: I used metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE) to assess the model’s performance.

Results:

MSE: 0.0336

MAE: 0.1358
These values indicate that the Linear Regression model performs fairly well with small errors in predictions.

Unsupervised Learning

K-Means Clustering: K-Means was employed to group stocks into different clusters based on feature similarity.
![Ekran görüntüsü 2024-09-19 200049](https://github.com/user-attachments/assets/33078fff-379f-4250-9531-ab545f33b4a3)


I used Principal Component Analysis (PCA) to reduce dimensionality before applying K-Means.
![Ekran görüntüsü 2024-09-19 200307](https://github.com/user-attachments/assets/9c6600c5-7e38-4232-a858-8fb48a04b10d)


The Elbow Method helped determine the optimal number of clusters (3 in this case).
![Ekran görüntüsü 2024-09-19 200213](https://github.com/user-attachments/assets/29e2f1ae-381c-4f82-b99f-61b87bf1de39)

Final Results

Through this project, it was found that the Linear Regression model provides good accuracy for predicting stock prices, while K-Means clustering helped in effectively segmenting stocks into clusters.
The supervised model demonstrated strong predictive power, making it more suitable for this specific dataset.

The unsupervised K-Means algorithm worked well in clustering but might not capture complex patterns for a time-series-based stock dataset as effectively as supervised methods.
This showcases that the dataset is better suited for predictive tasks (supervised learning) than for clustering (unsupervised learning).

Link to Kaggle Notebook

You can find the full project and code implementation on Kaggle: [Kaggle Notebook Link](https://www.kaggle.com/code/hasan1000/gaih-mlproject)
