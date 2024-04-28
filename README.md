# Breast-Cancer-Prediction

The project aim to predict whether the patient has breast cancer or not i.e malignant tumor or benign tumor

# Project steps
1. **Data collection and Data Analysis**
Data is collected from the sklearn datasets in the form of numpy array.
Explore the datasets information-the data,the target,features name.
2. **convert the array into a Datasets**
Converting the numpy array into a dataframe by concatenating data and target and providing the features name.
3. **Data Visualization**
Visualizing the data by using a seaborn pair plot.
Visualizing the data using heatmap and understanding the correlation between each features and the target.
4. **Data Preprocessing**
Spliting the data into train and test datasets
feature scaling-converting different units and magnitude data in one unit
5. **Model Training**
we have clean data to build the ML model but which machine learning algorithm is best for the data we have to find.The output is a categorical format so we will use supervised classification machine learning algorithms.To build the best model,we have to train and test the dataset with multiple machine learning algorithm then we can find the best ML model.
- Support vector classifier
- Logistic Regression
- Naive Bayes classifier
- Descision Tree classifier
- Random Forest classifier
To find the ML model is overfitted,under fitted or generalize doing cross-validation.
