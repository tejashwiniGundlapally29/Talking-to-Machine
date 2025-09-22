# Talking to a Machine: Image Question Answering

**Talking to a Machine** is a project that enables machines to understand both images and natural language questions about them. The system takes an image and a related question, then generates an answer by combining computer vision and natural language processing techniques.

---

## Project Overview

It started with a question: *how can machines understand both what they see and what we ask about it?*  

This project builds a system that:

1. Extracts visual features from an image.
2. Encodes a natural language question.
3. Generates a context-aware answer.

By combining **CNNs for vision** and **LSTMs for language**, the model connects pixels with words, bridging the gap between images and text.

---

## CNN + LSTM Architecture

### Purpose & Approach
- **Vision**: Image features are extracted using **VGG16**, a pre-trained Convolutional Neural Network (CNN).  
- **Language**: Questions are encoded using **embeddings** and **LSTMs** (Long Short-Term Memory networks).  
- **Answer Generation**: The combined features predict answers one word at a time, learning context through sequence modeling.

---

## Key Features

- Image feature extraction with **VGG16 CNN**  
- Language encoding with embeddings and **LSTMs**  
- Sequence-based word prediction for generating answers  
- End-to-end pipeline: **image + question → answer**

---

## Why LSTMs?

Dense networks fail to capture meaning because words depend on their neighbors. **LSTMs** solve this by:

- Maintaining memory cells to store long-term dependencies  
- Using gates to control the flow of information  
- Producing more contextually meaningful answers

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/tejashwiniGundlapally29/Talking-to-Machine.git
