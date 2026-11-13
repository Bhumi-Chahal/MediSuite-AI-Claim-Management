# MediSuite – AI-Powered Hospital and Insurance Claim Management System

## Overview

MediSuite is an AI-assisted hospital and insurance claim management system designed to simplify and streamline the medical insurance claim process.
The platform aims to reduce manual paperwork, improve document processing, assist with medical information extraction, and make claim tracking more efficient. It brings important stages of the claim lifecycle together in one system, from document submission and validation to claim review and settlement.
MediSuite uses AI-assisted processing to support users in handling claim-related information while keeping important decisions under human supervision.

## Objectives

- Simplify the hospital and insurance claim management process.
- Reduce repetitive manual data entry.
- Extract relevant information from uploaded medical documents.
- Assist with medical diagnosis and procedure code identification.
- Support claim validation and review.
- Improve transparency through claim tracking and status updates.
- Maintain organized claim records and supporting documents.

## Key Features

### 1. AI-Assisted Document Processing
Processes uploaded medical documents and helps extract relevant information for claim preparation.
### 2. Medical Code Identification
Uses medical code datasets to assist in identifying relevant diagnosis and procedure codes.
### 3. Claim Information Management
Organizes patient, hospital, policy, billing, and claim-related information.
### 4. Claim Validation Support
Helps identify missing information and potential inconsistencies before claim review.
### 5. Claim Review and Approval
Supports the claim review workflow, with final decisions made by authorized insurance personnel.
### 6. Claim Tracking
Provides a structured way to monitor claim progress and status.

## Technology Stack
| Component | Technology |
|---|---|
| Programming Language | Python |
| Application Interface | Streamlit (if used in the current implementation) |
| AI Integration | OpenAI API / Mistral API |
| Medical Code Data | ICD-10 and CPT-4 |
| Document Processing | PDF processing libraries |
| Version Control | Git and GitHub |

## Project Structure
MediSuite-AI-Claim-Management/
│
├── Agent.py
├── app.py
├── main.py
├── PDFBuilder.py
├── llm_interface.py
├── openai_implementation.py
├── mistral_implementation.py
│
├── CPT4.json
├── ICD10.json
│
├── requirements.txt
├── setup.sh
├── .gitignore
├── LICENSE
└── README.md
```
## Installation and Setup

### Prerequisites

- Python 3.9 or later
- Git
- API key for the AI provider you intend to use

### 1. Clone the Repository

```bash
git clone https://github.com/Bhumi-Chahal/MediSuite-AI-Claim-Management.git
cd MediSuite-AI-Claim-Management
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```
Activate it on Windows:
```powershell
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Keys

Set the API keys as environment variables instead of hardcoding them in the source code.

PowerShell:

$env:OPENAI_API_KEY="your-openai-api-key"
$env:MISTRAL_API_KEY="your-mistral-api-key"

5. Run the Application

Check the application's configured entry point and run the appropriate command. If app.py is the Streamlit entry point:

streamlit run app.py

Development and Contributions

This repository is maintained as part of the MediSuite project. Project development, improvements, testing, and documentation are tracked through GitHub.

The project incorporates an existing open-source MediSuite AI claim-management codebase as its starting point. Original source-code attribution and applicable licence terms are retained. Further modifications and additions are documented through subsequent development commits.

Disclaimer

MediSuite is an academic software project. AI-generated information is intended to assist with claim processing and should be verified by authorized personnel. The system is not intended to replace professional medical judgment or independent insurance claim decisions.
