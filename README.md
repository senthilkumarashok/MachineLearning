# MachineLearning

### Data Types
    https://www.youtube.com/watch?v=5rUVYWfZOb8 (Qualitative Vs Quantitative)
    https://www.youtube.com/watch?v=LuBD49SFpWs (Scales of Measurment Nominal, Ordinal, Interval, Ratio)

### Correlation (Correlation coefficient methods)
    Pearson - standard corrlation coefficient
    Spearman - rank correlation coefficient
    Kendall  - Kendall Tau correlation coefficient

### Timelines of Machine Learning 
    Electronic Brain, Perceptron, Adaline, XOR, MultiLayered Perceptron, SVM, Deep neural networks

### Supervised Learning
    Branch of ML which works with labeled data
    Goal is to predict the labels for the new data
    Common models used were regression (Numerical Data) and classification (Categorical Data)
    Example Model is to predict the price of an house 

    Commonly used algorithms based on the data
    1. Regression
        * Linear
    2. Classifier
        * Logistic, Naive Bayes Algorithms (Gauss, Mulitnomial, Bernoulli)  https://www.youtube.com/watch?v=l3dZ6ZNFjo0

#### Decision Trees
    

#### RandomForest Algorithm
    * Many decision trees form the random forest
    * It's used for both regression and classification problem
    
#### SVM ( Support Vector machines )
    - Goal of the SVM if to find the decision boundary that maximally separates the different classes
    - Hyperplane is the decision boundary that differentiate the two classes in the SVM
    - This hyperplane is crucial because it maximizes the margin between data points of different classes, while minimizing the classification errors.
    Kernel trick
    - By transforming the input space into a higher-dimensional space using kernel parameters such as polynomial or radial basis functions, 
    - SVMs can effectively classify data that isn't linearly separable in its original form.
    - Linear separable using normal regression
    - Handling Non Linear separable using kernel trick 
    
#### Boruta
    - It's a feature selection algorithm

### PCA (principle component analysis)
    - method used for dimensionality reduction 
    - wrapper around random forests

#### ROC ( Receiver operating characteristic curve )
    - gives the classifier accuracy
    - 
    

### UnSupervised Learning
    Branch of ML which works with unlabeled data
    Goal is to predict the state 
    Clustering , Dimensionality reduction
    Example Model is to classify whether incoming email is spam or not
    Stock Market predicting the price of the market based on some conditions & signals, 
    Sales predicting how much user will spend, Medicine predicting the life span of it , Video Recommendation to predict amount of time user spends on a video
    classification models predict a state
    Sometimes unsupervised learning used as preprocess step

    Hierarchial Clustering 
        Divisive
        Agglormate
    Non-Hierarchial Clustering
        Kmeans
        Fuzzy        

#### Dendrogam
    Tree diagram to illustrate clusters produced by hierarchial clustering
    
### K-means clustering
    - elbow technique
    
### Reinforcement Learning
    Branch of ML which works with unlabeled data

### Model creation steps

1. preprocess data
2. use train, test selection to train the model
3. use the appropriate algorithm to predict the label for those input values i mean fit the data to predict the values
4. use the test data to validate
5. use the metrics to check the accuracy score
6. Iterate if accuracy score is less

### Data preparation steps

1. Data Collection
2. Data Cleansing
3. Data Aggregation
4. Labelling
5. Transforming

### Model 

1. Model Technique selection
2. Training
3. Hyper Parameter setting
4. Validattion
5. Development and Testing
6. Algorithm selection
7. Model optimization

### Evaluation

1. Model Metric Evaluation
2. confusion matrix
3. Model perfomance evaluation
4. Quality measurements
5. KPI
6. Final Determination

### Classification Model Evaluation Metrics

1. Accuracy
2. Area under ROC curve
3. Confusion Matrix
4. Classification Report

#### Recommender Systems

Colloborative filtering - These systems try to match users with items based on items’ content (genre, color, etc) and users’ profiles (likes, dislikes, demographic information, etc). For example, Youtube might suggest me cooking videos based on the fact that I’m a chef, and/or that I’ve watched a lot of baking videos in the past, hence utilizing the information it has about a video’s content and my profile.

Content filtering - They rely on the assumption that similar users like similar items. Similarity measures between users and/or items are used to make recommendations.
Hybrid filtering

User based
Item based

**Matrix factorization** is an extensively used technique in collaborative filtering recommendation systems. 

**Matrix factorization** algorithms work by decomposing the user-item interaction matrix into the product of two lower dimensionality rectangular matrices.

Dimensionality reduction

    
