# Translator

A powerful language translation tool that can translate text from any language to another. This project has been an incredible learning experience, helping me sharpen my skills in Python and natural language processing. It serves as a practical tool for breaking language barriers and demonstrates the potential of integrating translation APIs and libraries into a user-friendly application.

## Project Overview

The **Translator** project is designed to translate text between different languages effortlessly. Built as a learning project, it not only provides a useful functionality but also allowed me to dive deep into working with APIs (or libraries) for translation and handling natural language data. Whether you're looking to translate a simple sentence or multiple paragraphs, this tool is here to help.

## Features

- **Multi-Language Support:** Translate text from any language to another.
- **User-Friendly Interface:** Simple and intuitive command-line interface for entering text and selecting languages.
- **Learning Experience:** Developed as a project to enhance my programming and language processing skills.

## Technologies & Additional Libraries Used

- **Python 3.x:** The main programming language used for building this application.
- **googletrans==4.0.0-rc1:** Library for translating text using the Google Translate API.
- **langdetect:** Library used for automatic language detection.
- **(Optional) Requests:** Utilized internally by some libraries to handle HTTP requests.

*Note: A complete list of dependencies is available in the `requirements.txt` file.*

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/krishnakeshab-banik/Translator.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd Translator
   ```

3. **Install the Required Packages:**

   If there's a `requirements.txt` file, run:

   ```bash
   pip install -r requirements.txt
   ```

   Alternatively, install the necessary packages manually:

   ```bash
   pip install googletrans==4.0.0-rc1 langdetect requests
   ```

## Usage

To use the Translator:

1. **Run the Application:**

   ```bash
   python translator.py
   ```

2. **Follow the Prompts:**
   - Input the text you wish to translate.
   - Specify the source language (or let the tool detect it automatically).
   - Specify the target language.
   
3. **View the Translation:**
   - The translated text will be displayed on the screen.

## Screenshot

![translator_img](https://github.com/user-attachments/assets/292c9517-53a9-4b6d-97b4-85339bcf293b)

### Example

- **Input:** "Hello, how are you?" (source: English, target: Spanish)
- **Output:** "Hola, ¿cómo estás?"

## Future Improvements

- **Graphical User Interface (GUI):** Integrate a GUI using frameworks like Tkinter or PyQt for a more interactive experience.
- **Enhanced Error Handling:** Improve error checking and handling for invalid inputs or network issues.
- **Translation History:** Implement functionality to save and view past translations.
- **Extended Language Support:** Automatically detect languages and support additional translation features.

## Acknowledgements

This project has been a valuable stepping stone in my learning journey, enabling me to explore the nuances of language processing and API integration. I extend my gratitude to the open-source community for providing the tools and libraries that made this project possible.

## Author

**Krishna Keshab Banik**  
[LinkedIn](https://www.linkedin.com/in/krishna-keshab-banik-067819324/)
