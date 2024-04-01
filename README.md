RandomForest | SMS Spam Detection Machine Learning | Classification 

![RandomForest](https://github.com/mitch-henderson/RandomForest_SMS_Spam_Detection_/blob/main/2023_08_mitch___h_RandomForest__SMS_Spam_Detection_Machine_Learning.png)

# SMS Spam Detection: Machine Learning Classification
By **Mitchell Henderson**, CSPB 3022  
  
## Project Overview:
Leveraging [machine learning techniques](https://machinelearningmastery.com/types-of-classification-in-machine-learning/), this project classifies a dataset of text messages into two categories: spam or ham.

## Primary Algorithm Toolset 

The code in this repository primarily leverages the following algorithms and tools from the `scikit-learn` library:
 
**K-Nearest Neighbors (KNN)**:
KNN is a non-parametric, lazy learning algorithm that classifies a data point based on how its neighbors are classified. Given a new observation, KNN searches through the training dataset for the 'k' training examples that are closest to the point and returns the output value (class) that has the majority among its 'k' nearest neighbors.
  
**Logistic Regression**:
A statistical method for analyzing datasets where the outcome variable is binary (e.g., spam or not spam). Logistic Regression estimates the probability that a given instance belongs to a particular category, making it especially suited for binary classification problems.

**Decision Tree Classifier**:
A type of flowchart-like structure where each internal node represents a feature(or attribute), each branch represents a decision rule, and each leaf node represents an outcome. The decision tree splits the data into subsets to eventually make a prediction based on the input features.
 
**Random Forest Classifier**:
An ensemble learning method that operates by constructing multiple decision trees during training and outputs the class that is the mode (most frequent classification) of the classes produced by individual trees. It provides improved accuracy and control over over-fitting compared to individual decision trees.

**Support Vector Machines (SVM)**:
A supervised machine learning algorithm which can be employed for both classification or regression challenges. It performs classification by seeking the hyperplane that best divides a dataset into classes. The core idea is to find the maximum marginal distance from the hyperplane to the nearest data point from either set.

**Linear Discriminant Analysis (LDA)**:
A method used in statistics, pattern recognition, and machine learning to find a linear combination of features that characterizes or separates two or more classes of objects or events. LDA is particularly useful when the classes are well-separated, and it maximizes the difference between means of these classes compared to the spread (variance) within each class.

To get started with the toolset, ensure you have scikit-learn installed. You can install it using pip:
```
pip install scikit-learn
```


## Platform:
This project is presented as a Jupyter Notebook. Ensure you have access to Jupyter to view and execute its contents.

## Data Description:
The SMS Spam Collection is a public compilation of SMS messages curated for research on mobile phone spam detection.

## Data Sources:
- **Unicamp**: [SMS Spam Collection Dataset](https://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)
- **Kaggle**: [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)

## Acknowledgements:
- **Tiago A. Almeida**, Department of Computer Science, Federal University of Sao Carlos (UFSCar), Sorocaba, Sao Paulo, Brazil. Contact: [talmeida@ufscar.br](mailto:talmeida@ufscar.br)
  
- **Jose Maria Gomez Hidalgo**, R&D Department, Optenet, Las Rozas, Madrid, Spain. Contact: [jmgomezh@yahoo.es](mailto:jmgomezh@yahoo.es)


CSPB_3022_Henderson_Final_Project
