# AI Content Summarizer

A Streamlit application that summarizes content from YouTube videos and websites using AI.

## Features

- Summarize YouTube videos (up to 30 minutes)
- Summarize web articles and blog posts
- Download summaries in PDF and text formats
- Beautiful and intuitive UI

## Setup Instructions

1. Clone the repository:
```bash
git clone <your-repo-url>
cd 7-Text-Summarization
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
   - Copy `.env.example` to `.env`:
     ```bash
     cp .env.example .env
     ```
   - Edit `.env` and add your Groq API key:
     ```
     GROQ_API_KEY = "your_groq_api_key_here"
     ```

4. Run the application:
```bash
streamlit run app.py
```

## Environment Variables

The following environment variables are required:

- `GROQ_API_KEY`: Your Groq API key for accessing the AI model

## Security Notes

- Never commit your `.env` file to version control
- Keep your API keys secure and private
- The `.env` file is already included in `.gitignore`

## Limitations

- Maximum video duration: 30 minutes
- Processing time may vary based on content length
- Requires internet connection for API access

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 