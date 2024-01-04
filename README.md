# HeelLife Webscraping

## Overview
This project involves a script written in R for scraping contact information from a website associated with the University of North Carolina. The script is designed to automate the process of gathering organizational information, positions, names, and email addresses.

## Features
- **Automated Web Scraping**: Efficiently collects detailed contact information from web pages.
- **Data Filtering**: Includes logic to ensure data accuracy and relevance (e.g., correct order of email attributes).
- **R Integration**: Utilizes various R packages like `dplyr`, `rvest`, `RSelenium`, and `purrr` for data manipulation and web scraping.

## Prerequisites
When running, the script will check if you have the following R packages installed and install them if needed:
- dplyr
- tidyverse
- rvest
- RSelenium
- wdman
- netstat
- xml2
- webdriver
- purrr

## Usage
1. **Initial Setup**: Fill in your ONYEN and password in the script to access HeelLife. (Don't share this with anyone outside of your own local desktop)
2. **Running the Script**: Execute the script. It will navigate to the website, log in, and start scraping data automatically.
3. **Output**: The script will save the scraped data as a CSV file named 'UNC Contacts List.csv' in the same directory as the R file is stored on your computer.

## Important Notes
- The script uses RSelenium to interact with web pages, so ensure you have a compatible web driver and browser. I'd recommend installing [Firefox](https://www.mozilla.org/en-US/firefox/new/) since it seems to work best with the package.
- Ensure you have permission to access and scrape the data such as a current ONYEN login.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
Special thanks to all contributors and maintainers of the R packages used in this project.
