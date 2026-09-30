# Generative AI API Playground

A hands-on exploration of modern Generative AI APIs and LLM-based applications using Python.

## Overview

This repository contains a single Python implementation demonstrating practical use cases of Generative AI APIs, including:

* Email Summarization
* AI Personal Assistant
* Text Generation
* Image Generation
* Multimodal AI with text and image inputs
* API-based interaction with Large Language Models

## APIs & Platforms Explored

### OpenAI API

OpenAI provides APIs for text generation, image understanding, image generation, tool use, and multimodal applications.

This project explores:

* Responses API
* Text generation
* Email summarization
* AI personal assistant
* Image generation
* Image-based input

### Anthropic Claude

Claude is Anthropic's family of large language models. Its API can be used for conversational AI, reasoning, text generation, and other LLM applications.

### Groq

Groq provides fast inference APIs for supported large language models. Its API follows an OpenAI-compatible chat-completion style interface for many use cases.

## Concepts Covered

* Large Language Models (LLMs)
* Generative AI
* Prompt Engineering
* API-based AI Applications
* Text Generation
* Summarization
* Multimodal AI
* Image Generation
* Model APIs

## Project Structure

```text
Generative-AI-API-Playground/
│
├── open_ai_api.py
└── README.md
```

## Setup

Install the required OpenAI package:

```bash
pip install openai
```

Set your API key as an environment variable:

```bash
OPENAI_API_KEY=your_api_key
```

Never hardcode API keys directly inside the source code.

## Example Use Cases

### 1. Email Summarizer

Takes an email as input and generates a concise summary containing the important information.

### 2. AI Personal Assistant

Uses an LLM with custom instructions to answer questions and assist with everyday tasks.

### 3. Image Generation

Generates an image from a natural-language prompt using an image-generation model.

### 4. Multimodal Input

Allows text and image information to be provided together so the model can understand and respond to visual content.

## Learning Objective

The purpose of this repository is to understand how modern AI applications communicate with LLM APIs and how the same API concepts can be used to build practical Generative AI applications.

## Technologies

* Python
* OpenAI API
* Large Language Models
* Generative AI
* REST APIs
* Prompt Engineering
