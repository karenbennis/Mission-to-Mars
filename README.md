# Mission-to-Mars
This repository contains files for creating a flask app which scrapes different astronomy websites for information about and images of Mars, and renders the Mars data in a browser and stores the scraped data in MongoDB.

## Resources
* Data Sources: http://mars.nasa.gov/news/, https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars, https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars, http://space-facts.com/mars/
* Langauges: Python 3.7.6,  HTML5, CSS, Bootstrap
* Libraries: Pandas, Splinter, BeautifulSoup4, Datetime, PyMongo, Flask
* Database: MongoDB 4.2.6
* Software: Jupyter Lab 1.2.6, Visual Studio Code 1.43.0, MongoDB Compass Community 1.20.5

## Summary
### Files
The following files were created to run the Mission-to-Mars web app:

* Mission-to-Mars.ipynb (working notebook for defining funcitons to be included in the application file)
* app.py (app routes)
* scraping.py (web scraping functions)
* index.html (front end code)

### Results
The following is a screenshot of the front-end of the Mission-to-Mars webapp:
![](https://github.com/karenbennis/Mission-to-Mars/blob/master/FrontEndApppng.png)

Note that the featured image and mars facts section are refreshed dynamically during scraping.

The following is a screenshot of the back-end of the Mission-to-Mars webapp:
![](https://github.com/karenbennis/Mission-to-Mars/blob/master/MongoDBCompassCommunity.png)

This confirms that the scraped data is indeed being stored in MongoDB.

### Recommendations for further analysis
This webapp is largely exploratory. It would be very interesting to work with a real client on pulling content that meets a real business need. Through elicitation and collaboration, it would be possible to create an app that serves a genuine purpose outside exploration.
