# google-news-summarizer



This is a Python script that scrapes the top 5 Google search results for a user-specified keyword, extracts article titles, links, descriptions, and summaries, performs sentiment analysis on the article descriptions, and generates a bar chart of the most common words in the article descriptions.

# Installation
Clone the repository: git clone https://github.com/adityapyy/google-news-summarizer.git
Install the required libraries: pip install -r requirements.txt
# Usage
Run the script: python google_news_summarizer.py
Enter a keyword to search for when prompted
Wait for the script to finish running
Check the news_articles.csv file for the extracted data and generated bar chart
# Customization
You can customize the number of top article links to scrape by changing the top_links variable in the script
You can experiment with different summarization algorithms by modifying the scrape_article function in the script
You can customize the number of common words to display in the bar chart by changing the head parameter in the value_counts() method in the script
# Contributing
Feel free to fork this repository and submit pull requests with any improvements or bug fixes.

# Credits
This script was created by [Aditya Chaudhary]
