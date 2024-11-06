# Market-Pulse-AI
Market-Pulse-AI is a notebook application designed to simplify stock research by combining historical price data and recent news analysis for selected companies. The application gathers real-time financial data from Tiingo and relevant, stock-specific news from Finnhub, then leverages a large language model (LLM) from OpenAI to generate concise summaries and sentiment analysis. This tool provides users with a streamlined approach to assessing a company's market performance and outlook.

## Key Problem
Researching a stock's historical performance and gathering up-to-date news to form an opinion on its outlook can be a time-consuming process. Typically, it requires:
- Looking up the stock symbol’s historical closing prices from multiple financial data sources.
- Searching for recent news articles or press releases about the company.
- Analyzing this data to assess market sentiment and potential trends.

## Solution
Market-Pulse-AI addresses these challenges by automating the data gathering, processing, and analysis steps:
- Historical Price Data: Retrieves historical stock prices through the Tiingo API, allowing for easy access to performance trends.
- Relevant News: Fetches company-specific news articles using the Finnhub API.
- Data Processing: Preprocesses the historical and news data to prepare it for analysis.
- Summary and Sentiment Analysis: Submits the processed data to an LLM (via the OpenAI API) to generate a concise summary and sentiment analysis of the company’s recent performance and outlook.
