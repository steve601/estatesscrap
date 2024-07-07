## REAL ESTATES KENYA WEB SCRAPING PROJECT

### Overview
This project involves web scraping to extract valuable data from a real estate in kenya website for further analysis. The scraper navigates multiple pages, collects specific elements, and compiles the data into a structured format. This project is built using Python with Selenium and BeautifulSoup libraries.

### Features
**Automated navigation through multiple web pages**
**Data extraction using BeautifulSoup**
**Handling dynamic content with Selenium**
**Storing extracted data in a pandas DataFrame**
**Flexible configuration for different websites**
### Installation
**Clone the repository:**

git clone https://github.com/yourusername/estatesscrap.git
cd web-scraping-project
**Create and activate a virtual environment (optional but recommended):**

python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
**Install the required dependencies:**

pip install -r requirements.txt
**Usage**
Configure the scraper:
Edit the config.ipynb file to match the structure of the target website.

*Output file name and path*
Data Extraction
The scraper collects the following data from each page:

House names
Locations
Image URLs
Prices
*The data is stored in a pandas DataFrame and exported to a CSV file.*

### Dependencies
Python 3.x
Selenium
BeautifulSoup4
pandas
numpy


