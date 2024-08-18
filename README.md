# Solution to Assignment Project (STA S380)

This repository has solutions to assignment questions for the course STA S380 : Introduction to Machine Learning at UT Austin. This part of the course is taught by [Prof. David Puelz](https://www.mccombs.utexas.edu/faculty-and-research/faculty-directory/david-puelz/). The questions can be found [here](https://github.com/dpuelz/STA380/tree/master/exercises).

This is a group assignment by :
1. Aman Sharma (as235548)
2. Sarthak Shivnani (ss223347)
3. Sushanth Ravichandran (sr56925)

### Question 1
The hand written write up answers the two probability problems. For part (a), the fraction of people who are truthful clickers and answered yes, has been calculated. For part (b), the probability of someone having the disease given that they tested positive has been calculated using Bayes' Theorm. [Handwritten solution](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/question%201.pdf)

### Question 2
This is an illustrative answer to the three parts of the Wrangling the Billboard Top 100 question. The python notebook should be accompanied by the data file [billboards.csv](https://github.com/dpuelz/STA380/blob/master/data/billboard.csv). [Solution python notebook](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/Question2.ipynb).

### Question 3
This solution delves into the folds of an argument made by an analyst at real estate developer. The question at hand is whether or not to go ahead with a 100 million dollar construction project at East Cesar Chavez in Austin. So it does call for deep dive into some of the assumptions that the analyst makes while providing their recommendation. The supporting data file can be found [here](https://github.com/dpuelz/STA380/blob/master/data/greenbuildings.csv). [Solution python notebook](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/Question3.ipynb).

### Question 4
We analyzed Capital Metro ridership data to uncover patterns in bus usage around the UT-Austin campus. We created visualizations that highlight ridership trends throughout the day, differences between weekdays and weekends, and the impact of temperature on boarding and alighting. Each figure is annotated to convey key insights clearly, illustrating how various factors influence bus usage and providing actionable information on ridership patterns.The supporting data file can be found [here](https://github.com/dpuelz/STA380/blob/master/data/capmetro_UT.csv). [Solution python notebook](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/Question%204.ipynb)

### Question 5
We applied PCA and t-SNE for dimensionality reduction on the 11 chemical properties of vinho verde wine and then performed K-Means clustering on the reduced components.The python notebook should be accompanied by the data file [here](https://github.com/dpuelz/STA380/blob/master/data/wine.csv). [Solution python notebook](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/Question%205.ipynb)

### Question 6
We performed PCA and K-Means clustering to segment Twitter followers into six distinct groups based on their interests. By identifying the top three interests for each cluster, we provided actionable insights into the specific profiles of these market segments, which can inform targeted marketing strategies.The supporting data file can be found [here](https://github.com/dpuelz/STA380/blob/master/data/social_marketing.csv).[Solution python notebook](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/Question%206.ipynb)

### Question 7
This is highly explorative question prompt. We are provided with [writing samples](https://github.com/dpuelz/STA380/tree/master/data/ReutersC50) of 50 journalists (labelled), and using this infomation we can work to uncover supervised or unsupervised learning quests. We choose an unsupervised task. Here are the exact details of the questions we sought answers for along with our findings. <br>
- Question : Explore if an unsupervised algorithm can identify industries a group of journalists reports about
- Approach : We will tokenize and vectorize all documents, for unsupervised algorithms to be able to consume them
- Results : There are three major categories we could uncover from our analysis - journalists who write about banking and finance, ones who report about China / Taiwan and finally the ones who focus on automobiles industry. The ones writing about finance are the highest in number.
- Conclusion : k-means++ using cosine distance measure on top of PCA is a very powerful tool to uncover otherwise hidden relationships
[Solution python notebook](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/Ques_7.ipynb)

### Question 8
We analyzed the groceries.txt data using association rule mining to uncover significant shopping patterns. By setting specific thresholds for support, confidence, and lift, we identified meaningful associations in consumer behavior. Our findings, presented through both numerical metrics and visualizations, reveal intriguing insights into purchasing patterns and item relationships.The supporting data file can be found [here](https://github.com/dpuelz/STA380/blob/master/data/groceries.txt) We exported our results to Gephi to visualize our results better. Here is the [solution python notebook](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/Question%208.ipynb) and here is the [gephi visualization](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/Updated%20Question%208%20Gephi%20.png) of the network of basket items of individuals. Looking at the network, few things that stand out are - items like milk, other vegetables, rolls have the highest degree (or support).


### Question 9
This is an image classification problem statement. The goal is to predict the landscape (10 unique values including Road, Forest etc). The images data can be found [here](https://github.com/dpuelz/STA380/tree/master/data/EuroSAT_RGB). We used CNN model to train on the labelled dataset. Some design calls taken during setting up network architecture include - not using padding, using only one max pooling layer and 3 convolution layers. Here is the [solution python notebook](https://github.com/aman-uta-kgp/ML_Assignment_Prof_Puelz/blob/main/Ques_9.ipynb)
