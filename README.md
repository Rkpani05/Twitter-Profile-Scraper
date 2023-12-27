# Twitter Profile Scraper

## Overview
This Python script is designed for scraping Twitter profiles. It extracts comprehensive information from given Twitter accounts and saves this data into structured Excel files.

## Prerequisites
- **Python 3.x**: Ensure Python is installed on your system.
- **Google Chrome Browser**: Required for Selenium WebDriver.

## Installation
1. **Clone/Download the Repository**: Obtain the script files onto your local machine.
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
This will install all necessary Python libraries like selenium, pandas, and webdriver_manager.

## Usage
Follow these instructions to run the script:

### Execute the Script
Open your terminal or IDE and run the script.

### Input Usernames
- Enter the number of Twitter profiles you wish to scrape.
- Input the usernames of these profiles.

### Login to Twitter
- A browser window will open for Twitter login.
- Manually log in within the provided 25-second window.

### Data Scraping
- The script will scrape data from each profile.
- Wait for the process to complete.

### Review Output
- Check the script's directory for two Excel files:
  - `twitter_data.xlsx`
  - `twitter_hashtags.xlsx`

## Output File Details
The script generates the following Excel files with specified columns:

### `twitter_data.xlsx`:
- **Name**: The full name of the Twitter profile.
- **Bio**: The bio description.
- **Location**: The location provided by the user.
- **Website**: The user's website URL.
- **Joined on**: The date when the user joined Twitter.
- **Following**: Number of accounts the user is following.
- **Followers**: Number of followers of the user.
- **Tweets**: Recent tweets from the profile.

### `twitter_hashtags.xlsx`:
- This file contains hashtags extracted from the user's recent tweets.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your enhancements.

## Acknowledgements
Thanks to Selenium WebDriver for enabling automated web interactions in this script.
