# Wikipedia Bot

## Overview

This repository contains a simple Wikipedia bot that utilizes the Wikipedia library, scikit-learn (sklearn), and NLTK (Natural Language Toolkit). The bot is designed to provide information on a specific subject, as requested by the user.

## How It Works

1. You provide a subject to the bot.
2. The bot asks the user, "What do you want to know about the {subject}?"
3. It then uses the Wikipedia library to fetch relevant information.
4. The bot provides the user with the answer to their question.

## Prerequisites

Before you can run the Wikipedia bot, make sure you have the following libraries installed:

- [Wikipedia library](https://pypi.org/project/wikipedia-api/)
- [scikit-learn](https://scikit-learn.org/stable/install.html)
- [NLTK (Natural Language Toolkit)](https://www.nltk.org/install.html)

## Usage

1. Clone this repository to your local machine.
2. Install the required libraries using the links provided in the "Prerequisites" section.
3. Run the bot script.
4. Provide a subject when prompted.
5. Ask the bot a question about the subject, and it will provide you with information from Wikipedia.

## Example

```python
python wikipedia_bot.py
# Bot: Please provide a subject:
# User: Elephants
# Bot: What do you want to know about elephants?
# User: How much do elephants weigh?
# Bot: Elephants can weigh up to 12,000 pounds.
```

## License

This project is licensed under the MIT License. You are free to use and modify the code for your own purposes.

