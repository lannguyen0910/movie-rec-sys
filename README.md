# **Movie Recommended System**


## **Explore the data** [![Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1A4kHKq9jrUPrCYXqoOj5iDQVcnRJK9sR?usp=sharing)
<p align="center">
    <h3><b>Number of movies watched by users</b></h3>
    <img src="./assets/movies_count.png" style="width:100%" />
</p>

<p align="center">
    <h3><b>Average ratings by users</b></h3>
    <img src="./assets/average_ratings.png" style="width:100%" />
</p>

## **Content-based Recommendation Method** [![Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Mr5BloC0Ub96vBAKKy-SZg6623tRdT9l?usp=sharing)

**For content-based method, we used 'tag' as the main feature, aim to find the most relevant 'tag' and extract the features of the tag content. There are clean tags with relevancy scoring so that make it easier to get the most relevant tags for the movie.**

<img src="./assets/cb_similar_movies.PNG" style="width:100%" />
<img src="./assets/cb_recommendation.PNG" style="width:100%" />
<img src="./assets/cb_result.PNG" style="width:100%" />


## **Collaborative Filtering Recommendation Method** [![Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HlXkBPCBWoxsRUeMAoUE1iJwaoNGDxoY?usp=sharing)

**For collaborative filtering (CF), we used the rating of the movie given by each user to find the similarity between the two users. We just use similarity-based on to calculate how similar the user interests are. The higher the similarity score, the closer the user profiles are.**

<p align="center">
    <img src="./assets/cf_similar_users.PNG" style="width:100%" />
    <br>
    <img src="./assets/cf_result.PNG" style="width:100%" />
</p>

# **References**
- Inspire by **Kaylode**: https://github.com/kaylode/rec-sys
