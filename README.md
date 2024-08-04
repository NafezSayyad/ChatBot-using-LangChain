# ChatBot using LangChain

This project demonstrates how to create an interactive communication assistant using the LangChain library. The assistant maintains session histories, manages message sizes, and provides responses based on past interactions.

## Key Features

- **Environment Setup**: Loads and sets up environment variables.
- **Model Initialization**: Initializes the GPT-4 model via ChatOpenAI.
- **Session History**: Manages message histories for different sessions.
- **Message Trimming**: Limits the number of tokens in the message history.
- **Prompt Template**: Creates a structured prompt template.
- **Runnable Chain**: Sets up a processing chain that includes history management and message trimming.
- **Response Streaming**: Streams responses from the model and prints them.
- **Trimming and Invocation**: Trims a set of messages and invokes the model to get a response.

## Purpose

This script is designed to facilitate interactive communication with an AI model, maintaining session histories, and managing message sizes to ensure efficient processing. The primary use case is for creating a helpful assistant that can remember past interactions and respond accordingly.

## Getting Started

### Prerequisites

- Python 3.7+
- [LangChain](https://github.com/hwchase17/langchain)
- [OpenAI API Key](https://beta.openai.com/signup/)

