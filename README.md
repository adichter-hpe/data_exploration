Student Data Exploration Project for DHBW Mannheim <br />
Andreas Dichter, Simon Schmid, Elisa Dandin

Goal of the project:
The goal of the project was to build a recommender system for movies.
The user should get to possibilities to get recommndations. One should be similar to the search function in Netflix, where the user inputs one title, but also gets similar movies recommended. The other method is similar to recommendations based on what the user watched. As we can't access live data on what the user watched, he gets do either like or dislike movies and these inputs are used for a comparison to a large number of other users, that rated a movie.

Necessities:<br />
Jupyter Notebook<br />
<br />
<br />
Optional Necessities for Webapp:<br />
Docker (with docker-compose)<br />
<br />
How To Use:<br />
There are 2 Jupyter Notebooks each inside their own folders (Jupyter content based and Jupyter ating based).<br />
They work separately from each other.<br />
Added to that a data folder needs to be downloaded from: https://drive.google.com/drive/folders/1oVauioVVkQPBdAkVoWw3MkV0Q13Lpg5W?usp=sharing<br />
A folder named "data" containing the .csv-files needs to be added to the project (or the import adresses inside the Jupyter notebooks need to be changed).<br />
Due to file size limitation on Github the datasets couldn't be included unfortunately.<br />
<br />
How to use basic webapp:<br />
The webapp is still work in progress, as we ran into RAM-limitations and therefore couldn't get the content (search) based algorithm to work and stopped implementing it.<br />
However an overview on how the webapp could look like with better equipment can be provided.<br />
  Commandline: Navigate to folder --> docker-compose up<br />
  End: Ctrl+C or (if run in detatched mode) docker-compose down<br />
  Webapp-App: localhost:5001<br />
<br />  
Datasets:<br />
https://www.kaggle.com/rounakbanik/the-movies-dataset/data (Content Based Recommendation)<br />
https://grouplens.org/datasets/movielens/latest/ (ml-latest-small.zip (direct link: https://files.grouplens.org/datasets/movielens/ml-latest-small.zip)) (Rating Based Recommendation)<br />

