🎓 Education Regulation Impact Analyzer (ERIA)
📌 Project Overview

Education Regulation Impact Analyzer (ERIA) is an AI-powered NLP and Large Language Model (LLM) application designed to simplify complex education policies, regulations, circulars, and notifications issued by educational authorities such as UGC, AICTE, NAAC, NIRF, and universities.

The system automatically analyzes uploaded regulation documents and generates easy-to-understand summaries, stakeholder impact reports, risk assessments, and policy insights.

🚀 Features
📄 PDF Regulation Analysis
Upload education regulation documents in PDF format
Automatic text extraction and preprocessing
🏷️ Regulation Topic Classification

Automatically categorizes regulations into:

Accreditation
Scholarship
Admissions
Curriculum
Faculty Policy
Examination
Research Policy
University Governance
🧠 AI-Powered Summarization

Generates:

Executive Summary
Purpose of Regulation
Key Changes
Opportunities
Recommendations
👥 Stakeholder Impact Analysis

Identifies impact on:

Students
Faculty
Universities
Colleges
Administrators
Accreditation Teams
⚠️ Risk Assessment

Detects:

Compliance Challenges
Administrative Burden
Academic Risks
Institutional Readiness Issues
📈 Impact Forecasting

Provides:

Short-Term Impact (0–1 Year)
Medium-Term Impact (1–5 Years)
Long-Term Impact (5+ Years)
🎨 Interactive Dashboard

Built using Gradio for:

PDF Upload
AI Summary Generation
Topic Detection
Impact Analysis
Risk Assessment
🏗️ Project Architecture
PDF Upload
     │
     ▼
PDF Text Extraction
     │
     ▼
Text Cleaning & NLP Processing
     │
     ▼
Topic Classification
     │
     ▼
Keyword Extraction
     │
     ▼
Stakeholder Detection
     │
     ▼
Gemini LLM Analysis
     │
     ├── Summary Generation
     ├── Impact Analysis
     ├── Risk Detection
     └── Recommendations
     │
     ▼
Gradio Dashboard
🛠️ Tech Stack
Category	Technology
Programming Language	Python
Development Environment	Google Colab
LLM	Gemini 1.5 Flash
NLP	NLTK, SpaCy
Topic Classification	Hugging Face Transformers
Keyword Extraction	KeyBERT
PDF Processing	PyMuPDF
Dashboard	Gradio
Visualization	Plotly
Deployment	Hugging Face Spaces
📂 Project Structure
ERIA/
│
├── data/
│   ├── raw_pdfs/
│   └── processed/
│
├── notebooks/
│   └── ERIA_Project.ipynb
│
├── src/
│   ├── pdf_parser.py
│   ├── preprocessing.py
│   ├── classifier.py
│   ├── impact_analyzer.py
│   ├── summarizer.py
│   └── report_generator.py
│
├── app.py
├── requirements.txt
├── README.md
└── presentation.pptx
⚙️ Installation

Clone the repository:

git clone https://github.com/yourusername/ERIA.git
cd ERIA

Install dependencies:

pip install -r requirements.txt

Download SpaCy model:

python -m spacy download en_core_web_sm
🔑 Gemini API Setup

Get your API key from:

https://aistudio.google.com/

Add your API key:

GEMINI_API_KEY = "YOUR_API_KEY"
▶️ Running the Project
Google Colab
Open ERIA_Project.ipynb
Install dependencies
Add Gemini API key
Upload regulation PDF
Run all cells
Gradio Dashboard
interface.launch()
📊 Sample Output
Detected Topic
Scholarship Policy
Executive Summary
The regulation introduces revised scholarship
guidelines aimed at increasing accessibility
for economically weaker students.
Stakeholder Impact
Students → High Positive Impact

Faculty → Low Impact

Institutions → Moderate Compliance Changes
Risk Assessment
Additional documentation requirements

Potential implementation delays

Compliance monitoring burden
📈 Evaluation Metrics
Topic Classification Accuracy
Summary Quality
Stakeholder Detection Accuracy
Risk Detection Relevance
User Readability Score
Processing Time
🔮 Future Enhancements
Retrieval-Augmented Generation (RAG)
FAISS Vector Database
Policy Similarity Search
Chat with Regulation Documents
Knowledge Graph Generation
Multi-Document Comparison
PDF Report Export
LangFlow Integration
🎯 Project Deliverables
Google Colab Notebook
Gradio Dashboard
GitHub Repository
Project Documentation
PPT Presentation
Demo Video
Hugging Face Deployment
👨‍💻 Author

Ankit Sharma

AI/ML | NLP | LLM Projects

📜 License

This project is developed for educational and research purposes.
