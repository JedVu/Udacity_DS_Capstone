# Facies (Lithology rock type) Classification using Machine Learning
## Project Scope
In this project, I made the decision to analyze the data from the drilled wells and use machine learning to forecast the facies (lithology rock type) in the oil and gas field, and to make predictions for other wells based on the model. Facies is a crucial predictor of where oil and gas are located, and there are challenges when there aren't enough data from rock sample. Using additional data and a machine learning technique is one of the best ways to interpret for Facie lithology rock type:

- **Project Overview**: One of the most crucial responsibilities for geoscientists working on development and exploratory projects is the characterization of facies. The physical, chemical, and biological conditions that a unit underwent throughout the sedimentation process are reflected in the sedimentary facies. In this project, I will analyze the data from 4 wells and the well log information to create a model that will predict the facies-lithology rocktype for further wells.
- **Problem Proposition**: In this study, machine learning algorithms (Neural Networks) are trained to predict facies from well log data using data from continuous logs (NPHI, RHOB, VCL, DT & and discrete log: Facies), in order to create a model for future facies forecast for another well without facies interpretation.
- **Metrics**: As a classification strategy in this research, we employed performance metrics including recall, accuracy, and F1-Score.

**The key of performance Metrics** from the True Positive, True Negative, False Positive, and False Negative concepts were used in this study to validate the classification metrics of precision, recall, and F1-Score.

## Installation
There are some neccessary library nees to install such as:
- numPy
- pandas
- matplolib
- Seaborn (version 0.9.0)
- sklearn

## File Descriptions
- The well log data can be referenced from this [Github](https://github.com/seg/tutorials-2016/tree/master/1610_Facies_classification)  
- Datasets: Data_ANN.csv **I took data from my university to do this project to be different with other in network**
- 1 notebooks showing all of my data explantory in my project.

## Results<a name="results"></a>

The main findings of the code are available in the post. [here](https://mysterious-shark-0da.notion.site/Rock-Type-Classification-90b8104fd667454186e797fe856ba920).

## Acknowledgements
- For more information about comparation between Accuracy and F1_score, you can follow this link (https://medium.com/analytics-vidhya/accuracy-vs-f1-score-6258237beca2)
- A Neural Network Implementation in Sklearn (https://scikit-learn.org/stable/modules/neural_networks_supervised.html#mlp-tips)
- You can find more information about Robust Scaler in this link (https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.RobustScaler.html)
