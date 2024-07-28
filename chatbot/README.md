# End-to-End-Chatbot-using-Python

An end-to-end chatbot implemented in Python using Streamlit, scikit-learn, and NLTK. The chatbot is designed to respond to various user inputs and provide information or assistance on different topics.

## Installation

Ensure you have Python installed. Clone the repository and install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To run the chatbot, execute the following command:

```bash
streamlit run ChatBot.py
```

This will launch the chatbot interface in your web browser. Type messages in the input box, and the chatbot will respond accordingly.

## Chatbot Features

- **Greeting:** Responds to greetings such as "Hi," "Hello," and "Hey."
- **Goodbye:** Provides farewell messages like "Goodbye" and "See you later."
- **Thanks:** Expresses gratitude in response to phrases like "Thank you" and "Thanks."
- **About:** Offers information about itself when asked, e.g., "Who are you?"
- **Help:** Assists and asks for clarification when the user needs help.
- **Age:** Playful responses to questions about its age.
- **Weather:** Explains its inability to provide real-time weather information and suggests checking weather apps.
- **Budget:** Gives advice on creating a budget, tracking income, and using the 50/30/20 rule.
- **Credit Score:** Defines a credit score and advises on checking and improving it.

## Model Training

The chatbot uses a logistic regression classifier trained on TF-IDF vectors of user input patterns.

