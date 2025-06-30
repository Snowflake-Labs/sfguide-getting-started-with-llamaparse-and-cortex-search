# Getting Started with LlamaParse and Cortex Search

This guide walks through how to build a RAG using LlamaParse (from LlamaIndex) to parse documents and Snowflake Cortex for text splitting, search and generation.

[LlamaParse](https://docs.llamaindex.ai/en/stable/llama_cloud/llama_parse/) is a genAI-native document parsing platform - built with LLMs and for LLM use cases. The main goal of LlamaParse is to parse and cleans your data, ensuring that it's high quality before passing to any downstream LLM use case such as RAG or agents.

In this guide, we will:

* Parse a PDF with LlamaParse
* Load the parsed data into Snowflake
* Split the text for search
* Create a Cortex Search service
* Retrieve relevant context
* Build a simple RAG pipeline for Q&A on your data

* ## Related Resources

* [LlamaParse (LlamaIndex)](https://docs.llamaindex.ai/en/stable/llama_cloud/llama_parse/)
* [Cortex Search](https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-search/cortex-search-overview)
* [Snowflake Python API](https://docs.snowflake.com/en/developer-guide/snowpark/python/index)
