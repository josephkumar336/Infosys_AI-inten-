# Infosys_AI-inten-
Just demo 


Enhanced Contract Compliance System
🌟 Project Overview

The Enhanced Contract Compliance System is an advanced AI-driven solution designed to streamline contract management, automate regulatory compliance checks, and intelligently process legal documents. Developed using Streamlit and LangChain, and powered by Groq’s Llama 3.3-70B, this platform enables organizations to analyze, monitor, and update contracts efficiently with minimal manual effort.

✨ Core Capabilities
🤖 Intelligent Contract Analysis

Automated Metadata Extraction
Identifies key contract details such as involved parties, dates, clauses, and applicable regulations using large language models.

Regulatory Compliance Validation
Performs real-time checks against standards like GDPR, DPDPA, and other compliance frameworks.

Risk Evaluation Engine
Generates automated risk scores supported by interactive visual indicators.

📂 Advanced Document Handling

Multiple Input Formats
Supports PDFs, URLs, text files, and direct text entry.

Optimized Storage
Uses AstraDB for secure and compressed document storage.

Contract Version Tracking
Maintains full revision history with change comparison and rollback support.

🔄 Automated Contract Updates

Regulatory Impact Detection
Analyzes how new laws or policies affect existing contracts.

AI-Assisted Revision Generation
Produces updated contract versions with detailed explanations of changes.

Email Alert System
Sends notifications for high-risk contracts and revision requirements.

💬 AI-Powered Chat Assistant

Context-Aware Q&A
Ask questions about specific contracts using a RAG-based chatbot.

Clause & Risk Insights
Get instant explanations of clauses, compliance issues, and risks.

Session Memory
Maintains conversational context for deeper analysis.

📊 Analytics & Visualization

Risk Level Gauges
Interactive charts displaying contract risk severity.

Compliance Overview
Visual summaries of regulatory adherence.

Revision Impact Metrics
Shows how updates affect overall contract compliance.

🏗️ System Architecture
Enhanced Contract Compliance System
├── User Interface (Streamlit)
│   ├── Analytics Dashboard
│   ├── Contract Upload & Review
│   ├── Chat Assistant
│   └── Revision Manager
├── AI Processing Layer
│   ├── Metadata Extraction
│   ├── Compliance Evaluation
│   ├── Contract Revision Engine
│   └── RAG Chatbot
├── Data Layer
│   ├── AstraDB Storage
│   ├── Vector Database
│   └── Caching Mechanism
└── Integration Services
    ├── Email Notifications
    ├── PDF & Text Processing
    └── External API Support

🚀 Getting Started
Prerequisites

Python 3.12

AstraDB account

Groq API Key

Gmail account (optional, for notifications)

Installation Steps

Clone the repository

git clone https:https://github.com/josephkumar336/Infosys_AI-inten
cd contract-compliance-system


Create and activate a virtual environment

python -m venv venv
# Windows
venv\Scripts\activate
# Linux / Mac
source venv/bin/activate


Install required packages

pip install -r requirements.txt


Set up environment variables
Create a .env file:

ASTRA_DB_APPLICATION_TOKEN=your_token
ASTRA_DB_ID=your_db_id
GROQ_API_KEY=your_groq_key
SENDER_EMAIL=your_josephladdu6@gmail.com
SENDER_PASSWORD=your_app_password


Launch the application

streamlit run app.py

📁 Directory Structure
contract-compliance-system/
├── complete_compliance_app.py   # Main application logic
├── api_integration.py           # External API handlers
├── database.py                  # Database connectivity
├── requirements.txt             # Dependency list
├── README.md                    # Documentation
├── .gitignore                   # Ignored files

🛠️ Major Components
1. Contract Lifecycle Manager

Centralized contract tracking

Real-time compliance status updates

Risk monitoring dashboard

2. AI Metadata Engine

Extracts structured contract data

Handles diverse legal formats and terminology

3. Compliance Evaluation Module

Multi-regulation support

Violation detection with correction suggestions

4. Smart Revision Generator

AI-generated contract updates

Detailed change logs

Stakeholder email alerts

5. Contract Chat Assistant

Retrieval-Augmented Generation (RAG)

Contract-aware conversations

Continuous contextual learning

🔧 Configuration Guide
Required Environment Variables
ASTRA_DB_APPLICATION_TOKEN=
ASTRA_DB_ID=
GROQ_API_KEY=

Optional (Email Alerts)
SENDER_EMAIL=
SENDER_PASSWORD=

📊 Typical Usage Flow
Uploading Contracts

Choose upload method (PDF, URL, Text)

Assign contract owner email

Select applicable regulations

Review AI-generated insights

Compliance Analysis

Select contract from dashboard

Run regulatory checks

Export compliance reports as PDFs

Managing Updates

Upload new regulations

Generate impact analysis

Apply AI-recommended revisions

Chatbot Assistance

Select contract

Ask compliance or clause-related questions

Receive AI-powered explanations

🔒 Security Measures

Secure environment variable handling

Email authentication via app passwords

Input validation and session isolation

Controlled API access

🧪 Testing
python database.py
python api_integration.py

📈 Performance Highlights

Metadata extraction in under 5 seconds

Storage optimization up to 70%

Real-time UI updates

Scalable for large contract repositories

🤝 Contribution Guidelines

Fork the repository

Create a new branch

Commit your changes

Push and open a Pull Request

📄 License

This project is released under the MIT License.
Refer to the LICENSE file for details.

🙏 Credits

Streamlit – UI framework

Groq – High-speed LLM inference

LangChain – AI workflow orchestration

AstraDB – Scalable data & vector storage

Plotly – Interactive data visualization

Built with ❤️ to modernize legal contract compliance using AI
