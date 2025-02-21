## Overview
**DataWhisk** is a sophisticated toolkit crafted to harness the power of web scraping and sentiment analysis to distill actionable insights from Google Reviews. This project integrates <img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Playwright" width="20" height="20"> for scraping and <img src="https://cdn-icons-png.flaticon.com/512/1822/1822899.png" alt="Python" width="20" height="20"> for data analytics and visualization, employing libraries like Scikit-Learn, Transformers, Matplotlib, and WordCloud.

## Key Features
- **Automated Web Scraping**: Harnesses <img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Playwright" width="20" height="20"> to methodically gather reviews from Google.
- **Advanced Sentiment Analysis**: Utilizes transformer-based models to assess the emotional tone of reviews.
- **Aspect-Based Evaluation**: Organizes reviews into relevant categories such as food quality, service efficiency, ambiance, and price fairness.
- **Insightful Keyword Extraction**: Pinpoints prevalent terms in negative feedback to guide improvements.
- **Rich Data Visualization**: Creates engaging word clouds and summarizes aspect-based evaluations visually.

## Technology Stack
- **<img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Playwright" width="20" height="20"> (Node.js)**: Automates web scraping tasks.
- **Python Libraries**:
  - <img src="https://cdn-icons-png.flaticon.com/512/919/919853.png" alt="Python" width="20" height="20"> `transformers`: Employs BERT for nuanced sentiment analysis.
  - <img src="https://cdn-icons-png.flaticon.com/512/337/337953.png" alt="Python" width="20" height="20"> `scikit-learn`: Facilitates keyword extraction and data processing.
  - <img src="https://cdn-icons-png.flaticon.com/512/5968/5968322.png" alt="Python" width="20" height="20"> `pandas`: Manages and manipulates dataset.
  - <img src="https://cdn-icons-png.flaticon.com/512/888/888954.png" alt="Python" width="20" height="20"> `matplotlib` & <img src="https://cdn-icons-png.flaticon.com/512/888/888955.png" alt="Python" width="20" height="20"> `wordcloud`: Enhances data presentation through visualizations.

## Installation Instructions
1. **Repository Cloning**
   ```bash
   git clone https://github.com/abaan-noman/datawhisk.git
   cd datawhisk
Dependencies Installation
Node.js (Playwright):
bash
Copy
npm install playwright
Python (Analysis & Visualization):
bash
Copy
pip install transformers torch pandas scikit-learn matplotlib wordcloud
Usage Guidelines
Step 1: Extract Reviews
Execute the Playwright script to collect reviews from Google:

bash
Copy
node scrape.js
This script populates the googreviews directory with JSON files containing the reviews.

Step 2: Process and Analyze Reviews
Execute the Python script to analyze the collected reviews:

bash
Copy
python bert.py
Outputs include:

Aspect-based sentiment evaluations
Visual word clouds
Constructive suggestions derived from critical reviews
Output Files
reviews_with_aspects.json: Contains reviews categorized with sentiment-based aspect evaluations.
aspect_rating_summary.json: Summarizes average aspect ratings.
improvement_suggestions.json: Offers keywords and suggestions for service enhancement.
css
Copy

By using HTML tags, you can customize the size of each icon, making them unobtrusive yet visually effective. Adjust the width and height attributes to match your visual preference.
