# medical-llm-hallucination-mitigation



# Explainable Sentence-Level Self-Correction for Hallucination Mitigation in Medical Question Answering Using Large Language Models


## Abstract

Large Language Models (LLMs) demonstrate strong capabilities in medical question answering and biomedical text generation. However, they frequently produce hallucinations—fluent yet factually unsupported medical statements.

This project proposes an explainable self-correcting framework for hallucination mitigation using biomedical evidence retrieval and sentence-level verification.

## Workflow

User Query  
↓  
Initial LLM Answer (Mistral-7B-Instruct)  
↓  
Biomedical Evidence Retrieval (FAISS + PubMed)  
↓  
Sentence-Level Hallucination Detection  
↓  
Targeted Self-Correction  
↓  
Re-Verification  
↓  
Final Explainable Medical Answer

## Technologies

- Python
- HuggingFace Transformers
- Sentence Transformers
- FAISS
- PyTorch
- PubMed biomedical dataset

## Repository Structure
