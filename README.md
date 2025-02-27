# Awesome LMMs Mechanistic Interpretability
All the papers listed in this project come from my usual reading.
If you have found some new and interesting papers, I would appreciate it if you let me know!!!

## Table of Contents
- [Surveys](#Surveys)
- [Blog](#Blog)
- [Papers](#Papers)
  - [Sparse Autoencoder](#Sparse-Autoencoder)
  - [Neuron Analysis](#Neuron-Analysis)
  - [Logit Lens](#Logit-Lens)
  - [Causal Tracing](#Causal-Tracing)
  - [Linear Probing](#Linear-Probing)
  - [Steering Vector](#Steering-Vector)
  - [Representation](#Representation)
  - [Tool](#Tool)

## Surveys:
([Back to Table of Contents](#table-of-contents))
+ [A Survey on Mechanistic Interpretability for Multi-Modal Foundation Models](https://arxiv.org/abs/2502.17516) (Feb. 22, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.17516)

+ [A Review of Multimodal Explainable Artificial Intelligence: Past, Present and Future](https://arxiv.org/abs/2412.14056) (Dec. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14056)

+ [Explainable and Interpretable Multimodal Large Language Models: A Comprehensive Survey](https://arxiv.org/abs/2412.02104) (Dec. 3, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02104)
  
## Blog:
([Back to Table of Contents](#table-of-contents))
+ [Are SAE features from the Base Model still meaningful to LLaVA?](https://www.lesswrong.com/posts/8JTi7N3nQmjoRRuMD/are-sae-features-from-the-base-model-still-meaningful-to-1) (Dec. 6, 2024)

+ [Bridging the VLM and mech interp communities for multimodal interpretability](https://www.lesswrong.com/posts/aa5fzGr8JA3pqvhYC/bridging-the-vlm-and-mech-interp-communities-for-multimodal) (Oct. 28, 2024)

+ [Laying the Foundations for Vision and Multimodal Mechanistic Interpretability & Open Problems](https://www.lesswrong.com/posts/kobJymvvcvhbjWFKe/laying-the-foundations-for-vision-and-multimodal-mechanistic) (May. 14, 2024)

## Papers:
([Back to Table of Contents](#table-of-contents))
### Sparse Autoencoder
+ **SAE 4 LMM** [Large Multi-modal Models Can Interpret Features in Large Multi-modal Models](https://arxiv.org/abs/2411.14982) (Nov. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.14982)
  [![Star](https://img.shields.io/github/stars/EvolvingLMMs-Lab/multimodal-sae.svg?style=social&label=Star)](https://github.com/EvolvingLMMs-Lab/multimodal-sae)
  
### Linear Probing
+ **Probing MLLMs** [Probing Multimodal Large Language Models for Global and Local Semantic Representations](https://arxiv.org/abs/2402.17304) (Jan. 6, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17304)

+ **Probing Hallucination in VIT** [Plausible May Not Be Faithful: Probing Object Hallucination in Vision-Language Pre-training](https://arxiv.org/abs/2210.07688) (Feb. 10, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.07688)

+ **Probing VIT** [Are Vision-Language Transformers Learning Multimodal Representations? A Probing Perspective](https://ojs.aaai.org/index.php/AAAI/article/view/21375) (Jun. 28, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ojs.aaai.org/index.php/AAAI/article/view/21375)
  
### Logit Lens
+ **Attention Lens** [Devils in Middle Layers of Large Vision-Language Models: Interpreting, Detecting and Mitigating Object Hallucinations via Attention Lens](https://www.arxiv.org/abs/2411.16724) (Nov. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2411.16724)
  
### Causal Tracing
+ **Causal Tracing Tool 4 BLIP** [Towards Vision-Language Mechanistic Interpretability: A Causal Tracing Tool for BLIP](https://arxiv.org/abs/2308.14179) (Aug. 27, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14179)
  [![Star](https://img.shields.io/github/stars/vedantpalit/Towards-Vision-Language-Mechanistic-Interpretability.svg?style=social&label=Star)](https://github.com/vedantpalit/Towards-Vision-Language-Mechanistic-Interpretability)
  
### Steering Vector
+ **LMM Concept Explainability** [A Concept-Based Explainability Framework for Large Multimodal Models](https://arxiv.org/abs/2406.08074) (Nov. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.08074)
  [![Star](https://img.shields.io/github/stars/mshukor/xl-vlms.svg?style=social&label=Star)](https://github.com/mshukor/xl-vlms)
  
+ **Concept Sliders** [Concept Sliders: LoRA Adaptors for Precise Control in Diffusion Models](https://link.springer.com/chapter/10.1007/978-3-031-73661-2_10) (Nov. 10, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://link.springer.com/chapter/10.1007/978-3-031-73661-2_10)
  [![Star](https://img.shields.io/github/stars/CompVis/attribute-conl.svg?style=social&label=Star)](https://sliders.baulab.info/)
  
+ **Attribute Control** [Continuous, Subject-Specific Attribute Control in T2I Models by Identifying Semantic Directions](https://arxiv.org/abs/2403.17064) (Mar. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17064)
  [![Star](https://img.shields.io/github/stars/CompVis/attribute-control.svg?style=social&label=Star)](https://github.com/CompVis/attribute-control)
  
### Representation
+ **Fine-tuning Representation Shift** [Analyzing Fine-tuning Representation Shift for Multimodal LLMs Steering](https://arxiv.org/abs/2501.03012) (Jan. 6, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03012)
  [![Star](https://img.shields.io/github/stars/mshukor/xl-vlms.svg?style=social&label=Star)](https://github.com/mshukor/xl-vlms)

+ **Decomposing and Interpreting Image Representations** [Decomposing and Interpreting Image Representations via Text in ViTs Beyond CLIP](https://arxiv.org/abs/2406.01583) (Oct. 21, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01583)
  [![Star](https://img.shields.io/github/stars/SriramB-98/vit-decompose.svg?style=social&label=Star)](https://github.com/SriramB-98/vit-decompose)

+ **Implicit Multimodal Alignment** [Implicit Multimodal Alignment: On the Generalization of Frozen LLMs to Multimodal Inputs](https://arxiv.org/abs/2405.16700) (Oct. 5, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16700)
  [![Star](https://img.shields.io/github/stars/mshukor/ima-lmms.svg?style=social&label=Star)](https://github.com/mshukor/ima-lmms)

+ **Text-Based Decomposition** [Interpreting CLIP's Image Representation via Text-Based Decomposition](https://arxiv.org/abs/2310.05916) (Mar. 29, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05916)
  [![Star](https://img.shields.io/github/stars/yossigandelsman/clip_text_span.svg?style=social&label=Star)](https://github.com/yossigandelsman/clip_text_span)
  
### Neuron Analysis
+ **Multi-Modal Neurons** [Finding and Editing Multi-Modal Neurons in Pre-Trained Transformers](https://arxiv.org/abs/2311.07470) (Jun. 11, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.07470)
  [![Star](https://img.shields.io/github/stars/opanhw/MM_Neurons.svg?style=social&label=Star)](https://github.com/opanhw/MM_Neurons)

+ **Information Storage and Transfer** [Understanding Information Storage and Transfer in Multi-modal Large Language Models](https://arxiv.org/abs/2406.04236) (June. 06, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.04236)
  [![Star](https://img.shields.io/github/stars/IntelLabs/lvlm-interpret.svg?style=social&label=Star)](https://github.com/IntelLabs/lvlm-interpret)

+ **Multimodal In-Context Learning** [What Makes Multimodal In-Context Learning Work?](https://arxiv.org/abs/2404.15736) (April. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15736)
  [![Star](https://img.shields.io/github/stars/folbaeni/multimodal-icl.svg?style=social&label=Star)](https://github.com/folbaeni/multimodal-icl)

+ **Modality-Specific Neurons in MLLMs** [MINER: Mining the Underlying Pattern of Modality-Specific Neurons in Multimodal Large Language Models](https://arxiv.org/abs/2410.04819) (Oct. 7, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.04819)
  [![Star](https://img.shields.io/github/stars/huang-kc/MINER.svg?style=social&label=Star)](https://github.com/huang-kc/MINER)

+ **LLaVA in VQA** [Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering](https://arxiv.org/abs/2411.10950) (Nov. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10950)
  [![Star](https://img.shields.io/github/stars/zepingyu0512/llava-mechanism.svg?style=social&label=Star)](https://github.com/zepingyu0512/llava-mechanism)

+ **What Do VLMs NOTICE?** [What Do VLMs NOTICE? A Mechanistic Interpretability Pipeline for Gaussian-Noise-free Text-Image Corruption and Evaluation](https://arxiv.org/abs/2406.16320) (Oct. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16320)
  [![Star](https://img.shields.io/github/stars/wrudman/NOTICE.svg?style=social&label=Star)](https://anonymous.4open.science/r/NOTICE-ARR-Submission/README.md)
  
### Tool
+ **LLaVA-Intrepret** [Towards Interpreting Visual Information Processing in Vision-Language Models](https://arxiv.org/abs/2410.07149) (Oct. 09, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07149)
  [![Star](https://img.shields.io/github/stars/clemneo/llava-interp.svg?style=social&label=Star)](https://github.com/clemneo/llava-interp)

+ **LVLM-Intrepret** [LVLM-Intrepret: An Interpretability Tool for Large Vision-Language Models](https://arxiv.org/abs/2404.03118) (June. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.03118)
  [![Star](https://img.shields.io/github/stars/IntelLabs/lvlm-interpret.svg?style=social&label=Star)](https://github.com/IntelLabs/lvlm-interpret)




