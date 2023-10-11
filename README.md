```markdown
# WhatsApp-Chat-Analyser

## Overview

The WhatsApp Chat Analyzer is a tool designed to analyze and provide statistical insights into WhatsApp group or individual chats. By uploading the chat data, users can obtain valuable information such as total media sent, message count, word frequency, word cloud representation, emojis usage, and sentiment analysis.

## Features

- **Media Statistics:** Displays the total number of media files shared in the chat.
- **Message Count:** Provides the overall count of messages exchanged.
- **Word Analysis:** Analyzes the most frequently used words in the chat.
- **Word Cloud:** Generates a visually appealing word cloud representation based on the chat content.
- **Emojis Usage:** Highlights the emojis used and their frequency.
- **Sentiment Analysis:** Analyzes the sentiment of messages using the VADER sentiment analyzer.

## Usage

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

### Running the Application

```bash
streamlit run app.py
```

Open your browser and navigate to [URL](https://whatsapp-chat-analyser-grml.onrender.com) to access the application.

### Uploading Chat Data

1. Click on the "Upload Chat" button.
2. Select the WhatsApp chat file (.txt) you want to analyze.

### Viewing Statistics

Explore the different tabs to view detailed statistics and visualizations.

## Tech Stack

- **Streamlit:** Used for building the web application interface.
- **Python:** The primary programming language for developing the analyzer.
- **Pandas, WordCloud:** Libraries for data manipulation and word cloud generation.
- **VADER Sentiment Analyzer:** Utilized for sentiment analysis.

## Contributors

- [Sheefa Naaz](https://github.com/sheefanaaz123)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
