# Mission-to-Mars

## Overview
Build a Web Application to scrapes different websites for data related to the Mission to Mars and the create an HTML Page to display my findings.

### Tools:
- Chrome Developer Tools to identify HTML components.
- Beatutiful Soup and Splinter to automated scrape and gather the data I identified.
- Mongo to store the data.
- Flask to create a Web Aplication to display.

## Summary

### Step 1: Data Scraping

*NASA Mars News:*
Collect the latest News Title and Paragraph Text.

*Mars Space Images - Featured Image:*
Find the image url for the current Featured Mars Image.

*Mars Facts:*
Visit the Mars Facts webpage and uses Pandas to scrape the table containing facts about the planet.

*Mars Hemispheres:*
Visit the USGS Astrogeology site and obtain the full resolution images for each of Mar's hemispheres.

### Step 2: MongoDB and Flask Application

Use MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped.


