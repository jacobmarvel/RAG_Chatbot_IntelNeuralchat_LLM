## RAG Chatbot Using Intel's Neural Chat LLM
## Overview
This README provides guidance on setting up a Retrieval-Augmented Generation (RAG) Chatbot leveraging Intel's Neural Chat Large Language Models (LLM). The RAG Chatbot combines the strengths of retrieval-based and generative AI models to deliver highly informative and contextually relevant responses, making it a cutting-edge solution for natural language processing applications.

## Features
Integration with Intel's Neural Chat LLM for state-of-the-art performance.
Dynamic response generation combining retrieved information with generative capabilities.
Customizable query and response formats for diverse application needs.
## Setup and Installation
- Create a folder called "Data" in the repo and download the data from the given link
- and keep inside the folder "https://drive.google.com/file/d/1qw0hs9rHAMfPZzgnv7CLN9W-ZY1Aj0Wc/view?usp=sharing"
```
create conda -= venv python==3.9 -y
conda activate venv/
pip install -r requirements.txt
python main.py
```
There should not be a folder called stores/medical_cosine, after running this command, python main.py it will make a directory there.
```
python app.py
```
You will direct to a localhost, where you can see your chatbot

