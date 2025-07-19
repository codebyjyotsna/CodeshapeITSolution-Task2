# CodeshapeITSolution-Task2
# AI Resume Screening & Candidate Ranking System

This repository contains a Streamlit-powered application for automated resume screening and candidate ranking. By leveraging natural language processing (NLP) techniques, the app compares uploaded resumes against a provided job description and ranks candidates based on relevance and similarity.

## Overview

Recruiters and hiring managers often receive numerous resumes for a single job posting. This tool uses machine learning to automate the screening process, saving time and improving consistency. The system extracts text from uploaded PDFs, compares them with the job description using TF-IDF and cosine similarity, and outputs a ranked list of candidates.

## Features

- **Upload Multiple Resumes:** Supports batch uploading of PDF files for screening.
- **Job Description Input:** Enter the job requirements directly in the app.
- **Automatic Text Extraction:** Uses PyPDF2 to extract content from PDFs.
- **Similarity Scoring:** Calculates how closely each resume matches the job description.
- **Ranking Table:** Displays candidates in order of relevance, with scores.
