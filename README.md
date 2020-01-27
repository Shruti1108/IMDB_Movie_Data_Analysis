This project is about Data Analysis.
How we can load the dataset, do analysis & find out insights of Data.
In this project I will analyse IMDb's data set containing information about 6486662 movies.
The link of datasource - https://datasets.imdbws.com/
So here dataset is explain below
1. title.basics - Contains the following information for titles:
tconst (string) - alphanumeric unique identifier of the title
titleType (string) – the type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc)
primaryTitle (string) – the more popular title / the title used by the filmmakers on promotional materials at the point of release
originalTitle (string) - original title, in the original language
isAdult (boolean) - 0: non-adult title; 1: adult title
startYear (YYYY) – represents the release year of a title. In the case of TV Series, it is the series start year
endYear (YYYY) – TV Series end year. ‘\N’ for all other title types
runtimeMinutes – primary runtime of the title, in minutes
genres (string array) – includes up to three genres associated with the title

2. title.ratings – Contains the IMDb rating and votes information for titles
tconst (string) - alphanumeric unique identifier of the title
averageRating – weighted average of all the individual user ratings
numVotes - number of votes the title has received

3. Movie_finance_data.csv
popularity - numbers of popularity
budget - total film making budget
revenue - total revenue earn by film

Business Questions to derive from
1.Which genres are the most common (number of movies made)?
2.Which genres have high avg. budget and revenue?
3.Which genres have high avg. profit?
4.Which genres have high average rating?
5.Which genres have high avg. popularity?
6. Which genres have high number of vote count?

Analysis & hypothesis
1.Analysis of variables per genre over the years
2.Budget per genre per year
3.Avg.rating per genre
4.Highly budgeted movies return high revenue and profit.
