
# Movie recommendations project 


Welcome to the Movie Recommender System Repository! Our project offers a streamlined movie recommender system that, as you type a movie's name in the search box, promptly generates five closely related movie suggestions. This user-friendly system provides you with relevant recommendations in an aesthetically pleasing and grammatically correct format, enhancing your cinematic exploration. Discover your next movie adventure effortlessly with us!














## 🛠 Tools used


Pyhton, Nltk , Sklearn, Streamlit
# Steps 
## 1) Data cleaning and analysis with python
#### (i) Cleansed the data
#### (i) Extracted the important key words from each column 
#### (ii) Combined some of the columns and created a new column name tags

## 2) Model Building
#### (i) Applied stemming on tags column with the help of ntlk library.
#### (ii) Generated vectors from tags column with the help of sklearn countvectorizer.
#### (iii) Generated cosine similarity between all the movies based on tags column and stored that into object called similarity.
#### (iv) Perfomed python functions which will fetch top 5 movie names from our data  which are most similar to the movie the user will search in our webpage on the basis of cosine similarity.
#### (iv) Saved our DataFrame to a folder with pickle  by converting it to dictionary.
#### (v) Also saved similarity data to a folder with pickle.

## 3) Webpage building
### (i) Imported the pickle folders from jupyter notebook.
### (ii) created various features of webpage with streamlit. 
### (iii) Applied function which  will fetch title of top 5 movie after searching movie in title box .
### (iv) Deployed to render.com

# Here are some screen shots showing how it works:




<img width="960" alt="1" src="https://github.com/bhratsharmaa/movies_recommendation_1/assets/132134997/2cc57ca2-26f7-42eb-b736-1d1a192abab8">






<img width="960" alt="2" src="https://github.com/bhratsharmaa/movies_recommendation_1/assets/132134997/ed4c511e-fb08-4b7e-9b2d-dab0e64c35b6">






<img width="960" alt="3" src="https://github.com/bhratsharmaa/movies_recommendation_1/assets/132134997/232d2639-f508-4845-8bc8-6073c4bdac03">







# Problems Faced
### (i) Selecting important keywords from the columns
### (ii) Determining the most effective method for measuring movie similarity.
### (iii) Identifying the approach to building the webpage.
### (iv)  Exploring the process of deploying our webpage.


.




