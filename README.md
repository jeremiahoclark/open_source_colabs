# Google Colab Scripts Repository

Welcome to the Google Colab Scripts Repository! This repository is a collection of open-source Google Colab scripts that aim to provide convenient and useful tools for various tasks. Whether you're a data scientist, machine learning enthusiast, or just someone who enjoys automating processes, you'll hopefully find something valuable here.

## Table of Contents
- [Introduction](#introduction)
- [Scripts](#scripts)
  - [LinkedIn Activity Scraper](#linkedin-activity-scraper)
  - [OpenAI TTS and Groq Whisper Reading While Listening](#openai-tts-and-groq-whisper-reading-while-listening)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Google Colab is a powerful platform that allows you to write and execute Python code in your browser. It provides a convenient environment for data analysis, machine learning, and more. This repository leverages the capabilities of Google Colab to offer a range of scripts that can help streamline your workflow and solve common problems.

## Scripts

### LinkedIn Activity Scraper

The LinkedIn Activity Scraper is a Python script that allows you to scrape recent activity data from a LinkedIn profile. It utilizes the Selenium WebDriver to automate the process of logging in to LinkedIn, navigating to the specified profile's activity page, and extracting the activity data.

To use the LinkedIn Activity Scraper, follow these steps:

1. Open the `linkedin_activity_scraper.ipynb` notebook in Google Colab.
2. Install the required dependencies by running the provided installation commands.
3. Provide your LinkedIn login credentials and the profile link of the user whose activity you want to scrape.
4. Run the script and wait for it to complete the scraping process.
5. The scraped activity data will be saved as a JSON file named `activities.json`, which you can download from Colab.

Please note that the script requires a valid LinkedIn account and may be subject to LinkedIn's terms of service and privacy policy. Use the script responsibly and respect the privacy of others.

If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

### OpenAI TTS and Groq Whisper Reading While Listening

The OpenAI TTS and Groq Whisper Reading While Listening project is a Python script that demonstrates how to create a Reading While Listening app similar to Kindle and Audible combined. It uses OpenAI's Text-to-Speech (TTS) API to generate audio from text, and Groq's Whisper API for speech-to-text transcription with timestamps.

Key features of this script include:

- Text-to-speech conversion using OpenAI's TTS API
- Speech-to-text transcription with timestamps using Groq's Whisper API
- Sentence-level tracking for synchronized reading and listening
- Cursor position calculation for a reading interface

To use the OpenAI TTS and Groq Whisper Reading While Listening script:

1. Open the `openai_tts_groq_whisper_rwl.ipynb` notebook in Google Colab.
2. Install the required dependencies (openai and groq-sdk).
3. Set up your OpenAI and Groq API keys in the notebook.
4. Run the cells to generate speech from text, transcribe it, and analyze the results.
5. Review the output for insights on implementing a Reading While Listening app.

This script provides a foundation for building a Reading While Listening application, demonstrating how to synchronize text with audio using AI-powered speech services.

## Contributing

We welcome contributions from the community! If you have a script that you believe would be a valuable addition to this repository, please follow these steps:

1. Fork the repository.
2. Create a new branch for your script.
3. Add your script to the repository, along with a detailed README file.
4. Submit a pull request, describing your script and its benefits.

Please ensure that your code follows the repository's coding style and guidelines. Also, make sure to test your script thoroughly before submitting a pull request.

If you have any ideas for new scripts or improvements to existing ones, feel free to open an issue and discuss it with the community.

## License

This repository is licensed under the MIT License. By contributing to this repository, you agree to license your contributions under the same license.

We hope you find the scripts in this repository helpful and convenient. Happy coding!
