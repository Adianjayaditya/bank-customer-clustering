# Bank Customer Clustering

This project involves clustering bank customer transactions using K-Means and Principal Component Analysis (PCA). The clustering result is used as a dataset for the classification project to predict whether a bank customer belongs to which cluster.

##  Objective

- Identify distinct customer segments using unsupervised learning.
- Label each customer with their corresponding cluster.
- Build classification models to predict a customer's segment based on their profile.

##  Dataset

The dataset contains information about bank customers, such as:

- Age
- Transaction Amount
- Account Balance
- Transaction Type
- Location
- Customer Occupation

##  Methods Used

1. **Preprocessing**:
   - Handling missing values and duplicate data
   - Feature scaling/normalization
   - Handling outlier
   - Categorical data encoding
   - Binning for visualisation

2. **Clustering**:
   - K-NN used to group customers based on feature similarity
   - Number of clusters determined via Elbow Method and Silhouette Score
   - Cluster labels assigned to each data point

3. **Classification**:
   - Cluster labels used as target for classification
   - Algorithms used:
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors (K-NN)

4. **Evaluation**:
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix

##  Technologies used
- Pandas
- Matplotlib
- Scikit-learn
- NumPy
- Seaborn

## Installation and Setup

### Clone the Repository

```bash
git clone https://github.com/Adianjayaditya/bank-customer-clustering.git
```

### Install Dependencies

You can install the required dependencies using the following command:

```bash
pip install -r requirements.txt
```

Once everything is set up, you can run the code in Jupiter Notebook.
