# Trading Recommendation Bot for the Cement Sector

## Overview
This project involves building a Trading Recommendation Bot specifically designed for the cement sector. The bot leverages a Retrieval-Augmented Generation (RAG)-based approach to analyze market trends, company performance, and industry-specific events, ultimately providing actionable trading recommendations.

### Key Features:
- **Data Sources**: The bot utilizes financial news articles, cement sector annual reports, and tagged features to generate insights.
- **Relevance Scoring**: Features tagged in the news articles are scored based on their relevance to the cement sector.
- **Trading Recommendations**: The bot generates buy, hold, or sell recommendations based on aggregated feature scores.
- **Multi-Agent System**: The bot employs agents to calculate relevance scores and aggregate them into overall event scores.

## Project Structure:
- **Day1**: Feature extraction using prompt engineering.
- **Day2**: Setup of the Retrieval-Augmented Generation (RAG) system.
- **Day3**: Feature tagging and news filtering pipeline.
- **Day4**: Multi-agent system for relevance scoring and event aggregation.
- **Day5**: Building a trading recommendation bot based on the processed data.

## Technologies Used:
- Python
- Natural Language Processing (NLP)
- RAG-based Retrieval-Augmented Generation
- Pandas (for data manipulation)
- Jupyter Notebooks

## Installation:
Clone the repository and install the necessary dependencies:
```bash
git clone https://github.com/your-username/Trading-Recommendation-Bot-for-Cement-Sector.git
cd Trading-Recommendation-Bot-for-Cement-Sector
pip install -r requirements.txt
