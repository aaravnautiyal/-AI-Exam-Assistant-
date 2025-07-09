This model is to be used locally for summarizing of ppts/pdfs and generation of questions to help students for their exams. This model can be used for any locally setup LLM using Ollama, I have used Mystral for
precise reasoning and detailed summaries.

Python, Mistral 7B via Ollama, PyMuPDF, python-pptx, REST APIs

Features -
  -Developed a local AI assistant that summarizes content from academic PDFs and PowerPoint files, and generates relevant exam-style questions using a locally hosted Mistral 7B model via Ollama.
  -Built an automated pipeline combining PyMuPDF and python-pptx for extracting structured text from multi-format documents.
  -Implemented intelligent text chunking and prompt engineering to comply with token limits, ensuring consistent LLM inference.
  -Designed REST-based prompt interface to stream prompts to the Mistral model locally without relying on external APIs or exposing data.
  -Outputted organized summaries and questions into .txt files, simulating a fully offline, privacy-first academic assistant.

