# Rasa Chatbot 

Welcome to the Rasa Chatbot, a simple yet powerful conversational agent built using Rasa, an open-source machine learning framework.

## Features

The chatbot boasts the following features:

- Handles basic conversational intents such as greetings, farewells, affirmations, and denials.
- Recognizes user moods, providing appropriate responses to emotions like happiness and sadness.
- Answers basic inquiries about the weather.
- Detects and responds to challenges posed by the user.
- Utilizes a combination of rule-based algorithms and machine learning models for intent classification and entity extraction. Responses are hardcoded for a more controlled user experience.

## Architecture

Key components of the chatbot include:

- **NLU (Natural Language Understanding):** Employs the Rasa NLU pipeline for accurate intent classification and entity extraction. The pipeline includes components like tokenizer, featurizers, and the DIET classifier.
- **Dialogue Management:** Uses rule-based algorithms to map intents to predefined responses.
- **Configuration:** Manages environment-specific settings, such as credentials.
- **Custom Actions:** Integrates external APIs, such as fetching weather information using Python code.
- **Testing:** Includes NLU and dialogue management test cases for robust evaluation.

## Getting Started

### Installation

1. Clone this repository.
2. Install required dependencies.
3. Train the NLU model: `rasa train nlu`.
4. Train the dialogue model: `rasa train`.

### Running the Bot

1. Start the action server: `rasa run actions`.
2. Initiate the bot in the shell: `rasa shell`.
3. Engage in a conversation with the bot directly within the shell.

Feel free to explore and enhance the capabilities of the Rasa Chatbot for a more interactive user experience!
