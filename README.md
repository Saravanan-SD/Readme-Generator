# ReadMe Generator with ChatGPT

This ReadMe Generator with ChatGPT is a Streamlit application that utilizes OpenAI's GPT-3.5 model to generate README files based on provided code.

## Usage

1. **Upload Code File**: Upload the code file for which you want to generate the README.md.

2. **Read the Code and Generate README**: Once the code file is uploaded, the application reads the code and generates a README.md for it in markdown format.

## How it Works

The application utilizes the `ask` function from the `readme_generator` module. This function interacts with the GPT-3.5 model provided by OpenAI to generate text based on the provided code.

## Setup

To run this application locally, follow these steps:

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Make sure you have a valid OpenAI API key. You need to store this key in a file named `secrets.json` in the following format:
    ```json
    {
        "api_key": "YOUR_API_KEY"
    }
    ```
4. Run the Streamlit application using `streamlit run app.py`.
5. Upload your code file and generate the README.

## Dependencies

- `openai`: Python library for interacting with the OpenAI API.
- `streamlit`: Web application framework for building interactive web applications.
- `json`: Library for working with JSON data in Python.

## Example

Suppose you have a Python code file named `example.py` containing some code. You can upload this file using the application, and it will generate a README.md based on the code.

## Note

Ensure that your code file is properly formatted and contains relevant information to generate an accurate README.
