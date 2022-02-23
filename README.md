# Netflix-Movies-and-TV-shows

## Description:

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
Netflix, Inc. is an American over-the-top content platform and production company headquartered in Los Gatos, California. The company's primary business is a subscription-based streaming service offering online streaming from a library of films and television series, including those produced in-house. 
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

The streaming platform has increased his catalogue substantially in his last 10 years of existence. Netflix has way more films than all his competitors, such as HBO or Amazon video, which are following Netflix`s steps in order to obtain the same success. 

## Execution: 

### Dataset: 
https://www.kaggle.com/onyonixch/netflix-movies-tv-shows-eda-and-clustering

### Data Visualization:

Data Visualization is graphical representation of information and data. One such visualization is to plot distribution of the variable type (Movie or TV Show) and to find out that around 65% of the data we have is of the type “movie” and the rest is of the type “TV show”.

Similarly, we can also plot the frequency of different kinds of rating in the whole dataset to find out that the most of the movies are rated TV-MA (TV-Mature Audience) and last on the list are the ratings NC-17 and UR.

Also, we can plot relation between Type and Rating which gives us the frequency of different ratings for different kinds of movie titles namely Movie and TV shows.

Next, we plotted the distribution of the data after dropping the null values. We previously saw that we had some null values and after removing those null values, we lost a lot of data mainly in the genre of TV shows.

Also, we plotted the frequency of the number of titles released per year. Plotting that graph, we find out that the number of titles released increase from the year 1994 till the year 2017 and after the year 2017 we see a gradual decrease in the number of titles whose possible reasons could be either lack of data or the Covid-19.

Similarly, we plotted the frequency of different genres in titles released in Netflix to find out that the genre “International Movies” stands first continued with “Dramas” and “action and adventures”.

Also, we plotted a Word Cloud for different Countries. A Word Cloud is an image composed of words used in a particular text or subject, in which the size of each word indicates its frequency or importance. We can infer from the picture that the United States comes first followed by India and the United Kingdom.

Next, plotting a Word Cloud of directors, we find out that David is the most common name that comes up for a director and following that name is John, Michael and peter.

Coming to the second part, which is Data Modelling in which we try out different Un Supervised Machine Learning Classification algorithms fits the best to our dataset and gives us good recommendations.

### Data Modelling:

I tried two different algorithms, 1. Natural Language processing (NLP) and 2. K-means Clustering.

The first model i.e., NLP is a subfield of linguistics, computer science, and artificial intelligence concerned with the interactions between computers and human language, in particular how to program computers to process and analyze large amounts of natural language data.

Testing the NLP model in our Movies and TV Shows we don’t find satisfactory results and we move on to the next model K-means Clustering.

k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. 

Fitting the K-means model on our dataset, we find out that the recommendations given from the K-means are very close to the given Netflix title.

### Conclusion:

According to the recommendations seen from both the models, the results from the K-means model were very close to the films in terms of the description of the movie.

### References: 
  1. https://www.analyticsvidhya.com/blog/2021/06/tv-shows-analysis-netflix-prime-video-hulu-and-disney/
  2. https://towardsdatascience.com/netflix-recommender-system-a-big-data-case-study-19cfa6d56ff5

