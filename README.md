# Stellaris

Stellaris is a cosmic-themed conversational AI assistant powered by **DialoGPT** for contextual dialogue generation and **SentenceTransformer** for knowledge retrieval. It is designed to answer questions, retrieve space-themed facts, tell jokes, and provide real-time date and time information, all with an interstellar flair.

## Features

* Conversational AI with contextual awareness
* Real-time date and time fetching
* Wikipedia summary retrieval
* Space-themed jokes and cosmic facts
* Basic calculator functions
* Interactive chatbot experience

## Installation

To run Stellaris, make sure you have the following packages installed:

```bash
pip install transformers torch sentence-transformers faiss-cpu wikipedia datetime pytz
```

## Usage

To start the chatbot, run the following:

```python
from Stellaris import Stellaris
cosmic_bot = Stellaris()
cosmic_bot.start_chat()
```

### Commands Supported:

* **General Questions**: Just ask anything, and Stellaris will answer.
* **Time:** `What time is it?`
* **Date:** `What's the date today?`
* **Weather:** `How's the weather in Andromeda?`
* **Jokes:** `Tell me a space joke.`
* **Wikipedia Lookup:** `Who is Neil Armstrong?`
* **Math Calculations:** `5 + 3`, `12 * 4`

To quit the chat, simply type:

```
quit
```

## Project Structure

* `Stellaris`: Main class handling chatbot operations
* `retrieve_knowledge`: Searches for predefined information
* `generate_response`: Generates AI responses based on context
* `start_chat`: Launches the interactive chat loop

## Future Enhancements

* Real-time weather API integration for cosmic locations
* Voice input and output for immersive experience
* Enhanced conversation memory and context awareness

## Contributions

Contributions are welcome! Please follow the guidelines for pull requests.

## License

This project is licensed under the MIT License.
