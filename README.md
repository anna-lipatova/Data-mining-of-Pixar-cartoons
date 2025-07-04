# Pixar Movies Analysis
## Project Description
*Dataset*: [Pixar Films](https://github.com/erictleung/pixarfilms)
*Source*: [Maven Pixar Challenge](https://mavenanalytics.io/challenges/maven-pixar-challenge/967013fc-1ff2-4453-a1ac-1ac1e0624c52)
*GitHub Source*: [Git Pixar Films](https://github.com/erictleung/pixarfilms)

### Description:
There are 6 tables which describe different movies produced by Pixar.
1. Films - Title, Release Date, Duration.
2. People - Title, Role, Name_Surname
3. Genres - Title, Category, Value
4. Box Office - Title, Budget, Box Office US+Canada, Box Office Other, Box Office Worldwide
5. Review - Title, Rotten Tomatoes Score, Rotten Tomatoes Counts, Metacritic Score, Metacritic Counts, Cinema Score, Cinema Counts, IMDB Score, IMDB Counts
6. Awards - Title, Award Type, Status

The project is going to embrace the following tables:
- Films (Title, Release Date, Duration)
- Genres (Title, Category, Value)
- Box Office (Title, Budget, Box Office Worldwide)
- Review (Title, IMDB Score, IMDB Counts)

Here we are interested in filtered data. For instance, Box Office Worldwide only, IMDB reviews only.

The plan is following:
- to preprocess data;
- to show distributions of 'run time per year', 'number of films per year', '(sub)genre frequency ', 'rating and counts', 'avg budget and box office per year';
- to show correlation 'rating' and 'budget' and 'box office';
- to predict a box office depending on budget, (sub)genre, rating.
