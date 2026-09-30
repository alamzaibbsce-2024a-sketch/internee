# AI-Powered Interview Question Generator

## Overview

This project is a basic AI-powered interview question generator created as part of my DecodeLabs internship.

The project uses a text-generation model to generate customized technical and behavioral interview questions based on:

* Intern profile
* Job role
* Job description

## Objective

The objective of this project is to generate role-specific interview questions for interns using a text-generation model.

## Technologies Used

* Python
* Jupyter Notebook
* Hugging Face Transformers
* PyTorch
* DistilGPT-2

## Features

* Generate technical interview questions
* Generate behavioral interview questions
* Customize questions using an intern profile
* Customize questions based on a job role
* Use a job description to make questions more relevant
* Reusable Python function for generating questions

## How It Works

The user provides:

1. Intern profile
2. Job role
3. Job description

The information is added to prompts and passed to the DistilGPT-2 text-generation model.

The model then generates separate technical and behavioral interview questions.

## Project Structure

```text
Project-5-AI-Interview-Question-Generator/
│
├── interview_question_generator.ipynb
├── README.md
├── requirements.txt
└── screenshot.png
```

## How to Run

1. Install Python.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run the notebook cells from top to bottom.
5. Enter or modify the intern profile, job role, and job description.
6. Run the generator function to generate interview questions.

## Note

This is a basic educational project demonstrating text generation and prompt-based customization using a pre-trained language model.
