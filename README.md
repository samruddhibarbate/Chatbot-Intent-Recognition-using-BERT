# Chatbot-Intent-Recognition-using-BERT

This project showcases how BERT (Bidirectional Encoder Representations from Transformers) can be fine-tuned for accurately identifying customer intent from text queries. It's designed to assist customer service bots in understanding user requests like "Where is my order?" or "I want to cancel my subscription".

🧠 Key Features

Uses bert-base-uncased from Hugging Face for intent classification.

Tokenizes input using BERT’s WordPiece tokenizer.

Handles common customer intents such as tracking orders, resetting passwords, or speaking to a human.

Trained on a labeled dataset easy fine-tuning and evaluation.

Temporarily deployed using Gradio


📁 Project Files

bert_model_final.ipynb – Full notebook with training, prediction, and model-saving code.

dataset.csv – Contains labeled customer service queries.

README.md – Project overview and instructions (this file).


🚀 What It Does

The model classifies input text into intent categories by learning contextual embeddings using BERT. It's capable of understanding variations in phrasing, slang, and grammar, making it suitable for real-world usage in chatbots and automated helpdesks.

📌 Example Intents

Track_Order

Cancel_Subscription

Reset_Password

Speak_to_Agent

and 23 more...


🎯 Project Outcome

This project demonstrates how modern NLP models like BERT outperform traditional methods in understanding user intent, particularly in dynamic and informal communication settings. It serves as a foundation for intelligent chatbot systems.

⚙ Future Enhancements

Integrate a permanent chatbot interface.

Deploy the model via an API for real-time inference.

Expand the dataset with more diverse queries.


💫Thankyou for visitng our project
