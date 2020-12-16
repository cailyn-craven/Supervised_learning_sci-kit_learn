# Supervised_learning_sci-kit_learn

These notes and the code in this repository are based on the DataCamp Supervisd Learning in Sci-kit Learn Course.
https://campus.datacamp.com/courses/supervised-learning-with-scikit-learn

Building and tuning predictive models; evaluating how they perform on unseen data. 

Machine learning: the art and science of 
  * Giving computers the ability to learn to make decisions from data
  * without being explicitly programmed

Examples:
* Learning to predict whether an email is spam or not
* Clustering wikipedia entries into different categories

**Supervised learning**: uses labeled data <br>
**Unsupervised learning**: uses unlabeled data <br>

* Unsupervised learning:
  * Uncovering hidden patterns from unlabeled data
  Example: grouping customers into distinct categories (Clustering)

* Reinforcement learning
  * Software agents interact with an environment
  * Learn how to optimize their behavior
  * Given a system of rewards and punishments
  * Draws inspiration from behavioral psychology
  * Applications: economics, genetics, game playing

* Supervised learning
  * Predictor variables/features and a target variable
  * Aim: predict the target variable, give the predictor variables
	* Classification: target variable consists of categories
	* Regression: target variable is continuous

**Features**=predictor variables=independent variables
**Target variable** = dependent variable = response variable

Automate time-consuming or expensive manual tasks
 Example: Doctor’s diagnosis *Make predictions about the future
	Example: will a customer click on an ad or not?
Need labeled data. Here are some ways to get labeled data: 	
        + Historical data with labels
	+ Experiments to get labeled data
	+ Crowd-sourcing labeled data

Using labeled financial data to predict whether the value of a stock will go up or go down next week: supervised learning classification.
Using labeled housing price data to predict the price of a new house based on various features: supervised learning regression.
Using unlabeled data to cluster the students of an online education company into different categories based on their learning styles.: unsupervised learning clustering.
Using labeled financial data to predict what the value of a stock will be next week: supervised learning regression.

* ***Sci-kit Learn, Sklearn***: a free machine learning library for the Python programming language. It features various classification, clustering, and regression algorithms, including support vector machines. It also integrates well with the SciPy stack with libraries like NumPy and Pandas. https://www.scipy.org/stackspec.html <br>
Python has a number of other machine learning libraris including Tensorflow and Keras. 
