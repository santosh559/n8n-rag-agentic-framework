# RAG-Based Agentic Workflow in n8n
This workflow implements Retrieval-Augmented Generation (RAG) using LangChain nodes inside n8n.
- Accepts PDF/CSV file uploads
- Generates embeddings using OpenAI
- Uses an in-memory vector store for document retrieval
- Responds via GPT-4o-mini agent

## How to Use
1. Import `My_workflow.json` into your n8n instance.
2. Connect your OpenAI API key.
3. Execute workflow to upload and query documents.
