# Resume ATS (Application Tracking System)

This project aims to enhance the recruitment process by evaluating resumes against job descriptions using Generative AI.

## Features

- **Resume Evaluation:** Upload a resume (PDF format supported) and a job description to receive a detailed evaluation.
- **Keyword Matching:** Analyze the match percentage of the resume with the provided job description.
- **Missing Keywords:** Identify keywords missing in the resume that are crucial for the job role.
- **Profile Summary:** Summarize the overall suitability of the resume for the job.

## Technologies Used

- Python
- Streamlit
- PyPDF2
- Google GenerativeAI
- Python-dotenv

## Install Dependencies
- run `pip install -r requirements.txt`

## Set up environment variables (if applicable, update .env file):
- `GOOGLE_API_KEY=your_google_api_key_here`

## Usage
- To run the application run `streamlit run src/main.py`
- **Evaluate resumes:** Upload a resume and paste a job description to evaluate the match and missing keywords.
