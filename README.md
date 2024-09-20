# T5 Translation App

This project is a simple web-based translation app using the T5 model from Hugging Face's `transformers` library. The app allows users to translate text between English, French, German, and Romanian using a Gradio interface.

## Features
- Translation from English to French, German, and Romanian.
- Interactive UI with Gradio for easy user input and language selection.

## Requirements
To run this project, you'll need the following Python packages:
- `transformers`
- `gradio`

## Example
1. Enter the text you want to translate in the provided textbox.
2. Select the target language (e.g., French).
3. Press "Submit" to get the translated result.

## Code Explanation
- **Model & Tokenizer:** We use the pre-trained T5 model (`t5-small`) from Hugging Face's model hub to perform translations. The tokenizer converts text into token IDs for the model to process.
- **Translation Function:** The `translate_text` function takes two inputs: the text to be translated and the selected target language. Based on the target language, the function adjusts the translation prompt and generates the result.
- **Gradio Interface:** We use Gradio to create an easy-to-use interface. Users can input text, choose a target language, and see the translated text in real-time.

## Languages Supported
- **English to French**
- **English to German**
- **English to Romanian**
