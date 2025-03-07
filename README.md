# AI Resume Screening App

This Streamlit application allows users to screen resumes based on a provided job description. Users can upload multiple PDF resumes, and the app will extract text from each resume, rank them according to their relevance to the job description, and display the results along with a snippet of each resume.

## Features
- Upload multiple PDF resumes.
- Input a job description for screening.
- Rank resumes based on cosine similarity to the job description.
- Display scores and snippets of the resumes for quick review.

## Usage
1. Enter the job description in the text area.
2. Upload one or more PDF resumes.
3. Click "Submit" to view the ranked results.

## Requirements
- Streamlit
- PyPDF2
- pandas
- scikit-learn

To run the app, install the required packages and execute the Streamlit app using the command:
streamlit run app.py
