<b>Flatiron School Mod 1 Project</b><br>
<br>
<br>
Contributors: Austin Krause and Ran Tokman<br><br>
Link to presentation slideshow: https://docs.google.com/presentation/d/1kgbR6-_efBxQQtMYtiyv-YSppf2fU431R0HFtjnoDbo/edit#slide=id.p<br>
<br>
<b>Project Goals:</b><br>
  -scrape data from Rotten Tomatoes and use titles as a base dataframe<br>
  -use aspects of the scraped data to make API requests on IMDB, OMDB and TMDB<br>
  -find relationships within our data to describe what types of movies may return higher revenue/profits<br>
  -find insights within the data using Pandas and display that information using Seaborn, Matplotlib etc

<b>Questions to be answered:</b><br>
  -Does Rotten Score or Metascore have an overall impact on profitability of a movie?<br>
  -Are there trends in profitibility based on movie ratings (G, PG, PG-13, R)? <br>
  -Does accessibility of seeing a movie bring higher profits?<br>
  <br><br>
  
  
  ![graph_1](mod_1_pic_1.png)<br>
  Is there a discrepancy between Metascore and Rotten Score? Above shows the break down of the average difference between Metascore and Rotten Score per year.<br><br>
  ![graph_2](mod_1_pic_2.png)<br>
  Next we made a subset of our dataframe to only include movies that scored above 90 in either Metascore or Rotten Score. Shown by the graph, Metascore does not seem to be a reliable way of prediciting profitibility. We cannot say that Rotten Score can predict profitibility either, however, it shows to be a bit more consistent than Metascore.<br><br>
  ![graph_3](mod_1_pic_4.png)<br>
  What movie rating shows the highest average profits? To do this we grouped our dataset into the most popular movie categories (G, PG, PG-13, R) and found the mean profit for each grouping. According to our data, PG movies tend to profit the most, with G and PG-13 movies profitting strongly as well. This may speak to the accessibility of the movies. Rated R movies will exclude most of the younger population and could play a factor in that regard. Finally, we look at the break down of the each group.<br><br>
  ![graph_4](mod_1_pic_3.png)<br>
  To get a better look, we will need to incorporate more data in the future to even out the groupings. <br><br>
<b>Going forward:</b><br>
  -Utilize data from that we scraped from BoxOfficeMojo<br>
  -Compare our findings with findings in the new data<br>
  -Expand range of movie years beyond 2009-2018<br>
