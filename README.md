Project Summary
This chatbot application allows users to interact with a simple bot that can:

Respond to greetings and farewells.
Retrieve information from Wikipedia based on user input.
Perform sentiment analysis on text input.
Utilize NLTK for natural language processing (tokenization, lemmatization).
Implement TF-IDF for generating responses based on similarities to pre-stored text data.
Key Features
Welcome Response: It responds to basic greetings such as "hello", "hi", etc.
Wikipedia Integration: If the user asks for information like "Tell me about X", the chatbot retrieves a summary of the topic from Wikipedia.
Sentiment Analysis: Analyzes whether a user's statement is positive, negative, or neutral using VADER.
Response Generation: Uses TF-IDF vectorization to determine the best response from pre-defined data.
Python Packages Used
nltk: For natural language processing tasks such as tokenization, stemming, and sentiment analysis.
sklearn: Used for TF-IDF vectorization and cosine similarity for response generation.
wikipedia: Fetches topic summaries from Wikipedia.
