Text Summarization with Hugging Face and Gradio
Overview
This project demonstrates how to use the Hugging Face Transformers library for text summarization, integrated with the Gradio library to provide an interactive web interface.

Purpose
The purpose of this project is to showcase the capabilities of the Hugging Face text-to-text pipeline for summarization and to provide an interactive way for users to experiment with text summarization via a web interface. 

Main Files
Hugging_Face_Text_to_Text_Pipeline.ipynb: A notebook demonstrating the integration of Hugging Face's text-to-text pipeline without Gradio. 
requirements.txt: Lists the required Python packages (transformers and gradio) for running the project.
README.md: This file, which provides an overview of the project, instructions, and other relevant information.
How the Hugging Face Text-to-Text Pipeline Works
Loading the Model: The Hugging Face Transformers library provides pre-trained models for various NLP tasks. In this project, we use the facebook/bart-large-cnn model for summarization.

Summarization Function: The text-to-text pipeline takes an input text and generates a summary. The summarization function uses the pre-trained model to produce concise summaries.

Gradio Interface: The Gradio library creates a web-based interface that allows users to interact with the summarization function. Users can input text into the interface and receive a summarized version in real-time.


The notebook includes a Gradio interface that will be launched automatically when you run the relevant cell. Follow the prompts to enter text and receive summaries.

Expected Output from the Gradio Interface:
When using the Gradio interface, you should see:

Input Field: A text box where you can enter or paste your text.
Output Field: The summarized version of the input text, generated by the model.
For example, if you input a long paragraph, the interface will display a concise summary based on the model's output.




