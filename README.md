# 🤖 AI Resume Screening System

An AI-powered desktop application that analyzes resumes and compares candidate profiles with job requirements using Artificial Intelligence, Machine Learning, and Natural Language Processing techniques.

---

## 📌 Project Overview

The **AI Resume Screening System** is designed to assist recruiters in the initial screening of candidates.

The system allows users to upload a resume, enter job requirements, and perform AI-based analysis to determine how closely the candidate matches the position.

The application extracts text from the resume, identifies relevant skills, compares them with the required skills, and generates an overall matching score.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze resumes automatically
- Extract important skills and qualifications
- Compare candidate skills with job requirements
- Identify matched and missing skills
- Calculate resume-job similarity
- Generate an overall candidate match score
- Provide an easy-to-use graphical interface

---

## ✨ Features

### 📄 Resume Upload

Users can upload a resume in PDF format.

The system extracts the text from the uploaded resume for further analysis.

### 📝 Job Requirements

Users can enter the requirements and description of the job they are hiring for.

### 🧠 AI Analysis

The system analyzes the resume and job requirements using text-processing and machine-learning techniques.

### 🔍 Skill Matching

The application identifies skills in the resume and compares them with the required job skills.

The results show:

- Matched Skills
- Missing Skills
- Skill Match Percentage

### 📊 Similarity Analysis

The system uses **TF-IDF Vectorization** and **Cosine Similarity** to compare the resume content with the job requirements.

### 📈 Match Score

The application generates an overall candidate match score based on the analysis.

### 🎨 Modern GUI

The application provides an interactive desktop interface built using **CustomTkinter**.

The interface contains separate sections for:

- Dashboard
- Resume
- Job Requirements
- AI Analysis
- Results

---

## 🛠️ Technologies Used

- Python
- CustomTkinter
- PyPDF2
- Pandas
- NumPy
- Scikit-learn
- TF-IDF
- Cosine Similarity
- Natural Language Processing
- Regular Expressions

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-Resume-Screening-System.git