# Human-Like Text Summarization Model

This repository contains the implementation of a custom text summarization model designed to generate human-like summaries. The model is fine-tuned on the SAMsum dataset, which is specifically crafted for training conversational agents to produce human-style text summaries.

## Project Overview

### 1. Custom Text Summarization Model
- **Model Architecture**: This project leverages a pre-trained Flan-T5 language model (LLM) as the base architecture. The model is fine-tuned on the SAMsum dataset to enhance its ability to generate concise and coherent summaries that closely replicate human-style writing.

### 2. SAMsum Dataset Utilization
- **Dataset Details**: The SAMsum dataset consists of a collection of dialogues and their corresponding summaries, making it ideal for training models to summarize conversations and textual data in a human-like manner.
- **Fine-Tuning Process**: The Flan-T5 model was fine-tuned on the SAMsum dataset to adapt the pre-trained language model to the specific task of text summarization. This fine-tuning process involved adjusting the model weights to better capture the nuances of human-written summaries.



## Getting Started

### Prerequisites

- Hugging Face Transformers library
- ROUGE evaluation package
- SAMsum dataset
