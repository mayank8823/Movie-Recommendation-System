# Movie-Recommendation-System
Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site and performed sentiment analysis on those reviews.

This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc. Don't worry if the movie that you are looking for is not auto-suggested. Just type the movie name and click on "enter". You will be good to go eventhough if you made some typo errors.

# Architecture:
![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/16528da4-0f54-44eb-a086-6adba31727f5)

# Similarity Score And Cosine Similarity:
Similarity score is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items.

Cosine similarity measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

# Technologies Used:
Web Technologies: Html , Css , JavaScript , Bootstrap , ExpressJS

Machine Learning Library In Python3: Jupyter Notebook, Numpy, Pandas, Flask

Database: MongoDB

Github, Figma

# Screenshots of my Project:
Registration Page:

![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/adcd017b-34db-4662-814c-1f4e489ece6e)

Login Page:

![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/8b9e4444-7ce8-44dc-9665-794f2240b000)

Home Page:

![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/f1f3b334-254b-4acd-97cb-5c6482c2edcf)

User Profile Page:

![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/cf2366f4-87d4-4031-b715-0064cf82aad8)

Auto-Complete Suggestion and Voice Search:

![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/adabccb4-172c-4cf8-a393-5ee93f7a827b)

Recommendation on Search Basis:

![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/237f6675-029e-4b03-9c50-909561807a6c)

Description And Comment Section:

![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/3b0d7972-a5da-4abe-8888-0992cb4579ce)

Give review if already watched:

![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/e53532e1-73c8-4aaa-9857-f37715953c5e)

Contact Us Page:

![image](https://github.com/mayank8823/Movie-Recommendation-System/assets/111684416/650b169f-4091-449d-9243-9af418a4c95c)


Thank you for visiting my repository.
