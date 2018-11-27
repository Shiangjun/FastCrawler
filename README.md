# Web_Crawler_For_Movielens
This is the source for sub-project in Chestnut: "Investigate, Collect and Supply Related Movie Information in Movielens via Web Crawler"

## Data set 
Movielens ml-latest & HetRec-2011

## Features
It applied three key features here:

1. Through IMDB instead of Movielens
  Since Movielens required user to log in, we take adavantage of that default data set has offered three different link tags for one movie. To ensure information could be gathered as much as possible, we chose IMDB as our target.

2. Retrive information directly
  Through source files analysis, we found these movie pages in imdb (which could be transfered from movielens ID) contain a special component "description". Following a default setting, director's names are contained between "Directed by" and the first ".". 
  
3. Local analysis for director information
  As previous setting shown, we utilize this feature to contain "description" information, and then we get director information locally through string processing.
  
