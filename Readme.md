## Track My Resume Application
> Track My Resume Application is an Applicant Tracking System (ATS) built using the Gemini Pro LLM model for natural language processing and classification. It allows users to streamline their hiring process by efficiently managing resumes, extracting text from various file formats, and providing insights into applicant data.


### Features:
- Resume Tracking: Easily manage and track resumes of job applicants.
- Text Extraction: Extract text content from PDF and DOCX files for further processing.
- Streamlit Interface: User-friendly web interface powered by Streamlit.
- Natural Language Processing: Utilizes the Gemini Pro LLM model for text classification and analysis.
- Google Generative AI Integration: Enhances the application with advanced AI capabilities.
- Environment Configuration: Integration with python-dotenv for environment variable management.

### Dependencies:
- Gemini Pro LLM: Natural language processing model for text classification.
- Streamlit: Web application framework for building interactive web applications.
- Google Generative AI: Integrates advanced AI capabilities into the application.
- python-dotenv: Manages environment variables for configuration.
- pdf2image: Converts PDF files to images for text extraction.
- docx2txt: Extracts text content from DOCX files.
- PyPDF2: Library for reading and manipulating PDF files.
- streamlit-lottie: Library for adding Lottie animations to Streamlit applications.

### Installation:

Clone the repository:
```
git clone https://github.com/Gitesh08/Track-my-resume.git
```

Navigate to the project directory:
```
cd Track-my-resume
```

Create a Python virtual environment:
```
python -m virtualenv . 
```

Activate venv:
```
.\scripts\activate
```

Install the required dependencies:
```
pip install -r requirements.txt
```
Ensure all dependencies are installed.


Run the Streamlit application:
```
streamlit run app.py
```
Access the application through your web browser using the provided local address.


### Contributing :handshake:
Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to open an issue or submit a pull request.


### License
This project is licensed under the MIT License.
