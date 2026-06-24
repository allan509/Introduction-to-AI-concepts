# Introduction to AI Concepts

A collaborative guide by **Allan, Mary, Francis, Sarah, Wambui, and Simon**.

## Table of Contents
 1. Introduction
 2. Machine-learning
 3. Neural Networks
 4. Natural language processing_NPL
 5. Convolutional Neural Networks (CNN)
 6. Deep learning
 7. Large Language Models (LMM)
 

## Introduction (24/06/2024), edited 
From Netflix's personalized movies and shows to voice assistants such as Siri and Alexa, Artificial Intelligence (AI) seems to be revolutionizing the world around us. This is a co-created guide that facilitates the understanding of the three core concepts of AI which include,
1. Machine Learning
2. Neural Network
3. Natural Language Processing (NLP)
4. Deep learning
5. CNN
6. LLM

At the completion of this guide, I should have a strong grasp of the fundamental concepts that are the backbone of the current wave of AI innovation.
## Machine Learning
Machine learning is a subset of artificial intelligence that enables computer systems to learn fron data and identify patterns autonomously. It is divided into supervised learning, unsupervised learning, semi-supervised learning and reinforcement learning. In fraud detection, banks use machine learning to scan millions of credit card transactions per second, instantly flagging unusual purchases to prevent fraud.


## Neural Networks

### Neural Networks and How They Work

Neural networks are a type of Artificial Intelligence (AI) inspired by the human brain. They help computers learn patterns and make decisions from data.

### A neural network has three main parts:

Input Layer – Receives information such as images, numbers, or text.
Hidden Layers – Processes the information by finding patterns and relationships.
Output Layer – Produces the final result or prediction.

### How neural networks work:

Data is entered into the input layer.
The hidden layers analyze the data using mathematical calculations.
The network makes a prediction.
The prediction is compared with the correct answer.
Errors are calculated and the network adjusts itself to improve accuracy.
This process repeats many times until performance improves.

### Example:
If a neural network is trained to recognize cats, it studies thousands of images and learns features like ears, eyes, and shapes until it can identify a cat correctly.

### Neural networks are used in:

Image recognition
Speech recognition
Chatbots
Recommendation systems
Self-driving cars
Medical diagnosis

Neural networks are a major part of machine learning and modern AI systems 
24/06/2026.


## Natural Language Processing (NLP)

Natural Language Processing (NLP) is a branch of Artificial Intelligence that enables
computers to understand, interpret, and generate human language in a meaningful way.
It sits at the intersection of linguistics, computer science, and machine learning.

### How NLP Works

NLP systems process text or speech through a pipeline of steps:

1. **Tokenization** – Breaking text into smaller units (words, sentences, or subwords).
2. **Part-of-Speech Tagging** – Identifying whether each word is a noun, verb, adjective, etc.
3. **Parsing** – Analysing the grammatical structure of sentences.
4. **Semantic Analysis** – Extracting the meaning behind the words.
5. **Pragmatic Analysis** – Understanding context and intent.

### Key NLP Tasks

- **Sentiment Analysis** – Determining whether text expresses positive, negative, or neutral emotion.
- **Machine Translation** – Automatically translating text between languages (e.g., Google Translate).
- **Named Entity Recognition (NER)** – Identifying names of people, places, and organisations in text.
- **Text Summarisation** – Condensing long documents into shorter summaries.
- **Question Answering** – Systems that respond to queries in natural language (e.g., chatbots).
- **Speech Recognition** – Converting spoken language into text.

### Popular NLP Tools & Libraries

| Library | Language | Use Case |
|---|---|---|
| NLTK | Python | Teaching & research |
| spaCy | Python | Production NLP pipelines |
| Hugging Face Transformers | Python | State-of-the-art models |
| Stanford NLP | Java/Python | Academic research |

### Real-World Applications

NLP powers many technologies we use daily:
- **Virtual assistants** like Siri, Alexa, and Google Assistant
- **Email spam filters** that classify unwanted messages
- **Grammar checkers** like Grammarly
- **Search engines** that understand query intent
- **AI chatbots** like Claude and ChatGPT

### Challenges in NLP

Human language is complex. NLP systems must grapple with:
- **Ambiguity** – "I saw the man with the telescope" (who has the telescope?)
- **Sarcasm & irony** – Hard to detect without context
- **Multilingualism** – Thousands of languages, many with limited training data
- **Evolving language** – Slang, neologisms, and cultural references change over time

### The Role of Transformers

Modern NLP is dominated by **transformer-based models** (introduced in the 2017 paper
*"Attention Is All You Need"*). Models like BERT, GPT, and T5 learn language patterns
from vast amounts of text, enabling remarkable performance across nearly all NLP tasks.

NLP is one of the fastest-moving fields in AI, with new breakthroughs emerging regularly —
making it an exciting area for both researchers and practitioners.

## Convolutional Neural Networks
<!-- [Wambui] will write this section -->

## Deep Learning
Deep learning is a branch of AI that teaches computers to learn patterns from data using structures called neural networks.
Basically,Deep learning teaches computers to learn from examples instead of being explicitly programmed.

### How Deep Learning Learns
Suppose we want to predict house prices.
Step 1: Feed data
Size → 1200
Bedrooms → 3
Location → Urban
↓
Prediction:$60,000
Actual:$75,000
Error:15,000
↓
The model adjusts itself.

↓

Repeats thousands of times.

This process is called:

Forward Propagation;Make prediction
Loss Function;Measure error
Backpropagation;Learn from error
Gradient Descent;Update weights

## Large Language Models

These are advanced computer programs designed to understand, process, and generate human language. They are trained on vast amounts of text data, enabling them to perform tasks such as answering questions, summarizing information, translating languages, and generating written content. LLMs are a subset of Artificial Intelligence (AI), specifically within the fields of Machine Learning (ML) and Natural Language Processing (NLP). They contribute to AI by allowing machines to communicate with humans in a natural and meaningful way.
Some common examples of Large Language Models include ChatGPT, Gemini, and Claude. ChatGPT, developed by OpenAI, is widely used for answering questions, assisting with learning, content creation, and programming support. Gemini, developed by Google, helps users with research, writing, problem-solving, and information retrieval. Claude, developed by Anthropic, is designed to assist with document analysis, customer service, and professional workplace tasks.
In real-life applications, LLMs are used in virtual assistants, customer support chatbots, educational platforms, language translation services, and content-generation tools. These applications help individuals and organizations improve productivity, access information quickly, and communicate more effectively.

