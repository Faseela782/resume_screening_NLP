# Resume Screening NLP Project

This project uses Natural Language Processing (NLP) to automate the process of screening resumes. The system extracts important information like skills, education, and work experience, and compares them against job descriptions to rank candidates based on their relevance to the role.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Data](#data)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Run the Project](#how-to-run-the-project)
- [Future Work](#future-work)

## Overview

The goal of this project is to simplify the recruitment process by automating resume screening through NLP techniques. Resumes are analyzed, parsed for relevant sections, and matched with job descriptions to prioritize candidates based on how well their qualifications align with the role.

## Features

- Extracts important sections from resumes such as:
  - Contact Information
  - Education
  - Work Experience
  - Skills
- Compares resumes with a given job description to rank candidates.
- Automatically screens multiple resumes in bulk.
- Ranks resumes based on job description match score.
  
## Data

- *Resumes*: The dataset includes a collection of resumes in text or PDF format.
- *Job Descriptions*: A text-based job description that outlines the necessary skills, qualifications, and experience required for the position.

## Technologies Used

- *Python*: Main programming language used for development.
- *NLTK/Spacy*: Natural Language Processing libraries for parsing and analyzing resumes.
- *Pandas*: For data manipulation and handling.
- *Scikit-learn*: For model building, if classification or ranking models are used.
- *Flask/Django*: (Optional) Web framework to build a front-end interface for recruiters.
  
## Project Structure

- *resume_screening.ipynb*: Jupyter notebook that contains the full code for parsing resumes and matching them against job descriptions.
- *data/*: Directory containing resume and job description files.
- *output/*: Directory where ranked resumes or their summaries are saved.
- *README.md*: Project overview (this file).

## How to Run the Project

1. *Clone the repository*:
   ```bash
   git clone https://github.com/yourusername/resume_screening_nlp.git
