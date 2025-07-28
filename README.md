# EchoYT - YouTube Video Summarizer & Chatbot

🎥 An intelligent AI-powered application that extracts transcripts from YouTube videos and enables interactive Q&A conversations with enhanced audio features.

## Features

### 🎯 Core Functionality
- **YouTube Transcript Extraction**: Automatically fetches video transcripts with multi-language support
- **AI-Powered Q&A**: Chat with your videos using advanced language models
- **Voice Input**: Ask questions using voice recordings
- **Enhanced Audio Responses**: Text-to-speech with 15+ voice options

### 🎵 Advanced Audio Features
- **Multiple Voice Options**: 15+ voices including English, Hindi, French, German, Spanish
- **Customizable Speech Speed**: Adjustable playback speed (0.5x - 2.0x)
- **Audio Download**: Save responses as WAV/MP3 files
- **Audio Caching**: Improved performance with intelligent caching
- **Auto-play Options**: Seamless audio experience

### 🌍 Language Support
- English (US, UK, Indian)
- Hindi/English (Bilingual)
- French, German, Spanish
- Auto-detection of transcript languages

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rajdeep183/youtube_classification.git
   cd EchoYT
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**
   Create a `.env` file with:
   ```
   OPENAI_API_KEY=your_openai_api_key
   AWS_ACCESS_KEY_ID=your_aws_access_key
   AWS_SECRET_ACCESS_KEY=your_aws_secret_key
   ```

4. **Run the application:**
   ```bash
   streamlit run main.py
   ```

## Usage

1. **Enter YouTube URL**: Paste any YouTube video URL
2. **Analyze Video**: Click to process the video transcript
3. **Ask Questions**: Use text or voice input to interact
4. **Listen to Responses**: Enjoy AI responses with custom voice options
5. **Download Audio**: Save responses for offline listening

## Technology Stack

- **Frontend**: Streamlit
- **AI/ML**: OpenAI GPT-4, LangChain, FAISS
- **Audio Processing**: AWS Polly, OpenAI Whisper, FFmpeg
- **Vector Database**: FAISS for semantic search
- **Authentication**: AWS SDK

## Requirements

- Python 3.8+
- OpenAI API key
- AWS credentials (for Polly TTS)
- FFmpeg (included in project)

## Project Structure

```
EchoYT/
├── main.py                    # Main Streamlit application
├── requirements.txt           # Python dependencies
├── README.md                 # Project documentation
├── bin/
│   └── ffmpeg                # Audio processing binary
└── ffmpeg-7.0.2-i686-static/ # FFmpeg static build
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Rajdeep Roy**
- GitHub: [@Rajdeep183](https://github.com/Rajdeep183)
- Project: [youtube_classification](https://github.com/Rajdeep183/youtube_classification)

## Acknowledgments

- OpenAI for GPT-4 and Whisper APIs
- AWS for Polly text-to-speech service
- LangChain for RAG implementation
- Streamlit for the web interface

---

*Built with ❤️ by Rajdeep Roy*
