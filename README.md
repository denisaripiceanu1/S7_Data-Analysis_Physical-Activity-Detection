# S7 - Data Analysis - Physical Activity Detection

ENSEEIHT (S7), in pair

Project report and Jupyter Notebook
This project was carried out in pairs during the 7th semester at ENSEEIHT. The main objective was to predict five different human physical activities (such as standing, walking, cycling, vacuuming, and ironing). To achieve this, we analyzed and classified time-series signals extracted from accelerometer sensors placed on a user's chest and ankle.   

We implemented several machine learning models to classify the activities accurately. For supervised learning, we used Gaussian Naive Bayes and K-Nearest Neighbors (KNN), while for unsupervised learning, we applied K-Means and Agglomerative Clustering. A key feature of our approach was the data preprocessing: we used Principal Component Analysis (PCA) to reduce the dimensionality to just 3 components while retaining over 99% of the original data's variance. The technical stack was entirely Python-based, utilizing scikit-learn for the machine learning algorithms, NumPy and Pandas for data manipulation, and Matplotlib and Seaborn to visualize confusion matrices and performance graphs.   


It was fascinating to compare how different algorithms perform on the exact same dataset. Through our analysis, we concluded that the KNN algorithm was the most robust and accurate method for separating the different classes of activities. This project significantly improved my practical skills in data science, predictive modeling, and evaluating algorithm performance.
