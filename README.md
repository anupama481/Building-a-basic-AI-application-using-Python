AI Chatbot: A Basic AI Application Using Python


This project demonstrates the creation of a simple AI chatbot using Python and the Natural Language Toolkit (NLTK). The chatbot acts as a conversational agent, responding to user inputs based on predefined rules and patterns. It is designed for beginners who want to explore AI and chatbot development.

Features
Text Preprocessing: Utilizes tokenization, lowercase conversion, and stopword removal for better understanding of user inputs.
Interactive Functions:
Greets users upon starting the chat.
Captures and uses the user's name during the conversation.
Responds to queries using keyword-based patterns.
Continues chatting until the user types "exit."
Predefined Responses: Handles simple queries like greetings or questions (e.g., "Which is the best US state?").
Structure
The project is divided into functional components:

preprocess_text(): Cleans and prepares user input.
greet(): Welcomes the user.
get_user_name(): Captures the user’s name.
respond_to_input(): Processes input and generates responses.
Chat(): Orchestrates the chatbot's flow until the conversation ends.
Output Example
Greets the user and asks their name.
Responds with relevant messages or predefined answers.
Ends the chat gracefully upon request.
