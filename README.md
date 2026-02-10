# TOPSIS_FOR_PRETRAINED_MODELS
## Overview
This project focuses on selecting the best pre-trained conversational AI model using the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) multi-criteria decision-making method.

Conversational AI models are widely used in chatbots, virtual assistants, and daily communication systems. Since multiple models exist with different strengths and weaknesses, selecting the most suitable model requires evaluation based on multiple parameters.

## Objective
- Evaluate multiple conversational AI models
- Compare performance using multiple criteria
- Rank models using TOPSIS
- Visualize comparison using graphs

## Domain Selected
* General Daily Conversation
   This domain includes:
   - Greetings
   - Casual chatting
   - General daily queries
   - Small talk
It represents real-world chatbot applications.

## Conversational Models Compared
- DialoGPT (Microsoft)
- BlenderBot (Meta)
- GPT-2 (OpenAI)
- DistilGPT2
- T5 Small (Google)

## Evaulation Parameters

| Parameter | Description | Impact | Range |
|------------|----------------|------------|-------------|
| Relevance | Accuracy of generated response with respect to user input | Positive (+) | 1 – 10 |
| Context Maintenance | Ability to preserve conversation continuity | Positive (+) | 1 – 10 |
| Fluency | Naturalness and grammatical correctness of response | Positive (+) | 1 – 10 |
| Response Time | Time required to generate response | Negative (-) | 100 – 500 ms |
| Memory Usage | Computational resource consumption of model | Negative (-) | 100 – 2500 |

## Methodology
Step 1: Model Response Generation

Each conversational model generates responses to daily conversation prompts.

Step 2: Performance Measurement

Metrics such as response quality, response time, and memory usage are collected.

Step 3: TOPSIS Implementation

TOPSIS ranks models based on:

Distance from ideal best solution

Distance from ideal worst solution

Step 4: Model Ranking

Models are ranked using TOPSIS score.

## Output
- Graph

  <img width="453" height="360" alt="image" src="https://github.com/user-attachments/assets/a04255f0-7b08-486e-976f-400a699db2e7" />
  
- Result file

  <img width="873" height="109" alt="image" src="https://github.com/user-attachments/assets/c855317e-9a02-43d8-bf18-9f7ce724aef3" />

