# art-station-scraper

This repo contains a scraper for the website https://www.artstation.com/, as well as some other GAN stuff I've been working on with my scraped data.

Scraper and data used for academic purposes only. Feel free to use, but please do so within reasonable limits. There are some inbuilt delay timers which can be adjusted.

How to use:

This scraper allows targeted scraping using query keywords. You can change the keywords in the notebooks.

1) Use art-station-scraper.ipynb to scrape metadata from the site. The metadata will contain urls that will be used to scrape images. Json files will be produced containing the image urls.

2) Use art-station-download-images.ipynb to download the images from the json files.
