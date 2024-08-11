# Smart-Buddy - AI-Powered Chat App
Welcome to EasyChatGPT - your AI-powered chat application! This app demonstrates real-time conversations with the OpenAI GPT-3 model using the OkHttp library for API calls. Below, we provide an overview of key files and features:
![Untitled design](https://user-images.githubusercontent.com/60041910/218378637-adf9bcbf-5c7e-4274-8491-1ebe2a28b396.gif)


## Key Features

- **Real-time Conversations:** Engage in dynamic conversations with the OpenAI GPT-3 model.
- **User-friendly Interface:** Simple and intuitive user interface for seamless chatting.
- **Message History:** Display a history of sent and received messages.
- **OpenAI Integration:** Utilize the power of the OpenAI API for text completion.

## Usage

1. Clone or download the repository to your local machine.
2. Open the project in Android Studio.
3. Replace `YOUR_API_KEY` in `callAPI()` with your OpenAI API key.
4. Build and run the app on your Android device or emulator.

## File Structure

- `MainActivity.java`: The main activity managing chat functionality and API calls.
- `Message.java`: Data model for individual chat messages.
- `MessageAdapter.java`: RecyclerView adapter for displaying messages.
- `activity_main.xml`: Layout XML file for the main chat activity.

## How It Works

1. User inputs a message and taps the send button.
2. The message is added to the chat history as "Sent by Me".
3. The app calls the OpenAI API with the user's message.
4. The API response (bot's reply) is added to the chat history as "Sent by Bot".

## Important Note

Ensure you have obtained your OpenAI API key and added it to the `Authorization` header in the `callAPI()` function.

## Disclaimer

Please be cautious while integrating API keys and sensitive information in your code. This repository is for educational purposes and to showcase integration with the OpenAI API.

## Resources

- [OpenAI API Documentation](https://beta.openai.com/docs/)
- [OkHttp Library](https://square.github.io/okhttp/)

Feel free to explore, experiment, and contribute to this project. Happy coding!

---

*Disclaimer: This repository is for educational purposes and does not provide guarantees or warranties for any purpose. It is recommended to follow best practices for securing API keys and sensitive information.*


# Real-Time Conversation with OpenAI GPT-3

This project enables real-time conversations with OpenAI GPT-3 through an intuitive Android interface. Users can clone the repository, add their API key, and run the app in Android Studio, with chat history displayed.

## Features

- **Real-Time Conversations**: Interact with OpenAI GPT-3 in real time through a user-friendly Android interface.
- **Chat History**: View previous messages and responses in the chat history.
- **Easy Setup**: Clone the repository, add your API key, and run the app in Android Studio.

## Built With

- **Java**: The core programming language used for Android development.
- **OpenAI API**: For integrating GPT-3 conversational capabilities.
- **Android Studio**: The official IDE for Android development.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- [Android Studio](https://developer.android.com/studio)
- [OpenAI API Key](https://beta.openai.com/signup/)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/gpt3-android-chatbot.git
    ```
2. Open the project in Android Studio:
    ```bash
    cd gpt3-android-chatbot
    ```
    - Open Android Studio and select "Open an existing project."
    - Navigate to the project directory and open it.

3. Add your OpenAI API key:
    - Locate `MainActivity.java` in the `src/main/java/com/yourpackage/` directory.
    - Add your API key in the designated area.

4. Build and run the app:
    - Click on the "Run" button in Android Studio or use `Shift + F10`.

## File Structure and Operation

Key files include:

- **MainActivity.java**: Manages chat interactions and API calls.
- **Message.java**: Data model for chat messages.
- **MessageAdapter.java**: Adapter for displaying messages in the chat interface.
- **activity_main.xml**: Layout file for the main activity.

### How It Works

1. **User Input**: Users enter messages in the chat interface.
2. **API Call**: The app sends the user's message to the OpenAI GPT-3 API.
3. **Response Handling**: The API response is received and dynamically added to the chat history.
4. **Display**: Both user messages and GPT-3 responses are displayed in the chat interface.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by various open-source projects for real-time chat applications.
- Thanks to OpenAI for providing the GPT-3 API and to the developers of the libraries used in this project.

---

Enjoy using the **Real-Time Conversation with OpenAI GPT-3** app! If you have any questions or need further assistance, feel free to open an issue or contact us directly.
