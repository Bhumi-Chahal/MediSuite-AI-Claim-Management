# InsuraMedix – AI-Powered Hospital and Insurance Claim Management System

## Overview

InsuraMedix is an AI-assisted hospital and medical insurance claim management system designed to simplify and streamline the medical insurance claim process.

The system aims to reduce manual paperwork, improve document processing, assist with medical information extraction, and make claim tracking more efficient. It brings different stages of the claim lifecycle together, from document submission and validation to claim review and settlement.

AI-assisted processing helps users handle claim-related information while important decisions remain under human supervision.

## Objectives

- Simplify the hospital and insurance claim management process.
- Reduce repetitive manual data entry.
- Extract relevant information from uploaded medical documents.
- Assist in identifying medical diagnosis and procedure codes.
- Support claim validation and review.
- Improve transparency through claim tracking and status updates.
- Maintain organized claim records and supporting documents.

## Key Features

### 1. AI-Assisted Document Processing
Processes uploaded medical documents and helps extract relevant information for claim preparation.

### 2. Medical Code Identification
Uses ICD-10 and CPT-4 datasets to assist in identifying relevant diagnosis and procedure codes.

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
| AI Integration | OpenAI API, Mistral API |
| Medical Code Datasets | ICD-10, CPT-4 |
| Document Processing | Python PDF processing libraries |
| Version Control | Git and GitHub |

## Project Structure

```text
InsuraMedix-AI-Claim-Management/
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
git clone https://github.com/Bhumi-Chahal/InsuraMedix-AI-Claim-Management.git
cd InsuraMedix-AI-Claim-Management
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment on Windows:

```powershell
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Keys

Configure your API keys using environment variables. Do not hardcode credentials in the source code.

For Windows PowerShell:

```powershell
$env:OPENAI_API_KEY="your-openai-api-key"
$env:MISTRAL_API_KEY="your-mistral-api-key"
```

### 5. Run the Application

Run the application using its configured entry point. For example, if `app.py` is the application entry point:

```bash
python app.py
```

Check the project configuration for the exact execution command.

## Development and Contributions

InsuraMedix is maintained as an academic software project. Development activities, improvements, testing, and documentation are managed through GitHub.

The repository uses an existing open-source codebase as its starting point. Original source-code attribution and applicable licence terms are retained. Further development and project-specific modifications are tracked through Git commits.

## Disclaimer

InsuraMedix is an academic software project. AI-generated information is intended to assist with claim processing and must be verified by authorized personnel. The system is not intended to replace professional medical judgment or independent insurance claim decisions.

## License

This repository retains the applicable MIT License and original copyright notices. Refer to the `LICENSE` file for details.