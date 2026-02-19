# Executive summary
This report focuses on the Glass Identification dataset, which involves classifying glass samples based on
their chemical composition. The objective is to predict the type of glass, such as building windows, vehicle
windows, and containers, using measurements of various chemical elements.
The solutions presented in this report address the Glass Identification as classification problem through a
comprehensive process involving data retrieval and preparation, exploratory data analysis, and data
modeling using Jupyter Notebook.
The findings from this research suggest that with two classification model, KNeighbors and Decision Tree,
combination with Simple Hill Climping Algorithms have similar prediction accuracy which are and . The
findings suggest that the two classification model without selecting proper features will return to low
accuracy. Meanwhile, applying Simple Hill Climping influenced to high accuracy in classifying glass types.

# Introduction
The Glass Identification dataset presents a classification problem that involves predicting the type of glass
based on its chemical composition. This dataset, sourced from the UCI Machine Learning Repository,
contains measurements of various chemical elements in glass samples. These measurements serve as
features to train machine learning models to classify glass into categories such as building windows, vehicle
windows, and containers. The accurate classification of glass types is crucial in science, manufacturing, and
quality control processes. This report aims to explore the Glass Identification dataset, prepare the data for
analysis, and develop models to achieve high classification accuracy using supervised learning techniques.
Methodology
The methodology for this project consists of several key steps, each critical to developing an accurate and
reliable classification model. The process includes data retrieval, data preprocessing, exploratory data
analysis, feature selection, model training, evaluation, and tuning.

# Methodology
The methodology for this project consists of several key steps, each critical to developing an accurate and
reliable classification model. The process includes data retrieval, data preprocessing, exploratory data
analysis, feature selection, model training, evaluation, and tuning.

## 1.Setting the research goal
The Glass Identification dataset focuses on classifying glass based on its chemical component. The objective
is to identify and predict chemical component of the new sample type of glass (such as vehicle windows)
based on measurement as the weight percent in corresponding oxide in the glass.
The research goal is to develop a machine learning model to accurate classify type of glass based on its
chemical composition. The model can be apply to use in future scientific research and industrial.

## 2.Data Retrieval:
The glass identification is a dataset from UCI Machine Learning Repository. This dataset has 214 rows and 10
columns, which contains 10 attributes including Id and 7 of glass sample types. There is no missing value in
this dataset.

### Preparation Step: Access dataset and convert to .csv file
1. 2. Download Glass Identification from UCI Machine Learning.
Open Microsoft Excel and import glass.data file as csv file.
3. 4. Convert glass.data file to .csv by selecting delimiters using tab and comma.
Export to glass.csv file and save the file into JupyterNotebook workspace directory.

## 3.Data Preparation
Remove duplications
One duplication was removed by df.drop_duplicates().
Identify missing value
There is no missing value in Glass Identification dataset as it described in dataset information.
Find and remove Outliers
There are outliers in the Glass Identification dataset. Since this dataset measures chemical components as
weight percent in corresponding oxides, these chemical components are sensitive data. Additionally, most of
the outliers have values of 0.0, which are meaningful in terms of chemical composition. In this report, outliers
will not be removed but will be indicated and represented if they appear in the visualizations.

## 4.Data Exploration
Task 2.1: Explore each column
Display basic descriptive staticstics for all columns by using df.describe()
Task 2.2: Explore the relationship between pairs of attributes
Exploration of the relationship between pairs of attributes
This report choose 10 pairs of attribute by first 4 pairs will focusing on RI (Refractive Index) by selecting RI pair
with large number of weight percent in corresponding oxide, Si and Na, and pair with small number of weight
percent in corresponding oxide, Al and Mg.
The 6 pairs will comparing between large number and small of weight percent in corresponding oxide.

## 5.Data Modelling
The modelling phase consists of four steps:
1. Feature engineering and model selection
2. Training the model
3. Model validation and selection


To see full result, please refer to the report.pdf file which attached on this git repo.
Kind Regards,
Kara U.
