# TEXT-SUMMARIZATION-TOOL

COMPANY:CODTECH IT SOLUTIONS

NAME:MANGALGI SNEHA

INTERN-ID:CTO4WT53

DOMAIN:ARTIFICIAL INTELLIGENCE

DURATION:4 WEEKS

DESCRIPTION:


This Python code demonstrates a robust and improved text summarization approach using Natural Language Toolkit (NLTK) and the Sumy library. It provides both extractive and abstractive summarization methods for 

processing input text.

- Imports and Setup:- The code imports necessary modules like nltk for tokenization, collections.Counter for counting word frequencies, and the sumy library for advanced text summarization.

- It ensures that necessary NLTK data, such as punkt (for tokenization) and stopwords, is downloaded quietly.


- Extractive Summary Function:- This function, extractive_summary, processes the text to generate a summary by ranking sentences based on word frequency.

- Using word_tokenize, it breaks text into individual words, then calculates word occurrence frequencies.

- Sentences are sorted by their collective word scores, and the top-ranked sentences are returned to form the summary.


- Abstractive Summary Function:- The abstractive_summary function utilizes Sumy's LsaSummarizer for latent semantic analysis-based summarization.


- Input text is parsed with PlaintextParser and tokenized.

- The summarizer condenses the content into fewer sentences, offering a higher-level abstraction compared to the extractive method.

- It incorporates error handling to manage failures gracefully and ensure user-friendly feedback.

- Text Validation and Workflow:- The summarize_text function validates input by checking the text length (minimum 50 words) to ensure meaningful summarization.

- It combines the extractive and abstractive summaries into a dictionary output format.

- If the text is too short, it provides an appropriate error message.


- Main Example:- A sample text on natural language processing (NLP) and its applications is summarized using both methods.

- Outputs include key points about NLP, its challenges, and applications like machine translation and text summarization.

- OUTPUT:

- 



