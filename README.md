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

 # Installation Instructions

## Cloning the Repository
To get started, clone the repository to your local system with the commands:
```bash
git clone https://github.com/Mahmoud-Berkoti/datawhisk.git

cd datawhisk

# Installing Dependencies

## For Node.js (Playwright)
To install the necessary Node.js dependencies for web scraping with Playwright, run the following command:
```bash
npm install playwright
