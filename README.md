# Voice AI Restaurant Assistant

This project is a Voice AI agent named "James" that acts as a receptionist in an AI restaurant. James can handle table reservations and take orders from a predefined menu using natural voice interactions. The application uses the OpenAI GPT model for conversational intelligence and Deepgram for speech-to-text and text-to-speech functionalities.

## Features

- Engage in human-like voice conversations.
- Handle table reservations, including asking for date, time, and the number of guests.
- Take food orders, confirm the order, and calculate the total price.
- Provide delivery time estimates.
- Voice interaction with synthesized responses.

## Technologies Used

- Python
- OpenAI API
- Deepgram API
- Pygame for audio playback
- dotenv for environment variable management

## Prerequisites

Before running this project, make sure you have the following:

- Python 3.7 or higher installed
- An API key for OpenAI
- An API key for Deepgram

## Installation

Follow these steps to set up and run the project:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/voice-ai-restaurant-assistant.git
    cd voice-ai-restaurant-assistant
    ```

2. **Create and activate a virtual environment:**

    On Windows:

    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```

    On macOS and Linux:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**

    Create a `.env` file in the root of the project directory and add your API keys:

    ```plaintext
    DEEPGRAM_API_KEY=your_deepgram_api_key
    OPENAI_API_KEY=your_openai_api_key
    ```

    Replace `your_deepgram_api_key` and `your_openai_api_key` with your actual API keys.

5. **Run the application:**

    ```bash
    python app.py
    ```

## Usage

- The application will start listening for voice input once it runs.
- You can interact with the AI agent "James" by speaking into your microphone.
- James will respond using synthesized voice and will handle tasks like table reservations and order-taking.

## Notes

- Make sure you have a working microphone connected to your computer.
- Ensure your API keys have sufficient quota to handle the requests.
- If you encounter a `429 - insufficient_quota` error, check your OpenAI and Deepgram usage and plan limits.

## Troubleshooting

- If the application fails to start, check if all dependencies are installed correctly and that your environment variables are set up properly.
- In case of API errors, ensure that your API keys are valid and have sufficient quota.
- For any other issues, feel free to open an issue in the GitHub repository.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch-name`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- OpenAI for providing the GPT model
- Deepgram for speech-to-text and text-to-speech capabilities
