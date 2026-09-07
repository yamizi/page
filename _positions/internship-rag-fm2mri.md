---
title: "Retrieval-Augmented and Privacy-Preserving Deployment of Foundation Models for MRI"
collection: positions
permalink: /position/internship-rag-fm2mri
category: internship
status: open
host: "Luxembourg Institute of Health (LIH) — BraINE Research Group"
location: "Luxembourg (on-site)"
duration: "Master's internship; duration and start date to be agreed with the candidate; 6-9 months preferred"
contact_email: "salah.ghamizi[at]lih.lu"
---

This internship is part of FM2MRI, a project building a foundation model combining Mixture of Experts (MoE) and Retrieval Augmented Generation (RAG) for MRI segmentation and synthesis. Robust models for medical imaging must generalize across the diverse acquisition settings of different hospitals while remaining deployable locally under data privacy and compute constraints. RAG addresses generalization by letting a model retrieve and incorporate relevant information from an institution's own database at inference time, without retraining. This internship will build that retrieval mechanism, integrate it with the project's MoE model, and evaluate the solution both for effectiveness and for its privacy guarantees.

**What you'll work on:**
- **RAG database & context generation.** Design a vector database engine that indexes MRI image and prompt embeddings, and a query-retrieval-context pipeline that merges the top relevant embeddings from the database with the original prompt to guide the model.
- **Evaluation on MRI segmentation & synthesis.** Evaluate the RAG-augmented prompting mechanism on scarce MRI scenarios from the BraTS2023 challenge (e.g. paediatric glioma, sub-Saharan glioma, adult metastasis), and as a data-augmentation pipeline for MRI synthesis models built on MONAI.
- **MONAI integration & embedding fusion.** Integrate the datasets and processing pipelines into the MONAI API, and implement multi-modal fusion techniques (early fusion, late fusion, joint embedding) to merge the project's image and prompt embeddings.
- **Packaging & privacy-preserving deployment.** Package the combined MoE + RAG solution into a deployable container, and implement and evaluate privacy-preserving mechanisms (e.g. differential privacy, encrypted machine learning) to report on their performance and safety trade-offs.

**Deliverables:**
- A retrieval-augmented vector database and query/context-generation pipeline for MRI data, integrated with the project's MONAI-based components.
- A packaged prototype combining Mixture of Experts and RAG, with a technical report evaluating its effectiveness, robustness, and privacy guarantees.

**Profile sought:**
- Enrolled in a Master's program in Computer Science, AI/Data Science, or a related field
- Strong programming skills in Python, with hands-on experience in deep learning frameworks (PyTorch, MONAI preferred)
- Interest in retrieval-augmented generation, mixture-of-experts architectures, or privacy-preserving machine learning; prior exposure to medical imaging is a plus
- Autonomous, rigorous, and comfortable working at the interface of AI research and system integration

**How to apply:** Send your CV and your Master transcripts by email.
