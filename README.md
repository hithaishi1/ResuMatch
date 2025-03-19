# ResuMatch: Smart Resume Parser & Job Fit Analyzer

1. Description:
This project aims to develop a browser extension that automatically analyzes a user's resume when they open a job application form. Unlike conventional resume parsers, our system goes beyond keyword matching by identifying related tools and technologies that align with job requirements. Additionally, it suggests job roles based on the candidate’s skills and experience, helping users discover suitable opportunities.

2. Dataset:
Resume Datasets: 
https://www.kaggle.com/datasets/saugataroyarghya/resume-dataset
https://www.kaggle.com/datasets/jithinjagadeesh/resume-dataset
Job Descriptions: Collected from job boards like LinkedIn, Glassdoor, and Indeed using web scraping techniques.

3. Methodology and Expected Results:
Preprocessing & Feature Extraction: Tokenization, Named Entity Recognition (NER) for extracting skills, job titles, and experience. Semantic similarity models (BERT, SBERT) to find related tools and technologies.
Resume-Job Matching: Use TF-IDF and word embeddings (Word2Vec, FastText) to compute similarity between resumes and job descriptions. Employ graph-based approaches to identify missing but relevant skills.
Job Role Recommendation: Train a classification model using job descriptions and resumes to predict suitable roles. Implement clustering techniques (K-Means, HDBSCAN) to group similar job titles.
Browser Extension Integration: Use JavaScript for front-end interaction and Flask/FastAPI for backend processing. Display a match score and recommendations within the job application form.
Expected Outcome: A fully functional extension providing resume-job match scores, missing skills, and job role recommendations.
