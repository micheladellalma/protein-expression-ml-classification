# protein-expression-ml-classification

# :dna: Protein Expression classification in mice with Down Syndrome

## :bar_chart: Dataset
The dataset contains:
- 76 protein expression features
- 8 classes representing different experimental conditions
- Only continous variables
- No missing values
  
1. Preliminary analysis
2. Classification
3. Prediction with different algorithms and evaluation
4.a Prediction of the expression values of the protein
4.b Determination if the test performance of the best model found at 
step (2.) improves if the SOD1_N feature is also used for prediction (and training).

Programming language: Python in jupyter notebook
The datasets used for the analysis are: training and test datasets

## :mag: Exploratory data analysis (EDA)
An initial exploratory data analysis was performed on the training dataset:
- Inspection of feature distributions using boxplots
- Analysis of varaibility across protein expressions
- Verification of dataset quality (no missing values)

This steps helped understand:
- Data dispersion
- Potential outliers
- General structure of the dataset

## Machine learning tasks
### 1. Classification task
Goal: classify each sample into one of 8 classes

### 2. Regression task

### Project structure

### 1. Preliminary analysis: exploratory data analysis on training data
- Inspection of classes and parameters/proteins
- Inspection of protein expression distribution
- Missing data
- Extreme values
- General look to the proteins important for the prediction of each class
- Feature to feature relationships, collinearity
- Check for unbalanced classes
- Protein division in groups of lowly, medium and highly expressed for each class
- Important proteins for each pair of biological meaningful classes
- Clustering, serch for structure in data 

### 2. Classification: find a model that is able to classify mice in the 8 different classes 
- Feature selection
- Comparison of different classification algorithms
- Test the best algorithm on the test set

### 3. Using the training data, train and compare different regression algorithms to predict the expression value of SOD1 protein given the other feature, usage of robust evaluation techniques to compare algorithms

### 4. Usage of the right model previously found to predict expression value of SOD1_N such that the column in test data is filled

### 5. Determination of the test performance of the model found, if SOD1_N feature is also used for prediction and training
