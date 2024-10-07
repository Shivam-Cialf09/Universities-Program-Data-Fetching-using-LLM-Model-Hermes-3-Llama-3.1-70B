University Program Data Extraction Model 
Description
The University Program Data Extraction Tool is an AI-powered Python script that automates the collection of undergraduate program information from multiple educational institutions. It leverages the Groq API to process bulk data and outputs a comprehensive Excel file, streamlining research and analysis in the higher education sector.
Features

Bulk data extraction from multiple institutions
Integration with Groq API for AI-powered information retrieval
AISHE (All India Survey on Higher Education) code incorporation
Structured Excel output for easy analysis
Robust error handling and retry mechanism

Prerequisites

Python 3
pandas
groq API 
LLM-Model-Hermes-3-Llama-3.1-70B
requests

Installation

Clone the repository:
Copygit clone https://github.com/Shivam-Cialf09/university-program-extractor.git

Navigate to the project directory:
Copycd university-program-extractor

Install required packages:
Copypip install -r requirements.txt


Usage

Prepare an Excel file with columns 'For GPT' (institution names) and 'Aishe Code'.
Update the file_path variable in the script with your input file path.
Replace the Groq API key in the script with your own.
Run the script:
Copypython program_extractor.py


Configuration

Adjust the row range in the script to process different sections of your input file.
Modify the output file path as needed.

Output
The script generates an Excel file containing:

Aishe Code
University Name
Program Name
Major
Program Link

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
Acknowledgments

Groq API for providing the AI capabilities
All contributors and testers of this project
