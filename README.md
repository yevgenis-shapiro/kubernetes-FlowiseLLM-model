![FlowiseIntro](https://github.com/user-attachments/assets/33b6d277-b66e-446e-a763-6eed4b4de7dc)


## Generative AI | Agents and LLM workflows 
Flowise is an open-source, no-code / low-code tool for visually building LLM-based applications — like chatbots, RAG (Retrieval-Augmented Generation) systems, agents, and pipelines — using a drag-and-drop interface similar to Node-RED or n8n.

⚙️ Key features:
```
✅ Visual Builder - Create LLM workflows by connecting blocks (LLM, Prompt, Tools, Database) 
✅ Powered by LangChain - Every node corresponds to a LangChain component .
✅ Supports many models:
OpenAI (GPT-3.5 / GPT-4)
Anthropic Claude
Google Gemini
Mistral, Ollama (local models)
Hugging Face models
And through LiteLLM — virtually any model you want!
✅ RAG & vector stores - Integrates with Pinecone, FAISS, Chroma, Weaviate, Supabase
✅ Agents & Tools - Add nodes for Google Search, API calls, or your own custom Python functions
✅ API endpoints - Each flow can be deployed as a REST API endpoint.
✅ Authentication, caching, and data logging included.
```

🚀 Deployment
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```




