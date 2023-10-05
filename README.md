# Creating_Chatbot
This repository is a comprehensive guide and codebase for building an AI chatbot and deploying it as a user-friendly web application using Python, ChatterBot, and Streamlit. 

## Usage

1. Clone the repository or download the script to your local machine.

2. Open the Python script in your preferred code editor or environment.

3. Execute the script to launch the chatbot application.

4. Interact with the chatbot by asking questions related to the text file content.

## Dependencies

The script utilizes the following Python libraries:

- [NLTK (Natural Language Toolkit)](https://www.nltk.org/): Used for text preprocessing and tokenization.
- [Streamlit](https://streamlit.io/): Used for creating a user-friendly web interface for the chatbot.

## Text Preprocessing

The script performs the following text preprocessing steps:

- Tokenization: The text is tokenized into words and sentences.
- Stopword Removal: Common English stopwords are removed from the text.
- Punctuation Removal: Punctuation characters are removed from the text.
- Lemmatization: Words are lemmatized to their base forms.

## How It Works

1. The script loads the text content from the 'book.txt' file.

2. The user can input a question related to the text.

3. The chatbot analyzes the question and retrieves the most relevant sentence from the text as the answer.

4. The answer is displayed to the user via the Streamlit web interface.

## Example

Here's a sample interaction with the chatbot:

User: "What is the main topic of the book?"

Chatbot: "The main topic of the book is..."

## License

This script is open-source and available under the [MIT License](LICENSE).



**Note:** This script is intended for educational purposes and demonstrates a simple chatbot concept. 

