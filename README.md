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
7. Add column names and check the dataframe
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

To connect the url, you have to paste the link and follow the given steps from on assignment4_WebScraping.


  **_Check the title of the page_**

Use title = Soup.title to see the Title of the page


 **_Check the web links given on the page_**
  
Create the for loop to get href and follow the given steps from on assignment4_WebScraping.


 _**Check the Header of the table row**_

 By using allrows, you can select rows based on the scripted HTML

 
 _**Check all rows of table**_

Create Forloop for rows and cells using table row(tr) and data cell(td)


 _**Add column nameS and check the dataframe**_

Here column name was not alligned, so, I decided to add column name again using Cols function.


 _**shape of the dataframe**_

It is used to check number of rows and columns of extracted dataframe


 _**Tail of the dataframe**_

Further, I have considered last 20 data from the dataframe to visualize. We can do it same for head of the dataframe too.


 _**Bar Graph**_

The objective was to understand how Gender of last 20 runner has performed in different Cities
You have to assign variable name to X axis and y axis for Bar Graph using 'plt.bar'. 
Here gender is my 'x axis' and City is my 'y axis'. I have also named the title using 'plt.title'.

 
 _**Scatter plot**_

The objective was to understand ages spread of last 20 runner across different cities
You can create scatter plot using 'plt.scatter'. To create this, assign variable name to X axis and y axis. 
Here City is my 'x axis' and Age is my 'y axis'. I have also named the title using 'plt.title'.


 _ **TOOL**  _    
 
1. Python (Version: 3.11)   
2. Git (Version: 2.23.0)


 _ **CONTRIBUTER**_  
  
Sathi Adak


 _  **ACKNOWLEDGMENTS**  _     

I would like to thank who helped me to accomplish this project.       
_Will:_ an instructor of the course, who provided his valuable guidance, mentorship, and expertise throughout the project.           
_Cantek IT Program:_ Cantek IT Program, an educational institution, played a significant role in supporting the project. They provided resources, facilities, and a conducive learning environment for the team to work on the project.        


