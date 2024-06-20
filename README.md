**Best Fares Scraper**
  Welcome to the Best Fares Scraper repository! This repository contains a Python script that retrieves flight information from the MakeMyTrip website. The script efficiently collects data on flight names, costs, layover details, and departure times, providing a comprehensive overview of available flights.

  The source code for the Best Fares Scraper can be found in the best_fa.py.

**Features**
1) Flight Data Scraper: The program scrapes flight information using Selenium and BeautifulSoup.
2) Interactive Input: Users can specify the departure city, arrival city, and travel date.
3) Data Export: The scraped data is saved to a CSV file for easy reference and analysis.

**How to Use:**

Set Up the Environment:

Ensure you have Python 3.x, Selenium, BeautifulSoup, and Chrome WebDriver installed.
Install the required Python packages using:
sh
Copy code
**pip install selenium beautifulsoup4**
Run the Python Script:

Execute the script using Python:
sh
Copy code
**python best_fares_scraper.py**
Input Flight Details:

Define the departure city, arrival city, and travel date in the script:
python
Copy code
origin = "BOM"   # Departure city code (e.g., BOM for Mumbai)
destin = "DEL"   # Arrival city code (e.g., DEL for Delhi)
trDate = "28/06/2023"  # Travel date in DD/MM/YYYY format
View the Results:

The program will scrape the flight information and save it to a CSV file named FlightsData_<origin>-<destin>-<dd>-<mm>-<yyyy>.csv.
Feel free to explore the code and customize the scraper as needed. Enjoy retrieving the best fares for your flights!
