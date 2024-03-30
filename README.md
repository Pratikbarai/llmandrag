# llmandrag
UPSC Current Affairs Interpreter

This project is a Flask application that fetches and interprets news articles. It uses the Google Custom Search Engine (CSE) to fetch news articles for a given date, and the RAG model from Hugging Face's Transformers library to interpret the articles in a historical context. The application also includes a Discord bot that can fetch and interpret news articles on command.


Features
PDF Processor: Extracts text from PDF files and interprets events mentioned within.
News Interpreter: Fetches news articles from Google Custom Search Engine and interprets them with historical context.
Discord Bot: Provides daily news updates and historical context directly on Discord.

## Installation

1. Clone the repository:
 git clone https://github.com/Pratikbarai/llmandrag.git

2. Navigate to the project directory:
 cd llmandrag

3. Install the dependencies:
 pip install -r requirements.txt

4. Create a `.env` file in the project directory and add your environment variables:
 BOT_TOKEN=your_discord_bot_token
 GOOGLE_API_KEY=your_google_api_key 
 GOOGLE_CX=your_google_cx
 
5. Run the application:
  python3 discord.py
 
## Dependencies

- Flask
- requests
- PyPDF2
- newspaperk
- nextcord
- python-dotenv
- transformers
- threading

## License

This project is licensed under the terms of the MIT license.
