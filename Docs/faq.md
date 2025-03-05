# Frequently Asked Questions (FAQ)

## General Questions

### What is AIMS?
AIMS (Artificial Intelligence Meeting Summarizer) is an AI-powered application that automatically processes meeting transcripts and documents to generate comprehensive summaries and enable intelligent question-answering about meeting content.

### What file formats does AIMS support?
AIMS supports PDF, DOCX, VTT, and TXT files with 100% format compatibility. This covers most common formats used for meeting transcripts and notes.

### How does AIMS integrate with ServiceNow?
AIMS connects directly with the ServiceNow meeting module, enabling automated processing of meeting transcripts and publishing summaries back to ServiceNow, making them accessible to enterprise users.

### Is AIMS available on mobile devices?
AIMS has a responsive design that works across desktop and mobile devices, allowing users to access meeting summaries and ask questions from anywhere.

## Usage Questions

### How do I upload a document to AIMS?
Simply click the "Upload your document" button and select the file you want to process. AIMS will automatically detect the file format and process it accordingly.

### How long does it take to process a document?
Processing time varies based on document size and complexity. Typical meeting transcripts (5-10 pages) are processed in 10-30 seconds. Longer documents may take 1-2 minutes.

### Can I ask follow-up questions?
Yes, AIMS includes a conversation memory system that maintains chat history context, allowing for natural follow-up questions and coherent conversation flows.

### How accurate are the summaries?
AIMS generates summaries with high accuracy for standard meeting content. The system is continuously improved based on user feedback. For technical or highly specialized meetings, some nuance may be lost, which is why the Q&A feature is available to extract specific details.

## Technical Questions

### How does AIMS maintain data privacy?
AIMS processes all documents locally. No meeting content is sent to external services, ensuring data privacy and compliance with organizational security policies.

### What technologies power AIMS?
AIMS is built using:
- Streamlit (frontend interface)
- LangChain & Ollama (language model integration)
- Chroma DB (vector storage)
- PyPDF2, Docx2txt (document processing)

### Does AIMS require internet access?
AIMS can operate entirely within your organization's network, without requiring external internet access. This enhances security and performance for enterprise deployments.

### How does the vector storage optimization work?
AIMS uses Chroma DB with cosine similarity indexing to optimize vector storage and retrieval. This approach reduces query latency by up to 30% compared to standard vector search methods, resulting in faster response times.

## Repository Information

### Why isn't the source code available in this repository?
This GitHub repository serves as a showcase for the AIMS application's capabilities and interface. The actual source code is not available publicly. This repository contains only mockups, documentation, and demonstration assets.

### Are there any known limitations?
Current limitations include:
- Maximum file size of 50MB
- Processing very large documents (100+ pages) may take extended time
- Some highly specialized technical terminology may not be accurately summarized
- Complex tables and diagrams within documents may not be fully interpreted
