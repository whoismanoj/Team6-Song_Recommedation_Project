# Welcome to Song Recommedation Project Repository 

This is the repository containing the work done by Team 6 for SC1015 Miniproject. We have chosen to focus on the recommendation of songs to users based on what they are looking for & based on their existing playlist as well.

![image](https://user-images.githubusercontent.com/129975594/232229889-c995f7c2-9578-46f5-98e6-6efec064454e.png)

# Content Breakdown for Team 6 - Project Folder

1. Proof of Concept Folder - Contains the files titled "Proof of Concept XXK.ipynb" that we have done. The aim was to see what will be difference when we use different sample sizes of 10K, 20K, 30K, 40K and 50K. Using the information from this exercise, we chose the appropriate sample size of 20K for our project as the difference in recommendation is minimized as compared to 10K and the time savings as compared to using 30K as the sample size.

# Dataset

The dataset that we have used for this project is the Spotify Tracks Dataset from Kaggle. The dataset is owned by Maharshi Pandya. 

URL: https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset

The dataset as well as data description is contained in the repository as well.

# Contributors

1. Gim Long - Data Extraction, Cleaning & Visualisation, Exploratory Data Analysis, Machine Learning + Prediction (Song Recommendation based on a song input), Presentation Slides, Presentation Video

2. Nurhidayat - Machine Learning + Prediction (Song recommendation based on a playlist), presentation slides, presentation video

# Problem Statement & Aim of Project

Problem Statement: To create a mockup feature that can recommend new songs for users to add into their current playlist. 

Aim: To help listeners discover new music that they can explore and to suggest songs that align with their musical interests based on their listening history and existing playlists.

# Algorithms / Libraries used for this project

1. Pandas

2. Seaborn

3. Matplotlib.pyplot

4. Plotly.express

5. KMeans & Principal Component Analysis (PCA)

6. Count Vectorisation & Cosine Similarity

# Conclusion

1. Outcome of Project
   - A Program that looks for 5 song recommendations based on user input
   - A Program that can recommend songs based on a given user playlist
   - Computes the song recommendations by converting song data into array object & computing the similarity between songs with cosine similarity

2. Constraints faced in the project:
   - Some songs are not available in the dataset even though it is a song that is available in reality 
   - Due to long computational time, we had to could only use at roughly 1/4 of the total dataset for recommendation 
   - Unable to find a suitably big dataset that contains the user data as well as the audio features of the songs for analysis. 

# Learning Outcomes

1. Collaborating using Google Collab for this project

2. Learning about Count Vectorizer and KMeans from various sources such as scikit-learn and towardsdatascience.com

3. Learning to create and plot a PCA scatter plot as well as understand what it represents from various sources such as scikit-learn and towardsdatascience.com

4. Learning how to use tokens generated by Count Vectorizer to build a song recommendation for 1 song and a list of songs 

5. Understanding how to use Cosine Similarity to calculate the similarities of different songs by using the vectors for the song

6. Learning how to use plotly.express to plot graphs to represent audio features and use it to intepret what the data means

# References

1. https://www.geeksforgeeks.org/apply-function-to-every-row-in-a-pandas-dataframe/

2. https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html

3. https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html

4. https://scikit-learn.org/stable/modules/generated/sklearn.metrics.pairwise.cosine_similarity.html

5. https://towardsdatascience.com/basics-of-countvectorizer-e26677900f9c

6. https://towardsdatascience.com/k-means-clustering-algorithm-applications-evaluation-methods-and-drawbacks-aa03e644b48a

7. https://towardsdatascience.com/k-means-clustering-and-principal-component-analysis-in-10-minutes-2c5b69c36b6b

8. https://towardsdatascience.com/3-ways-to-load-csv-files-into-colab-7c14fcbdcb92#:~:text=Click%20on%20the%20dataset%20in,read_csv%20to%20get%20the%20dataframe

9. https://bioturing.medium.com/how-to-read-pca-biplots-and-scree-plots-186246aae063#:~:text=1.,samples%20based%20on%20their%20similarity.&text=PCA%20does%20not%20discard%20any,constructing%20principal%20components%20(PCs)

10. https://algoritmaonline.com/song2vec-music-recommender/

11. https://blog.bioturing.com/2018/06/18/how-to-read-pca-biplots-and-scree-plots/#:~:text=1.,samples%20based%20on%20their%20similarity.&text=PCA%20does%20not%20discard%20any,constructing%20principal%20components%20(PCs).

12. https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html

13. https://www.geeksforgeeks.org/adding-new-column-to-existing-dataframe-in-pandas/

14.  https://towardsdatascience.com/part-iii-building-a-song-recommendation-system-with-spotify-cf76b52705e7
