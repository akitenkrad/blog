---
draft: false
title: "arXiv @ 2023.08.26"
date: 2023-08-26
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.08.26"
    identifier: arxiv_20230826
    parent: 202308_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.LG (13)](#cslg-13)
- [cs.CL (17)](#cscl-17)
- [cs.CV (42)](#cscv-42)
- [cs.RO (4)](#csro-4)
- [cs.SI (3)](#cssi-3)
- [cs.HC (5)](#cshc-5)
- [eess.IV (2)](#eessiv-2)
- [cs.AI (6)](#csai-6)
- [cs.CR (2)](#cscr-2)
- [cs.IR (4)](#csir-4)
- [q-bio.QM (1)](#q-bioqm-1)
- [cs.SD (5)](#cssd-5)
- [cs.MA (1)](#csma-1)
- [cs.SE (4)](#csse-4)
- [cs.IT (1)](#csit-1)
- [cs.MM (2)](#csmm-2)
- [cs.CE (1)](#csce-1)
- [eess.SY (1)](#eesssy-1)
- [physics.chem-ph (1)](#physicschem-ph-1)
- [eess.SP (1)](#eesssp-1)

## cs.LG (13)



### (1/116) Business Metric-Aware Forecasting for Inventory Management (Helen Zhou et al., 2023)

{{<citation>}}

Helen Zhou, Sercan O. Arik, Jingtao Wang. (2023)  
**Business Metric-Aware Forecasting for Inventory Management**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2308.13118v1)  

---


**ABSTRACT**  
Time-series forecasts play a critical role in business planning. However, forecasters typically optimize objectives that are agnostic to downstream business goals and thus can produce forecasts misaligned with business preferences. In this work, we demonstrate that optimization of conventional forecasting metrics can often lead to sub-optimal downstream business performance. Focusing on the inventory management setting, we derive an efficient procedure for computing and optimizing proxies of common downstream business metrics in an end-to-end differentiable manner. We explore a wide range of plausible cost trade-off scenarios, and empirically demonstrate that end-to-end optimization often outperforms optimization of standard business-agnostic forecasting metrics (by up to 45.7% for a simple scaling model, and up to 54.0% for an LSTM encoder-decoder model). Finally, we discuss how our findings could benefit other business contexts.

{{</citation>}}


### (2/116) Contrastive Learning of Temporal Distinctiveness for Survival Analysis in Electronic Health Records (Mohsen Nayebi Kerdabadi et al., 2023)

{{<citation>}}

Mohsen Nayebi Kerdabadi, Arya Hadizadeh Moghaddam, Bin Liu, Mei Liu, Zijun Yao. (2023)  
**Contrastive Learning of Temporal Distinctiveness for Survival Analysis in Electronic Health Records**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2308.13104v1)  

---


**ABSTRACT**  
Survival analysis plays a crucial role in many healthcare decisions, where the risk prediction for the events of interest can support an informative outlook for a patient's medical journey. Given the existence of data censoring, an effective way of survival analysis is to enforce the pairwise temporal concordance between censored and observed data, aiming to utilize the time interval before censoring as partially observed time-to-event labels for supervised learning. Although existing studies mostly employed ranking methods to pursue an ordering objective, contrastive methods which learn a discriminative embedding by having data contrast against each other, have not been explored thoroughly for survival analysis. Therefore, in this paper, we propose a novel Ontology-aware Temporality-based Contrastive Survival (OTCSurv) analysis framework that utilizes survival durations from both censored and observed data to define temporal distinctiveness and construct negative sample pairs with adjustable hardness for contrastive learning. Specifically, we first use an ontological encoder and a sequential self-attention encoder to represent the longitudinal EHR data with rich contexts. Second, we design a temporal contrastive loss to capture varying survival durations in a supervised setting through a hardness-aware negative sampling mechanism. Last, we incorporate the contrastive task into the time-to-event predictive task with multiple loss components. We conduct extensive experiments using a large EHR dataset to forecast the risk of hospitalized patients who are in danger of developing acute kidney injury (AKI), a critical and urgent medical condition. The effectiveness and explainability of the proposed model are validated through comprehensive quantitative and qualitative studies.

{{</citation>}}


### (3/116) Multivariate Time Series Anomaly Detection: Fancy Algorithms and Flawed Evaluation Methodology (Mohamed El Amine Sehili et al., 2023)

{{<citation>}}

Mohamed El Amine Sehili, Zonghua Zhang. (2023)  
**Multivariate Time Series Anomaly Detection: Fancy Algorithms and Flawed Evaluation Methodology**  

---
Primary Category: cs.LG  
Categories: G-3; I-2-6; I-2-m, cs-AI, cs-LG, cs-PF, cs.LG, stat-CO, stat-ML  
Keywords: Anomaly Detection, Computer Vision, NLP, Natural Language Processing, Time Series  
[Paper Link](http://arxiv.org/abs/2308.13068v1)  

---


**ABSTRACT**  
Multivariate Time Series (MVTS) anomaly detection is a long-standing and challenging research topic that has attracted tremendous research effort from both industry and academia recently. However, a careful study of the literature makes us realize that 1) the community is active but not as organized as other sibling machine learning communities such as Computer Vision (CV) and Natural Language Processing (NLP), and 2) most proposed solutions are evaluated using either inappropriate or highly flawed protocols, with an apparent lack of scientific foundation. So flawed is one very popular protocol, the so-called \pa protocol, that a random guess can be shown to systematically outperform \emph{all} algorithms developed so far. In this paper, we review and evaluate many recent algorithms using more robust protocols and discuss how a normally good protocol may have weaknesses in the context of MVTS anomaly detection and how to mitigate them. We also share our concerns about benchmark datasets, experiment design and evaluation methodology we observe in many works. Furthermore, we propose a simple, yet challenging, baseline algorithm based on Principal Components Analysis (PCA) that surprisingly outperforms many recent Deep Learning (DL) based approaches on popular benchmark datasets. The main objective of this work is to stimulate more effort towards important aspects of the research such as data, experiment design, evaluation methodology and result interpretability, instead of putting the highest weight on the design of increasingly more complex and "fancier" algorithms.

{{</citation>}}


### (4/116) Extreme Risk Mitigation in Reinforcement Learning using Extreme Value Theory (Karthik Somayaji NS et al., 2023)

{{<citation>}}

Karthik Somayaji NS, Yu Wang, Malachi Schram, Jan Drgona, Mahantesh Halappanavar, Frank Liu, Peng Li. (2023)  
**Extreme Risk Mitigation in Reinforcement Learning using Extreme Value Theory**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.13011v1)  

---


**ABSTRACT**  
Risk-sensitive reinforcement learning (RL) has garnered significant attention in recent years due to the growing interest in deploying RL agents in real-world scenarios. A critical aspect of risk awareness involves modeling highly rare risk events (rewards) that could potentially lead to catastrophic outcomes. These infrequent occurrences present a formidable challenge for data-driven methods aiming to capture such risky events accurately. While risk-aware RL techniques do exist, their level of risk aversion heavily relies on the precision of the state-action value function estimation when modeling these rare occurrences. Our work proposes to enhance the resilience of RL agents when faced with very rare and risky events by focusing on refining the predictions of the extreme values predicted by the state-action value function distribution. To achieve this, we formulate the extreme values of the state-action value function distribution as parameterized distributions, drawing inspiration from the principles of extreme value theory (EVT). This approach effectively addresses the issue of infrequent occurrence by leveraging EVT-based parameterization. Importantly, we theoretically demonstrate the advantages of employing these parameterized distributions in contrast to other risk-averse algorithms. Our evaluations show that the proposed method outperforms other risk averse RL algorithms on a diverse range of benchmark tasks, each encompassing distinct risk scenarios.

{{</citation>}}


### (5/116) Low-count Time Series Anomaly Detection (Philipp Renz et al., 2023)

{{<citation>}}

Philipp Renz, Kurt Cutajar, Niall Twomey, Gavin K. C. Cheung, Hanting Xie. (2023)  
**Low-count Time Series Anomaly Detection**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ML  
Keywords: Anomaly Detection, Time Series  
[Paper Link](http://arxiv.org/abs/2308.12925v1)  

---


**ABSTRACT**  
Low-count time series describe sparse or intermittent events, which are prevalent in large-scale online platforms that capture and monitor diverse data types. Several distinct challenges surface when modelling low-count time series, particularly low signal-to-noise ratios (when anomaly signatures are provably undetectable), and non-uniform performance (when average metrics are not representative of local behaviour). The time series anomaly detection community currently lacks explicit tooling and processes to model and reliably detect anomalies in these settings. We address this gap by introducing a novel generative procedure for creating benchmark datasets comprising of low-count time series with anomalous segments. Via a mixture of theoretical and empirical analysis, our work explains how widely-used algorithms struggle with the distribution overlap between normal and anomalous segments. In order to mitigate this shortcoming, we then leverage our findings to demonstrate how anomaly score smoothing consistently improves performance. The practical utility of our analysis and recommendation is validated on a real-world dataset containing sales data for retail stores.

{{</citation>}}


### (6/116) Evaluating the Vulnerabilities in ML systems in terms of adversarial attacks (John Harshith et al., 2023)

{{<citation>}}

John Harshith, Mantej Singh Gill, Madhan Jothimani. (2023)  
**Evaluating the Vulnerabilities in ML systems in terms of adversarial attacks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.12918v1)  

---


**ABSTRACT**  
There have been recent adversarial attacks that are difficult to find. These new adversarial attacks methods may pose challenges to current deep learning cyber defense systems and could influence the future defense of cyberattacks. The authors focus on this domain in this research paper. They explore the consequences of vulnerabilities in AI systems. This includes discussing how they might arise, differences between randomized and adversarial examples and also potential ethical implications of vulnerabilities. Moreover, it is important to train the AI systems appropriately when they are in testing phase and getting them ready for broader use.

{{</citation>}}


### (7/116) Easy attention: A simple self-attention mechanism for Transformers (Marcial Sanchis-Agudo et al., 2023)

{{<citation>}}

Marcial Sanchis-Agudo, Yuning Wang, Karthik Duraisamy, Ricardo Vinuesa. (2023)  
**Easy attention: A simple self-attention mechanism for Transformers**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: LSTM, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2308.12874v1)  

---


**ABSTRACT**  
To improve the robustness of transformer neural networks used for temporal-dynamics prediction of chaotic systems, we propose a novel attention mechanism called easy attention. Due to the fact that self attention only makes usage of the inner product of queries and keys, it is demonstrated that the keys, queries and softmax are not necessary for obtaining the attention score required to capture long-term dependencies in temporal sequences. Through implementing singular-value decomposition (SVD) on the softmax attention score, we further observe that the self attention compresses contribution from both queries and keys in the spanned space of the attention score. Therefore, our proposed easy-attention method directly treats the attention scores as learnable parameters. This approach produces excellent results when reconstructing and predicting the temporal dynamics of chaotic systems exhibiting more robustness and less complexity than the self attention or the widely-used long short-term memory (LSTM) network. Our results show great potential for applications in more complex high-dimensional dynamical systems.

{{</citation>}}


### (8/116) Fast Adversarial Training with Smooth Convergence (Mengnan Zhao et al., 2023)

{{<citation>}}

Mengnan Zhao, Lihe Zhang, Yuqiu Kong, Baocai Yin. (2023)  
**Fast Adversarial Training with Smooth Convergence**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Adversarial Training  
[Paper Link](http://arxiv.org/abs/2308.12857v1)  

---


**ABSTRACT**  
Fast adversarial training (FAT) is beneficial for improving the adversarial robustness of neural networks. However, previous FAT work has encountered a significant issue known as catastrophic overfitting when dealing with large perturbation budgets, \ie the adversarial robustness of models declines to near zero during training.   To address this, we analyze the training process of prior FAT work and observe that catastrophic overfitting is accompanied by the appearance of loss convergence outliers.   Therefore, we argue a moderately smooth loss convergence process will be a stable FAT process that solves catastrophic overfitting.   To obtain a smooth loss convergence process, we propose a novel oscillatory constraint (dubbed ConvergeSmooth) to limit the loss difference between adjacent epochs. The convergence stride of ConvergeSmooth is introduced to balance convergence and smoothing. Likewise, we design weight centralization without introducing additional hyperparameters other than the loss balance coefficient.   Our proposed methods are attack-agnostic and thus can improve the training stability of various FAT techniques.   Extensive experiments on popular datasets show that the proposed methods efficiently avoid catastrophic overfitting and outperform all previous FAT methods. Code is available at \url{https://github.com/FAT-CS/ConvergeSmooth}.

{{</citation>}}


### (9/116) Match-And-Deform: Time Series Domain Adaptation through Optimal Transport and Temporal Alignment (François Painblanc et al., 2023)

{{<citation>}}

François Painblanc, Laetitia Chapel, Nicolas Courty, Chloé Friguet, Charlotte Pelletier, Romain Tavenard. (2023)  
**Match-And-Deform: Time Series Domain Adaptation through Optimal Transport and Temporal Alignment**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2308.12686v2)  

---


**ABSTRACT**  
While large volumes of unlabeled data are usually available, associated labels are often scarce. The unsupervised domain adaptation problem aims at exploiting labels from a source domain to classify data from a related, yet different, target domain. When time series are at stake, new difficulties arise as temporal shifts may appear in addition to the standard feature distribution shift. In this paper, we introduce the Match-And-Deform (MAD) approach that aims at finding correspondences between the source and target time series while allowing temporal distortions. The associated optimization problem simultaneously aligns the series thanks to an optimal transport loss and the time stamps through dynamic time warping. When embedded into a deep neural network, MAD helps learning new representations of time series that both align the domains and maximize the discriminative power of the network. Empirical studies on benchmark datasets and remote sensing data demonstrate that MAD makes meaningful sample-to-sample pairing and time shift estimation, reaching similar or better classification performance than state-of-the-art deep time series domain adaptation strategies.

{{</citation>}}


### (10/116) Try with Simpler -- An Evaluation of Improved Principal Component Analysis in Log-based Anomaly Detection (Lin Yang et al., 2023)

{{<citation>}}

Lin Yang, Junjie Chen, Zhihao Gong, Shutao Gao, Hongyu Zhang, Yue Kang, Huaan Li. (2023)  
**Try with Simpler -- An Evaluation of Improved Principal Component Analysis in Log-based Anomaly Detection**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-SE, cs.LG  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2308.12612v1)  

---


**ABSTRACT**  
The rapid growth of deep learning (DL) has spurred interest in enhancing log-based anomaly detection. This approach aims to extract meaning from log events (log message templates) and develop advanced DL models for anomaly detection. However, these DL methods face challenges like heavy reliance on training data, labels, and computational resources due to model complexity. In contrast, traditional machine learning and data mining techniques are less data-dependent and more efficient but less effective than DL. To make log-based anomaly detection more practical, the goal is to enhance traditional techniques to match DL's effectiveness. Previous research in a different domain (linking questions on Stack Overflow) suggests that optimized traditional techniques can rival state-of-the-art DL methods. Drawing inspiration from this concept, we conducted an empirical study. We optimized the unsupervised PCA (Principal Component Analysis), a traditional technique, by incorporating lightweight semantic-based log representation. This addresses the issue of unseen log events in training data, enhancing log representation. Our study compared seven log-based anomaly detection methods, including four DL-based, two traditional, and the optimized PCA technique, using public and industrial datasets. Results indicate that the optimized unsupervised PCA technique achieves similar effectiveness to advanced supervised/semi-supervised DL methods while being more stable with limited training data and resource-efficient. This demonstrates the adaptability and strength of traditional techniques through small yet impactful adaptations.

{{</citation>}}


### (11/116) Multivariate Time-Series Anomaly Detection with Contaminated Data: Application to Physiological Signals (Thi Kieu Khanh Ho et al., 2023)

{{<citation>}}

Thi Kieu Khanh Ho, Narges Armanfard. (2023)  
**Multivariate Time-Series Anomaly Detection with Contaminated Data: Application to Physiological Signals**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, eess-SP  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2308.12563v1)  

---


**ABSTRACT**  
Mainstream unsupervised anomaly detection algorithms often excel in academic datasets, yet their real-world performance is restricted due to the controlled experimental conditions involving clean training data. Addressing the challenge of training with noise, a prevalent issue in practical anomaly detection, is frequently overlooked. In a pioneering endeavor, this study delves into the realm of label-level noise within sensory time-series anomaly detection (TSAD). This paper presents a novel and practical end-to-end unsupervised TSAD when the training data are contaminated with anomalies. The introduced approach, called TSAD-C, is devoid of access to abnormality labels during the training phase. TSAD-C encompasses three modules: a Decontaminator to rectify the abnormalities (aka noise) present in the training data, a Variable Dependency Modeling module to capture both long-term intra- and inter-variable dependencies within the decontaminated data that can be considered as a surrogate of the pure normal data, and an Anomaly Scoring module to detect anomalies. Our extensive experiments conducted on three widely used physiological datasets conclusively demonstrate that our approach surpasses existing methodologies, thus establishing a new state-of-the-art performance in the field.

{{</citation>}}


### (12/116) Variational Information Pursuit with Large Language and Multimodal Models for Interpretable Predictions (Kwan Ho Ryan Chan et al., 2023)

{{<citation>}}

Kwan Ho Ryan Chan, Aditya Chattopadhyay, Benjamin David Haeffele, Rene Vidal. (2023)  
**Variational Information Pursuit with Large Language and Multimodal Models for Interpretable Predictions**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, stat-ML  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2308.12562v1)  

---


**ABSTRACT**  
Variational Information Pursuit (V-IP) is a framework for making interpretable predictions by design by sequentially selecting a short chain of task-relevant, user-defined and interpretable queries about the data that are most informative for the task. While this allows for built-in interpretability in predictive models, applying V-IP to any task requires data samples with dense concept-labeling by domain experts, limiting the application of V-IP to small-scale tasks where manual data annotation is feasible. In this work, we extend the V-IP framework with Foundational Models (FMs) to address this limitation. More specifically, we use a two-step process, by first leveraging Large Language Models (LLMs) to generate a sufficiently large candidate set of task-relevant interpretable concepts, then using Large Multimodal Models to annotate each data sample by semantic similarity with each concept in the generated concept set. While other interpretable-by-design frameworks such as Concept Bottleneck Models (CBMs) require an additional step of removing repetitive and non-discriminative concepts to have good interpretability and test performance, we mathematically and empirically justify that, with a sufficiently informative and task-relevant query (concept) set, the proposed FM+V-IP method does not require any type of concept filtering. In addition, we show that FM+V-IP with LLM generated concepts can achieve better test performance than V-IP with human annotated concepts, demonstrating the effectiveness of LLMs at generating efficient query sets. Finally, when compared to other interpretable-by-design frameworks such as CBMs, FM+V-IP can achieve competitive test performance using fewer number of concepts/queries in both cases with filtered or unfiltered concept sets.

{{</citation>}}


### (13/116) A Co-training Approach for Noisy Time Series Learning (Weiqi Zhang et al., 2023)

{{<citation>}}

Weiqi Zhang, Jianfeng Zhang, Jia Li, Fugee Tsung. (2023)  
**A Co-training Approach for Noisy Time Series Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2308.12551v1)  

---


**ABSTRACT**  
In this work, we focus on robust time series representation learning. Our assumption is that real-world time series is noisy and complementary information from different views of the same time series plays an important role while analyzing noisy input. Based on this, we create two views for the input time series through two different encoders. We conduct co-training based contrastive learning iteratively to learn the encoders. Our experiments demonstrate that this co-training approach leads to a significant improvement in performance. Especially, by leveraging the complementary information from different views, our proposed TS-CoT method can mitigate the impact of data noise and corruption. Empirical evaluations on four time series benchmarks in unsupervised and semi-supervised settings reveal that TS-CoT outperforms existing methods. Furthermore, the representations learned by TS-CoT can transfer well to downstream tasks through fine-tuning.

{{</citation>}}


## cs.CL (17)



### (14/116) Sentence Embedding Models for Ancient Greek Using Multilingual Knowledge Distillation (Kevin Krahn et al., 2023)

{{<citation>}}

Kevin Krahn, Derrick Tate, Andrew C. Lamicela. (2023)  
**Sentence Embedding Models for Ancient Greek Using Multilingual Knowledge Distillation**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-CL, cs.CL  
Keywords: BERT, Embedding, Knowledge Distillation, Multilingual, Sentence Embedding  
[Paper Link](http://arxiv.org/abs/2308.13116v1)  

---


**ABSTRACT**  
Contextual language models have been trained on Classical languages, including Ancient Greek and Latin, for tasks such as lemmatization, morphological tagging, part of speech tagging, authorship attribution, and detection of scribal errors. However, high-quality sentence embedding models for these historical languages are significantly more difficult to achieve due to the lack of training data. In this work, we use a multilingual knowledge distillation approach to train BERT models to produce sentence embeddings for Ancient Greek text. The state-of-the-art sentence embedding approaches for high-resource languages use massive datasets, but our distillation approach allows our Ancient Greek models to inherit the properties of these models while using a relatively small amount of translated sentence data. We build a parallel sentence dataset using a sentence-embedding alignment method to align Ancient Greek documents with English translations, and use this dataset to train our models. We evaluate our models on translation search, semantic similarity, and semantic retrieval tasks and investigate translation bias. We make our training and evaluation datasets freely available at https://github.com/kevinkrahn/ancient-greek-datasets .

{{</citation>}}


### (15/116) Towards a Holistic Approach: Understanding Sociodemographic Biases in NLP Models using an Interdisciplinary Lens (Pranav Narayanan Venkit, 2023)

{{<citation>}}

Pranav Narayanan Venkit. (2023)  
**Towards a Holistic Approach: Understanding Sociodemographic Biases in NLP Models using an Interdisciplinary Lens**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Bias, NLP, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2308.13089v1)  

---


**ABSTRACT**  
The rapid growth in the usage and applications of Natural Language Processing (NLP) in various sociotechnical solutions has highlighted the need for a comprehensive understanding of bias and its impact on society. While research on bias in NLP has expanded, several challenges persist that require attention. These include the limited focus on sociodemographic biases beyond race and gender, the narrow scope of analysis predominantly centered on models, and the technocentric implementation approaches. This paper addresses these challenges and advocates for a more interdisciplinary approach to understanding bias in NLP. The work is structured into three facets, each exploring a specific aspect of bias in NLP.

{{</citation>}}


### (16/116) Financial News Analytics Using Fine-Tuned Llama 2 GPT Model (Bohdan M. Pavlyshenko, 2023)

{{<citation>}}

Bohdan M. Pavlyshenko. (2023)  
**Financial News Analytics Using Fine-Tuned Llama 2 GPT Model**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CE, cs-CL, cs-IR, cs-LG, cs.CL  
Keywords: Financial, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2308.13032v1)  

---


**ABSTRACT**  
The paper considers the possibility to fine-tune Llama 2 Large Language Model (LLM) for the multitask analysis of financial news. For fine-tuning, the PEFT/LoRA based approach was used. In the study, the model was fine-tuned for the following tasks: analysing a text from financial market perspectives, highlighting main points of a text, summarizing a text and extracting named entities with appropriate sentiments. The obtained results show that the fine-tuned Llama 2 model can perform a multitask financial news analysis with a specified structure of response, part of response can be a structured text and another part of data can have JSON format for further processing. Extracted sentiments for named entities can be considered as predictive features in supervised machine learning models with quantitative target variables.

{{</citation>}}


### (17/116) Large Language Models Vote: Prompting for Rare Disease Identification (David Oniani et al., 2023)

{{<citation>}}

David Oniani, Jordan Hilsman, Hang Dong, Fengyi Gao, Shiven Verma, Yanshan Wang. (2023)  
**Large Language Models Vote: Prompting for Rare Disease Identification**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Few-Shot, Language Model  
[Paper Link](http://arxiv.org/abs/2308.12890v2)  

---


**ABSTRACT**  
The emergence of generative Large Language Models (LLMs) emphasizes the need for accurate and efficient prompting approaches. LLMs are often applied in Few-Shot Learning (FSL) contexts, where tasks are executed with minimal training data. FSL has become popular in many Artificial Intelligence (AI) subdomains, including AI for health. Rare diseases affect a small fraction of the population. Rare disease identification from clinical notes inherently requires FSL techniques due to limited data availability. Manual data collection and annotation is both expensive and time-consuming. In this paper, we propose Models-Vote Prompting (MVP), a flexible prompting approach for improving the performance of LLM queries in FSL settings. MVP works by prompting numerous LLMs to perform the same tasks and then conducting a majority vote on the resulting outputs. This method achieves improved results to any one model in the ensemble on one-shot rare disease identification and classification tasks. We also release a novel rare disease dataset for FSL, available to those who signed the MIMIC-IV Data Use Agreement (DUA). Furthermore, in using MVP, each model is prompted multiple times, substantially increasing the time needed for manual annotation, and to address this, we assess the feasibility of using JSON for automating generative LLM evaluation.

{{</citation>}}


### (18/116) Inducing Causal Structure for Abstractive Text Summarization (Lu Chen et al., 2023)

{{<citation>}}

Lu Chen, Ruqing Zhang, Wei Huang, Wei Chen, Jiafeng Guo, Xueqi Cheng. (2023)  
**Inducing Causal Structure for Abstractive Text Summarization**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Abstractive Text Summarization, Seq2Seq, Sequence-to-Sequence, Summarization, Text Summarization  
[Paper Link](http://arxiv.org/abs/2308.12888v1)  

---


**ABSTRACT**  
The mainstream of data-driven abstractive summarization models tends to explore the correlations rather than the causal relationships. Among such correlations, there can be spurious ones which suffer from the language prior learned from the training corpus and therefore undermine the overall effectiveness of the learned model. To tackle this issue, we introduce a Structural Causal Model (SCM) to induce the underlying causal structure of the summarization data. We assume several latent causal factors and non-causal factors, representing the content and style of the document and summary. Theoretically, we prove that the latent factors in our SCM can be identified by fitting the observed training data under certain conditions. On the basis of this, we propose a Causality Inspired Sequence-to-Sequence model (CI-Seq2Seq) to learn the causal representations that can mimic the causal factors, guiding us to pursue causal information for summary generation. The key idea is to reformulate the Variational Auto-encoder (VAE) to fit the joint distribution of the document and summary variables from the training corpus. Experimental results on two widely used text summarization datasets demonstrate the advantages of our approach.

{{</citation>}}


### (19/116) Text Similarity from Image Contents using Statistical and Semantic Analysis Techniques (Sagar Kulkarni et al., 2023)

{{<citation>}}

Sagar Kulkarni, Sharvari Govilkar, Dhiraj Amin. (2023)  
**Text Similarity from Image Contents using Statistical and Semantic Analysis Techniques**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BERT, NLP, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2308.12842v1)  

---


**ABSTRACT**  
Plagiarism detection is one of the most researched areas among the Natural Language Processing(NLP) community. A good plagiarism detection covers all the NLP methods including semantics, named entities, paraphrases etc. and produces detailed plagiarism reports. Detection of Cross Lingual Plagiarism requires deep knowledge of various advanced methods and algorithms to perform effective text similarity checking. Nowadays the plagiarists are also advancing themselves from hiding the identity from being catch in such offense. The plagiarists are bypassed from being detected with techniques like paraphrasing, synonym replacement, mismatching citations, translating one language to another. Image Content Plagiarism Detection (ICPD) has gained importance, utilizing advanced image content processing to identify instances of plagiarism to ensure the integrity of image content. The issue of plagiarism extends beyond textual content, as images such as figures, graphs, and tables also have the potential to be plagiarized. However, image content plagiarism detection remains an unaddressed challenge. Therefore, there is a critical need to develop methods and systems for detecting plagiarism in image content. In this paper, the system has been implemented to detect plagiarism form contents of Images such as Figures, Graphs, Tables etc. Along with statistical algorithms such as Jaccard and Cosine, introducing semantic algorithms such as LSA, BERT, WordNet outperformed in detecting efficient and accurate plagiarism.

{{</citation>}}


### (20/116) Use of LLMs for Illicit Purposes: Threats, Prevention Measures, and Vulnerabilities (Maximilian Mozes et al., 2023)

{{<citation>}}

Maximilian Mozes, Xuanli He, Bennett Kleinberg, Lewis D. Griffin. (2023)  
**Use of LLMs for Illicit Purposes: Threats, Prevention Measures, and Vulnerabilities**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CR, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.12833v1)  

---


**ABSTRACT**  
Spurred by the recent rapid increase in the development and distribution of large language models (LLMs) across industry and academia, much recent work has drawn attention to safety- and security-related threats and vulnerabilities of LLMs, including in the context of potentially criminal activities. Specifically, it has been shown that LLMs can be misused for fraud, impersonation, and the generation of malware; while other authors have considered the more general problem of AI alignment. It is important that developers and practitioners alike are aware of security-related problems with such models. In this paper, we provide an overview of existing - predominantly scientific - efforts on identifying and mitigating threats and vulnerabilities arising from LLMs. We present a taxonomy describing the relationship between threats caused by the generative capabilities of LLMs, prevention measures intended to address such threats, and vulnerabilities arising from imperfect prevention measures. With our work, we hope to raise awareness of the limitations of LLMs in light of such security concerns, among both experienced developers and novel users of such technologies.

{{</citation>}}


### (21/116) Harnessing the Power of David against Goliath: Exploring Instruction Data Generation without Using Closed-Source Models (Yue Wang et al., 2023)

{{<citation>}}

Yue Wang, Xinrui Wang, Juntao Li, Jinxiong Chang, Qishen Zhang, Zhongyi Liu, Guannan Zhang, Min Zhang. (2023)  
**Harnessing the Power of David against Goliath: Exploring Instruction Data Generation without Using Closed-Source Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2308.12711v1)  

---


**ABSTRACT**  
Instruction tuning is instrumental in enabling Large Language Models~(LLMs) to follow user instructions to complete various open-domain tasks. The success of instruction tuning depends on the availability of high-quality instruction data. Owing to the exorbitant cost and substandard quality of human annotation, recent works have been deeply engaged in the exploration of the utilization of powerful closed-source models to generate instruction data automatically. However, these methods carry potential risks arising from the usage requirements of powerful closed-source models, which strictly forbid the utilization of their outputs to develop machine learning models. To deal with this problem, in this work, we explore alternative approaches to generate high-quality instruction data that do not rely on closed-source models. Our exploration includes an investigation of various existing instruction generation methods, culminating in the integration of the most efficient variant with two novel strategies to enhance the quality further. Evaluation results from two benchmarks and the GPT-4 model demonstrate the effectiveness of our generated instruction data, which can outperform Alpaca, a method reliant on closed-source models. We hope that more progress can be achieved in generating high-quality instruction data without using closed-source models.

{{</citation>}}


### (22/116) Improving Translation Faithfulness of Large Language Models via Augmenting Instructions (Yijie Chen et al., 2023)

{{<citation>}}

Yijie Chen, Yijin Liu, Fandong Meng, Yufeng Chen, Jinan Xu, Jie Zhou. (2023)  
**Improving Translation Faithfulness of Large Language Models via Augmenting Instructions**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: BLEU, BLOOM, Embedding, LLaMA, Language Model  
[Paper Link](http://arxiv.org/abs/2308.12674v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) present strong general capabilities, and a current compelling challenge is stimulating their specialized capabilities, such as machine translation, through low-cost instruction tuning. The standard instruction-following data is sequentially organized as the concatenation of an instruction, an input, and a response. As the attention mechanism of LLMs has limitations on local focus, LLMs tend to focus more on the words or sentences nearby at each position. This leads to a high risk of instruction forgetting during decoding. To alleviate the above issues, We propose SWIE (Segment-Weighted Instruction Embedding) and an instruction-following dataset OVERMISS. SWIE improves the model instruction understanding by adding a global instruction representation on the following input and response representations. OVERMISS improves model faithfulness by comparing over-translation and miss-translation results with the correct translation. We apply our methods to two main-stream open-source LLMs, BLOOM and LLaMA. The experimental results demonstrate significant improvements in translation performance with SWIE based on BLOOMZ-3b, particularly in zero-shot and long text translations due to reduced instruction forgetting risk. Additionally, OVERMISS outperforms the baseline in translation performance (e.g. an increase in BLEU scores from 0.69 to 3.12 and an average improvement of 0.48 percentage comet scores for LLaMA-7b) with further enhancements seen in models combining OVERMISS and SWIE (e.g. the BLUE scores increase up to 0.56 from English to German across three different backbones), and both exhibit improvements in the faithfulness metric based on word alignment.

{{</citation>}}


### (23/116) From Chatter to Matter: Addressing Critical Steps of Emotion Recognition Learning in Task-oriented Dialogue (Shutong Feng et al., 2023)

{{<citation>}}

Shutong Feng, Nurul Lubis, Benjamin Ruppik, Christian Geishauser, Michael Heck, Hsien-chin Lin, Carel van Niekerk, Renato Vukovic, Milica Gašić. (2023)  
**From Chatter to Matter: Addressing Critical Steps of Emotion Recognition Learning in Task-oriented Dialogue**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue, Emotion Recognition  
[Paper Link](http://arxiv.org/abs/2308.12648v1)  

---


**ABSTRACT**  
Emotion recognition in conversations (ERC) is a crucial task for building human-like conversational agents. While substantial efforts have been devoted to ERC for chit-chat dialogues, the task-oriented counterpart is largely left unattended. Directly applying chit-chat ERC models to task-oriented dialogues (ToDs) results in suboptimal performance as these models overlook key features such as the correlation between emotions and task completion in ToDs. In this paper, we propose a framework that turns a chit-chat ERC model into a task-oriented one, addressing three critical aspects: data, features and objective. First, we devise two ways of augmenting rare emotions to improve ERC performance. Second, we use dialogue states as auxiliary features to incorporate key information from the goal of the user. Lastly, we leverage a multi-aspect emotion definition in ToDs to devise a multi-task learning objective and a novel emotion-distance weighted loss function. Our framework yields significant improvements for a range of chit-chat ERC models on EmoWOZ, a large-scale dataset for user emotion in ToDs. We further investigate the generalisability of the best resulting model to predict user satisfaction in different ToD datasets. A comparison with supervised baselines shows a strong zero-shot capability, highlighting the potential usage of our framework in wider scenarios.

{{</citation>}}


### (24/116) Advancing Hungarian Text Processing with HuSpaCy: Efficient and Accurate NLP Pipelines (György Orosz et al., 2023)

{{<citation>}}

György Orosz, Gergő Szabó, Péter Berkecz, Zsolt Szántó, Richárd Farkas. (2023)  
**Advancing Hungarian Text Processing with HuSpaCy: Efficient and Accurate NLP Pipelines**  

---
Primary Category: cs.CL  
Categories: 68T50, I-2-7, cs-AI, cs-CL, cs.CL, stat-ML  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2308.12635v1)  

---


**ABSTRACT**  
This paper presents a set of industrial-grade text processing models for Hungarian that achieve near state-of-the-art performance while balancing resource efficiency and accuracy. Models have been implemented in the spaCy framework, extending the HuSpaCy toolkit with several improvements to its architecture. Compared to existing NLP tools for Hungarian, all of our pipelines feature all basic text processing steps including tokenization, sentence-boundary detection, part-of-speech tagging, morphological feature tagging, lemmatization, dependency parsing and named entity recognition with high accuracy and throughput. We thoroughly evaluated the proposed enhancements, compared the pipelines with state-of-the-art tools and demonstrated the competitive performance of the new models in all text preprocessing steps. All experiments are reproducible and the pipelines are freely available under a permissive license.

{{</citation>}}


### (25/116) Mind vs. Mouth: On Measuring Re-judge Inconsistency of Social Bias in Large Language Models (Yachao Zhao et al., 2023)

{{<citation>}}

Yachao Zhao, Bo Wang, Dongming Zhao, Kun Huang, Yan Wang, Ruifang He, Yuexian Hou. (2023)  
**Mind vs. Mouth: On Measuring Re-judge Inconsistency of Social Bias in Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Bias, ChatGPT, GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2308.12578v1)  

---


**ABSTRACT**  
Recent researches indicate that Pre-trained Large Language Models (LLMs) possess cognitive constructs similar to those observed in humans, prompting researchers to investigate the cognitive aspects of LLMs. This paper focuses on explicit and implicit social bias, a distinctive two-level cognitive construct in psychology. It posits that individuals' explicit social bias, which is their conscious expression of bias in the statements, may differ from their implicit social bias, which represents their unconscious bias. We propose a two-stage approach and discover a parallel phenomenon in LLMs known as "re-judge inconsistency" in social bias. In the initial stage, the LLM is tasked with automatically completing statements, potentially incorporating implicit social bias. However, in the subsequent stage, the same LLM re-judges the biased statement generated by itself but contradicts it. We propose that this re-judge inconsistency can be similar to the inconsistency between human's unaware implicit social bias and their aware explicit social bias. Experimental investigations on ChatGPT and GPT-4 concerning common gender biases examined in psychology corroborate the highly stable nature of the re-judge inconsistency. This finding may suggest that diverse cognitive constructs emerge as LLMs' capabilities strengthen. Consequently, leveraging psychological theories can provide enhanced insights into the underlying mechanisms governing the expressions of explicit and implicit constructs in LLMs.

{{</citation>}}


### (26/116) A Small and Fast BERT for Chinese Medical Punctuation Restoration (Tongtao Ling et al., 2023)

{{<citation>}}

Tongtao Ling, Chen Liao, Zhipeng Yu, Lei Chen, Shilei Huang, Yi Liu. (2023)  
**A Small and Fast BERT for Chinese Medical Punctuation Restoration**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2308.12568v1)  

---


**ABSTRACT**  
In clinical dictation, utterances after automatic speech recognition (ASR) without explicit punctuation marks may lead to the misunderstanding of dictated reports. To give a precise and understandable clinical report with ASR, automatic punctuation restoration is required. Considering a practical scenario, we propose a fast and light pre-trained model for Chinese medical punctuation restoration based on 'pretraining and fine-tuning' paradigm. In this work, we distill pre-trained models by incorporating supervised contrastive learning and a novel auxiliary pre-training task (Punctuation Mark Prediction) to make it well-suited for punctuation restoration. Our experiments on various distilled models reveal that our model can achieve 95% performance while 10% model size relative to state-of-the-art Chinese RoBERTa.

{{</citation>}}


### (27/116) CALM : A Multi-task Benchmark for Comprehensive Assessment of Language Model Bias (Vipul Gupta et al., 2023)

{{<citation>}}

Vipul Gupta, Pranav Narayanan Venkit, Hugo Laurençon, Shomir Wilson, Rebecca J. Passonneau. (2023)  
**CALM : A Multi-task Benchmark for Comprehensive Assessment of Language Model Bias**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: Bias, Language Model  
[Paper Link](http://arxiv.org/abs/2308.12539v1)  

---


**ABSTRACT**  
As language models (LMs) become increasingly powerful, it is important to quantify and compare them for sociodemographic bias with potential for harm. Prior bias measurement datasets are sensitive to perturbations in their manually designed templates, therefore unreliable. To achieve reliability, we introduce the Comprehensive Assessment of Language Model bias (CALM), a benchmark dataset to quantify bias in LMs across three tasks. We integrate 16 existing datasets across different domains, such as Wikipedia and news articles, to filter 224 templates from which we construct a dataset of 78,400 examples. We compare the diversity of CALM with prior datasets on metrics such as average semantic similarity, and variation in template length, and test the sensitivity to small perturbations. We show that our dataset is more diverse and reliable than previous datasets, thus better capture the breadth of linguistic variation required to reliably evaluate model bias. We evaluate 20 large language models including six prominent families of LMs such as Llama-2. In two LM series, OPT and Bloom, we found that larger parameter models are more biased than lower parameter models. We found the T0 series of models to be the least biased. Furthermore, we noticed a tradeoff between gender and racial bias with increasing model size in some model series. The code is available at https://github.com/vipulgupta1011/CALM.

{{</citation>}}


### (28/116) CARE: Co-Attention Network for Joint Entity and Relation Extraction (Wenjun Kong et al., 2023)

{{<citation>}}

Wenjun Kong, Yamei Xia. (2023)  
**CARE: Co-Attention Network for Joint Entity and Relation Extraction**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Attention, Relation Extraction  
[Paper Link](http://arxiv.org/abs/2308.12531v1)  

---


**ABSTRACT**  
Joint entity and relation extraction is the fundamental task of information extraction, consisting of two subtasks: named entity recognition and relation extraction. Most existing joint extraction methods suffer from issues of feature confusion or inadequate interaction between two subtasks. In this work, we propose a Co-Attention network for joint entity and Relation Extraction (CARE). Our approach involves learning separate representations for each subtask, aiming to avoid feature overlap. At the core of our approach is the co-attention module that captures two-way interaction between two subtasks, allowing the model to leverage entity information for relation prediction and vice versa, thus promoting mutual enhancement. Extensive experiments on three joint entity-relation extraction benchmark datasets (NYT, WebNLG and SciERC) show that our proposed model achieves superior performance, surpassing existing baseline models.

{{</citation>}}


### (29/116) Large Language Model as Autonomous Decision Maker (Yining Ye et al., 2023)

{{<citation>}}

Yining Ye, Xin Cong, Yujia Qin, Yankai Lin, Zhiyuan Liu, Maosong Sun. (2023)  
**Large Language Model as Autonomous Decision Maker**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2308.12519v1)  

---


**ABSTRACT**  
While large language models (LLMs) exhibit impressive language understanding and in-context learning abilities, their decision-making ability still heavily relies on the guidance of task-specific expert knowledge when solving real-world tasks. To unleash the potential of LLMs as autonomous decision makers, this paper presents an approach JuDec to endow LLMs with the self-judgment ability, enabling LLMs to achieve autonomous judgment and exploration for decision making. Specifically, in JuDec, Elo-based Self-Judgment Mechanism is designed to assign Elo scores to decision steps to judge their values and utilities via pairwise comparisons between two solutions and then guide the decision-searching process toward the optimal solution accordingly. Experimental results on the ToolBench dataset demonstrate JuDec's superiority over baselines, achieving over 10% improvement in Pass Rate on diverse tasks. It offers higher-quality solutions and reduces costs (ChatGPT API calls), highlighting its effectiveness and efficiency.

{{</citation>}}


### (30/116) American Stories: A Large-Scale Structured Text Dataset of Historical U.S. Newspapers (Melissa Dell et al., 2023)

{{<citation>}}

Melissa Dell, Jacob Carlson, Tom Bryan, Emily Silcock, Abhishek Arora, Zejiang Shen, Luca D'Amico-Wong, Quan Le, Pablo Querubin, Leander Heldring. (2023)  
**American Stories: A Large-Scale Structured Text Dataset of Historical U.S. Newspapers**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CV, cs.CL, econ-GN, q-fin-EC  
Keywords: OCR  
[Paper Link](http://arxiv.org/abs/2308.12477v1)  

---


**ABSTRACT**  
Existing full text datasets of U.S. public domain newspapers do not recognize the often complex layouts of newspaper scans, and as a result the digitized content scrambles texts from articles, headlines, captions, advertisements, and other layout regions. OCR quality can also be low. This study develops a novel, deep learning pipeline for extracting full article texts from newspaper images and applies it to the nearly 20 million scans in Library of Congress's public domain Chronicling America collection. The pipeline includes layout detection, legibility classification, custom OCR, and association of article texts spanning multiple bounding boxes. To achieve high scalability, it is built with efficient architectures designed for mobile phones. The resulting American Stories dataset provides high quality data that could be used for pre-training a large language model to achieve better understanding of historical English and historical world knowledge. The dataset could also be added to the external database of a retrieval-augmented language model to make historical information - ranging from interpretations of political events to minutiae about the lives of people's ancestors - more widely accessible. Furthermore, structured article texts facilitate using transformer-based methods for popular social science applications like topic classification, detection of reproduced content, and news story clustering. Finally, American Stories provides a massive silver quality dataset for innovating multimodal layout analysis models and other multimodal applications.

{{</citation>}}


## cs.CV (42)



### (31/116) Interpretable Image Quality Assessment via CLIP with Multiple Antonym-Prompt Pairs (Takamichi Miyata, 2023)

{{<citation>}}

Takamichi Miyata. (2023)  
**Interpretable Image Quality Assessment via CLIP with Multiple Antonym-Prompt Pairs**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2308.13094v1)  

---


**ABSTRACT**  
No reference image quality assessment (NR-IQA) is a task to estimate the perceptual quality of an image without its corresponding original image. It is even more difficult to perform this task in a zero-shot manner, i.e., without task-specific training. In this paper, we propose a new zero-shot and interpretable NRIQA method that exploits the ability of a pre-trained visionlanguage model to estimate the correlation between an image and a textual prompt. The proposed method employs a prompt pairing strategy and multiple antonym-prompt pairs corresponding to carefully selected descriptive features corresponding to the perceptual image quality. Thus, the proposed method is able to identify not only the perceptual quality evaluation of the image, but also the cause on which the quality evaluation is based. Experimental results show that the proposed method outperforms existing zero-shot NR-IQA methods in terms of accuracy and can evaluate the causes of perceptual quality degradation.

{{</citation>}}


### (32/116) EgoBlur: Responsible Innovation in Aria (Nikhil Raina et al., 2023)

{{<citation>}}

Nikhil Raina, Guruprasad Somasundaram, Kang Zheng, Steve Saarinen, Jeff Messiner, Mark Schwesinger, Luis Pesqueira, Ishita Prasad, Edward Miller, Prince Gupta, Mingfei Yan, Richard Newcombe, Carl Ren, Omkar M Parkhi. (2023)  
**EgoBlur: Responsible Innovation in Aria**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.13093v1)  

---


**ABSTRACT**  
Project Aria pushes the frontiers of Egocentric AI with large-scale real-world data collection using purposely designed glasses with privacy first approach. To protect the privacy of bystanders being recorded by the glasses, our research protocols are designed to ensure recorded video is processed by an AI anonymization model that removes bystander faces and vehicle license plates. Detected face and license plate regions are processed with a Gaussian blur such that these personal identification information (PII) regions are obscured. This process helps to ensure that anonymized versions of the video is retained for research purposes. In Project Aria, we have developed a state-of-the-art anonymization system EgoBlur. In this paper, we present extensive analysis of EgoBlur on challenging datasets comparing its performance with other state-of-the-art systems from industry and academia including extensive Responsible AI analysis on recently released Casual Conversations V2 dataset.

{{</citation>}}


### (33/116) SurGNN: Explainable visual scene understanding and assessment of surgical skill using graph neural networks (Shuja Khalid et al., 2023)

{{<citation>}}

Shuja Khalid, Frank Rudzicz. (2023)  
**SurGNN: Explainable visual scene understanding and assessment of surgical skill using graph neural networks**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV, eess-IV  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2308.13073v1)  

---


**ABSTRACT**  
This paper explores how graph neural networks (GNNs) can be used to enhance visual scene understanding and surgical skill assessment. By using GNNs to analyze the complex visual data of surgical procedures represented as graph structures, relevant features can be extracted and surgical skill can be predicted. Additionally, GNNs provide interpretable results, revealing the specific actions, instruments, or anatomical structures that contribute to the predicted skill metrics. This can be highly beneficial for surgical educators and trainees, as it provides valuable insights into the factors that contribute to successful surgical performance and outcomes. SurGNN proposes two concurrent approaches -- one supervised and the other self-supervised. The paper also briefly discusses other automated surgical skill evaluation techniques and highlights the limitations of hand-crafted features in capturing the intricacies of surgical expertise. We use the proposed methods to achieve state-of-the-art results on EndoVis19, and custom datasets. The working implementation of the code can be found at https://github.com/<redacted>.

{{</citation>}}


### (34/116) Spherical Vision Transformer for 360-degree Video Saliency Prediction (Mert Cokelek et al., 2023)

{{<citation>}}

Mert Cokelek, Nevrez Imamoglu, Cagri Ozcinar, Erkut Erdem, Aykut Erdem. (2023)  
**Spherical Vision Transformer for 360-degree Video Saliency Prediction**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-MM, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.13004v1)  

---


**ABSTRACT**  
The growing interest in omnidirectional videos (ODVs) that capture the full field-of-view (FOV) has gained 360-degree saliency prediction importance in computer vision. However, predicting where humans look in 360-degree scenes presents unique challenges, including spherical distortion, high resolution, and limited labelled data. We propose a novel vision-transformer-based model for omnidirectional videos named SalViT360 that leverages tangent image representations. We introduce a spherical geometry-aware spatiotemporal self-attention mechanism that is capable of effective omnidirectional video understanding. Furthermore, we present a consistency-based unsupervised regularization term for projection-based 360-degree dense-prediction models to reduce artefacts in the predictions that occur after inverse projection. Our approach is the first to employ tangent images for omnidirectional saliency prediction, and our experimental results on three ODV saliency datasets demonstrate its effectiveness compared to the state-of-the-art.

{{</citation>}}


### (35/116) Scenimefy: Learning to Craft Anime Scene via Semi-Supervised Image-to-Image Translation (Yuxin Jiang et al., 2023)

{{<citation>}}

Yuxin Jiang, Liming Jiang, Shuai Yang, Chen Change Loy. (2023)  
**Scenimefy: Learning to Craft Anime Scene via Semi-Supervised Image-to-Image Translation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2308.12968v1)  

---


**ABSTRACT**  
Automatic high-quality rendering of anime scenes from complex real-world images is of significant practical value. The challenges of this task lie in the complexity of the scenes, the unique features of anime style, and the lack of high-quality datasets to bridge the domain gap. Despite promising attempts, previous efforts are still incompetent in achieving satisfactory results with consistent semantic preservation, evident stylization, and fine details. In this study, we propose Scenimefy, a novel semi-supervised image-to-image translation framework that addresses these challenges. Our approach guides the learning with structure-consistent pseudo paired data, simplifying the pure unsupervised setting. The pseudo data are derived uniquely from a semantic-constrained StyleGAN leveraging rich model priors like CLIP. We further apply segmentation-guided data selection to obtain high-quality pseudo supervision. A patch-wise contrastive style loss is introduced to improve stylization and fine details. Besides, we contribute a high-resolution anime scene dataset to facilitate future research. Our extensive experiments demonstrate the superiority of our method over state-of-the-art baselines in terms of both perceptual quality and quantitative performance.

{{</citation>}}


### (36/116) Qwen-VL: A Frontier Large Vision-Language Model with Versatile Abilities (Jinze Bai et al., 2023)

{{<citation>}}

Jinze Bai, Shuai Bai, Shusheng Yang, Shijie Wang, Sinan Tan, Peng Wang, Junyang Lin, Chang Zhou, Jingren Zhou. (2023)  
**Qwen-VL: A Frontier Large Vision-Language Model with Versatile Abilities**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2308.12966v1)  

---


**ABSTRACT**  
We introduce the Qwen-VL series, a set of large-scale vision-language models designed to perceive and understand both text and images. Comprising Qwen-VL and Qwen-VL-Chat, these models exhibit remarkable performance in tasks like image captioning, question answering, visual localization, and flexible interaction. The evaluation covers a wide range of tasks including zero-shot captioning, visual or document visual question answering, and grounding. We demonstrate the Qwen-VL outperforms existing Large Vision Language Models (LVLMs). We present their architecture, training, capabilities, and performance, highlighting their contributions to advancing multimodal artificial intelligence. Code, demo and models are available at https://github.com/QwenLM/Qwen-VL.

{{</citation>}}


### (37/116) Dense Text-to-Image Generation with Attention Modulation (Yunji Kim et al., 2023)

{{<citation>}}

Yunji Kim, Jiyoung Lee, Jin-Hwa Kim, Jung-Woo Ha, Jun-Yan Zhu. (2023)  
**Dense Text-to-Image Generation with Attention Modulation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-GR, cs-LG, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2308.12964v1)  

---


**ABSTRACT**  
Existing text-to-image diffusion models struggle to synthesize realistic images given dense captions, where each text prompt provides a detailed description for a specific image region. To address this, we propose DenseDiffusion, a training-free method that adapts a pre-trained text-to-image model to handle such dense captions while offering control over the scene layout. We first analyze the relationship between generated images' layouts and the pre-trained model's intermediate attention maps. Next, we develop an attention modulation method that guides objects to appear in specific regions according to layout guidance. Without requiring additional fine-tuning or datasets, we improve image generation performance given dense captions regarding both automatic and human evaluation scores. In addition, we achieve similar-quality visual results with models specifically trained with layout conditions.

{{</citation>}}


### (38/116) Motion-Guided Masking for Spatiotemporal Representation Learning (David Fan et al., 2023)

{{<citation>}}

David Fan, Jue Wang, Shuai Liao, Yi Zhu, Vimal Bhat, Hector Santos-Villalobos, Rohith MV, Xinyu Li. (2023)  
**Motion-Guided Masking for Spatiotemporal Representation Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2308.12962v1)  

---


**ABSTRACT**  
Several recent works have directly extended the image masked autoencoder (MAE) with random masking into video domain, achieving promising results. However, unlike images, both spatial and temporal information are important for video understanding. This suggests that the random masking strategy that is inherited from the image MAE is less effective for video MAE. This motivates the design of a novel masking algorithm that can more efficiently make use of video saliency. Specifically, we propose a motion-guided masking algorithm (MGM) which leverages motion vectors to guide the position of each mask over time. Crucially, these motion-based correspondences can be directly obtained from information stored in the compressed format of the video, which makes our method efficient and scalable. On two challenging large-scale video benchmarks (Kinetics-400 and Something-Something V2), we equip video MAE with our MGM and achieve up to +$1.3\%$ improvement compared to previous state-of-the-art methods. Additionally, our MGM achieves equivalent performance to previous video MAE using up to $66\%$ fewer training epochs. Lastly, we show that MGM generalizes better to downstream transfer learning and domain adaptation tasks on the UCF101, HMDB51, and Diving48 datasets, achieving up to +$4.9\%$ improvement compared to baseline methods.

{{</citation>}}


### (39/116) Less is More: Towards Efficient Few-shot 3D Semantic Segmentation via Training-free Networks (Xiangyang Zhu et al., 2023)

{{<citation>}}

Xiangyang Zhu, Renrui Zhang, Bowei He, Ziyu Guo, Jiaming Liu, Hao Dong, Peng Gao. (2023)  
**Less is More: Towards Efficient Few-shot 3D Semantic Segmentation via Training-free Networks**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2308.12961v1)  

---


**ABSTRACT**  
To reduce the reliance on large-scale datasets, recent works in 3D segmentation resort to few-shot learning. Current 3D few-shot semantic segmentation methods first pre-train the models on `seen' classes, and then evaluate their generalization performance on `unseen' classes. However, the prior pre-training stage not only introduces excessive time overhead, but also incurs a significant domain gap on `unseen' classes. To tackle these issues, we propose an efficient Training-free Few-shot 3D Segmentation netwrok, TFS3D, and a further training-based variant, TFS3D-T. Without any learnable parameters, TFS3D extracts dense representations by trigonometric positional encodings, and achieves comparable performance to previous training-based methods. Due to the elimination of pre-training, TFS3D can alleviate the domain gap issue and save a substantial amount of time. Building upon TFS3D, TFS3D-T only requires to train a lightweight query-support transferring attention (QUEST), which enhances the interaction between the few-shot query and support data. Experiments demonstrate TFS3D-T improves previous state-of-the-art methods by +6.93% and +17.96% mIoU respectively on S3DIS and ScanNet, while reducing the training time by -90%, indicating superior effectiveness and efficiency.

{{</citation>}}


### (40/116) Towards Realistic Zero-Shot Classification via Self Structural Semantic Alignment (Sheng Zhang et al., 2023)

{{<citation>}}

Sheng Zhang, Muzammal Naseer, Guangyi Chen, Zhiqiang Shen, Salman Khan, Kun Zhang, Fahad Khan. (2023)  
**Towards Realistic Zero-Shot Classification via Self Structural Semantic Alignment**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Language Model, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2308.12960v1)  

---


**ABSTRACT**  
Large-scale pre-trained Vision Language Models (VLMs) have proven effective for zero-shot classification. Despite the success, most traditional VLMs-based methods are restricted by the assumption of partial source supervision or ideal vocabularies, which rarely satisfy the open-world scenario. In this paper, we aim at a more challenging setting, Realistic Zero-Shot Classification, which assumes no annotation but instead a broad vocabulary. To address this challenge, we propose the Self Structural Semantic Alignment (S^3A) framework, which extracts the structural semantic information from unlabeled data while simultaneously self-learning. Our S^3A framework adopts a unique Cluster-Vote-Prompt-Realign (CVPR) algorithm, which iteratively groups unlabeled data to derive structural semantics for pseudo-supervision. Our CVPR process includes iterative clustering on images, voting within each cluster to identify initial class candidates from the vocabulary, generating discriminative prompts with large language models to discern confusing candidates, and realigning images and the vocabulary as structural semantic alignment. Finally, we propose to self-learn the CLIP image encoder with both individual and structural semantic alignment through a teacher-student learning strategy. Our comprehensive experiments across various generic and fine-grained benchmarks demonstrate that the S^3A method offers substantial improvements over existing VLMs-based approaches, achieving a more than 15% accuracy improvement over CLIP on average. Our codes, models, and prompts are publicly released at https://github.com/sheng-eatamath/S3A.

{{</citation>}}


### (41/116) Perspective-aware Convolution for Monocular 3D Object Detection (Jia-Quan Yu et al., 2023)

{{<citation>}}

Jia-Quan Yu, Soo-Chang Pei. (2023)  
**Perspective-aware Convolution for Monocular 3D Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2308.12938v1)  

---


**ABSTRACT**  
Monocular 3D object detection is a crucial and challenging task for autonomous driving vehicle, while it uses only a single camera image to infer 3D objects in the scene. To address the difficulty of predicting depth using only pictorial clue, we propose a novel perspective-aware convolutional layer that captures long-range dependencies in images. By enforcing convolutional kernels to extract features along the depth axis of every image pixel, we incorporates perspective information into network architecture. We integrate our perspective-aware convolutional layer into a 3D object detector and demonstrate improved performance on the KITTI3D dataset, achieving a 23.9\% average precision in the easy benchmark. These results underscore the importance of modeling scene clues for accurate depth inference and highlight the benefits of incorporating scene structure in network design. Our perspective-aware convolutional layer has the potential to enhance object detection accuracy by providing more precise and context-aware feature extraction.

{{</citation>}}


### (42/116) CDAN: Convolutional Dense Attention-guided Network for Low-light Image Enhancement (Hossein Shakibania et al., 2023)

{{<citation>}}

Hossein Shakibania, Sina Raoufi, Hassan Khotanlou. (2023)  
**CDAN: Convolutional Dense Attention-guided Network for Low-light Image Enhancement**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2308.12902v2)  

---


**ABSTRACT**  
Low-light images, characterized by inadequate illumination, pose challenges of diminished clarity, muted colors, and reduced details. Low-light image enhancement, an essential task in computer vision, aims to rectify these issues by improving brightness, contrast, and overall perceptual quality, thereby facilitating accurate analysis and interpretation. This paper introduces the Convolutional Dense Attention-guided Network (CDAN), a novel solution for enhancing low-light images. CDAN integrates an autoencoder-based architecture with convolutional and dense blocks, complemented by an attention mechanism and skip connections. This architecture ensures efficient information propagation and feature learning. Furthermore, a dedicated post-processing phase refines color balance and contrast. Our approach demonstrates notable progress compared to state-of-the-art results in low-light image enhancement, showcasing its robustness across a wide range of challenging scenarios. Our model performs remarkably on benchmark datasets, effectively mitigating under-exposure and proficiently restoring textures and colors in diverse low-light scenarios. This achievement underscores CDAN's potential for diverse computer vision tasks, notably enabling robust object detection and recognition in challenging low-light conditions.

{{</citation>}}


### (43/116) Boosting Semantic Segmentation from the Perspective of Explicit Class Embeddings (Yuhe Liu et al., 2023)

{{<citation>}}

Yuhe Liu, Chuanjian Liu, Kai Han, Quan Tang, Zengchang Qin. (2023)  
**Boosting Semantic Segmentation from the Perspective of Explicit Class Embeddings**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Embedding, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2308.12894v1)  

---


**ABSTRACT**  
Semantic segmentation is a computer vision task that associates a label with each pixel in an image. Modern approaches tend to introduce class embeddings into semantic segmentation for deeply utilizing category semantics, and regard supervised class masks as final predictions. In this paper, we explore the mechanism of class embeddings and have an insight that more explicit and meaningful class embeddings can be generated based on class masks purposely. Following this observation, we propose ECENet, a new segmentation paradigm, in which class embeddings are obtained and enhanced explicitly during interacting with multi-stage image features. Based on this, we revisit the traditional decoding process and explore inverted information flow between segmentation masks and class embeddings. Furthermore, to ensure the discriminability and informativity of features from backbone, we propose a Feature Reconstruction module, which combines intrinsic and diverse branches together to ensure the concurrence of diversity and redundancy in features. Experiments show that our ECENet outperforms its counterparts on the ADE20K dataset with much less computational cost and achieves new state-of-the-art results on PASCAL-Context dataset. The code will be released at https://gitee.com/mindspore/models and https://github.com/Carol-lyh/ECENet.

{{</citation>}}


### (44/116) Federated Learning for Computer Vision (Yassine Himeur et al., 2023)

{{<citation>}}

Yassine Himeur, Iraklis Varlamis, Hamza Kheddar, Abbes Amira, Shadi Atalla, Yashbir Singh, Faycal Bensaali, Wathiq Mansoor. (2023)  
**Federated Learning for Computer Vision**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Computer Vision  
[Paper Link](http://arxiv.org/abs/2308.13558v1)  

---


**ABSTRACT**  
Computer Vision (CV) is playing a significant role in transforming society by utilizing machine learning (ML) tools for a wide range of tasks. However, the need for large-scale datasets to train ML models creates challenges for centralized ML algorithms. The massive computation loads required for processing and the potential privacy risks associated with storing and processing data on central cloud servers put these algorithms under severe strain. To address these issues, federated learning (FL) has emerged as a promising solution, allowing privacy preservation by training models locally and exchanging them to improve overall performance. Additionally, the computational load is distributed across multiple clients, reducing the burden on central servers. This paper presents, to the best of the authors' knowledge, the first review discussing recent advancements of FL in CV applications, comparing them to conventional centralized training paradigms. It provides an overview of current FL applications in various CV tasks, emphasizing the advantages of FL and the challenges of implementing it in CV. To facilitate this, the paper proposes a taxonomy of FL techniques in CV, outlining their applications and security threats. It also discusses privacy concerns related to implementing blockchain in FL schemes for CV tasks and summarizes existing privacy preservation methods. Moving on, the paper identifies open research challenges and potential future research directions to further exploit the potential of FL and blockchain in CV applications.

{{</citation>}}


### (45/116) Implicit Obstacle Map-driven Indoor Navigation Model for Robust Obstacle Avoidance (Wei Xie et al., 2023)

{{<citation>}}

Wei Xie, Haobo Jiang, Shuo Gu, Jin Xie. (2023)  
**Implicit Obstacle Map-driven Indoor Navigation Model for Robust Obstacle Avoidance**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.12845v1)  

---


**ABSTRACT**  
Robust obstacle avoidance is one of the critical steps for successful goal-driven indoor navigation tasks.Due to the obstacle missing in the visual image and the possible missed detection issue, visual image-based obstacle avoidance techniques still suffer from unsatisfactory robustness. To mitigate it, in this paper, we propose a novel implicit obstacle map-driven indoor navigation framework for robust obstacle avoidance, where an implicit obstacle map is learned based on the historical trial-and-error experience rather than the visual image. In order to further improve the navigation efficiency, a non-local target memory aggregation module is designed to leverage a non-local network to model the intrinsic relationship between the target semantic and the target orientation clues during the navigation process so as to mine the most target-correlated object clues for the navigation decision. Extensive experimental results on AI2-Thor and RoboTHOR benchmarks verify the excellent obstacle avoidance and navigation efficiency of our proposed method. The core source code is available at https://github.com/xwaiyy123/object-navigation.

{{</citation>}}


### (46/116) FaceTouch: Detecting hand-to-face touch with supervised contrastive learning to assist in tracing infectious disease (Mohamed R. Ibrahim et al., 2023)

{{<citation>}}

Mohamed R. Ibrahim, Terry Lyons. (2023)  
**FaceTouch: Detecting hand-to-face touch with supervised contrastive learning to assist in tracing infectious disease**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2308.12840v1)  

---


**ABSTRACT**  
Through our respiratory system, many viruses and diseases frequently spread and pass from one person to another. Covid-19 served as an example of how crucial it is to track down and cut back on contacts to stop its spread. There is a clear gap in finding automatic methods that can detect hand-to-face contact in complex urban scenes or indoors. In this paper, we introduce a computer vision framework, called FaceTouch, based on deep learning. It comprises deep sub-models to detect humans and analyse their actions. FaceTouch seeks to detect hand-to-face touches in the wild, such as through video chats, bus footage, or CCTV feeds. Despite partial occlusion of faces, the introduced system learns to detect face touches from the RGB representation of a given scene by utilising the representation of the body gestures such as arm movement. This has been demonstrated to be useful in complex urban scenarios beyond simply identifying hand movement and its closeness to faces. Relying on Supervised Contrastive Learning, the introduced model is trained on our collected dataset, given the absence of other benchmark datasets. The framework shows a strong validation in unseen datasets which opens the door for potential deployment.

{{</citation>}}


### (47/116) EFormer: Enhanced Transformer towards Semantic-Contour Features of Foreground for Portraits Matting (Zitao Wang et al., 2023)

{{<citation>}}

Zitao Wang, Qiguang Miao, Yue Xi. (2023)  
**EFormer: Enhanced Transformer towards Semantic-Contour Features of Foreground for Portraits Matting**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI, Transformer  
[Paper Link](http://arxiv.org/abs/2308.12831v1)  

---


**ABSTRACT**  
The portrait matting task aims to extract an alpha matte with complete semantics and finely-detailed contours. In comparison to CNN-based approaches, transformers with self-attention allow a larger receptive field, enabling it to better capture long-range dependencies and low-frequency semantic information of a portrait. However, the recent research shows that self-attention mechanism struggle with modeling high-frequency information and capturing fine contour details, which can lead to bias while predicting the portrait's contours. To address the problem, we propose EFormer to enhance the model's attention towards semantic and contour features. Especially the latter, which is surrounded by a large amount of high-frequency details. We build a semantic and contour detector (SCD) to accurately capture the distribution of semantic and contour features. And we further design contour-edge extraction branch and semantic extraction branch for refining contour features and complete semantic information. Finally, we fuse the two kinds of features and leverage the segmentation head to generate the predicted portrait matte. Remarkably, EFormer is an end-to-end trimap-free method and boasts a simple structure. Experiments conducted on VideoMatte240K-JPEGSD and AIM datasets demonstrate that EFormer outperforms previous portrait matte methods.

{{</citation>}}


### (48/116) Robotic Scene Segmentation with Memory Network for Runtime Surgical Context Inference (Zongyu Li et al., 2023)

{{<citation>}}

Zongyu Li, Ian Reyes, Homa Alemzadeh. (2023)  
**Robotic Scene Segmentation with Memory Network for Runtime Surgical Context Inference**  

---
Primary Category: cs.CV  
Categories: 65D19, 68T07, 68T40, cs-CV, cs.CV  
Keywords: AWS  
[Paper Link](http://arxiv.org/abs/2308.12789v1)  

---


**ABSTRACT**  
Surgical context inference has recently garnered significant attention in robot-assisted surgery as it can facilitate workflow analysis, skill assessment, and error detection. However, runtime context inference is challenging since it requires timely and accurate detection of the interactions among the tools and objects in the surgical scene based on the segmentation of video data. On the other hand, existing state-of-the-art video segmentation methods are often biased against infrequent classes and fail to provide temporal consistency for segmented masks. This can negatively impact the context inference and accurate detection of critical states. In this study, we propose a solution to these challenges using a Space Time Correspondence Network (STCN). STCN is a memory network that performs binary segmentation and minimizes the effects of class imbalance. The use of a memory bank in STCN allows for the utilization of past image and segmentation information, thereby ensuring consistency of the masks. Our experiments using the publicly available JIGSAWS dataset demonstrate that STCN achieves superior segmentation performance for objects that are difficult to segment, such as needle and thread, and improves context inference compared to the state-of-the-art. We also demonstrate that segmentation and context inference can be performed at runtime without compromising performance.

{{</citation>}}


### (49/116) On Offline Evaluation of 3D Object Detection for Autonomous Driving (Tim Schreier et al., 2023)

{{<citation>}}

Tim Schreier, Katrin Renz, Andreas Geiger, Kashyap Chitta. (2023)  
**On Offline Evaluation of 3D Object Detection for Autonomous Driving**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2308.12779v1)  

---


**ABSTRACT**  
Prior work in 3D object detection evaluates models using offline metrics like average precision since closed-loop online evaluation on the downstream driving task is costly. However, it is unclear how indicative offline results are of driving performance. In this work, we perform the first empirical evaluation measuring how predictive different detection metrics are of driving performance when detectors are integrated into a full self-driving stack. We conduct extensive experiments on urban driving in the CARLA simulator using 16 object detection models. We find that the nuScenes Detection Score has a higher correlation to driving performance than the widely used average precision metric. In addition, our results call for caution on the exclusive reliance on the emerging class of `planner-centric' metrics.

{{</citation>}}


### (50/116) PartSeg: Few-shot Part Segmentation via Part-aware Prompt Learning (Mengya Han et al., 2023)

{{<citation>}}

Mengya Han, Heliang Zheng, Chaoyue Wang, Yong Luo, Han Hu, Jing Zhang, Yonggang Wen. (2023)  
**PartSeg: Few-shot Part Segmentation via Part-aware Prompt Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2308.12757v1)  

---


**ABSTRACT**  
In this work, we address the task of few-shot part segmentation, which aims to segment the different parts of an unseen object using very few labeled examples. It is found that leveraging the textual space of a powerful pre-trained image-language model (such as CLIP) can be beneficial in learning visual features. Therefore, we develop a novel method termed PartSeg for few-shot part segmentation based on multimodal learning. Specifically, we design a part-aware prompt learning method to generate part-specific prompts that enable the CLIP model to better understand the concept of ``part'' and fully utilize its textual space. Furthermore, since the concept of the same part under different object categories is general, we establish relationships between these parts during the prompt learning process. We conduct extensive experiments on the PartImageNet and Pascal$\_$Part datasets, and the experimental results demonstrated that our proposed method achieves state-of-the-art performance.

{{</citation>}}


### (51/116) Learning Heavily-Degraded Prior for Underwater Object Detection (Chenping Fu et al., 2023)

{{<citation>}}

Chenping Fu, Xin Fan, Jiewen Xiao, Wanqi Yuan, Risheng Liu, Zhongxuan Luo. (2023)  
**Learning Heavily-Degraded Prior for Underwater Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2308.12738v1)  

---


**ABSTRACT**  
Underwater object detection suffers from low detection performance because the distance and wavelength dependent imaging process yield evident image quality degradations such as haze-like effects, low visibility, and color distortions. Therefore, we commit to resolving the issue of underwater object detection with compounded environmental degradations. Typical approaches attempt to develop sophisticated deep architecture to generate high-quality images or features. However, these methods are only work for limited ranges because imaging factors are either unstable, too sensitive, or compounded. Unlike these approaches catering for high-quality images or features, this paper seeks transferable prior knowledge from detector-friendly images. The prior guides detectors removing degradations that interfere with detection. It is based on statistical observations that, the heavily degraded regions of detector-friendly (DFUI) and underwater images have evident feature distribution gaps while the lightly degraded regions of them overlap each other. Therefore, we propose a residual feature transference module (RFTM) to learn a mapping between deep representations of the heavily degraded patches of DFUI- and underwater- images, and make the mapping as a heavily degraded prior (HDP) for underwater detection. Since the statistical properties are independent to image content, HDP can be learned without the supervision of semantic labels and plugged into popular CNNbased feature extraction networks to improve their performance on underwater object detection. Without bells and whistles, evaluations on URPC2020 and UODD show that our methods outperform CNN-based detectors by a large margin. Our method with higher speeds and less parameters still performs better than transformer-based detectors. Our code and DFUI dataset can be found in https://github.com/xiaoDetection/Learning-Heavily-Degraed-Prior.

{{</citation>}}


### (52/116) Asymmetric Co-Training with Explainable Cell Graph Ensembling for Histopathological Image Classification (Ziqi Yang et al., 2023)

{{<citation>}}

Ziqi Yang, Zhongyu Li, Chen Liu, Xiangde Luo, Xingguang Wang, Dou Xu, Chaoqun Li, Xiaoying Qin, Meng Yang, Long Jin. (2023)  
**Asymmetric Co-Training with Explainable Cell Graph Ensembling for Histopathological Image Classification**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Image Classification  
[Paper Link](http://arxiv.org/abs/2308.12737v1)  

---


**ABSTRACT**  
Convolutional neural networks excel in histopathological image classification, yet their pixel-level focus hampers explainability. Conversely, emerging graph convolutional networks spotlight cell-level features and medical implications. However, limited by their shallowness and suboptimal use of high-dimensional pixel data, GCNs underperform in multi-class histopathological image classification. To make full use of pixel-level and cell-level features dynamically, we propose an asymmetric co-training framework combining a deep graph convolutional network and a convolutional neural network for multi-class histopathological image classification. To improve the explainability of the entire framework by embedding morphological and topological distribution of cells, we build a 14-layer deep graph convolutional network to handle cell graph data. For the further utilization and dynamic interactions between pixel-level and cell-level information, we also design a co-training strategy to integrate the two asymmetric branches. Notably, we collect a private clinically acquired dataset termed LUAD7C, including seven subtypes of lung adenocarcinoma, which is rare and more challenging. We evaluated our approach on the private LUAD7C and public colorectal cancer datasets, showcasing its superior performance, explainability, and generalizability in multi-class histopathological image classification.

{{</citation>}}


### (53/116) DeepLOC: Deep Learning-based Bone Pathology Localization and Classification in Wrist X-ray Images (Razan Dibo et al., 2023)

{{<citation>}}

Razan Dibo, Andrey Galichin, Pavel Astashev, Dmitry V. Dylov, Oleg Y. Rogov. (2023)  
**DeepLOC: Deep Learning-based Bone Pathology Localization and Classification in Wrist X-ray Images**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.12727v1)  

---


**ABSTRACT**  
In recent years, computer-aided diagnosis systems have shown great potential in assisting radiologists with accurate and efficient medical image analysis. This paper presents a novel approach for bone pathology localization and classification in wrist X-ray images using a combination of YOLO (You Only Look Once) and the Shifted Window Transformer (Swin) with a newly proposed block. The proposed methodology addresses two critical challenges in wrist X-ray analysis: accurate localization of bone pathologies and precise classification of abnormalities. The YOLO framework is employed to detect and localize bone pathologies, leveraging its real-time object detection capabilities. Additionally, the Swin, a transformer-based module, is utilized to extract contextual information from the localized regions of interest (ROIs) for accurate classification.

{{</citation>}}


### (54/116) VIGC: Visual Instruction Generation and Correction (Bin Wang et al., 2023)

{{<citation>}}

Bin Wang, Fan Wu, Xiao Han, Jiahui Peng, Huaping Zhong, Pan Zhang, Xiaoyi Dong, Weijia Li, Wei Li, Jiaqi Wang, Conghui He. (2023)  
**VIGC: Visual Instruction Generation and Correction**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2308.12714v1)  

---


**ABSTRACT**  
The integration of visual encoders and large language models (LLMs) has driven recent progress in multimodal large language models (MLLMs). However, the scarcity of high-quality instruction-tuning data for vision-language tasks remains a challenge. The current leading paradigm, such as LLaVA, relies on language-only GPT-4 to generate data, which requires pre-annotated image captions and detection bounding boxes, suffering from understanding image details. A practical solution to this problem would be to utilize the available multimodal large language models (MLLMs) to generate instruction data for vision-language tasks. However, it's worth noting that the currently accessible MLLMs are not as powerful as their LLM counterparts, as they tend to produce inadequate responses and generate false information. As a solution for addressing the current issue, this paper proposes the Visual Instruction Generation and Correction (VIGC) framework that enables multimodal large language models to generate instruction-tuning data and progressively enhance its quality on-the-fly. Specifically, Visual Instruction Generation (VIG) guides the vision-language model to generate diverse instruction-tuning data. To ensure generation quality, Visual Instruction Correction (VIC) adopts an iterative update mechanism to correct any inaccuracies in data produced by VIG, effectively reducing the risk of hallucination. Leveraging the diverse, high-quality data generated by VIGC, we finetune mainstream models and validate data quality based on various evaluations. Experimental results demonstrate that VIGC not only compensates for the shortcomings of language-only data generation methods, but also effectively enhances the benchmark performance. The models, datasets, and code will be made publicly available.

{{</citation>}}


### (55/116) A Parse-Then-Place Approach for Generating Graphic Layouts from Textual Descriptions (Jiawei Lin et al., 2023)

{{<citation>}}

Jiawei Lin, Jiaqi Guo, Shizhao Sun, Weijiang Xu, Ting Liu, Jian-Guang Lou, Dongmei Zhang. (2023)  
**A Parse-Then-Place Approach for Generating Graphic Layouts from Textual Descriptions**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.12700v1)  

---


**ABSTRACT**  
Creating layouts is a fundamental step in graphic design. In this work, we propose to use text as the guidance to create graphic layouts, i.e., Text-to-Layout, aiming to lower the design barriers. Text-to-Layout is a challenging task, because it needs to consider the implicit, combined, and incomplete layout constraints from text, each of which has not been studied in previous work. To address this, we present a two-stage approach, named parse-then-place. The approach introduces an intermediate representation (IR) between text and layout to represent diverse layout constraints. With IR, Text-to-Layout is decomposed into a parse stage and a place stage. The parse stage takes a textual description as input and generates an IR, in which the implicit constraints from the text are transformed into explicit ones. The place stage generates layouts based on the IR. To model combined and incomplete constraints, we use a Transformer-based layout generation model and carefully design a way to represent constraints and layouts as sequences. Besides, we adopt the pretrain-then-finetune strategy to boost the performance of the layout generation model with large-scale unlabeled layouts. To evaluate our approach, we construct two Text-to-Layout datasets and conduct experiments on them. Quantitative results, qualitative analysis, and user studies demonstrate the effectiveness of our approach.

{{</citation>}}


### (56/116) A Study of Age and Sex Bias in Multiple Instance Learning based Classification of Acute Myeloid Leukemia Subtypes (Ario Sadafi et al., 2023)

{{<citation>}}

Ario Sadafi, Matthias Hehr, Nassir Navab, Carsten Marr. (2023)  
**A Study of Age and Sex Bias in Multiple Instance Learning based Classification of Acute Myeloid Leukemia Subtypes**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV, eess-IV  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2308.12675v1)  

---


**ABSTRACT**  
Accurate classification of Acute Myeloid Leukemia (AML) subtypes is crucial for clinical decision-making and patient care. In this study, we investigate the potential presence of age and sex bias in AML subtype classification using Multiple Instance Learning (MIL) architectures. To that end, we train multiple MIL models using different levels of sex imbalance in the training set and excluding certain age groups. To assess the sex bias, we evaluate the performance of the models on male and female test sets. For age bias, models are tested against underrepresented age groups in the training data. We find a significant effect of sex and age bias on the performance of the model for AML subtype classification. Specifically, we observe that females are more likely to be affected by sex imbalance dataset and certain age groups, such as patients with 72 to 86 years of age with the RUNX1::RUNX1T1 genetic subtype, are significantly affected by an age bias present in the training data. Ensuring inclusivity in the training data is thus essential for generating reliable and equitable outcomes in AML genetic subtype classification, ultimately benefiting diverse patient populations.

{{</citation>}}


### (57/116) Masked Feature Modelling: Feature Masking for the Unsupervised Pre-training of a Graph Attention Network Block for Bottom-up Video Event Recognition (Dimitrios Daskalakis et al., 2023)

{{<citation>}}

Dimitrios Daskalakis, Nikolaos Gkalelis, Vasileios Mezaris. (2023)  
**Masked Feature Modelling: Feature Masking for the Unsupervised Pre-training of a Graph Attention Network Block for Bottom-up Video Event Recognition**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs-MM, cs.CV  
Keywords: Attention, Event Recognition, Graph Attention Network  
[Paper Link](http://arxiv.org/abs/2308.12673v2)  

---


**ABSTRACT**  
In this paper, we introduce Masked Feature Modelling (MFM), a novel approach for the unsupervised pre-training of a Graph Attention Network (GAT) block. MFM utilizes a pretrained Visual Tokenizer to reconstruct masked features of objects within a video, leveraging the MiniKinetics dataset. We then incorporate the pre-trained GAT block into a state-of-the-art bottom-up supervised video-event recognition architecture, ViGAT, to improve the model's starting point and overall accuracy. Experimental evaluations on the YLI-MED dataset demonstrate the effectiveness of MFM in improving event recognition performance.

{{</citation>}}


### (58/116) Don't Look into the Sun: Adversarial Solarization Attacks on Image Classifiers (Paul Gavrikov et al., 2023)

{{<citation>}}

Paul Gavrikov, Janis Keuper. (2023)  
**Don't Look into the Sun: Adversarial Solarization Attacks on Image Classifiers**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2308.12661v1)  

---


**ABSTRACT**  
Assessing the robustness of deep neural networks against out-of-distribution inputs is crucial, especially in safety-critical domains like autonomous driving, but also in safety systems where malicious actors can digitally alter inputs to circumvent safety guards. However, designing effective out-of-distribution tests that encompass all possible scenarios while preserving accurate label information is a challenging task. Existing methodologies often entail a compromise between variety and constraint levels for attacks and sometimes even both. In a first step towards a more holistic robustness evaluation of image classification models, we introduce an attack method based on image solarization that is conceptually straightforward yet avoids jeopardizing the global structure of natural images independent of the intensity. Through comprehensive evaluations of multiple ImageNet models, we demonstrate the attack's capacity to degrade accuracy significantly, provided it is not integrated into the training augmentations. Interestingly, even then, no full immunity to accuracy deterioration is achieved. In other settings, the attack can often be simplified into a black-box attack with model-independent parameters. Defenses against other corruptions do not consistently extend to be effective against our specific attack.   Project website: https://github.com/paulgavrikov/adversarial_solarization

{{</citation>}}


### (59/116) An All Deep System for Badminton Game Analysis (Po-Yung Chou et al., 2023)

{{<citation>}}

Po-Yung Chou, Yu-Chun Lo, Bo-Zheng Xie, Cheng-Hung Lin, Yu-Yung Kao. (2023)  
**An All Deep System for Badminton Game Analysis**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.12645v1)  

---


**ABSTRACT**  
The CoachAI Badminton 2023 Track1 initiative aim to automatically detect events within badminton match videos. Detecting small objects, especially the shuttlecock, is of quite importance and demands high precision within the challenge. Such detection is crucial for tasks like hit count, hitting time, and hitting location. However, even after revising the well-regarded shuttlecock detecting model, TrackNet, our object detection models still fall short of the desired accuracy. To address this issue, we've implemented various deep learning methods to tackle the problems arising from noisy detectied data, leveraging diverse data types to improve precision. In this report, we detail the detection model modifications we've made and our approach to the 11 tasks. Notably, our system garnered a score of 0.78 out of 1.0 in the challenge.

{{</citation>}}


### (60/116) Towards Hierarchical Regional Transformer-based Multiple Instance Learning (Josef Cersovsky et al., 2023)

{{<citation>}}

Josef Cersovsky, Sadegh Mohammadi, Dagmar Kainmueller, Johannes Hoehne. (2023)  
**Towards Hierarchical Regional Transformer-based Multiple Instance Learning**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.12634v1)  

---


**ABSTRACT**  
The classification of gigapixel histopathology images with deep multiple instance learning models has become a critical task in digital pathology and precision medicine. In this work, we propose a Transformer-based multiple instance learning approach that replaces the traditional learned attention mechanism with a regional, Vision Transformer inspired self-attention mechanism. We present a method that fuses regional patch information to derive slide-level predictions and show how this regional aggregation can be stacked to hierarchically process features on different distance levels. To increase predictive accuracy, especially for datasets with small, local morphological features, we introduce a method to focus the image processing on high attention regions during inference. Our approach is able to significantly improve performance over the baseline on two histopathology datasets and points towards promising directions for further research.

{{</citation>}}


### (61/116) Cross-Video Contextual Knowledge Exploration and Exploitation for Ambiguity Reduction in Weakly Supervised Temporal Action Localization (Songchun Zhang et al., 2023)

{{<citation>}}

Songchun Zhang, Chunhui Zhao. (2023)  
**Cross-Video Contextual Knowledge Exploration and Exploitation for Ambiguity Reduction in Weakly Supervised Temporal Action Localization**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Contrastive Learning, Summarization  
[Paper Link](http://arxiv.org/abs/2308.12609v1)  

---


**ABSTRACT**  
Weakly supervised temporal action localization (WSTAL) aims to localize actions in untrimmed videos using video-level labels. Despite recent advances, existing approaches mainly follow a localization-by-classification pipeline, generally processing each segment individually, thereby exploiting only limited contextual information. As a result, the model will lack a comprehensive understanding (e.g. appearance and temporal structure) of various action patterns, leading to ambiguity in classification learning and temporal localization. Our work addresses this from a novel perspective, by exploring and exploiting the cross-video contextual knowledge within the dataset to recover the dataset-level semantic structure of action instances via weak labels only, thereby indirectly improving the holistic understanding of fine-grained action patterns and alleviating the aforementioned ambiguities. Specifically, an end-to-end framework is proposed, including a Robust Memory-Guided Contrastive Learning (RMGCL) module and a Global Knowledge Summarization and Aggregation (GKSA) module. First, the RMGCL module explores the contrast and consistency of cross-video action features, assisting in learning more structured and compact embedding space, thus reducing ambiguity in classification learning. Further, the GKSA module is used to efficiently summarize and propagate the cross-video representative action knowledge in a learnable manner to promote holistic action patterns understanding, which in turn allows the generation of high-confidence pseudo-labels for self-learning, thus alleviating ambiguity in temporal localization. Extensive experiments on THUMOS14, ActivityNet1.3, and FineAction demonstrate that our method outperforms the state-of-the-art methods, and can be easily plugged into other WSTAL methods.

{{</citation>}}


### (62/116) HR-Pro: Point-supervised Temporal Action Localization via Hierarchical Reliability Propagation (Huaxin Zhang et al., 2023)

{{<citation>}}

Huaxin Zhang, Xiang Wang, Xiaohao Xu, Zhiwu Qing, Changxin Gao, Nong Sang. (2023)  
**HR-Pro: Point-supervised Temporal Action Localization via Hierarchical Reliability Propagation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2308.12608v1)  

---


**ABSTRACT**  
Point-supervised Temporal Action Localization (PSTAL) is an emerging research direction for label-efficient learning. However, current methods mainly focus on optimizing the network either at the snippet-level or the instance-level, neglecting the inherent reliability of point annotations at both levels. In this paper, we propose a Hierarchical Reliability Propagation (HR-Pro) framework, which consists of two reliability-aware stages: Snippet-level Discrimination Learning and Instance-level Completeness Learning, both stages explore the efficient propagation of high-confidence cues in point annotations. For snippet-level learning, we introduce an online-updated memory to store reliable snippet prototypes for each class. We then employ a Reliability-aware Attention Block to capture both intra-video and inter-video dependencies of snippets, resulting in more discriminative and robust snippet representation. For instance-level learning, we propose a point-based proposal generation approach as a means of connecting snippets and instances, which produces high-confidence proposals for further optimization at the instance level. Through multi-level reliability-aware learning, we obtain more reliable confidence scores and more accurate temporal boundaries of predicted proposals. Our HR-Pro achieves state-of-the-art performance on multiple challenging benchmarks, including an impressive average mAP of 60.3% on THUMOS14. Notably, our HR-Pro largely surpasses all previous point-supervised methods, and even outperforms several competitive fully supervised methods. Code will be available at https://github.com/pipixin321/HR-Pro.

{{</citation>}}


### (63/116) APLA: Additional Perturbation for Latent Noise with Adversarial Training Enables Consistency (Yupu Yao et al., 2023)

{{<citation>}}

Yupu Yao, Shangqi Deng, Zihan Cao, Harry Zhang, Liang-Jian Deng. (2023)  
**APLA: Additional Perturbation for Latent Noise with Adversarial Training Enables Consistency**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Adversarial Training, Transformer  
[Paper Link](http://arxiv.org/abs/2308.12605v1)  

---


**ABSTRACT**  
Diffusion models have exhibited promising progress in video generation. However, they often struggle to retain consistent details within local regions across frames. One underlying cause is that traditional diffusion models approximate Gaussian noise distribution by utilizing predictive noise, without fully accounting for the impact of inherent information within the input itself. Additionally, these models emphasize the distinction between predictions and references, neglecting information intrinsic to the videos. To address this limitation, inspired by the self-attention mechanism, we propose a novel text-to-video (T2V) generation network structure based on diffusion models, dubbed Additional Perturbation for Latent noise with Adversarial training (APLA). Our approach only necessitates a single video as input and builds upon pre-trained stable diffusion networks. Notably, we introduce an additional compact network, known as the Video Generation Transformer (VGT). This auxiliary component is designed to extract perturbations from the inherent information contained within the input, thereby refining inconsistent pixels during temporal predictions. We leverage a hybrid architecture of transformers and convolutions to compensate for temporal intricacies, enhancing consistency between different frames within the video. Experiments demonstrate a noticeable improvement in the consistency of the generated videos both qualitatively and quantitatively.

{{</citation>}}


### (64/116) Logic-induced Diagnostic Reasoning for Semi-supervised Semantic Segmentation (Chen Liang et al., 2023)

{{<citation>}}

Chen Liang, Wenguan Wang, Jiaxu Miao, Yi Yang. (2023)  
**Logic-induced Diagnostic Reasoning for Semi-supervised Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Reasoning, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2308.12595v1)  

---


**ABSTRACT**  
Recent advances in semi-supervised semantic segmentation have been heavily reliant on pseudo labeling to compensate for limited labeled data, disregarding the valuable relational knowledge among semantic concepts. To bridge this gap, we devise LogicDiag, a brand new neural-logic semi-supervised learning framework. Our key insight is that conflicts within pseudo labels, identified through symbolic knowledge, can serve as strong yet commonly ignored learning signals. LogicDiag resolves such conflicts via reasoning with logic-induced diagnoses, enabling the recovery of (potentially) erroneous pseudo labels, ultimately alleviating the notorious error accumulation problem. We showcase the practical application of LogicDiag in the data-hungry segmentation scenario, where we formalize the structured abstraction of semantic concepts as a set of logic rules. Extensive experiments on three standard semi-supervised semantic segmentation benchmarks demonstrate the effectiveness and generality of LogicDiag. Moreover, LogicDiag highlights the promising opportunities arising from the systematic integration of symbolic reasoning into the prevalent statistical, neural learning approaches.

{{</citation>}}


### (65/116) REB: Reducing Biases in Representation for Industrial Anomaly Detection (Shuai Lyu et al., 2023)

{{<citation>}}

Shuai Lyu, Dongmei Mo, Waikeung Wong. (2023)  
**REB: Reducing Biases in Representation for Industrial Anomaly Detection**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Anomaly Detection, Bias  
[Paper Link](http://arxiv.org/abs/2308.12577v1)  

---


**ABSTRACT**  
Existing K-nearest neighbor (KNN) retrieval-based methods usually conduct industrial anomaly detection in two stages: obtain feature representations with a pre-trained CNN model and perform distance measures for defect detection. However, the features are not fully exploited as they ignore domain bias and the difference of local density in feature space, which limits the detection performance. In this paper, we propose Reducing Biases (REB) in representation by considering the domain bias of the pre-trained model and building a self-supervised learning task for better domain adaption with a defect generation strategy (DefectMaker) imitating the natural defects. Additionally, we propose a local density KNN (LDKNN) to reduce the local density bias and obtain effective anomaly detection. We achieve a promising result of 99.5\% AUROC on the widely used MVTec AD benchmark. We also achieve 88.0\% AUROC on the challenging MVTec LOCO AD dataset and bring an improvement of 4.7\% AUROC to the state-of-the-art result. All results are obtained with smaller backbone networks such as Vgg11 and Resnet18, which indicates the effectiveness and efficiency of REB for practical industrial applications.

{{</citation>}}


### (66/116) NOVA: NOvel View Augmentation for Neural Composition of Dynamic Objects (Dakshit Agrawal et al., 2023)

{{<citation>}}

Dakshit Agrawal, Jiajie Xu, Siva Karthik Mustikovela, Ioannis Gkioulekas, Ashish Shrivastava, Yuning Chai. (2023)  
**NOVA: NOvel View Augmentation for Neural Composition of Dynamic Objects**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2308.12560v1)  

---


**ABSTRACT**  
We propose a novel-view augmentation (NOVA) strategy to train NeRFs for photo-realistic 3D composition of dynamic objects in a static scene. Compared to prior work, our framework significantly reduces blending artifacts when inserting multiple dynamic objects into a 3D scene at novel views and times; achieves comparable PSNR without the need for additional ground truth modalities like optical flow; and overall provides ease, flexibility, and scalability in neural composition. Our codebase is on GitHub.

{{</citation>}}


### (67/116) Synchronize Feature Extracting and Matching: A Single Branch Framework for 3D Object Tracking (Teli Ma et al., 2023)

{{<citation>}}

Teli Ma, Mengmeng Wang, Jimin Xiao, Huifeng Wu, Yong Liu. (2023)  
**Synchronize Feature Extracting and Matching: A Single Branch Framework for 3D Object Tracking**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.12549v1)  

---


**ABSTRACT**  
Siamese network has been a de facto benchmark framework for 3D LiDAR object tracking with a shared-parametric encoder extracting features from template and search region, respectively. This paradigm relies heavily on an additional matching network to model the cross-correlation/similarity of the template and search region. In this paper, we forsake the conventional Siamese paradigm and propose a novel single-branch framework, SyncTrack, synchronizing the feature extracting and matching to avoid forwarding encoder twice for template and search region as well as introducing extra parameters of matching network. The synchronization mechanism is based on the dynamic affinity of the Transformer, and an in-depth analysis of the relevance is provided theoretically. Moreover, based on the synchronization, we introduce a novel Attentive Points-Sampling strategy into the Transformer layers (APST), replacing the random/Farthest Points Sampling (FPS) method with sampling under the supervision of attentive relations between the template and search region. It implies connecting point-wise sampling with the feature learning, beneficial to aggregating more distinctive and geometric features for tracking with sparse points. Extensive experiments on two benchmark datasets (KITTI and NuScenes) show that SyncTrack achieves state-of-the-art performance in real-time tracking.

{{</citation>}}


### (68/116) Hybrid Models for Facial Emotion Recognition in Children (Rafael Zimmer et al., 2023)

{{<citation>}}

Rafael Zimmer, Marcos Sobral, Helio Azevedo. (2023)  
**Hybrid Models for Facial Emotion Recognition in Children**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Emotion Recognition  
[Paper Link](http://arxiv.org/abs/2308.12547v1)  

---


**ABSTRACT**  
This paper focuses on the use of emotion recognition techniques to assist psychologists in performing children's therapy through remotely robot operated sessions. In the field of psychology, the use of agent-mediated therapy is growing increasingly given recent advances in robotics and computer science. Specifically, the use of Embodied Conversational Agents (ECA) as an intermediary tool can help professionals connect with children who face social challenges such as Attention Deficit Hyperactivity Disorder (ADHD), Autism Spectrum Disorder (ASD) or even who are physically unavailable due to being in regions of armed conflict, natural disasters, or other circumstances. In this context, emotion recognition represents an important feedback for the psychotherapist. In this article, we initially present the result of a bibliographical research associated with emotion recognition in children. This research revealed an initial overview on algorithms and datasets widely used by the community. Then, based on the analysis carried out on the results of the bibliographical research, we used the technique of dense optical flow features to improve the ability of identifying emotions in children in uncontrolled environments. From the output of a hybrid model of Convolutional Neural Network, two intermediary features are fused before being processed by a final classifier. The proposed architecture was called HybridCNNFusion. Finally, we present the initial results achieved in the recognition of children's emotions using a dataset of Brazilian children.

{{</citation>}}


### (69/116) Channel and Spatial Relation-Propagation Network for RGB-Thermal Semantic Segmentation (Zikun Zhou et al., 2023)

{{<citation>}}

Zikun Zhou, Shukun Wu, Guoqing Zhu, Hongpeng Wang, Zhenyu He. (2023)  
**Channel and Spatial Relation-Propagation Network for RGB-Thermal Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2308.12534v1)  

---


**ABSTRACT**  
RGB-Thermal (RGB-T) semantic segmentation has shown great potential in handling low-light conditions where RGB-based segmentation is hindered by poor RGB imaging quality. The key to RGB-T semantic segmentation is to effectively leverage the complementarity nature of RGB and thermal images. Most existing algorithms fuse RGB and thermal information in feature space via concatenation, element-wise summation, or attention operations in either unidirectional enhancement or bidirectional aggregation manners. However, they usually overlook the modality gap between RGB and thermal images during feature fusion, resulting in modality-specific information from one modality contaminating the other. In this paper, we propose a Channel and Spatial Relation-Propagation Network (CSRPNet) for RGB-T semantic segmentation, which propagates only modality-shared information across different modalities and alleviates the modality-specific information contamination issue. Our CSRPNet first performs relation-propagation in channel and spatial dimensions to capture the modality-shared features from the RGB and thermal features. CSRPNet then aggregates the modality-shared features captured from one modality with the input feature from the other modality to enhance the input feature without the contamination issue. While being fused together, the enhanced RGB and thermal features will be also fed into the subsequent RGB or thermal feature extraction layers for interactive feature fusion, respectively. We also introduce a dual-path cascaded feature refinement module that aggregates multi-layer features to produce two refined features for semantic and boundary prediction. Extensive experimental results demonstrate that CSRPNet performs favorably against state-of-the-art algorithms.

{{</citation>}}


### (70/116) I3DOD: Towards Incremental 3D Object Detection via Prompting (Wenqi Liang et al., 2023)

{{<citation>}}

Wenqi Liang, Gan Sun, Chenxi Liu, Jiahua Dong, Kangru Wang. (2023)  
**I3DOD: Towards Incremental 3D Object Detection via Prompting**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2308.12512v1)  

---


**ABSTRACT**  
3D object detection has achieved significant performance in many fields, e.g., robotics system, autonomous driving, and augmented reality. However, most existing methods could cause catastrophic forgetting of old classes when performing on the class-incremental scenarios. Meanwhile, the current class-incremental 3D object detection methods neglect the relationships between the object localization information and category semantic information and assume all the knowledge of old model is reliable. To address the above challenge, we present a novel Incremental 3D Object Detection framework with the guidance of prompting, i.e., I3DOD. Specifically, we propose a task-shared prompts mechanism to learn the matching relationships between the object localization information and category semantic information. After training on the current task, these prompts will be stored in our prompt pool, and perform the relationship of old classes in the next task. Moreover, we design a reliable distillation strategy to transfer knowledge from two aspects: a reliable dynamic distillation is developed to filter out the negative knowledge and transfer the reliable 3D knowledge to new detection model; the relation feature is proposed to capture the responses relation in feature space and protect plasticity of the model when learning novel 3D classes. To the end, we conduct comprehensive experiments on two benchmark datasets and our method outperforms the state-of-the-art object detection methods by 0.6% - 2.7% in terms of mAP@0.25.

{{</citation>}}


### (71/116) Masked Autoencoders are Efficient Class Incremental Learners (Jiang-Tian Zhai et al., 2023)

{{<citation>}}

Jiang-Tian Zhai, Xialei Liu, Andrew D. Bagdanov, Ke Li, Ming-Ming Cheng. (2023)  
**Masked Autoencoders are Efficient Class Incremental Learners**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2308.12510v1)  

---


**ABSTRACT**  
Class Incremental Learning (CIL) aims to sequentially learn new classes while avoiding catastrophic forgetting of previous knowledge. We propose to use Masked Autoencoders (MAEs) as efficient learners for CIL. MAEs were originally designed to learn useful representations through reconstructive unsupervised learning, and they can be easily integrated with a supervised loss for classification. Moreover, MAEs can reliably reconstruct original input images from randomly selected patches, which we use to store exemplars from past tasks more efficiently for CIL. We also propose a bilateral MAE framework to learn from image-level and embedding-level fusion, which produces better-quality reconstructed images and more stable representations. Our experiments confirm that our approach performs better than the state-of-the-art on CIFAR-100, ImageNet-Subset, and ImageNet-Full. The code is available at https://github.com/scok30/MAE-CIL .

{{</citation>}}


### (72/116) DD-GCN: Directed Diffusion Graph Convolutional Network for Skeleton-based Human Action Recognition (Chang Li et al., 2023)

{{<citation>}}

Chang Li, Qian Huang, Yingchi Mao. (2023)  
**DD-GCN: Directed Diffusion Graph Convolutional Network for Skeleton-based Human Action Recognition**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Graph Convolutional Network  
[Paper Link](http://arxiv.org/abs/2308.12501v1)  

---


**ABSTRACT**  
Graph Convolutional Networks (GCNs) have been widely used in skeleton-based human action recognition. In GCN-based methods, the spatio-temporal graph is fundamental for capturing motion patterns. However, existing approaches ignore the physical dependency and synchronized spatio-temporal correlations between joints, which limits the representation capability of GCNs. To solve these problems, we construct the directed diffusion graph for action modeling and introduce the activity partition strategy to optimize the weight sharing mechanism of graph convolution kernels. In addition, we present the spatio-temporal synchronization encoder to embed synchronized spatio-temporal semantics. Finally, we propose Directed Diffusion Graph Convolutional Network (DD-GCN) for action recognition, and the experiments on three public datasets: NTU-RGB+D, NTU-RGB+D 120, and NW-UCLA, demonstrate the state-of-the-art performance of our method.

{{</citation>}}


## cs.RO (4)



### (73/116) Racing Towards Reinforcement Learning based control of an Autonomous Formula SAE Car (Aakaash Salvaji et al., 2023)

{{<citation>}}

Aakaash Salvaji, Harry Taylor, David Valencia, Trevor Gee, Henry Williams. (2023)  
**Racing Towards Reinforcement Learning based control of an Autonomous Formula SAE Car**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-LG, cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.13088v1)  

---


**ABSTRACT**  
With the rising popularity of autonomous navigation research, Formula Student (FS) events are introducing a Driverless Vehicle (DV) category to their event list. This paper presents the initial investigation into utilising Deep Reinforcement Learning (RL) for end-to-end control of an autonomous FS race car for these competitions. We train two state-of-the-art RL algorithms in simulation on tracks analogous to the full-scale design on a Turtlebot2 platform. The results demonstrate that our approach can successfully learn to race in simulation and then transfer to a real-world racetrack on the physical platform. Finally, we provide insights into the limitations of the presented approach and guidance into the future directions for applying RL toward full-scale autonomous FS racing.

{{</citation>}}


### (74/116) Actuator Trajectory Planning for UAVs with Overhead Manipulator using Reinforcement Learning (Hazim Alzorgan et al., 2023)

{{<citation>}}

Hazim Alzorgan, Abolfazl Razi, Ata Jahangir Moshayedi. (2023)  
**Actuator Trajectory Planning for UAVs with Overhead Manipulator using Reinforcement Learning**  

---
Primary Category: cs.RO  
Categories: cs-LG, cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.12843v2)  

---


**ABSTRACT**  
In this paper, we investigate the operation of an aerial manipulator system, namely an Unmanned Aerial Vehicle (UAV) equipped with a controllable arm with two degrees of freedom to carry out actuation tasks on the fly. Our solution is based on employing a Q-learning method to control the trajectory of the tip of the arm, also called end-effector. More specifically, we develop a motion planning model based on Time To Collision (TTC), which enables a quadrotor UAV to navigate around obstacles while ensuring the manipulator's reachability. Additionally, we utilize a model-based Q-learning model to independently track and control the desired trajectory of the manipulator's end-effector, given an arbitrary baseline trajectory for the UAV platform. Such a combination enables a variety of actuation tasks such as high-altitude welding, structural monitoring and repair, battery replacement, gutter cleaning, skyscrapper cleaning, and power line maintenance in hard-to-reach and risky environments while retaining compatibility with flight control firmware. Our RL-based control mechanism results in a robust control strategy that can handle uncertainties in the motion of the UAV, offering promising performance. Specifically, our method achieves 92% accuracy in terms of average displacement error (i.e. the mean distance between the target and obtained trajectory points) using Q-learning with 15,000 episodes

{{</citation>}}


### (75/116) Reinforcement Learning Informed Evolutionary Search for Autonomous Systems Testing (Dmytro Humeniuk et al., 2023)

{{<citation>}}

Dmytro Humeniuk, Foutse Khomh, Giuliano Antoniol. (2023)  
**Reinforcement Learning Informed Evolutionary Search for Autonomous Systems Testing**  

---
Primary Category: cs.RO  
Categories: cs-NE, cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.12762v1)  

---


**ABSTRACT**  
Evolutionary search-based techniques are commonly used for testing autonomous robotic systems. However, these approaches often rely on computationally expensive simulator-based models for test scenario evaluation. To improve the computational efficiency of the search-based testing, we propose augmenting the evolutionary search (ES) with a reinforcement learning (RL) agent trained using surrogate rewards derived from domain knowledge. In our approach, known as RIGAA (Reinforcement learning Informed Genetic Algorithm for Autonomous systems testing), we first train an RL agent to learn useful constraints of the problem and then use it to produce a certain part of the initial population of the search algorithm. By incorporating an RL agent into the search process, we aim to guide the algorithm towards promising regions of the search space from the start, enabling more efficient exploration of the solution space. We evaluate RIGAA on two case studies: maze generation for an autonomous ant robot and road topology generation for an autonomous vehicle lane keeping assist system. In both case studies, RIGAA converges faster to fitter solutions and produces a better test suite (in terms of average test scenario fitness and diversity). RIGAA also outperforms the state-of-the-art tools for vehicle lane keeping assist system testing, such as AmbieGen and Frenetic.

{{</citation>}}


### (76/116) HuBo-VLM: Unified Vision-Language Model designed for HUman roBOt interaction tasks (Zichao Dong et al., 2023)

{{<citation>}}

Zichao Dong, Weikun Zhang, Xufeng Huang, Hang Ji, Xin Zhan, Junbo Chen. (2023)  
**HuBo-VLM: Unified Vision-Language Model designed for HUman roBOt interaction tasks**  

---
Primary Category: cs.RO  
Categories: cs-CV, cs-RO, cs.RO  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2308.12537v1)  

---


**ABSTRACT**  
Human robot interaction is an exciting task, which aimed to guide robots following instructions from human. Since huge gap lies between human natural language and machine codes, end to end human robot interaction models is fair challenging. Further, visual information receiving from sensors of robot is also a hard language for robot to perceive. In this work, HuBo-VLM is proposed to tackle perception tasks associated with human robot interaction including object detection and visual grounding by a unified transformer based vision language model. Extensive experiments on the Talk2Car benchmark demonstrate the effectiveness of our approach. Code would be publicly available in https://github.com/dzcgaara/HuBo-VLM.

{{</citation>}}


## cs.SI (3)



### (77/116) Exploring Gender-Based Toxic Speech on Twitter in Context of the #MeToo movement: A Mixed Methods Approach (Sayak Saha Roy et al., 2023)

{{<citation>}}

Sayak Saha Roy, Ohad Gilbar, Christina Palantza, Maxine Davis, Shirin Nilizadeh. (2023)  
**Exploring Gender-Based Toxic Speech on Twitter in Context of the #MeToo movement: A Mixed Methods Approach**  

---
Primary Category: cs.SI  
Categories: cs-CY, cs-SI, cs.SI  
Keywords: Twitter  
[Paper Link](http://arxiv.org/abs/2308.13076v1)  

---


**ABSTRACT**  
The #MeToo movement has catalyzed widespread public discourse surrounding sexual harassment and assault, empowering survivors to share their stories and holding perpetrators accountable. While the movement has had a substantial and largely positive influence, this study aims to examine the potential negative consequences in the form of increased hostility against women and men on the social media platform Twitter. By analyzing tweets shared between October 2017 and January 2020 by more than 47.1k individuals who had either disclosed their own sexual abuse experiences on Twitter or engaged in discussions about the movement, we identify the overall increase in gender-based hostility towards both women and men since the start of the movement. We also monitor 16 pivotal real-life events that shaped the #MeToo movement to identify how these events may have amplified negative discussions targeting the opposite gender on Twitter. Furthermore, we conduct a thematic content analysis of a subset of gender-based hostile tweets, which helps us identify recurring themes and underlying motivations driving the expressions of anger and resentment from both men and women concerning the #MeToo movement. This study highlights the need for a nuanced understanding of the impact of social movements on online discourse and underscores the importance of addressing gender-based hostility in the digital sphere.

{{</citation>}}


### (78/116) Video Recommendation Using Social Network Analysis and User Viewing Patterns (Mehrdad Maghsoudi et al., 2023)

{{<citation>}}

Mehrdad Maghsoudi, MohammdHossein Valikhan, MohammdHossein Zohdi. (2023)  
**Video Recommendation Using Social Network Analysis and User Viewing Patterns**  

---
Primary Category: cs.SI  
Categories: cs-IR, cs-SI, cs.SI  
Keywords: Social Network  
[Paper Link](http://arxiv.org/abs/2308.12743v1)  

---


**ABSTRACT**  
With the meteoric rise of video-on-demand (VOD) platforms, users face the challenge of sifting through an expansive sea of content to uncover shows that closely match their preferences. To address this information overload dilemma, VOD services have increasingly incorporated recommender systems powered by algorithms that analyze user behavior and suggest personalized content. However, a majority of existing recommender systems depend on explicit user feedback in the form of ratings and reviews, which can be difficult and time-consuming to collect at scale. This presents a key research gap, as leveraging users' implicit feedback patterns could provide an alternative avenue for building effective video recommendation models, circumventing the need for explicit ratings. However, prior literature lacks sufficient exploration into implicit feedback-based recommender systems, especially in the context of modeling video viewing behavior. Therefore, this paper aims to bridge this research gap by proposing a novel video recommendation technique that relies solely on users' implicit feedback in the form of their content viewing percentages.

{{</citation>}}


### (79/116) False Information, Bots and Malicious Campaigns: Demystifying Elements of Social Media Manipulations (Mohammad Majid Akhtar et al., 2023)

{{<citation>}}

Mohammad Majid Akhtar, Rahat Masood, Muhammad Ikram, Salil S. Kanhere. (2023)  
**False Information, Bots and Malicious Campaigns: Demystifying Elements of Social Media Manipulations**  

---
Primary Category: cs.SI  
Categories: cs-CY, cs-LG, cs-SI, cs.SI  
Keywords: Social Media  
[Paper Link](http://arxiv.org/abs/2308.12497v1)  

---


**ABSTRACT**  
The rapid spread of false information and persistent manipulation attacks on online social networks (OSNs), often for political, ideological, or financial gain, has affected the openness of OSNs. While researchers from various disciplines have investigated different manipulation-triggering elements of OSNs (such as understanding information diffusion on OSNs or detecting automated behavior of accounts), these works have not been consolidated to present a comprehensive overview of the interconnections among these elements. Notably, user psychology, the prevalence of bots, and their tactics in relation to false information detection have been overlooked in previous research. To address this research gap, this paper synthesizes insights from various disciplines to provide a comprehensive analysis of the manipulation landscape. By integrating the primary elements of social media manipulation (SMM), including false information, bots, and malicious campaigns, we extensively examine each SMM element. Through a systematic investigation of prior research, we identify commonalities, highlight existing gaps, and extract valuable insights in the field. Our findings underscore the urgent need for interdisciplinary research to effectively combat social media manipulations, and our systematization can guide future research efforts and assist OSN providers in ensuring the safety and integrity of their platforms.

{{</citation>}}


## cs.HC (5)



### (80/116) Project Aria: A New Tool for Egocentric Multi-Modal AI Research (Kiran Somasundaram et al., 2023)

{{<citation>}}

Kiran Somasundaram, Jing Dong, Huixuan Tang, Julian Straub, Mingfei Yan, Michael Goesele, Jakob Julian Engel, Renzo De Nardi, Richard Newcombe. (2023)  
**Project Aria: A New Tool for Egocentric Multi-Modal AI Research**  

---
Primary Category: cs.HC  
Categories: cs-CV, cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.13561v1)  

---


**ABSTRACT**  
Egocentric, multi-modal data as available on future augmented reality (AR) devices provides unique challenges and opportunities for machine perception. These future devices will need to be all-day wearable in a socially acceptable form-factor to support always available, context-aware and personalized AI applications. Our team at Meta Reality Labs Research built the Aria device, an egocentric, multi-modal data recording and streaming device with the goal to foster and accelerate research in this area. In this paper, we describe the Aria device hardware including its sensor configuration and the corresponding software tools that enable recording and processing of such data.

{{</citation>}}


### (81/116) Influences of Displaying Permission-related Information on Web Single Sign-On Login Decisions (Srivathsan G. Morkonda et al., 2023)

{{<citation>}}

Srivathsan G. Morkonda, Sonia Chiasson, Paul C. van Oorschot. (2023)  
**Influences of Displaying Permission-related Information on Web Single Sign-On Login Decisions**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2308.13074v1)  

---


**ABSTRACT**  
Web users are increasingly presented with multiple login options, including password-based login and common web single sign-on (SSO) login options such as "Login with Google" and "Login with Facebook". There has been little focus in previous studies on how users choose from a list of login options and how to better inform users about privacy issues in web SSO systems. In this paper, we conducted a 200-participant study to understand factors that influence participants' login decisions, and how they are affected by displaying permission differences across login options; permissions in SSO result in release of user personal information to third-party web sites through SSO identity providers. We compare and report on login decisions made by participants before and after viewing permission-related information, examine self-reported responses for reasons related to their login decisions, and report on the factors that motivated their choices. We find that usability preferences and inertia causes (habituation) were among the dominant factors influencing login decisions. After participants viewed permission-related information, many prioritised privacy over other factors, changing their login decisions to more privacy-friendly alternatives. Displaying permission-related information also influenced some participants to make tradeoffs between privacy and usability preferences.

{{</citation>}}


### (82/116) Augmenting a Firefighters PPE -- Gas Mask SCBA (Kunal Aneja et al., 2023)

{{<citation>}}

Kunal Aneja, Tejaswini Ramkumar Babu, Rachel Chan. (2023)  
**Augmenting a Firefighters PPE -- Gas Mask SCBA**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2308.13021v1)  

---


**ABSTRACT**  
PPE (Personal Protective Equipment) has allowed firefighters to perform their everyday tasks without getting harmed since the mid 1800s. Now, the advancement of technology has given rise to the improvements of PPE. PPE can now include sensors to detect any number of environmental hazards (chemical, biological, temperature etc.). As the GT class of CS3750, we have decided to create a version of an interface design sensor that will help firefighters in two ways: navigation and communication. In order to augment a firefighter display when they are within a building, we chose to augment their SCBA (self-contained breathing apparatus). The gas mask will include a small screen that displays vital information directly towards the firefighter without need of any other support. We used the Google Glass to display vital information directly towards the eye in a minimalistic manner, while also augmenting that by adding LED lights to simulate someone calling their name or other auditory signals.While our prototype focuses on two main components of a firefighters search and rescue in a building, both of them combine to augment a firefighters display when searching throughout a building to help improve accuracy, speed and overall experience.

{{</citation>}}


### (83/116) Language as Reality: A Co-Creative Storytelling Game Experience in 1001 Nights using Generative AI (Yuqian Sun et al., 2023)

{{<citation>}}

Yuqian Sun, Zhouyi Li, Ke Fang, Chang Hee Lee, Ali Asadipour. (2023)  
**Language as Reality: A Co-Creative Storytelling Game Experience in 1001 Nights using Generative AI**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-HC, cs.HC  
Keywords: AI, GPT, GPT-4, Generative AI  
[Paper Link](http://arxiv.org/abs/2308.12915v1)  

---


**ABSTRACT**  
In this paper, we present "1001 Nights", an AI-native game that allows players lead in-game reality through co-created storytelling with the character driven by large language model. The concept is inspired by Wittgenstein's idea of the limits of one's world being determined by the bounds of their language. Using advanced AI tools like GPT-4 and Stable Diffusion, the second iteration of the game enables the protagonist, Shahrzad, to realize words and stories in her world. The player can steer the conversation with the AI King towards specific keywords, which then become battle equipment in the game. This blend of interactive narrative and text-to-image transformation challenges the conventional border between the game world and reality through a dual perspective. We focus on Shahrzad, who seeks to alter her fate compared to the original folklore, and the player, who collaborates with AI to craft narratives and shape the game world. We explore the technical and design elements of implementing such a game with an objective to enhance the narrative game genre with AI-generated content and to delve into AI-native gameplay possibilities.

{{</citation>}}


### (84/116) Continuous Reinforcement Learning-based Dynamic Difficulty Adjustment in a Visual Working Memory Game (Masoud Rahimi et al., 2023)

{{<citation>}}

Masoud Rahimi, Hadi Moradi, Abdol-hossein Vahabie, Hamed Kebriaei. (2023)  
**Continuous Reinforcement Learning-based Dynamic Difficulty Adjustment in a Visual Working Memory Game**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-HC, cs-LG, cs.HC  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.12726v1)  

---


**ABSTRACT**  
Dynamic Difficulty Adjustment (DDA) is a viable approach to enhance a player's experience in video games. Recently, Reinforcement Learning (RL) methods have been employed for DDA in non-competitive games; nevertheless, they rely solely on discrete state-action space with a small search space. In this paper, we propose a continuous RL-based DDA methodology for a visual working memory (VWM) game to handle the complex search space for the difficulty of memorization. The proposed RL-based DDA tailors game difficulty based on the player's score and game difficulty in the last trial. We defined a continuous metric for the difficulty of memorization. Then, we consider the task difficulty and the vector of difficulty-score as the RL's action and state, respectively. We evaluated the proposed method through a within-subject experiment involving 52 subjects. The proposed approach was compared with two rule-based difficulty adjustment methods in terms of player's score and game experience measured by a questionnaire. The proposed RL-based approach resulted in a significantly better game experience in terms of competence, tension, and negative and positive affect. Players also achieved higher scores and win rates. Furthermore, the proposed RL-based DDA led to a significantly less decline in the score in a 20-trial session.

{{</citation>}}


## eess.IV (2)



### (85/116) Full-dose PET Synthesis from Low-dose PET Using High-efficiency Diffusion Denoising Probabilistic Model (Shaoyan Pan et al., 2023)

{{<citation>}}

Shaoyan Pan, Elham Abouei, Junbo Peng, Joshua Qian, Jacob F Wynne, Tonghe Wang, Chih-Wei Chang, Justin Roper, Jonathon A Nye, Hui Mao, Xiaofeng Yang. (2023)  
**Full-dose PET Synthesis from Low-dose PET Using High-efficiency Diffusion Denoising Probabilistic Model**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.13072v1)  

---


**ABSTRACT**  
To reduce the risks associated with ionizing radiation, a reduction of radiation exposure in PET imaging is needed. However, this leads to a detrimental effect on image contrast and quantification. High-quality PET images synthesized from low-dose data offer a solution to reduce radiation exposure. We introduce a diffusion-model-based approach for estimating full-dose PET images from low-dose ones: the PET Consistency Model (PET-CM) yielding synthetic quality comparable to state-of-the-art diffusion-based synthesis models, but with greater efficiency. There are two steps: a forward process that adds Gaussian noise to a full dose PET image at multiple timesteps, and a reverse diffusion process that employs a PET Shifted-window Vision Transformer (PET-VIT) network to learn the denoising procedure conditioned on the corresponding low-dose PETs. In PET-CM, the reverse process learns a consistency function for direct denoising of Gaussian noise to a clean full-dose PET. We evaluated the PET-CM in generating full-dose images using only 1/8 and 1/4 of the standard PET dose. Comparing 1/8 dose to full-dose images, PET-CM demonstrated impressive performance with normalized mean absolute error (NMAE) of 1.233+/-0.131%, peak signal-to-noise ratio (PSNR) of 33.915+/-0.933dB, structural similarity index (SSIM) of 0.964+/-0.009, and normalized cross-correlation (NCC) of 0.968+/-0.011, with an average generation time of 62 seconds per patient. This is a significant improvement compared to the state-of-the-art diffusion-based model with PET-CM reaching this result 12x faster. In the 1/4 dose to full-dose image experiments, PET-CM is also competitive, achieving an NMAE 1.058+/-0.092%, PSNR of 35.548+/-0.805dB, SSIM of 0.978+/-0.005, and NCC 0.981+/-0.007 The results indicate promising low-dose PET image quality improvements for clinical applications.

{{</citation>}}


### (86/116) Learned Local Attention Maps for Synthesising Vessel Segmentations (Yash Deo et al., 2023)

{{<citation>}}

Yash Deo, Rodrigo Bonazzola, Haoran Dou, Yan Xia, Tianyou Wei, Nishant Ravikumar, Alejandro F. Frangi, Toni Lassila. (2023)  
**Learned Local Attention Maps for Synthesising Vessel Segmentations**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2308.12861v1)  

---


**ABSTRACT**  
Magnetic resonance angiography (MRA) is an imaging modality for visualising blood vessels. It is useful for several diagnostic applications and for assessing the risk of adverse events such as haemorrhagic stroke (resulting from the rupture of aneurysms in blood vessels). However, MRAs are not acquired routinely, hence, an approach to synthesise blood vessel segmentations from more routinely acquired MR contrasts such as T1 and T2, would be useful. We present an encoder-decoder model for synthesising segmentations of the main cerebral arteries in the circle of Willis (CoW) from only T2 MRI. We propose a two-phase multi-objective learning approach, which captures both global and local features. It uses learned local attention maps generated by dilating the segmentation labels, which forces the network to only extract information from the T2 MRI relevant to synthesising the CoW. Our synthetic vessel segmentations generated from only T2 MRI achieved a mean Dice score of $0.79 \pm 0.03$ in testing, compared to state-of-the-art segmentation networks such as transformer U-Net ($0.71 \pm 0.04$) and nnU-net($0.68 \pm 0.05$), while using only a fraction of the parameters. The main qualitative difference between our synthetic vessel segmentations and the comparative models was in the sharper resolution of the CoW vessel segments, especially in the posterior circulation.

{{</citation>}}


## cs.AI (6)



### (87/116) Causal Parrots: Large Language Models May Talk Causality But Are Not Causal (Matej Zečević et al., 2023)

{{<citation>}}

Matej Zečević, Moritz Willig, Devendra Singh Dhami, Kristian Kersting. (2023)  
**Causal Parrots: Large Language Models May Talk Causality But Are Not Causal**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2308.13067v1)  

---


**ABSTRACT**  
Some argue scale is all what is needed to achieve AI, covering even causal models. We make it clear that large language models (LLMs) cannot be causal and give reason onto why sometimes we might feel otherwise. To this end, we define and exemplify a new subgroup of Structural Causal Model (SCM) that we call meta SCM which encode causal facts about other SCM within their variables. We conjecture that in the cases where LLM succeed in doing causal inference, underlying was a respective meta SCM that exposed correlations between causal facts in natural language on whose data the LLM was ultimately trained. If our hypothesis holds true, then this would imply that LLMs are like parrots in that they simply recite the causal knowledge embedded in the data. Our empirical analysis provides favoring evidence that current LLMs are even weak `causal parrots.'

{{</citation>}}


### (88/116) Perimeter Control with Heterogeneous Cordon Signal Behaviors: A Semi-Model Dependent Reinforcement Learning Approach (Jiajie Yu et al., 2023)

{{<citation>}}

Jiajie Yu, Pierre-Antoine Laharotte, Yu Han, Ludovic Leclercq. (2023)  
**Perimeter Control with Heterogeneous Cordon Signal Behaviors: A Semi-Model Dependent Reinforcement Learning Approach**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-SY, cs.AI, eess-SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.12985v1)  

---


**ABSTRACT**  
Perimeter Control (PC) strategies have been proposed to address urban road network control in oversaturated situations by monitoring transfer flows of the Protected Network (PN). The uniform metering rate for cordon signals in existing studies ignores the variety of local traffic states at the intersection level, which may cause severe local traffic congestion and ruin the network stability. This paper introduces a semi-model dependent Multi-Agent Reinforcement Learning (MARL) framework to conduct PC with heterogeneous cordon signal behaviors. The proposed strategy integrates the MARL-based signal control method with centralized feedback PC policy and is applied to cordon signals of the PN. It operates as a two-stage system, with the feedback PC strategy detecting the overall traffic state within the PN and then distributing local instructions to cordon signals controlled by agents in the MARL framework. Each cordon signal acts independently and differently, creating a slack and distributed PC for the PN. The combination of the model-free and model-based methods is achieved by reconstructing the action-value function of the local agents with PC feedback reward without violating the integrity of the local signal control policy learned from the RL training process. Through numerical tests with different demand patterns in a microscopic traffic environment, the proposed PC strategy (a) is shown robustness, scalability, and transferability, (b) outperforms state-of-the-art model-based PC strategies in increasing network throughput, reducing cordon queue and carbon emission.

{{</citation>}}


### (89/116) Human Comprehensible Active Learning of Genome-Scale Metabolic Networks (Lun Ai et al., 2023)

{{<citation>}}

Lun Ai, Shi-Shun Liang, Wang-Zhou Dai, Liam Hallett, Stephen H. Muggleton, Geoff S. Baldwin. (2023)  
**Human Comprehensible Active Learning of Genome-Scale Metabolic Networks**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI, q-bio-MN, q-bio-QM  
Keywords: Active Learning  
[Paper Link](http://arxiv.org/abs/2308.12740v1)  

---


**ABSTRACT**  
An important application of Synthetic Biology is the engineering of the host cell system to yield useful products. However, an increase in the scale of the host system leads to huge design space and requires a large number of validation trials with high experimental costs. A comprehensible machine learning approach that efficiently explores the hypothesis space and guides experimental design is urgently needed for the Design-Build-Test-Learn (DBTL) cycle of the host cell system. We introduce a novel machine learning framework ILP-iML1515 based on Inductive Logic Programming (ILP) that performs abductive logical reasoning and actively learns from training examples. In contrast to numerical models, ILP-iML1515 is built on comprehensible logical representations of a genome-scale metabolic model and can update the model by learning new logical structures from auxotrophic mutant trials. The ILP-iML1515 framework 1) allows high-throughput simulations and 2) actively selects experiments that reduce the experimental cost of learning gene functions in comparison to randomly selected experiments.

{{</citation>}}


### (90/116) SayCanPay: Heuristic Planning with Large Language Models using Learnable Domain Knowledge (Rishi Hazra et al., 2023)

{{<citation>}}

Rishi Hazra, Pedro Zuidberg Dos Martires, Luc De Raedt. (2023)  
**SayCanPay: Heuristic Planning with Large Language Models using Learnable Domain Knowledge**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2308.12682v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have demonstrated impressive planning abilities due to their vast "world knowledge". Yet, obtaining plans that are both feasible (grounded in affordances) and cost-effective (in plan length), remains a challenge, despite recent progress. This contrasts with heuristic planning methods that employ domain knowledge (formalized in action models such as PDDL) and heuristic search to generate feasible, optimal plans. Inspired by this, we propose to combine the power of LLMs and heuristic planning by leveraging the world knowledge of LLMs and the principles of heuristic search. Our approach, SayCanPay, employs LLMs to generate actions (Say) guided by learnable domain knowledge, that evaluates actions' feasibility (Can) and long-term reward/payoff (Pay), and heuristic search to select the best sequence of actions. Our contributions are (1) a novel framing of the LLM planning problem in the context of heuristic planning, (2) integrating grounding and cost-effective elements into the generated plans, and (3) using heuristic search over actions. Our extensive evaluations show that our model surpasses other LLM planning approaches.

{{</citation>}}


### (91/116) LR-XFL: Logical Reasoning-based Explainable Federated Learning (Yanci Zhang et al., 2023)

{{<citation>}}

Yanci Zhang, Han Yu. (2023)  
**LR-XFL: Logical Reasoning-based Explainable Federated Learning**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-DC, cs-LG, cs-LO, cs.AI  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2308.12681v1)  

---


**ABSTRACT**  
Federated learning (FL) is an emerging approach for training machine learning models collaboratively while preserving data privacy. The need for privacy protection makes it difficult for FL models to achieve global transparency and explainability. To address this limitation, we incorporate logic-based explanations into FL by proposing the Logical Reasoning-based eXplainable Federated Learning (LR-XFL) approach. Under LR-XFL, FL clients create local logic rules based on their local data and send them, along with model updates, to the FL server. The FL server connects the local logic rules through a proper logical connector that is derived based on properties of client data, without requiring access to the raw data. In addition, the server also aggregates the local model updates with weight values determined by the quality of the clients' local data as reflected by their uploaded logic rules. The results show that LR-XFL outperforms the most relevant baseline by 1.19%, 5.81% and 5.41% in terms of classification accuracy, rule accuracy and rule fidelity, respectively. The explicit rule evaluation and expression under LR-XFL enable human experts to validate and correct the rules on the server side, hence improving the global FL model's robustness to errors. It has the potential to enhance the transparency of FL models for areas like healthcare and finance where both data privacy and explainability are important.

{{</citation>}}


### (92/116) GPTEval: A Survey on Assessments of ChatGPT and GPT-4 (Rui Mao et al., 2023)

{{<citation>}}

Rui Mao, Guanyi Chen, Xulang Zhang, Frank Guerin, Erik Cambria. (2023)  
**GPTEval: A Survey on Assessments of ChatGPT and GPT-4**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: ChatGPT, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2308.12488v1)  

---


**ABSTRACT**  
The emergence of ChatGPT has generated much speculation in the press about its potential to disrupt social and economic systems. Its astonishing language ability has aroused strong curiosity among scholars about its performance in different domains. There have been many studies evaluating the ability of ChatGPT and GPT-4 in different tasks and disciplines. However, a comprehensive review summarizing the collective assessment findings is lacking. The objective of this survey is to thoroughly analyze prior assessments of ChatGPT and GPT-4, focusing on its language and reasoning abilities, scientific knowledge, and ethical considerations. Furthermore, an examination of the existing evaluation methods is conducted, offering several recommendations for future research in evaluating large language models.

{{</citation>}}


## cs.CR (2)



### (93/116) ZeroLeak: Using LLMs for Scalable and Cost Effective Side-Channel Patching (M. Caner Tol et al., 2023)

{{<citation>}}

M. Caner Tol, Berk Sunar. (2023)  
**ZeroLeak: Using LLMs for Scalable and Cost Effective Side-Channel Patching**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-LG, cs-SE, cs.CR  
Keywords: GPT, Language Model, Security  
[Paper Link](http://arxiv.org/abs/2308.13062v1)  

---


**ABSTRACT**  
Security critical software, e.g., OpenSSL, comes with numerous side-channel leakages left unpatched due to a lack of resources or experts. The situation will only worsen as the pace of code development accelerates, with developers relying on Large Language Models (LLMs) to automatically generate code. In this work, we explore the use of LLMs in generating patches for vulnerable code with microarchitectural side-channel leakages. For this, we investigate the generative abilities of powerful LLMs by carefully crafting prompts following a zero-shot learning approach. All generated code is dynamically analyzed by leakage detection tools, which are capable of pinpointing information leakage at the instruction level leaked either from secret dependent accesses or branches or vulnerable Spectre gadgets, respectively. Carefully crafted prompts are used to generate candidate replacements for vulnerable code, which are then analyzed for correctness and for leakage resilience. From a cost/performance perspective, the GPT4-based configuration costs in API calls a mere few cents per vulnerability fixed. Our results show that LLM-based patching is far more cost-effective and thus provides a scalable solution. Finally, the framework we propose will improve in time, especially as vulnerability detection tools and LLMs mature.

{{</citation>}}


### (94/116) Security Assessment and Hardening of Fog Computing Systems (Carmine Cesarano, 2023)

{{<citation>}}

Carmine Cesarano. (2023)  
**Security Assessment and Hardening of Fog Computing Systems**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2308.12707v1)  

---


**ABSTRACT**  
In recent years, there has been a shift in computing architectures, moving away from centralized cloud computing towards decentralized edge and fog computing. This shift is driven by factors such as the increasing volume of data generated at the edge, the growing demand for real-time processing and low-latency applications, and the need for improved privacy and data locality. Although this new paradigm offers numerous advantages, it also introduces significant security and reliability challenges. This paper aims to review the architectures and technologies employed in fog computing and identify opportunities for developing novel security assessment and security hardening techniques. These techniques include secure configuration and debloating to enhance the security of middleware, testing techniques to assess secure communication mechanisms, and automated rehosting to speed up the security testing of embedded firmware.

{{</citation>}}


## cs.IR (4)



### (95/116) Multi-BERT for Embeddings for Recommendation System (Shashidhar Reddy Javaji et al., 2023)

{{<citation>}}

Shashidhar Reddy Javaji, Krutika Sarode. (2023)  
**Multi-BERT for Embeddings for Recommendation System**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs.IR  
Keywords: BERT, Embedding  
[Paper Link](http://arxiv.org/abs/2308.13050v1)  

---


**ABSTRACT**  
In this paper, we propose a novel approach for generating document embeddings using a combination of Sentence-BERT (SBERT) and RoBERTa, two state-of-the-art natural language processing models. Our approach treats sentences as tokens and generates embeddings for them, allowing the model to capture both intra-sentence and inter-sentence relations within a document. We evaluate our model on a book recommendation task and demonstrate its effectiveness in generating more semantically rich and accurate document embeddings. To assess the performance of our approach, we conducted experiments on a book recommendation task using the Goodreads dataset. We compared the document embeddings generated using our MULTI-BERT model to those generated using SBERT alone. We used precision as our evaluation metric to compare the quality of the generated embeddings. Our results showed that our model consistently outperformed SBERT in terms of the quality of the generated embeddings. Furthermore, we found that our model was able to capture more nuanced semantic relations within documents, leading to more accurate recommendations. Overall, our results demonstrate the effectiveness of our approach and suggest that it is a promising direction for improving the performance of recommendation systems

{{</citation>}}


### (96/116) On Popularity Bias of Multimodal-aware Recommender Systems: a Modalities-driven Analysis (Daniele Malitesta et al., 2023)

{{<citation>}}

Daniele Malitesta, Giandomenico Cornacchia, Claudio Pomo, Tommaso Di Noia. (2023)  
**On Popularity Bias of Multimodal-aware Recommender Systems: a Modalities-driven Analysis**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: Amazon, Bias  
[Paper Link](http://arxiv.org/abs/2308.12911v1)  

---


**ABSTRACT**  
Multimodal-aware recommender systems (MRSs) exploit multimodal content (e.g., product images or descriptions) as items' side information to improve recommendation accuracy. While most of such methods rely on factorization models (e.g., MFBPR) as base architecture, it has been shown that MFBPR may be affected by popularity bias, meaning that it inherently tends to boost the recommendation of popular (i.e., short-head) items at the detriment of niche (i.e., long-tail) items from the catalog. Motivated by this assumption, in this work, we provide one of the first analyses on how multimodality in recommendation could further amplify popularity bias. Concretely, we evaluate the performance of four state-of-the-art MRSs algorithms (i.e., VBPR, MMGCN, GRCN, LATTICE) on three datasets from Amazon by assessing, along with recommendation accuracy metrics, performance measures accounting for the diversity of recommended items and the portion of retrieved niche items. To better investigate this aspect, we decide to study the separate influence of each modality (i.e., visual and textual) on popularity bias in different evaluation dimensions. Results, which demonstrate how the single modality may augment the negative effect of popularity bias, shed light on the importance to provide a more rigorous analysis of the performance of such models.

{{</citation>}}


### (97/116) On the Consistency of Average Embeddings for Item Recommendation (Walid Bendada et al., 2023)

{{<citation>}}

Walid Bendada, Guillaume Salha-Galvan, Romain Hennequin, Thomas Bouabça, Tristan Cazenave. (2023)  
**On the Consistency of Average Embeddings for Item Recommendation**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs-LG, cs.IR, stat-ML  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2308.12767v1)  

---


**ABSTRACT**  
A prevalent practice in recommender systems consists of averaging item embeddings to represent users or higher-level concepts in the same embedding space. This paper investigates the relevance of such a practice. For this purpose, we propose an expected precision score, designed to measure the consistency of an average embedding relative to the items used for its construction. We subsequently analyze the mathematical expression of this score in a theoretical setting with specific assumptions, as well as its empirical behavior on real-world data from music streaming services. Our results emphasize that real-world averages are less consistent for recommendation, which paves the way for future research to better align real-world embeddings with assumptions from our theoretical setting.

{{</citation>}}


### (98/116) Exploring the Integration Strategies of Retriever and Large Language Models (Ye Liu et al., 2023)

{{<citation>}}

Ye Liu, Semih Yavuz, Rui Meng, Meghana Moorthy, Shafiq Joty, Caiming Xiong, Yingbo Zhou. (2023)  
**Exploring the Integration Strategies of Retriever and Large Language Models**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs.IR  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2308.12574v1)  

---


**ABSTRACT**  
The integration of retrieved passages and large language models (LLMs), such as ChatGPTs, has significantly contributed to improving open-domain question answering. However, there is still a lack of exploration regarding the optimal approach for incorporating retrieved passages into the answer generation process. This paper aims to fill this gap by investigating different methods of combining retrieved passages with LLMs to enhance answer generation. We begin by examining the limitations of a commonly-used concatenation approach. Surprisingly, this approach often results in generating "unknown" outputs, even when the correct document is among the top-k retrieved passages. To address this issue, we explore four alternative strategies for integrating the retrieved passages with the LLMs. These strategies include two single-round methods that utilize chain-of-thought reasoning and two multi-round strategies that incorporate feedback loops. Through comprehensive analyses and experiments, we provide insightful observations on how to effectively leverage retrieved passages to enhance the answer generation capability of LLMs.

{{</citation>}}


## q-bio.QM (1)



### (99/116) The intersection of video capsule endoscopy and artificial intelligence: addressing unique challenges using machine learning (Shan Guleria et al., 2023)

{{<citation>}}

Shan Guleria, Benjamin Schwartz, Yash Sharma, Philip Fernandes, James Jablonski, Sodiq Adewole, Sanjana Srivastava, Fisher Rhoads, Michael Porter, Michelle Yeghyayan, Dylan Hyatt, Andrew Copland, Lubaina Ehsan, Donald Brown, Sana Syed. (2023)  
**The intersection of video capsule endoscopy and artificial intelligence: addressing unique challenges using machine learning**  

---
Primary Category: q-bio.QM  
Categories: cs-LG, q-bio-QM, q-bio.QM  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.13035v1)  

---


**ABSTRACT**  
Introduction: Technical burdens and time-intensive review processes limit the practical utility of video capsule endoscopy (VCE). Artificial intelligence (AI) is poised to address these limitations, but the intersection of AI and VCE reveals challenges that must first be overcome. We identified five challenges to address. Challenge #1: VCE data are stochastic and contains significant artifact. Challenge #2: VCE interpretation is cost-intensive. Challenge #3: VCE data are inherently imbalanced. Challenge #4: Existing VCE AIMLT are computationally cumbersome. Challenge #5: Clinicians are hesitant to accept AIMLT that cannot explain their process.   Methods: An anatomic landmark detection model was used to test the application of convolutional neural networks (CNNs) to the task of classifying VCE data. We also created a tool that assists in expert annotation of VCE data. We then created more elaborate models using different approaches including a multi-frame approach, a CNN based on graph representation, and a few-shot approach based on meta-learning.   Results: When used on full-length VCE footage, CNNs accurately identified anatomic landmarks (99.1%), with gradient weighted-class activation mapping showing the parts of each frame that the CNN used to make its decision. The graph CNN with weakly supervised learning (accuracy 89.9%, sensitivity of 91.1%), the few-shot model (accuracy 90.8%, precision 91.4%, sensitivity 90.9%), and the multi-frame model (accuracy 97.5%, precision 91.5%, sensitivity 94.8%) performed well. Discussion: Each of these five challenges is addressed, in part, by one of our AI-based models. Our goal of producing high performance using lightweight models that aim to improve clinician confidence was achieved.

{{</citation>}}


## cs.SD (5)



### (100/116) Generalizable Zero-Shot Speaker Adaptive Speech Synthesis with Disentangled Representations (Wenbin Wang et al., 2023)

{{<citation>}}

Wenbin Wang, Yang Song, Sanjay Jha. (2023)  
**Generalizable Zero-Shot Speaker Adaptive Speech Synthesis with Disentangled Representations**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-SD, cs.SD, eess-AS  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2308.13007v1)  

---


**ABSTRACT**  
While most research into speech synthesis has focused on synthesizing high-quality speech for in-dataset speakers, an equally essential yet unsolved problem is synthesizing speech for unseen speakers who are out-of-dataset with limited reference data, i.e., speaker adaptive speech synthesis. Many studies have proposed zero-shot speaker adaptive text-to-speech and voice conversion approaches aimed at this task. However, most current approaches suffer from the degradation of naturalness and speaker similarity when synthesizing speech for unseen speakers (i.e., speakers not in the training dataset) due to the poor generalizability of the model in out-of-distribution data. To address this problem, we propose GZS-TV, a generalizable zero-shot speaker adaptive text-to-speech and voice conversion model. GZS-TV introduces disentangled representation learning for both speaker embedding extraction and timbre transformation to improve model generalization and leverages the representation learning capability of the variational autoencoder to enhance the speaker encoder. Our experiments demonstrate that GZS-TV reduces performance degradation on unseen speakers and outperforms all baseline models in multiple datasets.

{{</citation>}}


### (101/116) Sparks of Large Audio Models: A Survey and Outlook (Siddique Latif et al., 2023)

{{<citation>}}

Siddique Latif, Moazzam Shoukat, Fahad Shamshad, Muhammad Usama, Heriberto Cuayáhuitl, Björn W. Schuller. (2023)  
**Sparks of Large Audio Models: A Survey and Outlook**  

---
Primary Category: cs.SD  
Categories: cs-SD, cs.SD, eess-AS  
Keywords: AI, Natural Language Processing, Speech Recognition  
[Paper Link](http://arxiv.org/abs/2308.12792v1)  

---


**ABSTRACT**  
This survey paper provides a comprehensive overview of the recent advancements and challenges in applying large language models to the field of audio signal processing. Audio processing, with its diverse signal representations and a wide range of sources--from human voices to musical instruments and environmental sounds--poses challenges distinct from those found in traditional Natural Language Processing scenarios. Nevertheless, \textit{Large Audio Models}, epitomized by transformer-based architectures, have shown marked efficacy in this sphere. By leveraging massive amount of data, these models have demonstrated prowess in a variety of audio tasks, spanning from Automatic Speech Recognition and Text-To-Speech to Music Generation, among others. Notably, recently these Foundational Audio Models, like SeamlessM4T, have started showing abilities to act as universal translators, supporting multiple speech tasks for up to 100 languages without any reliance on separate task-specific systems. This paper presents an in-depth analysis of state-of-the-art methodologies regarding \textit{Foundational Large Audio Models}, their performance benchmarks, and their applicability to real-world scenarios. We also highlight current limitations and provide insights into potential future research directions in the realm of \textit{Large Audio Models} with the intent to spark further discussion, thereby fostering innovation in the next generation of audio-processing systems. Furthermore, to cope with the rapid development in this area, we will consistently update the relevant repository with relevant recent articles and their open-source implementations at https://github.com/EmulationAI/awesome-large-audio-models.

{{</citation>}}


### (102/116) Real-time Detection of AI-Generated Speech for DeepFake Voice Conversion (Jordan J. Bird et al., 2023)

{{<citation>}}

Jordan J. Bird, Ahmad Lotfi. (2023)  
**Real-time Detection of AI-Generated Speech for DeepFake Voice Conversion**  

---
Primary Category: cs.SD  
Categories: cs-CL, cs-HC, cs-LG, cs-SD, cs.SD, eess-AS  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.12734v1)  

---


**ABSTRACT**  
There are growing implications surrounding generative AI in the speech domain that enable voice cloning and real-time voice conversion from one individual to another. This technology poses a significant ethical threat and could lead to breaches of privacy and misrepresentation, thus there is an urgent need for real-time detection of AI-generated speech for DeepFake Voice Conversion. To address the above emerging issues, the DEEP-VOICE dataset is generated in this study, comprised of real human speech from eight well-known figures and their speech converted to one another using Retrieval-based Voice Conversion. Presenting as a binary classification problem of whether the speech is real or AI-generated, statistical analysis of temporal audio features through t-testing reveals that there are significantly different distributions. Hyperparameter optimisation is implemented for machine learning models to identify the source of speech. Following the training of 208 individual machine learning models over 10-fold cross validation, it is found that the Extreme Gradient Boosting model can achieve an average classification accuracy of 99.3% and can classify speech in real-time, at around 0.004 milliseconds given one second of speech. All data generated for this study is released publicly for future research on AI speech detection.

{{</citation>}}


### (103/116) A Survey of AI Music Generation Tools and Models (Yueyue Zhu et al., 2023)

{{<citation>}}

Yueyue Zhu, Jared Baca, Banafsheh Rekabdar, Reza Rawassizadeh. (2023)  
**A Survey of AI Music Generation Tools and Models**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-HC, cs-SD, cs.SD, eess-AS  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.12982v1)  

---


**ABSTRACT**  
In this work, we provide a comprehensive survey of AI music generation tools, including both research projects and commercialized applications. To conduct our analysis, we classified music generation approaches into three categories: parameter-based, text-based, and visual-based classes. Our survey highlights the diverse possibilities and functional features of these tools, which cater to a wide range of users, from regular listeners to professional musicians. We observed that each tool has its own set of advantages and limitations. As a result, we have compiled a comprehensive list of these factors that should be considered during the tool selection process. Moreover, our survey offers critical insights into the underlying mechanisms and challenges of AI music generation.

{{</citation>}}


### (104/116) Attention-Based Acoustic Feature Fusion Network for Depression Detection (Xiao Xu et al., 2023)

{{<citation>}}

Xiao Xu, Yang Wang, Xinru Wei, Fei Wang, Xizhe Zhang. (2023)  
**Attention-Based Acoustic Feature Fusion Network for Depression Detection**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-SD, cs.SD, eess-AS  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2308.12478v1)  

---


**ABSTRACT**  
Depression, a common mental disorder, significantly influences individuals and imposes considerable societal impacts. The complexity and heterogeneity of the disorder necessitate prompt and effective detection, which nonetheless, poses a difficult challenge. This situation highlights an urgent requirement for improved detection methods. Exploiting auditory data through advanced machine learning paradigms presents promising research directions. Yet, existing techniques mainly rely on single-dimensional feature models, potentially neglecting the abundance of information hidden in various speech characteristics. To rectify this, we present the novel Attention-Based Acoustic Feature Fusion Network (ABAFnet) for depression detection. ABAFnet combines four different acoustic features into a comprehensive deep learning model, thereby effectively integrating and blending multi-tiered features. We present a novel weight adjustment module for late fusion that boosts performance by efficaciously synthesizing these features. The effectiveness of our approach is confirmed via extensive validation on two clinical speech databases, CNRAC and CS-NRAC, thereby outperforming previous methods in depression detection and subtype classification. Further in-depth analysis confirms the key role of each feature and highlights the importance of MFCCrelated features in speech-based depression detection.

{{</citation>}}


## cs.MA (1)



### (105/116) An Efficient Distributed Multi-Agent Reinforcement Learning for EV Charging Network Control (Amin Shojaeighadikolaei et al., 2023)

{{<citation>}}

Amin Shojaeighadikolaei, Morteza Hashemi. (2023)  
**An Efficient Distributed Multi-Agent Reinforcement Learning for EV Charging Network Control**  

---
Primary Category: cs.MA  
Categories: cs-LG, cs-MA, cs-SY, cs.MA, eess-SY, math-OC  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.12921v1)  

---


**ABSTRACT**  
The increasing trend in adopting electric vehicles (EVs) will significantly impact the residential electricity demand, which results in an increased risk of transformer overload in the distribution grid. To mitigate such risks, there are urgent needs to develop effective EV charging controllers. Currently, the majority of the EV charge controllers are based on a centralized approach for managing individual EVs or a group of EVs. In this paper, we introduce a decentralized Multi-agent Reinforcement Learning (MARL) charging framework that prioritizes the preservation of privacy for EV owners. We employ the Centralized Training Decentralized Execution-Deep Deterministic Policy Gradient (CTDE-DDPG) scheme, which provides valuable information to users during training while maintaining privacy during execution. Our results demonstrate that the CTDE framework improves the performance of the charging network by reducing the network costs. Moreover, we show that the Peak-to-Average Ratio (PAR) of the total demand is reduced, which, in turn, reduces the risk of transformer overload during the peak hours.

{{</citation>}}


## cs.SE (4)



### (106/116) Automated Test Generation for Medical Rules Web Services: A Case Study at the Cancer Registry of Norway (Christoph Laaber et al., 2023)

{{<citation>}}

Christoph Laaber, Tao Yue, Shaukat Ali, Thomas Schwitalla, Jan F. Nygård. (2023)  
**Automated Test Generation for Medical Rules Web Services: A Case Study at the Cancer Registry of Norway**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.12805v1)  

---


**ABSTRACT**  
The Cancer Registry of Norway (CRN) collects, curates, and manages data related to cancer patients in Norway, supported by an interactive, human-in-the-loop, socio-technical decision support software system. Automated software testing of this software system is inevitable; however, currently, it is limited in CRN's practice. To this end, we present an industrial case study to evaluate an AI-based system-level testing tool, i.e., EvoMaster, in terms of its effectiveness in testing CRN's software system. In particular, we focus on GURI, CRN's medical rule engine, which is a key component at the CRN. We test GURI with EvoMaster's black-box and white-box tools and study their test effectiveness regarding code coverage, errors found, and domain-specific rule coverage. The results show that all EvoMaster tools achieve a similar code coverage; i.e., around 19% line, 13% branch, and 20% method; and find a similar number of errors; i.e., 1 in GURI's code. Concerning domain-specific coverage, EvoMaster's black-box tool is the most effective in generating tests that lead to applied rules; i.e., 100% of the aggregation rules and between 12.86% and 25.81% of the validation rules; and to diverse rule execution results; i.e., 86.84% to 89.95% of the aggregation rules and 0.93% to 1.72% of the validation rules pass, and 1.70% to 3.12% of the aggregation rules and 1.58% to 3.74% of the validation rules fail. We further observe that the results are consistent across 10 versions of the rules. Based on these results, we recommend using EvoMaster's black-box tool to test GURI since it provides good results and advances the current state of practice at the CRN. Nonetheless, EvoMaster needs to be extended to employ domain-specific optimization objectives to improve test effectiveness further. Finally, we conclude with lessons learned and potential research directions, which we believe are generally applicable.

{{</citation>}}


### (107/116) Pre-training Code Representation with Semantic Flow Graph for Effective Bug Localization (Yali Du et al., 2023)

{{<citation>}}

Yali Du, Zhongxing Yu. (2023)  
**Pre-training Code Representation with Semantic Flow Graph for Effective Bug Localization**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2308.12773v1)  

---


**ABSTRACT**  
Enlightened by the big success of pre-training in natural language processing, pre-trained models for programming languages have been widely used to promote code intelligence in recent years. In particular, BERT has been used for bug localization tasks and impressive results have been obtained. However, these BERT-based bug localization techniques suffer from two issues. First, the pre-trained BERT model on source code does not adequately capture the deep semantics of program code. Second, the overall bug localization models neglect the necessity of large-scale negative samples in contrastive learning for representations of changesets and ignore the lexical similarity between bug reports and changesets during similarity estimation. We address these two issues by 1) proposing a novel directed, multiple-label code graph representation named Semantic Flow Graph (SFG), which compactly and adequately captures code semantics, 2) designing and training SemanticCodeBERT based on SFG, and 3) designing a novel Hierarchical Momentum Contrastive Bug Localization technique (HMCBL). Evaluation results show that our method achieves state-of-the-art performance in bug localization.

{{</citation>}}


### (108/116) Prompt-Enhanced Software Vulnerability Detection Using ChatGPT (Chenyuan Zhang et al., 2023)

{{<citation>}}

Chenyuan Zhang, Hao Liu, Jiutian Zeng, Kejing Yang, Yuhong Li, Hui Li. (2023)  
**Prompt-Enhanced Software Vulnerability Detection Using ChatGPT**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: ChatGPT, GPT, Vulnerability Detection  
[Paper Link](http://arxiv.org/abs/2308.12697v1)  

---


**ABSTRACT**  
With the increase in software vulnerabilities that cause significant economic and social losses, automatic vulnerability detection has become essential in software development and maintenance. Recently, large language models (LLMs) like GPT have received considerable attention due to their stunning intelligence, and some studies consider using ChatGPT for vulnerability detection. However, they do not fully consider the characteristics of LLMs, since their designed questions to ChatGPT are simple without a specific prompt design tailored for vulnerability detection. This paper launches a study on the performance of software vulnerability detection using ChatGPT with different prompt designs. Firstly, we complement previous work by applying various improvements to the basic prompt. Moreover, we incorporate structural and sequential auxiliary information to improve the prompt design. Besides, we leverage ChatGPT's ability of memorizing multi-round dialogue to design suitable prompts for vulnerability detection. We conduct extensive experiments on two vulnerability datasets to demonstrate the effectiveness of prompt-enhanced vulnerability detection using ChatGPT. We also analyze the merit and demerit of using ChatGPT for vulnerability detection.

{{</citation>}}


### (109/116) kTrans: Knowledge-Aware Transformer for Binary Code Embedding (Wenyu Zhu et al., 2023)

{{<citation>}}

Wenyu Zhu, Hao Wang, Yuchen Zhou, Jiaming Wang, Zihan Sha, Zeyu Gao, Chao Zhang. (2023)  
**kTrans: Knowledge-Aware Transformer for Binary Code Embedding**  

---
Primary Category: cs.SE  
Categories: cs-AI, cs-CR, cs-SE, cs.SE  
Keywords: Embedding, Transformer  
[Paper Link](http://arxiv.org/abs/2308.12659v1)  

---


**ABSTRACT**  
Binary Code Embedding (BCE) has important applications in various reverse engineering tasks such as binary code similarity detection, type recovery, control-flow recovery and data-flow analysis. Recent studies have shown that the Transformer model can comprehend the semantics of binary code to support downstream tasks. However, existing models overlooked the prior knowledge of assembly language. In this paper, we propose a novel Transformer-based approach, namely kTrans, to generate knowledge-aware binary code embedding. By feeding explicit knowledge as additional inputs to the Transformer, and fusing implicit knowledge with a novel pre-training task, kTrans provides a new perspective to incorporating domain knowledge into a Transformer framework. We inspect the generated embeddings with outlier detection and visualization, and also apply kTrans to 3 downstream tasks: Binary Code Similarity Detection (BCSD), Function Type Recovery (FTR) and Indirect Call Recognition (ICR). Evaluation results show that kTrans can generate high-quality binary code embeddings, and outperforms state-of-the-art (SOTA) approaches on downstream tasks by 5.2%, 6.8%, and 12.6% respectively. kTrans is publicly available at: https://github.com/Learner0x5a/kTrans-release

{{</citation>}}


## cs.IT (1)



### (110/116) Separating the Human Touch from AI-Generated Text using Higher Criticism: An Information-Theoretic Approach (Alon Kipnis, 2023)

{{<citation>}}

Alon Kipnis. (2023)  
**Separating the Human Touch from AI-Generated Text using Higher Criticism: An Information-Theoretic Approach**  

---
Primary Category: cs.IT  
Categories: cs-AI, cs-IT, cs.IT, math-IT, stat-AP  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.12747v1)  

---


**ABSTRACT**  
We propose a method to determine whether a given article was entirely written by a generative language model versus an alternative situation in which the article includes some significant edits by a different author, possibly a human. Our process involves many perplexity tests for the origin of individual sentences or other text atoms, combining these multiple tests using Higher Criticism (HC). As a by-product, the method identifies parts suspected to be edited. The method is motivated by the convergence of the log-perplexity to the cross-entropy rate and by a statistical model for edited text saying that sentences are mostly generated by the language model, except perhaps for a few sentences that might have originated via a different mechanism. We demonstrate the effectiveness of our method using real data and analyze the factors affecting its success. This analysis raises several interesting open challenges whose resolution may improve the method's effectiveness.

{{</citation>}}


## cs.MM (2)



### (111/116) Exploring Transferability of Multimodal Adversarial Samples for Vision-Language Pre-training Models with Contrastive Learning (Youze Wang et al., 2023)

{{<citation>}}

Youze Wang, Wenbo Hu, Yinpeng Dong, Richang Hong. (2023)  
**Exploring Transferability of Multimodal Adversarial Samples for Vision-Language Pre-training Models with Contrastive Learning**  

---
Primary Category: cs.MM  
Categories: cs-MM, cs.MM  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2308.12636v1)  

---


**ABSTRACT**  
Vision-language pre-training models (VLP) are vulnerable, especially to multimodal adversarial samples, which can be crafted by adding imperceptible perturbations on both original images and texts. However, under the black-box setting, there have been no works to explore the transferability of multimodal adversarial attacks against the VLP models. In this work, we take CLIP as the surrogate model and propose a gradient-based multimodal attack method to generate transferable adversarial samples against the VLP models. By applying the gradient to optimize the adversarial images and adversarial texts simultaneously, our method can better search for and attack the vulnerable images and text information pairs. To improve the transferability of the attack, we utilize contrastive learning including image-text contrastive learning and intra-modal contrastive learning to have a more generalized understanding of the underlying data distribution and mitigate the overfitting of the surrogate model so that the generated multimodal adversarial samples have a higher transferability for VLP models. Extensive experiments validate the effectiveness of the proposed method.

{{</citation>}}


### (112/116) Emotion-Aligned Contrastive Learning Between Images and Music (Shanti Stewart et al., 2023)

{{<citation>}}

Shanti Stewart, Tiantian Feng, Kleanthis Avramidis, Shrikanth Narayanan. (2023)  
**Emotion-Aligned Contrastive Learning Between Images and Music**  

---
Primary Category: cs.MM  
Categories: cs-MM, cs-SD, cs.MM, eess-AS  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2308.12610v1)  

---


**ABSTRACT**  
Traditional music search engines rely on retrieval methods that match natural language queries with music metadata. There have been increasing efforts to expand retrieval methods to consider the audio characteristics of music itself, using queries of various modalities including text, video, and speech. Most approaches aim to match general music semantics to the input queries, while only a few focus on affective qualities. We address the task of retrieving emotionally-relevant music from image queries by proposing a framework for learning an affective alignment between images and music audio. Our approach focuses on learning an emotion-aligned joint embedding space between images and music. This joint embedding space is learned via emotion-supervised contrastive learning, using an adapted cross-modal version of the SupCon loss. We directly evaluate the joint embeddings with cross-modal retrieval tasks (image-to-music and music-to-image) based on emotion labels. In addition, we investigate the generalizability of the learned music embeddings with automatic music tagging as a downstream task. Our experiments show that our approach successfully aligns images and music, and that the learned embedding space is effective for cross-modal retrieval applications.

{{</citation>}}


## cs.CE (1)



### (113/116) Hydrogen jet diffusion modeling by using physics-informed graph neural network and sparsely-distributed sensor data (Xinqi Zhang et al., 2023)

{{<citation>}}

Xinqi Zhang, Jihao Shi, Junjie Li, Guoming Chen. (2023)  
**Hydrogen jet diffusion modeling by using physics-informed graph neural network and sparsely-distributed sensor data**  

---
Primary Category: cs.CE  
Categories: cs-CE, cs.CE  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2308.12621v1)  

---


**ABSTRACT**  
Efficient modeling of jet diffusion during accidental release is critical for operation and maintenance management of hydrogen facilities. Deep learning has proven effective for concentration prediction in gas jet diffusion scenarios. Nonetheless, its reliance on extensive simulations as training data and its potential disregard for physical laws limit its applicability to unseen accidental scenarios. Recently, physics-informed neural networks (PINNs) have emerged to reconstruct spatial information by using data from sparsely-distributed sensors which are easily collected in real-world applications. However, prevailing approaches use the fully-connected neural network as the backbone without considering the spatial dependency of sensor data, which reduces the accuracy of concentration prediction. This study introduces the physics-informed graph deep learning approach (Physic_GNN) for efficient and accurate hydrogen jet diffusion prediction by using sparsely-distributed sensor data. Graph neural network (GNN) is used to model the spatial dependency of such sensor data by using graph nodes at which governing equations describing the physical law of hydrogen jet diffusion are immediately solved. The computed residuals are then applied to constrain the training process. Public experimental data of hydrogen jet is used to compare the accuracy and efficiency between our proposed approach Physic_GNN and state-of-the-art PINN. The results demonstrate our Physic_GNN exhibits higher accuracy and physical consistency of centerline concentration prediction given sparse concentration compared to PINN and more efficient compared to OpenFOAM. The proposed approach enables accurate and robust real-time spatial consequence reconstruction and underlying physical mechanisms analysis by using sparse sensor data.

{{</citation>}}


## eess.SY (1)



### (114/116) Deep Reinforcement Learning-driven Cross-Community Energy Interaction Optimal Scheduling (Yang Li et al., 2023)

{{<citation>}}

Yang Li, Fanjin Bu, Zhen Yang, Bin Wang, Meng Han. (2023)  
**Deep Reinforcement Learning-driven Cross-Community Energy Interaction Optimal Scheduling**  

---
Primary Category: eess.SY  
Categories: cs-LG, cs-SY, eess-SY, eess.SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.12554v1)  

---


**ABSTRACT**  
In order to coordinate energy interactions among various communities and energy conversions among multi-energy subsystems within the multi-community integrated energy system under uncertain conditions, and achieve overall optimization and scheduling of the comprehensive energy system, this paper proposes a comprehensive scheduling model that utilizes a multi-agent deep reinforcement learning algorithm to learn load characteristics of different communities and make decisions based on this knowledge. In this model, the scheduling problem of the integrated energy system is transformed into a Markov decision process and solved using a data-driven deep reinforcement learning algorithm, which avoids the need for modeling complex energy coupling relationships between multi-communities and multi-energy subsystems. The simulation results show that the proposed method effectively captures the load characteristics of different communities and utilizes their complementary features to coordinate reasonable energy interactions among them. This leads to a reduction in wind curtailment rate from 16.3% to 0% and lowers the overall operating cost by 5445.6 Yuan, demonstrating significant economic and environmental benefits.

{{</citation>}}


## physics.chem-ph (1)



### (115/116) May the Force be with You: Unified Force-Centric Pre-Training for 3D Molecular Conformations (Rui Feng et al., 2023)

{{<citation>}}

Rui Feng, Qi Zhu, Huan Tran, Binghong Chen, Aubrey Toland, Rampi Ramprasad, Chao Zhang. (2023)  
**May the Force be with You: Unified Force-Centric Pre-Training for 3D Molecular Conformations**  

---
Primary Category: physics.chem-ph  
Categories: cs-AI, cs-LG, physics-chem-ph, physics.chem-ph, q-bio-BM  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2308.14759v1)  

---


**ABSTRACT**  
Recent works have shown the promise of learning pre-trained models for 3D molecular representation. However, existing pre-training models focus predominantly on equilibrium data and largely overlook off-equilibrium conformations. It is challenging to extend these methods to off-equilibrium data because their training objective relies on assumptions of conformations being the local energy minima. We address this gap by proposing a force-centric pretraining model for 3D molecular conformations covering both equilibrium and off-equilibrium data. For off-equilibrium data, our model learns directly from their atomic forces. For equilibrium data, we introduce zero-force regularization and forced-based denoising techniques to approximate near-equilibrium forces. We obtain a unified pre-trained model for 3D molecular representation with over 15 million diverse conformations. Experiments show that, with our pre-training objective, we increase forces accuracy by around 3 times compared to the un-pre-trained Equivariant Transformer model. By incorporating regularizations on equilibrium data, we solved the problem of unstable MD simulations in vanilla Equivariant Transformers, achieving state-of-the-art simulation performance with 2.45 times faster inference time than NequIP. As a powerful molecular encoder, our pre-trained model achieves on-par performance with state-of-the-art property prediction tasks.

{{</citation>}}


## eess.SP (1)



### (116/116) Fall Detection using Knowledge Distillation Based Long short-term memory for Offline Embedded and Low Power Devices (Hannah Zhou et al., 2023)

{{<citation>}}

Hannah Zhou, Allison Chen, Celine Buer, Emily Chen, Kayleen Tang, Lauryn Gong, Zhiqi Liu, Jianbin Tang. (2023)  
**Fall Detection using Knowledge Distillation Based Long short-term memory for Offline Embedded and Low Power Devices**  

---
Primary Category: eess.SP  
Categories: cs-LG, eess-SP, eess.SP  
Keywords: Knowledge Distillation, LSTM  
[Paper Link](http://arxiv.org/abs/2308.12481v1)  

---


**ABSTRACT**  
This paper presents a cost-effective, low-power approach to unintentional fall detection using knowledge distillation-based LSTM (Long Short-Term Memory) models to significantly improve accuracy. With a primary focus on analyzing time-series data collected from various sensors, the solution offers real-time detection capabilities, ensuring prompt and reliable identification of falls. The authors investigate fall detection models that are based on different sensors, comparing their accuracy rates and performance. Furthermore, they employ the technique of knowledge distillation to enhance the models' precision, resulting in refined accurate configurations that consume lower power. As a result, this proposed solution presents a compelling avenue for the development of energy-efficient fall detection systems for future advancements in this critical domain.

{{</citation>}}
