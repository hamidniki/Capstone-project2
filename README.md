# Capstone project2: Building a recommender engine using artist rating data from Last.fm

This project aims to build a recommender system using user-artist rating data.

### Dataset:

Number of unique users: **1,892**  
Number of unique artists: **17,631**  
Number of ratings (i.e. total number of rows): **92,834**

Source: http://files.grouplens.org/datasets/hetrec2011/hetrec2011-lastfm-readme.txt

After splitting the data into 80% train and 20% test sets, 3 versions of the engine were implememnted. RMSE was used to evaluate the performance of each version:

- **Baseline:** Predicted by taking the average of other users: **RMSE = 2.95**
- **Cosine similarity:** Used cosine method to assess similarity between two users' rating profiles: **RMSE = 2.95**
- **Pearson similarity:** Used pearson correlation coefficient to assess similarity between two users' rating profiles: **RMSE = 2.83**

### Code:
https://github.com/hamidniki/Capstone-project2/blob/master/Recommender-Engine-Using-A-Last.fm-Music-Dataset.ipynb

### Final report:
https://github.com/hamidniki/Capstone-project2/blob/master/Report-Capstone-Project2.pdf

### Final presentation:
https://github.com/hamidniki/Capstone-project2/blob/master/Recommender-Engine-Using-Last.fms-Artist-Rating-Data.pdf
