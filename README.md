# DataWhisk Overview

DataWhisk is an innovative platform designed to automate the extraction and analysis of Google reviews. Utilizing Playwright for web scraping and Python for data analysis and visualization, it harnesses transformer models for sentiment analysis to derive valuable insights from customer feedback.

## Key Features

- **Automated Web Scraping:** Leverages Playwright to efficiently scrape reviews directly from Google.
- **Sentiment Analysis:** Utilizes transformer-based models to analyze the sentiment of each review.
- **Aspect-Based Insights:** Classifies reviews into categories such as food, service, atmosphere, and pricing for detailed analysis.
- **Keyword Extraction:** Identifies key terms in negative reviews to highlight areas for improvement.
- **Data Visualization:** Produces compelling visual representations like word clouds and aspect rating aggregations to depict data insights.

## Technologies Used

- **Playwright (Node.js):** For automated web scraping tasks.
- **Python Libraries:**
  
  - **Transformers:** For BERT-based sentiment analysis.
  - **Scikit-Learn:** For efficient keyword extraction.
  - **Pandas:** For advanced data manipulation.
  - **Matplotlib & WordCloud:** For creating impactful data visualizations.
  - 
## Installation
1. **Clone the repository**
   ```
   git clone https://github.com/Mahmoud-Berkoti/datawhisk.git
   
   cd datawhisk
   ```

2. **Install dependencies**
   - **For Node.js (Playwright)**:
     ```
     npm install playwright
     ```
   - **For Python (Data Analysis & Sentiment)**:
     ```
     pip install transformers torch pandas scikit-learn matplotlib wordcloud
     ```

## Usage

### 1. Scrape Reviews
Run the Playwright script to extract Google Reviews:
```
node scrape.js
```
This will save reviews in the `googreviews` folder as JSON files.

### 2. Analyze Reviews
Run the Python script to process and analyze the reviews:
```
python bert.py
```
This will generate:
- **Sentiment-based aspect ratings**
- **Word cloud visualization**
- **Improvement suggestions based on negative reviews**

## Output Files
- `reviews_with_aspects.json`: Reviews with sentiment-based aspect ratings.
- `aspect_rating_summary.json`: Average ratings for each aspect.
- `improvement_suggestions.json`: Keywords and improvement insights.
