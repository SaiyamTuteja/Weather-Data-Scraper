
# Weather Data Scraper

## Description

This Python script fetches daily weather data from a website and stores it in an Excel file. It is designed to run on a daily basis to keep track of temperature data.

## Features

- Retrieves temperature data from a specified website.
- Appends the data to an Excel file, creating the file if it doesn't exist.
- Handles website fetching errors and missing data gracefully.
- Provides clear instructions for use.

## Usage

1. **Install Dependencies:**
   ```bash
   pip install requests beautifulsoup4 openpyxl
   ```

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/SaiyamTuteja/weather-data-scraper.git
   ```

3. **Navigate to the Project Directory:**
   ```bash
   cd weather-data-scraper
   ```

4. **Run the Script:**
   ```bash
   python weather_script.py
   ```

5. **Configure the Script:**
   - Replace the `url` variable with the actual URL of the website providing weather data.
   - Adjust the HTML parsing part in the `get_weather_data` function based on the structure of the webpage.

6. **Schedule Daily Execution (Optional):**
   - To automate daily execution, use a task scheduler (e.g., Task Scheduler on Windows, cron on Unix-based systems) to run the script at a specific time each day.

## Folder Structure

- `weather_script.py`: The main Python script.
- `weather_data.xlsx`: Excel file for storing weather data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Requests Library](https://docs.python-requests.org/en/latest/)
- [Beautiful Soup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [OpenPyXL Documentation](https://openpyxl.readthedocs.io/en/stable/)

Feel free to contribute, report issues, or provide feedback.

Happy coding!
```
