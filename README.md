<link rel="stylesheet" href="readme.css">

<h1 style="text-align: center;">MICROSOFT NEW MOVIE STUDIO</h1>


![film%20logo.png](attachment:film%20logo.png)


### BUSINESS PROBLEM


Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.


### OBJECTIVE


Use exploratory data analysis and investigate the film industry data set to gain in depth knowledge of what makes a studio successful and in turn utilize this analysis to create actionable recommendations for Microsoft new movie studio.


Import all the necessary libraries and import data frames

```

#load the data set
movie_gross_df = pd.read_csv('bom.movie_gross.csv')

movie_gross_df

```

```

tmdb_df = pd.read_csv('tmdb.movies.csv')
tmdb_df

```

### DATA CLEANING


This will involve dropping columns not required,deleting duplicate rows and filling Nan value spaces to make the data sets easier to work with.
Save the cleaned data set and Combine the two files into one dataset for analysis.


```

movie_df = tmdb_df2.merge(movie_gross_df2, on='title')

movie_df

```












