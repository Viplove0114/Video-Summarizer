# Video Summarizer

One-stop solution to automatically summarize videos using AI.

## Overview

**Video Summarizer** is a Python-based application that extracts essential insights from video content. Powered by AI (e.g., Google Gemini, OpenAI’s GPT models), it transforms long videos into concise summaries—ideal for lectures, tutorials, or any video where time is of the essence.

---

## Features

- **Video Input:** Accepts local video files.
- **AI-Powered Analysis:** Uses Gemini 2.5 Flash for multimodal understanding.
- **Web Search Integration:** Gathers supplementary information using DuckDuckGo.
- **Interactive Q&A:** Ask any question about your uploaded video and get a detailed response.
- **Easy Setup:** Lightweight Python script with minimal dependencies.

---

## Project Structure

```text
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
└── .gitignore          # Ignored files for Git
```

---

## Getting Started

### Prerequisites

- Python 3.12
- [Streamlit](https://streamlit.io/)
- Google API Key for Gemini (set as `GOOGLE_API_KEY` in your `.env` file)

### Installation

```bash
git clone https://github.com/Viplove0114/Video-Summarizer.git
cd Video-Summarizer
pip install -r requirements.txt
```

### Configuration

1. Create a `.env` file in the root directory.
2. Add your API key:
    ```
    GOOGLE_API_KEY="your_google_api_key_here"
    ```
   *(You may also use `OPENAI_API_KEY` if using OpenAI models.)*

---

## Usage

1. Run the app:
    ```bash
    streamlit run app.py
    ```
2. Open the app in your browser (usually at [http://localhost:8501](http://localhost:8501)).
3. Upload a video file.
4. Enter your question or insight in the text area.
5. Click "Analyze Video" to receive AI-generated insights.

---

## 🚀 Future Improvements

- **Multi-Language Support:** Add transcription and summarization for different languages.
- **Topic Detection:** Automatically break the summary into sections/topics (e.g., chapters).
- **Extractive + Abstractive Summaries:** Allow users to choose between bullet-point extraction or natural language abstraction.
- **Keyword Highlighting:** Highlight key terms, timestamps, and important quotes from the video.
- **Interactive Summaries:** Provide clickable summaries linked to exact timestamps in the video.
- **Summarization Modes:** Options for *short summary*, *detailed summary*, or *Q&A style output*.
- **Batch Processing:** Summarize multiple videos at once.
- **Cloud Integration:** Store summaries on Google Drive, Notion, or export to PDF/Markdown automatically.
- **Mobile/Browser Extension:** Build a Chrome extension or Android/iOS app to summarize YouTube videos on the fly.
- **Advanced Models:** Integrate with state-of-the-art LLMs (Claude, Gemini, LLaMA-based models) for better summaries.
- **Fine-Tuned Models:** Train/fine-tune on lecture or meeting datasets for domain-specific summarization.
- **User Customization:** Let users set parameters like summary length, tone (formal/informal), or focus area (e.g., technical, motivational).

---

## Contributing

Feel free to contribute:
- Add features (e.g., multi-language support, UI).
- Improve error handling and logging.
- Write tests for core functionality.

Please fork the repo and open a pull request.

---

## Contact & Author

Created by **Viplove0114**.
Email: viplovethakran4@gmail.com
Feel free to open issues for feedback,