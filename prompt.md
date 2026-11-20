# Project requirements and technical specifications

## Git and GitHub

- Use the local project directory as a Git repository on branch `main`.
- Configure this repository's commit identity as Shir Alkalay <shiralklay2000@gmail.com>.
- Authenticate GitHub CLI as `Shiral47`; use that authentication for Git over HTTPS.
- Create a public GitHub repository named `Chatbot` under `Shiral47`, configure it as `origin`, and push `main` with upstream tracking.
- Never store passwords or access tokens in project files.
- Document the work in a Git commit (“create git record” workflow).

## Files

- `to-do app.ipynb`: beginner-friendly Google Colab notebook, with markdown explanations and simple, commented Python cells.
- `README.md`: project summary, repository structure, instructions to clone/open and run in Colab, and API key security guidance.

## Notebook behavior

1. Install the OpenAI SDK only if it is missing (`!pip -q install openai`).
2. Request the OpenAI API key at runtime using `getpass`; never hardcode, display, save in outputs, or commit it.
3. Ask for an everyday object using `input()`.
4. Call `client.responses.create` with model `gpt-6-luna` and ask for exactly one unusual, creative, practical use for the object.
5. Display the generated suggestion without exposing the key.

## README security guidance

State clearly that an OpenAI API key is needed at runtime and must never be committed or uploaded to GitHub.
