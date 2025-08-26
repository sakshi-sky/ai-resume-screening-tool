# ai-resume-screening-tool
A project for parsing and ranking resumes based on how well they match a given job description. 

#Features

- Smart Resume Parsing: Extract structured data from PDF and DOCX files

- AI-Powered Matching: TF-IDF vectorization and cosine similarity for job compatibility

- Skill Analysis: Automated identification and matching of technical and soft skills

- Batch Processing: Handle multiple resumes simultaneously

- Export Results: Download rankings in Excel/CSV format


#Technology Stack

- Backend: Python 3.8+

- NLP: spaCy, scikit-learn (TF-IDF, Cosine Similarity)

- File Processing: PyPDF2, python-docx

- Data Analysis: pandas, NumPy

- Visualization: Plotly

- Web Framework: Streamlit


#Installation

Prerequisites
- Python 3.8 or higher
- pip package manager

Setup

1. Clone the repository

2. Install dependencies
   bashpip install -r requirements.txt

3. Download spaCy language model
   bashpython -m spacy download en_core_web_sm

4. Run the application
   bashstreamlit run app.py

Project Structure

ai-resume-screening/

│
├── app.py                 # Main Streamlit application

├── resume_parser.py       # Resume parsing functionality

├── job_matcher.py         # Job matching and similarity logic

├── utils.py              # Utility functions

├── requirements.txt      # Dependencies

└── sample_data/          # Folder for sample resumes

    ├── sample_job.txt
    
    └── resumes/

Made with Python and Streamlit
