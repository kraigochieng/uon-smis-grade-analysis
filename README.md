# UoN SMIS Grade Analysis

The project aim is to analyze and visualize my grades hosted in the UoN website. 

# Tools used
1. [Requests](https://pypi.org/project/requests/) for **HTTP queries**
2. [BeautifulSoup](https://pypi.org/project/beautifulsoup4/) for **web scraping**
3. [Pandas](https://pandas.pydata.org/) for **data manipulation**
4. [Matplotlib](https://matplotlib.org/) for **data visualization**

# Steps to take before running the project
1. Fill in registration details and password in `.env_template`
2. Rename the file `.env_template` to `.env`


## Problems occured in the project
- Prone to man in the middle attacks, since SSL verification is disabled. The reason SSL verification is disabled is because it is not working.