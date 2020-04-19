# Hollywood-movie-data-analysis
Analyze Hollywood movies data set from 1960 to 2015



Note and Conclusion 

1.	The data set (TMDB movie data) I analyzed was download from:   https://www.kaggle.com/tmdb/tmdb-movie-metadata.  

The data set being used for analysis is named “ tmdb_5000_movies.csv  ”

2.	Questions I posted 

Movie 
1.	List the highest rating(or top 10) movies (base on weighted rating)
2.	List the most(or top 10) profitable movies 

Genery
1.	List the most profit Genery(or top 10)/or combination
2.	List the highest score Genery(or top 10)
3.	Find out the most frequent genres hit both “excellent rating and great profit ” category
4.	Fin out the highest ratio of the genery hit “excellent rating and great profit ” category

Directors 
1.	List the director(or top 10) has the most combined profit (all the movie he/she has directed)
2.	List the director(or top 10) has the highest average movie score(all the movie he/she has directed)
3.	List eh director (or top 10) has the most movies hit “excellent rating and great profit” category
4.	Who(or top 10) has most movies been directed.


Production Companies
1.	Which producton companies(or top 10) produced most movies hit “excellent rating and great profit” category
2.	Which production companies(or top 10) produced movies with the highest ratio met “excellent rating and great profit” category



3. Step I investigate those question:

1.	Clean data set
2.	Set up the formula (weighted rating) to calculate rating score.
3.	Categorized all data  into 4 rating level
4.	Create and append score ranking column
5.	Calculate profit (revenue – budget)
6.	Categorized all data into 4 profit level
7.	Create and append profit ranking column
8.	Combined and append the above
9.	Find out the data set overlapping “excellent rating and great profit”
10.	List out the data for movies, production companies, director, genery all hit the “excellent rating and great profit”
11.	Calculate the ratio which hit “excellent rating and great profit” ( total frame and profit/total movies counts)
12.	Create bar chart 



4.Documentation of data wrangling I did
tmdb-movies.csv

Reference :

The movie rating score (‘weighted rating’) was referened
From “Ibtesam Ahmed” under Kaggle kernels.
 




5.Conclusion : 

Analysis was based on 10866 row and 21 columns movies data. 

 44  row  ‘director’  data were missing
 23  row  ‘ genres ‘  data were missing



Genres :

plot 2-1, plot 2-2, plot 4-1 , plot 4-2

1.	Genres key word or combine genres :  DRAMA ,CRIME, THRILLER,  MYSTERY, ACTION has higher ratio to meet ‘Great Profit’ movie compare to other genres.

2.	Genres key word or combine genres :  DRAMA, HISTORY, THRILLER, WAR, FANTASY,ROANCE , CRIME,  FANTASY   has higher ratio to meet ‘ Excellent Rating’ compare to other genres.


3.	Genres key word : DRAMA , CRIME, THRILLER has the highest ratio to meet both “Fame and profit ”

4.	‘Drama’ dominances the ratio for   ‘ Fame and Profit’

5.	Drama’ is also the most frequent occurrence element genres of all movies. There are about 5000 movies with drama elements. Followed by comedy and Thriller and Action.

6.	 Data shows that Drama, Comedy and Thriller has the most robust trend from 1960 to 2015 compare the rest genres



Production Company:

Plot 1-1, plot 1-2

Compared with other companies, the big 6 has a prominent performance in the film of "Fame and Fortune". Among them, Paramount Picture is particularly prominent in quantity and proportion.


Data Correlation: 

Plot 3-1 , plot 3-2

Score Rating and Profit has positive correlate relation. But not a significant one.

Budget and Profit has positive correlate relation.




About the Analysis

I made this report is to serve as a reference for the film investors. If you want to invest in a movie , some questions would be likes : what kind of genres and what kind of directors will be used , what kind of production companies will you cooperate with, or how large-scale investment will you intend to commit in return for a greater chance of producing "fame and gain" movies.   Of course, we understand that the above data can only be used as a statistic to explain some aspect of the industry, and true artistic creation contains more specific factors. But the above data can serve as a reference for a different angle of a bigger picture for the investors.

The lack of some movie data also affects the accuracy of the analysis.




