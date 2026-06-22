# Task-1-Areej-Hafeez
----------------------------------------------
## Overview

This project focuses on using Prompt Engineering techniques to extract product information from text and convert it into a structured JSON format.

The goal is to make the AI understand unstructured product descriptions and return important details such as product name, brand, price, category, and key features.

## What I Learned
----------------------------------------------
* Zero-Shot Prompting
* Few-Shot Prompting
* Output Formatting
* Structured Data Extraction
* Handling Missing Information
* Prompt Evaluation

## Project Tasks

### 1. Zero-Shot Prompting

The model was given instructions only and asked to extract product information without any examples.

### 2. Few-Shot Prompting

The model was provided with examples before the actual task to improve extraction accuracy and consistency.

### 3. Edge Case Handling

The prompts were designed so that missing information is returned as `null` instead of making guesses.

### 4. Evaluation

The model was tested on different product descriptions, including incomplete and noisy inputs, to check its reliability.

## Output Format

```json
{
  "product_name": "",
  "brand": "",
  "price": null,
  "category": "",
  "key_features": ""
}
```

## Skills Used

* Prompt Engineering
* Zero-Shot Learning
* Few-Shot Learning
* Information Extraction
* JSON Formatting
* LLM Evaluation

