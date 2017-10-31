# NewsScraper
This is an app that lets users leave comments on the latest UG Football news. It usees Mongoose and Cheerio to scrape news from espn Georgia College Football site.

NPM Packages used:
express
mongoose
morgan
body-parser
cheerio
reques

Whenever a user visits the site, the app will scrape stories from a news page. 

It uses Cheerio to grab the site content and Mongoose to save MongoDB database.

All users can leave comments on the stories they collect. They are also allowed to delete whatever comments they want removed.

All stored comments are visible to every user.
