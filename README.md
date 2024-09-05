# RAG-Evaluation

## Overview
This Repository Contains the Implementation of my Final Project for the Course Fundamentals of Natural Language Processing taken during the Spring 2024 Semester at the School of Computer Engineering at Iran University of Science and Technology. The project explores the concept of Retrieval-Augmented Generation (RAG), a method that enhances the capabilities of large language models by integrating retrieval-based techniques to generate more accurate and contextually relevant responses.

## Project Context

- **Course**: Introduction to Natural Language Processing (NLP)
- **Institution**: IUST Computer Engineering Department
- **Instructor**: Dr. Marzieh Davoodabadi Farahani
- **Teaching Assistant**: Erfan Moosavi Monazzah

## What is RAG?

RAG stands for Retrieval-Augmented Generation, a technique that addresses some of the limitations of Large Language Models (LLMs) such as ChatGPT. While LLMs are trained on extensive datasets, they can still produce incorrect or outdated information. RAG improves this by retrieving relevant documents or data from a large corpus based on the user's query and then generating a response using both the retrieved information and the generative model.

## Models Used

### Generator Models

The following models were used as the generator part of the RAG system:

- **TinyLlama-1.1B-Chat-v1.0** (`TinyLlama/TinyLlama-1.1B-Chat-v1.0`): A large-scale language model optimized for generating instructive and helpful content.
- **Phi-3-mini-4k-instruct** (`microsoft/Phi-3-mini-4k-instruct`): A powerful generative model designed for high-quality instruction-based responses.
- **zephyr-7b-beta** (`HuggingFaceH4/zephyr-7b-beta`): Another strong generative model focused on producing accurate and concise instructive responses.

### Evaluation Model

The outputs of the models were evaluated using:

- **bart-large-mnli** (`facebook/bart-large-mnli`): This model was employed to assess the quality and relevance of the generated responses, ensuring the outputs meet the required standards.

## Dataset Used
The project utilizes [the PubMedQA dataset](https://huggingface.co/datasets/qiaojin/PubMedQA):

## Project Structure
The project is implemented in a Jupyter notebook and includes:

1. **Introduction to RAG**: A conceptual overview of RAG, its importance, and how it compares to traditional LLMs.
2. **Setup and Installation**: Instructions for setting up the environment, including the installation of necessary Python libraries.
3. **Implementation**: Code examples demonstrating how to implement a basic RAG model using libraries like `transformers`, `sentence-transformers`, and `datasets`.
4. **Experiments and Results**: Testing the model with various queries and analyzing the results.
