# Baby Names ETL Project

In this project, my team wanted to examine popular baby name data alongside popular tv show/movie data in order to determine if there is a relationship between popular movie/show character names and the most commonly used baby names during those years. 

    1. We looked at a dataset containing the most popular baby names from 2005-2017. 
    2. We used an API provided by The Movie DB to return the most popular movies and tv shows from 2012-2017. 
    3. We used the OMDb API to return each movie/tv show's uniqiue ID # that is listed on IMDb in order to web scrape for the list of character names using BeautifulSoup. 
    4. We brought all of this data into a Pandas dataframe for munging/transforming. 
    5. We merged the baby names dataframe with the movies/tv shows dataframe and examined for any correlation. 
    6. We used Plotly and Matplotlib to create visualizations. 
    7. We also loaded our final data into MongoDB for user access. 

In the end, we observed no definitive relationship between popular movie/tv character names and popular baby names during that time period. 

To see one of our interactive visualizations, please visit this link: https://cecind123.github.io/class_activities/Names_Plot.html
