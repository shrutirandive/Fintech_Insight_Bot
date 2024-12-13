# Fintech_Insight_Bot📊

Fintech Insight Bot is a comprehensive application that combines the power of Natural Language Processing (NLP) and financial data analysis to provide real-time insights and summarizations. The bot utilizes the OpenAI GPT models, Pinecone for vector storage, and Streamlit for a user-friendly interface, offering functionalities such as article summarization, stock price analysis, and an intelligent Q&A system based on financial articles.

## Features

1. Insight Bot:
  - Processes and indexes financial articles using Pinecone.
  - Enables users to ask questions about processed articles.
  - Retrieves relevant information using embeddings and GPT models.

2. Real-Time Stock Prices:
  - Fetches stock prices using ```yfinance```.
  - Displays market information such as Market Cap, P/E ratio, and sector.
  - Provides related news for selected stocks.

3. News Article Summarizer:
  - Extracts and summarizes news articles from provided URLs.
  - Displays article keywords and summary using NLP techniques.

## Tech Stack

- Programming Language: Python
- Libraries:
  - LangChain for LLM chaining
  - OpenAI for GPT-based models
  - Pinecone for vector storage
  - Streamlit for the UI
  - ```yfinance``` for stock data
  - ```newspaper3k``` for news article processing
  - ```feedparser``` for RSS feeds
  - ```matplotlib``` for data visualization
  - ```nltk``` for sentiment analysis
- Environment: Streamlit web app
- Database: Pinecone

## Prerequisites

1. Python Environment: Ensure you have Python 3.8 or higher installed.
2. API Keys: Obtain the following API keys and set them in your environment variables:
    - OpenAI API Key
    - Pinecone API Key

3. Dependencies: Install required Python libraries using:
     ```pip install -r requirements.txt```

5. Environment Variables:
   - Create a .env file in the root directory with the following keys:
    ```
    OPENAI_API_KEY=your_openai_api_key
    PINECONE_API_KEY=your_pinecone_api_key
    
    ```

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/your_username/fintech-insight-bot.git
   cd fintech-insight-bot
   
   ```

3. Install the dependencies:
  ```pip install -r requirements.txt```

4. Run the Streamlit app:
  ```streamlit run app.py```

## Usage

### Insight Bot

1. Navigate to the Insight Bot section.
2. Enter the URLs of articles to process.
3. Click on Process URLs to index the articles.
4. Ask questions about the processed articles in the query box.

### Real-Time Stock Prices

1. Navigate to the Real-Time Stock Prices section.
2. Enter the stock symbol (e.g., AAPL, TSLA).
3. View the stock price, market cap, P/E ratio, sector, and related news.

### News Article Summarizer

1. Navigate to the News Article Summarizer section.
2. Enter a URL for a news article.
3. View the extracted title, summary, and keywords of the article.

## File Structure
```
fintech-insight-bot/
├── app.py                # Main Streamlit application file
├── requirements.txt      # List of required Python packages
├── .env                  # Environment variables
├── config.toml           # Streamlit configuration
├── README.md             # Project documentation
```
## Future Improvements

1. Add support for more financial data APIs.
2. Optimize Pinecone indexing for faster retrieval.
3. Enhance the user interface for better usability.
4. Integrate sentiment analysis for financial news.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [OpenAI](https://openai.com/) for GPT models
- [Pinecone](https://www.pinecone.io/) for vector storage
- [Streamlit](https://streamlit.io/) for building the app

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact

For any inquiries, reach out at [Email](sameernimse99@gmail.com) or connect via [LinkedIn](https://www.linkedin.com/in/sameer522/).

