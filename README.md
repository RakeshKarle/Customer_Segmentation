# Customer_Segmentation

The project focuses on customer segmentation, dividing customers into groups based on their characteristics. It involves data loading, cleaning, visualization, and one-hot encoding for categorical features.  Machine learning models (Decision Tree and Random Forest) are used for segmentation, and K-Means clustering is also explored.Tools & Skills  Demonstrated - Data analysis, Visualization, and Machine Learning (K-means clustering).

# Detailed description of the project:
1. Objective: The project aims to perform customer segmentation, which is the process of dividing customers into distinct groups based on similar characteristics, behavior, or preferences. 

2. Data Loading: The project starts by loading the data from a CSV file named 'train.csv' using the pandas library.

3. Data Exploration: The data is explored using various pandas functions like head(), info(), describe(), and value_counts(). The data contains information about customers, including features such as gender, age, marital status, education, profession, spending score, family size, and segmentation (target variable).

4. Data Cleaning: The next step involves handling missing values in the dataset. Columns with missing data are dropped using dropna() function to ensure a clean dataset.

5. Data Visualization: The project utilizes matplotlib and seaborn libraries for data visualization. Various plots, such as histograms and bar plots, are created to visualize the distribution of age, work experience, family size, and other features.

6. Feature Engineering: The project performs one-hot encoding for categorical features like gender, ever-married, graduated, profession, spending score, and var_1. This step transforms categorical variables into numerical representation to be used in machine learning models.

7. Label Encoding: The project uses label encoding to convert the target variable 'Segmentation' into numeric form for training the machine learning models.

8. Machine Learning: Two machine learning algorithms are used for customer segmentation: Decision Tree and Random Forest classifiers. The data is split into training and testing sets using train_test_split(). The models are trained on the training data and evaluated on the test data using accuracy scores.

9. Clustering: The project also explores the K-Means clustering algorithm to segment customers based on age and family size. The optimal number of clusters is determined by analyzing the inertia graph.

10. Data Visualization (Clustering): After performing K-Means clustering, the clusters are visualized using scatter plots, where each point represents a customer and is colored based on the assigned cluster.
