# ATS-Radar
An intelligent ATS (Applicant Tracking System) resume analyser with AI-generated content detection.<br>
This repository contains the full-stack implementation of ATS-Radar: a platform that parses resumes (PDF/DOCX), evaluates ATS compatibility, matches resumes to job descriptions, and detects AI-written content using perplexity and linguistic analysis.
<br>
🚀 Features
Resume Parsing

Extract text from PDF/DOCX

Section detection: Skills, Experience, Projects, Education

Text cleaning & normalisation

ATS Scoring Engine

Keyword match score

Skills relevance score

Section completeness

Formatting issue detection

Job Description Matching

JD keyword extraction

Resume–JD comparison

Missing skills identification

Semantic similarity with embeddings

AI Content Detection

Perplexity analysis using GPT-2

Linguistic pattern scoring

AI-likelihood probability

Highlighting suspicious sentences

Frontend Dashboard

Upload resume & JD

ATS Score visualization

Missing keywords list

AI detection heatmap

🧠 Tech Stack
Backend

Python (FastAPI / Flask)

spaCy, NLTK

SentenceTransformers

PyPDF2, python-docx

Frontend

React

TailwindCSS

Recharts

Database

MongoDB / PostgreSQL

Deployment

Docker

Render / Railway (Backend)

Vercel (Frontend)
