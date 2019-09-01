# Classification-of-Breast-Cancer-Cells

This project aims to increase the prediction accuracy of the classification of the cancer cells for the corresponding patients, 
as benign or malignant. In order to detect the sickness of the cells various Machine Learning algorithms are used. 
In order to train and test the program a dataset is used. For obtaining the dataset, cells taken from the patients are observed
by using the digitized images of the cells. Then, the features for data training are created based the different properties of the cell.
In this project, the dataset is taken from Kaggle. https://www.kaggle.com/uciml/breast-cancer-wisconsin-data. In Kaggle,
the data is preprocessed so there are suitable values for every label for each cell. This dataset has 569 cells and each cell has 30 
features. 70% of the dataset is used for training the algorithms in order to get estimations and the 30% of the dataset are used for
testing the accuracy of the program.

<br>

The features of the cells are based on the grayscale images of them. There are 30 features and they are based on the properties of the 
cell; such as size of the cell where radius, perimeter and area are observed or the patterns on the cell where standard deviations 
in gray-scale values, variation is radius lengths and the general symmetry of the cell are measured or the shape of the cell where the 
concave points of the cell and proportions of radius and perimeter to each other are observed. The high number of the used features and 
the variance in the type of the features makes the data classification and detection of the cancer cells a lot easier.

<br>

In this project, various concepts are used for evaluating the cells and increasing the accuracy of cancer detection. These concepts are 
Principal Component Analysis (PCA), Logistic Regression Classification, K-Nearest Neighbors (KNN) Classification, Support Vector Machine (SVM) 
Classification, Decision Tree Classification, ANN and Naïve Bayes Classification. This algorithms are implemented by using scikit learn 
library and Pytorch. Algorithms of these concepts will be explained in detail in the other parts of the code.
