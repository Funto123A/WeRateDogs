
## Report: act_report

#### Weratedogs Analysis and Visualization

The first thing i did was to read the stored 'twitter_archive_master.csv' file using pd.read_csv. I looked through the data again using functions('.head()', '.describe()', '.info()'), to be sure it's ready for analysis. 

The next step i did was to identify questions for analysis to guide my visualisations;
#### Questions for analysis
* what is the most popular and the least popular dog stage?

* Is there a correlation between favorite count and retweet count?

* What are the top 5 Dog breed by tweet?.

#### Visualisation

In creating my visualisations, i imported the neccessary libraries needed;

"import matplotlib.pyplot as plt

%matplotlib inline

import seaborn as sns"



Then i created visuals to answer the questions identified.

* Question 1: what is the most popular and the least popular dog stage
![image.png](attachment:image.png)

From the above bar chart, Pupper is the most popular dog stage while Floofer, 'doggo,floofer', 'doggo,puppo' are the least popular.

*  Question 2: Is there a correlation between favorite count and retweet count
![image.png](attachment:image.png)

The scatter plot above shows a strong positive correlation between Favorite count and retweet count. This means that most people retweet their favorite tweets.

* Question 3: What are the top 5 Dog breed by tweet

![image.png](attachment:image.png)

* Golden Retriever is the most common breed, it has the highest tweet of 139. followed by Labrador Retriever, pembroke, Chihuahua and pug with 95, 88, 79 and 54 tweets respectively.

![image.png](attachment:image.png)

A Golden Retriever Breed

#### Insights
* Pupper is the most popular dog stage while Floofer is the least popular.

* There is a positive correlation between Favorite count and retweet count. This means that most people retweet their favorite tweets.

* Golden Retriever is the most common breed, it has the highest tweet of 139. followed by Labrador Retriever, pembroke, Chihuahua and pug with 95, 88, 79 and 54 tweets respectively.
