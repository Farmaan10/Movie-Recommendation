
# Movie Recommendation System
Movie recommendation system has become an interesting research topic due to the growth of users in a mobile environment. To recommend movies, a complete aggregation of user’s preferences, feelings (emotions), and reviews required to assist users for find best movies in more convenient way. In this project, the method is based on extracting and analysing adjectives from user-based reviews. We exploit the idea that adjectives often contain a sentiment, and present a system entirely based on adjectives as sentiment deciders.

Check out the final work at:  [Movie Recommendation System using Sentiment Analysis](https://movie-recommendation-system10.herokuapp.com/)

## How to get the API key?
Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

## Architecture
![IMG-20210306-WA0012](https://user-images.githubusercontent.com/36665975/110212434-597bb700-7ec1-11eb-9ffa-7ac319e33123.jpg)

## Schematic Diagram
![Schematic](https://user-images.githubusercontent.com/68768741/133893556-3d667194-0ee9-422c-ab37-344db4aaa062.PNG)

## Block Diagram
![Block Diagram](https://user-images.githubusercontent.com/68768741/133893557-edab5c35-3ff5-44bf-a47e-5b6368b5e9c5.png)

## How Cosine Similarity works?
  Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![image](https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png)

## Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

## Example Top 10 Recommended Movies
![Top 10](https://user-images.githubusercontent.com/68768741/133893734-9d34b8d7-e1b5-406f-9929-896c3452dd57.png)
