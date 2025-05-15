# Sentiment Analysis on Web Reviews

This project scrapes reviews from a web page using BeautifulSoup, analyzes the sentiments using TextBlob, and visualizes them in a bar chart.

## Technologies Used

- Python 3.10+
- Requests
- BeautifulSoup
- TextBlob
- Matplotlib

## Installation

1. Clone the repository or download the files.
2. Create a virtual environment (optional but recommended):
    bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    
3. Install dependencies:
    bash
    pip install -r requirements.txt
    

## Usage

1. Replace the url in reviews_analysis.py with a real review page URL.
2. Update the soup.find_all(...) to match the review HTML structure.
3. Run the script:
    bash
    python3 reviews_analysis.py
    

##  Output

- Terminal shows sentiment counts and average values.
- A bar chart displays the distribution of Good, Better, and Bad reviews.

##  Notes

- The TextBlob sentiment polarity ranges from -1 (very negative) to +1 (very positive).
- You'll need to inspect the target review site to customize the HTML scraping logic.
