
# Tata Cars Web Scraper

This project is a web scraper that extracts details of Tata cars listed on the Cars24 website for the Mumbai location.

## Project Description

The script uses Selenium to navigate to the Cars24 website, applies filters to search for Tata cars in Mumbai, and extracts relevant details using BeautifulSoup. The extracted data is saved into a CSV file.

## Features

- Extracts car name, kilometers driven, fuel type, transmission type, price, and EMI.
- Saves the data to a CSV file.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/vaibhavi1224/car-details-scraper.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd car-details-scraper
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Download and install ChromeDriver:**

   - Visit the [ChromeDriver download page](https://sites.google.com/chromium.org/driver/downloads).
   - Download the version that matches your Chrome browser.
   - Place the `chromedriver` executable in your PATH or specify its location in the script.
 data and generate visualizations.

## Requirements

- Python 3.x
- Selenium
- BeautifulSoup4
- pandas
- time

## Usage

 **Run the scraper script:**

   ```bash
   python scrape_cars24.py
   ```

   This script will scrape car details from Cars24.com and save the data to a CSV file.

## Project Structure

- `scrape_tata_mumbai_cars24.py`: Contains the code for web scraping car details.
- `requirements.txt`: Lists the required Python packages.
- `tata_data/`: Directory where the scraped data CSV file is stored.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
