---
title: "Multi-Task Learning vs. Mixture of Experts in Medical Imaging"
collection: positions
permalink: /position/internship-mtl-vs-moe
category: internship
status: open
excerpt: "Identify which medical imaging tasks can be combined, exploring both multi-task learning and mixture-of-experts strategies."
host: "Luxembourg Institute of Health (LIH) — BraINE Research Group"
location: "Luxembourg (on-site)"
duration: "Master's internship; 6 months"
contact_email: "salah.ghamizi[at]lih.lu"
---

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
