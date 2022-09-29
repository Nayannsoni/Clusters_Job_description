# Clusters_Job_description
This programme clusters the job descriptions.The dataset consists of Job description data which consists of 3 attributes for 2367 job description. Here we are doing data cleaning , EDA, Data visualization using wordcloud as its a text data and finally apply k-means clustering to cluster the job description.

The dataset contains the following columns(MetaData) :
1) unnamed column(not relevant)
2) description - Job description
3) value -Job location

Text Visulization-Bag of words

![word cloud visulaization](https://user-images.githubusercontent.com/89747951/193011953-1efb08b0-3a76-4f82-a830-79506c6aefeb.png)


1.1-

![1 1](https://user-images.githubusercontent.com/89747951/193013998-3ab3012e-4844-4a5f-978b-42ed22fba614.png)

1.2- 

![1 2](https://user-images.githubusercontent.com/89747951/193014042-d66cd9bc-0014-476b-bbb2-732dcd911200.png)

Final Observation:-
Kmeans for bag of words and TFIDF

* By using Elbow method, we generated optimal 5 clusters for both the bag of words and tfidf techniques.
* FOR TFIDF K means is best for identification than K MEANS for BOW, Because 
when BOW cluster are not evenly distributed as compared to TFIDF as you can 
in plots (reference-1.1,1.2).
* However, K means did best on the cluster centers top terms but however when we caopare reviews ,few places it is not matching.
