# LLMWebScraper

## Overview
LLMWebScraper is a Python-based web scraping tool designed to extract and process data from websites. It utilizes Selenium WebDriver for dynamic content handling and integrates AI capabilities for advanced data parsing.

## Features
- **Dynamic Content Scraping:** Powered by Selenium and ChromeDriver.
- **Data Parsing:** Efficiently processes extracted data using `parse.py`.
- **Modular Design:** Clear separation of responsibilities across scripts.
- **AI Integration:** Advanced processing capabilities within the `ai` module.

## Prerequisites
- **Python 3.8+**
- **Google Chrome** (Ensure compatibility with the provided `chromedriver` version.)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/asingh2kk/LLMWebScraper.git
   cd LLMWebScraper
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Run the Main Script:**
   ```bash
   python main.py
   ```

2. **Custom Parsing:**
   Use `parse.py` to process scraped data:
   ```bash
   python parse.py
   ```

3. **Scraping Tasks:**
   Execute `scrape.py` for standalone scraping:
   ```bash
   python scrape.py
   ```

## Files and Directories
- **`main.py`:** Entry point of the application.
- **`scrape.py`:** Handles data scraping logic.
- **`parse.py`:** Responsible for parsing and transforming scraped data.
- **`requirements.txt`:** Lists the required Python packages.
- **`chromedriver`:** Required for Selenium WebDriver functionality.
- **`ai/`:** Directory for AI-related modules and resources.
