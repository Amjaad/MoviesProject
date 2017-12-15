# MoviesProject

Source code for CU Boulder CSCI 4502 final project. 

The project mines IMDb ratings dataings to answer the question, "Are IMDb ratings biased?"  

regression.ipynb
This code provides our regression analysis of the IMDB dataset. It first finds the most popular actors in the dataset and finds their average ratings. Then it moves on to a simple linear regression of the data. In this section we test average ratings with a series of attributes in the dataset including run time and start year.
 
 
anova.ipynb
This code provides the ANOVA testing for several attributes of the IMDB dataset. The chief relationship we looked at here was between ratings and genre, with additional attributes including number of votes and runtime. We found that there was only little variance due to the genre attribute. This leaves us with the conclusion that genre and ratings are very weakly correlated. 
 
 
titles.principals.ipynb
Preprocessing, descriptive statistics and preliminary visualizations of the IMDb actor data.

title.crew.ipynb
Preprocessing, descriptive statistics and preliminary visualizations of the IMDb writer and director data. 

title.ratings.ipynb
Preprocessing, descriptive statistics and preliminary visualizations of the IMDb genre and year data. 

OMDb.ipynb
Code for downloading Metacritic data from the OMDb API.




