# **Artificial Intelligence**
### Supervised Machine Learning Project

**2024 - 2nd Semester**  
**Course:** Artificial Intelligence  
**Grade:** 18/20

## Project developed by:
- Gonçalo Matias
- Tiago Simões
- Fernando Afonso

| Project Number | Project Name                                          | Description                                                                                               |
|----------------|-------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| 2              | Predictive Modeling with the Titanic Dataset         | Exploration and application of machine learning models to predict survival on the Titanic. This project involves data preprocessing, feature engineering, model selection, training, and evaluation to derive insights and patterns that contributed to the survival of passengers. |

---

## Project Description - Titanic Survival Rate

The aim of this project is to predict whether a passenger boarding the Titanic survived or not, based on attributes of each person. This means we are dealing with a binary classification problem, where the possible outcomes are *survived* or *not survived*. 

### Data Preprocessing

Before applying machine learning models, we first conduct a thorough analysis of the dataset. This step is crucial as it helps us understand the underlying structure of the data, identify any anomalies or errors, and determine which attributes are relevant for our prediction task.

1. **Data Exploration**: We start by exploring the dataset to understand the distribution of variables, the relationship between different attributes, and identify any initial patterns or anomalies.

2. **Attribute Selection**: Not all attributes in the dataset are useful for predicting the survival rate. Some attributes may be irrelevant or redundant. We identify and remove such attributes to reduce the dimensionality of our data and improve the efficiency of our models.

3. **Data Cleaning**: We handle missing, incorrect, and inconsistent data to ensure the quality and reliability of our models' outputs. This involves strategies such as filling missing values based on certain criteria or removing records with faulty data.

After these preprocessing steps, our data is ready to be used for training machine learning models. This clean and well-structured data helps improve the performance of our models and the reliability of their predictions.

### Algorithms Implementation

We use several Supervised Learning Algorithms to perform the training and evaluation, each with different results, so that we can compare them using different metrics and perform an analysis with valuable conclusions.

*More detailed information can be found inside the notebook*

### How to Run

Open the file `src/titanic_analysis.ipynb` in Jupyter Notebook or any IDE and run all the blocks. This should automatically import the necessary libraries and output results. In case of problems with the import process, there are indications inside the notebook that can help. All the comments and explanations behind the code are inside the notebook.