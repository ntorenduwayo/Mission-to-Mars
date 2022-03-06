# Mission-to-Mars

## Overview of the analysis

We used scraping tools (i.e. BeautifulSoup, Splinter, ChromeDriverManager, webdriver, and Service) to scrape full-resolution images of Mars’s hemispheres and the titles of those images. Then, we stored the scraped data on a Mongo database, and used MongoDB and Flask application to display the data. Finally, we altered the design of the web app to accommodate these images.

## Results

  *	Scrape High-Resolution Mars Hemisphere Images and Titles:

  We visited https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars website and used DevTools to inspect it for the proper elements to scrape. 
  Using the scraping tools, we retrieved Mars Facts, the full-resolution image URL and title for each hemisphere image.
  (For more details see the Mission_to_Mars_Challenge.ipynb file)

  ### Table 1: Mars Facts
  ![](https://github.com/ntorenduwayo/Mission-to-Mars/blob/main/Resources/Mars%20Facts.png)

  ### Table 2: Image's Titles and URL Links
  ![](https://github.com/ntorenduwayo/Mission-to-Mars/blob/main/Resources/List%20that%20holds%20the%20dictionary%20of%20each%20image%20url%20and%20title..png)

  *	Update the Web App with Mars’s Hemisphere Images and Titles:

  We used the elements from our web scraping via MongoDB and Flask application to grab and display the full-resolution image URL and title for each hemisphere image from             https://marshemispheres.com/ website. (For more information, see the scraping.py file under the hemisphere function section.)

  *	Add Bootstrap 3 Components:

  We updated the web app to make it mobile-responsive, and add two additional Bootstrap 3 components to make it stand out. (For more information, see the index.html file in the     template folder.)

  ### Full resolution Mars's Images and Facts
  ![](https://github.com/ntorenduwayo/Mission-to-Mars/blob/main/Resources/Full-resolution%20images%20and%20the%20titles%20of%20the%20four%20hemisphere%20images..png)
