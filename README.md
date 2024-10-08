# mentalhealth_chatbot

This project is a Mental Health Chatbot application built using Python, which provides users with a conversational interface to ask questions related to mental health. The chatbot is powered by a TF-IDF vectorizer and cosine similarity to find the most relevant responses from a pre-defined dataset of questions and answers.

Key features of the project include:

User Authentication: Users can log in or register for a new account using a graphical interface built with Tkinter, which connects to an SQLite database to manage user credentials.
Natural Language Processing: The chatbot processes user queries using lemmatization and stopword removal, enabling it to understand and respond more accurately.
Chat Interface: The chatbot interface allows users to interact in a chat-like environment, where they can type questions, receive answers, and even exit the chat.
Dataset Integration: The chatbot's responses are generated by comparing user queries with a merged dataset from multiple CSV files containing mental health-related questions and answers.
This project aims to provide a helpful and accessible tool for users seeking information or support on mental health topics, leveraging machine learning techniques to deliver relevant and accurate responses.
