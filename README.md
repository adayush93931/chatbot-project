![image](https://github.com/raghav-decoded/ChatbotProject/assets/50199745/f7786236-eb35-467c-91be-929b3f342abd)
![image](https://github.com/raghav-decoded/ChatbotProject/assets/50199745/0b7945b0-1982-4b0a-a5e1-507a36225d1b)



# chatbot_project
# Chatbot with OpenAI API

This is a simple chatbot implementation using the OpenAI API. It allows users to interact with the chatbot by sending messages through a form. The chatbot then generates a response using the OpenAI API and displays it in the chat window.

## Getting Started

To get started with this chatbot, follow the steps below:

1. Clone the repository to your local machine.

2. Replace `"APIKEYHERE"` in the `apiKey` variable with your actual OpenAI API key. Make sure you have a valid API key from OpenAI.

3. Open the `index.html` file in a web browser.

4. Interact with the chatbot by typing messages in the input field and pressing Enter or clicking the Submit button.

## Dependencies

This chatbot implementation relies on the following dependencies:

- [axios](https://axios-http.com): A promise-based HTTP client for making requests to the OpenAI API.

## Structure

The project consists of the following files:

- `index.html`: The HTML file that contains the structure of the chatbot interface.

- `script.js`: The JavaScript file that handles the interaction with the chatbot and makes requests to the OpenAI API.

- `styles.css`: The CSS file that defines the styling for the chatbot interface.

- `icons/`: A directory containing icon images for the user and bot.

## Usage

Once you have set up the project and opened the `index.html` file, you can start interacting with the chatbot. Type your message in the input field and press Enter or click the Submit button. The chatbot will generate a response based on your input and display it in the chat window.

The chatbot uses the OpenAI API to generate responses. The API request is made using the `axios.post` method, which sends a POST request to the `https://api.openai.com/v1/completions` endpoint with the necessary data, including your API key for authorization.

The response from the API is then displayed in the chat window. The chatbot response is also accompanied by an animated bot icon.

## Additional Features

The chatbot implementation includes an additional feature: text-to-speech conversion. After receiving the chatbot's response, the text is passed to a `textToSpeech` function, which can be implemented separately. This function converts the text into speech and plays it back to the user.

In the provided code, a fake delay of 2 seconds is added before displaying the chatbot's response to simulate a more natural conversation flow. You can adjust this delay or remove it as needed.

## Limitations

Please note that this implementation is a basic example and may not cover all possible scenarios or handle errors. It is intended as a starting point for building a chatbot using the OpenAI API and can be expanded upon to suit your specific requirements.

## Disclaimer

This chatbot implementation is for educational purposes only and does not guarantee the accuracy or reliability of the generated responses. The behavior and responses of the chatbot depend on the underlying model provided by OpenAI.

## License

The code in this repository is licensed under the [License](https://github.com/adayush93931/chatbot_project/commit/1b93bcf2516bb82bba4e41c3cb86862a5c5b3177#diff-5842e31900c3e1909b44f0fcd58b775240854a16f421e2248c808b5a450ebb4d). Feel free to modify and distribute it as needed.
