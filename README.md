
# Auto Speech Recognition with Whisper and Demo

## Description
This project extends the basic functionality of automatic speech recognition (ASR) with OpenAI's Whisper model by including a live demo built with Gradio. It provides an interactive way to test the model's capabilities by allowing users to upload audio files and see the transcription results in real-time. This repository contains a Jupyter notebook that guides you through data preparation, model usage, and setting up the demo interface.

## Installation

Make sure Python is installed on your system. For managing project dependencies, the use of a virtual environment is recommended.

Install the necessary packages with the following command:

\```bash
pip install transformers datasets soundfile librosa gradio
\```

These dependencies include libraries for the machine learning model, handling data, processing audio files, and creating web interfaces for demonstrations.

## Usage

To use this project for speech recognition with a live demo, follow these instructions:

1. **Clone this repository** to your local machine.
2. **Open the notebook** `Auto Speech Recognition (Whisper Speech to Text) with DEMO.ipynb` in Jupyter Lab or Jupyter Notebook.
3. **Execute the notebook cells** in sequence, following any specific instructions given. The notebook will lead you through preparing your audio data, using the Whisper model for transcription, and deploying a Gradio interface for interactive testing.

## Features

- Preparation and loading of data using the `datasets` library.
- Speech-to-text conversion using the Whisper model.
- A Gradio demo interface for interactive speech recognition testing.

## Contributing

Contributions are welcome! For improvements or bug fixes, please fork the repository, make your changes, and submit a pull request. If you have significant changes in mind, open an issue first to discuss what you'd like to do.

## License

This project is freely available under the MIT License. For more details, see the LICENSE file.
