## Overview
**DataWhisk** is a sophisticated toolkit crafted to harness the power of web scraping and sentiment analysis to distill actionable insights from Google Reviews. This project integrates ![Playwright](https://cdn-icons-png.flaticon.com/512/5968/5968350.png "Playwright") for scraping and ![Python](https://cdn-icons-png.flaticon.com/512/1822/1822899.png "Python") for data analytics and visualization, employing libraries like Scikit-Learn, Transformers, Matplotlib, and WordCloud.

## Key Features
- **Automated Web Scraping**: Harnesses ![Playwright](https://cdn-icons-png.flaticon.com/512/5968/5968350.png "Playwright") to methodically gather reviews from Google.
- **Advanced Sentiment Analysis**: Utilizes transformer-based models to assess the emotional tone of reviews.
- **Aspect-Based Evaluation**: Organizes reviews into relevant categories such as food quality, service efficiency, ambiance, and price fairness.
- **Insightful Keyword Extraction**: Pinpoints prevalent terms in negative feedback to guide improvements.
- **Rich Data Visualization**: Creates engaging word clouds and summarizes aspect-based evaluations visually.

## Technology Stack
- **![Playwright](https://cdn-icons-png.flaticon.com/512/5968/5968350.png "Playwright") (Node.js)**: Automates web scraping tasks.
- **Python Libraries**:
  - ![Transformers](https://cdn-icons-png.flaticon.com/512/919/919853.png "Python") `transformers`: Employs BERT for nuanced sentiment analysis.
  - ![Scikit-Learn](https://cdn-icons-png.flaticon.com/512/337/337953.png "Python") `scikit-learn`: Facilitates keyword extraction and data processing.
  - ![Pandas](https://cdn-icons-png.flaticon.com/512/5968/5968322.png "Python") `pandas`: Manages and manipulates dataset.
  - ![Matplotlib](https://cdn-icons-png.flaticon.com/512/888/888954.png "Python") `matplotlib` & ![WordCloud](https://cdn-icons-png.flaticon.com/512/888/888955.png "Python") `wordcloud`: Enhances data presentation through visualizations.

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
pgsql
Copy

This markdown setup includes all necessary information, structured with appropriate visual cues to ensure both
