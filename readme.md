# Bot-to-bot chat With OpenAI's API

This project utilizes OpenAI's GPT-3.5 Turbo model to generate chatbot personalities and facilitate a conversation between two AI language models (LLMs). The chatbot provides engaging and informative responses based on the personalities generated for each LLM.

## Features

- Generate distinct personalities for two different LLMs.
- Create starting prompts for initiating conversations with real problems that need solving.
- Simulate a chat between two LLMs with a user-driven message.
- Save chat logs to a JSON file for later review.

## Prerequisites

Before running this project, you will need:

- Python 3.x
- OpenAI API key (you can obtain one from [OpenAI](https://openai.com/api/))

## Installation

To set up the project on your local machine:

1. Clone the repository:
   ```bash
    git clone https://github.com/kaneda2004/problem_solvers_gpt


2. Navigate to the project directory:
    ```bash
    cd problem_solvers_gpt

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt


## Usage
Before running the script, make sure to set the OPENAI_API_KEY environment variable with your OpenAI API key. This can be done by exporting the variable in your terminal or using an .env file.

To run the main program:
    ```bash
    python agents.py

Follow the prompts in the terminal to interact with the chatbot and view the chat logs.

Configuration
You can adjust the following settings in the script:

MODEL: The OpenAI model being used, default is "gpt-3.5-turbo".
TEMPERATURE: Controls randomness in the responses, default is 0.9.
MAX_TOKENS: Limits the response length, default is 400.

## Contributing

Contributions to improve the project are welcome, hmu with your PRs.
To contribute do this:

Fork the repository.
Create a new branch for your feature (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a pull request.

License
Distributed under the MIT License.

Contact
😎😎

Project Link: https://github.com/kaneda2004/problem_solvers_gpt

## Acknowledgments

OpenAI
termcolor