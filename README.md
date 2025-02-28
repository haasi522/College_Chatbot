SVECW College Chatbot 🎓

Overview

The SVECW College Chatbot is an AI-powered chatbot built with Streamlit that helps users get information about the college. It uses a CSV database to find the closest matching answers to user queries and, if no match is found, generates responses using Google's Gemini AI.

Features

Interactive Chat Interface: Users can ask questions and get instant responses.

CSV-Based Q&A Matching: Finds the best answer from a dataset of frequently asked questions.

AI-Powered Responses: Uses Google's Gemini AI to generate answers when no match is found.

User-Friendly UI: Built with Streamlit for an easy-to-use interface.

Technologies Used

Python

Streamlit

Pandas

Google Generative AI (Gemini-1.5-Flash)

Scikit-learn (TF-IDF & Cosine Similarity)

Usage

Start the chatbot using streamlit run chatbot.py.

Type your queries in the chat input box.

If a match is found in the CSV, it will respond with a predefined answer.

If no match is found, it will use Gemini AI to generate an answer.

sample:
  <img width="659" alt="image" src="https://github.com/user-attachments/assets/8d27cd82-d393-4ae0-8c49-227b6015d96f" />
