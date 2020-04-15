# News-Scraper

### Overview

My New York Time's Scraper is a scraper app which grabs the title, summary and image of articles from The New York Times. Users can save their preferred articles, add notes and edit notes to one or multiple articles. In addition the app provides search feature, allowing users to search in titles according to different key words.

In this repository, you can see source code of News Scraper. 


### Key Dependencies

`request`: enables `cheerio` to get access to front-end code of https://www.nytimes.com/section/world

`cheerio`: scrapes front-end code from https://www.nytimes.com/section/world

`mongoose`: be in charge of database of `scrap`

`express`: builds server-side routes and functions

`morgan`: logs server-side requests, helping debugging

`express-handlebars`: a powerful front-end builder without requiring multiple html pages