# agente_ia
agente de ia simples




---
# Arquitetura futura



Angular
   ↓ HTTP
FastAPI
   ↓
Agent Service
   ├── Ollama / LLM
   ├── ferramentas Python
   ├── Redis para memória
   ├── Oracle para dados
   └── APIs externas

Estrutura Python:

app/
├── main.py
├── schemas/
│   └── chat_schema.py
├── agents/
│   └── estoque_agent.py
├── tools/
│   └── estoque_tool.py
├── services/
│   └── ollama_service.py
└── repositories/
    └── estoque_repository.py