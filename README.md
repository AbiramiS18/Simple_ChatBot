# Simple Chatbot in Python using NLTK

This repository contains a simple rule-based chatbot implemented in Python using the Natural Language Toolkit (NLTK). The chatbot responds to user inputs based on predefined patterns and responses.

## Description

A chatbot (also known as a talkbot, chatterbot, Bot, IM bot, interactive agent, or Artificial Conversational Entity) is a computer program or artificial intelligence that conducts a conversation via auditory or textual methods. This simple chatbot uses NLTK's ⁠ Chat ⁠ module and a set of predefined patterns and responses to simulate a conversational agent.

### Features

- Recognizes and responds to basic greetings and introductions.
- Answers questions about its name and state of being.
- Engages in simple conversations.
- Exits the conversation upon receiving the "quit" command.

## Getting Started

### Prerequisites

To run this project, ensure you have the following installed:

- Python 3.x
- NLTK library

Install NLTK using pip if not already installed:

```sh
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```
