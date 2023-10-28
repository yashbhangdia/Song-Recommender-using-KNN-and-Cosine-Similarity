# Song-Recommender-cosine-similarity-and-KNN-
[Colab Notebook](https://colab.research.google.com/drive/1vbPJnJIXYUzoC8RfQ8QfvSbg5S6v7nKS#scrollTo=ppWlDR9njTb5)
A song recommender using Spotify data based on two approaches - "Content-based recommendation" that uses TFIDF and cosine similarity and "Collaborative Filtering based recommendation" that uses KNN (K-nearest neighbors) classification model. For content based filtering, we find similarity based on song name, album, artist and release date, whereas for collaborative filtering, we consider numeric features like accousticness, popularity, danceability, etc.

# Steps to Run:
- python3 -m pip install -r requirements.txt
- python3 app.py

- Home Screen:
  ![image](https://github.com/yashbhangdia/Song-Recommender-using-KNN-and-Cosine-Similarity/assets/55742719/25a2fd3c-5e9c-472d-8ca7-be3f4e0889e5)


- Content-based Recommendations <br>
A. Based on Song Name
![image](https://github.com/yashbhangdia/Song-Recommender-using-KNN-and-Cosine-Similarity/assets/55742719/5ca5f1b6-138a-4dbc-8adf-ace74b694e8b)
B. Based on Artist
![image](https://github.com/yashbhangdia/Song-Recommender-using-KNN-and-Cosine-Similarity/assets/55742719/cd25d7e5-2ab9-481f-9d2e-f036bf12dacf)
C. Based on Release Date
![image](https://github.com/yashbhangdia/Song-Recommender-using-KNN-and-Cosine-Similarity/assets/55742719/caac5b64-7985-4f15-9893-d81d360b331f)

- Collaborative Filter based Recommendations
![image](https://github.com/yashbhangdia/Song-Recommender-using-KNN-and-Cosine-Similarity/assets/55742719/8b3bd25f-8cdd-47d5-af59-6dc8ff556f8c)

