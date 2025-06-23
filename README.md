# Chat with YouTube Videos

This project demonstrates how to build an application that allows users to interact with YouTube video content using Large Language Models (LLMs). Users can ask questions about the content of a YouTube video and receive intelligent, context-aware responses.

## Features

- Extracts transcripts from YouTube videos.
- Uses LLMs to answer questions about video content.
- Simple interface for chatting with video content.
- Easily extendable for other video platforms or LLM providers.

## Getting Started

### Prerequisites

- Python 3.8+
- [pip](https://pip.pypa.io/en/stable/)
- OpenAI API key (or another LLM provider)
- (Optional) [ffmpeg](https://ffmpeg.org/) for audio processing

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/chat_with_youtube_videos.git
    cd chat_with_youtube_videos
    ```

2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Set up your API keys as environment variables or in a `.env` file.

### Usage

1. Run the main application:
    ```sh
    python main.py
    ```

2. Enter a YouTube video URL when prompted.

3. Ask questions about the video content in the chat interface.

## Project Structure

```
chat_with_youtube_videos/
├── main.py
├── requirements.txt
├── README.md
├── utils/
│   └── ...
└── ...
```

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

## License

This project is licensed under the MIT license.
