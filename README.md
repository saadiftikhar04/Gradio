# Gradio and Hugging Face Tutorial

I created this tutorial to show you how to build interactive web applications for machine learning models. I designed it to walk you through everything from basic text processing to creating a full AI suite using Hugging Face pipelines.

## Features

* **Basic Functionality**: I included simple text conversion tools using the Gradio Interface class.
* **Image Processing**: I demonstrated how to upload and blur images using PIL integration.
* **Advanced Layouts**: I used Rows, Columns, and Tabs to help you organize complex apps.
* **Hugging Face Integration**: I added real-time sentiment analysis and image classification using pre-trained models.

## Getting Started

To run these examples on your machine, I recommend installing these dependencies first:

```bash
pip install gradio transformers torch pillow


Tutorial Structure
Basic Interface: I started with a simple way to wrap a Python function in a web UI.

Image Handling: I showed how to work with image inputs and the PIL library.

Blocks Layout: I used the gr.Blocks API so you can create custom, side-by-side layouts.

Sentiment Analysis: I integrated a Hugging Face text pipeline for NLP tasks.

Image Classification: I used a pre-trained computer vision model to identify objects in photos.

Multi-Model Suite: I built a final app that lets you switch between text and image models using a tabbed interface.

Key Concepts Summary
Interface: This is the fastest way I found to connect a function to a UI.

Blocks: I use this system when I need more flexibility for custom layouts and event triggers.

Rows and Columns: These tools helped me place components side-by-side or stack them vertically.

Pipeline: I used this Hugging Face API because it handles model downloading and inference automatically.
