Xin Ping is lazy to read the news online so she created an agent to help her collate all the news report to summarise all the things happening.
# News Summarizer

A simple web app that fetches news and generates AI-powered summaries. Works on mobile and desktop.

## Project Structure

```
news-summarizer/
├── backend/              # Python Flask API
│   ├── app.py           # Main Flask application
│   ├── news_fetcher.py  # Fetches news from NewsAPI
│   ├── summarizer.py    # AI summarization with Ollama
│   ├── requirements.txt # Python dependencies
│   └── .env.example     # Environment variables template
│
├── frontend/            # Web interface
│   ├── index.html      # Main webpage (mobile responsive)
│   ├── styles.css      # Styling
│   └── app.js          # Frontend JavaScript
│
└── README.md           # You are here!
```
