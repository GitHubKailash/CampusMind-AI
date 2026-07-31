# CampusMind AI

> An AI-powered, voice-first campus intelligence platform that transforms scattered college documents into a unified, searchable, and conversational knowledge system.

CampusMind AI enables students to ask campus-related questions naturally through text or voice and receive fast, context-aware, and citation-backed answers. Administrators can update the system simply by uploading or replacing official PDF circulars, eliminating the need for manual AI retraining.

---

## Live Application

**CampusMind AI Web Application:**  
https://campusmind-2didyr9swn6mhbamspue.streamlit.app/

---

# Problem Statement

Critical campus updates are often fragmented across:

- Emails
- WhatsApp groups
- Google Drive links
- PDF circulars
- Department notices
- Static websites
- Notice boards

This information fragmentation creates significant difficulty for students. Finding a simple detail such as a fee deadline, examination schedule, revaluation date, event information, or academic announcement may require **10–15 minutes of manual searching**.

This can result in:

- Missed deadlines
- Delayed access to important information
- Unnecessary student stress
- Repeated administrative queries
- Increased workload for faculty and administrators
- Inefficient campus communication
- Lack of a centralized source of verified information

---

# Our Solution — CampusMind AI

CampusMind AI acts as a unified, intelligent, and voice-enabled digital brain for a campus.

The system ingests official campus documents and makes their information instantly accessible through natural conversation. Students can ask questions such as:

> “When is the revaluation fee deadline?”

> “What is the examination schedule?”

> “When is the last date to pay the semester fee?”

> “What are the important campus events this month?”

CampusMind AI retrieves relevant information from official documents and generates a context-aware response with supporting citations.

For administrators, the platform provides a **zero-training update workflow**. A new PDF circular can be uploaded or placed in the designated document repository, after which the system processes and indexes the updated information without requiring the AI model to be retrained.

---

# Project Objectives

- Centralize fragmented campus information.
- Reduce the time required to find important academic information.
- Provide a natural-language question-answering interface.
- Enable voice-based interaction for improved accessibility.
- Retrieve information from official campus documents.
- Generate context-aware and reliable answers.
- Provide citation-backed responses.
- Reduce repetitive administrative queries.
- Allow administrators to update the knowledge base easily.
- Eliminate the need for manual AI retraining after document updates.
- Build a scalable and future-ready campus intelligence platform.
- Improve communication between students and administrators.

---

# Key Features

## Real-Time Voice Search

CampusMind AI provides a natural and human-like voice interaction experience.

Students can speak their questions instead of manually typing them.

### Features

- Voice-based campus queries
- Natural conversational interaction
- Fast audio processing
- Reduced typing effort
- Improved accessibility
- Quick access to campus information

The system uses **Google Gemini 1.5 Flash** as a high-speed multimodal perception layer for handling voice input and generating rapid responses.

Example:

>  “When is the revaluation fee due?”

The system processes the query and returns the relevant information within seconds.

---

##  Natural-Language Campus Assistant

Students can ask questions using normal conversational language.

Examples:

- “When is the semester examination?”
- “What is the last date for fee payment?”
- “When is the revaluation application deadline?”
- “What are the upcoming college events?”
- “Where can I find the latest circular?”
- “What is the procedure for applying for revaluation?”

The system understands the meaning and context of the question instead of relying only on exact keyword matching.

---

##  Dynamic RAG Engine

CampusMind AI uses **Retrieval-Augmented Generation (RAG)** to provide answers based on official campus documents.

The RAG pipeline performs the following operations:

1. Collects official campus documents.
2. Extracts text from uploaded PDF files.
3. Divides the content into meaningful text chunks.
4. Converts the text chunks into vector embeddings.
5. Stores the embeddings in a vector database.
6. Converts the user query into a query embedding.
7. Searches for the most relevant document content.
8. Sends the retrieved context to the AI model.
9. Generates a context-aware response.
10. Displays supporting citations or document references.

This approach helps the AI provide answers grounded in the available campus information.

---

## Zero-Training Document Updates

Administrators can update the knowledge base without retraining the AI model.

### Workflow

```text
New Campus Circular
        │
        ▼
Upload PDF to Google Drive
        │
        ▼
Document Text Extraction
        │
        ▼
Text Chunking
        │
        ▼
Embedding Generation
        │
        ▼
Vector Database Update
        │
        ▼
CampusMind AI Knowledge Base Updated
