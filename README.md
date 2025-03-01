# Data-Mining-Project

## Project Overview

This project is a web scraper designed to extract recipe information from allrecipes.com and food.com. It gathers details about recipes, including their origin, ingredients, preparation steps, and user reviews. The data is processed and stored in a structured format for further analysis. We analyze how different or similar cultures are by looking at what ingredients they use and how they prepare their meals. We look an overview of how people enjoy certain foods, by analyzing the reviews using sentiment analysis. Finally, a recommendation system is built to facilitate new recipe ideas for a user based on his preferences.

## Features
- Extracts recipe details (title, origin, ingredients, directions)
- Scrapes user reviews for additional insights
- Handles JavaScript-rendered content using Playwright
- Filters non-recipe links to improve data accuracy
- Uses NLP (spaCy) for text processing

## Technologies Used
- Python
- BeautifulSoup - HTML parsing
- Requests - Handling HTTP requests
- Playwright - Handling dynamic web content
- spaCy - NLP processing
- Pandas - Data manipulation
