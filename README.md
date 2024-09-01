# Resume Reviewer

Resume Reviewer is a Streamlit-based web application designed to help job seekers optimize their resumes for Applicant Tracking Systems (ATS). The app allows users to upload their resumes in PDF format, analyze them based on different criteria, and receive suggestions for improving their resume's ATS compatibility. Additionally, users can ask custom questions about their resume or the analysis provided.

## Features

- **PDF Resume Upload**: Upload your resume in PDF format for analysis.
- **Resume Analysis**: Choose between Quick Scan, Detailed Analysis, or ATS Optimization.
- **Job Description Matching**: Paste a job description to get specific optimization suggestions.
- **Custom Questions**: Ask specific questions about your resume or the provided analysis.
- **ATS Compatibility Score**: Receive a score and suggestions on how to improve your resume for ATS systems.

## Installation

### Prerequisites

- Python 3.8 or higher
- [Streamlit](https://streamlit.io/)
- [PyPDF2](https://pypdf2.readthedocs.io/)
- [dotenv](https://pypi.org/project/python-dotenv/)
- [Google Generative AI](https://github.com/google/generative-ai-python)

### Setup

1. Clone this repository:

```bash
git clone https://github.com/abhishek-gupta-ducs/Resume-Reviewer
cd Resume-Reviewer
```

2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory and add your Google API key:

```
GOOGLE_API_KEY=your_google_api_key
```

4. Run the Streamlit application:

```
streamlit run app.py
```

## Usage

1. Open the application in your web browser.
2. Upload your resume in PDF format.
3. Paste a job description to receive ATS-specific optimization suggestions.
4. Choose the type of analysis you want to perform:
   - **Quick Scan**: A basic overview of your resume.
   - **Detailed Analysis**: A more thorough analysis, focusing on various resume aspects.
   - **ATS Optimization**: Suggestions to improve your resume's compatibility with ATS.
5. Ask custom questions about your resume based on the analysis.
6. View the results and make the recommended changes to your resume.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any bugs, improvements, or features you would like to see.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, feel free to reach out:

- **Email**: abhishek.gupta.mca21.du@gmail.com
- **LinkedIn**: [Abhishek Gupta](https://www.linkedin.com/in/abhishek-gupta-ducs/)
- **GitHub**: [Abhishek Gupta](https://github.com/abhishek-gupta-ducs)
