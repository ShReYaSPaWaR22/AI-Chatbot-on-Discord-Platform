# AI Chatbot for Discord

This project is a Discord bot that integrates with Google's Generative AI to provide AI-driven responses to users' messages. The bot is capable of generating text and image responses based on the inputs provided by users. It can handle both direct messages and messages where the bot is mentioned in a server channel.

## Features

- **Text Response Generation**: Generates AI-powered responses to text inputs using Google Generative AI's Gemini model.
- **Image Response Generation**: Handles image-based queries and generates AI-powered image descriptions or interactions.
- **Message History**: Keeps a conversation history for better context-aware responses (configurable via `MAX_HISTORY`).
- **Commands**: Can reset history and interact through Discord chat commands.

## Installation and Setup

### Prerequisites

- Python 3.8 or higher
- [Discord Developer Portal](https://discord.com/developers/applications) account with a bot token.
- Google Generative AI account with an API key.

## How to Use
1) Start the Bot: The bot will come online and be ready to respond to messages.
2) Mention the Bot: Mention the bot in a server channel, or direct message the bot to start interacting.
3) Image Interactions: Send an image to the bot, and it will provide a response based on the image and any accompanying text.
4) Reset Conversation History: Type RESET to reset your chat history with the bot.
