---
permalink: /positions/
title: "Open Positions"
modified: 2026-09-07
author_profile: true
---

I am regularly looking for motivated students and researchers to join us, working on trustworthy machine learning, world models, and their application to safety-critical systems, in particular medical imaging and neuro-imaging. Open positions are listed below by type.



# Postdoctoral researcher

No open positions at the moment. Feel free to reach out at salah.ghamizi[Arobase]uni.lu if you are interested in future opportunities.

# PhD student

## Doctoral Researcher in Trustworthy World Models for Critical Systems — Power Grids 

**Host institution:** Interdisciplinary Centre for Security, Reliability and Trust (SnT), University of Luxembourg,SERVAL Research Group
**Duration:** 36 months, full-time
**Salary:** EUR 44,531 gross annually
**Industrial partner:** [CREOS Luxembourg](https://www.creos-net.lu/) 
**Contact:** Dr. Salah Ghamizi (salah.ghamizi[Arobase]uni.lu)

This PhD position focuses on designing **novel neuro-symbolic learning encoders for world models** applied to **power grid systems**. The candidate will investigate architectures that embed the electrical laws governing power flows (e.g. Kirchhoff's laws, power balance constraints) and battery chemical dynamics directly into the learning process, so that the resulting world models remain physically consistent and generalize better than purely data-driven approaches.

Beyond architectural design, the trustworthiness dimension of the thesis will focus on **logic-informed certification** of these models — inspired by algorithms such as alpha-beta-CROWN — to formally verify properties of the learned world models against the symbolic constraints of the domain. The choice of which properties to certify, and their priority, will be driven directly by the operational needs of CREOS, ensuring the work targets what matters most for the real-world reliability of power grid monitoring and simulation tools.

**Profile sought:**
- Master's degree in Computer Science, with a specialization in machine learning preferred
- Strong programming and analytical skills
- Knowledge of foundational and contemporary machine learning approaches (including foundation and generative models)
- Prior experience in ICT for energy is a plus

**How to apply:** Applications (CV + cover letter) must be submitted online through the University of Luxembourg's HR system (applications by email are not considered). Early applications are strongly encouraged, as applications are processed upon receipt: [Application here](https://www.uni.lu/en/jobs/doctoral-researcher-in-trustworthy-world-models-for-critical-systems/)

---

## Doctoral Researcher in Trustworthy World Models for Critical Systems — Neuro-Oncology (with CHL and Charité)

**Host institution:** Interdisciplinary Centre for Security, Reliability and Trust (SnT), University of Luxembourg,SERVAL Research Group
**Duration:** 36 months, full-time
**Salary:** EUR 44,531 gross annually
**Clinical partners:** Departments of Neuro-Oncology, Centre Hospitalier de Luxembourg (CHL) and Charité – Universitätsmedizin Berlin
**Contact:** Dr. Salah Ghamizi (salah.ghamizi[Arobase]uni.lu)

This PhD position focuses on designing **novel neuro-symbolic learning encoders for world models** applied to **neuro-oncology**. The candidate will investigate architectures that embed mathematical models of brain tumor growth and treatment response into multimodal world models combining imaging, tabular clinical data, and graph-structured information, so that predictions remain consistent with known tumor biology and clinical constraints.

Beyond architectural design, the trustworthiness dimension of the thesis will focus on **logic-informed certification** of these models — inspired by algorithms such as alpha-beta-CROWN — to formally verify properties of the learned world models against clinically meaningful constraints. The choice of which properties to certify, and their priority, will be driven directly by clinical input from neuro-oncologists at CHL and Charité, ensuring the work targets what matters most for the real-world reliability of models supporting clinical decision-making.

**Profile sought:**
- Master's degree in Computer Science, with a specialization in machine learning or computer vision preferred
- Strong programming and analytical skills
- Knowledge of foundational and contemporary machine learning approaches (including foundation and generative models)
- Prior experience in ICT for healthcare is a plus

**How to apply:** Applications (CV + cover letter) must be submitted online through the University of Luxembourg's HR system (applications by email are not considered). Early applications are strongly encouraged, as applications are processed upon receipt. [Application here](https://www.uni.lu/en/jobs/doctoral-researcher-in-trustworthy-world-models-for-critical-systems/)

---

Both positions are part of the same research effort on **Trustworthy World Models for multimodal vision-graph-tabular settings**, and the two candidates will work closely together on shared neuro-symbolic encoder architectures and certification methods, while each specializing in the mathematical/physical structure and stakeholder priorities of their own application domain.


# Internship

## Clinical Validation of Generative Models for Medical Image Synthesis

*Evaluating and improving AI models that synthesize PET from MRI, for Alzheimer's disease assessment.*

**Host institution:** Luxembourg Institute of Health (LIH) — BraINE Research Group
**Location:** Luxembourg (on-site)
**Duration & start:** Master's internship; duration and start date to be agreed with the candidate; 6-9 months preferred
**Contact:** Dr. Salah Ghamizi (salah.ghamizi[Arobase]lih.lu)

We have developed predictive models that synthesize PET images from multi-parametric MRI, using publicly available datasets. This internship will define and apply a rigorous clinical evaluation framework for these models — including a downstream disease-staging task and a comprehensive set of clinical performance and reliability metrics — benchmark them across three clinical scenarios (MRI-only, MRI+synthetic PET, MRI+real PET), and then optimize the models to improve these metrics.

**What you'll work on:**
- **State of the art & data.** Review existing literature and appropriate the datasets and in-house developed generative models.
- **Disease-stage prediction.** Build a downstream task predicting Alzheimer's disease stage from synthetic PET using vision-language models (VLMs).
- **Biomarker quantification.** Compute amyloid beta, tau and FDG biomarkers (SUVR, centiloid, A/T/N classification) from synthetic PET.
- **Clinical evaluation metrics.** Assess fidelity, robustness, generalizability, reliability, safety, fairness & bias, explainability (XAI) and uncertainty (evidential deep learning).
- **Benchmarking & optimization.** Compare the three clinical scenarios against these metrics, then fine-tune the generative models to improve them.

**Profile sought:**
- Enrolled in a Master's program in Biomedical Engineering, Computer Science, AI/Data Science, Physics, or a related field
- Strong programming skills in Python, with hands-on experience in deep learning frameworks (PyTorch, MONAI preferred)
- Interest in medical imaging, neuroscience, or clinical AI applications; prior exposure to MRI/PET data is a plus
- Familiarity with explainability, uncertainty quantification, or model evaluation methods is an asset
- Autonomous, rigorous, and comfortable working at the interface of AI research and clinical validation

**How to apply:** Send your CV and your Master transcripts by email.

---

## Multi-Task Learning vs. Mixture of Experts in Medical Imaging

*Identify which medical imaging tasks can be combined, exploring both multi-task learning and mixture-of-experts strategies.*

**Host institution:** Luxembourg Institute of Health (LIH) — BraINE Research Group
**Location:** Luxembourg (on-site)
**Duration & start:** Master's internship; 6 months
**Contact:** Dr. Salah Ghamizi (salah.ghamizi[Arobase]lih.lu)

Deep learning models in medicine are typically designed as "narrow experts" (e.g. only for segmentation or only for classification). Integrating these into a universal system is difficult due to *negative transfer*, where learning one task degrades performance on another. Multi-Task Learning (MTL) attempts to solve this via shared encoders, while Mixture of Experts (MoE) offers a dynamic routing mechanism to specialize computations. This internship will investigate which combinations of medical imaging tasks (e.g. reconstruction + segmentation vs. classification + registration) result in positive inductive transfer, and whether an MoE architecture mitigates negative transfer better than traditional hard-parameter-sharing MTL — contributing a taxonomy of compatible neuroimaging tasks and a novel MoE architecture tailored for multi-objective medical image analysis.

**What you'll work on:**
- **Task identification & architecture design (Month 1).** Review the literature on MTL, MoE, and negative transfer in medical imaging; select three distinct tasks on a unified dataset (e.g. BraTS for tumor segmentation, ID classification, and survival prediction); design the baseline MTL architecture (shared encoder, separate heads) and the MoE architecture (gating network + expert layers).
- **Baseline MTL & task pairing (Months 2-3).** Implement and train single-task baselines to establish gold-standard performance for each task; train the standard MTL model on pairs of tasks to identify which combinations yield positive vs. negative transfer; document the affinity between different tasks.
- **Mixture of Experts implementation (Months 4-5).** Implement a Sparse Mixture of Experts (SMoE) layer within the network backbone; train the MoE model on the task combinations identified as difficult (negative transfer) in the previous milestone; visualize the gating network's choices to understand which experts are activated for which tasks.
- **Evaluation and deliverables (Month 6).** Compare MTL vs. MoE performance across all tasks; finalize the thesis text and bibliography; package the code for the unified framework.

**Deliverables:**
- A research paper (4-8 pages) suitable for submission to a workshop such as MICCAI or MIDL.
- A prototype/tool (command-line or GUI, e.g. using Gradio or Streamlit) that takes an image as input and outputs results for multiple tasks simultaneously, using the MoE backend.

**Profile sought:**
- Enrolled in a Master's program in Computer Science, Biomedical Engineering, AI/Data Science, or a related field
- Strong programming skills in Python, with hands-on experience in deep learning frameworks (PyTorch preferred)
- Interest in medical imaging, multi-task learning, or mixture-of-experts architectures; prior exposure to segmentation or classification models is a plus
- Autonomous, rigorous, and comfortable working at the interface of AI research and medical imaging

**How to apply:** Send your CV and your Master transcripts.

---

## Retrieval-Augmented and Privacy-Preserving Deployment of Foundation Models for MRI

**Host institution:** Luxembourg Institute of Health (LIH) — BraINE Research Group
**Location:** Luxembourg (on-site)
**Duration & start:** Master's internship; duration and start date to be agreed with the candidate; 6-9 months preferred
**Contact:** Dr. Salah Ghamizi (salah.ghamizi[Arobase]lih.lu)

This internship is part of FM2MRI, a project building a foundation model combining Mixture of Experts (MoE) and Retrieval Augmented Generation (RAG) for MRI segmentation and synthesis. Robust models for medical imaging must generalize across the diverse acquisition settings of different hospitals while remaining deployable locally under data privacy and compute constraints. RAG addresses generalization by letting a model retrieve and incorporate relevant information from an institution's own database at inference time, without retraining. This internship will build that retrieval mechanism, integrate it with the project's MoE model, and evaluate the resulting solution both for effectiveness and for its privacy guarantees when packaged for deployment.

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
