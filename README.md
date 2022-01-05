# Mission-to-Mars
## Overview:
The purpose of this project was to build an APP to conduct web-scraping of MARS data and create an HTML page to show the results. Using BeautifulSoup, Splinter, and Pandas to scrape full-resolution images of Mars’s hemispheres and the titles of those images, the scraped data was stored in a Mongo database, and displayed in a re-designed web app using Flask to accommodate these images.

## Resources

- **Data Sources:**  
    [Mars News](https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest), [Mars Featured Images](https://spaceimages-mars.com/), [Mars Facts](https://galaxyfacts-mars.com/), [Mars Hemispheres](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars)

- **Environment:**

   Python 3.7
- **Dependencies:**

   Beautiful Soup and Splinter
- **Languages:**

   HTML, CSS, Bootstrap 3 and Python
- **Software:**

   Jupyter Notebook, VS Code, MongoDB, Flask and Chrome

## Results
**Scraping Mars Data**

By using, splinter and beautiful soup libraries we have scrape the relevant data in [Mission-to-Mars Jupyter notebook](https://github.com/NensiH/Mission-to-Mars/blob/main/mars_scraping/Mission_to_Mars_Challenge.ipynb). Then, Python to write the script in [scraping.py](https://github.com/NensiH/Mission-to-Mars/blob/main/mars_scraping/scraping.py) and transformed the data to a Mongo Database before uploading the data to the webpage using flask in [app.py](https://github.com/NensiH/Mission-to-Mars/blob/main/mars_scraping/app.py) and at last, used bootstrap to cleanup the webpage to make it presentable in [index.html](https://github.com/NensiH/Mission-to-Mars/blob/main/mars_scraping/templates/index.html).

Here is the screenshot of the successfully created a page that displays the data collected and also mobile-responsive webpage:



<img width="588" alt="Screen Shot 2022-01-01 at 11 54 32 PM" src="https://user-images.githubusercontent.com/92277581/147867550-0b93ee26-7417-4b18-9142-1d6a235eb471.png">
