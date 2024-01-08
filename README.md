# web-scrapping
## This Python project is on a web scraping task focused on extracting chess player ratings and related information from the chess.com website. Here's a breakdown of the project:

### Libraries Import: 
**The necessary libraries such as requests, BeautifulSoup, pandas, and numpy are imported.**

### Web Scraping: 
**The code starts by making a request to the chess.com ratings page and then uses BeautifulSoup to parse the HTML content.**

### Data Extraction: 
**It extracts specific information about a single player like name, title, classical points, and so on, using the BeautifulSoup's find and find_all methods.**

### Loop for Multiple Pages: 
**It sets up a loop to iterate through multiple pages of player rankings (50 pages in total) by changing the URL with the page number. Then, it extracts information for each player on every page and stores it in separate lists for rank, name, classical, rapid, and blitz ratings.**

### Data Validation and Storage: 
**It performs a data validation by ensuring the lengths of the lists match the expected count (2499 players) and then creates a Pandas DataFrame from these lists.**

### Data Export: 
**Finally, it saves the extracted data into CSV and Excel formats using Pandas' to_csv and to_excel functions.**

This project essentially collects and structures chess player data from multiple pages on chess.com and stores it in a convenient tabular format for further analysis or reference.
