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
## Project Steps

1. **Environment Setup:**
   - Configured project dependencies and loaded environment variables using `dotenv`.

2. **API Configuration:**
   - Integrated Google's generative AI API for content generation.

3. **Text Extraction:**
   - Implemented PDF text extraction using `PyPDF2` to process uploaded resumes.

4. **User Interface:**
   - Developed a Streamlit web app for user interaction.

5. **Model Interaction:**
   - Utilized `genai`'s `gemini-pro` model for evaluating resume-job description matches.

6. **Display Results:**
   - Presented evaluation results (JD Match, Missing Keywords, Profile Summary) on the frontend.

7. **Error Handling:**
    - Implemented error management for invalid responses or missing resume uploads.

## Usage

- **Installation:** Install dependencies with `pip install -r requirements.txt`.
- **Setup:** Set up environment variables, including `GOOGLE_API_KEY=your_google_api_key_here`.
- **Execution:** Run the application using `streamlit run src/main.py`.
- **Evaluate resumes:** Upload a resume and paste a job description to evaluate the match and missing keywords.
