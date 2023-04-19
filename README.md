# Facies (Lithology rock type) Classification using Machine Learning
## Project Scope
In this project, I choose to utilize machine learning to analyze the information from the drilled wells, forecast the facies (lithology rock type) in the oil and gas field, and generate forecasts for more wells based on the model. There are difficulties when there are insufficient data from rock samples because facies is a key indicator of where oil and gas are situated. One of the most effective techniques to evaluate Facies lithology rock type is by using additional data and a machine learning technique:

- **Project Overview**: Characterizing facies is one of the most important tasks for geoscientists working on development and exploratory projects. Sedimentary facies are a reflection of the physical, chemical, and biological conditions that a unit experiences during the sedimentation process. In this project, I will analyze the data from 4 wells and the wells log information to create a model that will predict the facies-lithology rock type for further wells.
- **Problem Proposition**: In this research, machine learning algorithms (Neural Networks) are trained to predict facies from well log data using data from continuous logs (NPHI, RHOB, VCL, DT & and discrete log: Facies), in order to construct a model for future facies forecast for another well without facies interpretation.
- **Metrics**: As a classification strategy in this research, we employed performance metrics including recall, accuracy, and F1-Score.

The key of performance Metrics from the True Positive, True Negative, False Positive, and False Negative concepts were used in this study to validate the classification metrics of precision, recall, and F1-Score.

## Installation
There are some neccessary library nees to install such as:
- numPy
- pandas
- matplolib
- Seaborn (version 0.9.0)
- sklearn

## File Descriptions
- There are 2 datasets contain Data_ANN.csv, test_well_4.csv
- Test.csv is the dataset saved while clean test_well_4
- There is 1 notebooks showing all of my data explantory in my project.

## Results<a name="results"></a>

The main findings of the code are available in the post. [here](https://mysterious-shark-0da.notion.site/Rock-Type-Classification-90b8104fd667454186e797fe856ba920).

## Acknowledgements
- For more information about comparation between Accuracy and F1_score, you can follow this link (https://medium.com/analytics-vidhya/accuracy-vs-f1-score-6258237beca2)
- A Neural Network Implementation in Sklearn (https://scikit-learn.org/stable/modules/neural_networks_supervised.html#mlp-tips)
- You can find more information about Robust Scaler in this link (https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.RobustScaler.html)
