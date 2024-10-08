# AI-Statement-correctness-checker
An application that automates the process of identifying and validating correct statements from ppt/pdf files using advanced Natural Language Processing (NLP) techniques, including MPNet(from BERT family) and GPT models.

This project provides a tool to check the correctness of statements against text extracted from PPT or PDF files using mpnet (Sentence Transformer) and GPT models.

## Project Structure
- [main.py](https://github.com/amina042297/AI-Statement-correctness-checker/blob/main/main.py) - Main entry point for the Streamlit application
- [functions.py](https://github.com/amina042297/AI-Statement-correctness-checker/blob/main/functions.py) -  functions for text processing and statement checking
- [gpt_utils.py](https://github.com/amina042297/AI-Statement-correctness-checker/blob/main/gpt_utils.py) -  Functions related to GPT-4
- [requirements.txt](https://github.com/amina042297/AI-Statement-correctness-checker/blob/main/requirements.txt) - Python dependencies required to run the project
- [__init__.py](https://github.com/amina042297/AI-Statement-correctness-checker/blob/main/__init__.py) - Marks the directory as a package



## Setup Instructions

- Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate 

- Install the required dependencies:

pip install -r requirements.txt

- Run the Streamlit application with the following command:

streamlit run main.py

- in Streamlite application you can upload ppt/pdf documents, write statements to check.

# [This presentation includes summary of the project](https://github.com/amina042297/AI-Statement-correctness-checker/blob/main/Term%20Project%20Presentation.pdf)
