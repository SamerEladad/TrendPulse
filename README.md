# TrendPulse

TrendPulse is an AI-powered chatbot designed to provide insights about current and upcoming product trends for dropshipping. Leveraging the power of web scraping and large language models (LLMs), TrendPulse helps users identify potential winning products to sell before they become saturated in the market.

## Table of Contents
- [TrendPulse](#trendpulse)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Folder Structure](#folder-structure)
  - [Installation](#installation)

## Project Overview
TrendPulse scrapes data from various e-commerce platforms, processes the data to identify trending products, and provides insights through a conversational AI chatbot. The chatbot is designed to interact with users, answer their queries about potential products to dropship, and provide recommendations based on market trends.

## Features
- **Web Scraping:** Automated data collection from e-commerce platforms like Amazon, eBay, and AliExpress.
- **Trend Analysis:** Analyzes the scraped data to identify trending products.
- **AI Chatbot:** Conversational AI that interacts with users and provides product recommendations.
- **User Interface:** A web-based interface for user interactions with the chatbot.

## Technologies Used
- **Programming Languages:** Python
- **Frameworks:** Flask (backend), BeautifulSoup/Scrapy (web scraping)
- **Libraries:** Hugging Face Transformers (LLM), SQLAlchemy (database), Bootstrap (front-end)
- **Database:** SQLite
- **Version Control:** Git, GitHub

## Folder Structure
- **data/**: Contains all the data files.
  - **archive/**: For archived or old data files.
  - **clean/**: For cleaned data files.
  - **raw/**: For raw data files directly from scraping.
- **images/**: Store images, such as screenshots, used in the project or README.
- **notebooks/**: Jupyter notebooks for exploration, analysis, and prototyping.
- **src/**: Source code for the project.
  - **app.py**: Main Flask application file.
  - **chatbot.py**: Logic for the chatbot.
  - **data_processing.py**: Data processing scripts.
  - **models/**: Directory for model-related scripts.
    - **model_utils.py**: Utility functions for models.
  - **scraping/**: Directory for web scraping scripts.
    - **scraper.py**: Web scraping logic.
  - **static/**: Static files for the web app (CSS, JavaScript).
  - **templates/**: HTML templates for the web app.
- **tests/**: Unit tests for the project.
  - **test_app.py**: Tests for the Flask app.
  - **test_scraper.py**: Tests for the scraper.
- **.gitignore**: Specifies which files and directories to ignore in version control.
- **README.md**: Project documentation.
- **requirements.txt**: List of Python dependencies.

## Installation
To set up TrendPulse on your local machine, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/SamerEladad/TrendPulse.git
   cd TrendPulse