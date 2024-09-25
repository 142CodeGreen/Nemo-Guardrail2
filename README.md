# Nemo-Guardrail

This notebook is to practise Nemo Guardrail developed by NVIDIA for adding programmable guardrails to LLM-based conversational systems.

NeMo Guardrails are added to a simple RAG pipeline built with with LlamaIndex, NVIDIA NIM and NVIDIA embeddings. The dataset is from https://docs.nvidia.com/ai-enterprise/latest/pdf/nvidia-ai-enterprise-user-guide.pdf -O ./data/nvidia-ai-enterprise-user-guide.pdf.

The following rails are tested during practice:

- Input rails
- Dialog rails
- Execution rails
- Output rails

## Environment Installation
```
%pip install llama-index-core==0.10.50
%pip install llama-index-readers-file==0.1.25
%pip install llama-index-llms-nvidia==0.1.3
%pip install llama-index-embeddings-nvidia==0.1.4
%pip install llama-index-postprocessor-nvidia-rerank==0.1.2
!pip install -q nemoguardrails llama_index pypdf
```
