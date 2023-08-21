 # WebScraping with Python

![image](https://github.com/Sathiadak/Web_Scraping/assets/141050291/2ad855b8-07dd-4ecb-a409-4a2ada2649ea)
![image](https://github.com/Sathiadak/Web_Scraping/assets/141050291/9fecc54d-f75a-4cb2-b2dd-4c02a3706391)

**INTRODUCTION**

The Huber Timing provides race timing service across Pacific Northwest.They are known for different services such as Chip Timing, Results Production, Results Kiosks, Results Kiosks Receipt Printers, Finish Line Video Integrated with Results,Live Video Feed of Finish Line, Inflatable Arch, Day of Race Registration Kiosks, XC Scoring and USATF Course Measurement. Please note the data is based on their '5k run' event publish on their website. 

**Objective**

To analyse '5k run' event data using web scrapping.

**Table of Content**

1. Import libraries
2. Connect the page using url
3. Check the title of the page
4. Check the web links given on the page
5. Check the Header of the table row
6. Check all rows of table
7. Add column nameS and check the dataframe
8. shape of the dataframe
9. Tail of the dataframe
10. Bar Graph
11. Scatter plot



_**Import libraries**_

We have imported 8 libraries. The following are the libraries:
a. import pandas as pd
b. import numpy as np
c. import matplotlib.pyplot as plt
d. from urllib.request import urlopen
e. import requests
f. from bs4 import BeautifulSoup
g. import nltk.data
h. from requests_html import HTMLSession


   _**Connect the page using url**_

To connect the url, you have to paste the link and follow the given steps from given assignment4_WebScraping.


  _Check the title of the page_

Use title = Soup.title to see the Title of the page


 _Check the web links given on the page_
  
