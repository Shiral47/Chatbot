# Creative Object Ideas

A beginner-friendly Google Colab notebook that asks for an everyday object and uses the OpenAI Responses API to suggest one unusual, creative, practical use for it.

## Repository structure

- `to-do app.ipynb` — Colab notebook with setup, secure API key entry, object prompt, and AI-generated idea.
- `prompt.md` — project requirements and technical specifications.
- `README.md` — project overview and usage instructions.

## Run in Google Colab

1. Open [`to-do app.ipynb` in Google Colab](https://colab.research.google.com/github/Shiral47/Chatbot/blob/main/to-do%20app.ipynb). You can also clone this repository with `git clone https://github.com/Shiral47/Chatbot.git`, then upload/open the notebook in Colab.
2. Run the notebook cells from top to bottom. The setup cell installs the OpenAI SDK if it is not already installed.
3. When prompted, enter your OpenAI API key in the secure, hidden prompt, then type an everyday object.

An OpenAI API key is required at runtime. Keep it private: enter it only into the notebook's runtime prompt, never put it in notebook source, saved outputs, commits, or a GitHub repository. The notebook does not save the key to the project files.
