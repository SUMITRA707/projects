AI-Powered Resume Screening Tool
Objective:
Automate the process of parsing and ranking resumes based on how well they match a
given job description.
Tech Stack:
Python, NLP (spaCy, TF-IDF), Streamlit, cosine similarity, pandas
Description:
This project uses Natural Language Processing to extract relevant information from
resumes like skills, experience, and education. It compares each resume to a job
description using cosine similarity and TF-IDF vectors, ranking candidates based on their
relevance. A clean Streamlit web interface allows HR users to upload multiple resumes
and get an instant ranked list of candidates.
Key Features:
Resume parser using spaCy
Job description-matching logic with TF-IDF + cosine similarity
Web UI to upload PDFs and see candidate rankings
Export ranked results to Excel/CSV
Use Case:
Used by HR or recruiters to save time on manual resume screening and shortlisting.
