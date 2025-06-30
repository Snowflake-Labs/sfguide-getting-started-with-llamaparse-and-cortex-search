# Getting Started with LlamaParse and Cortex Search

## Overview

This guide walks through how to build a RAG using LlamaParse (from LlamaIndex) to parse documents and Snowflake Cortex for text splitting, search and generation.

[LlamaParse](https://docs.llamaindex.ai/en/stable/llama_cloud/llama_parse/) is a genAI-native document parsing platform - built with LLMs and for LLM use cases. The main goal of LlamaParse is to parse and clean your data, ensuring that it's high quality before passing to any downstream LLM use case such as RAG or agents.

In this guide, we will:

* Parse a PDF with LlamaParse
* Load the parsed data into Snowflake
* Split the text for search
* Create a Cortex Search service
* Retrieve relevant context
* Build a simple RAG pipeline for Q&A on your data

## Step-By-Step Guide

For prerequisites, environment setup, step-by-step guide and instructions, please refer to the [QuickStart Guide](https://quickstarts.snowflake.com/guide/getting-started-with-llamaparse-and-cortex-search/index.html).
