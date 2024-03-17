# Image Scraper Web Application

This is a simple Flask web application for scraping images from Google search results based on user input and storing them in a MongoDB database.

# Usage:
1. Enter a search query in the input field on the homepage and click the "Search" button.
2. The application will scrape images related to the query from Google search results.
3. Scraped images will be stored in the images/ directory.
4. The image data will also be saved in a MongoDB database named image_scrap in a collection named image_scrap_data.

## Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.x
- Flask
- Flask-Cors
- Requests
- BeautifulSoup
- pymongo

You can install the dependencies using pip:

```bash
pip install flask flask-cors requests beautifulsoup4 pymongo
