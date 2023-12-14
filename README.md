# Hybrid Recommender System using MovieLens Dataset
- User-Based Recommendation
- Item-Based Recommendation

**Business Problem**

Make a guess for the user whose ID is given, using the **item-based** and **user-based** recommender methods.
Consider 5 suggestions from the **user-based** model and 5 suggestions from the **item-based** model and finally make 10 suggestions from 2 models.

**Dataset Story**

The dataset was provided by **MovieLens**, a movie recommendation service. It contains the rating scores for these movies along with the movies. It contains 20.000.263 ratings across 27.278 movies. This dataset was created on October 17, 2016. Includes 138.493 users and data from 09 January 1995 to 31 March 2015. Users are randomly selected. It is known that all selected users voted for at least 20 movies.

**Variables**

**Movie Dataset**
- **movieId:** Unique movie ID
- **title:** Movie title
- **genres:** Movie genre

**Rating Dataset**
- **userId:** Unique User ID
- **movieId:** Unique Movie ID
- **rating:** Rating given to the movie by the user
- **timestamp:** Review data

---

## Requirements
~~~python
pandas==1.5.1
~~~

---

## Author
[Oktay Acar](https://github.com/oktay-acar)