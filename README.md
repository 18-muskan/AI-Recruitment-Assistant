# AI Recruitment Assistant

An AI-powered recruitment backend that helps recruiters manage job requirements, process candidate resumes, extract relevant candidate information, and evaluate candidates against job requirements.

## Features

* Resume upload and processing
* PDF and DOCX resume parsing
* Candidate information extraction
* Skills, education, projects, and experience extraction
* Job creation and management
* Candidate search and management
* CV-to-Job Description matching
* Skill matching and missing-skill identification
* Experience matching
* Candidate ranking
* Match score calculation
* RESTful APIs
* Interactive API documentation with Swagger UI

## Tech Stack

* Python
* FastAPI
* Pydantic
* SQLAlchemy
* SQLite
* Uvicorn
* NLP / Text Processing
* PDF Parsing
* DOCX Parsing
* REST APIs
* Swagger UI

## Project Structure

AI-Recruitment-Assistant/
│
├── backend/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── resume.py
│   ├── requirement.py
│   └── ...
│
├── .venv/
├── requirements.txt
└── README.md

## Requirements

Before running the project, make sure you have:

* Python 3.11 or higher
* pip
* Git (optional, for version control)

## Installation

### 1. Clone the Repository

git clone <your-github-repository-url>
cd AI-Recruitment-Assistant

### 2. Create a Virtual Environment

python -m venv .venv

### 3. Activate the Virtual Environment

**Windows PowerShell:**

.venv\Scripts\Activate.ps1

**Windows CMD:**

.venv\Scripts\activate


### 4. Install Dependencies

pip install -r requirements.txt

## Run the Project

Navigate to the backend folder:

cd backend

Start the FastAPI server:

uvicorn main:app --reload

The backend will run at:

http://127.0.0.1:8000

## API Documentation

After starting the server, open Swagger UI:

http://127.0.0.1:8000/docs

Swagger UI allows you to test the available API endpoints directly from your browser.

## Main API Modules

### Recruitment APIs

* Job creation and management
* Job search
* Job statistics
* Ranked candidates
* Candidate matching
* Candidate shortlisting

### Resume APIs

* Resume upload
* Resume parsing
* Candidate information extraction
* Candidate search
* Candidate details

### Matching

The system evaluates candidates using:

* Skill matching
* Experience matching
* Overall match score
* Matching skills
* Missing skills
* Candidate ranking

## Example Workflow

Upload Resume
      ↓
Parse Resume
      ↓
Extract Candidate Information
      ↓
Create / Select Job
      ↓
Compare Candidate with Job
      ↓
Calculate Match Score
      ↓
Identify Matching & Missing Skills
      ↓
Rank Candidates

## Project Status

🚧 **In Development**

The backend recruitment and resume-processing functionality is being developed incrementally, with additional AI/LLM-based capabilities planned for future versions.

## Author

**Muskan Ejaz**

AI Engineering / Generative AI Project
