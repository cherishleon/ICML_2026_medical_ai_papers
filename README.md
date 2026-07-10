# ICML 2026 medical ai papers

Additions or corrections are welcome in Issues! format: Title + Paper Link + Code Link. 

## Table of Contents
- [Large Language Models (LLMs) & NLP](#large-language-models-llms--nlp)
- [Multimodal & Vision-Language (VLM)](#multimodal--vision-language-vlm)
- [Physiological Signals / ECG / PPG / Time-Series / Medical Audio](#physiological-signals--ecg--ppg--time-series)
- [Agents & Reasoning](#agents--reasoning)
- [Benchmarks, Datasets & Toolkits](#benchmarks-datasets--toolkits)
- [Image Segmentation & Diagnosis](#image-segmentation--diagnosis)
- [Others (Surgical AI, Genomics, Federated Learning)](#others-surgical-ai-genomics-federated-learning)

---

## Large Language Models (LLMs) & NLP
* From Token to Token Pair: Efficient Prompt Compression for Large Language Models in Clinical Prediction [[Paper](https://arxiv.org/abs/2605.11774)][[Code](https://github.com/JasonZuu/MedTPE)]
* InfiMed-ORBIT: Aligning LLMs on Open-Ended Complex Tasks via Rubric-Based Incremental Training [[Paper]](https://arxiv.org/abs/2510.15859)[[Code](https://pidneuralode.github.io/ORBIT/)]
* MedREK: Retrieval-Based Editing for Medical LLMs with Key-Aware Prompts [[Paper](https://arxiv.org/abs/2510.13500)][[Code](https://github.com/mylittleriver/MedREK)]
* TwinWeaver: An LLM-Based Foundation Model Framework for Pan-Cancer Digital Twins [[Paper](https://arxiv.org/abs/2601.20906)][[Code](https://github.com/MendenLab/TwinWeaver)]
* PathwayLLM: Explainable Clinical Trajectory Modeling with Structured Pathways for Sepsis Prediction [[Paper]](https://icml.cc/virtual/2026/poster/61641)
* ClinTutor-R1: Advancing Scalable and Robust One-to-Many Alignment in Clinical Socratic Education [[Paper]](https://arxiv.org/abs/2512.05671)[[Code](https://github.com/Zhitao-He/ClinTutor-R1)]
* STT-LLM: Structural-Temporal Tokenization for Adapting LLMs to Longitudinal Clinical Profiles [[Paper]](https://icml.cc/virtual/2026/poster/61629)
* SPR-RAFT: Parameter-Efficient Regression-Aware Fine-Tuning for Biomedical LLM Regression [[Paper]](https://icml.cc/virtual/2026/poster/63748)
* MedCoG: Maximizing LLM Inference Density in Medical Reasoning via Meta-Cognitive Regulation [[Paper]](https://arxiv.org/html/2602.07905v2)
* Expert-guided Clinical Text Augmentation via Query-Based Model Collaboration [[Paper]](https://arxiv.org/abs/2509.21530)
* The Double Dilemma in Multi-Task Radiology Report Generation: A Gradient Dynamics Analysis and Solution [[Paper]](https://arxiv.org/abs/2605.22635)[[Code](https://github.com/vpsg-research/CAME-Grad)]
  
## Multimodal & Vision-Language (VLM)

* Token-Sparse Medical Multimodal Reasoning via Dual-Stream Reinforcement Learning [[Paper]](https://icml.cc/virtual/2026/poster/62640)[[Code](https://github.com/JLINEkai/ViTos)]
* SynerMedGen: Synergizing Medical Multimodal Understanding with Generation via Task Alignment [[Paper]](https://arxiv.org/abs/2605.08724)[[Code](https://github.com/piooip/SynerMedGen)]
* UniMedVL: Unifying Medical Multimodal Understanding and Generation through Observation-Knowledge-Analysis [[Paper]](https://arxiv.org/abs/2510.15710)[[Code]](https://uni-medical.github.io/UniMedVL_Web/index_zh.html)
* MedSIGHT: Towards Grounded Visual Comprehension in Medical Large Vision-Language Models [[Paper](https://icml.cc/virtual/2026/poster/63100)][[Code](https://aofei-chang.github.io/MedSIGHT_Page/)]
* Scalable Medical Multimodal Fusion via Symmetric Consistency Modeling [[Paper](https://icml.cc/virtual/2026/poster/65096)][[Code](https://github.com/xxiaowSun/SMMF)]
* MEDA: Medical-Oriented Activation Editing for Hallucination Mitigation in Medical Large Vision-Language Model [[Paper](https://icml.cc/virtual/2026/poster/63562)]
* LLM-Guided Diagnostic Evidence Alignment for Medical Vision–Language Pretraining under Limited Pairing [[Paper](https://arxiv.org/abs/2602.07540)]
* Med-Scout: Curing MLLMs' Geometric Blindness in Medical Perception via Geometry-Aware RL Post-Training [[Paper](https://arxiv.org/abs/2601.23220)][[Code](https://github.com/HKUSTGZ-ML4Health-Lab/Med-Scout)]
* M-IDoL: Information Decomposition for Modality-Specific and Diverse Representation Learning in Medical Foundation Model [[Paper](https://arxiv.org/abs/2604.08936)]

## Physiological Signals / ECG / PPG / Time-Series
* Physiology-Aware Masked Cross-Modal Reconstruction for Biosignal Representation Learning [[Paper]](https://arxiv.org/abs/2605.00973)[[Code](https://github.com/hzhou3/xMAE)]
* OpenTSLM: Time-Series Language Models for Reasoning over Multivariate Medical Text- and Time-Series Data [[Paper](https://arxiv.org/abs/2510.02410)][[Code](https://github.com/StanfordBDHG/OpenTSLM)]
* BioFormer: Rethinking Cross-Subject Generalization via Spectral Structural Alignment in Biomedical Time-Series [[Paper]](https://arxiv.org/abs/2605.22468)[[Code](https://github.com/NKU-EmbeddedSystem/BioFormer)]
* MoRGEN: Mixture-of-Resolutions Generative Forecasting for Irregularly Sampled Medical Time-Series Data [[Paper](https://icml.cc/virtual/2026/poster/64999)]
* Learning Fingerprints for Medical Time Series with Redundancy-Constrained Information Maximization [[Paper](https://arxiv.org/abs/2605.00130)]
* SGERA: Stein-Guided ECG-Report Alignment for ECG Representation Learning [[Paper]](https://icml.cc/virtual/2026/poster/62258)[[Code](https://github.com/cccccj-03/SGERA)]
* ECG-R1: Protocol-Guided and Modality-Agnostic MLLM for Reliable ECG Interpretation [[Paper]](https://arxiv.org/abs/2602.04279)[[Code]](https://github.com/PKUDigitalHealth/ECG-R1)
* SIGMA-PPG: Statistical-prior Informed Generative Masking Architecture for PPG Foundation Model [[Paper](https://arxiv.org/abs/2601.21031)][[Code](https://github.com/ZonghengGuo/SigmaPPG)]
* Unlocking Cross-Modal Biosignal Synthesis: A Temporally-Aware VAE-Diffusion Model [[Paper]](https://icml.cc/virtual/2026/poster/63091)
* Cardio-mmFlow: A Gaussian-Prior-Free Physics-Informed Flow Matching Framework for Electrocardiogram to mmWave Radar Synthesis [[Paper](https://icml.cc/virtual/2026/poster/62703)]
* Image-to-Brain Signal Generation for Visual Prosthesis with CLIP Guided Multimodal Diffusion Models [[Paper](https://arxiv.org/abs/2509.00787)]
* MedMamba: Multi-View State Space Models with Adaptive Graph Learning for Medical Time Series Classification [[Paper](https://arxiv.org/abs/2605.24961)][[Code](https://github.com/zhangda1018/MedMamba)]
* HEARTS: Benchmarking LLM Reasoning on Health Time Series [[Paper](https://arxiv.org/abs/2603.06638)][[Code](https://github.com/yang-ai-lab/HEARTS)]

### Medical Audio

* MedMosaic: A Challenging Large Scale Benchmark of Diverse Medical Audio [[Paper](https://arxiv.org/abs/2605.00969)][[web](https://huggingface.co/datasets/icml-anon-submission/medmosaic-dataset)]
* Spherical Procrustes Alignment for Reliable Medical Audio Diagnosis [[Paper](https://icml.cc/virtual/2026/poster/62817)][[code](https://github.com/wangying1586/SPA)]
* Listening Through the Noise: Cauchy-Driven Diffusion Bridges for Robust Gastrointestinal Auscultation and Clinical Benchmarking [[Paper]](https://icml.cc/virtual/2026/poster/65341)
* StethoLM: Audio Language Model for Cardiopulmonary Analysis Across Clinical Tasks [[Paper]](https://arxiv.org/abs/2603.00355)[[Code](https://github.com/yishani/StethoLM)]

## Agents & Reasoning

* AgentScore: Autoformulation of Deployable Clinical Scoring Systems [[Paper]](https://arxiv.org/abs/2601.22324v2)
* Ophiuchus: Incentivizing Tool-augmented ''Think with Images'' for Joint Medical Segmentation, Understanding and Reasoning [[Paper]](https://arxiv.org/abs/2512.14157)
* Evidential Reasoning Advances Interpretable Real-World Disease Screening [[Paper]](https://arxiv.org/abs/2605.15171)][[Code](https://github.com/DopamineLcy/EviScreen)]
* MedScope: Incentivizing "Think with Videos" for Clinical Reasoning via Coarse-to-Fine Tool Calling [[Paper](https://arxiv.org/abs/2602.13332)][[Code](https://github.com/SII-WenjieLisjtu/MedScope/tree/main)]
* Optimizing Inference-Time Compute for Medical Reasoning via Uncertainty Quantification [[Paper](https://arxiv.org/abs/2509.24560)][[Code](https://shaohao011.github.io/AdaThink-Med/)]
* 3DMedAgent: Unified Perception-to-Understanding for 3D Medical Analysis [[Paper](https://arxiv.org/abs/2602.18064)]
* From Conflict to Consensus: Boosting Medical Reasoning via Multi-Round Agentic RAG [[Paper](https://arxiv.org/abs/2603.03292)][[Code](https://github.com/NJU-RL/MA-RAG/tree/main)]
* Turning Drift into Constraint: Robust Reasoning Alignment in Non-Stationary Multi-Stream Environments [[Paper](https://arxiv.org/abs/2510.04142)][[Code](https://github.com/XiaoyuYoung/APO)]
* Thinking in Scales: Accelerating Gigapixel Pathology Image Analysis via Adaptive Continuous Reasoning [[Paper](https://arxiv.org/abs/2605.19491)][[Code](https://github.com/JSGe-AI/PathCTM)]
* Why Specialist Models Still Matter: A Heterogeneous Multi-Agent Paradigm for Medical Artificial Intelligence [[Paper](https://arxiv.org/abs/2605.29744)]


## Benchmarks, Datasets & Toolkits

* PyHealth 2.0: A Comprehensive Open-Source Toolkit for Accessible and Reproducible Clinical Deep Learning [[Paper]](https://arxiv.org/abs/2601.16414)
* Seizure-Semiology-Suite (S³): A Clinically Multimodal Dataset, Benchmark, and Models for Seizure Semiology Understanding [[Paper]](https://arxiv.org/abs/2605.21852)[[Code]](https://github.com/LinaZhangUCLA/SeizureSemiologySuite)
* Benchmarking the Scientific Mind: Toward Evaluation of Complex-Reasoning Biomedical VQA [[Paper](https://icml.cc/virtual/2026/poster/64231)]
* CLINIC : Evaluating Multilingual Trustworthiness in Language Models for Healthcare [[Paper](https://arxiv.org/abs/2512.11437)][[Code](https://github.com/AikyamLab/clinic)]
  
## Image Segmentation & Diagnosis

* Are We Overconfident in Models and Results for Semi-Supervised 3D Medical Image Segmentation? [[Paper](https://arxiv.org/abs/2605.25561)][[Code](https://github.com/DirkLiii/TCSeg)]
* Auditing Sybil: Explaining Deep Lung Cancer Risk Prediction Through Generative Interventional Attributions [[Paper](https://arxiv.org/abs/2602.02560)]
* FACT: Fuzzy Alignment with Comorbidity Topology for Reliable Multi-Label Medical Image Diagnosis [[Paper](https://icml.cc/virtual/2026/poster/63862)][[Code](https://github.com/yyuChen9/FACT)]
* Stabilizing In-Context Multi-Source Domain Adaptation for Biomedical Images Through Controls [[Paper](https://icml.cc/virtual/2026/poster/61614)]
* Med-SegLens: Latent-Level Model Diffing for Interpretable Medical Image Segmentation [[Paper](https://arxiv.org/abs/2602.10508)]
* MedCRP-CL: Continual Medical Image Segmentation via Bayesian Nonparametric Semantic Modality Discovery [[Paper](https://arxiv.org/abs/2605.20297)][[Code](https://github.com/zygao930/MedCRP-CL)]
* Shift-Dependent Asymmetry: Orthogonal Inverse Low-Rank Adaptation for Federated Medical Segmentation [[Paper](https://icml.cc/virtual/2026/poster/66734)]
* On Revisiting Entropy for Identifying Mislabeled Medical Images [[Paper](https://arxiv.org/abs/2605.31090)][[Code](https://github.com/MedAITech/SEI)]
* Auditing Sybil: Explaining Deep Lung Cancer Risk Prediction Through Generative Interventional Attributions [[Paper](https://arxiv.org/abs/2602.02560)]
* Dynamic Decision Learning: Test-Time Evolution for Abnormality Grounding in Rare Diseases [[Paper](https://arxiv.org/abs/2604.24972)][[Code](https://lijunrio.github.io/DDL/)]
* ProConMV: Provenance-Enabled Conceptual Framework for Interpretable Multi-View Diabetic Retinopathy Diagnosis


## Others (Surgical AI, Genomics, Federated Learning)

* ORBIT: A Prognostic World Model for Ocular Reasoning Based on Imagined Trajectories [[Paper]](https://openreview.net/forum?id=pd6GY2x8FG)
* Mitigating Surgical Data Imbalance with Dual-Prediction Video Diffusion Model [[Paper]](https://arxiv.org/abs/2510.07345)
* BioToken and BioFM – Biologically-Informed Tokenization Enables Accurate and Efficient Genomic Foundation Models [[Paper]](https://www.biorxiv.org/content/10.1101/2025.03.27.645711v1)[[Code]](https://github.com/m42-health/biofm-eval/)
* Fair-FedMOE: Group-Fair One-Shot Federated Learning via Prototype-Guided Experts for Medical Imaging Analysis [[Paper](https://icml.cc/virtual/2026/poster/62867)]
* Rethinking Federated Prompt Learning for Medical Images: From Textual Tuning to Visual Manifold Anchoring [[Paper](https://icml.cc/virtual/2026/poster/66474)]
* Plug-and-Play Diffusion Meets ADMM: Dual-Variable Coupling for Robust Medical Image Reconstruction [[Paper](https://arxiv.org/abs/2602.23214)][[Code](https://github.com/duchenhe/DC-PnPDP)]
* Geometrically Constrained Stenosis Editing in Coronary Angiography via Entropic Optimal Transport [[Paper](https://arxiv.org/abs/2605.08851)][[Code](https://github.com/LiJialin001/OT-Bridge-Editor)]
* Scaling Vision Transformers for Functional MRI with Flat Maps [[Paper](https://arxiv.org/abs/2510.13768)][[Code](https://github.com/MedARC-AI/CortexMAE)]
* GenCircuit-RL: Reinforcement Learning from Hierarchical Verification for Genetic Circuit Design [[Paper](https://arxiv.org/abs/2605.14215)]
