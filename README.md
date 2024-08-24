**AI Image Description & Translation**

This repository contains a Streamlit app that generates image descriptions based on user prompts using Google Generative AI and provides translations of the descriptions in multiple languages. Additionally, the app features a text-to-speech function that converts the generated description into audio.

**Features**

**Image Description Generation:** Upload an image and provide a prompt to generate a description using Google Generative AI.

**Translation:** Translate the generated description into multiple languages.

**Text-to-Speech:** Convert the generated description into audio with a choice of male or female voices.

**Requirements**

Python 3.x

Streamlit

PIL (Pillow)

Google Generative AI (gemini-1.5-flash-001)

pyttsx3

googletrans

**Installation**

Clone the repository:

git clone https://github.com/your-username/AI-Image-Description-Translation.git

Navigate to the project directory:

cd AI-Image-Description-Translation

Install the required dependencies:

pip install -r requirements.txt

**Usage**

API Key Setup:

Obtain an API key from Google Generative AI.

Replace the placeholder API key in the script with your own API key.

Running the App:

Run the Streamlit app using the following command:

streamlit run app.py

Upload an image, enter a prompt, and interact with the app.

Audio and Translation:

Choose a voice (Male/Female) for text-to-speech conversion.

Select a language to translate the generated description.

**Example Output**

The app will display the uploaded image along with the generated description, translated text, and an audio file of the description.

**License**

This project is licensed under the MIT License. See the LICENSE file for details.

**Acknowledgements**

Google Generative AI for image description generation.
Streamlit for the web app framework.
pyttsx3 for text-to-speech functionality.
Googletrans for translation services.

**Contributing**

Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.
