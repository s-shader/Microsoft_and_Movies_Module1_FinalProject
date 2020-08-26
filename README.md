# Microsoft_and_Movies_Module1_FinalProject
## Question: What qualities make for a good movie and should Microsoft produce them?
  * What effect do ratings, reviews, movie length have on a movies success?
  * How does Microsoft's operations compare, financilay, to those of movie producers?
## Process & Tools Used:
### From included files:
  *  RT, IMDB, TMDB, and TN 
### Other
  * Web Scraping: Wikipedia and Yahoo Finance
  * YFinance: Yahoo Finance library
## Findings 
### I analyzed movies by three metrics: 
  * Ratings (G,PG,Pg-13...)
  * Reveiws (on scale of 1 to 10) 
  * Length (in minutes)
### All three metrics occur across all movies and are universal, definable, and/or group-able  
### My first angle was to look at ratings and see how they effeccted box office sale, which is the best avalable proxy for success. All of the neccesary data is avalable via the RT tables and with some cleaning and organizing shows the following.
![alt text](https://github.com/s-shader/Microsoft_and_Movies_Module1_FinalProject/blob/master/Images/boxOffice_vs_ratings.png)
### The data is skewed so I included both mean and median data. Either way, however, it is clear that PG and PG-13 movies did the best.

### Next I looked at runtime i.e. movie lenght in minutes. Given the impoerct dat avaliable I used reviews as a proxy for movie sucess. The both data sets existed in IMDB tables and with some merging and rearanging showed the following. 
![alt text](https://github.com/s-shader/Microsoft_and_Movies_Module1_FinalProject/blob/master/Images/ratings_vs_runtime.png)
### As can be seen in the graph above lenght is barely corellated with reviews i.e. the correlation coefficient is 0.026.

### Finally I looked at reviews and in comparsons to the ROI of movies. Return on investment being the percent profit a movie made on it's budget. This data existed across the TMDB and TN data sets but with a bit of trial and error were able to be merged and compared to show:
![alt text](https://github.com/s-shader/Microsoft_and_Movies_Module1_FinalProject/blob/master/Images/voteAVG_vs_ROI.png)
### Again ROI and reviews are hardley correlated with a correlation coefficient or 0.03.  

### Switching directions I took a broader look at the industry. Wikipedia provided some easily scrapable table on market share in the industry.
![alt text](https://github.com/s-shader/Microsoft_and_Movies_Module1_FinalProject/blob/master/Images/marketShare_table.png)
### Put diffrently.
![alt text](https://github.com/s-shader/Microsoft_and_Movies_Module1_FinalProject/blob/master/Images/marketShare_graph.png)
### As can be seen from either, 6 companies control the bulk of the industry (>80%) and became my proxy for the broader industry.
### From Yaho Finance I was able to scrape data on operating margnins, net margind, return on assets, and return on equity for the top movie producers along with Microsoft. Given the potential for the data to be skewed I took both the mean and medain for all financial metrics of the movie industry companies to comapre with those of Microsoft's.
![alt text](https://github.com/s-shader/Microsoft_and_Movies_Module1_FinalProject/blob/master/Images/Microsoft_vs_Industry.png)
### Above you can see Microsoft, in green, and the mean and median data from the top movie producers. For all metrics using both the mean and median Microsoft does significantly better.

