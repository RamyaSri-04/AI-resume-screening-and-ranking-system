# AI-resume-screening-and-ranking-system

## Overview

Resume Ranking AI is a Streamlit-based web application that helps in ranking resumes based on predefined criteria. It uses Natural Language Processing (NLP) and Machine Learning techniques to analyze and score resumes based on job descriptions.

## Output

👉[ output](screencapture-localhost-8501-2025-03-19-12_09_27.png)


## Features

- Upload and process multiple resumes
- Compare resumes against a given job description
- Generate a ranking based on relevance
- User-friendly interface with Streamlit
- Local and public access via LocalTunnel

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- pip (Python package manager)

### Steps to Install & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/RamyaSri-04/AI-resume-screening-and-ranking-system.git
   cd resume-rankings
   ```
2. Install the required dependencies:
   ```bash
   pip install streamlit
   pip install pypdf2
   pip install pandas
   pip install sklearn
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run resume_rankings.py
   ```
4. If accessing remotely, use LocalTunnel:
   ```bash
   npx localtunnel --port 8501
   ```

## Usage

1. Open the application in a browser using the provided `localhost` or external URL.
2. Upload resumes in PDF or DOCX format.
3. Enter the job description.
4. View ranked resumes based on relevance.

## Troubleshooting

- If the app does not open, check if Streamlit is running properly by verifying the terminal output.
- If `localhost:8501` does not load, try running on a different port:
  ```bash
  streamlit run resume_rankings.py --server.port 8502
  ```
- Ensure all required Python libraries are installed.

## Technologies Used

- **Python**: Backend processing
- **Streamlit**: Web interface
- **NLP & Machine Learning**: Resume processing and ranking
- **LocalTunnel**: External access / cmd

## Contributing

Feel free to fork this repository, make improvements, and submit a pull request.


## Contact

For questions or contributions, contact:

- **Your Name**: [chennusramyasri@example.com](mailto:chennusramyasri@example.com)
- GitHub: [RamyaSri-04](https://github.com/RamyaSri-04)
