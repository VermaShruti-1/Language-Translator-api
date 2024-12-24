It is a Java implementation of a simple Language Translator using the Google Translate API. To use this code, you'll need an API key from Google Cloud's Translation API.
Steps to Use Google Translate API
1. Go to Google Cloud Console.
2. Enable the Google Cloud Translation API.
3. Generate an API key for your project.

Explanation of the Code
1. API Key:
Replace YOUR_API_KEY with the API key you generated in Google Cloud.
2. Translation Logic:
The translateText method takes the text, source language code, and target language code as parameters.
It creates an HTTP POST request with the required JSON payload.
3. HTTP Request:
Uses OkHttp library to send the request to the Google Translate API.
4. Parsing Response:
The response from the API is parsed using the org.json library to extract the translated text.
