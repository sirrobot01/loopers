### Loopers


**Loopers** is a tiny script used in scrapping emails out of a web page.

***

#### **Functions**
- Scraps emails from web page
- Allow checking first level subdirectories of a page


***

#### **Requirements**
- Python 3.x or 2.x
- Working internet
- Requests
- BeautifulSoup
***

#### **Installation**

- Install loopers by entering this command in your terminal 

> pip install loopers


#### Argument(s)

Pass string(s) of links you want to scrap. 

***

#### Usage

- Import looper to your codes. 

> from loopers import loop
> data = loop("https://nairaland.com", "https://twitter.com", "https://linkedin.com")

The functions returns a dictionary with the url(s) as key(s) which are also 
dictionaries with the following keys

emails: List of emails found in the page
n_links: Number of links in the scrapped page
links: Links generated from the page
***

##### Endnote
If at all there is an issue raised during execution of the command, kindly raise an issue here or better still **mail me at akeremukhtar10@gmail.com**.
Thanks for your time. 


 