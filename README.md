# prompt-engineering-chatbot


# Building a Simple OpenAI Chatbot in Google Colab

This project is a beginner-friendly notebook that shows how to build a simple chatbot using the OpenAI API in Google Colab.

## What this project covers

- installing the OpenAI Python SDK
- setting up an API key in Colab
- sending a first prompt to an LLM
- understanding basic prompt engineering
- building a simple multi-turn chatbot with chat history

## Why this project matters

This notebook is meant to help understand the engineering behind a basic LLM application.

It demonstrates the core flow:

**user input -> prompt/message history -> OpenAI API request -> model response -> stored conversation state**

## Files

- `Ai_chatbot_commented.ipynb` — the main Colab notebook with explanations and comments
- `README.md` — project overview and usage instructions

## Notebook sections

1. Install the OpenAI SDK  
2. Set the API key  
3. Create the OpenAI client  
4. Make the first API call  
5. Learn intro prompt engineering  
6. Build a simple chatbot  
7. Test multi-turn conversation  

## How to run

1. Open the notebook in Google Colab
2. Run the install cell
3. Replace the API key placeholder with your real OpenAI API key
4. Run the cells in order
5. Ask follow-up questions using the `chat(...)` function

## Important security note

Do not upload a real API key to GitHub.

Before pushing this notebook to a public repository:

- replace the key with a placeholder like `"your_api_key_here"`
- optionally clear notebook outputs
- double-check that no secrets are stored in the notebook

## Example learning outcomes

After completing this notebook, you should understand:

- how a Python app calls an LLM through an API
- how prompt engineering affects model behavior
- how conversation history is managed in code
- why chatbots need to resend previous messages for context

## Suggested repository names

- `understanding-llms`
- `openai-chatbot-colab`
- `llm-chatbot-basics`
- `intro-to-llm-chatbots`

## Future improvements

You can extend this project by adding:

- streaming responses
- error handling
- token usage management
- system prompt customization
- Gradio or Streamlit UI
- retrieval-augmented generation (RAG)

## License

This project is for learning and experimentation.
