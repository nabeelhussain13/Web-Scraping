
# Web Scraping Project: E-Book Store Data

## Project Overview
This project involves web scraping data from an online e-book store to extract useful information such as book titles, prices, stock availability, and product links. The scraped data is stored in a structured format using **pandas** and can be used for further data analysis.

## Objective
The objective of this project is to collect the following information from the e-book store:
- **Book Titles**
- **Prices**
- **Stock Availability**
- **Product Links**

The final dataset contains 1,000 rows and 4 columns.

## Tools & Libraries Used
- **BeautifulSoup**: For parsing HTML content and extracting data.
- **requests**: For sending HTTP requests to retrieve web pages.
- **pandas**: For storing and managing the scraped data.

## Project Workflow
1. **Web Scraping**: The script navigates through 50 pages of the e-book store and collects the required information by parsing the HTML content using BeautifulSoup.
2. **Data Cleaning**: Prices are cleaned to remove unwanted characters and extra spaces.
3. **Data Storage**: The collected data is stored in a pandas dataframe, which is then exported to a CSV file.

## Final Output
The final dataset includes the following columns:
- Book Titles
- Prices
- Stock Availability
- Product Links

This dataset contains 1,000 entries.

## Conclusion
This project showcases the power of web scraping in gathering useful data from the web. It demonstrates how to collect, clean, and organize data in a meaningful way for further analysis or applications.

## License
This project is licensed under the MIT License.
