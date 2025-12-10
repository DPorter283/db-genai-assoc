# db-genai-assoc
🚀 Project OverviewThis repository documents the development of a production-ready Retrieval Augmented Generation (RAG) system built on the Databricks Lakehouse Platform. This project was developed as a structured curriculum to achieve the Databricks Certified Generative AI Engineer Associate certification.The core goal is to demonstrate end-to-end capabilities, from raw data ingestion and chunking to model deployment, governance, and safety monitoring.

<img width="2217" height="906" alt="image" src="https://github.com/user-attachments/assets/3c2c4f54-ecd8-4278-b28f-ae48e05b8390" />

🏗️ Architecture & Component Breakdown
The system follows a standard RAG architecture, leveraging Databricks-native services for scale and governance.

Ingestion: Raw documents are processed, parsed, and chunked using Python.

Indexing: Text chunks are stored in Delta Tables, and vector embeddings are indexed via Databricks Vector Search.

Retrieval: The RAG agent queries the Vector Index to retrieve relevant context.

Generation: An LLM (via Foundation Model APIs) generates the final response.

Deployment: The full chain is deployed as a secure, monitored Model Serving Endpoint.

📁 Repository Structure & Syllabus Map
The repository is organized by the functional steps of the AI development lifecycle, mirroring the 6-week certification syllabus.
<img width="1644" height="1068" alt="image" src="https://github.com/user-attachments/assets/d2a4bcc9-56e7-4f89-be35-a8458bd92f1b" />

