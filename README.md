## Overview
**DataWhisk** is a sophisticated toolkit crafted to harness the power of web scraping and sentiment analysis to distill actionable insights from Google Reviews. This project integrates [<img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Playwright" width="20" height="20">](https://playwright.dev/) for scraping and [<img src="https://cdn-icons-png.flaticon.com/512/1822/1822899.png" alt="Python" width="20" height="20">](https://www.python.org/) for data analytics and visualization, employing libraries like Scikit-Learn, Transformers, Matplotlib, and WordCloud.

## Key Features
- **Automated Web Scraping**: Harnesses [<img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Playwright" width="20" height="20">](https://playwright.dev/) to methodically gather reviews from Google.
- **Advanced Sentiment Analysis**: Utilizes transformer-based models to assess the emotional tone of reviews.
- **Aspect-Based Evaluation**: Organizes reviews into relevant categories such as food quality, service efficiency, ambiance, and price fairness.
- **Insightful Keyword Extraction**: Pinpoints prevalent terms in negative feedback to guide improvements.
- **Rich Data Visualization**: Creates engaging word clouds and summarizes aspect-based evaluations visually.

## Technology Stack
- **[<img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Playwright" width="20" height="20">](https://playwright.dev/) (Node.js)**: Automates web scraping tasks.
- **Python Libraries**:
  - [<img src="https://cdn-icons-png.flaticon.com/512/919/919853.png" alt="Python" width="20" height="20">](https://huggingface.co/docs/transformers/index) `transformers`: Employs BERT for nuanced sentiment analysis.
  - [<img src="https://cdn-icons-png.flaticon.com/512/337/337953.png" alt="Python" width="20" height="20">](https://scikit-learn.org/) `scikit-learn`: Facilitates keyword extraction and data processing.
  - [<img src="https://cdn-icons-png.flaticon.com/512/5968/5968322.png" alt="Python" width="20" height="20">](https://pandas.pydata.org/) `pandas`: Manages and manipulates dataset.
  - [<img src="https://cdn-icons-png.flaticon.com/512/888/888954.png" alt="Python" width="20" height="20">](https://matplotlib.org/) `matplotlib` & [<img src="https://cdn-icons-png.flaticon.com/512/888/888955.png" alt="Python" width="20" height="20">](https://www.python.org/) `wordcloud`: Enhances data presentation through visualizations.

## Installation Instructions
1. **Repository Cloning**
   ```bash
   git clone https://github.com/abaan-noman/datawhisk.git
   cd datawhisk
