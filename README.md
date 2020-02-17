# anime-scraper
Scrapes anime links and details using **bs4** module

<p align="center"><img src="https://image.freepik.com/free-vector/young-woman-anime-style-character-vector-illustration-design_18591-62213.jpg" width="270px" height="300px"></p>

<h1> Anime Scraper </h1>
Anime scraper uses python's requests and BeautifulSoup module to scrape anime titles. The data is fetched from GogoAnime. 

<h2> How It Works </h2>
The script first fetches URL output which depends on the user's anime input. The requests.get() and variable.content helps in fethcing the page source and the page content. A soup object is created from the page content using BeautifulSoup.<br/>The soup objects is then filtered multiple time to obtain the desired results.

<h2> Libraries Required </h2>
<ol>
  <li> BeautifulSoup </li>
  <li> requests </li>
</ol>
<p> To add these modules, enter the following commands in your terminal </p>
<code> python -m pip install -r requirements.txt</code><br/>

## Examples

### Scraping by links

![links_scrape.png]

### Scraping by details

![details_scrape.png]
