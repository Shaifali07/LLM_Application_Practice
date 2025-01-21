This repository contains various practice examples for llm applications.

1) English assistant:
    This example demonstrates how to use the PromptTemplate from LangChain to generate dynamic prompts for getting the meaning, translation, and synonyms of a word. You can input a word and a language, format the template, and invoke a language model to generate the response.
    Input: A word (e.g., "journey") and a language (e.g., "Hindi").
    Output: The meaning of the word, its translation into the specified language, and synonyms in English.
2) Sentiment Classification with Few-Shot Learning
This project uses Langchain's FewShotPromptTemplate to classify the sentiment of user reviews based on a set of predefined examples. The prompt template formats the input review and invokes an LLM for sentiment classification. Customize the examples and input to classify other reviews.
3) Employee Assistant
This project uses Langchain's LLMChain in combination with Groq to automate the generation of formal email responses based on various workplace issues. It leverages prompt templates and large language models to streamline communication tasks.
