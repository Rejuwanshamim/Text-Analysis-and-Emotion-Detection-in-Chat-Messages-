# Text-Analysis-and-Emotion-Detection-in-Chat-Messages-
This project focuses on analyzing text data, particularly chat messages, to extract insights related to sentiment, message types, and emotional content. It employs Natural Language Processing (NLP) techniques to better understand the underlying sentiments and emotions expressed in text, which can be useful in various applications such as chatbot development, customer feedback analysis, and social media sentiment analysis.

The process begins with text pre-processing, which involves converting the text to lowercase, removing punctuation, and eliminating common stopwords to clean the text data. This clean text is then subjected to sentiment analysis using the VADER (Valence Aware Dictionary and sEntiment Reasoner) tool, which assigns a sentiment score to each message. The sentiment score classifies each message as positive, negative, or neutral based on the compound score.

Additionally, the project categorizes messages into different types: questions, exclamations, or statements. It identifies the primary emotional content within the text, such as happiness, sadness, anger, excitement, fear, disgust, surprise, love, or hate. This multi-faceted analysis provides a comprehensive understanding of the text's underlying characteristics.

The main script reads chat messages from a file named "chat.txt" and analyzes them. It then presents the results in terms of sentiment categories, message types, and emotional content. Furthermore, it visualizes the distribution of emotions in a bar chart, making it easier to grasp the emotional context of the text.

This project is a valuable tool for businesses and organizations seeking to gain insights from unstructured text data, allowing them to understand customer sentiments and tailor their services accordingly. It also has applications in the field of chatbots and AI-driven customer support systems.
