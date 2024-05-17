# Senior Living Projects Web Scraper (Jupyter Notebook)

This project is a Jupyter Notebook containing Python code designed to gather and analyze data from senior living operators and community websites using web scraping techniques. The primary objective is to extract information about various senior living projects across India, including project names, addresses, price ranges, amenities, and project details URLs.

## Features

- Scrapes data from the website "https://www.ashianahousing.com/senior-living-india"
- Utilizes Selenium for web browser automation to handle dynamic content
- Employs BeautifulSoup for efficient HTML/XML parsing
- Performs data cleaning and formatting using the pandas library
- Exports scraped data to a CSV file named "senior_living_projects.csv"
- Implements robust error handling and exception management
- Follows a modular design with separate functions for different tasks

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (specified in the notebook's import statements)

## Installation

1. Clone the repository:
   ```bash
   https://github.com/N-epiphany/Senior-Living-Projects-Web-Scraper
   ```
2. Navigate to the project directory:
   ```bash
   cd senior-living-scraper
   ```
3. Install the required Python libraries (if not already installed):
   ```bash
    pip install requests beautifulsoup4 pandas selenium webdriver-manager
   ```
  
## Usage

1. Open the Jupyter Notebook file (`senior_living_scraper.ipynb`) in your Jupyter Notebook environment.

2. Follow the instructions in the notebook and run the code cells sequentially.

3. The scraper will navigate to the specified website, extract the relevant data, and save it to the `senior_living_projects.csv` file in the project directory.

## Project Structure

- `senior_living_scraper.ipynb`: Jupyter Notebook containing the web scraping code
- `senior_living_projects.csv`: Output file containing the scraped data (generated after running the notebook)
- `README.md`: This file, providing project documentation

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/): HTML/XML parsing library
- [Selenium](https://www.selenium.dev/): Web browser automation tool
- [Pandas](https://pandas.pydata.org/): Data manipulation and analysis library
- [webdriver_manager](https://github.com/SergeyPizhanski/webdriver_manager): Automated management of browser drivers

