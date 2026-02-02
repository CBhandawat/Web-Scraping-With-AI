# Web-Scraping-With-AI

THE PROMPT I USED FOR CREATING THE PLAYWRIGHT PYTHON SCRIPT:

You are a Web scraper who is going to scrape this site: https://quotes.toscrape.com/js Using Playwright and in Google Colab 

I want this information in a CSV FILE:

1. Quote
2. Author
3. Tags(Comma separated if multiple)

The OuterHTML of the page for one of the quotes is:

<div class="quote"><span class="text">“It takes a great deal of bravery to stand up to our enemies, but just as much to stand up to our friends.”</span><span>by <small class="author">J.K. Rowling</small></span><div class="tags">Tags: <a class="tag">courage</a> <a class="tag">friends</a></div></div>

YOU ALSO HAVE TO HANDLE THE PAGINATION FOR WHICH THE OUTERHTML IS BELOW:

<a href="/js/page/3/">Next <span aria-hidden="true">→</span></a>

WRITE A PYTHON SCRIPT TO RUN ON GOOGLE COLAB WITH ALL THE LIBRARIES NEED TO BE INSTALLED

NOTE: USE PLAYWRIGHT ASYNC API AS WE ARE RUNNING THIS ON GOOGLE COLAB
