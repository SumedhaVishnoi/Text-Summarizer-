# Text Summarizer

A user-friendly web application for automatic text summarization using the T5 Transformer model. The app enables users to condense large passages of text into concise summaries, with customizable summary length and creativity parameters—all via an interactive, no-code Gradio interface.

## Features

- Summarizes input text using the pretrained T5 model.
- Adjustable summary length and generation creativity (temperature).
- Clean web interface powered by Gradio.
- Handles edge cases and provides user feedback for empty input.
- Allows saving input and summary results to a local log file.



## Installation

1. Clone this repository or download the project files.
2. Install required Python libraries:
    ```
    pip install torch transformers gradio
    ```

## Usage

Run the main Python file: Text_Sumaarizer.py


After launch, a link will appear in your terminal—open it in your browser to interact with the summarizer.

## Parameters

- **Input Text:** Paste or type the text you want to summarize.
- **Max Summary Length:** Sets the upper limit for the summary (default: 150).
- **Min Summary Length:** Sets the minimum length for the summary (default: 40).
- **Creativity (Temperature):** Controls diversity in the generated summary (default: 1.0).

## Project Structure

- `text_summarizer.py`: Main application script.
- `summaries_log.txt`: Optional file for logging original and summarized texts.

## License

This project is MIT licensed.

## Acknowledgements

- Built using Hugging Face Transformers and Gradio.
- Model used: [T5-base](https://huggingface.co/t5-base).

