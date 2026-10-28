# Heng Zhang · 张恒

**Computer Science & Business Analytics undergraduate at Nanyang Technological University, Singapore.**

I work on multimodal learning, AI agents, and model evaluation, with a focus on implementing research ideas and building experiments that make model behaviour easier to understand.

[Academic homepage](https://hzhang086.github.io/) · [Email](mailto:HZHANG086@e.ntu.edu.sg) · [LinkedIn](https://www.linkedin.com/in/heng-zhang-734747321/)

## Featured research — MO-RiskVAE

### Multi-omics survival risk modeling in multiple myeloma

[**Research code →**](https://github.com/HZHANG086/MO-RiskVAE) · [**Paper · arXiv:2604.06267 →**](https://arxiv.org/abs/2604.06267)

**Paper co-author and author of the experimental research code and extensions.**

MO-RiskVAE investigates how latent regularization and representation design affect survival prediction from heterogeneous omics and clinical data. The experiments study regularization scale, MMD/HSIC alternatives, and a hybrid continuous–discrete latent space using Gumbel–Softmax.

**My implementation contributions**

- **Model experiments:** implemented research extensions and ablation code for latent regularization and continuous–discrete representations.
- **Evaluation workflows:** wrote experiment orchestration, seed aggregation, C-index evaluation, bootstrap confidence intervals, and paired-comparison utilities.
- **Research analysis:** wrote scripts for latent-space analysis, risk stratification, Kaplan–Meier plots, and experimental figures.

The work builds on the [MyeVAE framework](https://github.com/JiaGengChang/myevae); upstream authorship and license notices are retained. The public repository contains the available experimental source, with patient-level data and checkpoints excluded. Its README documents the current reproduction limitations.

*MO-RiskVAE: A Multi-Omics Variational Autoencoder for Survival Risk Modeling in Multiple Myeloma* — Zixuan Chen, **Heng Zhang**, YuPeng Qin, WenPeng Xing, Qiang Wang, Da Wang, Changting Lin, Meng Han. **arXiv preprint, 2026.**

## Selected application — GasAI-Select

[**Code & local demo →**](https://github.com/HZHANG086/GasAI-Select)

An interactive instrument-selection prototype built with Python and Streamlit. I implemented natural-language requirement parsing, Chinese budget matching, explainable candidate ranking, and the application interface. The public edition runs offline with 12 fictional product records and includes six passing retrieval, data-hygiene, and UI tests.

**Stack:** Python · Streamlit · rule-based retrieval · synthetic data. No API key or external model service is required.

## Research interests

| Area | Focus |
| --- | --- |
| Multimodal learning | Multi-omics integration, variational autoencoders, survival modeling |
| AI agents | Retrieval-augmented generation, knowledge graphs, scientific workflows |
| Model evaluation | Controlled ablations, robustness testing, statistical comparisons |

## Background & tools

- **Education:** dual degree in Computer Science and Business, specialising in Business Analytics, at NTU.
- **Research:** NTU Generative AI Lab; Xidian University’s Hangzhou Research Institute; previously Zhejiang University’s Binjiang Research Institute.
- **Tools:** Python, PyTorch, scikit-learn, NumPy, pandas, Linux, Git, Java, and C/C++.

For research details, project context, and my CV, visit my [academic homepage](https://hzhang086.github.io/).

