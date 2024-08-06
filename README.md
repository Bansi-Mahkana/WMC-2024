# WMC-2024
This is our repository for Website Making Challenge (WMC) - 2024
# GTA V Chatbot

This project is a simple web-based chatbot that allows users to interact with three characters from the game Grand Theft Auto V (GTA V): Michael, Trevor, and Franklin. Users can switch between these characters during the conversation, with each character maintaining their distinct personality and behavior.

## Features

- **Character Interaction**: Chat with Michael, Trevor, or Franklin from GTA V.
- **Dynamic Personality Switching**: Switch between characters on the fly, and the chat box clears when a new character is selected.
- **Real-time Responses**: The chatbot generates real-time responses using the Google Generative AI.

## Technologies Used

- HTML for the basic structure of the web page.
- JavaScript for handling user interactions and API calls.
- [Google Generative AI](https://developers.generativeai.google) for generating chatbot responses.

## Getting Started

### Prerequisites

To run this project, you'll need:

- A web browser that supports modern JavaScript.
- A Google Generative AI API key. You can get one by signing up at [Google Cloud](https://cloud.google.com).

### Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-repo/gta-v-chatbot.git
    cd gta-v-chatbot
    ```

2. **Update the API key**:
    - Replace the placeholder API key in the code (`const API_KEY = "YOUR_API_KEY";`) with your actual Google Generative AI API key.

3. **Run the project**:
    - Open the `index.html` file in your web browser to start interacting with the GTA V Chatbot.

### How to Use

1. **Select a character**:
   - Choose one of the characters (Michael, Trevor, Franklin) by selecting the corresponding radio button.

2. **Enter a prompt**:
   - Type your message or question in the input field.

3. **Send the message**:
   - Click the "Send" button to interact with the selected character.

4. **Switch characters**:
   - Select a different character at any time, and the chat will start fresh with the new character's greeting.

## File Structure

```plaintext
.
├── index.html        # Main HTML file containing the chatbot interface.
├── README.md         # This README file.
└── assets            # Directory for any additional assets (if needed).

