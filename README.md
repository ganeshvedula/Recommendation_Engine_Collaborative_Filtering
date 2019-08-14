# Recommendation_Engine_Collaborative_Filtering
----
One approach to the design of recommender systems that has wide use is collaborative filtering. Collaborative filtering is based on the assumption that people who agreed in the past will agree in the future, and that they will like similar kinds of items as they liked in the past. The system generates recommendations using only information about rating profiles for different users or items.

### User-User Collaborative filtering
This algorithm first finds the similarity score between users. Based on this similarity score, it then picks out the most similar users and recommends products which these similar users have liked or bought previously.

![image](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2018/05/0o0zVW2O6Rv-LI5Mu1-850x466.png)

### Item-Item Collaborative filtering
In this algorithm, we compute the similarity between each pair of items

![image](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2018/05/1skK2fqWiBF7weHU8SjuCzw.png)
