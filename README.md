# Mission-to-Mars

## Overview
### Purpose
In this ANalysis, we will help Robin scrape, organize, analyze, and visualize the data. We will identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup
## Results :
###Deliverable 1 :  Scrape titles and preview text from Mars news articles. Optionally export the data into a JSON file or a MongoDB database.
#### Code and Images
        mars_news = []
        for m in news_p:
        title = m.find("div", class_="content_title").text
        preview = m.find("div", class_="article_teaser_body").text
   
        mars_dict = {}
        mars_dict["title"] = title
        mars_dict["preview"] = preview
   
        mars_news.append(mars_dict)
        mars_dict

        
### Deliverable 2 :
Scrape and analyze Mars weather data, which exists in a table.


#### Code and Images
### CSV File
