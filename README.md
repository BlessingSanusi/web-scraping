## New Web Scraper

### Overview

A web app that scrapes New York Times and let users view and leave comments on the latest news

* The app accomplishes the following:

  1. Whenever a user visits the web page, the app scrapes stories from New York TImes website. Each scraped article is saved mongodb. At a minimum. The app scrapes and display the following information for each article:

     * Headline - the title of the article

     * Summary - a short summary of the article

     * URL - the url to the original article

  2. Users can also leave comments on the articles displayed and revisit them later. The comments are also saved in mongodb and associated with their articles. Users can also delete comments left on articles.

  ## NPM Packages
    * Axios
    * Cheerio
    * Mongoose 
    * Express
    * Express-handlebars


    ![scraper](/assets/images/web-app.png)