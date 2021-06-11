# football_price_prediction


## Seaborn:
Data visualization plays a key role when it comes to quick analysis and simple understanding. It made complex algorithms easy to understand. Seaborn is one of a great library to implement data visualization. Here I have used pair plot, correlation, etc.


## Regression Models:
Models are called either interpretable or flexible. 


![image](https://user-images.githubusercontent.com/64622055/121662710-492c3700-cac3-11eb-90db-20d4397e11dd.png)
 
I have implemented some regression models. They are
1. Linear regression: A basic regression algorithm and have a linear relationship between independent and dependent variables and No heteroscedasticity
2. Lasso and Ridge regression: dependent on lambda
3. SVR: kernel-based and it is a semi interpretable and semi-flexible type modes. Adaptable in nature
4. Random Forest Regressor, Gradient Boosting regression & Decision tree regressor: These algorithms are tree-based and they utilize rules such as series of inequalities. They rely on rules so that it is not necessary to use normalization/scaling and also not affected by any monotonic transformations. Even if you use the scaling it will remain the same.
5. KNN regression: distance-based. It converts the minor nodes to the nearest majority nodes. They measure by euclidian and manhattan distance and they should be scaled for all feature weights equally.


## Feature Scaling:
80% of Data Science jobs are cleaning and organizing the data. And the rest is research-oriented. First things are first. Always clean the junks, missing data, and organize them. More often we see the categorical data and it is useful in the discrete types of algorithms (Classification) but if we want to implement regression (continuous) we have to follow some process like one-hot encoding, replacing, etc. 
“More Data beats clever algorithm But better Data beats More Data” (- Peter Norvig)
 
There are ways to make better data 
1) Data reduction:
2) Feature scaling:
1. Chi-Squared
2. Recursive Feature Elimination
3. Lasso or Ridge (Embedded)
Data reduction and feature Scaling reduces the dimensionality and avoid the cause of overfitting. They also save a lot of time and increase the overall performance and efficiency of an algorithm. Always remember low-quality input procedures low-quality output. In order to make the best algorithms best quality of data is required.
Scaling is critical while performing PCA. It tries to get the features with maximum variance and the higher the variance the higher the magnitude feature and skews. 
But feature selection doesn’t work on tree-based algorithms because they are interpretable and uses rules. These require partitioning, even if you apply Normalization then also the result be the same.        


## Hyperparameter Tuning: 
1.  Hyperparameters are all the parameters that can be arbitrarily set by the user before starting training (eg. number of estimators in Random Forest). Model parameters are instead learned during the model training (eg. weights in Neural Networks, Linear Regression).
Hyperparameters control the parameters and direct them to reach the center which means finding either global maxima or global minima. Each algorithm has a predefine of tunning hyperparameters that are there and can’t summon them together. Some of the hyperparameter optimization techniques are manual search, random search and grid search, and genetic algorithm, etc.
According to a very popular book called “Applied Predictive Modelling” - “Many models have important parameters which cannot be directly estimated from the data. For example, in the K-nearest neighbor classification model … This type of model parameter is referred to as a tuning parameter because there is no analytical formula available to calculate an appropriate value.”
 
 
 
## Genetic Algorithm: 
Genetic Algorithms (GAs) are members of a general class of optimization algorithms, known as Evolutionary Algorithms (EAs), which simulate a fictional environment based on the theory of evolution to deal with various types of a mathematical problem, especially those related to optimization. Also, Genetic Algorithms can be categorized as a subset of Metaheuristics, which are general-purpose tools and algorithms to solve optimization and unsupervised learning problems. One of the advanced algorithms in the field of computer science is a Genetic Algorithm inspired by the Human genetic process of passing genes from one generation to another. It is generally used for optimization purposes and also data reduction. There are five stages are there 
1. Initial Population (1st generation)
2. Fitness Function (finds the fitness value)
3. Selection (best Fitted chromosomes or next generation)
4. Cross over (Create a new set of the chromosome)
5. Mutation (very new or hybrid gene are generated)
Repeat step 2-5 again for each generation
 
 
 
## Validation & learning curves: 
They are very helpful in complex situations. They are perspective and increase the chances of having a clear picture. They are a very good alternative for trial and error methods. By implementing these not only gives better accuracy but also get the intel like which position is most stable in a graph like that. Till now there is no evidence that how to take a hyperparameter without the trial and error method but these are very good alternatives in order to have a clever algorithm. 
 
