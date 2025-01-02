# Recommendation-system
Contract Analysis and Suggestion System
This Flask-based application provides an automated solution for analyzing legal contracts and generating structured suggestions in multiple languages (English, French, and Arabic). The application extracts text from uploaded or linked PDF files, processes the text using Azure OpenAI GPT-4, and outputs structured recommendations along with a downloadable PDF.

# Key-Features
🌐 Multilingual Support
Languages: Supports English, French, and Arabic for contract analysis.
Arabic Text Processing: Utilizes Arabic text reshaping and bidirectional (RTL) formatting for proper display.

📄 PDF Text Extraction
Extracts content from PDF files, including encrypted ones.
Seamlessly integrates with both uploaded files and external PDF URLs.

🤖 AI-Powered Insights
Leverages Azure OpenAI GPT-4 to generate structured insights:
Missing Articles/Clauses: Identifies gaps in contracts.
Problem Descriptions: Highlights potential issues.
Recommendations: Provides actionable advice.

🖨️ PDF Report Generation
Produces downloadable, well-formatted PDF reports with:
Language-specific styles and layouts.
Custom fonts for Arabic and RTL text alignment.

🌐 Web Integration Ready
CORS-enabled for easy integration with web-based applications.
Recommendations
PDF Generation: Outputs results as a downloadable, well-formatted PDF with language-specific styles and layouts.
Arabic Text Handling: Correctly displays Arabic text with proper reshaping and bidirectional support.
CORS Enabled: Ensures cross-origin compatibility for web-based integration.

# How It Works
Input: Upload a contract PDF or provide a PDF URL.

Example: https://www.annalindhfoundation.org/sites/default/files/2021-04/Draft%20contract%20template-English.pdf

Processing:

Extracts text from the PDF.
Detects the contract's language (English, French, or Arabic).
Analyzes the content using Azure OpenAI GPT-4 to generate insights.

Output:

Displays structured results: missing clauses, problem descriptions, and recommendations.
Generates a downloadable PDF report with the results.

Example: [Output.pdf](https://github.com/user-attachments/files/18290089/Output.pdf)

# Project Highlights

🖥️ Application Overview

![1](https://github.com/user-attachments/assets/64723122-d0ac-4508-92f5-4e56159ff17c)
![2](https://github.com/user-attachments/assets/af562be1-ef34-4353-95b9-5a8f72651a4e)

📊 Technologies Used

Backend: Flask

AI/ML: Azure OpenAI GPT-4

PDF Handling: PyPDF2, ReportLab

Languages: Python

Deployment: Azure
