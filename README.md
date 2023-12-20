# Video Summarizer

## Description
This Python script provides an automated way to summarize videos. It uses `replicate` to transcribe video audio through the Whisper API, and then employs OpenAI's GPT-4 model to generate a concise summary. This tool is ideal for quickly understanding the key points of a video without watching it in its entirety.

## Features
- Transcribes video audio using Whisper.
- Summarizes transcribed content using OpenAI's GPT-4.
- Handles large transcripts by splitting them into chunks and processing each separately.
- Combines multiple summaries into a single, coherent summary.

## Requirements
- Python 3
- `replicate` library
- `openai` library
- An API key for OpenAI

## Installation
Clone the repository and install the required packages:

git clone https://github.com/your-github-username/your-repo-name.git
cd your-repo-name
pip install replicate openai

## Usage
1. Set your OpenAI API key as an environment variable:

export OPENAI_API_KEY='your-api-key'

2. Run the script with a YouTube URL:
python script_name.py --url 'your-video-url'

## Example
python summerize.py --url 'https://www.youtube.com/watch?v=dQw4w9WgXcQ'

## Contributing
Contributions to improve the script are welcome. Please fork the repository and submit a pull request with your changes.

## License
[MIT License](LICENSE)


