**Project: Movie Recommender System Using Machine Learning!**

**workflow**


![Screenshot (255)](https://github.com/Ricky63rsd2002/Movie-recommender-System/assets/110671339/b4686e3c-967c-4548-960a-77eb8f90763e)

Recommendation systems are becoming increasingly important in today’s extremely busy world. People are always short on time with the myriad tasks they need to accomplish in the limited 24 hours. Therefore, the recommendation systems are important as they help them make the right choices, without having to expend their cognitive resources.

The purpose of a recommendation system is basically to search for content that would be interesting to an individual. Moreover, it involves a number of factors to create personalized lists of useful and interesting content specific to each user/individual. Recommendation systems are Artificial Intelligence-based algorithms that skim through all possible options and create a customized list of items that are interesting and relevant to an individual. These results are based on their profile, search/browsing history, what other people with similar traits/demographics are watching, and how likely they are to watch those movies. This is achieved through predictive modeling and heuristics with the data available.


**Types of Recommendation System:**
**1 ) Content Based:**
Content-based systems, use characteristic information and consider item attributes. Twitter, Youtube. Which music you are listening to, and what singer are you watching? Form embeddings for the features.
User-specific actions or similar items recommendation. It will create a vector of it.

These systems make recommendations using a user's item and profile features. They hypothesize that if a user was interested in an item in the past, they will once again be interested in it in the future

One issue that arises is making obvious recommendations because of excessive specialization (user A is only interested in categories B, C, and D, and the system is not able to recommend items outside those categories, even though they could be interesting to them).

**2 ) Collaborative Based:**
Collaborative filtering systems, are based on user-item interactions. Clusters of users with the same ratings, similar users. Book recommendation, so use cluster mechanism. We take only one parameter, ratings or comments.

In short, collaborative filtering systems are based on the assumption that if a user likes item A and another user likes the same item A as well as another item, item B, the first user could also be interested in the second item.

Issues are :
User-Item nXn matrix, so computationally expensive. Only famous items will be recommended. New items might not be recommended at all.

**3 ) Hybrid Based:**
Hybrid systems, combine both types of information to avoid problems that are generated when working with just one kind. A combination of both and used nowadays.
Uses: word2vec, embedding.

**Demo**

![Screenshot (25![Screenshot (257)](https://github.com/Ricky63rsd2002/Movie-recommender-System/assets/110671339/272af12e-9394-4ca3-bd62-6c128d448040)
6)](https://github.com/Ricky63rsd2002/Movie-recommender-System/assets/110671339/a2621912-8ef7-4a66-a270-ce37abda1188)
![Screenshot (258)](https://github.com/Ricky63rsd2002/Movie-recommender-System/assets/110671339/133e460d-2a5e-4ea2-bdea-d5c3c34438cd)


**How to run?**


**STEPS:**


Clone the repository

**STEP 01-**

Create a conda environment after opening the repository
conda create -n movie python=3.7.10 -y
conda activate movie


**STEP 02- **


Install the requirements
pip install -r requirements.txt
#run this file to generate the models


Movie Recommender System.ipynb

Now run,

streamlit run app.py

Author: Souvik Dutta



