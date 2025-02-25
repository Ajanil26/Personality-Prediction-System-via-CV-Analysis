# Personality Prediction System

## Project Overview

The Personality Prediction System is an AI-powered application designed to analyze resumes or textual data provided by candidates, predict their personality traits, and assist recruiters in making informed hiring decisions. This system utilizes various technologies and techniques, including machine learning, natural language processing (NLP), and a web interface to streamline the candidate evaluation process.

## Installation Guide

### Steps to Set Up

1. **Clone the Repository**
   ```sh
   git clone <repo_link>
   cd personality-prediction-system
   ```
2. **Create Your Gemini API Key**
   - Generate an API key by visiting: [Google Makersuite](https://makersuite.google.com/app/apikey)
3. **Install Required Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Run the Application**
   ```sh
   python app.py
   ```
5. **Enjoy Using the System!** 🎉

## Technologies Used

- **Programming Languages**: Python (backend), HTML, CSS, JavaScript (web interface)
- **Libraries/Frameworks**: Flask (web development), Pandas (data handling), NLTK (NLP), Google GenerativeAI (AI interaction)
- **Tools**: PyPDF2, textract, docx (text extraction from resumes)

## Implementation Details

### Resume Processing and Trait Assignment
- Extracts textual data from resumes using PyPDF2, textract, and docx.
- Preprocesses text by removing punctuation, tokenization, and lemmatization using NLTK.
- Assigns personality traits based on extracted skills and predefined associations from 'traits.txt'.

### Web Interface and User Interaction
- Implements a Flask-based web application to facilitate resume uploads and display analysis results.
- Renders HTML templates ('index.html' and 'result.html') for user interaction and results visualization.

### AI Interaction for Trait Description
- Utilizes Google's GenerativeAI to describe a candidate's personality based on assigned traits.
- Constructs queries to the AI model to generate descriptive insights about personality traits.

### Data Management and History
- Stores extracted resume details in a CSV file ('extracted_details.csv') for historical reference.
- Allows users to view history, export data, and clear history via the web application.

## Objective and Use Cases

The Personality Prediction System streamlines candidate evaluation by providing insights into personality traits derived from resumes or textual data.

### Use Cases

- **Recruitment Agencies**: Automates personality analysis to simplify candidate evaluation.
- **HR Departments**: Screens job applicants efficiently by analyzing personality traits.
- **Employers/Managers**: Helps in selecting candidates who fit company culture and job requirements.

## Conclusion

The Personality Prediction System is a powerful tool that integrates machine learning, NLP, and AI technologies to enhance the hiring process. By automating personality assessment and leveraging AI-driven insights, it enables recruiters and employers to make well-informed hiring decisions.

