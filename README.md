# Movie-Recommendation-System-Using-Python
![Uploading image.png…]()

 In this python project where using Pandas library we will find correlation and created basic Movie Recommender System with Python.

* I developed a **Movie Recommendation System** in Python to suggest popular movies based on ratings and vote counts. The project involved collecting and cleaning a movie dataset containing titles, genres, ratings, and vote information. A **popularity score** was calculated for each movie to rank them, highlighting the most trending and highly-rated films. I created a simple **user interface using Streamlit** to display the recommended movies in an organized layout. This project helped me understand real-world data handling, basic recommendation logic, and building a Python-based front-end, providing a foundation for more advanced recommendation techniques.
__________________
# 1)Content Based :
* Content-based systems, which use characteristic information and takes item attriubutes into consideration .

* Twitter , Youtube .

* Which music you are listening , what singer are you watching . Form embeddings for the features .

* User specific actions or similar items reccomendation .

* It will create a vector of it .

* These systems make recommendations using a user's item and profile features. They hypothesize that if a user was interested in an item in the past, they will once again be interested in it in the future

* One issue that arises is making obvious recommendations because of excessive specialization (user A is only interested in categories B, C, and D, and the system is not able to recommend items outside those categories, even though they could be interesting to them).
__________________
# 2) Collaborative Based :
*Collaborative filtering systems, which are based on user-item interactions.

* Clusters of users with same ratings , similar users .

* Book recommendation , so use cluster mechanism .

* We take only one parameter , ratings or comments .

* In short, collaborative filtering systems are based on the assumption that if a user likes item A and another user likes the same item A as well as another item, item B, the first user could also be interested in the second item .

* Issues are :

* User-Item nXn matrix , so computationally expensive .

* Only famous items will get reccomended .

* New items might not get reccomended at all .
_______________
# 3) Hybrid Based :
* Hybrid systems, which combine both types of information with the aim of avoiding problems that are generated when working with just one kind.

* Combination of both and used now a days .
### Extension
Have created a text input bar to add your movie whose recommendation you want. Output will give you top 4 matches that are recommended movies.

### Results
(https://user-images.githubusercontent.com/15246084/83949017-fdefa080-a83e-11ea-9b21-9c278a8dea45.png)
(https://user-images.githubusercontent.com/15246084/83949019-ffb96400-a83e-11ea-9607-3d1dbf5c3769.png)
