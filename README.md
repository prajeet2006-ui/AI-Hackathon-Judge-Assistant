# AI Hackathon Judge Assistant 🤖

## Project Overview
This project is an AI-powered assistant designed to help hackathon judges evaluate submissions. It uses Google's Gemini-2.5-Flash model to analyze a project's description, a screenshot, and a supporting PDF document. The assistant provides scores for "Innovation" and "Technical Execution," along with constructive feedback, streamlining the judging process.

## Features
- **Project Analysis:** Evaluates hackathon submissions based on multiple inputs.
- **Scoring System:** Provides scores for Innovation and Technical Execution (1-10).
- **Constructive Feedback:** Generates a short paragraph of feedback to help teams improve.
- **User-friendly Interface:** Built with Gradio for a simple and intuitive web interface.

## Prerequisites
- Python 3.8 or higher
- A Google Gemini API key

## Setup and Installation
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/AI-Hackathon-Judge-Assistant.git](https://github.com/your-username/AI-Hackathon-Judge-Assistant.git)
   cd AI-Hackathon-Judge-Assistant
2. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```
Note: You will need to create a requirements.txt file with the following contents:
   ```bash
   gradio
   google-generativeai
   PyMuPDF
   Pillow
   ```
3. **Configure your API key:**
   Add your Google Gemini API key to the code. Replace the placeholder value in main.py (or your    main script file) with your actual key:
   ```bash
   genai.configure(api_key="YOUR_API_KEY_HERE")
   ```
## Usage
1. **Run the application:**
   ```bash
   python app.py  # or the name of your Python file
   ```
2. **Access the interface:**
   Open your web browser and navigate to the local URL provided in the terminal (e.g.,    http://127.0.0.1:7860).
3. **Upload and analyze:**
   - Enter the project description in the text box.
   - Upload a project screenshot.
   - Upload a supporting PDF document.
   - Click the "Analyze Project" button to get the judge's report.

   
