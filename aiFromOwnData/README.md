# Using own data with Gen AI (E.g. Chat GPT)

Using the RAG approach create prompts form our own data and 'ask' GenAI to respond with written answer.

## Retrieval-Augmented Generation (RAG)

Retrieval-Augmented Generation (RAG) is an AI technique that enhances large language models (LLMs) by allowing them to access and incorporate external knowledge bases, improving the accuracy and relevance of their responses

### Approach

- Get user question
- Use a 'vector' search to get a collection of documents that is a good fit for the question
- Create a 'prompt', see below
- Feed prompt and return response to user

### Prompt

Rough idea is :

```:python
llm_prompt = f"Summarize these documents to answer the question.\n\nQuestion: {user_prompt}\nDocuments: {vector_response_documents}."
```

Maybe we need to also add to the prompt other aspects like 'industry/context'
