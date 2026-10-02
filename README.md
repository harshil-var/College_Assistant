## V1 
Hardcoded sample PDFs
       ->
LangGraph + RAG
       ->
Working chatbot
 

## 🏗️ Workflow Architecture

The workflow can be represented as:

```text

                    User selects branch
                 BCA / BBA / B.Com
                         │
                         ▼
                  ┌─────────────┐
                  │   Chatbot   │
                  └──────┬──────┘
                         │
                What is the question?
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
      Academic          Fees          General
         PDF             PDF          Knowledge
          │              │               │
          ▼              ▼               ▼
        RAG            RAG              LLM
          │              │               │
          └──────────────┼───────────────┘
                         ▼
                  Final Response
