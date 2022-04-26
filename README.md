# Customer-Segmentation-Using-K-mean-clustering
Abstract :- 
A lot of customers buy products from the mall and to generate more revenue for the mall, the
authorities need to attract these customers and for this large amount of capital is required. After
the advertisement, the output is only around 30-40%. Hence customer segmentation comes into
the picture.
Customer Segmentation is a popular application of unsupervised learning and by using this
technique we'll only focus on the potential customers (customers whose probability of buying the
product is very high). With this technique, the output will drastically increase to 90-95%.
Our project aims to build clusters of customers based on their Spending Score and Annual
Income. The algorithm used in this project is K-means

I . Introduction :-
To make predictions and find the clusters of potential customers of the mall and thus find
appropriate measures to increase the revenue of the mall is one of the prevailing applications
of unsupervised learning.
For example, a group of customers have high income but their spending score (amount spent in
the mall) is low so from the analysis we can convert such type of customers into potential
customers (whose spending score is high) by using strategies like better advertising, accepting
feedback and improving the quality of products.
To identify such customers, this project analyses and forms clusters based on different criteria
which are discussed in the further sections.

II . Problem Statement:-
Customer Segmentation is a popular application of unsupervised learning. Using clustering,
identify segments of customers to target the potential user base. They divide customers into
groups according to common characteristics like gender, age, interests, and spending habits so
they can market to each group effectively.
Use K-means clustering and also visualize the gender and age distributions. Then analyze their
annual incomes and spending scores.

III . Data:-
The size of the dataset is (200, 5) which is 200 rows and 5 columns. Also the dataset does not
contain any NULL or NaN values.

IV . Algorithms:-
K-means algorithm is used in this project to analyze and form clusters of customers based on
their income and spending score features.

V. Model:-
K-means model is used and is hyper tuned parameters like n_clusters=5 using elbow method to
find the optimal number of clusters also init=’k-means++’ to avoid random initialization traps.


VI . Programming and Environment:-
Programming Language: Python 3.6
Environment (Libraries and Technologies): Numpy, Pandas, Matplotlib, Seaborn, Jupyter
Notebook, Google Colab.
3


VII . Methodology:-

The Data Science Methodology aims to answer basic questions in a prescribed sequence, that
cover the five main aspects of data science projects. These aspects are:
● From Problem to Approach
● From Requirements to Collection
● From Understanding to Preparation
● From Modelling to Evaluation
● From Deployment to Feedback
In this project, the prescribed sequence is:
● Creating an approach to solve the given problem statement
● Exploring the dataset and obtaining useful insight from the same
● Cleaning the dataset by handling nan values, remove duplicate records, etc.
● Data Visualization used to obtain important information from the data
● Data Preprocessing is performed to make the data ready to fit the model this includes
feature scaling, splitting the dataset into features and labels, etc.
● Model Building

VIII . Clustering Analysis:-

a. High Income, High Spending Score (Cluster 5) - Target these customers by sending new
product alerts which would lead to an increase in the revenue collected by the mall as they are
loyal customers.
b. High Income, Low Spending Score (Cluster 2) - Target these customers by asking the
feedback and advertising the product in a better way to convert them into Cluster 5 customers.
c. Average Income, Average Spending Score (Cluster 1) - May or may not target these groups
of customers based on the policy of the mall.
d. Low Income, High Spending Score (Cluster 4) - Can target these set of customers by
providing them with Low-cost EMI's, etc.
e. Low Income, Low Spending Score (Cluster 3) - Don't target these customers since they have
less income and need to save money.
