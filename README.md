# science_article_webscraper
A **web crawler** that collects data about science articles, using Requests, Urllib2, and Selenium modules. Program visualizes article statistics using Plotly library, then outputs an HTML document.


Note: the `newsscraper.py` file is the **parent class** for all the individual site scrapers. In order to add a new website scraper, have it inherit all the functions from this class. This project currently collects data from three websites: engadget, popularmechanics, and techcrunch. Scrapers for additional websites can easily be added to `main_session.py`.


###### See the examples folder to view the sample HTML output document source. Also in that folder are more images, however the current graphs created by the program are fairly messy and need to be cleaned up.



<a href="https://cdn.rawgit.com/alexander-hamme/Science_Article_Webscraper/a0351637/examples/html_output_articles_list.html">
  <img src="https://github.com/alexander-hamme/Science_Article_Webscraper/blob/master/examples/screenshot.png?raw=true" alt="Image could not be loaded, please look in the examples folder of this repository."></a>

-----
###### Sample graph:


<img src="https://github.com/alexander-hamme/Science_Article_Webscraper/blob/master/examples/popular_mechanics_graph2.PNG?raw=true" alt="Image could not be loaded, please look in the examples folder of this repository.">



###### Final notes: in order to implement these scrapers, Chromedriver is needed. Additionally, keep in mind that websites get updated, and when this happens element tag names may change, so double checking that these identifiers are still correct is recommended.
