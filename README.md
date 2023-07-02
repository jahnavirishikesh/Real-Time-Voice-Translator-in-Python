# Real-Time-Voice-Translator-in-Python

This repository contains a voice translator application built in Python. The application allows users to input voice commands, detects the language of the input, translates the text into the desired destination language using the Google Translate API, and reads out the translated text while also displaying it in the console.

## Features

1. Voice Command Input: The application accepts voice commands as input, making it convenient for users to communicate their translation requests.

2. Language Detection: The application utilizes language detection to automatically determine the language of the input. This helps in accurately translating the text into the desired language.

3. Google Translate API Integration: The translation functionality is powered by the Google Translate API. This ensures reliable and accurate translations from the source language to the destination language.

4. Voice Input for Destination Language: To specify the destination language, the application accepts voice input from the user. This simplifies the process by eliminating the need for manual language selection.

5. Text-to-Speech and Console Display: Once the translation is complete, the application reads out the translated text using text-to-speech functionality. Additionally, the translated text is printed in the console for easy reference.

## Requirements

To run the voice translator application, the following dependencies are required:

- Python (version 3.7 or higher)
- Google Translate API credentials
- Python libraries: SpeechRecognition, googletrans, pyttsx3, playsound





## Installation

1. Clone the repository:

```shell
git clone https://github.com/jahnavirishikesh/Real-Time-Voice-Translator-in-Python.git
```

2. You can install the required Python libraries, including Playsound, using pip:

```shell
pip install SpeechRecognition googletrans pyttsx3 playsound
```

3. Obtain Google Translate API credentials by following the instructions in the [Google Cloud Translation API documentation](https://cloud.google.com/translate/docs/setup).

4. Rename the `.env.example` file to `.env` and update it with your Google Translate API credentials.

## Usage

1. Open a terminal or command prompt.

2. Navigate to the project directory:

```shell
cd Real-Time-Voice-Translator-in-Python
```

3. Run the application:

```shell
python Translator.py
```

4. Follow the instructions provided by the application. Speak your input when prompted, and specify the destination language using voice input.

5. The application will detect the input language, translate the text using the Google Translate API, read out the translated text, and display it in the console.

6. Repeat steps 4 and 5 for any additional translation requests.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for using the voice translator!
