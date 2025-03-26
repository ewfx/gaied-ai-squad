Replace this file with a document that describes the architecture and design of your solution architecture. This may include
## 📄 Script Overview
This script is an AI-powered automation tool designed to process financial documents and emails. It performs the following tasks:

Parses and extracts text from PDF, DOCX, and EML files.

Extracts key financial data using the Mistral-7B-Instruct model (quantized for efficient inference).

Classifies each document by Request Type and Sub Request Type based on field matching.

Identifies and flags duplicate documents based on field-level similarity.

Outputs structured results in JSON format for easy integration into downstream systems.

