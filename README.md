
# Movie recommendations project 




![movie](https://github.com/bhratsharmaa/movies_recommendation_1/assets/132134997/d63db2b8-94a0-448c-8020-2f797d7cc318)













# Movie recommendations project 

## Project Description:
### Overview:
The Movie Recommendation Web Application is a data-driven project designed to assist movie enthusiasts in discovering new films similar to their favorite titles. Leveraging data from Kaggle, this project involves data preprocessing, feature engineering, and machine learning techniques to deliver personalized movie recommendations to users through an intuitive web interface.
### Key Project Steps:
#### 1) Data Import and Cleansing:
(i) The project begins by importing movie-related data from Kaggle, which includes information about movie_id, titles, overviews, genres, keywords, cast, and crew.

(ii) Data cleansing techniques are applied to handle missing values, duplicates etc,ensuring the quality and consistency of the dataset.

#### 2) Feature Engineering:
To improve the recommendation process, key information from various columns, including overview, genres, keywords, cast, and crew, is combined to create a new composite feature called "tags." This step enriches the dataset with valuable content information.
#### 3) Text Preprocessing:
Natural Language Processing (NLP) techniques are employed to preprocess the text data. This includes stemming using NLTK, which reduces words to their base forms, improving text similarity calculations.
#### 4) Vectorization:
Scikit-learn's vectorization methods are utilized to convert the text data into numerical format, making it suitable for machine learning algorithms. This step transforms the "tags" column into a numerical representation.
#### 5) Cosine Similarity:
The heart of the recommendation system is built on cosine similarity. Using Scikit-learn's cosine similarity function, the project calculates the similarity between movies based on their "tags."
#### 6) Recommendation Engine:
A recommendation model is developed using the cosine similarity scores. When a user inputs a movie title, the system identifies the top 5 movies that are most similar to the user's input.
#### 7) Web Page Development:
(i) The recommendation model is integrated into a user-friendly web application using Streamlit, a Python library for creating interactive web apps.

(ii) The web page provides a search box where users can input a movie title of their choice.
#### 8) Deployment:
The Movie Recommendation Web Page is deployed on render.com .

## Objective:
(i) Develop an accurate and efficient movie recommendation system.

(ii) Provide users with personalized movie recommendations based on their input.

(iii) Enhance the user experience by creating an intuitive web interface.

(iv) Deploy the web Page to make it accessible to a broad audience of movie enthusiasts.















## 🛠 Tools used


Pyhton, Nltk , Sklearn, Streamlit
## Data Cleaning &  Feature Engineering  :
(i) Checked and removed null,noise,duplicates.



<img width="271" alt="1" src="https://github.com/bhratsharmaa/Pizza_Sales_analysis/assets/132134997/ae42e69f-d395-48f3-abb0-16e520914ece">




(ii) Extracted the desired values from each column by appliying functions on the columns which were in the form of dictionary.


<img width="449" alt="2" src="https://github.com/bhratsharmaa/Pizza_Sales_analysis/assets/132134997/1faeeb4d-2338-4689-860a-a5dd451eb2ec">




<img width="335" alt="3" src="https://github.com/bhratsharmaa/Pizza_Sales_analysis/assets/132134997/1f2001cd-0556-4b7a-9fa0-a17305605c56">







(iii)  meticulously amalgamated the contents of these columns, ingeniously crafting a novel column dubbed 'tags.' This involved uniting all the extracted values with spaces and then uniformly converting them to lowercase



<img width="617" alt="4" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/61d5272b-df0c-4021-b910-f027e486b71d">






 
 ## Model Building 
 (i) The installation of 'nltk' was followed by the importation of the 'PorterStemmer' module. Stemming, a crucial data refinement process, was then skillfully applied to reduce words to their base forms.
 
 
 
 
 
 <img width="474" alt="4" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/9b209dfc-5ae8-4ec9-b119-869d4252da7d">







 
 (ii) Installed 'CountVectorizer' from 'sklearn' with 'max_features' set to 5000. Created an object named 'vector' using 'cv.fit_transform' to transform the 'tags' column in our dataset into a numerical format.





<img width="591" alt="5" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/aac8757f-03d2-487d-a581-e25dc7ec38a1">






 
 (iii) Incorporating the power of 'cosine_similarity' from the 'sklearn.metrics.pairwise' library, this code elegantly measures the similarity between movies by analyzing their content. By constructing a similarity matrix, the 'recommend' function is equipped to accept a movie title as input. It meticulously identifies the movie's index in the dataset, subsequently retrieving the top 5 most akin movies. These recommendations are thoughtfully curated based on the movies' cosine similarity scores, empowering users to explore cinematic gems aligned with their unique content preferences.

 






<img width="764" alt="6" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/234a012c-ca44-402c-b35c-e3d7189374fd">











<img width="370" alt="7" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/e78d607d-c5c9-486b-93c3-7d8100f528ae">










 (iv) Saved the movies and similarity in a folder with the help of pickle.







<img width="626" alt="8" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/824daad0-1051-4a43-84e0-1d5a071b0ad7">








 

 ## Webpage building
 A Movie Recommender system was created using Python and Streamlit. The code utilizes a dataset of movies, loaded from a 'movies_dict.pkl' file, and a precomputed similarity matrix from 'similarity.pkl.' The heart of the system is the 'recommend' function, which takes a user-selected movie as input and returns a list of the top 5 recommended movies based on similarity scores. The Streamlit-based user interface allows users to choose a movie from the dataset and click the 'Recommend' button to instantly receive personalized movie suggestions. This project offers an engaging and user-friendly way to explore movie recommendations.










<img width="590" alt="9" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/329ec6e9-ae47-4b67-bfc8-1a298fa4cde1">










<img width="456" alt="10" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/d572b3ab-8bce-4551-85f6-5da6ba2f2cb9">




# Here are some screenshots showing how it works 








<img width="960" alt="11" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/b87c06d0-83a8-4a20-aff2-67206faa1175">










<img width="960" alt="12" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/4c1e8ed5-6df1-43dc-8f8f-212615863f70">













<img width="960" alt="13" src="https://github.com/bhratsharmaa/movies_recommendation_model/assets/132134997/ff1971fe-ca78-4489-8cf7-85727d1e1714">












# Problems Faced
### (i) Selecting important keywords from the columns
### (ii) Determining the most effective method for measuring movie similarity.
### (iii) Identifying the approach to building the webpage.
### (iv)  Exploring the process of deploying our webpage.  




.









