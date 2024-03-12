# Build-a-Web-Scraper-using-BeautifulSoup
I will be creating a CLI application that will extract player and team data statistics from the official website of the Indian Premier League. The app will be able to extract about 30 different statistics for the year 2008 to the latest edition.

I’ll be using Beautiful Soup for the job. It is a Python library used to extract data out of HTML and XML files. It works with a parser to provide idiomatic ways of navigating, searching and modifying the parse tree.

Next, I will be using Requests. Request will help us in downloading the HTML content from the IPL official website.

Since we are creating a CLI app we will not be providing the user with GUI but will provide a CLI interface using PyInquirer. It is a collection of common interactive command-line user interfaces.

We will also be using re: to use regular expressions, os: to handle directory address, signal: to handle keyboard interrupt, sys: again to handle keyboard interrupt and exit the application gracefully. The last in the list is, of course, pandas and numpy: for data manipulation.
