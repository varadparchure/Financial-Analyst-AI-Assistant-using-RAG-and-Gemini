# Financial Analyst AI Assistant using RAG and Gemini

## Overview
This project demonstrates the use of Retrieval Augmented Generation (RAG) with Google Gemini to analyze financial reports and answer domain-specific questions.  
It uses Tesla's latest 10-Q SEC filing along with live stock price data from Yahoo Finance to deliver accurate, up-to-date financial insights.  
The aim is to showcase how RAG bridges the gap between a large language model’s static knowledge and the need for grounded, real-time answers.

## What is RAG?
Retrieval Augmented Generation (RAG) is a technique that combines:
1. Retrieval — Searching relevant documents from a trusted source  
2. Augmentation — Injecting those documents into the AI’s context  
3. Generation — Producing accurate, context-aware answers  

In this project, RAG ensures the AI references actual financial filings instead of guessing.

## Key Features
- Load and parse SEC 10-Q filings  
- Store filing chunks in a Chroma vector database  
- Create embeddings using Google Gemini  
- Retrieve the most relevant sections for a given question  
- Generate grounded answers using Gemini  
- Visualize financial trends with Matplotlib and Yahoo Finance data

## Tech Stack
- Python  
- LangChain (RAG orchestration)  
- Google Gemini API (embeddings + generation)  
- ChromaDB (vector database)  
- Yahoo Finance API (stock data)  
- Matplotlib (financial charts)  

## Example Use Cases
- Financial analysis without manually searching filings  
- Automated Q&A over legal or technical documents  
- Research assistants for academia  
- Customer support over product manuals  

## Future Improvements
- Automate fetching SEC filings with API rate-limit handling  
- Extend support for multiple companies and filing types  
- Add sentiment analysis on earnings call transcripts

## License
This project is released under the MIT License.
