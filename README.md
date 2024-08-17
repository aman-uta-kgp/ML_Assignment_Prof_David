# Solution to Assignment Project (STA S380)

This repository has solutions to assignment questions for the course STA S380 : Introduction to Machine Learning at UT Austin. This part of the course is taught by [Prof. David Puelz](https://www.mccombs.utexas.edu/faculty-and-research/faculty-directory/david-puelz/). The questions can be found [here](https://github.com/dpuelz/STA380/tree/master/exercises).

This is a group assignment by :
1. Aman Sharma (as235548)
2. Sarthak Shivnani ()
3. Sushanth Ravichanran (sr56925)

### Question 1
The hand written write up answers the two probability problems. For part (a), the fraction of people who are truthful clickers and answered yes, has been calculated. For part (b), the probability of someone having the disease given that they tested positive has been calculated using Bayes' Theorm.

### Question 2
This is an illustrative answer to the three parts of the Wrangling the Billboard Top 100 question. The python notebook should be accompanied by the data file [billboards.csv](https://github.com/dpuelz/STA380/blob/master/data/billboard.csv).

### Question 3
This solution delves into the folds of an argument made by an analyst at real estate developer. The question at hand is whether or not to go ahead with a 100 million dollar construction project at East Cesar Chavez in Austin. So it does call for deep dive into some of the assumptions that the analyst makes while providing their recommendation. The supporting data file can be found [here](https://github.com/dpuelz/STA380/blob/master/data/greenbuildings.csv).

### Question 7
This is highly explorative question prompt. We are provided with [writing samples](https://github.com/dpuelz/STA380/tree/master/data/ReutersC50) of 50 journalists (labelled), and using this infomation we can work to uncover supervised or unsupervised learning quests. We choose an unsupervised task. Here are the exact details of the questions we sought answers for along with our findings. <br>
- Question : Explore if an unsupervised algorithm can identify industries a group of journalists reports about
- Approach : We will tokenize and vectorize all documents, for unsupervised algorithms to be able to consume them
- Results : There are three major categories we could uncover from our analysis - journalists who write about China, ones who write about automobiles and finally the ones who write about finance and banking. The ones writing about finance are the most
- Conclusion : k-means on top of PCA is a very powerful tool to uncover otherwise hidden relationships
