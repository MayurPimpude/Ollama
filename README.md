# Ollama in Colab using Phi3 and RAG Model with Gemma 2

Welcome to the Ollama project in Colab! This repository contains instructions for using Phi3 with Ollama and training a Retrieval-Augmented Generation (RAG) model using Gemma 2. We also use RAGAS for evaluation, achieving the following results: `context_precision: 0.7917`, `faithfulness: nan`, `answer_relevancy: 0.8104`, `context_recall: 1.0000`.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Using Phi3 with Ollama](#using-phi3-with-ollama)
- [Training RAG Model using Gemma 2](#training-rag-model-using-gemma-2)
- [Evaluation using RAGAS](#evaluation-using-ragas)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

This project aims to demonstrate the use of Phi3 with Ollama in a Colab environment, followed by training a Retrieval-Augmented Generation (RAG) model using the Gemma 2 dataset. Finally, we evaluate the model's performance using RAGAS, reporting key metrics such as context precision, faithfulness, answer relevancy, and context recall.

## Setup

To get started, follow these steps to set up your Colab environment:

1. Open Colab and create a new notebook.
2. Ensure you have the required libraries installed: `ollama`, `transformers`, `datasets`, and `ragas`.

## Using Phi3 with Ollama

To use Phi3 with Ollama, follow these steps:

1. Import the necessary libraries.
2. Load the Phi3 model and tokenizer.
3. Use the model for text generation.

## Training RAG Model using Gemma 2

To train a RAG model using the Gemma 2 dataset, follow these steps:

1. Load the Gemma 2 dataset.
2. Initialize the RAG model and tokenizer.
3. Train the RAG model.

## Evaluation using RAGAS

To evaluate the model's performance using RAGAS, follow these steps:

1. Import the RAGAS evaluation library.
2. Evaluate the model and review the results.

## Results

The evaluation results for the model are as follows:
- `context_precision: 0.7917`
- `faithfulness: nan`
- `answer_relevancy: 0.8104`
- `context_recall: 1.0000`

## Contributing

We welcome contributions to improve this project! Please submit pull requests or open issues to discuss potential enhancements or bug fixes.

