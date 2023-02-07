# Awesome-LLM-Generated-Text-Detection-Materials [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated, but probably biased and incomplete, list of LLM-generated text detection resources.

If you want to contribute to this list, feel free to pull a request. Also you can contact [Ruixiang Tang](https://www.ruixiangtang.net/) from the [Data Lab](http://faculty.cs.tamu.edu/xiahu/) at Rice University through email: rt39@rice.edu.


## What is LLM-generated Text Detection?

The emergence of large language models (LLMs) has resulted in the production of LLM-generated texts that is highly sophisticated and almost indistinguishable from texts written by humans. However, this has also sparked concerns about the potential misuse of such texts, such as spreading misinformation and causing disruptions in the education system.

we group exitsting methods into two categories: **black-box detection** and **white-box detection**. Black-box detection methods are limited to API-level access to LLMs. They rely on collecting text samples from human and machine sources, respectively, to train a classification model that can be used to discriminate between LLM- and human-generated texts. 

An alternative is white-box detection, in this scenario, the detector has full access to the LLMs and can control the model's generation behavior for traceability purposes. In practice, black-box detectors are commonly constructed by external entities, whereas white-box detection is generally carried out by LLM developers.

## Table of Contents
* [Review Paper](#Review-Paper)

* [Black-Box Detection](#Black-Box-Detection)
  * Data Collection
  * Detection Feature Selectio
  * Classification Mode
* [White-Box Detection](#White-Box-Detection)
  * Post-hoc Watermarking
  * Inference Time Watermark
  

## Review Paper
  * [The Science of Detecting LLM-Generated Texts](https://github.com/datamllab/The-Science-of-LLM-generated-Text-Detection)
  * [Machine Generated Text: A Comprehensive Survey of Threat Models and Detection Methods](https://arxiv.org/pdf/2210.07321.pdf)
  * [Automatic Detection of Machine Generated Text: A Critical Survey](https://arxiv.org/pdf/2011.01314.pdf)
  * [Deepfake Text Detection: Limitations and Opportunities](https://arxiv.org/pdf/2210.09421.pdf)
  * [A Brief Survey on Deep Learning Based Data Hiding](http://staff.ustc.edu.cn/~zhangwm/Paper/2021_30.pdf)
  * [Making Machine Learning Robust Against Adversarial Inputs](https://dl.acm.org/doi/pdf/10.1145/3134599)


## Black-Box Detection
  * [How Close is ChatGPT to Human Experts? Comparison Corpus, Evaluation, and Detection](https://arxiv.org/pdf/2301.07597.pdf)
  * [GLTR: Statistical Detection and Visualization of Generated Text](https://arxiv.org/pdf/1906.04043.pdf)
  * [Automatic Detection of Generated Text is Easiest when Humans are Fooled](http://aclanthology.lst.uni-saarland.de/2020.acl-main.164.pdf)
  * [Neural Deepfake Detection with Factual Structure of Text](https://arxiv.org/pdf/2010.07475.pdf)
  * [Defending Against Neural Fake News](https://arxiv.org/pdf/1905.12616.pdf)
  * [All That’s ‘Human’ Is Not Gold: Evaluating Human Evaluation of Generated Text](https://arxiv.org/pdf/2107.00061.pdf)
  * [The Limitations of Stylometry for Detecting Machine-Generated Fake News](https://aclanthology.org/2020.cl-2.8.pdf)
  * [MAUVE: Measuring the Gap Between Neural Text and Human Text using Divergence Frontiers](https://proceedings.neurips.cc/paper/2021/file/260c2432a0eecc28ce03c10dadc078a4-Paper.pdf)
  * [RoFT: A Tool for Evaluating Human Detection of Machine-Generated Text](https://arxiv.org/pdf/2010.03070.pdf)
  * [TURINGBENCH: A Benchmark Environment for Turing Test in the Age of Neural Text Generation](https://arxiv.org/pdf/2109.13296.pdf)
  * [Cross-Domain Detection of GPT-2-Generated Technical Text](https://aclanthology.org/2022.naacl-main.88.pdf)
  * [A Benchmark Corpus for the Detection of Automatically Generated Text in Academic Publications](https://arxiv.org/pdf/2202.02013.pdf)
  * [Unsupervised and Distributional Detection of Machine-Generated Text](https://arxiv.org/pdf/2111.02878.pdf)
  * [Threat Scenarios and Best Practices for Neural Fake News Detection](https://aclanthology.org/2022.coling-1.106.pdf)
  * [Real or Fake Text?: Investigating Human Ability to Detect Boundaries Between Human-Written and Machine-Generated Text](https://arxiv.org/pdf/2212.12672.pdf)
  * [Unraveling the Mystery of Artifacts in Machine Generated Text](https://aclanthology.org/2022.lrec-1.744.pdf)
  * [Detecting Bot-Generated Text by Characterizing Linguistic Accommodation in Human-Bot Interactions](https://aclanthology.org/2021.findings-acl.286.pdf)
  * [Automatic Detection of Machine Generated Texts: Need More Tokens](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9983964&tag=1)
  * [CoCo: Coherence-Enhanced Machine-Generated Text Detection Under Data Limitation With Contrastive Learning](https://arxiv.org/pdf/2212.10341.pdf)
  * [Feature-based detection of automated language models: tackling GPT-2, GPT-3 and Grover](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8049133/)
  * [Release strategies and the social impacts of language models](https://arxiv.org/pdf/1908.09203.pdf)
  * [Adversarial Robustness of Neural-Statistical Features in Detection of Generative Transformer](https://arxiv.org/abs/2203.07983)
  

## White-Box Detection
  * [Attribution and Obfuscation of Neural Text Authorship: A Data Mining Perspective](https://arxiv.org/pdf/2210.10488.pdf)
  * [Adversarial Watermarking Transformer: Towards Tracing Text Provenance with Data Hiding](https://arxiv.org/pdf/2009.03015.pdf)
  * [Through the Looking Glass: Learning to Attribute Synthetic Text Generated by Language Models](https://aclanthology.org/2021.eacl-main.155.pdf)
  * [Tracing Text Provenance via Context-Aware Lexical Substitution](https://ojs.aaai.org/index.php/AAAI/article/view/21415)
  * [On Information Hiding in Natural Language Systems](https://arxiv.org/pdf/2203.06512.pdf)
  * [DeepHider: A Covert NLP Watermarking FrameworkBasedon Multi-task Learning](https://arxiv.org/pdf/2208.04676.pdf)
