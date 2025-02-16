# RomanScriptDetect

RomanScriptDetect is an advanced and efficient tool designed to identify and classify Indian languages written in the Roman alphabet. It leverages cutting-edge machine learning and natural language processing (NLP) techniques to ensure high accuracy in detecting romanized text. This makes it an ideal solution for automatic language detection in informal, non-standard, or non-native scripts used across various digital platforms, including social media, chat applications, and multilingual datasets.

## Features

- **Accurate Language Detection**: Uses state-of-the-art machine learning models to analyze and classify romanized Indian languages with high precision.
- **NLP-Based Processing**: Incorporates advanced natural language processing techniques to enhance detection accuracy and efficiency.
- **Lightweight and Fast**: Designed with optimization in mind, ensuring rapid and efficient language detection.
- **Scalable and Flexible**: Works well for small-scale applications and can be scaled up for large-scale projects and enterprise applications.
- **Easy Integration**: Can be used as a standalone tool or seamlessly integrated into existing software applications and pipelines.

## Installation

RomanScriptDetect is easy to install and set up. Follow the steps below to get started:

### Clone the Repository:
```sh
git clone https://github.com/AbhishekOmray/RomanScriptDetect.git
```

### Navigate to the Project Directory:
```sh
cd RomanScriptDetect
```

### Install Dependencies:
```sh
pip install -r requirements.txt
```

## Usage

RomanScriptDetect provides a simple and intuitive API for detecting the language of romanized Indian text. Below is a basic example:

```python
from romanscriptdetect import detect_language

text = "Namaste doston, kaise ho?"
lang = detect_language(text)
print(f"Detected language: {lang}")
```

This will output the detected Indian language of the given text.

## Supported Languages

Currently, RomanScriptDetect supports the following Indian languages in romanized form:

- Hindi
- Marathi
- Tamil
- Telugu
- Bengali
- Kannada
- Malayalam
- Gujarati
- Punjabi
- Odia
- Sindhi
- Urdu

More languages will be added in future updates.

## Applications

RomanScriptDetect can be used in various applications, including:
- **Social Media Analytics**: Automatically classify and analyze romanized Indian text on social media platforms.
- **Machine Translation Preprocessing**: Identify the source language of romanized Indian text before applying machine translation.
- **Search and Indexing**: Improve search engines' ability to index and retrieve romanized Indian content.
- **Digital Forensics and Cybersecurity**: Detect languages used in digital communications and online forums.



### Stay tuned for future updates as we continue to enhance RomanScriptDetect with new features and expanded Indian language support!
