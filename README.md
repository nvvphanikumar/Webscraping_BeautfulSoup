# Webscraping_BeautfulSoup
Performed web scraping on a website "https://subslikescript.com/" which contains transcripts of various movies. 
Beautiful Soup is a Python package for parsing HTML and XML documents. It creates a parsed tree for parsed pages that can be used to extract data from HTML.
Extracted data from a website https://subslikescript.com/ which contains transcripts of movies using standard HTML tags for title, paragraph, and section in a HTML document. Opened a text file to write contents to it.
Extracted data of multiple hyperlinks in a single page using find_all function and appropriate HTML tag into a list. Iterate over that list to get transcripts of that movies and stored them in individual text files by performing write operation.
Extracted data from multiple pages using pagination class. Got the number of pages into a list and iterate over the same to generate file consisting of transcripts of various movies.
