# Resume Classification System

## Project Overview

This project focuses on the development of an automated Resume Classification System using Machine Learning and Natural Language Processing (NLP) techniques. The system is designed to assist in the screening process by categorizing resumes into various professional fields based on their content. This tool aims to enhance the efficiency of the recruitment process, allowing recruiters to focus on the most relevant candidates for specific job roles.

## Features

- **Automated Resume Classification**: Classifies resumes into different categories based on textual content.
- **NLP-Based Keyword Extraction**: Utilizes Named Entity Recognition (NER) to extract significant keywords from resumes.
- **Advanced Text Processing**: Employs techniques such as TF-IDF Vectorization to convert text data into a machine-readable format.
- **Interactive Web Application**: Built with Streamlit, offering a user-friendly interface for uploading and classifying resumes.
- **Robust Model Training**: Uses Logistic Regression and cross-validation to ensure reliable and consistent classification.

## Technologies Used

- **Python**: Primary programming language for model development and web app.
- **NLTK**: For natural language processing tasks.
- **Scikit-learn**: For machine learning model development and text vectorization.
- **Streamlit**: For creating the interactive web application.

## Model Development

The project encompasses several stages of development:

1. **Data Preprocessing**: Standardizing and cleaning resume data.
2. **Feature Engineering**: Extracting meaningful features using NLP techniques and one-hot encoding.
3. **Model Training and Evaluation**: Logistic Regression model trained and evaluated with cross-validation.
4. **Web Application Development**: Streamlit app for real-time resume classification.

## Getting Started

To use this project, clone the repository and install the required Python packages. Instructions for running the Streamlit app locally are included.

```bash
git clone https://github.com/StephaneWamba/resume-classification-system.git
cd resume-classification-system
pip install -r requirements.txt
streamlit run app.py

## License
This project is open source and available under the MIT License
