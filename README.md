# Udacity-Finding-Donors-Project

## Introduction 

## Code
The code for this project is fully embodied in the **finding_donors.ipynb** Jupyter Notebook file in this Github repository.

### The python version used in this code is:

	Python version
	3.7.6 (default, Jan  8 2020, 20:23:39) [MSC v.1916 64 bit (AMD64)]
	Version info.
	sys.version_info(major=3, minor=7, micro=6, releaselevel='final', serial=0)

>See below for more details on environment etc. 

## Datasets
	The **census.csv** dataset was provided by Udacity and used for this project and is also in this Github.
 
## Acknowledgments and Sources of Code and Data:

	Udacity project documents 
	README-Template - https://gist.github.com/PurpleBooth/109311bb0361f32d87a2
	ChatGPT
	Udacity GPT
	Google
 
 >### References:
	https://github.com/rahulpatraiitkgp/Finding-Donors-For-CharityML/blob/master/finding_donors.ipynb
 	https://github.com/lmego/finding_donors/blob/master/finding_donors.ipynb

## Rubric item: Exploring the Data
### Data Exploration
> Implementation correctly calculates the following:

    Number of records
    Number of individuals with income >$50,000
    Number of individuals with income <=$50,000
    Percentage of individuals with income > $50,000
>>### done according to specification

## Rubric item: Preparing the Data
> ### Data Preprocessing
    Correctly implements one-hot encoding for the feature and income data.

## Rubric item: Evaluating Model Performance
> ### Question 1: Naive Predictor Performance
    Student correctly calculates the benchmark score of the naive predictor for both accuracy and F1 scores.

> ### Question 2: Model Application
    The pros and cons or application for each model is provided with reasonable 
    justification why each model was chosen to be explored.
    Please list all the references you use while listing out your pros and cons.

> ### Creating a Training and Predicting Pipeline
    Student successfully implements a pipeline in code that will train and predict on 
    the supervised learning algorithm given.

> ### Initial Model Evaluation
    Student correctly implements three supervised learning models and produces 
    a performance visualization.

## Rubric item: Improving Results
> ### Question 3: Choosing the Best Model
	Justification is provided for which model appears to be the best to use given computational cost, 
	model performance, and the characteristics of the data.
 
> ### Question 4: Describing the Model in Layman's Terms
	Student is able to clearly and concisely describe how the optimal model works in 
 	layman's terms to someone who is not familiar with machine learning nor has a technical background.
> ### Model Tuning
	The final model chosen is correctly tuned using grid search with at least one parameter using at 
	least three settings. If the model does not need any parameter tuning it is explicitly stated 
	with reasonable justification.
> ### Question 5: Final Model Evaluation
	Student reports the accuracy and F1 score of the optimized, unoptimized, models correctly in the table 
	provided. Student compares the final model results to previous results obtained.
## Rubric item: Feature Importance
> ### Question 6: Feature Relevance Observation
	Student ranks five features which they believe to be the most relevant for predicting an individual's 
	income. Discussion is provided for why these features were chosen.
> ### Question 7: Extracting Feature Importances
	Student correctly implements a supervised learning model that makes use of the feature_importances_ attribute. 
	Additionally, student discusses the differences or similarities between the features they considered relevant 
	and the reported relevant features.
> ### Question 8: Effects of Feature Selection
	Student analyzes the final model's performance when only the top 5 features are used and compares 
	this performance to the optimized model from Question 5.

### Installing
The jupyter notebook file can be operated with the standard Jupyter Notebook software.
As in all projects, it is recommended to set up an environment with the required packages. These include:

	Python
	NumPy
	pandas
	scikit-learn (v0.17)
	Matplotlib
 
 ### NOTE: a requirements.txt file can be found in this Github that contains all the packages used in this project
 
 ## License
This project is licensed under the MIT License  License - see the LICENSE.md file for details

## Built With
	Anaconda
	Eclipse IDE for Developers (used for checking code)
	Jupyter Notebook
## Author
**Theodore van Kessel** 
