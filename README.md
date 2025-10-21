# Functipn for Youtube Link 🎥

A Python script that fetches YouTube video links based on a search query using the **YouTube Data API v3**. The tool returns video titles and URLs for easy access.

---

## Features

- Search YouTube for videos using any query.
- Fetches up to **20 videos** by default (configurable).
- Returns **video titles** and **direct YouTube links**.
- Uses environment variables for secure API key management.

---

## Requirements

- Python 3.x
- Libraries:
  - `google-api-python-client`
  - `python-dotenv`

Install dependencies using pip:
```bash
pip install google-api-python-client python-dotenv
