---
draft: false
title: "arXiv @ 2023.10.25"
date: 2023-10-25
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.10.25"
    identifier: arxiv_20231025
    parent: 202310_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.LG (32)](#cslg-32)
- [cs.HC (5)](#cshc-5)
- [cs.CL (110)](#cscl-110)
- [eess.IV (2)](#eessiv-2)
- [cs.AI (7)](#csai-7)
- [stat.ML (4)](#statml-4)
- [cs.CV (24)](#cscv-24)
- [q-bio.NC (1)](#q-bionc-1)
- [cs.RO (3)](#csro-3)
- [cs.CR (2)](#cscr-2)
- [math.NA (1)](#mathna-1)
- [cs.IT (1)](#csit-1)
- [cs.SE (2)](#csse-2)
- [eess.SY (4)](#eesssy-4)
- [cs.NE (1)](#csne-1)
- [cs.DS (1)](#csds-1)
- [cs.SD (1)](#cssd-1)
- [cs.MM (1)](#csmm-1)
- [cs.IR (1)](#csir-1)
- [q-bio.GN (1)](#q-biogn-1)
- [cs.DB (1)](#csdb-1)
- [cs.SI (1)](#cssi-1)
- [q-bio.QM (1)](#q-bioqm-1)
- [physics.ed-ph (1)](#physicsed-ph-1)

## cs.LG (32)



### (1/208) Efficient Active Learning Halfspaces with Tsybakov Noise: A Non-convex Optimization Approach (Yinan Li et al., 2023)

{{<citation>}}

Yinan Li, Chicheng Zhang. (2023)  
**Efficient Active Learning Halfspaces with Tsybakov Noise: A Non-convex Optimization Approach**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, stat-ML  
Keywords: Active Learning  
[Paper Link](http://arxiv.org/abs/2310.15411v1)  

---


**ABSTRACT**  
We study the problem of computationally and label efficient PAC active learning $d$-dimensional halfspaces with Tsybakov Noise~\citep{tsybakov2004optimal} under structured unlabeled data distributions. Inspired by~\cite{diakonikolas2020learning}, we prove that any approximate first-order stationary point of a smooth nonconvex loss function yields a halfspace with a low excess error guarantee. In light of the above structural result, we design a nonconvex optimization-based algorithm with a label complexity of $\tilde{O}(d (\frac{1}{\epsilon})^{\frac{8-6\alpha}{3\alpha-1}})$\footnote{In the main body of this work, we use $\tilde{O}(\cdot), \tilde{\Theta}(\cdot)$ to hide factors of the form $\polylog(d, \frac{1}{\epsilon}, \frac{1}{\delta})$}, under the assumption that the Tsybakov noise parameter $\alpha \in (\frac13, 1]$, which narrows down the gap between the label complexities of the previously known efficient passive or active algorithms~\citep{diakonikolas2020polynomial,zhang2021improved} and the information-theoretic lower bound in this setting.

{{</citation>}}


### (2/208) HetGPT: Harnessing the Power of Prompt Tuning in Pre-Trained Heterogeneous Graph Neural Networks (Yihong Ma et al., 2023)

{{<citation>}}

Yihong Ma, Ning Yan, Jiayu Li, Masood Mortazavi, Nitesh V. Chawla. (2023)  
**HetGPT: Harnessing the Power of Prompt Tuning in Pre-Trained Heterogeneous Graph Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: GNN, GPT, Graph Neural Network, Graph Neural Networks, NLP, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2310.15318v1)  

---


**ABSTRACT**  
Graphs have emerged as a natural choice to represent and analyze the intricate patterns and rich information of the Web, enabling applications such as online page classification and social recommendation. The prevailing "pre-train, fine-tune" paradigm has been widely adopted in graph machine learning tasks, particularly in scenarios with limited labeled nodes. However, this approach often exhibits a misalignment between the training objectives of pretext tasks and those of downstream tasks. This gap can result in the "negative transfer" problem, wherein the knowledge gained from pre-training adversely affects performance in the downstream tasks. The surge in prompt-based learning within Natural Language Processing (NLP) suggests the potential of adapting a "pre-train, prompt" paradigm to graphs as an alternative. However, existing graph prompting techniques are tailored to homogeneous graphs, neglecting the inherent heterogeneity of Web graphs. To bridge this gap, we propose HetGPT, a general post-training prompting framework to improve the predictive performance of pre-trained heterogeneous graph neural networks (HGNNs). The key is the design of a novel prompting function that integrates a virtual class prompt and a heterogeneous feature prompt, with the aim to reformulate downstream tasks to mirror pretext tasks. Moreover, HetGPT introduces a multi-view neighborhood aggregation mechanism, capturing the complex neighborhood structure in heterogeneous graphs. Extensive experiments on three benchmark datasets demonstrate HetGPT's capability to enhance the performance of state-of-the-art HGNNs on semi-supervised node classification.

{{</citation>}}


### (3/208) Fast and Reliable Generation of EHR Time Series via Diffusion Models (Muhang Tian et al., 2023)

{{<citation>}}

Muhang Tian, Bernie Chen, Allan Guo, Shiyi Jiang, Anru R. Zhang. (2023)  
**Fast and Reliable Generation of EHR Time Series via Diffusion Models**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2310.15290v1)  

---


**ABSTRACT**  
Electronic Health Records (EHRs) are rich sources of patient-level data, including laboratory tests, medications, and diagnoses, offering valuable resources for medical data analysis. However, concerns about privacy often restrict access to EHRs, hindering downstream analysis. Researchers have explored various methods for generating privacy-preserving EHR data. In this study, we introduce a new method for generating diverse and realistic synthetic EHR time series data using Denoising Diffusion Probabilistic Models (DDPM). We conducted experiments on six datasets, comparing our proposed method with seven existing methods. Our results demonstrate that our approach significantly outperforms all existing methods in terms of data utility while requiring less training effort. Our approach also enhances downstream medical data analysis by providing diverse and realistic synthetic EHR data.

{{</citation>}}


### (4/208) GradSim: Gradient-Based Language Grouping for Effective Multilingual Training (Mingyang Wang et al., 2023)

{{<citation>}}

Mingyang Wang, Heike Adel, Lukas Lange, Jannik Strötgen, Hinrich Schütze. (2023)  
**GradSim: Gradient-Based Language Grouping for Effective Multilingual Training**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: Multilingual  
[Paper Link](http://arxiv.org/abs/2310.15269v1)  

---


**ABSTRACT**  
Most languages of the world pose low-resource challenges to natural language processing models. With multilingual training, knowledge can be shared among languages. However, not all languages positively influence each other and it is an open research question how to select the most suitable set of languages for multilingual training and avoid negative interference among languages whose characteristics or data distributions are not compatible. In this paper, we propose GradSim, a language grouping method based on gradient similarity. Our experiments on three diverse multilingual benchmark datasets show that it leads to the largest performance gains compared to other similarity measures and it is better correlated with cross-lingual model performance. As a result, we set the new state of the art on AfriSenti, a benchmark dataset for sentiment analysis on low-resource African languages. In our extensive analysis, we further reveal that besides linguistic features, the topics of the datasets play an important role for language grouping and that lower layers of transformer models encode language-specific features while higher layers capture task-specific information.

{{</citation>}}


### (5/208) Linear Representations of Sentiment in Large Language Models (Curt Tigges et al., 2023)

{{<citation>}}

Curt Tigges, Oskar John Hollinsworth, Atticus Geiger, Neel Nanda. (2023)  
**Linear Representations of Sentiment in Large Language Models**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.15154v1)  

---


**ABSTRACT**  
Sentiment is a pervasive feature in natural language text, yet it is an open question how sentiment is represented within Large Language Models (LLMs). In this study, we reveal that across a range of models, sentiment is represented linearly: a single direction in activation space mostly captures the feature across a range of tasks with one extreme for positive and the other for negative. Through causal interventions, we isolate this direction and show it is causally relevant in both toy tasks and real world datasets such as Stanford Sentiment Treebank. Through this case study we model a thorough investigation of what a single direction means on a broad data distribution.   We further uncover the mechanisms that involve this direction, highlighting the roles of a small subset of attention heads and neurons. Finally, we discover a phenomenon which we term the summarization motif: sentiment is not solely represented on emotionally charged words, but is additionally summarized at intermediate positions without inherent sentiment, such as punctuation and names. We show that in Stanford Sentiment Treebank zero-shot classification, 76% of above-chance classification accuracy is lost when ablating the sentiment direction, nearly half of which (36%) is due to ablating the summarized sentiment direction exclusively at comma positions.

{{</citation>}}


### (6/208) Federated Learning of Large Language Models with Parameter-Efficient Prompt Tuning and Adaptive Optimization (Tianshi Che et al., 2023)

{{<citation>}}

Tianshi Che, Ji Liu, Yang Zhou, Jiaxiang Ren, Jiwen Zhou, Victor S. Sheng, Huaiyu Dai, Dejing Dou. (2023)  
**Federated Learning of Large Language Models with Parameter-Efficient Prompt Tuning and Adaptive Optimization**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-DC, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.15080v1)  

---


**ABSTRACT**  
Federated learning (FL) is a promising paradigm to enable collaborative model training with decentralized data. However, the training process of Large Language Models (LLMs) generally incurs the update of significant parameters, which limits the applicability of FL techniques to tackle the LLMs in real scenarios. Prompt tuning can significantly reduce the number of parameters to update, but it either incurs performance degradation or low training efficiency. The straightforward utilization of prompt tuning in the FL often raises non-trivial communication costs and dramatically degrades performance. In addition, the decentralized data is generally non-Independent and Identically Distributed (non-IID), which brings client drift problems and thus poor performance. This paper proposes a Parameter-efficient prompt Tuning approach with Adaptive Optimization, i.e., FedPepTAO, to enable efficient and effective FL of LLMs. First, an efficient partial prompt tuning approach is proposed to improve performance and efficiency simultaneously. Second, a novel adaptive optimization method is developed to address the client drift problems on both the device and server sides to enhance performance further. Extensive experiments based on 10 datasets demonstrate the superb performance (up to 60.8\% in terms of accuracy) and efficiency (up to 97.59\% in terms of training time) of FedPepTAO compared with 9 baseline approaches. Our code is available at https://github.com/llm-eff/FedPepTAO.

{{</citation>}}


### (7/208) MGAS: Multi-Granularity Architecture Search for Effective and Efficient Neural Networks (Xiaoyun Liu et al., 2023)

{{<citation>}}

Xiaoyun Liu, Divya Saxena, Jiannong Cao, Yuqing Zhao, Penghui Ruan. (2023)  
**MGAS: Multi-Granularity Architecture Search for Effective and Efficient Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2310.15074v2)  

---


**ABSTRACT**  
Differentiable architecture search (DAS) revolutionizes neural architecture search (NAS) with time-efficient automation, transitioning from discrete candidate sampling and evaluation to differentiable super-net optimization and discretization. However, existing DAS methods either only conduct coarse-grained operation-level search or manually define the remaining ratios for fine-grained kernel-level and weight-level units, which fail to simultaneously optimize model size and model performance. Furthermore, these methods compromise search quality to reduce memory consumption. To tackle these issues, we introduce multi-granularity architecture search (MGAS), a unified framework which aims to comprehensively and memory-efficiently explore the multi-granularity search space to discover both effective and efficient neural networks. Specifically, we learn discretization functions specific to each granularity level to adaptively determine the remaining ratios according to the evolving architecture. This ensures an optimal balance among units of different granularity levels for different target model sizes. Considering the memory demands, we break down the super-net optimization and discretization into multiple sub-net stages. Nevertheless, the greedy nature of this approach may introduce bias in the early stages. To compensate for the bias, we propose progressive re-evaluation to allow for re-pruning and regrowing of previous units during subsequent stages. Extensive experiments on CIFAR-10, CIFAR-100 and ImageNet demonstrate that MGAS outperforms other state-of-the-art methods in achieving a better trade-off between model performance and model size.

{{</citation>}}


### (8/208) Meta- (out-of-context) learning in neural networks (Dmitrii Krasheninnikov et al., 2023)

{{<citation>}}

Dmitrii Krasheninnikov, Egor Krasheninnikov, Bruno Mlodozeniec, David Krueger. (2023)  
**Meta- (out-of-context) learning in neural networks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15047v2)  

---


**ABSTRACT**  
Brown et al. (2020) famously introduced the phenomenon of in-context learning in large language models (LLMs). We establish the existence of a phenomenon we call meta-out-of-context learning (meta-OCL) via carefully designed synthetic experiments with LLMs. Our results suggest that meta-OCL leads LLMs to more readily "internalize" the semantic content of text that is, or appears to be, broadly useful (such as true statements, or text from authoritative sources) and use it in appropriate circumstances. We further demonstrate meta-OCL in a synthetic computer vision setting, and propose two hypotheses for the emergence of meta-OCL: one relying on the way models store knowledge in their parameters, and another suggesting that the implicit gradient alignment bias of gradient-descent-based optimizers may be responsible. Finally, we reflect on what our results might imply about capabilities of future AI systems, and discuss potential risks. Our code can be found at https://github.com/krasheninnikov/internalization.

{{</citation>}}


### (9/208) Neural Snowflakes: Universal Latent Graph Inference via Trainable Latent Geometries (Haitz Sáez de Ocáriz Borde et al., 2023)

{{<citation>}}

Haitz Sáez de Ocáriz Borde, Anastasis Kratsios. (2023)  
**Neural Snowflakes: Universal Latent Graph Inference via Trainable Latent Geometries**  

---
Primary Category: cs.LG  
Categories: cs-DM, cs-LG, cs-NE, cs.LG, math-MG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2310.15003v1)  

---


**ABSTRACT**  
The inductive bias of a graph neural network (GNN) is largely encoded in its specified graph. Latent graph inference relies on latent geometric representations to dynamically rewire or infer a GNN's graph to maximize the GNN's predictive downstream performance, but it lacks solid theoretical foundations in terms of embedding-based representation guarantees. This paper addresses this issue by introducing a trainable deep learning architecture, coined neural snowflake, that can adaptively implement fractal-like metrics on $\mathbb{R}^d$. We prove that any given finite weights graph can be isometrically embedded by a standard MLP encoder. Furthermore, when the latent graph can be represented in the feature space of a sufficiently regular kernel, we show that the combined neural snowflake and MLP encoder do not succumb to the curse of dimensionality by using only a low-degree polynomial number of parameters in the number of nodes. This implementation enables a low-dimensional isometric embedding of the latent graph. We conduct synthetic experiments to demonstrate the superior metric learning capabilities of neural snowflakes when compared to more familiar spaces like Euclidean space. Additionally, we carry out latent graph inference experiments on graph benchmarks. Consistently, the neural snowflake model achieves predictive performance that either matches or surpasses that of the state-of-the-art latent graph inference models. Importantly, this performance improvement is achieved without requiring random search for optimal latent geometry. Instead, the neural snowflake model achieves this enhancement in a differentiable manner.

{{</citation>}}


### (10/208) Understanding the Inner Workings of Language Models Through Representation Dissimilarity (Davis Brown et al., 2023)

{{<citation>}}

Davis Brown, Charles Godfrey, Nicholas Konz, Jonathan Tu, Henry Kvinge. (2023)  
**Understanding the Inner Workings of Language Models Through Representation Dissimilarity**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.14993v1)  

---


**ABSTRACT**  
As language models are applied to an increasing number of real-world applications, understanding their inner workings has become an important issue in model trust, interpretability, and transparency. In this work we show that representation dissimilarity measures, which are functions that measure the extent to which two model's internal representations differ, can be a valuable tool for gaining insight into the mechanics of language models. Among our insights are: (i) an apparent asymmetry in the internal representations of model using SoLU and GeLU activation functions, (ii) evidence that dissimilarity measures can identify and locate generalization properties of models that are invisible via in-distribution test set performance, and (iii) new evaluations of how language model features vary as width and depth are increased. Our results suggest that dissimilarity measures are a promising set of tools for shedding light on the inner workings of language models.

{{</citation>}}


### (11/208) XTSC-Bench: Quantitative Benchmarking for Explainers on Time Series Classification (Jacqueline Höllig et al., 2023)

{{<citation>}}

Jacqueline Höllig, Steffen Thoma, Florian Grimm. (2023)  
**XTSC-Bench: Quantitative Benchmarking for Explainers on Time Series Classification**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2310.14957v1)  

---


**ABSTRACT**  
Despite the growing body of work on explainable machine learning in time series classification (TSC), it remains unclear how to evaluate different explainability methods. Resorting to qualitative assessment and user studies to evaluate explainers for TSC is difficult since humans have difficulties understanding the underlying information contained in time series data. Therefore, a systematic review and quantitative comparison of explanation methods to confirm their correctness becomes crucial. While steps to standardized evaluations were taken for tabular, image, and textual data, benchmarking explainability methods on time series is challenging due to a) traditional metrics not being directly applicable, b) implementation and adaption of traditional metrics for time series in the literature vary, and c) varying baseline implementations. This paper proposes XTSC-Bench, a benchmarking tool providing standardized datasets, models, and metrics for evaluating explanation methods on TSC. We analyze 3 perturbation-, 6 gradient- and 2 example-based explanation methods to TSC showing that improvements in the explainers' robustness and reliability are necessary, especially for multivariate data.

{{</citation>}}


### (12/208) Diverse Priors for Deep Reinforcement Learning (Chenfan Weng et al., 2023)

{{<citation>}}

Chenfan Weng, Zhongguo Li. (2023)  
**Diverse Priors for Deep Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.14864v1)  

---


**ABSTRACT**  
In Reinforcement Learning (RL), agents aim at maximizing cumulative rewards in a given environment. During the learning process, RL agents face the dilemma of exploitation and exploration: leveraging existing knowledge to acquire rewards or seeking potentially higher ones. Using uncertainty as a guiding principle provides an active and effective approach to solving this dilemma and ensemble-based methods are one of the prominent avenues for quantifying uncertainty. Nevertheless, conventional ensemble-based uncertainty estimation lacks an explicit prior, deviating from Bayesian principles. Besides, this method requires diversity among members to generate less biased uncertainty estimation results. To address the above problems, previous research has incorporated random functions as priors. Building upon these foundational efforts, our work introduces an innovative approach with delicately designed prior NNs, which can incorporate maximal diversity in the initial value functions of RL. Our method has demonstrated superior performance compared with the random prior approaches in solving classic control problems and general exploration tasks, significantly improving sample efficiency.

{{</citation>}}


### (13/208) ULTRA-DP: Unifying Graph Pre-training with Multi-task Graph Dual Prompt (Mouxiang Chen et al., 2023)

{{<citation>}}

Mouxiang Chen, Zemin Liu, Chenghao Liu, Jundong Li, Qiheng Mao, Jianling Sun. (2023)  
**ULTRA-DP: Unifying Graph Pre-training with Multi-task Graph Dual Prompt**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2310.14845v1)  

---


**ABSTRACT**  
Recent research has demonstrated the efficacy of pre-training graph neural networks (GNNs) to capture the transferable graph semantics and enhance the performance of various downstream tasks. However, the semantic knowledge learned from pretext tasks might be unrelated to the downstream task, leading to a semantic gap that limits the application of graph pre-training. To reduce this gap, traditional approaches propose hybrid pre-training to combine various pretext tasks together in a multi-task learning fashion and learn multi-grained knowledge, which, however, cannot distinguish tasks and results in some transferable task-specific knowledge distortion by each other. Moreover, most GNNs cannot distinguish nodes located in different parts of the graph, making them fail to learn position-specific knowledge and lead to suboptimal performance. In this work, inspired by the prompt-based tuning in natural language processing, we propose a unified framework for graph hybrid pre-training which injects the task identification and position identification into GNNs through a prompt mechanism, namely multi-task graph dual prompt (ULTRA-DP). Based on this framework, we propose a prompt-based transferability test to find the most relevant pretext task in order to reduce the semantic gap. To implement the hybrid pre-training tasks, beyond the classical edge prediction task (node-node level), we further propose a novel pre-training paradigm based on a group of $k$-nearest neighbors (node-group level). The combination of them across different scales is able to comprehensively express more structural semantics and derive richer multi-grained knowledge. Extensive experiments show that our proposed ULTRA-DP can significantly enhance the performance of hybrid pre-training methods and show the generalizability to other pre-training tasks and backbone architectures.

{{</citation>}}


### (14/208) Calibration of Time-Series Forecasting Transformers: Detecting and Adapting Context-Driven Distribution Shift (Mouxiang Chen et al., 2023)

{{<citation>}}

Mouxiang Chen, Lefei Shen, Han Fu, Zhuo Li, Jianling Sun, Chenghao Liu. (2023)  
**Calibration of Time-Series Forecasting Transformers: Detecting and Adapting Context-Driven Distribution Shift**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2310.14838v1)  

---


**ABSTRACT**  
Recent years have witnessed the success of introducing Transformers to time series forecasting. From a data generation perspective, we illustrate that existing Transformers are susceptible to distribution shifts driven by temporal contexts, whether observed or unobserved. Such context-driven distribution shift (CDS) introduces biases in predictions within specific contexts and poses challenges for conventional training paradigm. In this paper, we introduce a universal calibration methodology for the detection and adaptation of CDS with a trained Transformer model. To this end, we propose a novel CDS detector, termed the "residual-based CDS detector" or "Reconditionor", which quantifies the model's vulnerability to CDS by evaluating the mutual information between prediction residuals and their corresponding contexts. A high Reconditionor score indicates a severe susceptibility, thereby necessitating model adaptation. In this circumstance, we put forth a straightforward yet potent adapter framework for model calibration, termed the "sample-level contextualized adapter" or "SOLID". This framework involves the curation of a contextually similar dataset to the provided test sample and the subsequent fine-tuning of the model's prediction layer with a limited number of steps. Our theoretical analysis demonstrates that this adaptation strategy is able to achieve an optimal equilibrium between bias and variance. Notably, our proposed Reconditionor and SOLID are model-agnostic and readily adaptable to a wide range of Transformers. Extensive experiments show that SOLID consistently enhances the performance of current SOTA Transformers on real-world datasets, especially on cases with substantial CDS detected by the proposed Reconditionor, thus validate the effectiveness of the calibration approach.

{{</citation>}}


### (15/208) Harnessing Attention Mechanisms: Efficient Sequence Reduction using Attention-based Autoencoders (Daniel Biermann et al., 2023)

{{<citation>}}

Daniel Biermann, Fabrizio Palumbo, Morten Goodwin, Ole-Christoffer Granmo. (2023)  
**Harnessing Attention Mechanisms: Efficient Sequence Reduction using Attention-based Autoencoders**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2310.14837v1)  

---


**ABSTRACT**  
Many machine learning models use the manipulation of dimensions as a driving force to enable models to identify and learn important features in data. In the case of sequential data this manipulation usually happens on the token dimension level. Despite the fact that many tasks require a change in sequence length itself, the step of sequence length reduction usually happens out of necessity and in a single step. As far as we are aware, no model uses the sequence length reduction step as an additional opportunity to tune the models performance. In fact, sequence length manipulation as a whole seems to be an overlooked direction. In this study we introduce a novel attention-based method that allows for the direct manipulation of sequence lengths. To explore the method's capabilities, we employ it in an autoencoder model. The autoencoder reduces the input sequence to a smaller sequence in latent space. It then aims to reproduce the original sequence from this reduced form. In this setting, we explore the methods reduction performance for different input and latent sequence lengths. We are able to show that the autoencoder retains all the significant information when reducing the original sequence to half its original size. When reducing down to as low as a quarter of its original size, the autoencoder is still able to reproduce the original sequence with an accuracy of around 90%.

{{</citation>}}


### (16/208) Text2Topic: Multi-Label Text Classification System for Efficient Topic Detection in User Generated Content with Zero-Shot Capabilities (Fengjun Wang et al., 2023)

{{<citation>}}

Fengjun Wang, Moran Beladev, Ofri Kleinfeld, Elina Frayerman, Tal Shachar, Eran Fainman, Karen Lastmann Assaraf, Sarai Mizrachi, Benjamin Wang. (2023)  
**Text2Topic: Multi-Label Text Classification System for Efficient Topic Detection in User Generated Content with Zero-Shot Capabilities**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Text Classification, Transformer, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2310.14817v1)  

---


**ABSTRACT**  
Multi-label text classification is a critical task in the industry. It helps to extract structured information from large amount of textual data. We propose Text to Topic (Text2Topic), which achieves high multi-label classification performance by employing a Bi-Encoder Transformer architecture that utilizes concatenation, subtraction, and multiplication of embeddings on both text and topic. Text2Topic also supports zero-shot predictions, produces domain-specific text embeddings, and enables production-scale batch-inference with high throughput. The final model achieves accurate and comprehensive results compared to state-of-the-art baselines, including large language models (LLMs).   In this study, a total of 239 topics are defined, and around 1.6 million text-topic pairs annotations (in which 200K are positive) are collected on approximately 120K texts from 3 main data sources on Booking.com. The data is collected with optimized smart sampling and partial labeling. The final Text2Topic model is deployed on a real-world stream processing platform, and it outperforms other models with 92.9% micro mAP, as well as a 75.8% macro mAP score. We summarize the modeling choices which are extensively tested through ablation studies, and share detailed in-production decision-making steps.

{{</citation>}}


### (17/208) Leveraging Ensemble Diversity for Robust Self-Training in the Presence of Sample Selection Bias (Ambroise Odonnat et al., 2023)

{{<citation>}}

Ambroise Odonnat, Vasilii Feofanov, Ievgen Redko. (2023)  
**Leveraging Ensemble Diversity for Robust Self-Training in the Presence of Sample Selection Bias**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2310.14814v2)  

---


**ABSTRACT**  
Self-training is a well-known approach for semi-supervised learning. It consists of iteratively assigning pseudo-labels to unlabeled data for which the model is confident and treating them as labeled examples. For neural networks, softmax prediction probabilities are often used as a confidence measure, despite the fact that they are known to be overconfident, even for wrong predictions. This phenomenon is particularly intensified in the presence of sample selection bias, i.e., when data labeling is subject to some constraint. To address this issue, we propose a novel confidence measure, called $\mathcal{T}$-similarity, built upon the prediction diversity of an ensemble of linear classifiers. We provide the theoretical analysis of our approach by studying stationary points and describing the relationship between the diversity of the individual members and their performance. We empirically demonstrate the benefit of our confidence measure for three different pseudo-labeling policies on classification datasets of various data modalities.

{{</citation>}}


### (18/208) Improved K-mer Based Prediction of Protein-Protein Interactions With Chaos Game Representation, Deep Learning and Reduced Representation Bias (Ruth Veevers et al., 2023)

{{<citation>}}

Ruth Veevers, Dan MacLean. (2023)  
**Improved K-mer Based Prediction of Protein-Protein Interactions With Chaos Game Representation, Deep Learning and Reduced Representation Bias**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2310.14764v1)  

---


**ABSTRACT**  
Protein-protein interactions drive many biological processes, including the detection of phytopathogens by plants' R-Proteins and cell surface receptors. Many machine learning studies have attempted to predict protein-protein interactions but performance is highly dependent on training data; models have been shown to accurately predict interactions when the proteins involved are included in the training data, but achieve consistently poorer results when applied to previously unseen proteins. In addition, models that are trained using proteins that take part in multiple interactions can suffer from representation bias, where predictions are driven not by learned biological features but by learning of the structure of the interaction dataset.   We present a method for extracting unique pairs from an interaction dataset, generating non-redundant paired data for unbiased machine learning. After applying the method to datasets containing _Arabidopsis thaliana_ and pathogen effector interations, we developed a convolutional neural network model capable of learning and predicting interactions from Chaos Game Representations of proteins' coding genes.

{{</citation>}}


### (19/208) Rethinking Tokenizer and Decoder in Masked Graph Modeling for Molecules (Zhiyuan Liu et al., 2023)

{{<citation>}}

Zhiyuan Liu, Yaorui Shi, An Zhang, Enzhi Zhang, Kenji Kawaguchi, Xiang Wang, Tat-Seng Chua. (2023)  
**Rethinking Tokenizer and Decoder in Masked Graph Modeling for Molecules**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2310.14753v1)  

---


**ABSTRACT**  
Masked graph modeling excels in the self-supervised representation learning of molecular graphs. Scrutinizing previous studies, we can reveal a common scheme consisting of three key components: (1) graph tokenizer, which breaks a molecular graph into smaller fragments (i.e., subgraphs) and converts them into tokens; (2) graph masking, which corrupts the graph with masks; (3) graph autoencoder, which first applies an encoder on the masked graph to generate the representations, and then employs a decoder on the representations to recover the tokens of the original graph. However, the previous MGM studies focus extensively on graph masking and encoder, while there is limited understanding of tokenizer and decoder. To bridge the gap, we first summarize popular molecule tokenizers at the granularity of node, edge, motif, and Graph Neural Networks (GNNs), and then examine their roles as the MGM's reconstruction targets. Further, we explore the potential of adopting an expressive decoder in MGM. Our results show that a subgraph-level tokenizer and a sufficiently expressive decoder with remask decoding have a large impact on the encoder's representation learning. Finally, we propose a novel MGM method SimSGT, featuring a Simple GNN-based Tokenizer (SGT) and an effective decoding strategy. We empirically validate that our method outperforms the existing molecule self-supervised learning methods. Our codes and checkpoints are available at https://github.com/syr-cn/SimSGT.

{{</citation>}}


### (20/208) Extended Deep Adaptive Input Normalization for Preprocessing Time Series Data for Neural Networks (Marcus A. K. September et al., 2023)

{{<citation>}}

Marcus A. K. September, Francesco Sanna Passino, Leonie Goldmann, Anton Hinel. (2023)  
**Extended Deep Adaptive Input Normalization for Preprocessing Time Series Data for Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, stat-ML  
Keywords: AI, Time Series  
[Paper Link](http://arxiv.org/abs/2310.14720v1)  

---


**ABSTRACT**  
Data preprocessing is a crucial part of any machine learning pipeline, and it can have a significant impact on both performance and training efficiency. This is especially evident when using deep neural networks for time series prediction and classification: real-world time series data often exhibit irregularities such as multi-modality, skewness and outliers, and the model performance can degrade rapidly if these characteristics are not adequately addressed. In this work, we propose the EDAIN (Extended Deep Adaptive Input Normalization) layer, a novel adaptive neural layer that learns how to appropriately normalize irregular time series data for a given task in an end-to-end fashion, instead of using a fixed normalization scheme. This is achieved by optimizing its unknown parameters simultaneously with the deep neural network using back-propagation. Our experiments, conducted using synthetic data, a credit default prediction dataset, and a large-scale limit order book benchmark dataset, demonstrate the superior performance of the EDAIN layer when compared to conventional normalization methods and existing adaptive time series preprocessing layers.

{{</citation>}}


### (21/208) A Hybrid GNN approach for predicting node data for 3D meshes (Shwetha Salimath et al., 2023)

{{<citation>}}

Shwetha Salimath, Francesca Bugiotti, Frederic Magoules. (2023)  
**A Hybrid GNN approach for predicting node data for 3D meshes**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-NA, cs.LG, math-NA  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2310.14707v1)  

---


**ABSTRACT**  
Metal forging is used to manufacture dies. We require the best set of input parameters for the process to be efficient. Currently, we predict the best parameters using the finite element method by generating simulations for the different initial conditions, which is a time-consuming process. In this paper, introduce a hybrid approach that helps in processing and generating new data simulations using a surrogate graph neural network model based on graph convolutions, having a cheaper time cost. We also introduce a hybrid approach that helps in processing and generating new data simulations using the model. Given a dataset representing meshes, our focus is on the conversion of the available information into a graph or point cloud structure. This new representation enables deep learning. The predicted result is similar, with a low error when compared to that produced using the finite element method. The new models have outperformed existing PointNet and simple graph neural network models when applied to produce the simulations.

{{</citation>}}


### (22/208) Data Pruning via Moving-one-Sample-out (Haoru Tan et al., 2023)

{{<citation>}}

Haoru Tan, Sitong Wu, Fei Du, Yukang Chen, Zhibin Wang, Fan Wang, Xiaojuan Qi. (2023)  
**Data Pruning via Moving-one-Sample-out**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs.LG  
Keywords: Pruning  
[Paper Link](http://arxiv.org/abs/2310.14664v2)  

---


**ABSTRACT**  
In this paper, we propose a novel data-pruning approach called moving-one-sample-out (MoSo), which aims to identify and remove the least informative samples from the training set. The core insight behind MoSo is to determine the importance of each sample by assessing its impact on the optimal empirical risk. This is achieved by measuring the extent to which the empirical risk changes when a particular sample is excluded from the training set. Instead of using the computationally expensive leaving-one-out-retraining procedure, we propose an efficient first-order approximator that only requires gradient information from different training stages. The key idea behind our approximation is that samples with gradients that are consistently aligned with the average gradient of the training set are more informative and should receive higher scores, which could be intuitively understood as follows: if the gradient from a specific sample is consistent with the average gradient vector, it implies that optimizing the network using the sample will yield a similar effect on all remaining samples. Experimental results demonstrate that MoSo effectively mitigates severe performance degradation at high pruning ratios and achieves satisfactory performance across various settings.

{{</citation>}}


### (23/208) $Λ$-Split: A Privacy-Preserving Split Computing Framework for Cloud-Powered Generative AI (Shoki Ohta et al., 2023)

{{<citation>}}

Shoki Ohta, Takayuki Nishio. (2023)  
**$Λ$-Split: A Privacy-Preserving Split Computing Framework for Cloud-Powered Generative AI**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-DC, cs-LG, cs-NI, cs.LG  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2310.14651v1)  

---


**ABSTRACT**  
In the wake of the burgeoning expansion of generative artificial intelligence (AI) services, the computational demands inherent to these technologies frequently necessitate cloud-powered computational offloading, particularly for resource-constrained mobile devices. These services commonly employ prompts to steer the generative process, and both the prompts and the resultant content, such as text and images, may harbor privacy-sensitive or confidential information, thereby elevating security and privacy risks. To mitigate these concerns, we introduce $\Lambda$-Split, a split computing framework to facilitate computational offloading while simultaneously fortifying data privacy against risks such as eavesdropping and unauthorized access. In $\Lambda$-Split, a generative model, usually a deep neural network (DNN), is partitioned into three sub-models and distributed across the user's local device and a cloud server: the input-side and output-side sub-models are allocated to the local, while the intermediate, computationally-intensive sub-model resides on the cloud server. This architecture ensures that only the hidden layer outputs are transmitted, thereby preventing the external transmission of privacy-sensitive raw input and output data. Given the black-box nature of DNNs, estimating the original input or output from intercepted hidden layer outputs poses a significant challenge for malicious eavesdroppers. Moreover, $\Lambda$-Split is orthogonal to traditional encryption-based security mechanisms, offering enhanced security when deployed in conjunction. We empirically validate the efficacy of the $\Lambda$-Split framework using Llama 2 and Stable Diffusion XL, representative large language and diffusion models developed by Meta and Stability AI, respectively. Our $\Lambda$-Split implementation is publicly accessible at https://github.com/nishio-laboratory/lambda_split.

{{</citation>}}


### (24/208) GNNEvaluator: Evaluating GNN Performance On Unseen Graphs Without Labels (Xin Zheng et al., 2023)

{{<citation>}}

Xin Zheng, Miao Zhang, Chunyang Chen, Soheila Molaei, Chuan Zhou, Shirui Pan. (2023)  
**GNNEvaluator: Evaluating GNN Performance On Unseen Graphs Without Labels**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2310.14586v1)  

---


**ABSTRACT**  
Evaluating the performance of graph neural networks (GNNs) is an essential task for practical GNN model deployment and serving, as deployed GNNs face significant performance uncertainty when inferring on unseen and unlabeled test graphs, due to mismatched training-test graph distributions. In this paper, we study a new problem, GNN model evaluation, that aims to assess the performance of a specific GNN model trained on labeled and observed graphs, by precisely estimating its performance (e.g., node classification accuracy) on unseen graphs without labels. Concretely, we propose a two-stage GNN model evaluation framework, including (1) DiscGraph set construction and (2) GNNEvaluator training and inference. The DiscGraph set captures wide-range and diverse graph data distribution discrepancies through a discrepancy measurement function, which exploits the outputs of GNNs related to latent node embeddings and node class predictions. Under the effective training supervision from the DiscGraph set, GNNEvaluator learns to precisely estimate node classification accuracy of the to-be-evaluated GNN model and makes an accurate inference for evaluating GNN model performance. Extensive experiments on real-world unseen and unlabeled test graphs demonstrate the effectiveness of our proposed method for GNN model evaluation.

{{</citation>}}


### (25/208) Tensor Decomposition Based Attention Module for Spiking Neural Networks (Haoyu Deng et al., 2023)

{{<citation>}}

Haoyu Deng, Ruijie Zhu, Xuerui Qiu, Yule Duan, Malu Zhang, Liangjian Deng. (2023)  
**Tensor Decomposition Based Attention Module for Spiking Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Attention, Transformer  
[Paper Link](http://arxiv.org/abs/2310.14576v1)  

---


**ABSTRACT**  
The attention mechanism has been proven to be an effective way to improve spiking neural network (SNN). However, based on the fact that the current SNN input data flow is split into tensors to process on GPUs, none of the previous works consider the properties of tensors to implement an attention module. This inspires us to rethink current SNN from the perspective of tensor-relevant theories. Using tensor decomposition, we design the \textit{projected full attention} (PFA) module, which demonstrates excellent results with linearly growing parameters. Specifically, PFA is composed by the \textit{linear projection of spike tensor} (LPST) module and \textit{attention map composing} (AMC) module. In LPST, we start by compressing the original spike tensor into three projected tensors using a single property-preserving strategy with learnable parameters for each dimension. Then, in AMC, we exploit the inverse procedure of the tensor decomposition process to combine the three tensors into the attention map using a so-called connecting factor. To validate the effectiveness of the proposed PFA module, we integrate it into the widely used VGG and ResNet architectures for classification tasks. Our method achieves state-of-the-art performance on both static and dynamic benchmark datasets, surpassing the existing SNN models with Transformer-based and CNN-based backbones.

{{</citation>}}


### (26/208) Making RL with Preference-based Feedback Efficient via Randomization (Runzhe Wu et al., 2023)

{{<citation>}}

Runzhe Wu, Wen Sun. (2023)  
**Making RL with Preference-based Feedback Efficient via Randomization**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-HC, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.14554v1)  

---


**ABSTRACT**  
Reinforcement Learning algorithms that learn from human feedback (RLHF) need to be efficient in terms of statistical complexity, computational complexity, and query complexity. In this work, we consider the RLHF setting where the feedback is given in the format of preferences over pairs of trajectories. In the linear MDP model, by using randomization in algorithm design, we present an algorithm that is sample efficient (i.e., has near-optimal worst-case regret bounds) and has polynomial running time (i.e., computational complexity is polynomial with respect to relevant parameters). Our algorithm further minimizes the query complexity through a novel randomized active learning procedure. In particular, our algorithm demonstrates a near-optimal tradeoff between the regret bound and the query complexity. To extend the results to more general nonlinear function approximation, we design a model-based randomized algorithm inspired by the idea of Thompson sampling. Our algorithm minimizes Bayesian regret bound and query complexity, again achieving a near-optimal tradeoff between these two quantities. Computation-wise, similar to the prior Thompson sampling algorithms under the regular RL setting, the main computation primitives of our algorithm are Bayesian supervised learning oracles which have been heavily investigated on the empirical side when applying Thompson sampling algorithms to RL benchmark problems.

{{</citation>}}


### (27/208) Corruption-Robust Offline Reinforcement Learning with General Function Approximation (Chenlu Ye et al., 2023)

{{<citation>}}

Chenlu Ye, Rui Yang, Quanquan Gu, Tong Zhang. (2023)  
**Corruption-Robust Offline Reinforcement Learning with General Function Approximation**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.14550v1)  

---


**ABSTRACT**  
We investigate the problem of corruption robustness in offline reinforcement learning (RL) with general function approximation, where an adversary can corrupt each sample in the offline dataset, and the corruption level $\zeta\geq0$ quantifies the cumulative corruption amount over $n$ episodes and $H$ steps. Our goal is to find a policy that is robust to such corruption and minimizes the suboptimality gap with respect to the optimal policy for the uncorrupted Markov decision processes (MDPs). Drawing inspiration from the uncertainty-weighting technique from the robust online RL setting \citep{he2022nearly,ye2022corruptionrobust}, we design a new uncertainty weight iteration procedure to efficiently compute on batched samples and propose a corruption-robust algorithm for offline RL. Notably, under the assumption of single policy coverage and the knowledge of $\zeta$, our proposed algorithm achieves a suboptimality bound that is worsened by an additive factor of $\mathcal O(\zeta \cdot (\text{CC}(\lambda,\hat{\mathcal F},\mathcal Z_n^H))^{1/2} (C(\hat{\mathcal F},\mu))^{-1/2} n^{-1})$ due to the corruption. Here $\text{CC}(\lambda,\hat{\mathcal F},\mathcal Z_n^H)$ is the coverage coefficient that depends on the regularization parameter $\lambda$, the confidence set $\hat{\mathcal F}$, and the dataset $\mathcal Z_n^H$, and $C(\hat{\mathcal F},\mu)$ is a coefficient that depends on $\hat{\mathcal F}$ and the underlying data distribution $\mu$. When specialized to linear MDPs, the corruption-dependent error term reduces to $\mathcal O(\zeta d n^{-1})$ with $d$ being the dimension of the feature map, which matches the existing lower bound for corrupted linear MDPs. This suggests that our analysis is tight in terms of the corruption-dependent term.

{{</citation>}}


### (28/208) Context-Aware Prediction of User Engagement on Online Social Platforms (Heinrich Peters et al., 2023)

{{<citation>}}

Heinrich Peters, Yozen Liu, Francesco Barbieri, Raiyan A. Baten, Sandra C. Matz, Maarten W. Bos. (2023)  
**Context-Aware Prediction of User Engagement on Online Social Platforms**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-HC, cs-LG, cs-SI, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2310.14533v1)  

---


**ABSTRACT**  
The success of online social platforms hinges on their ability to predict and understand user behavior at scale. Here, we present data suggesting that context-aware modeling approaches may offer a holistic yet lightweight and potentially privacy-preserving representation of user engagement on online social platforms. Leveraging deep LSTM neural networks to analyze more than 100 million Snapchat sessions from almost 80.000 users, we demonstrate that patterns of active and passive use are predictable from past behavior (R2=0.345) and that the integration of context information substantially improves predictive performance compared to the behavioral baseline model (R2=0.522). Features related to smartphone connectivity status, location, temporal context, and weather were found to capture non-redundant variance in user engagement relative to features derived from histories of in-app behaviors. Further, we show that a large proportion of variance can be accounted for with minimal behavioral histories if momentary context information is considered (R2=0.44). These results indicate the potential of context-aware approaches for making models more efficient and privacy-preserving by reducing the need for long data histories. Finally, we employ model explainability techniques to glean preliminary insights into the underlying behavioral mechanisms. Our findings are consistent with the notion of context-contingent, habit-driven patterns of active and passive use, underscoring the value of contextualized representations of user behavior for predicting user engagement on social platforms.

{{</citation>}}


### (29/208) Marginal Nodes Matter: Towards Structure Fairness in Graphs (Xiaotian Han et al., 2023)

{{<citation>}}

Xiaotian Han, Kaixiong Zhou, Ting-Hsiang Wang, Jundong Li, Fei Wang, Na Zou. (2023)  
**Marginal Nodes Matter: Towards Structure Fairness in Graphs**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2310.14527v1)  

---


**ABSTRACT**  
In social network, a person located at the periphery region (marginal node) is likely to be treated unfairly when compared with the persons at the center. While existing fairness works on graphs mainly focus on protecting sensitive attributes (e.g., age and gender), the fairness incurred by the graph structure should also be given attention. On the other hand, the information aggregation mechanism of graph neural networks amplifies such structure unfairness, as marginal nodes are often far away from other nodes. In this paper, we focus on novel fairness incurred by the graph structure on graph neural networks, named \emph{structure fairness}. Specifically, we first analyzed multiple graphs and observed that marginal nodes in graphs have a worse performance of downstream tasks than others in graph neural networks. Motivated by the observation, we propose \textbf{S}tructural \textbf{Fair} \textbf{G}raph \textbf{N}eural \textbf{N}etwork (SFairGNN), which combines neighborhood expansion based structure debiasing with hop-aware attentive information aggregation to achieve structure fairness. Our experiments show \SFairGNN can significantly improve structure fairness while maintaining overall performance in the downstream tasks.

{{</citation>}}


### (30/208) Do We Really Need Contrastive Learning for Graph Representation? (Yulan Hu et al., 2023)

{{<citation>}}

Yulan Hu, Sheng Ouyang, Jingyu Liu, Ge Chen, Zhirui Yang, Junchen Wan, Fuzheng Zhang, Zhongyuan Wang, Yong Liu. (2023)  
**Do We Really Need Contrastive Learning for Graph Representation?**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2310.14525v1)  

---


**ABSTRACT**  
In recent years, contrastive learning has emerged as a dominant self-supervised paradigm, attracting numerous research interests in the field of graph learning. Graph contrastive learning (GCL) aims to embed augmented anchor samples close to each other while pushing the embeddings of other samples (negative samples) apart. However, existing GCL methods require large and diverse negative samples to ensure the quality of embeddings, and recent studies typically leverage samples excluding the anchor and positive samples as negative samples, potentially introducing false negative samples (negatives that share the same class as the anchor). Additionally, this practice can result in heavy computational burden and high time complexity of $O(N^2)$, which is particularly unaffordable for large graphs. To address these deficiencies, we leverage rank learning and propose a simple yet effective model, GraphRank. Specifically, we first generate two graph views through corruption. Then, we compute the similarity of pairwise nodes (anchor node and positive node) in both views, an arbitrary node in the latter view is selected as a negative node, and its similarity with the anchor node is computed. Based on this, we introduce rank-based learning to measure similarity scores which successfully relieve the false negative provlem and decreases the time complexity from $O(N^2)$ to $O(N)$. Moreover, we conducted extensive experiments across multiple graph tasks, demonstrating that GraphRank performs favorably against other cutting-edge GCL methods in various tasks.

{{</citation>}}


### (31/208) Efficient Heterogeneous Graph Learning via Random Projection (Jun Hu et al., 2023)

{{<citation>}}

Jun Hu, Bryan Hooi, Bingsheng He. (2023)  
**Efficient Heterogeneous Graph Learning via Random Projection**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-SI, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2310.14481v1)  

---


**ABSTRACT**  
Heterogeneous Graph Neural Networks (HGNNs) are powerful tools for deep learning on heterogeneous graphs. Typical HGNNs require repetitive message passing during training, limiting efficiency for large-scale real-world graphs. Recent pre-computation-based HGNNs use one-time message passing to transform a heterogeneous graph into regular-shaped tensors, enabling efficient mini-batch training. Existing pre-computation-based HGNNs can be mainly categorized into two styles, which differ in how much information loss is allowed and efficiency. We propose a hybrid pre-computation-based HGNN, named Random Projection Heterogeneous Graph Neural Network (RpHGNN), which combines the benefits of one style's efficiency with the low information loss of the other style. To achieve efficiency, the main framework of RpHGNN consists of propagate-then-update iterations, where we introduce a Random Projection Squashing step to ensure that complexity increases only linearly. To achieve low information loss, we introduce a Relation-wise Neighbor Collection component with an Even-odd Propagation Scheme, which aims to collect information from neighbors in a finer-grained way. Experimental results indicate that our approach achieves state-of-the-art results on seven small and large benchmark datasets while also being 230% faster compared to the most effective baseline. Surprisingly, our approach not only surpasses pre-processing-based baselines but also outperforms end-to-end methods.

{{</citation>}}


### (32/208) Attention-Enhancing Backdoor Attacks Against BERT-based Models (Weimin Lyu et al., 2023)

{{<citation>}}

Weimin Lyu, Songzhu Zheng, Lu Pang, Haibin Ling, Chao Chen. (2023)  
**Attention-Enhancing Backdoor Attacks Against BERT-based Models**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Attention, BERT, NLP, Sentiment Analysis  
[Paper Link](http://arxiv.org/abs/2310.14480v2)  

---


**ABSTRACT**  
Recent studies have revealed that \textit{Backdoor Attacks} can threaten the safety of natural language processing (NLP) models. Investigating the strategies of backdoor attacks will help to understand the model's vulnerability. Most existing textual backdoor attacks focus on generating stealthy triggers or modifying model weights. In this paper, we directly target the interior structure of neural networks and the backdoor mechanism. We propose a novel Trojan Attention Loss (TAL), which enhances the Trojan behavior by directly manipulating the attention patterns. Our loss can be applied to different attacking methods to boost their attack efficacy in terms of attack successful rates and poisoning rates. It applies to not only traditional dirty-label attacks, but also the more challenging clean-label attacks. We validate our method on different backbone models (BERT, RoBERTa, and DistilBERT) and various tasks (Sentiment Analysis, Toxic Detection, and Topic Classification).

{{</citation>}}


## cs.HC (5)



### (33/208) Visual Elements and Cognitive Biases Influence Interpretations of Trends in Scatter Plots (Alexandre Filipowicz et al., 2023)

{{<citation>}}

Alexandre Filipowicz, Scott Carter, Nayeli Bravo, Rumen Iliev, Shabnam Hakimi, David Ayman Shamma, Kent Lyons, Candice Hogan, Charlene Wu. (2023)  
**Visual Elements and Cognitive Biases Influence Interpretations of Trends in Scatter Plots**  

---
Primary Category: cs.HC  
Categories: cs-CY, cs-GR, cs-HC, cs-MM, cs-SI, cs.HC  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2310.15406v1)  

---


**ABSTRACT**  
Visualizations are common methods to convey information but also increasingly used to spread misinformation. It is therefore important to understand the factors people use to interpret visualizations. In this paper, we focus on factors that influence interpretations of scatter plots, investigating the extent to which common visual aspects of scatter plots (outliers and trend lines) and cognitive biases (people's beliefs) influence perception of correlation trends. We highlight three main findings: outliers skew trend perception but exert less influence than other points; trend lines make trends seem stronger but also mitigate the influence of some outliers; and people's beliefs have a small influence on perceptions of weak, but not strong correlations. From these results we derive guidelines for adjusting visual elements to mitigate the influence of factors that distort interpretations of scatter plots. We explore how these guidelines may generalize to other visualization types and make recommendations for future studies.

{{</citation>}}


### (34/208) The Self 2.0: How AI-Enhanced Self-Clones Transform Self-Perception and Improve Presentation Skills (Qingxiao Zheng et al., 2023)

{{<citation>}}

Qingxiao Zheng, Yun Huang. (2023)  
**The Self 2.0: How AI-Enhanced Self-Clones Transform Self-Perception and Improve Presentation Skills**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15112v1)  

---


**ABSTRACT**  
This study explores the impact of AI-generated digital self-clones on improving online presentation skills. We carried out a mixed-design experiment involving 44 international students, comparing self-recorded videos (control) with self-clone videos (AI group) for English presentation practice. The AI videos utilized voice cloning, face swapping, lip-sync, and body-language simulation to refine participants' original presentations in terms of repetition, filler words, and pronunciation. Machine-rated scores indicated enhancements in speech performance for both groups. Though the groups didn't significantly differ, the AI group exhibited a heightened depth of reflection, self-compassion, and a meaningful transition from a corrective to an enhancive approach to self-critique. Within the AI group, congruence between self-perception and AI self-clones resulted in diminished speech anxiety and increased enjoyment. Our findings recommend the ethical employment of digital self-clones to enhance the emotional and cognitive facets of skill development.

{{</citation>}}


### (35/208) Synergizing Human-AI Agency: A Guide of 23 Heuristics for Service Co-Creation with LLM-Based Agents (Qingxiao Zheng et al., 2023)

{{<citation>}}

Qingxiao Zheng, Zhongwei Xu, Abhinav Choudhary, Yuting Chen, Yongming Li, Yun Huang. (2023)  
**Synergizing Human-AI Agency: A Guide of 23 Heuristics for Service Co-Creation with LLM-Based Agents**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-HC, cs.HC  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2310.15065v1)  

---


**ABSTRACT**  
This empirical study serves as a primer for interested service providers to determine if and how Large Language Models (LLMs) technology will be integrated for their practitioners and the broader community. We investigate the mutual learning journey of non-AI experts and AI through CoAGent, a service co-creation tool with LLM-based agents. Engaging in a three-stage participatory design processes, we work with with 23 domain experts from public libraries across the U.S., uncovering their fundamental challenges of integrating AI into human workflows. Our findings provide 23 actionable "heuristics for service co-creation with AI", highlighting the nuanced shared responsibilities between humans and AI. We further exemplar 9 foundational agency aspects for AI, emphasizing essentials like ownership, fair treatment, and freedom of expression. Our innovative approach enriches the participatory design model by incorporating AI as crucial stakeholders and utilizing AI-AI interaction to identify blind spots. Collectively, these insights pave the way for synergistic and ethical human-AI co-creation in service contexts, preparing for workforce ecosystems where AI coexists.

{{</citation>}}


### (36/208) From Proprietary to High-Level Trigger-Action Programming Rules: A Natural Language Processing Approach (Ekene Attoh et al., 2023)

{{<citation>}}

Ekene Attoh, Beat Signer. (2023)  
**From Proprietary to High-Level Trigger-Action Programming Rules: A Natural Language Processing Approach**  

---
Primary Category: cs.HC  
Categories: H-5-m, cs-HC, cs.HC  
Keywords: Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2310.15024v1)  

---


**ABSTRACT**  
With the rise of popular task automation or IoT platforms such as 'If This Then That (IFTTT)', users can define rules to enable interactions between smart devices in their environment and thereby improve their daily lives. However, the rules authored via these platforms are usually tied to the platforms and sometimes even to the specific devices for which they have been defined. Therefore, when a user wishes to move to a different environment controlled by a different platform and/or devices, they need to recreate their rules for the new environment. The rise in the number of smart devices further adds to the complexity of rule authoring since users will have to navigate an ever-changing landscape of IoT devices. In order to address this problem, we need human-computer interaction that works across the boundaries of specific IoT platforms and devices. A step towards this human-computer interaction across platforms and devices is the introduction of a high-level semantic model for end-user IoT development, enabling users to create rules at a higher level of abstraction. However, many users who already got used to the rule representation in their favourite tool might be unwilling to learn and adapt to a new representation. We present a method for translating proprietary rules to a high-level semantic model by using natural language processing techniques. Our translation enables users to work with their familiar rule representation language and tool, and at the same time apply their rules across different IoT platforms and devices.

{{</citation>}}


### (37/208) DocTrack: A Visually-Rich Document Dataset Really Aligned with Human Eye Movement for Machine Reading (Hao Wang et al., 2023)

{{<citation>}}

Hao Wang, Qingxuan Wang, Yue Li, Changqing Wang, Chenhui Chu, Rui Wang. (2023)  
**DocTrack: A Visually-Rich Document Dataset Really Aligned with Human Eye Movement for Machine Reading**  

---
Primary Category: cs.HC  
Categories: cs-CV, cs-HC, cs-IR, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.14802v1)  

---


**ABSTRACT**  
The use of visually-rich documents (VRDs) in various fields has created a demand for Document AI models that can read and comprehend documents like humans, which requires the overcoming of technical, linguistic, and cognitive barriers. Unfortunately, the lack of appropriate datasets has significantly hindered advancements in the field. To address this issue, we introduce \textsc{DocTrack}, a VRD dataset really aligned with human eye-movement information using eye-tracking technology. This dataset can be used to investigate the challenges mentioned above. Additionally, we explore the impact of human reading order on document understanding tasks and examine what would happen if a machine reads in the same order as a human. Our results suggest that although Document AI models have made significant progress, they still have a long way to go before they can read VRDs as accurately, continuously, and flexibly as humans do. These findings have potential implications for future research and development of Document AI models. The data is available at \url{https://github.com/hint-lab/doctrack}.

{{</citation>}}


## cs.CL (110)



### (38/208) GPT-4 as an Effective Zero-Shot Evaluator for Scientific Figure Captions (Ting-Yao Hsu et al., 2023)

{{<citation>}}

Ting-Yao Hsu, Chieh-Yang Huang, Ryan Rossi, Sungchul Kim, C. Lee Giles, Ting-Hao K. Huang. (2023)  
**GPT-4 as an Effective Zero-Shot Evaluator for Scientific Figure Captions**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, GPT-4, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2310.15405v1)  

---


**ABSTRACT**  
There is growing interest in systems that generate captions for scientific figures. However, assessing these systems output poses a significant challenge. Human evaluation requires academic expertise and is costly, while automatic evaluation depends on often low-quality author-written captions. This paper investigates using large language models (LLMs) as a cost-effective, reference-free method for evaluating figure captions. We first constructed SCICAP-EVAL, a human evaluation dataset that contains human judgments for 3,600 scientific figure captions, both original and machine-made, for 600 arXiv figures. We then prompted LLMs like GPT-4 and GPT-3 to score (1-6) each caption based on its potential to aid reader understanding, given relevant context such as figure-mentioning paragraphs. Results show that GPT-4, used as a zero-shot evaluator, outperformed all other models and even surpassed assessments made by Computer Science and Informatics undergraduates, achieving a Kendall correlation score of 0.401 with Ph.D. students rankings

{{</citation>}}


### (39/208) Irreducible Curriculum for Language Model Pretraining (Simin Fan et al., 2023)

{{<citation>}}

Simin Fan, Martin Jaggi. (2023)  
**Irreducible Curriculum for Language Model Pretraining**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.15389v1)  

---


**ABSTRACT**  
Automatic data selection and curriculum design for training large language models is challenging, with only a few existing methods showing improvements over standard training. Furthermore, current schemes focus on domain-level selection, overlooking the more fine-grained contributions of each individual training point. It is difficult to apply traditional datapoint selection methods on large language models: most online batch selection methods perform two-times forward or backward passes, which introduces considerable extra costs with large-scale models. To mitigate these obstacles, we propose irreducible curriculum as a curriculum learning algorithm for language model pretraining, which prioritizes samples with higher learnability. Specifically, to avoid prohibitive extra computation overhead, we simulate the sample loss along the main model's training trajectory using a small-scale proxy model. Our experiments on the RedPajama-1B dataset demonstrate a consistent improvement on validation perplexity across all 7 domains compared to random uniform baseline and the anti-curriculum strategy. Our method also reduces the sharpness of the network and illustrates a better 5-shot accuracy on MMLU benchmarks.

{{</citation>}}


### (40/208) GD-COMET: A Geo-Diverse Commonsense Inference Model (Mehar Bhatia et al., 2023)

{{<citation>}}

Mehar Bhatia, Vered Shwartz. (2023)  
**GD-COMET: A Geo-Diverse Commonsense Inference Model**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, NLP  
[Paper Link](http://arxiv.org/abs/2310.15383v1)  

---


**ABSTRACT**  
With the increasing integration of AI into everyday life, it's becoming crucial to design AI systems that serve users from diverse backgrounds by making them culturally aware. In this paper, we present GD-COMET, a geo-diverse version of the COMET commonsense inference model. GD-COMET goes beyond Western commonsense knowledge and is capable of generating inferences pertaining to a broad range of cultures. We demonstrate the effectiveness of GD-COMET through a comprehensive human evaluation across 5 diverse cultures, as well as extrinsic evaluation on a geo-diverse task. The evaluation shows that GD-COMET captures and generates culturally nuanced commonsense knowledge, demonstrating its potential to benefit NLP applications across the board and contribute to making NLP more inclusive.

{{</citation>}}


### (41/208) EpiK-Eval: Evaluation for Language Models as Epistemic Models (Gabriele Prato et al., 2023)

{{<citation>}}

Gabriele Prato, Jerry Huang, Prasannna Parthasarathi, Shagun Sodhani, Sarath Chandar. (2023)  
**EpiK-Eval: Evaluation for Language Models as Epistemic Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.15372v1)  

---


**ABSTRACT**  
In the age of artificial intelligence, the role of large language models (LLMs) is becoming increasingly central. Despite their growing prevalence, their capacity to consolidate knowledge from different training documents - a crucial ability in numerous applications - remains unexplored. This paper presents the first study examining the capability of LLMs to effectively combine such information within their parameter space. We introduce EpiK-Eval, a novel question-answering benchmark tailored to evaluate LLMs' proficiency in formulating a coherent and consistent knowledge representation from segmented narratives. Evaluations across various LLMs reveal significant weaknesses in this domain. We contend that these shortcomings stem from the intrinsic nature of prevailing training objectives. Consequently, we advocate for refining the approach towards knowledge consolidation, as it harbors the potential to dramatically improve their overall effectiveness and performance. The findings from this study offer insights for developing more robust and reliable LLMs. Our code and benchmark are available at https://github.com/chandar-lab/EpiK-Eval

{{</citation>}}


### (42/208) Why LLMs Hallucinate, and How to Get (Evidential) Closure: Perceptual, Intensional, and Extensional Learning for Faithful Natural Language Generation (Adam Bouyamourn, 2023)

{{<citation>}}

Adam Bouyamourn. (2023)  
**Why LLMs Hallucinate, and How to Get (Evidential) Closure: Perceptual, Intensional, and Extensional Learning for Faithful Natural Language Generation**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-AI, cs-CL, cs.CL  
Keywords: Natural Language Generation  
[Paper Link](http://arxiv.org/abs/2310.15355v1)  

---


**ABSTRACT**  
We show that LLMs hallucinate because their output is not constrained to be synonymous with claims for which they have evidence: a condition that we call evidential closure. Information about the truth or falsity of sentences is not statistically identified in the standard neural probabilistic language model setup, and so cannot be conditioned on to generate new strings. We then show how to constrain LLMs to produce output that does satisfy evidential closure. A multimodal LLM must learn about the external world (perceptual learning); it must learn a mapping from strings to states of the world (extensional learning); and, to achieve fluency when generalizing beyond a body of evidence, it must learn mappings from strings to their synonyms (intensional learning). The output of a unimodal LLM must be synonymous with strings in a validated evidence set. Finally, we present a heuristic procedure, Learn-Babble-Prune, that yields faithful output from an LLM by rejecting output that is not synonymous with claims for which the LLM has evidence.

{{</citation>}}


### (43/208) Specialist or Generalist? Instruction Tuning for Specific NLP Tasks (Chufan Shi et al., 2023)

{{<citation>}}

Chufan Shi, Yixuan Su, Cheng Yang, Yujiu Yang, Deng Cai. (2023)  
**Specialist or Generalist? Instruction Tuning for Specific NLP Tasks**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2310.15326v1)  

---


**ABSTRACT**  
The potential of large language models (LLMs) to simultaneously perform a wide range of natural language processing (NLP) tasks has been the subject of extensive research. Although instruction tuning has proven to be a data-efficient method for transforming LLMs into such generalist models, their performance still lags behind specialist models trained exclusively for specific tasks. In this paper, we investigate whether incorporating broad-coverage generalist instruction tuning can contribute to building a specialist model. We hypothesize that its efficacy depends on task specificity and skill requirements. Our experiments assess four target tasks with distinct coverage levels, revealing that integrating generalist instruction tuning consistently enhances model performance when the task coverage is broad. The effect is particularly pronounced when the amount of task-specific training data is limited. Further investigation into three target tasks focusing on different capabilities demonstrates that generalist instruction tuning improves understanding and reasoning abilities. However, for tasks requiring factual knowledge, generalist data containing hallucinatory information may negatively affect the model's performance. Overall, our work provides a systematic guide for developing specialist models with general instruction tuning. Our code and other related resources can be found at https://github.com/DavidFanzz/Generalist_or_Specialist.

{{</citation>}}


### (44/208) Hallucination Detection for Grounded Instruction Generation (Lingjun Zhao et al., 2023)

{{<citation>}}

Lingjun Zhao, Khanh Nguyen, Hal Daumé III. (2023)  
**Hallucination Detection for Grounded Instruction Generation**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: LSTM, Transformer  
[Paper Link](http://arxiv.org/abs/2310.15319v1)  

---


**ABSTRACT**  
We investigate the problem of generating instructions to guide humans to navigate in simulated residential environments. A major issue with current models is hallucination: they generate references to actions or objects that are inconsistent with what a human follower would perform or encounter along the described path. We develop a model that detects these hallucinated references by adopting a model pre-trained on a large corpus of image-text pairs, and fine-tuning it with a contrastive loss that separates correct instructions from instructions containing synthesized hallucinations. Our final model outperforms several baselines, including using word probability estimated by the instruction-generation model, and supervised models based on LSTM and Transformer.

{{</citation>}}


### (45/208) Exploring the Potential of Large Language Models in Generating Code-Tracing Questions for Introductory Programming Courses (Aysa Xuemo Fan et al., 2023)

{{<citation>}}

Aysa Xuemo Fan, Ranran Haoran Zhang, Luc Paquette, Rui Zhang. (2023)  
**Exploring the Potential of Large Language Models in Generating Code-Tracing Questions for Introductory Programming Courses**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CY, cs.CL  
Keywords: GPT, Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2310.15317v1)  

---


**ABSTRACT**  
In this paper, we explore the application of large language models (LLMs) for generating code-tracing questions in introductory programming courses. We designed targeted prompts for GPT4, guiding it to generate code-tracing questions based on code snippets and descriptions. We established a set of human evaluation metrics to assess the quality of questions produced by the model compared to those created by human experts. Our analysis provides insights into the capabilities and potential of LLMs in generating diverse code-tracing questions. Additionally, we present a unique dataset of human and LLM-generated tracing questions, serving as a valuable resource for both the education and NLP research communities. This work contributes to the ongoing dialogue on the potential uses of LLMs in educational settings.

{{</citation>}}


### (46/208) Probing Representations for Document-level Event Extraction (Barry Wang et al., 2023)

{{<citation>}}

Barry Wang, Xinya Du, Claire Cardie. (2023)  
**Probing Representations for Document-level Event Extraction**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Event Extraction, NLP  
[Paper Link](http://arxiv.org/abs/2310.15316v1)  

---


**ABSTRACT**  
The probing classifiers framework has been employed for interpreting deep neural network models for a variety of natural language processing (NLP) applications. Studies, however, have largely focused on sentencelevel NLP tasks. This work is the first to apply the probing paradigm to representations learned for document-level information extraction (IE). We designed eight embedding probes to analyze surface, semantic, and event-understanding capabilities relevant to document-level event extraction. We apply them to the representations acquired by learning models from three different LLM-based document-level IE approaches on a standard dataset. We found that trained encoders from these models yield embeddings that can modestly improve argument detections and labeling but only slightly enhance event-level tasks, albeit trade-offs in information helpful for coherence and event-type prediction. We further found that encoder models struggle with document length and cross-sentence discourse.

{{</citation>}}


### (47/208) Toward a Critical Toponymy Framework for Named Entity Recognition: A Case Study of Airbnb in New York City (Mikael Brunila et al., 2023)

{{<citation>}}

Mikael Brunila, Jack LaViolette, Sky CH-Wang, Priyanka Verma, Clara Féré, Grant McKenzie. (2023)  
**Toward a Critical Toponymy Framework for Named Entity Recognition: A Case Study of Airbnb in New York City**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-CY, cs.CL  
Keywords: NER, Named Entity Recognition  
[Paper Link](http://arxiv.org/abs/2310.15302v1)  

---


**ABSTRACT**  
Critical toponymy examines the dynamics of power, capital, and resistance through place names and the sites to which they refer. Studies here have traditionally focused on the semantic content of toponyms and the top-down institutional processes that produce them. However, they have generally ignored the ways in which toponyms are used by ordinary people in everyday discourse, as well as the other strategies of geospatial description that accompany and contextualize toponymic reference. Here, we develop computational methods to measure how cultural and economic capital shape the ways in which people refer to places, through a novel annotated dataset of 47,440 New York City Airbnb listings from the 2010s. Building on this dataset, we introduce a new named entity recognition (NER) model able to identify important discourse categories integral to the characterization of place. Our findings point toward new directions for critical toponymy and to a range of previously understudied linguistic signals relevant to research on neighborhood status, housing and tourism markets, and gentrification.

{{</citation>}}


### (48/208) TaskDiff: A Similarity Metric for Task-Oriented Conversations (Ankita Bhaumik et al., 2023)

{{<citation>}}

Ankita Bhaumik, Praveen Venkateswaran, Yara Rizk, Vatche Isahagian. (2023)  
**TaskDiff: A Similarity Metric for Task-Oriented Conversations**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2310.15298v2)  

---


**ABSTRACT**  
The popularity of conversational digital assistants has resulted in the availability of large amounts of conversational data which can be utilized for improved user experience and personalized response generation. Building these assistants using popular large language models like ChatGPT also require additional emphasis on prompt engineering and evaluation methods. Textual similarity metrics are a key ingredient for such analysis and evaluations. While many similarity metrics have been proposed in the literature, they have not proven effective for task-oriented conversations as they do not take advantage of unique conversational features. To address this gap, we present TaskDiff, a novel conversational similarity metric that utilizes different dialogue components (utterances, intents, and slots) and their distributions to compute similarity. Extensive experimental evaluation of TaskDiff on a benchmark dataset demonstrates its superior performance and improved robustness over other related approaches.

{{</citation>}}


### (49/208) DeTiME: Diffusion-Enhanced Topic Modeling using Encoder-decoder based LLM (Weijie Xu et al., 2023)

{{<citation>}}

Weijie Xu, Wenxiang Hu, Fanyou Wu, Srinivasan Sengamedu. (2023)  
**DeTiME: Diffusion-Enhanced Topic Modeling using Encoder-decoder based LLM**  

---
Primary Category: cs.CL  
Categories: 68T50, I-2-7, cs-AI, cs-CL, cs.CL  
Keywords: Language Model, Topic Model, Topic Modeling  
[Paper Link](http://arxiv.org/abs/2310.15296v1)  

---


**ABSTRACT**  
In the burgeoning field of natural language processing, Neural Topic Models (NTMs) and Large Language Models (LLMs) have emerged as areas of significant research interest. Despite this, NTMs primarily utilize contextual embeddings from LLMs, which are not optimal for clustering or capable for topic generation. Our study addresses this gap by introducing a novel framework named Diffusion-Enhanced Topic Modeling using Encoder-Decoder-based LLMs (DeTiME). DeTiME leverages ncoder-Decoder-based LLMs to produce highly clusterable embeddings that could generate topics that exhibit both superior clusterability and enhanced semantic coherence compared to existing methods. Additionally, by exploiting the power of diffusion, our framework also provides the capability to generate content relevant to the identified topics. This dual functionality allows users to efficiently produce highly clustered topics and related content simultaneously. DeTiME's potential extends to generating clustered embeddings as well. Notably, our proposed framework proves to be efficient to train and exhibits high adaptability, demonstrating its potential for a wide array of applications.

{{</citation>}}


### (50/208) Adaptive End-to-End Metric Learning for Zero-Shot Cross-Domain Slot Filling (Yuanjun Shi et al., 2023)

{{<citation>}}

Yuanjun Shi, Linzhi Wu, Minglai Shao. (2023)  
**Adaptive End-to-End Metric Learning for Zero-Shot Cross-Domain Slot Filling**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2310.15294v1)  

---


**ABSTRACT**  
Recently slot filling has witnessed great development thanks to deep learning and the availability of large-scale annotated data. However, it poses a critical challenge to handle a novel domain whose samples are never seen during training. The recognition performance might be greatly degraded due to severe domain shifts. Most prior works deal with this problem in a two-pass pipeline manner based on metric learning. In practice, these dominant pipeline models may be limited in computational efficiency and generalization capacity because of non-parallel inference and context-free discrete label embeddings. To this end, we re-examine the typical metric-based methods, and propose a new adaptive end-to-end metric learning scheme for the challenging zero-shot slot filling. Considering simplicity, efficiency and generalizability, we present a cascade-style joint learning framework coupled with context-aware soft label representations and slot-level contrastive representation learning to mitigate the data and label shift problems effectively. Extensive experiments on public benchmarks demonstrate the superiority of the proposed approach over a series of competitive baselines.

{{</citation>}}


### (51/208) On the Dimensionality of Sentence Embeddings (Hongwei Wang et al., 2023)

{{<citation>}}

Hongwei Wang, Hongming Zhang, Dong Yu. (2023)  
**On the Dimensionality of Sentence Embeddings**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Embedding, Sentence Embedding  
[Paper Link](http://arxiv.org/abs/2310.15285v1)  

---


**ABSTRACT**  
Learning sentence embeddings is a fundamental problem in natural language processing. While existing research primarily focuses on enhancing the quality of sentence embeddings, the exploration of sentence embedding dimensions is limited. Here we present a comprehensive and empirical analysis of the dimensionality of sentence embeddings. First, we demonstrate that the optimal dimension of sentence embeddings is usually smaller than the default value. Subsequently, to compress the dimension of sentence embeddings with minimum performance degradation, we identify two components contributing to the overall performance loss: the encoder's performance loss and the pooler's performance loss. Therefore, we propose a two-step training method for sentence representation learning models, wherein the encoder and the pooler are optimized separately to mitigate the overall performance loss in low-dimension scenarios. Experimental results on seven STS tasks and seven sentence classification tasks demonstrate that our method significantly improves the performance of low-dimensional sentence embeddings.

{{</citation>}}


### (52/208) Towards Possibilities & Impossibilities of AI-generated Text Detection: A Survey (Soumya Suvra Ghosal et al., 2023)

{{<citation>}}

Soumya Suvra Ghosal, Souradip Chakraborty, Jonas Geiping, Furong Huang, Dinesh Manocha, Amrit Singh Bedi. (2023)  
**Towards Possibilities & Impossibilities of AI-generated Text Detection: A Survey**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2310.15264v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have revolutionized the domain of natural language processing (NLP) with remarkable capabilities of generating human-like text responses. However, despite these advancements, several works in the existing literature have raised serious concerns about the potential misuse of LLMs such as spreading misinformation, generating fake news, plagiarism in academia, and contaminating the web. To address these concerns, a consensus among the research community is to develop algorithmic solutions to detect AI-generated text. The basic idea is that whenever we can tell if the given text is either written by a human or an AI, we can utilize this information to address the above-mentioned concerns. To that end, a plethora of detection frameworks have been proposed, highlighting the possibilities of AI-generated text detection. But in parallel to the development of detection frameworks, researchers have also concentrated on designing strategies to elude detection, i.e., focusing on the impossibilities of AI-generated text detection. This is a crucial step in order to make sure the detection frameworks are robust enough and it is not too easy to fool a detector. Despite the huge interest and the flurry of research in this domain, the community currently lacks a comprehensive analysis of recent developments. In this survey, we aim to provide a concise categorization and overview of current work encompassing both the prospects and the limitations of AI-generated text detection. To enrich the collective knowledge, we engage in an exhaustive discussion on critical and challenging open questions related to ongoing research on AI-generated text detection.

{{</citation>}}


### (53/208) Data Augmentation Techniques for Machine Translation of Code-Switched Texts: A Comparative Study (Injy Hamed et al., 2023)

{{<citation>}}

Injy Hamed, Nizar Habash, Ngoc Thang Vu. (2023)  
**Data Augmentation Techniques for Machine Translation of Code-Switched Texts: A Comparative Study**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Augmentation, Machine Translation  
[Paper Link](http://arxiv.org/abs/2310.15262v1)  

---


**ABSTRACT**  
Code-switching (CSW) text generation has been receiving increasing attention as a solution to address data scarcity. In light of this growing interest, we need more comprehensive studies comparing different augmentation approaches. In this work, we compare three popular approaches: lexical replacements, linguistic theories, and back-translation (BT), in the context of Egyptian Arabic-English CSW. We assess the effectiveness of the approaches on machine translation and the quality of augmentations through human evaluation. We show that BT and CSW predictive-based lexical replacement, being trained on CSW parallel data, perform best on both tasks. Linguistic theories and random lexical replacement prove to be effective in the lack of CSW parallel data, where both approaches achieve similar results.

{{</citation>}}


### (54/208) Reference Free Domain Adaptation for Translation of Noisy Questions with Question Specific Rewards (Baban Gain et al., 2023)

{{<citation>}}

Baban Gain, Ramakrishna Appicharla, Soumya Chennabasavaraj, Nikesh Garera, Asif Ekbal, Muthusamy Chelliah. (2023)  
**Reference Free Domain Adaptation for Translation of Noisy Questions with Question Specific Rewards**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: BERT, BLEU, Language Model, Machine Translation, QA  
[Paper Link](http://arxiv.org/abs/2310.15259v1)  

---


**ABSTRACT**  
Community Question-Answering (CQA) portals serve as a valuable tool for helping users within an organization. However, making them accessible to non-English-speaking users continues to be a challenge. Translating questions can broaden the community's reach, benefiting individuals with similar inquiries in various languages. Translating questions using Neural Machine Translation (NMT) poses more challenges, especially in noisy environments, where the grammatical correctness of the questions is not monitored. These questions may be phrased as statements by non-native speakers, with incorrect subject-verb order and sometimes even missing question marks. Creating a synthetic parallel corpus from such data is also difficult due to its noisy nature. To address this issue, we propose a training methodology that fine-tunes the NMT system only using source-side data. Our approach balances adequacy and fluency by utilizing a loss function that combines BERTScore and Masked Language Model (MLM) Score. Our method surpasses the conventional Maximum Likelihood Estimation (MLE) based fine-tuning approach, which relies on synthetic target data, by achieving a 1.9 BLEU score improvement. Our model exhibits robustness while we add noise to our baseline, and still achieve 1.1 BLEU improvement and large improvements on TER and BLEURT metrics. Our proposed methodology is model-agnostic and is only necessary during the training phase. We make the codes and datasets publicly available at \url{https://www.iitp.ac.in/~ai-nlp-ml/resources.html#DomainAdapt} for facilitating further research.

{{</citation>}}


### (55/208) Breaking the Language Barrier: Improving Cross-Lingual Reasoning with Structured Self-Attention (Negar Foroutan et al., 2023)

{{<citation>}}

Negar Foroutan, Mohammadreza Banaei, Karl Aberer, Antoine Bosselut. (2023)  
**Breaking the Language Barrier: Improving Cross-Lingual Reasoning with Structured Self-Attention**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Attention, Reasoning, Self-Attention  
[Paper Link](http://arxiv.org/abs/2310.15258v1)  

---


**ABSTRACT**  
In this work, we study whether multilingual language models (MultiLMs) can transfer logical reasoning abilities to other languages when they are fine-tuned for reasoning in a different language. We evaluate the cross-lingual reasoning abilities of MultiLMs in two schemes: (1) where the language of the context and the question remain the same in the new languages that are tested (i.e., the reasoning is still monolingual, but the model must transfer the learned reasoning ability across languages), and (2) where the language of the context and the question is different (which we term code-switched reasoning). On two logical reasoning datasets, RuleTaker and LeapOfThought, we demonstrate that although MultiLMs can transfer reasoning ability across languages in a monolingual setting, they struggle to transfer reasoning abilities in a code-switched setting. Following this observation, we propose a novel attention mechanism that uses a dedicated set of parameters to encourage cross-lingual attention in code-switched sequences, which improves the reasoning performance by up to 14% and 4% on the RuleTaker and LeapOfThought datasets, respectively.

{{</citation>}}


### (56/208) CRoW: Benchmarking Commonsense Reasoning in Real-World Tasks (Mete Ismayilzada et al., 2023)

{{<citation>}}

Mete Ismayilzada, Debjit Paul, Syrielle Montariol, Mor Geva, Antoine Bosselut. (2023)  
**CRoW: Benchmarking Commonsense Reasoning in Real-World Tasks**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: NLP, Reasoning  
[Paper Link](http://arxiv.org/abs/2310.15239v1)  

---


**ABSTRACT**  
Recent efforts in natural language processing (NLP) commonsense reasoning research have yielded a considerable number of new datasets and benchmarks. However, most of these datasets formulate commonsense reasoning challenges in artificial scenarios that are not reflective of the tasks which real-world NLP systems are designed to solve. In this work, we present CRoW, a manually-curated, multi-task benchmark that evaluates the ability of models to apply commonsense reasoning in the context of six real-world NLP tasks. CRoW is constructed using a multi-stage data collection pipeline that rewrites examples from existing datasets using commonsense-violating perturbations. We use CRoW to study how NLP systems perform across different dimensions of commonsense knowledge, such as physical, temporal, and social reasoning. We find a significant performance gap when NLP systems are evaluated on CRoW compared to humans, showcasing that commonsense reasoning is far from being solved in real-world task settings. We make our dataset and leaderboard available to the research community at https://github.com/mismayil/crow.

{{</citation>}}


### (57/208) LINC: A Neurosymbolic Approach for Logical Reasoning by Combining Language Models with First-Order Logic Provers (Theo X. Olausson et al., 2023)

{{<citation>}}

Theo X. Olausson, Alex Gu, Benjamin Lipkin, Cedegao E. Zhang, Armando Solar-Lezama, Joshua B. Tenenbaum, Roger Levy. (2023)  
**LINC: A Neurosymbolic Approach for Logical Reasoning by Combining Language Models with First-Order Logic Provers**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT, GPT-3.5, GPT-4, Language Model, Reasoning  
[Paper Link](http://arxiv.org/abs/2310.15164v1)  

---


**ABSTRACT**  
Logical reasoning, i.e., deductively inferring the truth value of a conclusion from a set of premises, is an important task for artificial intelligence with wide potential impacts on science, mathematics, and society. While many prompting-based strategies have been proposed to enable Large Language Models (LLMs) to do such reasoning more effectively, they still appear unsatisfactory, often failing in subtle and unpredictable ways. In this work, we investigate the validity of instead reformulating such tasks as modular neurosymbolic programming, which we call LINC: Logical Inference via Neurosymbolic Computation. In LINC, the LLM acts as a semantic parser, translating premises and conclusions from natural language to expressions in first-order logic. These expressions are then offloaded to an external theorem prover, which symbolically performs deductive inference. Leveraging this approach, we observe significant performance gains on FOLIO and a balanced subset of ProofWriter for three different models in nearly all experimental conditions we evaluate. On ProofWriter, augmenting the comparatively small open-source StarCoder+ (15.5B parameters) with LINC even outperforms GPT-3.5 and GPT-4 with Chain-of-Thought (CoT) prompting by an absolute 38% and 10%, respectively. When used with GPT-4, LINC scores 26% higher than CoT on ProofWriter while performing comparatively on FOLIO. Further analysis reveals that although both methods on average succeed roughly equally often on this dataset, they exhibit distinct and complementary failure modes. We thus provide promising evidence for how logical reasoning over natural language can be tackled through jointly leveraging LLMs alongside symbolic provers. All corresponding code is publicly available at https://github.com/benlipkin/linc

{{</citation>}}


### (58/208) Function Vectors in Large Language Models (Eric Todd et al., 2023)

{{<citation>}}

Eric Todd, Millicent L. Li, Arnab Sen Sharma, Aaron Mueller, Byron C. Wallace, David Bau. (2023)  
**Function Vectors in Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.15213v1)  

---


**ABSTRACT**  
We report the presence of a simple neural mechanism that represents an input-output function as a vector within autoregressive transformer language models (LMs). Using causal mediation analysis on a diverse range of in-context-learning (ICL) tasks, we find that a small number attention heads transport a compact representation of the demonstrated task, which we call a function vector (FV). FVs are robust to changes in context, i.e., they trigger execution of the task on inputs such as zero-shot and natural text settings that do not resemble the ICL contexts from which they are collected. We test FVs across a range of tasks, models, and layers and find strong causal effects across settings in middle layers. We investigate the internal structure of FVs and find while that they often contain information that encodes the output space of the function, this information alone is not sufficient to reconstruct an FV. Finally, we test semantic vector composition in FVs, and find that to some extent they can be summed to create vectors that trigger new complex tasks. Taken together, our findings suggest that LLMs contain internal abstractions of general-purpose functions that can be invoked in a variety of contexts.

{{</citation>}}


### (59/208) Verb Conjugation in Transformers Is Determined by Linear Encodings of Subject Number (Sophie Hao et al., 2023)

{{<citation>}}

Sophie Hao, Tal Linzen. (2023)  
**Verb Conjugation in Transformers Is Determined by Linear Encodings of Subject Number**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: BERT, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2310.15151v1)  

---


**ABSTRACT**  
Deep architectures such as Transformers are sometimes criticized for having uninterpretable "black-box" representations. We use causal intervention analysis to show that, in fact, some linguistic features are represented in a linear, interpretable format. Specifically, we show that BERT's ability to conjugate verbs relies on a linear encoding of subject number that can be manipulated with predictable effects on conjugation accuracy. This encoding is found in the subject position at the first layer and the verb position at the last layer, but distributed across positions at middle layers, particularly when there are multiple cues to subject number.

{{</citation>}}


### (60/208) S3Eval: A Synthetic, Scalable, Systematic Evaluation Suite for Large Language Models (Fangyu Lei et al., 2023)

{{<citation>}}

Fangyu Lei, Qian Liu, Yiming Huang, Shizhu He, Jun Zhao, Kang Liu. (2023)  
**S3Eval: A Synthetic, Scalable, Systematic Evaluation Suite for Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.15147v1)  

---


**ABSTRACT**  
The rapid development of Large Language Models (LLMs) has led to great strides in model capabilities like reasoning and long-context understanding. However, as LLMs are able to process longer contexts, it becomes more challenging to evaluate whether they have acquired certain capabilities, since the length of text (e.g., 100K tokens) they can process far exceeds what humans can reliably assess in a reasonable duration. In this paper, we propose using complex synthetic tasks as a proxy evaluation method, and present S3Eval, a Synthetic, Scalable, Systematic evaluation suite for LLMs evaluation. As a synthetic benchmark, S3Eval enables the creation of any number of evaluation examples that are theoretically invisible to LLMs, mitigating the test set contamination issue. The synthetic nature of S3Eval provides users full control over the dataset, allowing them to systematically probe LLM capabilities by scaling text length and varying task difficulty across diverse scenarios. The strong correlation between S3Eval performance and scores of real-world benchmarks like Big-Bench Hard (BBH) demonstrates the soundness of using S3Eval for evaluation of LLMs. The in-depth analysis also uncover additional insights, including performance drop when the answer is sparsely distributed or located in the middle context, as well as some counter-intuitive trends of model performance.

{{</citation>}}


### (61/208) Quantifying the Dialect Gap and its Correlates Across Languages (Anjali Kantharuban et al., 2023)

{{<citation>}}

Anjali Kantharuban, Ivan Vulić, Anna Korhonen. (2023)  
**Quantifying the Dialect Gap and its Correlates Across Languages**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2310.15135v1)  

---


**ABSTRACT**  
Historically, researchers and consumers have noticed a decrease in quality when applying NLP tools to minority variants of languages (i.e. Puerto Rican Spanish or Swiss German), but studies exploring this have been limited to a select few languages. Additionally, past studies have mainly been conducted in a monolingual context, so cross-linguistic trends have not been identified and tied to external factors. In this work, we conduct a comprehensive evaluation of the most influential, state-of-the-art large language models (LLMs) across two high-use applications, machine translation and automatic speech recognition, to assess their functionality on the regional dialects of several high- and low-resource languages. Additionally, we analyze how the regional dialect gap is correlated with economic, social, and linguistic factors. The impact of training data, including related factors like dataset size and its construction procedure, is shown to be significant but not consistent across models or languages, meaning a one-size-fits-all approach cannot be taken in solving the dialect gap. This work will lay the foundation for furthering the field of dialectal NLP by laying out evident disparities and identifying possible pathways for addressing them through mindful data collection.

{{</citation>}}


### (62/208) Location-Aware Visual Question Generation with Lightweight Models (Nicholas Collin Suwono et al., 2023)

{{<citation>}}

Nicholas Collin Suwono, Justin Chih-Yao Chen, Tun Min Hung, Ting-Hao Kenneth Huang, I-Bin Liao, Yung-Hui Li, Lun-Wei Ku, Shao-Hua Sun. (2023)  
**Location-Aware Visual Question Generation with Lightweight Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: BERT, GPT, GPT-4, Question Generation  
[Paper Link](http://arxiv.org/abs/2310.15129v1)  

---


**ABSTRACT**  
This work introduces a novel task, location-aware visual question generation (LocaVQG), which aims to generate engaging questions from data relevant to a particular geographical location. Specifically, we represent such location-aware information with surrounding images and a GPS coordinate. To tackle this task, we present a dataset generation pipeline that leverages GPT-4 to produce diverse and sophisticated questions. Then, we aim to learn a lightweight model that can address the LocaVQG task and fit on an edge device, such as a mobile phone. To this end, we propose a method which can reliably generate engaging questions from location-aware information. Our proposed method outperforms baselines regarding human evaluation (e.g., engagement, grounding, coherence) and automatic evaluation metrics (e.g., BERTScore, ROUGE-2). Moreover, we conduct extensive ablation studies to justify our proposed techniques for both generating the dataset and solving the task.

{{</citation>}}


### (63/208) Branch-Solve-Merge Improves Large Language Model Evaluation and Generation (Swarnadeep Saha et al., 2023)

{{<citation>}}

Swarnadeep Saha, Omer Levy, Asli Celikyilmaz, Mohit Bansal, Jason Weston, Xian Li. (2023)  
**Branch-Solve-Merge Improves Large Language Model Evaluation and Generation**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: GPT, GPT-4, LLaMA, Language Model  
[Paper Link](http://arxiv.org/abs/2310.15123v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) are frequently used for multi-faceted language generation and evaluation tasks that involve satisfying intricate user constraints or taking into account multiple aspects and criteria. However, their performance can fall short, due to the model's lack of coherence and inability to plan and decompose the problem. We propose Branch-Solve-Merge (BSM), a Large Language Model program (Schlag et al., 2023) for tackling such challenging natural language tasks. It consists of branch, solve, and merge modules that are parameterized with specific prompts to the base LLM. These three modules plan a decomposition of the task into multiple parallel sub-tasks, independently solve them, and fuse the solutions to the sub-tasks. We apply our method to the tasks of LLM response evaluation and constrained text generation and evaluate its effectiveness with multiple LLMs, including Vicuna, LLaMA-2-chat, and GPT-4. BSM improves the evaluation correctness and consistency for each LLM by enhancing human-LLM agreement by up to 26%, reducing length and pairwise position biases by up to 50%, and allowing LLaMA-2-chat to match or outperform GPT-4 on most domains. On the constraint story generation task, BSM improves the coherence of the stories while also improving constraint satisfaction by 12%.

{{</citation>}}


### (64/208) Counting the Bugs in ChatGPT's Wugs: A Multilingual Investigation into the Morphological Capabilities of a Large Language Model (Leonie Weissweiler et al., 2023)

{{<citation>}}

Leonie Weissweiler, Valentin Hofmann, Anjali Kantharuban, Anna Cai, Ritam Dutt, Amey Hengle, Anubha Kabra, Atharva Kulkarni, Abhishek Vijayakumar, Haofei Yu, Hinrich Schütze, Kemal Oflazer, David R. Mortensen. (2023)  
**Counting the Bugs in ChatGPT's Wugs: A Multilingual Investigation into the Morphological Capabilities of a Large Language Model**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT, Language Model, Multilingual  
[Paper Link](http://arxiv.org/abs/2310.15113v2)  

---


**ABSTRACT**  
Large language models (LLMs) have recently reached an impressive level of linguistic capability, prompting comparisons with human language skills. However, there have been relatively few systematic inquiries into the linguistic capabilities of the latest generation of LLMs, and those studies that do exist (i) ignore the remarkable ability of humans to generalize, (ii) focus only on English, and (iii) investigate syntax or semantics and overlook other capabilities that lie at the heart of human language, like morphology. Here, we close these gaps by conducting the first rigorous analysis of the morphological capabilities of ChatGPT in four typologically varied languages (specifically, English, German, Tamil, and Turkish). We apply a version of Berko's (1958) wug test to ChatGPT, using novel, uncontaminated datasets for the four examined languages. We find that ChatGPT massively underperforms purpose-built systems, particularly in English. Overall, our results -- through the lens of morphology -- cast a new light on the linguistic capabilities of ChatGPT, suggesting that claims of human-like language skills are premature and misleading.

{{</citation>}}


### (65/208) GRENADE: Graph-Centric Language Model for Self-Supervised Representation Learning on Text-Attributed Graphs (Yichuan Li et al., 2023)

{{<citation>}}

Yichuan Li, Kaize Ding, Kyumin Lee. (2023)  
**GRENADE: Graph-Centric Language Model for Self-Supervised Representation Learning on Text-Attributed Graphs**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, Representation Learning, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2310.15109v1)  

---


**ABSTRACT**  
Self-supervised representation learning on text-attributed graphs, which aims to create expressive and generalizable representations for various downstream tasks, has received increasing research attention lately. However, existing methods either struggle to capture the full extent of structural context information or rely on task-specific training labels, which largely hampers their effectiveness and generalizability in practice. To solve the problem of self-supervised representation learning on text-attributed graphs, we develop a novel Graph-Centric Language model -- GRENADE. Specifically, GRENADE exploits the synergistic effect of both pre-trained language model and graph neural network by optimizing with two specialized self-supervised learning algorithms: graph-centric contrastive learning and graph-centric knowledge alignment. The proposed graph-centric self-supervised learning algorithms effectively help GRENADE to capture informative textual semantics as well as structural context information on text-attributed graphs. Through extensive experiments, GRENADE shows its superiority over state-of-the-art methods. Implementation is available at \url{https://github.com/bigheiniu/GRENADE}.

{{</citation>}}


### (66/208) LLM-in-the-loop: Leveraging Large Language Model for Thematic Analysis (Shih-Chieh Dai et al., 2023)

{{<citation>}}

Shih-Chieh Dai, Aiping Xiong, Lun-Wei Ku. (2023)  
**LLM-in-the-loop: Leveraging Large Language Model for Thematic Analysis**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, GPT-3.5, Language Model  
[Paper Link](http://arxiv.org/abs/2310.15100v1)  

---


**ABSTRACT**  
Thematic analysis (TA) has been widely used for analyzing qualitative data in many disciplines and fields. To ensure reliable analysis, the same piece of data is typically assigned to at least two human coders. Moreover, to produce meaningful and useful analysis, human coders develop and deepen their data interpretation and coding over multiple iterations, making TA labor-intensive and time-consuming. Recently the emerging field of large language models (LLMs) research has shown that LLMs have the potential replicate human-like behavior in various tasks: in particular, LLMs outperform crowd workers on text-annotation tasks, suggesting an opportunity to leverage LLMs on TA. We propose a human-LLM collaboration framework (i.e., LLM-in-the-loop) to conduct TA with in-context learning (ICL). This framework provides the prompt to frame discussions with a LLM (e.g., GPT-3.5) to generate the final codebook for TA. We demonstrate the utility of this framework using survey datasets on the aspects of the music listening experience and the usage of a password manager. Results of the two case studies show that the proposed framework yields similar coding quality to that of human coders but reduces TA's labor and time demands.

{{</citation>}}


### (67/208) 'Don't Get Too Technical with Me': A Discourse Structure-Based Framework for Science Journalism (Ronald Cardenas et al., 2023)

{{<citation>}}

Ronald Cardenas, Bingsheng Yao, Dakuo Wang, Yufang Hou. (2023)  
**'Don't Get Too Technical with Me': A Discourse Structure-Based Framework for Science Journalism**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2310.15077v1)  

---


**ABSTRACT**  
Science journalism refers to the task of reporting technical findings of a scientific paper as a less technical news article to the general public audience. We aim to design an automated system to support this real-world task (i.e., automatic science journalism) by 1) introducing a newly-constructed and real-world dataset (SciTechNews), with tuples of a publicly-available scientific paper, its corresponding news article, and an expert-written short summary snippet; 2) proposing a novel technical framework that integrates a paper's discourse structure with its metadata to guide generation; and, 3) demonstrating with extensive automatic and human experiments that our framework outperforms other baseline methods (e.g. Alpaca and ChatGPT) in elaborating a content plan meaningful for the target audience, simplifying the information selected, and producing a coherent final report in a layman's style.

{{</citation>}}


### (68/208) TableQAKit: A Comprehensive and Practical Toolkit for Table-based Question Answering (Fangyu Lei et al., 2023)

{{<citation>}}

Fangyu Lei, Tongxu Luo, Pengqi Yang, Weihao Liu, Hanwen Liu, Jiahe Lei, Yiming Huang, Yifan Wei, Shizhu He, Jun Zhao, Kang Liu. (2023)  
**TableQAKit: A Comprehensive and Practical Toolkit for Table-based Question Answering**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2310.15075v1)  

---


**ABSTRACT**  
Table-based question answering (TableQA) is an important task in natural language processing, which requires comprehending tables and employing various reasoning ways to answer the questions. This paper introduces TableQAKit, the first comprehensive toolkit designed specifically for TableQA. The toolkit designs a unified platform that includes plentiful TableQA datasets and integrates popular methods of this task as well as large language models (LLMs). Users can add their datasets and methods according to the friendly interface. Also, pleasantly surprised using the modules in this toolkit achieves new SOTA on some datasets. Finally, \tableqakit{} also provides an LLM-based TableQA Benchmark for evaluating the role of LLMs in TableQA. TableQAKit is open-source with an interactive interface that includes visual operations, and comprehensive data for ease of use.

{{</citation>}}


### (69/208) The BLA Benchmark: Investigating Basic Language Abilities of Pre-Trained Multimodal Models (Xinyi Chen et al., 2023)

{{<citation>}}

Xinyi Chen, Raquel Fernández, Sandro Pezzelle. (2023)  
**The BLA Benchmark: Investigating Basic Language Abilities of Pre-Trained Multimodal Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-CV, cs.CL  
Keywords: BERT, Transformer  
[Paper Link](http://arxiv.org/abs/2310.15061v1)  

---


**ABSTRACT**  
Despite the impressive performance achieved by pre-trained language-and-vision models in downstream tasks, it remains an open question whether this reflects a proper understanding of image-text interaction. In this work, we explore to what extent they handle basic linguistic constructions -- active-passive voice, coordination, and relative clauses -- that even preschool children can typically master. We present BLA, a novel, automatically constructed benchmark to evaluate multimodal models on these Basic Language Abilities. We show that different types of Transformer-based systems, such as CLIP, ViLBERT, and BLIP2, generally struggle with BLA in a zero-shot setting, in line with previous findings. Our experiments, in particular, show that most of the tested models only marginally benefit when fine-tuned or prompted with construction-specific samples. Yet, the generative BLIP2 shows promising trends, especially in an in-context learning setting. This opens the door to using BLA not only as an evaluation benchmark but also to improve models' basic language abilities.

{{</citation>}}


### (70/208) Towards Conceptualization of 'Fair Explanation': Disparate Impacts of anti-Asian Hate Speech Explanations on Content Moderators (Tin Nguyen et al., 2023)

{{<citation>}}

Tin Nguyen, Jiannan Xu, Aayushi Roy, Hal Daumé III, Marine Carpuat. (2023)  
**Towards Conceptualization of 'Fair Explanation': Disparate Impacts of anti-Asian Hate Speech Explanations on Content Moderators**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-HC, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15055v1)  

---


**ABSTRACT**  
Recent research at the intersection of AI explainability and fairness has focused on how explanations can improve human-plus-AI task performance as assessed by fairness measures. We propose to characterize what constitutes an explanation that is itself "fair" -- an explanation that does not adversely impact specific populations. We formulate a novel evaluation method of "fair explanations" using not just accuracy and label time, but also psychological impact of explanations on different user groups across many metrics (mental discomfort, stereotype activation, and perceived workload). We apply this method in the context of content moderation of potential hate speech, and its differential impact on Asian vs. non-Asian proxy moderators, across explanation approaches (saliency map and counterfactual explanation). We find that saliency maps generally perform better and show less evidence of disparate impact (group) and individual unfairness than counterfactual explanations.   Content warning: This paper contains examples of hate speech and racially discriminatory language. The authors do not support such content. Please consider your risk of discomfort carefully before continuing reading!

{{</citation>}}


### (71/208) SLOG: A Structural Generalization Benchmark for Semantic Parsing (Bingzhi Li et al., 2023)

{{<citation>}}

Bingzhi Li, Lucia Donatelli, Alexander Koller, Tal Linzen, Yuekun Yao, Najoung Kim. (2023)  
**SLOG: A Structural Generalization Benchmark for Semantic Parsing**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2310.15040v1)  

---


**ABSTRACT**  
The goal of compositional generalization benchmarks is to evaluate how well models generalize to new complex linguistic expressions. Existing benchmarks often focus on lexical generalization, the interpretation of novel lexical items in syntactic structures familiar from training; structural generalization tasks, where a model needs to interpret syntactic structures that are themselves unfamiliar from training, are often underrepresented, resulting in overly optimistic perceptions of how well models can generalize. We introduce SLOG, a semantic parsing dataset that extends COGS (Kim and Linzen, 2020) with 17 structural generalization cases. In our experiments, the generalization accuracy of Transformer models, including pretrained ones, only reaches 40.6%, while a structure-aware parser only achieves 70.8%. These results are far from the near-perfect accuracy existing models achieve on COGS, demonstrating the role of SLOG in foregrounding the large discrepancy between models' lexical and structural generalization capacities.

{{</citation>}}


### (72/208) Efficient Data Learning for Open Information Extraction with Pre-trained Language Models (Zhiyuan Fan et al., 2023)

{{<citation>}}

Zhiyuan Fan, Shizhu He. (2023)  
**Efficient Data Learning for Open Information Extraction with Pre-trained Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Information Extraction, Language Model, Natural Language Processing, T5  
[Paper Link](http://arxiv.org/abs/2310.15021v1)  

---


**ABSTRACT**  
Open Information Extraction (OpenIE) is a fundamental yet challenging task in Natural Language Processing, which involves extracting all triples (subject, predicate, object) from a given sentence. While labeling-based methods have their merits, generation-based techniques offer unique advantages, such as the ability to generate tokens not present in the original sentence. However, these generation-based methods often require a significant amount of training data to learn the task form of OpenIE and substantial training time to overcome slow model convergence due to the order penalty. In this paper, we introduce a novel framework, OK-IE, that ingeniously transforms the task form of OpenIE into the pre-training task form of the T5 model, thereby reducing the need for extensive training data. Furthermore, we introduce an innovative concept of Anchor to control the sequence of model outputs, effectively eliminating the impact of order penalty on model convergence and significantly reducing training time. Experimental results indicate that, compared to previous SOTA methods, OK-IE requires only 1/100 of the training data (900 instances) and 1/120 of the training time (3 minutes) to achieve comparable results.

{{</citation>}}


### (73/208) Statistical Depth for Ranking and Characterizing Transformer-Based Text Embeddings (Parker Seegmiller et al., 2023)

{{<citation>}}

Parker Seegmiller, Sarah Masud Preum. (2023)  
**Statistical Depth for Ranking and Characterizing Transformer-Based Text Embeddings**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Embedding, NLP, Transformer  
[Paper Link](http://arxiv.org/abs/2310.15010v1)  

---


**ABSTRACT**  
The popularity of transformer-based text embeddings calls for better statistical tools for measuring distributions of such embeddings. One such tool would be a method for ranking texts within a corpus by centrality, i.e. assigning each text a number signifying how representative that text is of the corpus as a whole. However, an intrinsic center-outward ordering of high-dimensional text representations is not trivial. A statistical depth is a function for ranking k-dimensional objects by measuring centrality with respect to some observed k-dimensional distribution. We adopt a statistical depth to measure distributions of transformer-based text embeddings, transformer-based text embedding (TTE) depth, and introduce the practical use of this depth for both modeling and distributional inference in NLP pipelines. We first define TTE depth and an associated rank sum test for determining whether two corpora differ significantly in embedding space. We then use TTE depth for the task of in-context learning prompt selection, showing that this approach reliably improves performance over statistical baseline approaches across six text classification tasks. Finally, we use TTE depth and the associated rank sum test to characterize the distributions of synthesized and human-generated corpora, showing that five recent synthetic data augmentation processes cause a measurable distributional shift away from associated human-generated text.

{{</citation>}}


### (74/208) Did the Neurons Read your Book? Document-level Membership Inference for Large Language Models (Matthieu Meeus et al., 2023)

{{<citation>}}

Matthieu Meeus, Shubham Jain, Marek Rei, Yves-Alexandre de Montjoye. (2023)  
**Did the Neurons Read your Book? Document-level Membership Inference for Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CR, cs-LG, cs.CL  
Keywords: LLaMA, Language Model  
[Paper Link](http://arxiv.org/abs/2310.15007v1)  

---


**ABSTRACT**  
With large language models (LLMs) poised to become embedded in our daily lives, questions are starting to be raised about the dataset(s) they learned from. These questions range from potential bias or misinformation LLMs could retain from their training data to questions of copyright and fair use of human-generated text. However, while these questions emerge, developers of the recent state-of-the-art LLMs become increasingly reluctant to disclose details on their training corpus. We here introduce the task of document-level membership inference for real-world LLMs, i.e. inferring whether the LLM has seen a given document during training or not. First, we propose a procedure for the development and evaluation of document-level membership inference for LLMs by leveraging commonly used data sources for training and the model release date. We then propose a practical, black-box method to predict document-level membership and instantiate it on OpenLLaMA-7B with both books and academic papers. We show our methodology to perform very well, reaching an impressive AUC of 0.856 for books and 0.678 for papers. We then show our approach to outperform the sentence-level membership inference attacks used in the privacy literature for the document-level membership task. We finally evaluate whether smaller models might be less sensitive to document-level inference and show OpenLLaMA-3B to be approximately as sensitive as OpenLLaMA-7B to our approach. Taken together, our results show that accurate document-level membership can be inferred for LLMs, increasing the transparency of technology poised to change our lives.

{{</citation>}}


### (75/208) When Language Models Fall in Love: Animacy Processing in Transformer Language Models (Michael Hanna et al., 2023)

{{<citation>}}

Michael Hanna, Yonatan Belinkov, Sandro Pezzelle. (2023)  
**When Language Models Fall in Love: Animacy Processing in Transformer Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, Transformer  
[Paper Link](http://arxiv.org/abs/2310.15004v1)  

---


**ABSTRACT**  
Animacy - whether an entity is alive and sentient - is fundamental to cognitive processing, impacting areas such as memory, vision, and language. However, animacy is not always expressed directly in language: in English it often manifests indirectly, in the form of selectional constraints on verbs and adjectives. This poses a potential issue for transformer language models (LMs): they often train only on text, and thus lack access to extralinguistic information from which humans learn about animacy. We ask: how does this impact LMs' animacy processing - do they still behave as humans do? We answer this question using open-source LMs. Like previous studies, we find that LMs behave much like humans when presented with entities whose animacy is typical. However, we also show that even when presented with stories about atypically animate entities, such as a peanut in love, LMs adapt: they treat these entities as animate, though they do not adapt as well as humans. Even when the context indicating atypical animacy is very short, LMs pick up on subtle clues and change their behavior. We conclude that despite the limited signal through which LMs can learn about animacy, they are indeed sensitive to the relevant lexical semantic nuances available in English.

{{</citation>}}


### (76/208) Fidelity-Enriched Contrastive Search: Reconciling the Faithfulness-Diversity Trade-Off in Text Generation (Wei-Lin Chen et al., 2023)

{{<citation>}}

Wei-Lin Chen, Cheng-Kuang Wu, Hsin-Hsi Chen, Chung-Chi Chen. (2023)  
**Fidelity-Enriched Contrastive Search: Reconciling the Faithfulness-Diversity Trade-Off in Text Generation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Text Generation  
[Paper Link](http://arxiv.org/abs/2310.14981v1)  

---


**ABSTRACT**  
In this paper, we address the hallucination problem commonly found in natural language generation tasks. Language models often generate fluent and convincing content but can lack consistency with the provided source, resulting in potential inaccuracies. We propose a new decoding method called Fidelity-Enriched Contrastive Search (FECS), which augments the contrastive search framework with context-aware regularization terms. FECS promotes tokens that are semantically similar to the provided source while penalizing repetitiveness in the generated text. We demonstrate its effectiveness across two tasks prone to hallucination: abstractive summarization and dialogue generation. Results show that FECS consistently enhances faithfulness across various language model sizes while maintaining output diversity comparable to well-performing decoding algorithms.

{{</citation>}}


### (77/208) ACTOR: Active Learning with Annotator-specific Classification Heads to Embrace Human Label Variation (Xinpeng Wang et al., 2023)

{{<citation>}}

Xinpeng Wang, Barbara Plank. (2023)  
**ACTOR: Active Learning with Annotator-specific Classification Heads to Embrace Human Label Variation**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: Active Learning  
[Paper Link](http://arxiv.org/abs/2310.14979v1)  

---


**ABSTRACT**  
Label aggregation such as majority voting is commonly used to resolve annotator disagreement in dataset creation. However, this may disregard minority values and opinions. Recent studies indicate that learning from individual annotations outperforms learning from aggregated labels, though they require a considerable amount of annotation. Active learning, as an annotation cost-saving strategy, has not been fully explored in the context of learning from disagreement. We show that in the active learning setting, a multi-head model performs significantly better than a single-head model in terms of uncertainty estimation. By designing and evaluating acquisition functions with annotator-specific heads on two datasets, we show that group-level entropy works generally well on both datasets. Importantly, it achieves performance in terms of both prediction and uncertainty estimation comparable to full-scale training from disagreement, while saving up to 70% of the annotation budget.

{{</citation>}}


### (78/208) Penalty Decoding: Well Suppress the Self-Reinforcement Effect in Open-Ended Text Generation (Wenhong Zhu et al., 2023)

{{<citation>}}

Wenhong Zhu, Hongkun Hao, Rui Wang. (2023)  
**Penalty Decoding: Well Suppress the Self-Reinforcement Effect in Open-Ended Text Generation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Text Generation  
[Paper Link](http://arxiv.org/abs/2310.14971v1)  

---


**ABSTRACT**  
The decoding algorithm is critical for open-ended text generation, transforming latent representations into coherent and meaningful outputs. This paper investigates the self-reinforcement effect in text generation and the effectiveness of a repetition penalty to mitigate it. However, determining the optimal repetition penalty value is challenging. To tackle this, we propose a forgetting mechanism that disregards distant tokens, reducing the burden of penalty selection. In addition, we introduce a length penalty to address overly short sentences caused by excessive penalties. Our penalty decoding approach incorporating three strategies helps resolve issues with sampling methods deviating from factual information. Experimental results demonstrate the efficacy of our approach in generating high-quality sentences resembling human output.

{{</citation>}}


### (79/208) Towards LLM-driven Dialogue State Tracking (Yujie Feng et al., 2023)

{{<citation>}}

Yujie Feng, Zexin Lu, Bo Liu, Liming Zhan, Xiao-Ming Wu. (2023)  
**Towards LLM-driven Dialogue State Tracking**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, Dialog, Dialogue, GPT  
[Paper Link](http://arxiv.org/abs/2310.14970v1)  

---


**ABSTRACT**  
Dialogue State Tracking (DST) is of paramount importance in ensuring accurate tracking of user goals and system actions within task-oriented dialogue systems. The emergence of large language models (LLMs) such as GPT3 and ChatGPT has sparked considerable interest in assessing their efficacy across diverse applications. In this study, we conduct an initial examination of ChatGPT's capabilities in DST. Our evaluation uncovers the exceptional performance of ChatGPT in this task, offering valuable insights to researchers regarding its capabilities and providing useful directions for designing and enhancing dialogue systems. Despite its impressive performance, ChatGPT has significant limitations including its closed-source nature, request restrictions, raising data privacy concerns, and lacking local deployment capabilities. To address these concerns, we present LDST, an LLM-driven DST framework based on smaller, open-source foundation models. By utilizing a novel domain-slot instruction tuning method, LDST achieves performance on par with ChatGPT. Comprehensive evaluations across three distinct experimental settings, we find that LDST exhibits remarkable performance improvements in both zero-shot and few-shot setting compared to previous SOTA methods. The source code is provided for reproducibility.

{{</citation>}}


### (80/208) Unveiling A Core Linguistic Region in Large Language Models (Jun Zhao et al., 2023)

{{<citation>}}

Jun Zhao, Zhihao Zhang, Yide Ma, Qi Zhang, Tao Gui, Luhui Gao, Xuanjing Huang. (2023)  
**Unveiling A Core Linguistic Region in Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.14928v1)  

---


**ABSTRACT**  
Brain localization, which describes the association between specific regions of the brain and their corresponding functions, is widely accepted in the field of cognitive science as an objective fact. Today's large language models (LLMs) possess human-level linguistic competence and can execute complex tasks requiring abstract knowledge and reasoning. To deeply understand the inherent mechanisms of intelligence emergence in LLMs, this paper conducts an analogical research using brain localization as a prototype. We have discovered a core region in LLMs that corresponds to linguistic competence, accounting for approximately 1% of the total model parameters. This core region exhibits significant dimension dependency, and perturbations to even a single parameter on specific dimensions can lead to a loss of linguistic competence. Furthermore, we observe that an improvement in linguistic competence does not necessarily accompany an elevation in the model's knowledge level, which might imply the existence of regions of domain knowledge that are dissociated from the linguistic region. Overall, exploring the LLMs' functional regions provides insights into the foundation of their intelligence. In the future, we will continue to investigate knowledge regions within LLMs and the interactions between them.

{{</citation>}}


### (81/208) PartialFormer: Modeling Part Instead of Whole (Tong Zheng et al., 2023)

{{<citation>}}

Tong Zheng, Bei Li, Huiwen Bao, Weiqiao Shan, Tong Xiao, Jingbo Zhu. (2023)  
**PartialFormer: Modeling Part Instead of Whole**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2310.14921v1)  

---


**ABSTRACT**  
The design choices in Transformer feed-forward neural networks have resulted in significant computational and parameter overhead. In this work, we emphasize the importance of hidden dimension in designing lightweight FFNs, a factor often overlooked in previous architectures. Guided by this principle, we introduce PartialFormer, a parameter-efficient Transformer architecture utilizing multiple smaller FFNs to reduce parameters and computation while maintaining essential hidden dimensions. These smaller FFNs are integrated into a multi-head attention system to enable effective collaboration. We also propose a tailored head scaling strategy to enhance PartialFormer's capabilities. Furthermore, we present a residual-like attention calculation to improve depth scaling within PartialFormer. Extensive experiments on 9 translation tasks and 1 abstractive summarization task validate the effectiveness of our PartialFormer approach. Our code would be available at: \url{https://github.com/zhengkid/PartialFormer}.

{{</citation>}}


### (82/208) Linking Surface Facts to Large-Scale Knowledge Graphs (Gorjan Radevski et al., 2023)

{{<citation>}}

Gorjan Radevski, Kiril Gashteovski, Chia-Chien Hung, Carolin Lawrence, Goran Glavaš. (2023)  
**Linking Surface Facts to Large-Scale Knowledge Graphs**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: Information Extraction, Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2310.14909v1)  

---


**ABSTRACT**  
Open Information Extraction (OIE) methods extract facts from natural language text in the form of ("subject"; "relation"; "object") triples. These facts are, however, merely surface forms, the ambiguity of which impedes their downstream usage; e.g., the surface phrase "Michael Jordan" may refer to either the former basketball player or the university professor. Knowledge Graphs (KGs), on the other hand, contain facts in a canonical (i.e., unambiguous) form, but their coverage is limited by a static schema (i.e., a fixed set of entities and predicates). To bridge this gap, we need the best of both worlds: (i) high coverage of free-text OIEs, and (ii) semantic precision (i.e., monosemy) of KGs. In order to achieve this goal, we propose a new benchmark with novel evaluation protocols that can, for example, measure fact linking performance on a granular triple slot level, while also measuring if a system has the ability to recognize that a surface form has no match in the existing KG. Our extensive evaluation of several baselines show that detection of out-of-KG entities and predicates is more difficult than accurate linking to existing ones, thus calling for more research efforts on this difficult task. We publicly release all resources (data, benchmark and code) on https://github.com/nec-research/fact-linking.

{{</citation>}}


### (83/208) Air-Decoding: Attribute Distribution Reconstruction for Decoding-Time Controllable Text Generation (Tianqi Zhong et al., 2023)

{{<citation>}}

Tianqi Zhong, Quan Wang, Jingxuan Han, Yongdong Zhang, Zhendong Mao. (2023)  
**Air-Decoding: Attribute Distribution Reconstruction for Decoding-Time Controllable Text Generation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Text Generation  
[Paper Link](http://arxiv.org/abs/2310.14892v2)  

---


**ABSTRACT**  
Controllable text generation (CTG) aims to generate text with desired attributes, and decoding-time-based methods have shown promising performance on this task. However, in this paper, we identify the phenomenon of Attribute Collapse for the first time. It causes the fluency of generated text to rapidly decrease when the control strength exceeds a critical value, rendering the text completely unusable. This limitation hinders the effectiveness of decoding methods in achieving high levels of controllability. To address this problem, we propose a novel lightweight decoding framework named Air-Decoding. Its main idea is reconstructing the attribute distributions to balance the weights between attribute words and non-attribute words to generate more fluent text. Specifically, we train prefixes by prefix-tuning to obtain attribute distributions. Then we design a novel attribute distribution reconstruction method to balance the obtained distributions and use the reconstructed distributions to guide language models for generation, effectively avoiding the issue of Attribute Collapse. Experiments on multiple CTG tasks prove that our method achieves a new state-of-the-art control performance.

{{</citation>}}


### (84/208) Non-autoregressive Streaming Transformer for Simultaneous Translation (Zhengrui Ma et al., 2023)

{{<citation>}}

Zhengrui Ma, Shaolei Zhang, Shoutao Guo, Chenze Shao, Min Zhang, Yang Feng. (2023)  
**Non-autoregressive Streaming Transformer for Simultaneous Translation**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-AI, cs-CL, cs.CL  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2310.14883v1)  

---


**ABSTRACT**  
Simultaneous machine translation (SiMT) models are trained to strike a balance between latency and translation quality. However, training these models to achieve high quality while maintaining low latency often leads to a tendency for aggressive anticipation. We argue that such issue stems from the autoregressive architecture upon which most existing SiMT models are built. To address those issues, we propose non-autoregressive streaming Transformer (NAST) which comprises a unidirectional encoder and a non-autoregressive decoder with intra-chunk parallelism. We enable NAST to generate the blank token or repetitive tokens to adjust its READ/WRITE strategy flexibly, and train it to maximize the non-monotonic latent alignment with an alignment-based latency loss. Experiments on various SiMT benchmarks demonstrate that NAST outperforms previous strong autoregressive SiMT baselines.

{{</citation>}}


### (85/208) Can ChatGPT Perform Reasoning Using the IRAC Method in Analyzing Legal Scenarios Like a Lawyer? (Xiaoxi Kang et al., 2023)

{{<citation>}}

Xiaoxi Kang, Lizhen Qu, Lay-Ki Soon, Adnan Trakic, Terry Yue Zhuo, Patrick Charles Emerton, Genevieve Grant. (2023)  
**Can ChatGPT Perform Reasoning Using the IRAC Method in Analyzing Legal Scenarios Like a Lawyer?**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT, Language Model, Legal, Reasoning  
[Paper Link](http://arxiv.org/abs/2310.14880v1)  

---


**ABSTRACT**  
Large Language Models (LLMs), such as ChatGPT, have drawn a lot of attentions recently in the legal domain due to its emergent ability to tackle a variety of legal tasks. However, it is still unknown if LLMs are able to analyze a legal case and perform reasoning in the same manner as lawyers. Therefore, we constructed a novel corpus consisting of scenarios pertain to Contract Acts Malaysia and Australian Social Act for Dependent Child. ChatGPT is applied to perform analysis on the corpus using the IRAC method, which is a framework widely used by legal professionals for organizing legal analysis. Each scenario in the corpus is annotated with a complete IRAC analysis in a semi-structured format so that both machines and legal professionals are able to interpret and understand the annotations. In addition, we conducted the first empirical assessment of ChatGPT for IRAC analysis in order to understand how well it aligns with the analysis of legal professionals. Our experimental results shed lights on possible future research directions to improve alignments between LLMs and legal experts in terms of legal reasoning.

{{</citation>}}


### (86/208) We are Who We Cite: Bridges of Influence Between Natural Language Processing and Other Academic Fields (Jan Philip Wahle et al., 2023)

{{<citation>}}

Jan Philip Wahle, Terry Ruas, Mohamed Abdalla, Bela Gipp, Saif M. Mohammad. (2023)  
**We are Who We Cite: Bridges of Influence Between Natural Language Processing and Other Academic Fields**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-DL, cs.CL  
Keywords: NLP, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2310.14870v1)  

---


**ABSTRACT**  
Natural Language Processing (NLP) is poised to substantially influence the world. However, significant progress comes hand-in-hand with substantial risks. Addressing them requires broad engagement with various fields of study. Yet, little empirical work examines the state of such engagement (past or current). In this paper, we quantify the degree of influence between 23 fields of study and NLP (on each other). We analyzed ~77k NLP papers, ~3.1m citations from NLP papers to other papers, and ~1.8m citations from other papers to NLP papers. We show that, unlike most fields, the cross-field engagement of NLP, measured by our proposed Citation Field Diversity Index (CFDI), has declined from 0.58 in 1980 to 0.31 in 2022 (an all-time low). In addition, we find that NLP has grown more insular -- citing increasingly more NLP papers and having fewer papers that act as bridges between fields. NLP citations are dominated by computer science; Less than 8% of NLP citations are to linguistics, and less than 3% are to math and psychology. These findings underscore NLP's urgent need to reflect on its engagement with various fields.

{{</citation>}}


### (87/208) Assessing Step-by-Step Reasoning against Lexical Negation: A Case Study on Syllogism (Mengyu Ye et al., 2023)

{{<citation>}}

Mengyu Ye, Tatsuki Kuribayashi, Jun Suzuki, Goro Kobayashi, Hiroaki Funayama. (2023)  
**Assessing Step-by-Step Reasoning against Lexical Negation: A Case Study on Syllogism**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2310.14868v1)  

---


**ABSTRACT**  
Large language models (LLMs) take advantage of step-by-step reasoning instructions, e.g., chain-of-thought (CoT) prompting. Building on this, their ability to perform CoT-style reasoning robustly is of interest from a probing perspective. In this study, we inspect the step-by-step reasoning ability of LLMs with a focus on negation, which is a core linguistic phenomenon that is difficult to process. In particular, we introduce several controlled settings (e.g., reasoning in case of fictional entities) to evaluate the logical reasoning abilities of the models. We observed that dozens of modern LLMs were not robust against lexical negation (e.g., plausible ->implausible) when performing CoT-style reasoning, and the results highlight unique limitations in each LLM family.

{{</citation>}}


### (88/208) Contextual Refinement of Translations: Large Language Models for Sentence and Document-Level Post-Editing (Sai Koneru et al., 2023)

{{<citation>}}

Sai Koneru, Miriam Exel, Matthias Huck, Jan Niehues. (2023)  
**Contextual Refinement of Translations: Large Language Models for Sentence and Document-Level Post-Editing**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model, Machine Translation, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2310.14855v1)  

---


**ABSTRACT**  
Large Language Models (LLM's) have demonstrated considerable success in various Natural Language Processing tasks, but they have yet to attain state-of-the-art performance in Neural Machine Translation (NMT). Nevertheless, their significant performance in tasks demanding a broad understanding and contextual processing shows their potential for translation. To exploit these abilities, we investigate using LLM's for MT and explore recent parameter-efficient fine-tuning techniques. Surprisingly, our initial experiments find that fine-tuning for translation purposes even led to performance degradation. To overcome this, we propose an alternative approach: adapting LLM's as Automatic Post-Editors (APE) rather than direct translators. Building on the LLM's exceptional ability to process and generate lengthy sequences, we also propose extending our approach to document-level translation. We show that leveraging Low-Rank-Adapter fine-tuning for APE can yield significant improvements across both sentence and document-level metrics while generalizing to out-of-domain data. Most notably, we achieve a state-of-the-art accuracy rate of 89\% on the ContraPro test set, which specifically assesses the model's ability to resolve pronoun ambiguities when translating from English to German. Lastly, we investigate a practical scenario involving manual post-editing for document-level translation, where reference context is made available. Here, we demonstrate that leveraging human corrections can significantly reduce the number of edits required for subsequent translations\footnote{Interactive Demo for integrating manual feedback can be found \href{https://huggingface.co/spaces/skoneru/contextual_refinement_ende}{here}}

{{</citation>}}


### (89/208) Universal Domain Adaptation for Robust Handling of Distributional Shifts in NLP (Hyuhng Joon Kim et al., 2023)

{{<citation>}}

Hyuhng Joon Kim, Hyunsoo Cho, Sang-Woo Lee, Junyeob Kim, Choonghyun Park, Sang-goo Lee, Kang Min Yoo, Taeuk Kim. (2023)  
**Universal Domain Adaptation for Robust Handling of Distributional Shifts in NLP**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2310.14849v1)  

---


**ABSTRACT**  
When deploying machine learning systems to the wild, it is highly desirable for them to effectively leverage prior knowledge to the unfamiliar domain while also firing alarms to anomalous inputs. In order to address these requirements, Universal Domain Adaptation (UniDA) has emerged as a novel research area in computer vision, focusing on achieving both adaptation ability and robustness (i.e., the ability to detect out-of-distribution samples). While UniDA has led significant progress in computer vision, its application on language input still needs to be explored despite its feasibility. In this paper, we propose a comprehensive benchmark for natural language that offers thorough viewpoints of the model's generalizability and robustness. Our benchmark encompasses multiple datasets with varying difficulty levels and characteristics, including temporal shifts and diverse domains. On top of our testbed, we validate existing UniDA methods from computer vision and state-of-the-art domain adaptation techniques from NLP literature, yielding valuable findings: We observe that UniDA methods originally designed for image input can be effectively transferred to the natural language domain while also underscoring the effect of adaptation difficulty in determining the model's performance.

{{</citation>}}


### (90/208) Transparency at the Source: Evaluating and Interpreting Language Models With Access to the True Distribution (Jaap Jumelet et al., 2023)

{{<citation>}}

Jaap Jumelet, Willem Zuidema. (2023)  
**Transparency at the Source: Evaluating and Interpreting Language Models With Access to the True Distribution**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.14840v1)  

---


**ABSTRACT**  
We present a setup for training, evaluating and interpreting neural language models, that uses artificial, language-like data. The data is generated using a massive probabilistic grammar (based on state-split PCFGs), that is itself derived from a large natural language corpus, but also provides us complete control over the generative process. We describe and release both grammar and corpus, and test for the naturalness of our generated data. This approach allows us to define closed-form expressions to efficiently compute exact lower bounds on obtainable perplexity using both causal and masked language modelling. Our results show striking differences between neural language modelling architectures and training objectives in how closely they allow approximating the lower bound on perplexity. Our approach also allows us to directly compare learned representations to symbolic rules in the underlying source. We experiment with various techniques for interpreting model behaviour and learning dynamics. With access to the underlying true source, our results show striking differences and outcomes in learning dynamics between different classes of words.

{{</citation>}}


### (91/208) Characterizing how 'distributional' NLP corpora distance metrics are (Samuel Ackerman et al., 2023)

{{<citation>}}

Samuel Ackerman, George Kour, Eitan Farchi. (2023)  
**Characterizing how 'distributional' NLP corpora distance metrics are**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL, stat-AP  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2310.14829v1)  

---


**ABSTRACT**  
A corpus of vector-embedded text documents has some empirical distribution. Given two corpora, we want to calculate a single metric of distance (e.g., Mauve, Frechet Inception) between them. We describe an abstract quality, called `distributionality', of such metrics. A non-distributional metric tends to use very local measurements, or uses global measurements in a way that does not fully reflect the distributions' true distance. For example, if individual pairwise nearest-neighbor distances are low, it may judge the two corpora to have low distance, even if their two distributions are in fact far from each other. A more distributional metric will, in contrast, better capture the distributions' overall distance. We quantify this quality by constructing a Known-Similarity Corpora set from two paraphrase corpora and calculating the distance between paired corpora from it. The distances' trend shape as set element separation increases should quantify the distributionality of the metric. We propose that Average Hausdorff Distance and energy distance between corpora are representative examples of non-distributional and distributional distance metrics, to which other metrics can be compared, to evaluate how distributional they are.

{{</citation>}}


### (92/208) ALCUNA: Large Language Models Meet New Knowledge (Xunjian Yin et al., 2023)

{{<citation>}}

Xunjian Yin, Baizhou Huang, Xiaojun Wan. (2023)  
**ALCUNA: Large Language Models Meet New Knowledge**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2310.14820v1)  

---


**ABSTRACT**  
With the rapid development of NLP, large-scale language models (LLMs) excel in various tasks across multiple domains now. However, existing benchmarks may not adequately measure these models' capabilities, especially when faced with new knowledge. In this paper, we address the lack of benchmarks to evaluate LLMs' ability to handle new knowledge, an important and challenging aspect in the rapidly evolving world. We propose an approach called KnowGen that generates new knowledge by altering existing entity attributes and relationships, resulting in artificial entities that are distinct from real-world entities. With KnowGen, we introduce a benchmark named ALCUNA to assess LLMs' abilities in knowledge understanding, differentiation, and association. We benchmark several LLMs, reveals that their performance in face of new knowledge is not satisfactory, particularly in reasoning between new and internal knowledge. We also explore the impact of entity similarity on the model's understanding of entity knowledge and the influence of contextual entities. We appeal to the need for caution when using LLMs in new scenarios or with new knowledge, and hope that our benchmarks can help drive the development of LLMs in face of new knowledge.

{{</citation>}}


### (93/208) Analyzing Multilingual Competency of LLMs in Multi-Turn Instruction Following: A Case Study of Arabic (Sabri Boughorbel et al., 2023)

{{<citation>}}

Sabri Boughorbel, Majd Hawasly. (2023)  
**Analyzing Multilingual Competency of LLMs in Multi-Turn Instruction Following: A Case Study of Arabic**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, GPT-4, Language Model, Multilingual  
[Paper Link](http://arxiv.org/abs/2310.14819v1)  

---


**ABSTRACT**  
While significant progress has been made in benchmarking Large Language Models (LLMs) across various tasks, there is a lack of comprehensive evaluation of their abilities in responding to multi-turn instructions in less-commonly tested languages like Arabic. Our paper offers a detailed examination of the proficiency of open LLMs in such scenarios in Arabic. Utilizing a customized Arabic translation of the MT-Bench benchmark suite, we employ GPT-4 as a uniform evaluator for both English and Arabic queries to assess and compare the performance of the LLMs on various open-ended tasks. Our findings reveal variations in model responses on different task categories, e.g., logic vs. literacy, when instructed in English or Arabic. We find that fine-tuned base models using multilingual and multi-turn datasets could be competitive to models trained from scratch on multilingual data. Finally, we hypothesize that an ensemble of small, open LLMs could perform competitively to proprietary LLMs on the benchmark.

{{</citation>}}


### (94/208) DISC-FinLLM: A Chinese Financial Large Language Model based on Multiple Experts Fine-tuning (Wei Chen et al., 2023)

{{<citation>}}

Wei Chen, Qiushi Wang, Zefei Long, Xianyin Zhang, Zhongtian Lu, Bingxuan Li, Siyuan Wang, Jiarong Xu, Xiang Bai, Xuanjing Huang, Zhongyu Wei. (2023)  
**DISC-FinLLM: A Chinese Financial Large Language Model based on Multiple Experts Fine-tuning**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Financial, Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2310.15205v2)  

---


**ABSTRACT**  
We propose Multiple Experts Fine-tuning Framework to build a financial large language model (LLM), DISC-FinLLM. Our methodology improves general LLMs by endowing them with multi-turn question answering abilities, domain text processing capabilities, mathematical computation skills, and retrieval-enhanced generation capabilities. We build a financial instruction-tuning dataset named DISC-FIN-SFT, including instruction samples of four categories (consulting, NLP tasks, computing and retrieval-augmented generation). Evaluations conducted on multiple benchmarks demonstrate that our model performs better than baseline models in various financial scenarios. Further resources can be found at https://github.com/FudanDISC/DISC-FinLLM.

{{</citation>}}


### (95/208) Leveraging Timestamp Information for Serialized Joint Streaming Recognition and Translation (Sara Papi et al., 2023)

{{<citation>}}

Sara Papi, Peidong Wang, Junkun Chen, Jian Xue, Naoyuki Kanda, Jinyu Li, Yashesh Gaur. (2023)  
**Leveraging Timestamp Information for Serialized Joint Streaming Recognition and Translation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2310.14806v1)  

---


**ABSTRACT**  
The growing need for instant spoken language transcription and translation is driven by increased global communication and cross-lingual interactions. This has made offering translations in multiple languages essential for user applications. Traditional approaches to automatic speech recognition (ASR) and speech translation (ST) have often relied on separate systems, leading to inefficiencies in computational resources, and increased synchronization complexity in real time. In this paper, we propose a streaming Transformer-Transducer (T-T) model able to jointly produce many-to-one and one-to-many transcription and translation using a single decoder. We introduce a novel method for joint token-level serialized output training based on timestamp information to effectively produce ASR and ST outputs in the streaming setting. Experiments on {it,es,de}->en prove the effectiveness of our approach, enabling the generation of one-to-many joint outputs with a single decoder for the first time.

{{</citation>}}


### (96/208) Cross-lingual Prompting: Improving Zero-shot Chain-of-Thought Reasoning across Languages (Libo Qin et al., 2023)

{{<citation>}}

Libo Qin, Qiguang Chen, Fuxuan Wei, Shijue Huang, Wanxiang Che. (2023)  
**Cross-lingual Prompting: Improving Zero-shot Chain-of-Thought Reasoning across Languages**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2310.14799v1)  

---


**ABSTRACT**  
Chain-of-thought (CoT) is capable of eliciting models to explicitly generate reasoning paths, thus promoting reasoning accuracy and attracting increasing attention. Specifically, zero-shot CoT achieves remarkable improvements in a wide range of reasoning tasks by simply instructing the LLM with the prompt "Let's think step by step!". Despite the success of zero-shot CoT, the existing zero-shot prompting techniques remain limited to a single language, making it challenging to generalize to other languages and hindering global development. In this work, we introduce cross-lingual prompting (CLP), aiming to improve zero-shot CoT reasoning across languages. Specifically, CLP consists of two main components: (1) cross-lingual alignment prompting and (2) task-specific solver prompting. The cross-lingual alignment prompting is responsible for aligning representations across different languages, whereas the task-specific solver prompting is used to generate the final chain of thoughts and results for the reasoning task. In addition, we further introduce cross-lingual self-consistent prompting (CLSP) to ensemble different reasoning paths across languages. Our experimental evaluations on several benchmarks demonstrate that CLP and CLSP significantly outperform the existing prompting methods and achieve state-of-the-art performance. We hope this work will inspire further breakthroughs in cross-lingual CoT.

{{</citation>}}


### (97/208) Evaluating the Knowledge Base Completion Potential of GPT (Blerta Veseli et al., 2023)

{{<citation>}}

Blerta Veseli, Simon Razniewski, Jan-Christoph Kalo, Gerhard Weikum. (2023)  
**Evaluating the Knowledge Base Completion Potential of GPT**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2310.14771v1)  

---


**ABSTRACT**  
Structured knowledge bases (KBs) are an asset for search engines and other applications, but are inevitably incomplete. Language models (LMs) have been proposed for unsupervised knowledge base completion (KBC), yet, their ability to do this at scale and with high accuracy remains an open question. Prior experimental studies mostly fall short because they only evaluate on popular subjects, or sample already existing facts from KBs. In this work, we perform a careful evaluation of GPT's potential to complete the largest public KB: Wikidata. We find that, despite their size and capabilities, models like GPT-3, ChatGPT and GPT-4 do not achieve fully convincing results on this task. Nonetheless, they provide solid improvements over earlier approaches with smaller LMs. In particular, we show that, with proper thresholding, GPT-3 enables to extend Wikidata by 27M facts at 90% precision.

{{</citation>}}


### (98/208) SuperTweetEval: A Challenging, Unified and Heterogeneous Benchmark for Social Media NLP Research (Dimosthenis Antypas et al., 2023)

{{<citation>}}

Dimosthenis Antypas, Asahi Ushio, Francesco Barbieri, Leonardo Neves, Kiamehr Rezaee, Luis Espinosa-Anke, Jiaxin Pei, Jose Camacho-Collados. (2023)  
**SuperTweetEval: A Challenging, Unified and Heterogeneous Benchmark for Social Media NLP Research**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NLP, Social Media  
[Paper Link](http://arxiv.org/abs/2310.14757v1)  

---


**ABSTRACT**  
Despite its relevance, the maturity of NLP for social media pales in comparison with general-purpose models, metrics and benchmarks. This fragmented landscape makes it hard for the community to know, for instance, given a task, which is the best performing model and how it compares with others. To alleviate this issue, we introduce a unified benchmark for NLP evaluation in social media, SuperTweetEval, which includes a heterogeneous set of tasks and datasets combined, adapted and constructed from scratch. We benchmarked the performance of a wide range of models on SuperTweetEval and our results suggest that, despite the recent advances in language modelling, social media remains challenging.

{{</citation>}}


### (99/208) MCC-KD: Multi-CoT Consistent Knowledge Distillation (Hongzhan Chen et al., 2023)

{{<citation>}}

Hongzhan Chen, Siyue Wu, Xiaojun Quan, Rui Wang, Ming Yan, Ji Zhang. (2023)  
**MCC-KD: Multi-CoT Consistent Knowledge Distillation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Knowledge Distillation, LLaMA, T5  
[Paper Link](http://arxiv.org/abs/2310.14747v2)  

---


**ABSTRACT**  
Large language models (LLMs) have showcased remarkable capabilities in complex reasoning through chain of thought (CoT) prompting. Recently, there has been a growing interest in transferring these reasoning abilities from LLMs to smaller models. However, achieving both the diversity and consistency in rationales presents a challenge. In this paper, we focus on enhancing these two aspects and propose Multi-CoT Consistent Knowledge Distillation (MCC-KD) to efficiently distill the reasoning capabilities. In MCC-KD, we generate multiple rationales for each question and enforce consistency among the corresponding predictions by minimizing the bidirectional KL-divergence between the answer distributions. We investigate the effectiveness of MCC-KD with different model architectures (LLaMA/FlanT5) and various model scales (3B/7B/11B/13B) on both mathematical reasoning and commonsense reasoning benchmarks. The empirical results not only confirm MCC-KD's superior performance on in-distribution datasets but also highlight its robust generalization ability on out-of-distribution datasets.

{{</citation>}}


### (100/208) Unleashing the potential of prompt engineering in Large Language Models: a comprehensive review (Banghao Chen et al., 2023)

{{<citation>}}

Banghao Chen, Zhaofeng Zhang, Nicolas Langrené, Shengxin Zhu. (2023)  
**Unleashing the potential of prompt engineering in Large Language Models: a comprehensive review**  

---
Primary Category: cs.CL  
Categories: 62, I-2-7, cs-AI, cs-CL, cs.CL  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2310.14735v1)  

---


**ABSTRACT**  
This paper delves into the pivotal role of prompt engineering in unleashing the capabilities of Large Language Models (LLMs). Prompt engineering is the process of structuring input text for LLMs and is a technique integral to optimizing the efficacy of LLMs. This survey elucidates foundational principles of prompt engineering, such as role-prompting, one-shot, and few-shot prompting, as well as more advanced methodologies such as the chain-of-thought and tree-of-thoughts prompting. The paper sheds light on how external assistance in the form of plugins can assist in this task, and reduce machine hallucination by retrieving external knowledge. We subsequently delineate prospective directions in prompt engineering research, emphasizing the need for a deeper understanding of structures and the role of agents in Artificial Intelligence-Generated Content (AIGC) tools. We discuss how to assess the efficacy of prompt methods from different perspectives and using different methods. Finally, we gather information about the application of prompt engineering in such fields as education and programming, showing its transformative potential. This comprehensive survey aims to serve as a friendly guide for anyone venturing through the big world of LLMs and prompt engineering.

{{</citation>}}


### (101/208) Generating Prototypes for Contradiction Detection Using Large Language Models and Linguistic Rules (Maren Pielka et al., 2023)

{{<citation>}}

Maren Pielka, Svetlana Schmidt, Rafet Sifa. (2023)  
**Generating Prototypes for Contradiction Detection Using Large Language Models and Linguistic Rules**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.14732v1)  

---


**ABSTRACT**  
We introduce a novel data generation method for contradiction detection, which leverages the generative power of large language models as well as linguistic rules. Our vision is to provide a condensed corpus of prototypical contradictions, allowing for in-depth linguistic analysis as well as efficient language model fine-tuning. To this end, we instruct the generative models to create contradicting statements with respect to descriptions of specific contradiction types. In addition, the model is also instructed to come up with completely new contradiction typologies. As an auxiliary approach, we use linguistic rules to construct simple contradictions such as those arising from negation, antonymy and numeric mismatch. We find that our methods yield promising results in terms of coherence and variety of the data. Further studies, as well as manual refinement are necessary to make use of this data in a machine learning setup.

{{</citation>}}


### (102/208) A Survey on LLM-generated Text Detection: Necessity, Methods, and Future Directions (Junchao Wu et al., 2023)

{{<citation>}}

Junchao Wu, Shu Yang, Runzhe Zhan, Yulin Yuan, Derek F. Wong, Lidia S. Chao. (2023)  
**A Survey on LLM-generated Text Detection: Necessity, Methods, and Future Directions**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, NLP  
[Paper Link](http://arxiv.org/abs/2310.14724v2)  

---


**ABSTRACT**  
The powerful ability to understand, follow, and generate complex language emerging from large language models (LLMs) makes LLM-generated text flood many areas of our daily lives at an incredible speed and is widely accepted by humans. As LLMs continue to expand, there is an imperative need to develop detectors that can detect LLM-generated text. This is crucial to mitigate potential misuse of LLMs and safeguard realms like artistic expression and social networks from harmful influence of LLM-generated content. The LLM-generated text detection aims to discern if a piece of text was produced by an LLM, which is essentially a binary classification task. The detector techniques have witnessed notable advancements recently, propelled by innovations in watermarking techniques, zero-shot methods, fine-turning LMs methods, adversarial learning methods, LLMs as detectors, and human-assisted methods. In this survey, we collate recent research breakthroughs in this area and underscore the pressing need to bolster detector research. We also delve into prevalent datasets, elucidating their limitations and developmental requirements. Furthermore, we analyze various LLM-generated text detection paradigms, shedding light on challenges like out-of-distribution problems, potential attacks, and data ambiguity. Conclusively, we highlight interesting directions for future research in LLM-generated text detection to advance the implementation of responsible artificial intelligence (AI). Our aim with this survey is to provide a clear and comprehensive introduction for newcomers while also offering seasoned researchers a valuable update in the field of LLM-generated text detection. The useful resources are publicly available at: https://github.com/NLP2CT/LLM-generated-Text-Detection.

{{</citation>}}


### (103/208) Once Upon a $\textit{Time}$ in $\textit{Graph}$: Relative-Time Pretraining for Complex Temporal Reasoning (Sen Yang et al., 2023)

{{<citation>}}

Sen Yang, Xin Li, Lidong Bing, Wai Lam. (2023)  
**Once Upon a $\textit{Time}$ in $\textit{Graph}$: Relative-Time Pretraining for Complex Temporal Reasoning**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NLP, Reasoning, T5  
[Paper Link](http://arxiv.org/abs/2310.14709v1)  

---


**ABSTRACT**  
Our physical world is constantly evolving over time, rendering challenges for pre-trained language models to understand and reason over the temporal contexts of texts. Existing work focuses on strengthening the direct association between a piece of text and its time-stamp. However, the knowledge-time association is usually insufficient for the downstream tasks that require reasoning over temporal dependencies between knowledge. In this work, we make use of the underlying nature of time, all temporally-scoped sentences are strung together through a one-dimensional time axis, and suggest creating a graph structure based on the relative placements of events along the time axis. Inspired by the graph view, we propose RemeMo ($\underline{Re}$lative Ti$\underline{me}$ $\underline{Mo}$deling), which explicitly connects all temporally-scoped facts by modeling the time relations between any two sentences. Experimental results show that RemeMo outperforms the baseline T5 on multiple temporal question answering datasets under various settings. Further analysis suggests that RemeMo is especially good at modeling long-range complex temporal dependencies. We release our code and pre-trained checkpoints at $\href{https://github.com/DAMO-NLP-SG/RemeMo}{\text{this url}}$.

{{</citation>}}


### (104/208) Strong and Efficient Baselines for Open Domain Conversational Question Answering (Andrei C. Coman et al., 2023)

{{<citation>}}

Andrei C. Coman, Gianni Barlacchi, Adrià de Gispert. (2023)  
**Strong and Efficient Baselines for Open Domain Conversational Question Answering**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2310.14708v1)  

---


**ABSTRACT**  
Unlike the Open Domain Question Answering (ODQA) setting, the conversational (ODConvQA) domain has received limited attention when it comes to reevaluating baselines for both efficiency and effectiveness. In this paper, we study the State-of-the-Art (SotA) Dense Passage Retrieval (DPR) retriever and Fusion-in-Decoder (FiD) reader pipeline, and show that it significantly underperforms when applied to ODConvQA tasks due to various limitations. We then propose and evaluate strong yet simple and efficient baselines, by introducing a fast reranking component between the retriever and the reader, and by performing targeted finetuning steps. Experiments on two ODConvQA tasks, namely TopiOCQA and OR-QuAC, show that our method improves the SotA results, while reducing reader's latency by 60%. Finally, we provide new and valuable insights into the development of challenging baselines that serve as a reference for future, more intricate approaches, including those that leverage Large Language Models (LLMs).

{{</citation>}}


### (105/208) The continued usefulness of vocabulary tests for evaluating large language models (Gonzalo Martínez et al., 2023)

{{<citation>}}

Gonzalo Martínez, Javier Conde, Elena Merino-Gómez, Beatriz Bermúdez-Margaretto, José Alberto Hernández, Pedro Reviriego, Marc Brysbaert. (2023)  
**The continued usefulness of vocabulary tests for evaluating large language models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.14703v1)  

---


**ABSTRACT**  
In their seminal article on semantic vectors, Landauer and Dumain (1997) proposed testing the quality of AI language models with a challenging vocabulary test. We show that their Test of English as a Foreign Language (TOEFL) test remains informative for contemporary major language models, since none of the models was perfect and made errors on divergent items. The TOEFL test consists of target words with four alternatives to choose from. We further tested the models on a Yes/No test that requires distinguishing between existing words and made-up nonwords. The models performed significantly worse on the nonword items, in line with other observations that current major language models provide non-existent information. The situation was worse when we generalized the tests to Spanish. Here, most models gave meanings/translations for the majority of random letter sequences. On the plus side, the best models began to perform quite well, and they also pointed to nonwords that were unknown to the test participants but can be found in dictionaries.

{{</citation>}}


### (106/208) Tree of Clarifications: Answering Ambiguous Questions with Retrieval-Augmented Large Language Models (Gangwoo Kim et al., 2023)

{{<citation>}}

Gangwoo Kim, Sungdong Kim, Byeongguk Jeon, Joonsuk Park, Jaewoo Kang. (2023)  
**Tree of Clarifications: Answering Ambiguous Questions with Retrieval-Augmented Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, QA  
[Paper Link](http://arxiv.org/abs/2310.14696v1)  

---


**ABSTRACT**  
Questions in open-domain question answering are often ambiguous, allowing multiple interpretations. One approach to handling them is to identify all possible interpretations of the ambiguous question (AQ) and to generate a long-form answer addressing them all, as suggested by Stelmakh et al., (2022). While it provides a comprehensive response without bothering the user for clarification, considering multiple dimensions of ambiguity and gathering corresponding knowledge remains a challenge. To cope with the challenge, we propose a novel framework, Tree of Clarifications (ToC): It recursively constructs a tree of disambiguations for the AQ -- via few-shot prompting leveraging external knowledge -- and uses it to generate a long-form answer. ToC outperforms existing baselines on ASQA in a few-shot setup across the metrics, while surpassing fully-supervised baselines trained on the whole training set in terms of Disambig-F1 and Disambig-ROUGE. Code is available at https://github.com/gankim/tree-of-clarifications.

{{</citation>}}


### (107/208) API-Assisted Code Generation for Question Answering on Varied Table Structures (Yihan Cao et al., 2023)

{{<citation>}}

Yihan Cao, Shuyi Chen, Ryan Liu, Zhiruo Wang, Daniel Fried. (2023)  
**API-Assisted Code Generation for Question Answering on Varied Table Structures**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2310.14687v1)  

---


**ABSTRACT**  
A persistent challenge to table question answering (TableQA) by generating executable programs has been adapting to varied table structures, typically requiring domain-specific logical forms. In response, this paper introduces a unified TableQA framework that: (1) provides a unified representation for structured tables as multi-index Pandas data frames, (2) uses Python as a powerful querying language, and (3) uses few-shot prompting to translate NL questions into Python programs, which are executable on Pandas data frames. Furthermore, to answer complex relational questions with extended program functionality and external knowledge, our framework allows customized APIs that Python programs can call. We experiment with four TableQA datasets that involve tables of different structures -- relational, multi-table, and hierarchical matrix shapes -- and achieve prominent improvements over past state-of-the-art systems. In ablation studies, we (1) show benefits from our multi-index representation and APIs over baselines that use only an LLM, and (2) demonstrate that our approach is modular and can incorporate additional APIs.

{{</citation>}}


### (108/208) SpEL: Structured Prediction for Entity Linking (Hassan S. Shavarani et al., 2023)

{{<citation>}}

Hassan S. Shavarani, Anoop Sarkar. (2023)  
**SpEL: Structured Prediction for Entity Linking**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.14684v1)  

---


**ABSTRACT**  
Entity linking is a prominent thread of research focused on structured data creation by linking spans of text to an ontology or knowledge source. We revisit the use of structured prediction for entity linking which classifies each individual input token as an entity, and aggregates the token predictions. Our system, called SpEL (Structured prediction for Entity Linking) is a state-of-the-art entity linking system that uses some new ideas to apply structured prediction to the task of entity linking including: two refined fine-tuning steps; a context sensitive prediction aggregation strategy; reduction of the size of the model's output vocabulary, and; we address a common problem in entity-linking systems where there is a training vs. inference tokenization mismatch. Our experiments show that we can outperform the state-of-the-art on the commonly used AIDA benchmark dataset for entity linking to Wikipedia. Our method is also very compute efficient in terms of number of parameters and speed of inference.

{{</citation>}}


### (109/208) Pre-Trained Language Models Augmented with Synthetic Scanpaths for Natural Language Understanding (Shuwen Deng et al., 2023)

{{<citation>}}

Shuwen Deng, Paul Prasse, David R. Reich, Tobias Scheffer, Lena A. Jäger. (2023)  
**Pre-Trained Language Models Augmented with Synthetic Scanpaths for Natural Language Understanding**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, NLP, Natural Language Understanding  
[Paper Link](http://arxiv.org/abs/2310.14676v1)  

---


**ABSTRACT**  
Human gaze data offer cognitive information that reflects natural language comprehension. Indeed, augmenting language models with human scanpaths has proven beneficial for a range of NLP tasks, including language understanding. However, the applicability of this approach is hampered because the abundance of text corpora is contrasted by a scarcity of gaze data. Although models for the generation of human-like scanpaths during reading have been developed, the potential of synthetic gaze data across NLP tasks remains largely unexplored. We develop a model that integrates synthetic scanpath generation with a scanpath-augmented language model, eliminating the need for human gaze data. Since the model's error gradient can be propagated throughout all parts of the model, the scanpath generator can be fine-tuned to downstream tasks. We find that the proposed model not only outperforms the underlying language model, but achieves a performance that is comparable to a language model augmented with real human gaze data. Our code is publicly available.

{{</citation>}}


### (110/208) Reasoning about Ambiguous Definite Descriptions (Stefan F. Schouten et al., 2023)

{{<citation>}}

Stefan F. Schouten, Peter Bloem, Ilia Markov, Piek Vossen. (2023)  
**Reasoning about Ambiguous Definite Descriptions**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model, Reasoning  
[Paper Link](http://arxiv.org/abs/2310.14657v1)  

---


**ABSTRACT**  
Natural language reasoning plays an increasingly important role in improving language models' ability to solve complex language understanding tasks. An interesting use case for reasoning is the resolution of context-dependent ambiguity. But no resources exist to evaluate how well Large Language Models can use explicit reasoning to resolve ambiguity in language. We propose to use ambiguous definite descriptions for this purpose and create and publish the first benchmark dataset consisting of such phrases. Our method includes all information required to resolve the ambiguity in the prompt, which means a model does not require anything but reasoning to do well. We find this to be a challenging task for recent LLMs. Code and data available at: https://github.com/sfschouten/exploiting-ambiguity

{{</citation>}}


### (111/208) SPRING-INX: A Multilingual Indian Language Speech Corpus by SPRING Lab, IIT Madras (Nithya R et al., 2023)

{{<citation>}}

Nithya R, Malavika S, Jordan F, Arjun Gangwar, Metilda N J, S Umesh, Rithik Sarab, Akhilesh Kumar Dubey, Govind Divakaran, Samudra Vijaya K, Suryakanth V Gangashetty. (2023)  
**SPRING-INX: A Multilingual Indian Language Speech Corpus by SPRING Lab, IIT Madras**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL, eess-AS  
Keywords: Multilingual  
[Paper Link](http://arxiv.org/abs/2310.14654v2)  

---


**ABSTRACT**  
India is home to a multitude of languages of which 22 languages are recognised by the Indian Constitution as official. Building speech based applications for the Indian population is a difficult problem owing to limited data and the number of languages and accents to accommodate. To encourage the language technology community to build speech based applications in Indian languages, we are open sourcing SPRING-INX data which has about 2000 hours of legally sourced and manually transcribed speech data for ASR system building in Assamese, Bengali, Gujarati, Hindi, Kannada, Malayalam, Marathi, Odia, Punjabi and Tamil. This endeavor is by SPRING Lab , Indian Institute of Technology Madras and is a part of National Language Translation Mission (NLTM), funded by the Indian Ministry of Electronics and Information Technology (MeitY), Government of India. We describe the data collection and data cleaning process along with the data statistics in this paper.

{{</citation>}}


### (112/208) Multilingual k-Nearest-Neighbor Machine Translation (David Stap et al., 2023)

{{<citation>}}

David Stap, Christof Monz. (2023)  
**Multilingual k-Nearest-Neighbor Machine Translation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BLEU, Machine Translation, Multilingual  
[Paper Link](http://arxiv.org/abs/2310.14644v1)  

---


**ABSTRACT**  
k-nearest-neighbor machine translation has demonstrated remarkable improvements in machine translation quality by creating a datastore of cached examples. However, these improvements have been limited to high-resource language pairs, with large datastores, and remain a challenge for low-resource languages. In this paper, we address this issue by combining representations from multiple languages into a single datastore. Our results consistently demonstrate substantial improvements not only in low-resource translation quality (up to +3.6 BLEU), but also for high-resource translation quality (up to +0.5 BLEU). Our experiments show that it is possible to create multilingual datastores that are a quarter of the size, achieving a 5.3x speed improvement, by using linguistic similarities for datastore creation.

{{</citation>}}


### (113/208) Extending Input Contexts of Language Models through Training on Segmented Sequences (Petros Karypis et al., 2023)

{{<citation>}}

Petros Karypis, Julian McAuley, George Karypis. (2023)  
**Extending Input Contexts of Language Models through Training on Segmented Sequences**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.14633v1)  

---


**ABSTRACT**  
Effectively training language models on long inputs poses many technical challenges. As a cost consideration, languages models are pretrained on a fixed sequence length before being adapted to longer sequences. We explore various methods for adapting models to longer inputs by training on segmented sequences and an interpolation-based method for extending absolute positional embeddings. We develop a training procedure to extend the input context size of pretrained models with no architectural changes and no additional memory costs than training on the original input lengths. By sub-sampling segments from long inputs while maintaining their original position the model is able to learn new positional interactions. Our method benefits both models trained with absolute positional embeddings, by extending their input contexts, as well as popular relative positional embedding methods showing a reduced perplexity on sequences longer than they were trained on. We demonstrate our method can extend input contexts by a factor of 4x while improving perplexity.

{{</citation>}}


### (114/208) Plan, Verify and Switch: Integrated Reasoning with Diverse X-of-Thoughts (Tengxiao Liu et al., 2023)

{{<citation>}}

Tengxiao Liu, Qipeng Guo, Yuqing Yang, Xiangkun Hu, Yue Zhang, Xipeng Qiu, Zheng Zhang. (2023)  
**Plan, Verify and Switch: Integrated Reasoning with Diverse X-of-Thoughts**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2310.14628v1)  

---


**ABSTRACT**  
As large language models (LLMs) have shown effectiveness with different prompting methods, such as Chain of Thought, Program of Thought, we find that these methods have formed a great complementarity to each other on math reasoning tasks. In this work, we propose XoT, an integrated problem solving framework by prompting LLMs with diverse reasoning thoughts. For each question, XoT always begins with selecting the most suitable method then executes each method iteratively. Within each iteration, XoT actively checks the validity of the generated answer and incorporates the feedback from external executors, allowing it to dynamically switch among different prompting methods. Through extensive experiments on 10 popular math reasoning datasets, we demonstrate the effectiveness of our proposed approach and thoroughly analyze the strengths of each module. Moreover, empirical results suggest that our framework is orthogonal to recent work that makes improvements on single reasoning methods and can further generalise to logical reasoning domain. By allowing method switching, XoT provides a fresh perspective on the collaborative integration of diverse reasoning thoughts in a unified framework.

{{</citation>}}


### (115/208) CrisisMatch: Semi-Supervised Few-Shot Learning for Fine-Grained Disaster Tweet Classification (Henry Peng Zou et al., 2023)

{{<citation>}}

Henry Peng Zou, Yue Zhou, Cornelia Caragea, Doina Caragea. (2023)  
**CrisisMatch: Semi-Supervised Few-Shot Learning for Fine-Grained Disaster Tweet Classification**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Few-Shot, Semi-Supervised, Twitter  
[Paper Link](http://arxiv.org/abs/2310.14627v1)  

---


**ABSTRACT**  
The shared real-time information about natural disasters on social media platforms like Twitter and Facebook plays a critical role in informing volunteers, emergency managers, and response organizations. However, supervised learning models for monitoring disaster events require large amounts of annotated data, making them unrealistic for real-time use in disaster events. To address this challenge, we present a fine-grained disaster tweet classification model under the semi-supervised, few-shot learning setting where only a small number of annotated data is required. Our model, CrisisMatch, effectively classifies tweets into fine-grained classes of interest using few labeled data and large amounts of unlabeled data, mimicking the early stage of a disaster. Through integrating effective semi-supervised learning ideas and incorporating TextMixUp, CrisisMatch achieves performance improvement on two disaster datasets of 11.2\% on average. Further analyses are also provided for the influence of the number of labeled data and out-of-domain results.

{{</citation>}}


### (116/208) Conversational Recommender System and Large Language Model Are Made for Each Other in E-commerce Pre-sales Dialogue (Yuanxing Liu et al., 2023)

{{<citation>}}

Yuanxing Liu, Wei-Nan Zhang, Yifan Chen, Yuchi Zhang, Haopeng Bai, Fan Feng, Hengbin Cui, Yongbin Li, Wanxiang Che. (2023)  
**Conversational Recommender System and Large Language Model Are Made for Each Other in E-commerce Pre-sales Dialogue**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-IR, cs.CL  
Keywords: Dialog, Dialogue, Language Model  
[Paper Link](http://arxiv.org/abs/2310.14626v1)  

---


**ABSTRACT**  
E-commerce pre-sales dialogue aims to understand and elicit user needs and preferences for the items they are seeking so as to provide appropriate recommendations. Conversational recommender systems (CRSs) learn user representation and provide accurate recommendations based on dialogue context, but rely on external knowledge. Large language models (LLMs) generate responses that mimic pre-sales dialogues after fine-tuning, but lack domain-specific knowledge for accurate recommendations. Intuitively, the strengths of LLM and CRS in E-commerce pre-sales dialogues are complementary, yet no previous work has explored this. This paper investigates the effectiveness of combining LLM and CRS in E-commerce pre-sales dialogues, proposing two collaboration methods: CRS assisting LLM and LLM assisting CRS. We conduct extensive experiments on a real-world dataset of Ecommerce pre-sales dialogues. We analyze the impact of two collaborative approaches with two CRSs and two LLMs on four tasks of Ecommerce pre-sales dialogue. We find that collaborations between CRS and LLM can be very effective in some cases.

{{</citation>}}


### (117/208) CoF-CoT: Enhancing Large Language Models with Coarse-to-Fine Chain-of-Thought Prompting for Multi-domain NLU Tasks (Hoang H. Nguyen et al., 2023)

{{<citation>}}

Hoang H. Nguyen, Ye Liu, Chenwei Zhang, Tao Zhang, Philip S. Yu. (2023)  
**CoF-CoT: Enhancing Large Language Models with Coarse-to-Fine Chain-of-Thought Prompting for Multi-domain NLU Tasks**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Abstract Meaning Representation, Language Model, NLU, Natural Language Understanding  
[Paper Link](http://arxiv.org/abs/2310.14623v1)  

---


**ABSTRACT**  
While Chain-of-Thought prompting is popular in reasoning tasks, its application to Large Language Models (LLMs) in Natural Language Understanding (NLU) is under-explored. Motivated by multi-step reasoning of LLMs, we propose Coarse-to-Fine Chain-of-Thought (CoF-CoT) approach that breaks down NLU tasks into multiple reasoning steps where LLMs can learn to acquire and leverage essential concepts to solve tasks from different granularities. Moreover, we propose leveraging semantic-based Abstract Meaning Representation (AMR) structured knowledge as an intermediate step to capture the nuances and diverse structures of utterances, and to understand connections between their varying levels of granularity. Our proposed approach is demonstrated effective in assisting the LLMs adapt to the multi-grained NLU tasks under both zero-shot and few-shot multi-domain settings.

{{</citation>}}


### (118/208) Efficient Cross-Task Prompt Tuning for Few-Shot Conversational Emotion Recognition (Yige Xu et al., 2023)

{{<citation>}}

Yige Xu, Zhiwei Zeng, Zhiqi Shen. (2023)  
**Efficient Cross-Task Prompt Tuning for Few-Shot Conversational Emotion Recognition**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Emotion Recognition, Few-Shot  
[Paper Link](http://arxiv.org/abs/2310.14614v1)  

---


**ABSTRACT**  
Emotion Recognition in Conversation (ERC) has been widely studied due to its importance in developing emotion-aware empathetic machines. The rise of pre-trained language models (PLMs) has further pushed the limit of ERC performance. However, most recent works on ERC using PLMs are heavily data-driven, and requires fine-tuning the entire PLMs. To improve both sample and computational efficiency, we propose a derivative-free optimization method called Cross-Task Prompt Tuning (CTPT) for few-shot conversational emotion recognition. Unlike existing methods that learn independent knowledge from individual tasks, CTPT leverages sharable cross-task knowledge by exploiting external knowledge from other source tasks to improve learning performance under the few-shot setting. Moreover, CTPT only needs to optimize a vector under the low intrinsic dimensionality without gradient, which is highly parameter-efficient compared with existing approaches. Experiments on five different contextual conversation datasets demonstrate that our CTPT method has superior results on both few-shot scenarios and zero-shot transfers.

{{</citation>}}


### (119/208) Long Short-Term Planning for Conversational Recommendation Systems (Xian Li et al., 2023)

{{<citation>}}

Xian Li, Hongguang Shi, Yunfei Wang, Yeqin Zhang, Xubin Li, Cam-Tu Nguyen. (2023)  
**Long Short-Term Planning for Conversational Recommendation Systems**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Conversational Recommendation  
[Paper Link](http://arxiv.org/abs/2310.14609v1)  

---


**ABSTRACT**  
In Conversational Recommendation Systems (CRS), the central question is how the conversational agent can naturally ask for user preferences and provide suitable recommendations. Existing works mainly follow the hierarchical architecture, where a higher policy decides whether to invoke the conversation module (to ask questions) or the recommendation module (to make recommendations). This architecture prevents these two components from fully interacting with each other. In contrast, this paper proposes a novel architecture, the long short-term feedback architecture, to connect these two essential components in CRS. Specifically, the recommendation predicts the long-term recommendation target based on the conversational context and the user history. Driven by the targeted recommendation, the conversational model predicts the next topic or attribute to verify if the user preference matches the target. The balance feedback loop continues until the short-term planner output matches the long-term planner output, that is when the system should make the recommendation.

{{</citation>}}


### (120/208) Investigating the Fairness of Large Language Models for Predictions on Tabular Data (Yanchen Liu et al., 2023)

{{<citation>}}

Yanchen Liu, Srishti Gautam, Jiaqi Ma, Himabindu Lakkaraju. (2023)  
**Investigating the Fairness of Large Language Models for Predictions on Tabular Data**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.14607v1)  

---


**ABSTRACT**  
Recent literature has suggested the potential of using large language models (LLMs) to make predictions for tabular tasks. However, LLMs have been shown to exhibit harmful social biases that reflect the stereotypes and inequalities present in the society. To this end, as well as the widespread use of tabular data in many high-stake applications, it is imperative to explore the following questions: what sources of information do LLMs draw upon when making predictions for tabular tasks; whether and to what extent are LLM predictions for tabular tasks influenced by social biases and stereotypes; and what are the consequential implications for fairness? Through a series of experiments, we delve into these questions and show that LLMs tend to inherit social biases from their training data which significantly impact their fairness in tabular prediction tasks. Furthermore, our investigations show that in the context of bias mitigation, though in-context learning and fine-tuning have a moderate effect, the fairness metric gap between different subgroups is still larger than that in traditional machine learning models, such as Random Forest and shallow Neural Networks. This observation emphasizes that the social biases are inherent within the LLMs themselves and inherited from their pre-training corpus, not only from the downstream task datasets. Besides, we demonstrate that label-flipping of in-context examples can significantly reduce biases, further highlighting the presence of inherent bias within LLMs.

{{</citation>}}


### (121/208) M2DF: Multi-grained Multi-curriculum Denoising Framework for Multimodal Aspect-based Sentiment Analysis (Fei Zhao et al., 2023)

{{<citation>}}

Fei Zhao, Chunhui Li, Zhen Wu, Yawen Ouyang, Jianbing Zhang, Xinyu Dai. (2023)  
**M2DF: Multi-grained Multi-curriculum Denoising Framework for Multimodal Aspect-based Sentiment Analysis**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-MM, cs.CL  
Keywords: Sentiment Analysis  
[Paper Link](http://arxiv.org/abs/2310.14605v1)  

---


**ABSTRACT**  
Multimodal Aspect-based Sentiment Analysis (MABSA) is a fine-grained Sentiment Analysis task, which has attracted growing research interests recently. Existing work mainly utilizes image information to improve the performance of MABSA task. However, most of the studies overestimate the importance of images since there are many noise images unrelated to the text in the dataset, which will have a negative impact on model learning. Although some work attempts to filter low-quality noise images by setting thresholds, relying on thresholds will inevitably filter out a lot of useful image information. Therefore, in this work, we focus on whether the negative impact of noisy images can be reduced without modifying the data. To achieve this goal, we borrow the idea of Curriculum Learning and propose a Multi-grained Multi-curriculum Denoising Framework (M2DF), which can achieve denoising by adjusting the order of training data. Extensive experimental results show that our framework consistently outperforms state-of-the-art work on three sub-tasks of MABSA.

{{</citation>}}


### (122/208) Generative Pre-trained Transformer for Vietnamese Community-based COVID-19 Question Answering (Tam Minh Vo et al., 2023)

{{<citation>}}

Tam Minh Vo, Khiem Vinh Tran. (2023)  
**Generative Pre-trained Transformer for Vietnamese Community-based COVID-19 Question Answering**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, Question Answering, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2310.14602v1)  

---


**ABSTRACT**  
Recent studies have provided empirical evidence of the wide-ranging potential of Generative Pre-trained Transformer (GPT), a pretrained language model, in the field of natural language processing. GPT has been effectively employed as a decoder within state-of-the-art (SOTA) question answering systems, yielding exceptional performance across various tasks. However, the current research landscape concerning GPT's application in Vietnamese remains limited. This paper aims to address this gap by presenting an implementation of GPT-2 for community-based question answering specifically focused on COVID-19 related queries in Vietnamese. We introduce a novel approach by conducting a comparative analysis of different Transformers vs SOTA models in the community-based COVID-19 question answering dataset. The experimental findings demonstrate that the GPT-2 models exhibit highly promising outcomes, outperforming other SOTA models as well as previous community-based COVID-19 question answering models developed for Vietnamese.

{{</citation>}}


### (123/208) Prefix-Tuning Based Unsupervised Text Style Transfer (Huiyu Mai et al., 2023)

{{<citation>}}

Huiyu Mai, Wenhao Jiang, Zhihong Deng. (2023)  
**Prefix-Tuning Based Unsupervised Text Style Transfer**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT, Style Transfer  
[Paper Link](http://arxiv.org/abs/2310.14599v1)  

---


**ABSTRACT**  
Unsupervised text style transfer aims at training a generative model that can alter the style of the input sentence while preserving its content without using any parallel data. In this paper, we employ powerful pre-trained large language models and present a new prefix-tuning-based method for unsupervised text style transfer. We construct three different kinds of prefixes, i.e., \textit{shared prefix, style prefix}, and \textit{content prefix}, to encode task-specific information, target style, and the content information of the input sentence, respectively. Compared to embeddings used by previous works, the proposed prefixes can provide richer information for the model. Furthermore, we adopt a recursive way of using language models in the process of style transfer. This strategy provides a more effective way for the interactions between the input sentence and GPT-2, helps the model construct more informative prefixes, and thus, helps improve the performance. Evaluations on the well-known datasets show that our method outperforms the state-of-the-art baselines. Results, analysis of ablation studies, and subjective evaluations from humans are also provided for a deeper understanding of the proposed method.

{{</citation>}}


### (124/208) Learning to Correct Noisy Labels for Fine-Grained Entity Typing via Co-Prediction Prompt Tuning (Minghao Tang et al., 2023)

{{<citation>}}

Minghao Tang, Yongquan He, Yongxiu Xu, Hongbo Xu, Wenyuan Zhang, Yang Lin. (2023)  
**Learning to Correct Noisy Labels for Fine-Grained Entity Typing via Co-Prediction Prompt Tuning**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2310.14596v1)  

---


**ABSTRACT**  
Fine-grained entity typing (FET) is an essential task in natural language processing that aims to assign semantic types to entities in text. However, FET poses a major challenge known as the noise labeling problem, whereby current methods rely on estimating noise distribution to identify noisy labels but are confused by diverse noise distribution deviation. To address this limitation, we introduce Co-Prediction Prompt Tuning for noise correction in FET, which leverages multiple prediction results to identify and correct noisy labels. Specifically, we integrate prediction results to recall labeled labels and utilize a differentiated margin to identify inaccurate labels. Moreover, we design an optimization objective concerning divergent co-predictions during fine-tuning, ensuring that the model captures sufficient information and maintains robustness in noise identification. Experimental results on three widely-used FET datasets demonstrate that our noise correction approach significantly enhances the quality of various types of training samples, including those annotated using distant supervision, ChatGPT, and crowdsourcing.

{{</citation>}}


### (125/208) JointMatch: A Unified Approach for Diverse and Collaborative Pseudo-Labeling to Semi-Supervised Text Classification (Henry Peng Zou et al., 2023)

{{<citation>}}

Henry Peng Zou, Cornelia Caragea. (2023)  
**JointMatch: A Unified Approach for Diverse and Collaborative Pseudo-Labeling to Semi-Supervised Text Classification**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Semi-Supervised, Text Classification  
[Paper Link](http://arxiv.org/abs/2310.14583v1)  

---


**ABSTRACT**  
Semi-supervised text classification (SSTC) has gained increasing attention due to its ability to leverage unlabeled data. However, existing approaches based on pseudo-labeling suffer from the issues of pseudo-label bias and error accumulation. In this paper, we propose JointMatch, a holistic approach for SSTC that addresses these challenges by unifying ideas from recent semi-supervised learning and the task of learning with noise. JointMatch adaptively adjusts classwise thresholds based on the learning status of different classes to mitigate model bias towards current easy classes. Additionally, JointMatch alleviates error accumulation by utilizing two differently initialized networks to teach each other in a cross-labeling manner. To maintain divergence between the two networks for mutual learning, we introduce a strategy that weighs more disagreement data while also allowing the utilization of high-quality agreement data for training. Experimental results on benchmark datasets demonstrate the superior performance of JointMatch, achieving a significant 5.13% improvement on average. Notably, JointMatch delivers impressive results even in the extremely-scarce-label setting, obtaining 86% accuracy on AG News with only 5 labels per class. We make our code available at https://github.com/HenryPengZou/JointMatch.

{{</citation>}}


### (126/208) DeCrisisMB: Debiased Semi-Supervised Learning for Crisis Tweet Classification via Memory Bank (Henry Peng Zou et al., 2023)

{{<citation>}}

Henry Peng Zou, Yue Zhou, Weizhi Zhang, Cornelia Caragea. (2023)  
**DeCrisisMB: Debiased Semi-Supervised Learning for Crisis Tweet Classification via Memory Bank**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Semi-Supervised, Twitter  
[Paper Link](http://arxiv.org/abs/2310.14577v1)  

---


**ABSTRACT**  
During crisis events, people often use social media platforms such as Twitter to disseminate information about the situation, warnings, advice, and support. Emergency relief organizations leverage such information to acquire timely crisis circumstances and expedite rescue operations. While existing works utilize such information to build models for crisis event analysis, fully-supervised approaches require annotating vast amounts of data and are impractical due to limited response time. On the other hand, semi-supervised models can be biased, performing moderately well for certain classes while performing extremely poorly for others, resulting in substantially negative effects on disaster monitoring and rescue. In this paper, we first study two recent debiasing methods on semi-supervised crisis tweet classification. Then we propose a simple but effective debiasing method, DeCrisisMB, that utilizes a Memory Bank to store and perform equal sampling for generated pseudo-labels from each class at each training iteration. Extensive experiments are conducted to compare different debiasing methods' performance and generalization ability in both in-distribution and out-of-distribution settings. The results demonstrate the superior performance of our proposed method. Our code is available at https://github.com/HenryPengZou/DeCrisisMB.

{{</citation>}}


### (127/208) Exploring the Boundaries of GPT-4 in Radiology (Qianchu Liu et al., 2023)

{{<citation>}}

Qianchu Liu, Stephanie Hyland, Shruthi Bannur, Kenza Bouzid, Daniel C. Castro, Maria Teodora Wetscherek, Robert Tinn, Harshita Sharma, Fernando Pérez-García, Anton Schwaighofer, Pranav Rajpurkar, Sameer Tajdin Khanna, Hoifung Poon, Naoto Usuyama, Anja Thieme, Aditya V. Nori, Matthew P. Lungren, Ozan Oktay, Javier Alvarez-Valle. (2023)  
**Exploring the Boundaries of GPT-4 in Radiology**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2310.14573v1)  

---


**ABSTRACT**  
The recent success of general-domain large language models (LLMs) has significantly changed the natural language processing paradigm towards a unified foundation model across domains and applications. In this paper, we focus on assessing the performance of GPT-4, the most capable LLM so far, on the text-based applications for radiology reports, comparing against state-of-the-art (SOTA) radiology-specific models. Exploring various prompting strategies, we evaluated GPT-4 on a diverse range of common radiology tasks and we found GPT-4 either outperforms or is on par with current SOTA radiology models. With zero-shot prompting, GPT-4 already obtains substantial gains ($\approx$ 10% absolute improvement) over radiology models in temporal sentence similarity classification (accuracy) and natural language inference ($F_1$). For tasks that require learning dataset-specific style or schema (e.g. findings summarisation), GPT-4 improves with example-based prompting and matches supervised SOTA. Our extensive error analysis with a board-certified radiologist shows GPT-4 has a sufficient level of radiology knowledge with only occasional errors in complex context that require nuanced domain knowledge. For findings summarisation, GPT-4 outputs are found to be overall comparable with existing manually-written impressions.

{{</citation>}}


### (128/208) Unveiling the Multi-Annotation Process: Examining the Influence of Annotation Quantity and Instance Difficulty on Model Performance (Pritam Kadasi et al., 2023)

{{<citation>}}

Pritam Kadasi, Mayank Singh. (2023)  
**Unveiling the Multi-Annotation Process: Examining the Influence of Annotation Quantity and Instance Difficulty on Model Performance**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2310.14572v1)  

---


**ABSTRACT**  
The NLP community has long advocated for the construction of multi-annotator datasets to better capture the nuances of language interpretation, subjectivity, and ambiguity. This paper conducts a retrospective study to show how performance scores can vary when a dataset expands from a single annotation per instance to multiple annotations. We propose a novel multi-annotator simulation process to generate datasets with varying annotation budgets. We show that similar datasets with the same annotation budget can lead to varying performance gains. Our findings challenge the popular belief that models trained on multi-annotation examples always lead to better performance than models trained on single or few-annotation examples.

{{</citation>}}


### (129/208) Language Models Hallucinate, but May Excel at Fact Verification (Jian Guan et al., 2023)

{{<citation>}}

Jian Guan, Jesse Dodge, David Wadden, Minlie Huang, Hao Peng. (2023)  
**Language Models Hallucinate, but May Excel at Fact Verification**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, Fact Verification, GPT, GPT-3.5, Language Model, NLP, T5  
[Paper Link](http://arxiv.org/abs/2310.14564v1)  

---


**ABSTRACT**  
Recent progress in natural language processing (NLP) owes much to remarkable advances in large language models (LLMs). Nevertheless, LLMs frequently "hallucinate," resulting in non-factual outputs. Our carefully designed human evaluation substantiates the serious hallucination issue, revealing that even GPT-3.5 produces factual outputs less than 25% of the time. This underscores the importance of fact verifiers in order to measure and incentivize progress. Our systematic investigation affirms that LLMs can be repurposed as effective fact verifiers with strong correlations with human judgments, at least in the Wikipedia domain. Surprisingly, FLAN-T5-11B, the least factual generator in our study, performs the best as a fact verifier, even outperforming more capable LLMs like GPT3.5 and ChatGPT. Delving deeper, we analyze the reliance of these LLMs on high-quality evidence, as well as their deficiencies in robustness and generalization ability. Our study presents insights for developing trustworthy generation models.

{{</citation>}}


### (130/208) NormDial: A Comparable Bilingual Synthetic Dialog Dataset for Modeling Social Norm Adherence and Violation (Oliver Li et al., 2023)

{{<citation>}}

Oliver Li, Mallika Subramanian, Arkadiy Saakyan, Sky CH-Wang, Smaranda Muresan. (2023)  
**NormDial: A Comparable Bilingual Synthetic Dialog Dataset for Modeling Social Norm Adherence and Violation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CY, cs.CL  
Keywords: Dialog  
[Paper Link](http://arxiv.org/abs/2310.14563v2)  

---


**ABSTRACT**  
Social norms fundamentally shape interpersonal communication. We present NormDial, a high-quality dyadic dialogue dataset with turn-by-turn annotations of social norm adherences and violations for Chinese and American cultures. Introducing the task of social norm observance detection, our dataset is synthetically generated in both Chinese and English using a human-in-the-loop pipeline by prompting large language models with a small collection of expert-annotated social norms. We show that our generated dialogues are of high quality through human evaluation and further evaluate the performance of existing large language models on this task. Our findings point towards new directions for understanding the nuances of social norms as they manifest in conversational contexts that span across languages and cultures.

{{</citation>}}


### (131/208) AlpaCare:Instruction-tuned Large Language Models for Medical Application (Xinlu Zhang et al., 2023)

{{<citation>}}

Xinlu Zhang, Chenxin Tian, Xianjun Yang, Lichang Chen, Zekun Li, Linda Ruth Petzold. (2023)  
**AlpaCare:Instruction-tuned Large Language Models for Medical Application**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: LLaMA, Language Model  
[Paper Link](http://arxiv.org/abs/2310.14558v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have demonstrated significant enhancements in instruction-following abilities through instruction tuning, achieving notable performances across various tasks. Previous research has focused on fine-tuning medical domain-specific LLMs using an extensive array of medical-specific data, incorporating millions of pieces of biomedical literature to augment their medical capabilities. However, existing medical instruction-tuned LLMs have been constrained by the limited scope of tasks and instructions available, restricting the efficacy of instruction tuning and adversely affecting performance in the general domain. In this paper, we fine-tune LLaMA-series models using 52k diverse, machine-generated, medical instruction-following data, MedInstruct-52k, resulting in the model AlpaCare. Comprehensive experimental results on both general and medical-specific domain free-form instruction evaluations showcase AlpaCare's strong medical proficiency and generalizability compared to previous instruction-tuned models in both medical and general domains. We provide public access to our MedInstruct-52k dataset and a clinician-crafted free-form instruction test set, MedInstruct-test, along with our codebase, to foster further research and development. Our project page is available at https://github.com/XZhang97666/AlpaCare.

{{</citation>}}


### (132/208) The Skipped Beat: A Study of Sociopragmatic Understanding in LLMs for 64 Languages (Chiyu Zhang et al., 2023)

{{<citation>}}

Chiyu Zhang, Khai Duy Doan, Qisheng Liao, Muhammad Abdul-Mageed. (2023)  
**The Skipped Beat: A Study of Sociopragmatic Understanding in LLMs for 64 Languages**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BLOOM, ChatGPT, GPT, NLP, T5  
[Paper Link](http://arxiv.org/abs/2310.14557v1)  

---


**ABSTRACT**  
Instruction tuned large language models (LLMs), such as ChatGPT, demonstrate remarkable performance in a wide range of tasks. Despite numerous recent studies that examine the performance of instruction-tuned LLMs on various NLP benchmarks, there remains a lack of comprehensive investigation into their ability to understand cross-lingual sociopragmatic meaning (SM), i.e., meaning embedded within social and interactive contexts. This deficiency arises partly from SM not being adequately represented in any of the existing benchmarks. To address this gap, we present SPARROW, an extensive multilingual benchmark specifically designed for SM understanding. SPARROW comprises 169 datasets covering 13 task types across six primary categories (e.g., anti-social language detection, emotion recognition). SPARROW datasets encompass 64 different languages originating from 12 language families representing 16 writing scripts. We evaluate the performance of various multilingual pretrained language models (e.g., mT5) and instruction-tuned LLMs (e.g., BLOOMZ, ChatGPT) on SPARROW through fine-tuning, zero-shot, and/or few-shot learning. Our comprehensive analysis reveals that existing open-source instruction tuned LLMs still struggle to understand SM across various languages, performing close to a random baseline in some cases. We also find that although ChatGPT outperforms many LLMs, it still falls behind task-specific finetuned models with a gap of 12.19 SPARROW score. Our benchmark is available at: https://github.com/UBC-NLP/SPARROW

{{</citation>}}


### (133/208) Harnessing ChatGPT for thematic analysis: Are we ready? (V Vien Lee et al., 2023)

{{<citation>}}

V Vien Lee, Stephanie C. C. van der Lubbe, Lay Hoon Goh, Jose M. Valderas. (2023)  
**Harnessing ChatGPT for thematic analysis: Are we ready?**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2310.14545v2)  

---


**ABSTRACT**  
ChatGPT is an advanced natural language processing tool with growing applications across various disciplines in medical research. Thematic analysis, a qualitative research method to identify and interpret patterns in data, is one application that stands to benefit from this technology. This viewpoint explores the utilization of ChatGPT in three core phases of thematic analysis within a medical context: 1) direct coding of transcripts, 2) generating themes from a predefined list of codes, and 3) preprocessing quotes for manuscript inclusion. Additionally, we explore the potential of ChatGPT to generate interview transcripts, which may be used for training purposes. We assess the strengths and limitations of using ChatGPT in these roles, highlighting areas where human intervention remains necessary. Overall, we argue that ChatGPT can function as a valuable tool during analysis, enhancing the efficiency of the thematic analysis and offering additional insights into the qualitative data.

{{</citation>}}


### (134/208) Evaluating Large Language Models on Controlled Generation Tasks (Jiao Sun et al., 2023)

{{<citation>}}

Jiao Sun, Yufei Tian, Wangchunshu Zhou, Nan Xu, Qian Hu, Rahul Gupta, John Frederick Wieting, Nanyun Peng, Xuezhe Ma. (2023)  
**Evaluating Large Language Models on Controlled Generation Tasks**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.14542v1)  

---


**ABSTRACT**  
While recent studies have looked into the abilities of large language models in various benchmark tasks, including question generation, reading comprehension, multilingual and etc, there have been few studies looking into the controllability of large language models on generation tasks. We present an extensive analysis of various benchmarks including a sentence planning benchmark with different granularities. After comparing large language models against state-of-the-start finetuned smaller models, we present a spectrum showing large language models falling behind, are comparable, or exceed the ability of smaller models. We conclude that **large language models struggle at meeting fine-grained hard constraints**.

{{</citation>}}


### (135/208) Continual Named Entity Recognition without Catastrophic Forgetting (Duzhen Zhang et al., 2023)

{{<citation>}}

Duzhen Zhang, Wei Cong, Jiahua Dong, Yahan Yu, Xiuyi Chen, Yonggang Zhang, Zhen Fang. (2023)  
**Continual Named Entity Recognition without Catastrophic Forgetting**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NER, Named Entity Recognition  
[Paper Link](http://arxiv.org/abs/2310.14541v1)  

---


**ABSTRACT**  
Continual Named Entity Recognition (CNER) is a burgeoning area, which involves updating an existing model by incorporating new entity types sequentially. Nevertheless, continual learning approaches are often severely afflicted by catastrophic forgetting. This issue is intensified in CNER due to the consolidation of old entity types from previous steps into the non-entity type at each step, leading to what is known as the semantic shift problem of the non-entity type. In this paper, we introduce a pooled feature distillation loss that skillfully navigates the trade-off between retaining knowledge of old entity types and acquiring new ones, thereby more effectively mitigating the problem of catastrophic forgetting. Additionally, we develop a confidence-based pseudo-labeling for the non-entity type, \emph{i.e.,} predicting entity types using the old model to handle the semantic shift of the non-entity type. Following the pseudo-labeling process, we suggest an adaptive re-weighting type-balanced learning strategy to handle the issue of biased type distribution. We carried out comprehensive experiments on ten CNER settings using three different datasets. The results illustrate that our method significantly outperforms prior state-of-the-art approaches, registering an average improvement of $6.3$\% and $8.0$\% in Micro and Macro F1 scores, respectively.

{{</citation>}}


### (136/208) Evaluating Spatial Understanding of Large Language Models (Yutaro Yamada et al., 2023)

{{<citation>}}

Yutaro Yamada, Yihan Bao, Andrew K. Lampinen, Jungo Kasai, Ilker Yildirim. (2023)  
**Evaluating Spatial Understanding of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT, GPT-3.5, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2310.14540v1)  

---


**ABSTRACT**  
Large language models (LLMs) show remarkable capabilities across a variety of tasks. Despite the models only seeing text in training, several recent studies suggest that LLM representations implicitly capture aspects of the underlying grounded concepts. Here, we explore LLM representations of a particularly salient kind of grounded knowledge -- spatial relationships. We design natural-language navigation tasks and evaluate the ability of LLMs, in particular GPT-3.5-turbo, GPT-4, and Llama2 series models, to represent and reason about spatial structures, and compare these abilities to human performance on the same tasks. These tasks reveal substantial variability in LLM performance across different spatial structures, including square, hexagonal, and triangular grids, rings, and trees. We also discover that, similar to humans, LLMs utilize object names as landmarks for maintaining spatial maps. Finally, in extensive error analysis, we find that LLMs' mistakes reflect both spatial and non-spatial factors. These findings suggest that LLMs appear to capture certain aspects of spatial structure implicitly, but room for improvement remains.

{{</citation>}}


### (137/208) Improving Seq2Seq Grammatical Error Correction via Decoding Interventions (Houquan Zhou et al., 2023)

{{<citation>}}

Houquan Zhou, Yumeng Liu, Zhenghua Li, Min Zhang, Bo Zhang, Chen Li, Ji Zhang, Fei Huang. (2023)  
**Improving Seq2Seq Grammatical Error Correction via Decoding Interventions**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Seq2Seq  
[Paper Link](http://arxiv.org/abs/2310.14534v1)  

---


**ABSTRACT**  
The sequence-to-sequence (Seq2Seq) approach has recently been widely used in grammatical error correction (GEC) and shows promising performance. However, the Seq2Seq GEC approach still suffers from two issues. First, a Seq2Seq GEC model can only be trained on parallel data, which, in GEC task, is often noisy and limited in quantity. Second, the decoder of a Seq2Seq GEC model lacks an explicit awareness of the correctness of the token being generated. In this paper, we propose a unified decoding intervention framework that employs an external critic to assess the appropriateness of the token to be generated incrementally, and then dynamically influence the choice of the next token. We discover and investigate two types of critics: a pre-trained left-to-right language model critic and an incremental target-side grammatical error detector critic. Through extensive experiments on English and Chinese datasets, our framework consistently outperforms strong baselines and achieves results competitive with state-of-the-art methods.

{{</citation>}}


### (138/208) Dual-Feedback Knowledge Retrieval for Task-Oriented Dialogue Systems (Tianyuan Shi et al., 2023)

{{<citation>}}

Tianyuan Shi, Liangzhi Li, Zijian Lin, Tao Yang, Xiaojun Quan, Qifan Wang. (2023)  
**Dual-Feedback Knowledge Retrieval for Task-Oriented Dialogue Systems**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue  
[Paper Link](http://arxiv.org/abs/2310.14528v1)  

---


**ABSTRACT**  
Efficient knowledge retrieval plays a pivotal role in ensuring the success of end-to-end task-oriented dialogue systems by facilitating the selection of relevant information necessary to fulfill user requests. However, current approaches generally integrate knowledge retrieval and response generation, which poses scalability challenges when dealing with extensive knowledge bases. Taking inspiration from open-domain question answering, we propose a retriever-generator architecture that harnesses a retriever to retrieve pertinent knowledge and a generator to generate system responses.~Due to the lack of retriever training labels, we propose relying on feedback from the generator as pseudo-labels to train the retriever. To achieve this, we introduce a dual-feedback mechanism that generates both positive and negative feedback based on the output of the generator. Our method demonstrates superior performance in task-oriented dialogue tasks, as evidenced by experimental results on three benchmark datasets.

{{</citation>}}


### (139/208) Turn-Level Active Learning for Dialogue State Tracking (Zihan Zhang et al., 2023)

{{<citation>}}

Zihan Zhang, Meng Fang, Fanghua Ye, Ling Chen, Mohammad-Reza Namazi-Rad. (2023)  
**Turn-Level Active Learning for Dialogue State Tracking**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Active Learning, Dialog, Dialogue  
[Paper Link](http://arxiv.org/abs/2310.14513v1)  

---


**ABSTRACT**  
Dialogue state tracking (DST) plays an important role in task-oriented dialogue systems. However, collecting a large amount of turn-by-turn annotated dialogue data is costly and inefficient. In this paper, we propose a novel turn-level active learning framework for DST to actively select turns in dialogues to annotate. Given the limited labelling budget, experimental results demonstrate the effectiveness of selective annotation of dialogue turns. Additionally, our approach can effectively achieve comparable DST performance to traditional training approaches with significantly less annotated data, which provides a more efficient way to annotate new dialogue data.

{{</citation>}}


### (140/208) CITB: A Benchmark for Continual Instruction Tuning (Zihan Zhang et al., 2023)

{{<citation>}}

Zihan Zhang, Meng Fang, Ling Chen, Mohammad-Reza Namazi-Rad. (2023)  
**CITB: A Benchmark for Continual Instruction Tuning**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, NLP  
[Paper Link](http://arxiv.org/abs/2310.14510v1)  

---


**ABSTRACT**  
Continual learning (CL) is a paradigm that aims to replicate the human ability to learn and accumulate knowledge continually without forgetting previous knowledge and transferring it to new tasks. Recent instruction tuning (IT) involves fine-tuning models to make them more adaptable to solving NLP tasks in general. However, it is still uncertain how instruction tuning works in the context of CL tasks. This challenging yet practical problem is formulated as Continual Instruction Tuning (CIT). In this work, we establish a CIT benchmark consisting of learning and evaluation protocols. We curate two long dialogue task streams of different types, InstrDialog and InstrDialog++, to study various CL methods systematically. Our experiments show that existing CL methods do not effectively leverage the rich natural language instructions, and fine-tuning an instruction-tuned model sequentially can yield similar or better results. We further explore different aspects that might affect the learning of CIT. We hope this benchmark will facilitate more research in this direction.

{{</citation>}}


### (141/208) EXPLAIN, EDIT, GENERATE: Rationale-Sensitive Counterfactual Data Augmentation for Multi-hop Fact Verification (Yingjie Zhu et al., 2023)

{{<citation>}}

Yingjie Zhu, Jiasheng Si, Yibo Zhao, Haiyang Zhu, Deyu Zhou, Yulan He. (2023)  
**EXPLAIN, EDIT, GENERATE: Rationale-Sensitive Counterfactual Data Augmentation for Multi-hop Fact Verification**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, Augmentation, Fact Verification, NER  
[Paper Link](http://arxiv.org/abs/2310.14508v1)  

---


**ABSTRACT**  
Automatic multi-hop fact verification task has gained significant attention in recent years. Despite impressive results, these well-designed models perform poorly on out-of-domain data. One possible solution is to augment the training data with counterfactuals, which are generated by minimally altering the causal features of the original data. However, current counterfactual data augmentation techniques fail to handle multi-hop fact verification due to their incapability to preserve the complex logical relationships within multiple correlated texts. In this paper, we overcome this limitation by developing a rationale-sensitive method to generate linguistically diverse and label-flipping counterfactuals while preserving logical relationships. In specific, the diverse and fluent counterfactuals are generated via an Explain-Edit-Generate architecture. Moreover, the checking and filtering modules are proposed to regularize the counterfactual data with logical relations and flipped labels. Experimental results show that the proposed approach outperforms the SOTA baselines and can generate linguistically diverse counterfactual data without disrupting their logical relationships.

{{</citation>}}


### (142/208) Sentiment analysis with adaptive multi-head attention in Transformer (Fanfei Meng et al., 2023)

{{<citation>}}

Fanfei Meng, David Demeter. (2023)  
**Sentiment analysis with adaptive multi-head attention in Transformer**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2310.14505v1)  

---


**ABSTRACT**  
We propose a novel framework based on the attention mechanism to identify the sentiment of a movie review document. Previous efforts on deep neural networks with attention mechanisms focus on encoder and decoder with fixed numbers of multi-head attention. Therefore, we need a mechanism to stop the attention process automatically if no more useful information can be read from the memory.In this paper, we propose an adaptive multi-head attention architecture (AdaptAttn) which varies the number of attention heads based on length of sentences. AdaptAttn has a data preprocessing step where each document is classified into any one of the three bins small, medium or large based on length of the sentence. The document classified as small goes through two heads in each layer, the medium group passes four heads and the large group is processed by eight heads. We examine the merit of our model on the Stanford large movie review dataset. The experimental results show that the F1 score from our model is on par with the baseline model.

{{</citation>}}


### (143/208) Diversify Question Generation with Retrieval-Augmented Style Transfer (Qi Gou et al., 2023)

{{<citation>}}

Qi Gou, Zehua Xia, Bowen Yu, Haiyang Yu, Fei Huang, Yongbin Li, Nguyen Cam-Tu. (2023)  
**Diversify Question Generation with Retrieval-Augmented Style Transfer**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: QA, Question Generation, Reinforcement Learning, Style Transfer  
[Paper Link](http://arxiv.org/abs/2310.14503v1)  

---


**ABSTRACT**  
Given a textual passage and an answer, humans are able to ask questions with various expressions, but this ability is still challenging for most question generation (QG) systems. Existing solutions mainly focus on the internal knowledge within the given passage or the semantic word space for diverse content planning. These methods, however, have not considered the potential of external knowledge for expression diversity. To bridge this gap, we propose RAST, a framework for Retrieval-Augmented Style Transfer, where the objective is to utilize the style of diverse templates for question generation. For training RAST, we develop a novel Reinforcement Learning (RL) based approach that maximizes a weighted combination of diversity reward and consistency reward. Here, the consistency reward is computed by a Question-Answering (QA) model, whereas the diversity reward measures how much the final output mimics the retrieved template. Experimental results show that our method outperforms previous diversity-driven baselines on diversity while being comparable in terms of consistency scores. Our code is available at https://github.com/gouqi666/RAST.

{{</citation>}}


### (144/208) InstructExcel: A Benchmark for Natural Language Instruction in Excel (Justin Payan et al., 2023)

{{<citation>}}

Justin Payan, Swaroop Mishra, Mukul Singh, Carina Negreanu, Christian Poelitz, Chitta Baral, Subhro Roy, Rasika Chakravarthy, Benjamin Van Durme, Elnaz Nouri. (2023)  
**InstructExcel: A Benchmark for Natural Language Instruction in Excel**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT, GPT-3.5, GPT-4, Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2310.14495v1)  

---


**ABSTRACT**  
With the evolution of Large Language Models (LLMs) we can solve increasingly more complex NLP tasks across various domains, including spreadsheets. This work investigates whether LLMs can generate code (Excel OfficeScripts, a TypeScript API for executing many tasks in Excel) that solves Excel specific tasks provided via natural language user instructions. To do so we introduce a new large-scale benchmark, InstructExcel, created by leveraging the 'Automate' feature in Excel to automatically generate OfficeScripts from users' actions. Our benchmark includes over 10k samples covering 170+ Excel operations across 2,000 publicly available Excel spreadsheets. Experiments across various zero-shot and few-shot settings show that InstructExcel is a hard benchmark for state of the art models like GPT-4. We observe that (1) using GPT-4 over GPT-3.5, (2) providing more in-context examples, and (3) dynamic prompting can help improve performance on this benchmark.

{{</citation>}}


### (145/208) Towards a Mechanistic Interpretation of Multi-Step Reasoning Capabilities of Language Models (Yifan Hou et al., 2023)

{{<citation>}}

Yifan Hou, Jiaoda Li, Yu Fei, Alessandro Stolfo, Wangchunshu Zhou, Guangtao Zeng, Antoine Bosselut, Mrinmaya Sachan. (2023)  
**Towards a Mechanistic Interpretation of Multi-Step Reasoning Capabilities of Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, GPT, LLaMA, Language Model, Reasoning  
[Paper Link](http://arxiv.org/abs/2310.14491v1)  

---


**ABSTRACT**  
Recent work has shown that language models (LMs) have strong multi-step (i.e., procedural) reasoning capabilities. However, it is unclear whether LMs perform these tasks by cheating with answers memorized from pretraining corpus, or, via a multi-step reasoning mechanism. In this paper, we try to answer this question by exploring a mechanistic interpretation of LMs for multi-step reasoning tasks. Concretely, we hypothesize that the LM implicitly embeds a reasoning tree resembling the correct reasoning process within it. We test this hypothesis by introducing a new probing approach (called MechanisticProbe) that recovers the reasoning tree from the model's attention patterns. We use our probe to analyze two LMs: GPT-2 on a synthetic task (k-th smallest element), and LLaMA on two simple language-based reasoning tasks (ProofWriter & AI2 Reasoning Challenge). We show that MechanisticProbe is able to detect the information of the reasoning tree from the model's attentions for most examples, suggesting that the LM indeed is going through a process of multi-step reasoning within its architecture in many cases.

{{</citation>}}


### (146/208) DetectGPT-SC: Improving Detection of Text Generated by Large Language Models through Self-Consistency with Masked Predictions (Rongsheng Wang et al., 2023)

{{<citation>}}

Rongsheng Wang, Qi Li, Sihong Xie. (2023)  
**DetectGPT-SC: Improving Detection of Text Generated by Large Language Models through Self-Consistency with Masked Predictions**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2310.14479v1)  

---


**ABSTRACT**  
General large language models (LLMs) such as ChatGPT have shown remarkable success, but it has also raised concerns among people about the misuse of AI-generated texts. Therefore, an important question is how to detect whether the texts are generated by ChatGPT or by humans. Existing detectors are built on the assumption that there is a distribution gap between human-generated and AI-generated texts. These gaps are typically identified using statistical information or classifiers. In contrast to prior research methods, we find that large language models such as ChatGPT exhibit strong self-consistency in text generation and continuation. Self-consistency capitalizes on the intuition that AI-generated texts can still be reasoned with by large language models using the same logical reasoning when portions of the texts are masked, which differs from human-generated texts. Using this observation, we subsequently proposed a new method for AI-generated texts detection based on self-consistency with masked predictions to determine whether a text is generated by LLMs. This method, which we call DetectGPT-SC. We conducted a series of experiments to evaluate the performance of DetectGPT-SC. In these experiments, we employed various mask scheme, zero-shot, and simple prompt for completing masked texts and self-consistency predictions. The results indicate that DetectGPT-SC outperforms the current state-of-the-art across different tasks.

{{</citation>}}


### (147/208) GeoLM: Empowering Language Models for Geospatially Grounded Language Understanding (Zekun Li et al., 2023)

{{<citation>}}

Zekun Li, Wenxuan Zhou, Yao-Yi Chiang, Muhao Chen. (2023)  
**GeoLM: Empowering Language Models for Geospatially Grounded Language Understanding**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.14478v1)  

---


**ABSTRACT**  
Humans subconsciously engage in geospatial reasoning when reading articles. We recognize place names and their spatial relations in text and mentally associate them with their physical locations on Earth. Although pretrained language models can mimic this cognitive process using linguistic context, they do not utilize valuable geospatial information in large, widely available geographical databases, e.g., OpenStreetMap. This paper introduces GeoLM, a geospatially grounded language model that enhances the understanding of geo-entities in natural language. GeoLM leverages geo-entity mentions as anchors to connect linguistic information in text corpora with geospatial information extracted from geographical databases. GeoLM connects the two types of context through contrastive learning and masked language modeling. It also incorporates a spatial coordinate embedding mechanism to encode distance and direction relations to capture geospatial context. In the experiment, we demonstrate that GeoLM exhibits promising capabilities in supporting toponym recognition, toponym linking, relation extraction, and geo-entity typing, which bridge the gap between natural language processing and geospatial sciences. The code is publicly available at https://github.com/knowledge-computing/geolm.

{{</citation>}}


## eess.IV (2)



### (148/208) Vicinal Feature Statistics Augmentation for Federated 3D Medical Volume Segmentation (Yongsong Huang et al., 2023)

{{<citation>}}

Yongsong Huang, Wanqing Xie, Mingzhen Li, Mingmei Cheng, Jinzhou Wu, Weixiao Wang, Jane You, Xiaofeng Liu. (2023)  
**Vicinal Feature Statistics Augmentation for Federated 3D Medical Volume Segmentation**  

---
Primary Category: eess.IV  
Categories: cs-AI, cs-CV, cs-LG, eess-IV, eess.IV, physics-med-ph  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2310.15371v1)  

---


**ABSTRACT**  
Federated learning (FL) enables multiple client medical institutes collaboratively train a deep learning (DL) model with privacy protection. However, the performance of FL can be constrained by the limited availability of labeled data in small institutes and the heterogeneous (i.e., non-i.i.d.) data distribution across institutes. Though data augmentation has been a proven technique to boost the generalization capabilities of conventional centralized DL as a "free lunch", its application in FL is largely underexplored. Notably, constrained by costly labeling, 3D medical segmentation generally relies on data augmentation. In this work, we aim to develop a vicinal feature-level data augmentation (VFDA) scheme to efficiently alleviate the local feature shift and facilitate collaborative training for privacy-aware FL segmentation. We take both the inner- and inter-institute divergence into consideration, without the need for cross-institute transfer of raw data or their mixup. Specifically, we exploit the batch-wise feature statistics (e.g., mean and standard deviation) in each institute to abstractly represent the discrepancy of data, and model each feature statistic probabilistically via a Gaussian prototype, with the mean corresponding to the original statistic and the variance quantifying the augmentation scope. From the vicinal risk minimization perspective, novel feature statistics can be drawn from the Gaussian distribution to fulfill augmentation. The variance is explicitly derived by the data bias in each individual institute and the underlying feature statistics characterized by all participating institutes. The added-on VFDA consistently yielded marked improvements over six advanced FL methods on both 3D brain tumor and cardiac segmentation.

{{</citation>}}


### (149/208) StenUNet: Automatic Stenosis Detection from X-ray Coronary Angiography (Hui Lin et al., 2023)

{{<citation>}}

Hui Lin, Tom Liu, Aggelos Katsaggelos, Adrienne Kline. (2023)  
**StenUNet: Automatic Stenosis Detection from X-ray Coronary Angiography**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.14961v1)  

---


**ABSTRACT**  
Coronary angiography continues to serve as the primary method for diagnosing coronary artery disease (CAD), which is the leading global cause of mortality. The severity of CAD is quantified by the location, degree of narrowing (stenosis), and number of arteries involved. In current practice, this quantification is performed manually using visual inspection and thus suffers from poor inter- and intra-rater reliability. The MICCAI grand challenge: Automatic Region-based Coronary Artery Disease diagnostics using the X-ray angiography imagEs (ARCADE) curated a dataset with stenosis annotations, with the goal of creating an automated stenosis detection algorithm. Using a combination of machine learning and other computer vision techniques, we propose the architecture and algorithm StenUNet to accurately detect stenosis from X-ray Coronary Angiography. Our submission to the ARCADE challenge placed 3rd among all teams. We achieved an F1 score of 0.5348 on the test set, 0.0005 lower than the 2nd place.

{{</citation>}}


## cs.AI (7)



### (150/208) Moral Foundations of Large Language Models (Marwa Abdulhai et al., 2023)

{{<citation>}}

Marwa Abdulhai, Gregory Serapio-Garcia, Clément Crepy, Daria Valter, John Canny, Natasha Jaques. (2023)  
**Moral Foundations of Large Language Models**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-CY, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.15337v1)  

---


**ABSTRACT**  
Moral foundations theory (MFT) is a psychological assessment tool that decomposes human moral reasoning into five factors, including care/harm, liberty/oppression, and sanctity/degradation (Graham et al., 2009). People vary in the weight they place on these dimensions when making moral decisions, in part due to their cultural upbringing and political ideology. As large language models (LLMs) are trained on datasets collected from the internet, they may reflect the biases that are present in such corpora. This paper uses MFT as a lens to analyze whether popular LLMs have acquired a bias towards a particular set of moral values. We analyze known LLMs and find they exhibit particular moral foundations, and show how these relate to human moral foundations and political affiliations. We also measure the consistency of these biases, or whether they vary strongly depending on the context of how the model is prompted. Finally, we show that we can adversarially select prompts that encourage the moral to exhibit a particular set of moral foundations, and that this can affect the model's behavior on downstream tasks. These findings help illustrate the potential risks and unintended consequences of LLMs assuming a particular moral stance.

{{</citation>}}


### (151/208) Systematic AI Approach for AGI: Addressing Alignment, Energy, and AGI Grand Challenges (Eren Kurshan, 2023)

{{<citation>}}

Eren Kurshan. (2023)  
**Systematic AI Approach for AGI: Addressing Alignment, Energy, and AGI Grand Challenges**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15274v1)  

---


**ABSTRACT**  
AI faces a trifecta of grand challenges the Energy Wall, the Alignment Problem and the Leap from Narrow AI to AGI. Contemporary AI solutions consume unsustainable amounts of energy during model training and daily operations.Making things worse, the amount of computation required to train each new AI model has been doubling every 2 months since 2020, directly translating to increases in energy consumption.The leap from AI to AGI requires multiple functional subsystems operating in a balanced manner, which requires a system architecture. However, the current approach to artificial intelligence lacks system design; even though system characteristics play a key role in the human brain from the way it processes information to how it makes decisions. Similarly, current alignment and AI ethics approaches largely ignore system design, yet studies show that the brains system architecture plays a critical role in healthy moral decisions.In this paper, we argue that system design is critically important in overcoming all three grand challenges. We posit that system design is the missing piece in overcoming the grand challenges.We present a Systematic AI Approach for AGI that utilizes system design principles for AGI, while providing ways to overcome the energy wall and the alignment challenges.

{{</citation>}}


### (152/208) Open-Ended Instructable Embodied Agents with Memory-Augmented Large Language Models (Gabriel Sarch et al., 2023)

{{<citation>}}

Gabriel Sarch, Yue Wu, Michael J. Tarr, Katerina Fragkiadaki. (2023)  
**Open-Ended Instructable Embodied Agents with Memory-Augmented Large Language Models**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-LG, cs-RO, cs.AI  
Keywords: Dialog, Dialogue, Language Model  
[Paper Link](http://arxiv.org/abs/2310.15127v1)  

---


**ABSTRACT**  
Pre-trained and frozen LLMs can effectively map simple scene re-arrangement instructions to programs over a robot's visuomotor functions through appropriate few-shot example prompting. To parse open-domain natural language and adapt to a user's idiosyncratic procedures, not known during prompt engineering time, fixed prompts fall short. In this paper, we introduce HELPER, an embodied agent equipped with an external memory of language-program pairs that parses free-form human-robot dialogue into action programs through retrieval-augmented LLM prompting: relevant memories are retrieved based on the current dialogue, instruction, correction or VLM description, and used as in-context prompt examples for LLM querying. The memory is expanded during deployment to include pairs of user's language and action plans, to assist future inferences and personalize them to the user's language and routines. HELPER sets a new state-of-the-art in the TEACh benchmark in both Execution from Dialog History (EDH) and Trajectory from Dialogue (TfD), with 1.7x improvement over the previous SOTA for TfD. Our models, code and video results can be found in our project's website: https://helper-agent-llm.github.io.

{{</citation>}}


### (153/208) Causal Inference Using LLM-Guided Discovery (Aniket Vashishtha et al., 2023)

{{<citation>}}

Aniket Vashishtha, Abbavaram Gowtham Reddy, Abhinav Kumar, Saketh Bachu, Vineeth N Balasubramanian, Amit Sharma. (2023)  
**Causal Inference Using LLM-Guided Discovery**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: GPT, GPT-3.5, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2310.15117v1)  

---


**ABSTRACT**  
At the core of causal inference lies the challenge of determining reliable causal graphs solely based on observational data. Since the well-known backdoor criterion depends on the graph, any errors in the graph can propagate downstream to effect inference. In this work, we initially show that complete graph information is not necessary for causal effect inference; the topological order over graph variables (causal order) alone suffices. Further, given a node pair, causal order is easier to elicit from domain experts compared to graph edges since determining the existence of an edge can depend extensively on other variables. Interestingly, we find that the same principle holds for Large Language Models (LLMs) such as GPT-3.5-turbo and GPT-4, motivating an automated method to obtain causal order (and hence causal effect) with LLMs acting as virtual domain experts. To this end, we employ different prompting strategies and contextual cues to propose a robust technique of obtaining causal order from LLMs. Acknowledging LLMs' limitations, we also study possible techniques to integrate LLMs with established causal discovery algorithms, including constraint-based and score-based methods, to enhance their performance. Extensive experiments demonstrate that our approach significantly improves causal ordering accuracy as compared to discovery algorithms, highlighting the potential of LLMs to enhance causal inference across diverse fields.

{{</citation>}}


### (154/208) Universal Knowledge Graph Embeddings (N'Dah Jean Kouagou et al., 2023)

{{<citation>}}

N'Dah Jean Kouagou, Caglar Demir, Hamada M. Zahera, Adrian Wilke, Stefan Heindorf, Jiayi Li, Axel-Cyrille Ngonga Ngomo. (2023)  
**Universal Knowledge Graph Embeddings**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Embedding, Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2310.14899v1)  

---


**ABSTRACT**  
A variety of knowledge graph embedding approaches have been developed. Most of them obtain embeddings by learning the structure of the knowledge graph within a link prediction setting. As a result, the embeddings reflect only the semantics of a single knowledge graph, and embeddings for different knowledge graphs are not aligned, e.g., they cannot be used to find similar entities across knowledge graphs via nearest neighbor search. However, knowledge graph embedding applications such as entity disambiguation require a more global representation, i.e., a representation that is valid across multiple sources. We propose to learn universal knowledge graph embeddings from large-scale interlinked knowledge sources. To this end, we fuse large knowledge graphs based on the owl:sameAs relation such that every entity is represented by a unique identity. We instantiate our idea by computing universal embeddings based on DBpedia and Wikidata yielding embeddings for about 180 million entities, 15 thousand relations, and 1.2 billion triples. Moreover, we develop a convenient API to provide embeddings as a service. Experiments on link prediction show that universal knowledge graph embeddings encode better semantics compared to embeddings computed on a single knowledge graph. For reproducibility purposes, we provide our source code and datasets open access at https://github.com/dice-group/Universal_Embeddings

{{</citation>}}


### (155/208) Local Universal Rule-based Explanations (Szymon Bobek et al., 2023)

{{<citation>}}

Szymon Bobek, Grzegorz J. Nalepa. (2023)  
**Local Universal Rule-based Explanations**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.14894v1)  

---


**ABSTRACT**  
Explainable artificial intelligence (XAI) is one of the most intensively developed are of AI in recent years. It is also one of the most fragmented one with multiple methods that focus on different aspects of explanations. This makes difficult to obtain the full spectrum of explanation at once in a compact and consistent way. To address this issue, we present Local Universal Explainer (LUX) that is a rule-based explainer which can generate factual, counterfactual and visual explanations. It is based on a modified version of decision tree algorithms that allows for oblique splits and integration with feature importance XAI methods such as SHAP or LIME. It does not use data generation in opposite to other algorithms, but is focused on selecting local concepts in a form of high-density clusters of real data that have the highest impact on forming the decision boundary of the explained model. We tested our method on real and synthetic datasets and compared it with state-of-the-art rule-based explainers such as LORE, EXPLAN and Anchor. Our method outperforms currently existing approaches in terms of simplicity, global fidelity and representativeness.

{{</citation>}}


### (156/208) A Study on Knowledge Graph Embeddings and Graph Neural Networks for Web Of Things (Rohith Teja Mittakola et al., 2023)

{{<citation>}}

Rohith Teja Mittakola, Thomas Hassan. (2023)  
**A Study on Knowledge Graph Embeddings and Graph Neural Networks for Web Of Things**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: Embedding, GNN, Graph Neural Network, Graph Neural Networks, Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2310.14866v1)  

---


**ABSTRACT**  
Graph data structures are widely used to store relational information between several entities. With data being generated worldwide on a large scale, we see a significant growth in the generation of knowledge graphs. Thing in the future is Orange's take on a knowledge graph in the domain of the Web Of Things (WoT), where the main objective of the platform is to provide a digital representation of the physical world and enable cross-domain applications to be built upon this massive and highly connected graph of things. In this context, as the knowledge graph grows in size, it is prone to have noisy and messy data. In this paper, we explore state-of-the-art knowledge graph embedding (KGE) methods to learn numerical representations of the graph entities and, subsequently, explore downstream tasks like link prediction, node classification, and triple classification. We also investigate Graph neural networks (GNN) alongside KGEs and compare their performance on the same downstream tasks. Our evaluation highlights the encouraging performance of both KGE and GNN-based methods on node classification, and the superiority of GNN approaches in the link prediction task. Overall, we show that state-of-the-art approaches are relevant in a WoT context, and this preliminary work provides insights to implement and evaluate them in this context.

{{</citation>}}


## stat.ML (4)



### (157/208) Unsupervised Federated Learning: A Federated Gradient EM Algorithm for Heterogeneous Mixture Models with Robustness against Adversarial Attacks (Ye Tian et al., 2023)

{{<citation>}}

Ye Tian, Haolei Weng, Yang Feng. (2023)  
**Unsupervised Federated Learning: A Federated Gradient EM Algorithm for Heterogeneous Mixture Models with Robustness against Adversarial Attacks**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: Adversarial Attack  
[Paper Link](http://arxiv.org/abs/2310.15330v1)  

---


**ABSTRACT**  
While supervised federated learning approaches have enjoyed significant success, the domain of unsupervised federated learning remains relatively underexplored. In this paper, we introduce a novel federated gradient EM algorithm designed for the unsupervised learning of mixture models with heterogeneous mixture proportions across tasks. We begin with a comprehensive finite-sample theory that holds for general mixture models, then apply this general theory on Gaussian Mixture Models (GMMs) and Mixture of Regressions (MoRs) to characterize the explicit estimation error of model parameters and mixture proportions. Our proposed federated gradient EM algorithm demonstrates several key advantages: adaptability to unknown task similarity, resilience against adversarial attacks on a small fraction of data sources, protection of local data privacy, and computational and communication efficiency.

{{</citation>}}


### (158/208) A Doubly Robust Approach to Sparse Reinforcement Learning (Wonyoung Kim et al., 2023)

{{<citation>}}

Wonyoung Kim, Garud Iyengar, Assaf Zeevi. (2023)  
**A Doubly Robust Approach to Sparse Reinforcement Learning**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.15286v1)  

---


**ABSTRACT**  
We propose a new regret minimization algorithm for episodic sparse linear Markov decision process (SMDP) where the state-transition distribution is a linear function of observed features. The only previously known algorithm for SMDP requires the knowledge of the sparsity parameter and oracle access to an unknown policy. We overcome these limitations by combining the doubly robust method that allows one to use feature vectors of \emph{all} actions with a novel analysis technique that enables the algorithm to use data from all periods in all episodes. The regret of the proposed algorithm is $\tilde{O}(\sigma^{-1}_{\min} s_{\star} H \sqrt{N})$, where $\sigma_{\min}$ denotes the restrictive the minimum eigenvalue of the average Gram matrix of feature vectors, $s_\star$ is the sparsity parameter, $H$ is the length of an episode, and $N$ is the number of rounds. We provide a lower regret bound that matches the upper bound up to logarithmic factors on a newly identified subclass of SMDPs. Our numerical experiments support our theoretical results and demonstrate the superior performance of our algorithm.

{{</citation>}}


### (159/208) UncertaintyPlayground: A Fast and Simplified Python Library for Uncertainty Estimation (Ilia Azizi, 2023)

{{<citation>}}

Ilia Azizi. (2023)  
**UncertaintyPlayground: A Fast and Simplified Python Library for Uncertainty Estimation**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2310.15281v1)  

---


**ABSTRACT**  
This paper introduces UncertaintyPlayground, a Python library built on PyTorch and GPyTorch for uncertainty estimation in supervised learning tasks. The library offers fast training for Gaussian and multi-modal outcome distributions through Sparse and Variational Gaussian Process Regressions (SVGPRs) for normally distributed outcomes and Mixed Density Networks (MDN) for mixed distributions. In addition to model training with various hyperparameters, UncertaintyPlayground can visualize the prediction intervals of one or more instances. Due to using tensor operations, the library can be trained both on CPU and GPU and offers various PyTorch-specific techniques for speed optimization. The library contains unit tests for each module and ensures multi-platform continuous integration with GitHub Workflows (online integration) and Tox (local integration). Finally, the code is documented with Google-style docstrings and offers a documentation website created with MkDocs and MkDocStrings.

{{</citation>}}


### (160/208) CAD-DA: Controllable Anomaly Detection after Domain Adaptation by Statistical Inference (Vo Nguyen Le Duy et al., 2023)

{{<citation>}}

Vo Nguyen Le Duy, Hsuan-Tien Lin, Ichiro Takeuchi. (2023)  
**CAD-DA: Controllable Anomaly Detection after Domain Adaptation by Statistical Inference**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2310.14608v1)  

---


**ABSTRACT**  
We propose a novel statistical method for testing the results of anomaly detection (AD) under domain adaptation (DA), which we call CAD-DA -- controllable AD under DA. The distinct advantage of the CAD-DA lies in its ability to control the probability of misidentifying anomalies under a pre-specified level $\alpha$ (e.g., 0.05). The challenge within this DA setting is the necessity to account for the influence of DA to ensure the validity of the inference results. Our solution to this challenge leverages the concept of conditional Selective Inference to handle the impact of DA. To our knowledge, this is the first work capable of conducting a valid statistical inference within the context of DA. We evaluate the performance of the CAD-DA method on both synthetic and real-world datasets.

{{</citation>}}


## cs.CV (24)



### (161/208) LXMERT Model Compression for Visual Question Answering (Maryam Hashemi et al., 2023)

{{<citation>}}

Maryam Hashemi, Ghazaleh Mahmoudi, Sara Kodeiri, Hadi Sheikhi, Sauleh Eetemadi. (2023)  
**LXMERT Model Compression for Visual Question Answering**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs-LG, cs.CV  
Keywords: NLP, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2310.15325v1)  

---


**ABSTRACT**  
Large-scale pretrained models such as LXMERT are becoming popular for learning cross-modal representations on text-image pairs for vision-language tasks. According to the lottery ticket hypothesis, NLP and computer vision models contain smaller subnetworks capable of being trained in isolation to full performance. In this paper, we combine these observations to evaluate whether such trainable subnetworks exist in LXMERT when fine-tuned on the VQA task. In addition, we perform a model size cost-benefit analysis by investigating how much pruning can be done without significant loss in accuracy. Our experiment results demonstrate that LXMERT can be effectively pruned by 40%-60% in size with 3% loss in accuracy.

{{</citation>}}


### (162/208) Large Language Models are Visual Reasoning Coordinators (Liangyu Chen et al., 2023)

{{<citation>}}

Liangyu Chen, Bo Li, Sheng Shen, Jingkang Yang, Chunyuan Li, Kurt Keutzer, Trevor Darrell, Ziwei Liu. (2023)  
**Large Language Models are Visual Reasoning Coordinators**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs.CV  
Keywords: Language Model, QA, Reasoning  
[Paper Link](http://arxiv.org/abs/2310.15166v1)  

---


**ABSTRACT**  
Visual reasoning requires multimodal perception and commonsense cognition of the world. Recently, multiple vision-language models (VLMs) have been proposed with excellent commonsense reasoning ability in various domains. However, how to harness the collective power of these complementary VLMs is rarely explored. Existing methods like ensemble still struggle to aggregate these models with the desired higher-order communications. In this work, we propose Cola, a novel paradigm that coordinates multiple VLMs for visual reasoning. Our key insight is that a large language model (LLM) can efficiently coordinate multiple VLMs by facilitating natural language communication that leverages their distinct and complementary capabilities. Extensive experiments demonstrate that our instruction tuning variant, Cola-FT, achieves state-of-the-art performance on visual question answering (VQA), outside knowledge VQA, visual entailment, and visual spatial reasoning tasks. Moreover, we show that our in-context learning variant, Cola-Zero, exhibits competitive performance in zero and few-shot settings, without finetuning. Through systematic ablation studies and visualizations, we validate that a coordinator LLM indeed comprehends the instruction prompts as well as the separate functionalities of VLMs; it then coordinates them to enable impressive visual reasoning capabilities.

{{</citation>}}


### (163/208) Online Detection of AI-Generated Images (David C. Epstein et al., 2023)

{{<citation>}}

David C. Epstein, Ishan Jain, Oliver Wang, Richard Zhang. (2023)  
**Online Detection of AI-Generated Images**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-GR, cs-LG, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15150v1)  

---


**ABSTRACT**  
With advancements in AI-generated images coming on a continuous basis, it is increasingly difficult to distinguish traditionally-sourced images (e.g., photos, artwork) from AI-generated ones. Previous detection methods study the generalization from a single generator to another in isolation. However, in reality, new generators are released on a streaming basis. We study generalization in this setting, training on N models and testing on the next (N+k), following the historical release dates of well-known generation methods. Furthermore, images increasingly consist of both real and generated components, for example through image inpainting. Thus, we extend this approach to pixel prediction, demonstrating strong performance using automatically-generated inpainted data. In addition, for settings where commercial models are not publicly available for automatic data generation, we evaluate if pixel detectors can be trained solely on whole synthetic images.

{{</citation>}}


### (164/208) DEsignBench: Exploring and Benchmarking DALL-E 3 for Imagining Visual Design (Kevin Lin et al., 2023)

{{<citation>}}

Kevin Lin, Zhengyuan Yang, Linjie Li, Jianfeng Wang, Lijuan Wang. (2023)  
**DEsignBench: Exploring and Benchmarking DALL-E 3 for Imagining Visual Design**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2310.15144v1)  

---


**ABSTRACT**  
We introduce DEsignBench, a text-to-image (T2I) generation benchmark tailored for visual design scenarios. Recent T2I models like DALL-E 3 and others, have demonstrated remarkable capabilities in generating photorealistic images that align closely with textual inputs. While the allure of creating visually captivating images is undeniable, our emphasis extends beyond mere aesthetic pleasure. We aim to investigate the potential of using these powerful models in authentic design contexts. In pursuit of this goal, we develop DEsignBench, which incorporates test samples designed to assess T2I models on both "design technical capability" and "design application scenario." Each of these two dimensions is supported by a diverse set of specific design categories. We explore DALL-E 3 together with other leading T2I models on DEsignBench, resulting in a comprehensive visual gallery for side-by-side comparisons. For DEsignBench benchmarking, we perform human evaluations on generated images in DEsignBench gallery, against the criteria of image-text alignment, visual aesthetic, and design creativity. Our evaluation also considers other specialized design capabilities, including text rendering, layout composition, color harmony, 3D design, and medium style. In addition to human evaluations, we introduce the first automatic image generation evaluator powered by GPT-4V. This evaluator provides ratings that align well with human judgments, while being easily replicable and cost-efficient. A high-resolution version is available at https://github.com/design-bench/design-bench.github.io/raw/main/designbench.pdf?download=

{{</citation>}}


### (165/208) Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model (Ruoxi Shi et al., 2023)

{{<citation>}}

Ruoxi Shi, Hansheng Chen, Zhuoyang Zhang, Minghua Liu, Chao Xu, Xinyue Wei, Linghao Chen, Chong Zeng, Hao Su. (2023)  
**Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-GR, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15110v1)  

---


**ABSTRACT**  
We report Zero123++, an image-conditioned diffusion model for generating 3D-consistent multi-view images from a single input view. To take full advantage of pretrained 2D generative priors, we develop various conditioning and training schemes to minimize the effort of finetuning from off-the-shelf image diffusion models such as Stable Diffusion. Zero123++ excels in producing high-quality, consistent multi-view images from a single image, overcoming common issues like texture degradation and geometric misalignment. Furthermore, we showcase the feasibility of training a ControlNet on Zero123++ for enhanced control over the generation process. The code is available at https://github.com/SUDO-AI-3D/zero123plus.

{{</citation>}}


### (166/208) FD-Align: Feature Discrimination Alignment for Fine-tuning Pre-Trained Models in Few-Shot Learning (Kun Song et al., 2023)

{{<citation>}}

Kun Song, Huimin Ma, Bochao Zou, Huishuai Zhang, Weiran Huang. (2023)  
**FD-Align: Feature Discrimination Alignment for Fine-tuning Pre-Trained Models in Few-Shot Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Few-Shot, Pre-Trained Model  
[Paper Link](http://arxiv.org/abs/2310.15105v2)  

---


**ABSTRACT**  
Due to the limited availability of data, existing few-shot learning methods trained from scratch fail to achieve satisfactory performance. In contrast, large-scale pre-trained models such as CLIP demonstrate remarkable few-shot and zero-shot capabilities. To enhance the performance of pre-trained models for downstream tasks, fine-tuning the model on downstream data is frequently necessary. However, fine-tuning the pre-trained model leads to a decrease in its generalizability in the presence of distribution shift, while the limited number of samples in few-shot learning makes the model highly susceptible to overfitting. Consequently, existing methods for fine-tuning few-shot learning primarily focus on fine-tuning the model's classification head or introducing additional structure. In this paper, we introduce a fine-tuning approach termed Feature Discrimination Alignment (FD-Align). Our method aims to bolster the model's generalizability by preserving the consistency of spurious features across the fine-tuning process. Extensive experimental results validate the efficacy of our approach for both ID and OOD tasks. Once fine-tuned, the model can seamlessly integrate with existing methods, leading to performance improvements. Our code can be found in https://github.com/skingorz/FD-Align.

{{</citation>}}


### (167/208) Acquiring Weak Annotations for Tumor Localization in Temporal and Volumetric Data (Yu-Cheng Chou et al., 2023)

{{<citation>}}

Yu-Cheng Chou, Bowen Li, Deng-Ping Fan, Alan Yuille, Zongwei Zhou. (2023)  
**Acquiring Weak Annotations for Tumor Localization in Temporal and Volumetric Data**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15098v1)  

---


**ABSTRACT**  
Creating large-scale and well-annotated datasets to train AI algorithms is crucial for automated tumor detection and localization. However, with limited resources, it is challenging to determine the best type of annotations when annotating massive amounts of unlabeled data. To address this issue, we focus on polyps in colonoscopy videos and pancreatic tumors in abdominal CT scans; both applications require significant effort and time for pixel-wise annotation due to the high dimensional nature of the data, involving either temporary or spatial dimensions. In this paper, we develop a new annotation strategy, termed Drag&Drop, which simplifies the annotation process to drag and drop. This annotation strategy is more efficient, particularly for temporal and volumetric imaging, than other types of weak annotations, such as per-pixel, bounding boxes, scribbles, ellipses, and points. Furthermore, to exploit our Drag&Drop annotations, we develop a novel weakly supervised learning method based on the watershed algorithm. Experimental results show that our method achieves better detection and localization performance than alternative weak annotations and, more importantly, achieves similar performance to that trained on detailed per-pixel annotations. Interestingly, we find that, with limited resources, allocating weak annotations from a diverse patient population can foster models more robust to unseen images than allocating per-pixel annotations for a small set of images. In summary, this research proposes an efficient annotation strategy for tumor detection and localization that is less accurate than per-pixel annotations but useful for creating large-scale datasets for screening tumors in various medical modalities.

{{</citation>}}


### (168/208) Localizing Active Objects from Egocentric Vision with Symbolic World Knowledge (Te-Lin Wu et al., 2023)

{{<citation>}}

Te-Lin Wu, Yu Zhou, Nanyun Peng. (2023)  
**Localizing Active Objects from Egocentric Vision with Symbolic World Knowledge**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15066v1)  

---


**ABSTRACT**  
The ability to actively ground task instructions from an egocentric view is crucial for AI agents to accomplish tasks or assist humans virtually. One important step towards this goal is to localize and track key active objects that undergo major state change as a consequence of human actions/interactions to the environment without being told exactly what/where to ground (e.g., localizing and tracking the `sponge` in video from the instruction "Dip the `sponge` into the bucket."). While existing works approach this problem from a pure vision perspective, we investigate to which extent the textual modality (i.e., task instructions) and their interaction with visual modality can be beneficial. Specifically, we propose to improve phrase grounding models' ability on localizing the active objects by: (1) learning the role of `objects undergoing change` and extracting them accurately from the instructions, (2) leveraging pre- and post-conditions of the objects during actions, and (3) recognizing the objects more robustly with descriptional knowledge. We leverage large language models (LLMs) to extract the aforementioned action-object knowledge, and design a per-object aggregation masking technique to effectively perform joint inference on object phrases and symbolic knowledge. We evaluate our framework on Ego4D and Epic-Kitchens datasets. Extensive experiments demonstrate the effectiveness of our proposed framework, which leads to>54% improvements in all standard metrics on the TREK-150-OPE-Det localization + tracking task, >7% improvements in all standard metrics on the TREK-150-OPE tracking task, and >3% improvements in average precision (AP) on the Ego4D SCOD task.

{{</citation>}}


### (169/208) DREAM+: Efficient Dataset Distillation by Bidirectional Representative Matching (Yanqing Liu et al., 2023)

{{<citation>}}

Yanqing Liu, Jianyang Gu, Kai Wang, Zheng Zhu, Kaipeng Zhang, Wei Jiang, Yang You. (2023)  
**DREAM+: Efficient Dataset Distillation by Bidirectional Representative Matching**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15052v1)  

---


**ABSTRACT**  
Dataset distillation plays a crucial role in creating compact datasets with similar training performance compared with original large-scale ones. This is essential for addressing the challenges of data storage and training costs. Prevalent methods facilitate knowledge transfer by matching the gradients, embedding distributions, or training trajectories of synthetic images with those of the sampled original images. Although there are various matching objectives, currently the strategy for selecting original images is limited to naive random sampling. We argue that random sampling overlooks the evenness of the selected sample distribution, which may result in noisy or biased matching targets. Besides, the sample diversity is also not constrained by random sampling. Additionally, current methods predominantly focus on single-dimensional matching, where information is not fully utilized. To address these challenges, we propose a novel matching strategy called Dataset Distillation by Bidirectional REpresentAtive Matching (DREAM+), which selects representative original images for bidirectional matching. DREAM+ is applicable to a variety of mainstream dataset distillation frameworks and significantly reduces the number of distillation iterations by more than 15 times without affecting performance. Given sufficient training time, DREAM+ can further improve the performance and achieve state-of-the-art results. We have released the code at github.com/NUS-HPC-AI-Lab/DREAM+.

{{</citation>}}


### (170/208) A Universal Anti-Spoofing Approach for Contactless Fingerprint Biometric Systems (Banafsheh Adami et al., 2023)

{{<citation>}}

Banafsheh Adami, Sara Tehranipoor, Nasser Nasrabadi, Nima Karimian. (2023)  
**A Universal Anti-Spoofing Approach for Contactless Fingerprint Biometric Systems**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15044v1)  

---


**ABSTRACT**  
With the increasing integration of smartphones into our daily lives, fingerphotos are becoming a potential contactless authentication method. While it offers convenience, it is also more vulnerable to spoofing using various presentation attack instruments (PAI). The contactless fingerprint is an emerging biometric authentication but has not yet been heavily investigated for anti-spoofing. While existing anti-spoofing approaches demonstrated fair results, they have encountered challenges in terms of universality and scalability to detect any unseen/unknown spoofed samples. To address this issue, we propose a universal presentation attack detection method for contactless fingerprints, despite having limited knowledge of presentation attack samples. We generated synthetic contactless fingerprints using StyleGAN from live finger photos and integrating them to train a semi-supervised ResNet-18 model. A novel joint loss function, combining the Arcface and Center loss, is introduced with a regularization to balance between the two loss functions and minimize the variations within the live samples while enhancing the inter-class variations between the deepfake and live samples. We also conducted a comprehensive comparison of different regularizations' impact on the joint loss function for presentation attack detection (PAD) and explored the performance of a modified ResNet-18 architecture with different activation functions (i.e., leaky ReLU and RelU) in conjunction with Arcface and center loss. Finally, we evaluate the performance of the model using unseen types of spoof attacks and live data. Our proposed method achieves a Bona Fide Classification Error Rate (BPCER) of 0.12\%, an Attack Presentation Classification Error Rate (APCER) of 0.63\%, and an Average Classification Error Rate (ACER) of 0.37\%.

{{</citation>}}


### (171/208) P2AT: Pyramid Pooling Axial Transformer for Real-time Semantic Segmentation (Mohammed A. M. Elhassan et al., 2023)

{{<citation>}}

Mohammed A. M. Elhassan, Changjun Zhou, Amina Benabid, Abuzar B. M. Adam. (2023)  
**P2AT: Pyramid Pooling Axial Transformer for Real-time Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation, Transformer  
[Paper Link](http://arxiv.org/abs/2310.15025v1)  

---


**ABSTRACT**  
Recently, Transformer-based models have achieved promising results in various vision tasks, due to their ability to model long-range dependencies. However, transformers are computationally expensive, which limits their applications in real-time tasks such as autonomous driving. In addition, an efficient local and global feature selection and fusion are vital for accurate dense prediction, especially driving scene understanding tasks. In this paper, we propose a real-time semantic segmentation architecture named Pyramid Pooling Axial Transformer (P2AT). The proposed P2AT takes a coarse feature from the CNN encoder to produce scale-aware contextual features, which are then combined with the multi-level feature aggregation scheme to produce enhanced contextual features. Specifically, we introduce a pyramid pooling axial transformer to capture intricate spatial and channel dependencies, leading to improved performance on semantic segmentation. Then, we design a Bidirectional Fusion module (BiF) to combine semantic information at different levels. Meanwhile, a Global Context Enhancer is introduced to compensate for the inadequacy of concatenating different semantic levels. Finally, a decoder block is proposed to help maintain a larger receptive field. We evaluate P2AT variants on three challenging scene-understanding datasets. In particular, our P2AT variants achieve state-of-art results on the Camvid dataset 80.5%, 81.0%, 81.1% for P2AT-S, P2ATM, and P2AT-L, respectively. Furthermore, our experiment on Cityscapes and Pascal VOC 2012 have demonstrated the efficiency of the proposed architecture, with results showing that P2AT-M, achieves 78.7% on Cityscapes. The source code will be available at

{{</citation>}}


### (172/208) 3M-TRANSFORMER: A Multi-Stage Multi-Stream Multimodal Transformer for Embodied Turn-Taking Prediction (Mehdi Fatan et al., 2023)

{{<citation>}}

Mehdi Fatan, Emanuele Mincato, Dimitra Pintzou, Mariella Dimiccoli. (2023)  
**3M-TRANSFORMER: A Multi-Stage Multi-Stream Multimodal Transformer for Embodied Turn-Taking Prediction**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2310.14859v1)  

---


**ABSTRACT**  
Predicting turn-taking in multiparty conversations has many practical applications in human-computer/robot interaction. However, the complexity of human communication makes it a challenging task. Recent advances have shown that synchronous multi-perspective egocentric data can significantly improve turn-taking prediction compared to asynchronous, single-perspective transcriptions. Building on this research, we propose a new multimodal transformer-based architecture for predicting turn-taking in embodied, synchronized multi-perspective data. Our experimental results on the recently introduced EgoCom dataset show a substantial performance improvement of up to 14.01% on average compared to existing baselines and alternative transformer-based approaches. The source code, and the pre-trained models of our 3T-Transformer will be available upon acceptance.

{{</citation>}}


### (173/208) Large Language Models can Share Images, Too! (Young-Jun Lee et al., 2023)

{{<citation>}}

Young-Jun Lee, Jonghwan Hyeon, Ho-Jin Choi. (2023)  
**Large Language Models can Share Images, Too!**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CL, cs-CV, cs.CV  
Keywords: ChatGPT, GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2310.14804v1)  

---


**ABSTRACT**  
This paper explores the image-sharing capability of Large Language Models (LLMs), such as InstructGPT, ChatGPT, and GPT-4, in a zero-shot setting, without the help of visual foundation models. Inspired by the two-stage process of image-sharing in human dialogues, we propose a two-stage framework that allows LLMs to predict potential image-sharing turns and generate related image descriptions using our effective restriction-based prompt template. With extensive experiments, we unlock the \textit{image-sharing} capability of LLMs in zero-shot prompting, with GPT-4 achieving the best performance. Additionally, we uncover the emergent \textit{image-sharing} ability in zero-shot prompting, demonstrating the effectiveness of restriction-based prompts in both stages of our framework. Based on this framework, we augment the PhotoChat dataset with images generated by Stable Diffusion at predicted turns, namely PhotoChat++. To our knowledge, this is the first study to assess the image-sharing ability of LLMs in a zero-shot setting without visual foundation models. The source code and the dataset will be released after publication.

{{</citation>}}


### (174/208) SAMCLR: Contrastive pre-training on complex scenes using SAM for view sampling (Benjamin Missaoui et al., 2023)

{{<citation>}}

Benjamin Missaoui, Chongbin Yuan. (2023)  
**SAMCLR: Contrastive pre-training on complex scenes using SAM for view sampling**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Computer Vision, ImageNet  
[Paper Link](http://arxiv.org/abs/2310.14736v1)  

---


**ABSTRACT**  
In Computer Vision, self-supervised contrastive learning enforces similar representations between different views of the same image. The pre-training is most often performed on image classification datasets, like ImageNet, where images mainly contain a single class of objects. However, when dealing with complex scenes with multiple items, it becomes very unlikely for several views of the same image to represent the same object category. In this setting, we propose SAMCLR, an add-on to SimCLR which uses SAM to segment the image into semantic regions, then sample the two views from the same region. Preliminary results show empirically that when pre-training on Cityscapes and ADE20K, then evaluating on classification on CIFAR-10, STL10 and ImageNette, SAMCLR performs at least on par with, and most often significantly outperforms not only SimCLR, but also DINO and MoCo.

{{</citation>}}


### (175/208) Rethinking Scale Imbalance in Semi-supervised Object Detection for Aerial Images (Ruixiang Zhang et al., 2023)

{{<citation>}}

Ruixiang Zhang, Chang Xu, Fang Xu, Wen Yang, Guangjun He, Huai Yu, Gui-Song Xia. (2023)  
**Rethinking Scale Imbalance in Semi-supervised Object Detection for Aerial Images**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection, Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2310.14718v1)  

---


**ABSTRACT**  
This paper focuses on the scale imbalance problem of semi-supervised object detection(SSOD) in aerial images. Compared to natural images, objects in aerial images show smaller sizes and larger quantities per image, increasing the difficulty of manual annotation. Meanwhile, the advanced SSOD technique can train superior detectors by leveraging limited labeled data and massive unlabeled data, saving annotation costs. However, as an understudied task in aerial images, SSOD suffers from a drastic performance drop when facing a large proportion of small objects. By analyzing the predictions between small and large objects, we identify three imbalance issues caused by the scale bias, i.e., pseudo-label imbalance, label assignment imbalance, and negative learning imbalance. To tackle these issues, we propose a novel Scale-discriminative Semi-Supervised Object Detection (S^3OD) learning pipeline for aerial images. In our S^3OD, three key components, Size-aware Adaptive Thresholding (SAT), Size-rebalanced Label Assignment (SLA), and Teacher-guided Negative Learning (TNL), are proposed to warrant scale unbiased learning. Specifically, SAT adaptively selects appropriate thresholds to filter pseudo-labels for objects at different scales. SLA balances positive samples of objects at different scales through resampling and reweighting. TNL alleviates the imbalance in negative samples by leveraging information generated by a teacher model. Extensive experiments conducted on the DOTA-v1.5 benchmark demonstrate the superiority of our proposed methods over state-of-the-art competitors. Codes will be released soon.

{{</citation>}}


### (176/208) BM2CP: Efficient Collaborative Perception with LiDAR-Camera Modalities (Binyu Zhao et al., 2023)

{{<citation>}}

Binyu Zhao, Wei Zhang, Zhaonian Zou. (2023)  
**BM2CP: Efficient Collaborative Perception with LiDAR-Camera Modalities**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-RO, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.14702v1)  

---


**ABSTRACT**  
Collaborative perception enables agents to share complementary perceptual information with nearby agents. This would improve the perception performance and alleviate the issues of single-view perception, such as occlusion and sparsity. Most existing approaches mainly focus on single modality (especially LiDAR), and not fully exploit the superiority of multi-modal perception. We propose a collaborative perception paradigm, BM2CP, which employs LiDAR and camera to achieve efficient multi-modal perception. It utilizes LiDAR-guided modal fusion, cooperative depth generation and modality-guided intermediate fusion to acquire deep interactions among modalities of different agents, Moreover, it is capable to cope with the special case where one of the sensors, same or different type, of any agent is missing. Extensive experiments validate that our approach outperforms the state-of-the-art methods with 50X lower communication volumes in both simulated and real-world autonomous driving scenarios. Our code is available at https://github.com/byzhaoAI/BM2CP.

{{</citation>}}


### (177/208) Inject Semantic Concepts into Image Tagging for Open-Set Recognition (Xinyu Huang et al., 2023)

{{<citation>}}

Xinyu Huang, Yi-Jie Huang, Youcai Zhang, Weiwei Tian, Rui Feng, Yuejie Zhang, Yanchun Xie, Yaqian Li, Lei Zhang. (2023)  
**Inject Semantic Concepts into Image Tagging for Open-Set Recognition**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2310.15200v1)  

---


**ABSTRACT**  
In this paper, we introduce the Recognize Anything Plus Model~(RAM++), a fundamental image recognition model with strong open-set recognition capabilities, by injecting semantic concepts into image tagging training framework. Previous approaches are either image tagging models constrained by limited semantics, or vision-language models with shallow interaction for suboptimal performance in multi-tag recognition. In contrast, RAM++ integrates image-text alignment and image-tagging within a unified fine-grained interaction framework based on image-tags-text triplets. This design enables RAM++ not only excel in identifying predefined categories, but also significantly augment the recognition ability in open-set categories. Moreover, RAM++ employs large language models~(LLMs) to generate diverse visual tag descriptions, pioneering the integration of LLM's knowledge into image tagging training. This approach empowers RAM++ to integrate visual description concepts for open-set recognition during inference. Evaluations on comprehensive image recognition benchmarks demonstrate RAM++ exceeds existing state-of-the-art (SOTA) fundamental image recognition models on most aspects. Specifically, for predefined common-used tag categories, RAM++ showcases 10.2 mAP and 15.4 mAP enhancements over CLIP on OpenImages and ImageNet. For open-set categories beyond predefined, RAM++ records improvements of 5 mAP and 6.4 mAP over CLIP and RAM respectively on OpenImages. For diverse human-object interaction phrases, RAM++ achieves 7.8 mAP and 4.7 mAP improvements on the HICO benchmark. Code, datasets and pre-trained models are available at \url{https://github.com/xinyu1205/recognize-anything}.

{{</citation>}}


### (178/208) Dataset Bias Mitigation in Multiple-Choice Visual Question Answering and Beyond (Zhecan Wang et al., 2023)

{{<citation>}}

Zhecan Wang, Long Chen, Haoxuan You, Keyang Xu, Yicheng He, Wenhao Li, Noal Codella, Kai-Wei Chang, Shih-Fu Chang. (2023)  
**Dataset Bias Mitigation in Multiple-Choice Visual Question Answering and Beyond**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CL, cs-CV, cs-LG, cs-MM, cs.CV  
Keywords: Bias, Question Answering  
[Paper Link](http://arxiv.org/abs/2310.14670v1)  

---


**ABSTRACT**  
Vision-language (VL) understanding tasks evaluate models' comprehension of complex visual scenes through multiple-choice questions. However, we have identified two dataset biases that models can exploit as shortcuts to resolve various VL tasks correctly without proper understanding. The first type of dataset bias is \emph{Unbalanced Matching} bias, where the correct answer overlaps the question and image more than the incorrect answers. The second type of dataset bias is \emph{Distractor Similarity} bias, where incorrect answers are overly dissimilar to the correct answer but significantly similar to other incorrect answers within the same sample. To address these dataset biases, we first propose Adversarial Data Synthesis (ADS) to generate synthetic training and debiased evaluation data. We then introduce Intra-sample Counterfactual Training (ICT) to assist models in utilizing the synthesized training data, particularly the counterfactual data, via focusing on intra-sample differentiation. Extensive experiments demonstrate the effectiveness of ADS and ICT in consistently improving model performance across different benchmarks, even in domain-shifted scenarios.

{{</citation>}}


### (179/208) Semantic-Aware Adversarial Training for Reliable Deep Hashing Retrieval (Xu Yuan et al., 2023)

{{<citation>}}

Xu Yuan, Zheng Zhang, Xunguang Wang, Lin Wu. (2023)  
**Semantic-Aware Adversarial Training for Reliable Deep Hashing Retrieval**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs-MM, cs.CV  
Keywords: Adversarial Training  
[Paper Link](http://arxiv.org/abs/2310.14637v1)  

---


**ABSTRACT**  
Deep hashing has been intensively studied and successfully applied in large-scale image retrieval systems due to its efficiency and effectiveness. Recent studies have recognized that the existence of adversarial examples poses a security threat to deep hashing models, that is, adversarial vulnerability. Notably, it is challenging to efficiently distill reliable semantic representatives for deep hashing to guide adversarial learning, and thereby it hinders the enhancement of adversarial robustness of deep hashing-based retrieval models. Moreover, current researches on adversarial training for deep hashing are hard to be formalized into a unified minimax structure. In this paper, we explore Semantic-Aware Adversarial Training (SAAT) for improving the adversarial robustness of deep hashing models. Specifically, we conceive a discriminative mainstay features learning (DMFL) scheme to construct semantic representatives for guiding adversarial learning in deep hashing. Particularly, our DMFL with the strict theoretical guarantee is adaptively optimized in a discriminative learning manner, where both discriminative and semantic properties are jointly considered. Moreover, adversarial examples are fabricated by maximizing the Hamming distance between the hash codes of adversarial samples and mainstay features, the efficacy of which is validated in the adversarial attack trials. Further, we, for the first time, formulate the formalized adversarial training of deep hashing into a unified minimax optimization under the guidance of the generated mainstay codes. Extensive experiments on benchmark datasets show superb attack performance against the state-of-the-art algorithms, meanwhile, the proposed adversarial training can effectively eliminate adversarial perturbations for trustworthy deep hashing-based retrieval. Our code is available at https://github.com/xandery-geek/SAAT.

{{</citation>}}


### (180/208) HallusionBench: You See What You Think? Or You Think What You See? An Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5, and Other Multi-modality Models (Fuxiao Liu et al., 2023)

{{<citation>}}

Fuxiao Liu, Tianrui Guan, Zongxia Li, Lichang Chen, Yaser Yacoob, Dinesh Manocha, Tianyi Zhou. (2023)  
**HallusionBench: You See What You Think? Or You Think What You See? An Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5, and Other Multi-modality Models**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs.CV  
Keywords: GPT, GPT-4, Reasoning  
[Paper Link](http://arxiv.org/abs/2310.14566v1)  

---


**ABSTRACT**  
Large language models (LLMs), after being aligned with vision models and integrated into vision-language models (VLMs), can bring impressive improvement in image reasoning tasks. This was shown by the recently released GPT-4V(ison), LLaVA-1.5, etc. However, the strong language prior in these SOTA LVLMs can be a double-edged sword: they may ignore the image context and solely rely on the (even contradictory) language prior for reasoning. In contrast, the vision modules in VLMs are weaker than LLMs and may result in misleading visual representations, which are then translated to confident mistakes by LLMs. To study these two types of VLM mistakes, i.e., language hallucination and visual illusion, we curated HallusionBench, an image-context reasoning benchmark that is still challenging to even GPT-4V and LLaVA-1.5. We provide a detailed analysis of examples in HallusionBench, which sheds novel insights on the illusion or hallucination of VLMs and how to improve them in the future. The benchmark and codebase will be released at https://github.com/tianyi-lab/HallusionBench.

{{</citation>}}


### (181/208) F$^2$AT: Feature-Focusing Adversarial Training via Disentanglement of Natural and Perturbed Patterns (Yaguan Qian et al., 2023)

{{<citation>}}

Yaguan Qian, Chenyu Zhao, Zhaoquan Gu, Bin Wang, Shouling Ji, Wei Wang, Boyang Zhou, Pan Zhou. (2023)  
**F$^2$AT: Feature-Focusing Adversarial Training via Disentanglement of Natural and Perturbed Patterns**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Adversarial Training  
[Paper Link](http://arxiv.org/abs/2310.14561v1)  

---


**ABSTRACT**  
Deep neural networks (DNNs) are vulnerable to adversarial examples crafted by well-designed perturbations. This could lead to disastrous results on critical applications such as self-driving cars, surveillance security, and medical diagnosis. At present, adversarial training is one of the most effective defenses against adversarial examples. However, traditional adversarial training makes it difficult to achieve a good trade-off between clean accuracy and robustness since spurious features are still learned by DNNs. The intrinsic reason is that traditional adversarial training makes it difficult to fully learn core features from adversarial examples when adversarial noise and clean examples cannot be disentangled. In this paper, we disentangle the adversarial examples into natural and perturbed patterns by bit-plane slicing. We assume the higher bit-planes represent natural patterns and the lower bit-planes represent perturbed patterns, respectively. We propose a Feature-Focusing Adversarial Training (F$^2$AT), which differs from previous work in that it enforces the model to focus on the core features from natural patterns and reduce the impact of spurious features from perturbed patterns. The experimental results demonstrated that F$^2$AT outperforms state-of-the-art methods in clean accuracy and adversarial robustness.

{{</citation>}}


### (182/208) ADoPT: LiDAR Spoofing Attack Detection Based on Point-Level Temporal Consistency (Minkyoung Cho et al., 2023)

{{<citation>}}

Minkyoung Cho, Yulong Cao, Zixiang Zhou, Z. Morley Mao. (2023)  
**ADoPT: LiDAR Spoofing Attack Detection Based on Point-Level Temporal Consistency**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2310.14504v1)  

---


**ABSTRACT**  
Deep neural networks (DNNs) are increasingly integrated into LiDAR (Light Detection and Ranging)-based perception systems for autonomous vehicles (AVs), requiring robust performance under adversarial conditions. We aim to address the challenge of LiDAR spoofing attacks, where attackers inject fake objects into LiDAR data and fool AVs to misinterpret their environment and make erroneous decisions. However, current defense algorithms predominantly depend on perception outputs (i.e., bounding boxes) thus face limitations in detecting attackers given the bounding boxes are generated by imperfect perception models processing limited points, acquired based on the ego vehicle's viewpoint. To overcome these limitations, we propose a novel framework, named ADoPT (Anomaly Detection based on Point-level Temporal consistency), which quantitatively measures temporal consistency across consecutive frames and identifies abnormal objects based on the coherency of point clusters. In our evaluation using the nuScenes dataset, our algorithm effectively counters various LiDAR spoofing attacks, achieving a low (< 10%) false positive ratio (FPR) and high (> 85%) true positive ratio (TPR), outperforming existing state-of-the-art defense methods, CARLO and 3D-TC2. Furthermore, our evaluation demonstrates the promising potential for accurate attack detection across various road environments.

{{</citation>}}


### (183/208) VQ-NeRF: Vector Quantization Enhances Implicit Neural Representations (Yiying Yang et al., 2023)

{{<citation>}}

Yiying Yang, Wen Liu, Fukun Yin, Xin Chen, Gang Yu, Jiayuan Fan, Tao Chen. (2023)  
**VQ-NeRF: Vector Quantization Enhances Implicit Neural Representations**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Quantization  
[Paper Link](http://arxiv.org/abs/2310.14487v1)  

---


**ABSTRACT**  
Recent advancements in implicit neural representations have contributed to high-fidelity surface reconstruction and photorealistic novel view synthesis. However, the computational complexity inherent in these methodologies presents a substantial impediment, constraining the attainable frame rates and resolutions in practical applications. In response to this predicament, we propose VQ-NeRF, an effective and efficient pipeline for enhancing implicit neural representations via vector quantization. The essence of our method involves reducing the sampling space of NeRF to a lower resolution and subsequently reinstating it to the original size utilizing a pre-trained VAE decoder, thereby effectively mitigating the sampling time bottleneck encountered during rendering. Although the codebook furnishes representative features, reconstructing fine texture details of the scene remains challenging due to high compression rates. To overcome this constraint, we design an innovative multi-scale NeRF sampling scheme that concurrently optimizes the NeRF model at both compressed and original scales to enhance the network's ability to preserve fine details. Furthermore, we incorporate a semantic loss function to improve the geometric fidelity and semantic coherence of our 3D reconstructions. Extensive experiments demonstrate the effectiveness of our model in achieving the optimal trade-off between rendering quality and efficiency. Evaluation on the DTU, BlendMVS, and H3DS datasets confirms the superior performance of our approach.

{{</citation>}}


### (184/208) Player Re-Identification Using Body Part Appearences (Mahesh Bhosale et al., 2023)

{{<citation>}}

Mahesh Bhosale, Abhishek Kumar, David Doermann. (2023)  
**Player Re-Identification Using Body Part Appearences**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2310.14469v1)  

---


**ABSTRACT**  
We propose a neural network architecture that learns body part appearances for soccer player re-identification. Our model consists of a two-stream network (one stream for appearance map extraction and the other for body part map extraction) and a bilinear-pooling layer that generates and spatially pools the body part map. Each local feature of the body part map is obtained by a bilinear mapping of the corresponding local appearance and body part descriptors. Our novel representation yields a robust image-matching feature map, which results from combining the local similarities of the relevant body parts with the weighted appearance similarity. Our model does not require any part annotation on the SoccerNet-V3 re-identification dataset to train the network. Instead, we use a sub-network of an existing pose estimation network (OpenPose) to initialize the part substream and then train the entire network to minimize the triplet loss. The appearance stream is pre-trained on the ImageNet dataset, and the part stream is trained from scratch for the SoccerNet-V3 dataset. We demonstrate the validity of our model by showing that it outperforms state-of-the-art models such as OsNet and InceptionNet.

{{</citation>}}


## q-bio.NC (1)



### (185/208) One-hot Generalized Linear Model for Switching Brain State Discovery (Chengrui Li et al., 2023)

{{<citation>}}

Chengrui Li, Soon Ho Kim, Chris Rodgers, Hannah Choi, Anqi Wu. (2023)  
**One-hot Generalized Linear Model for Switching Brain State Discovery**  

---
Primary Category: q-bio.NC  
Categories: cs-LG, q-bio-NC, q-bio.NC  
Keywords: GLM  
[Paper Link](http://arxiv.org/abs/2310.15263v1)  

---


**ABSTRACT**  
Exposing meaningful and interpretable neural interactions is critical to understanding neural circuits. Inferred neural interactions from neural signals primarily reflect functional interactions. In a long experiment, subject animals may experience different stages defined by the experiment, stimuli, or behavioral states, and hence functional interactions can change over time. To model dynamically changing functional interactions, prior work employs state-switching generalized linear models with hidden Markov models (i.e., HMM-GLMs). However, we argue they lack biological plausibility, as functional interactions are shaped and confined by the underlying anatomical connectome. Here, we propose a novel prior-informed state-switching GLM. We introduce both a Gaussian prior and a one-hot prior over the GLM in each state. The priors are learnable. We will show that the learned prior should capture the state-constant interaction, shedding light on the underlying anatomical connectome and revealing more likely physical neuron interactions. The state-dependent interaction modeled by each GLM offers traceability to capture functional variations across multiple brain states. Our methods effectively recover true interaction structures in simulated data, achieve the highest predictive likelihood with real neural datasets, and render interaction structures and hidden states more interpretable when applied to real neural data.

{{</citation>}}


## cs.RO (3)



### (186/208) Robot Fine-Tuning Made Easy: Pre-Training Rewards and Policies for Autonomous Real-World Reinforcement Learning (Jingyun Yang et al., 2023)

{{<citation>}}

Jingyun Yang, Max Sobol Mark, Brandon Vu, Archit Sharma, Jeannette Bohg, Chelsea Finn. (2023)  
**Robot Fine-Tuning Made Easy: Pre-Training Rewards and Policies for Autonomous Real-World Reinforcement Learning**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-LG, cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.15145v1)  

---


**ABSTRACT**  
The pre-train and fine-tune paradigm in machine learning has had dramatic success in a wide range of domains because the use of existing data or pre-trained models on the internet enables quick and easy learning of new tasks. We aim to enable this paradigm in robotic reinforcement learning, allowing a robot to learn a new task with little human effort by leveraging data and models from the Internet. However, reinforcement learning often requires significant human effort in the form of manual reward specification or environment resets, even if the policy is pre-trained. We introduce RoboFuME, a reset-free fine-tuning system that pre-trains a multi-task manipulation policy from diverse datasets of prior experiences and self-improves online to learn a target task with minimal human intervention. Our insights are to utilize calibrated offline reinforcement learning techniques to ensure efficient online fine-tuning of a pre-trained policy in the presence of distribution shifts and leverage pre-trained vision language models (VLMs) to build a robust reward classifier for autonomously providing reward signals during the online fine-tuning process. In a diverse set of five real robot manipulation tasks, we show that our method can incorporate data from an existing robot dataset collected at a different institution and improve on a target task within as little as 3 hours of autonomous real-world experience. We also demonstrate in simulation experiments that our method outperforms prior works that use different RL algorithms or different approaches for predicting rewards. Project website: https://robofume.github.io

{{</citation>}}


### (187/208) Denoising Opponents Position in Partial Observation Environment (Aref Sayareh et al., 2023)

{{<citation>}}

Aref Sayareh, Aria Sardari, Vahid Khoddami, Nader Zare, Vinicius Prado da Fonseca, Amilcar Soares. (2023)  
**Denoising Opponents Position in Partial Observation Environment**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-MA, cs-RO, cs.RO  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2310.14553v1)  

---


**ABSTRACT**  
The RoboCup competitions hold various leagues, and the Soccer Simulation 2D League is a major among them. Soccer Simulation 2D (SS2D) match involves two teams, including 11 players and a coach for each team, competing against each other. The players can only communicate with the Soccer Simulation Server during the game. Several code bases are released publicly to simplify team development. So researchers can easily focus on decision-making and implementing machine learning methods. SS2D actions and behaviors are only partially accurate due to different challenges, such as noise and partial observation. Therefore, one strategy is to implement alternative denoising methods to tackle observation inaccuracy. Our idea is to predict opponent positions while they have yet to be seen in a finite number of cycles using machine learning methods to make more accurate actions such as pass. We will explain our position prediction idea powered by Long Short-Term Memory models (LSTM) and Deep Neural Networks (DNN). The results show that the LSTM and DNN predict the opponents' position more accurately than the standard algorithm, such as the last-seen method.

{{</citation>}}


### (188/208) Intelligent Escape of Robotic Systems: A Survey of Methodologies, Applications, and Challenges (Junfei Li et al., 2023)

{{<citation>}}

Junfei Li, Simon X. Yang. (2023)  
**Intelligent Escape of Robotic Systems: A Survey of Methodologies, Applications, and Challenges**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-RO, cs-SY, cs.RO, eess-SY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.14485v1)  

---


**ABSTRACT**  
Intelligent escape is an interdisciplinary field that employs artificial intelligence (AI) techniques to enable robots with the capacity to intelligently react to potential dangers in dynamic, intricate, and unpredictable scenarios. As the emphasis on safety becomes increasingly paramount and advancements in robotic technologies continue to advance, a wide range of intelligent escape methodologies has been developed in recent years. This paper presents a comprehensive survey of state-of-the-art research work on intelligent escape of robotic systems. Four main methods of intelligent escape are reviewed, including planning-based methodologies, partitioning-based methodologies, learning-based methodologies, and bio-inspired methodologies. The strengths and limitations of existing methods are summarized. In addition, potential applications of intelligent escape are discussed in various domains, such as search and rescue, evacuation, military security, and healthcare. In an effort to develop new approaches to intelligent escape, this survey identifies current research challenges and provides insights into future research trends in intelligent escape.

{{</citation>}}


## cs.CR (2)



### (189/208) AutoDAN: Automatic and Interpretable Adversarial Attacks on Large Language Models (Sicheng Zhu et al., 2023)

{{<citation>}}

Sicheng Zhu, Ruiyi Zhang, Bang An, Gang Wu, Joe Barrow, Zichao Wang, Furong Huang, Ani Nenkova, Tong Sun. (2023)  
**AutoDAN: Automatic and Interpretable Adversarial Attacks on Large Language Models**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CL, cs-CR, cs-LG, cs.CR  
Keywords: Adversarial Attack, Language Model  
[Paper Link](http://arxiv.org/abs/2310.15140v1)  

---


**ABSTRACT**  
Safety alignment of Large Language Models (LLMs) can be compromised with manual jailbreak attacks and (automatic) adversarial attacks. Recent work suggests that patching LLMs against these attacks is possible: manual jailbreak attacks are human-readable but often limited and public, making them easy to block; adversarial attacks generate gibberish prompts that can be detected using perplexity-based filters. In this paper, we show that these solutions may be too optimistic. We propose an interpretable adversarial attack, \texttt{AutoDAN}, that combines the strengths of both types of attacks. It automatically generates attack prompts that bypass perplexity-based filters while maintaining a high attack success rate like manual jailbreak attacks. These prompts are interpretable and diverse, exhibiting strategies commonly used in manual jailbreak attacks, and transfer better than their non-readable counterparts when using limited training data or a single proxy model. We also customize \texttt{AutoDAN}'s objective to leak system prompts, another jailbreak application not addressed in the adversarial attack literature. Our work provides a new way to red-team LLMs and to understand the mechanism of jailbreak attacks.

{{</citation>}}


### (190/208) CryptoVerif: a Computationally-Sound Security Protocol Verifier (Initial Version with Communications on Channels) (Bruno Blanchet, 2023)

{{<citation>}}

Bruno Blanchet. (2023)  
**CryptoVerif: a Computationally-Sound Security Protocol Verifier (Initial Version with Communications on Channels)**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2310.14658v1)  

---


**ABSTRACT**  
This document presents the security protocol verifier CryptoVerif.CryptoVerif does not rely on the symbolic, Dolev-Yao model, but on the computational model. It can verify secrecy, correspondence (which include authentication), and indistinguishability properties. It produces proofs presented as sequences of games, like those manually written by cryptographers; these games are formalized in aprobabilistic process calculus. CryptoVerif provides a generic method for specifying security properties of the cryptographic primitives.It produces proofs valid for any number of sessions of the protocol, and provides an upper bound on the probability of success of an attack against the protocol as a function of the probability of breaking each primitive and of the number of sessions. It can work automatically, or the user can guide it with manual proof indications.

{{</citation>}}


## math.NA (1)



### (191/208) Convergence of a steepest descent algorithm in shape optimisation using $W^{1,\infty}$ functions (Klaus Deckelnick et al., 2023)

{{<citation>}}

Klaus Deckelnick, Philip J. Herbert, Michael Hinze. (2023)  
**Convergence of a steepest descent algorithm in shape optimisation using $W^{1,\infty}$ functions**  

---
Primary Category: math.NA  
Categories: cs-NA, math-NA, math-OC, math.NA  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15078v1)  

---


**ABSTRACT**  
Built upon previous work of the authors in (Deckelnick, Herbert, and Hinze, ESAIM: COCV 28 (2022)), we present a general shape optimisation framework based on the method of mappings in the $W^{1,\infty}$ topology together with a suitable finite element discretisation. For the numerical solution of the respective discrete shape optimisation problems we propose a steepest descent minimisation algorithm with Armijo-Goldstein stepsize rule. We show that the sequence generated by this descent method globally converges, and under mild assumptions also, that every accumulation point of this sequence is a stationary point of the shape functional. Moreover, for the mesh discretisation parameter tending to zero we under mild assumptions prove convergence of the discrete stationary shapes in the Hausdorff complementary metric. To illustrate our approach we present a selection of numerical examples for PDE constrained shape optimisation problems, where we include numerical convergence studies which support our analytical findings.

{{</citation>}}


## cs.IT (1)



### (192/208) TeleQnA: A Benchmark Dataset to Assess Large Language Models Telecommunications Knowledge (Ali Maatouk et al., 2023)

{{<citation>}}

Ali Maatouk, Fadhel Ayed, Nicola Piovesan, Antonio De Domenico, Merouane Debbah, Zhi-Quan Luo. (2023)  
**TeleQnA: A Benchmark Dataset to Assess Large Language Models Telecommunications Knowledge**  

---
Primary Category: cs.IT  
Categories: cs-AI, cs-IT, cs-LG, cs.IT, math-IT  
Keywords: GPT, GPT-3.5, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2310.15051v1)  

---


**ABSTRACT**  
We introduce TeleQnA, the first benchmark dataset designed to evaluate the knowledge of Large Language Models (LLMs) in telecommunications. Comprising 10,000 questions and answers, this dataset draws from diverse sources, including standards and research articles. This paper outlines the automated question generation framework responsible for creating this dataset, along with how human input was integrated at various stages to ensure the quality of the questions. Afterwards, using the provided dataset, an evaluation is conducted to assess the capabilities of LLMs, including GPT-3.5 and GPT-4. The results highlight that these models struggle with complex standards related questions but exhibit proficiency in addressing general telecom-related inquiries. Additionally, our results showcase how incorporating telecom knowledge context significantly enhances their performance, thus shedding light on the need for a specialized telecom foundation model. Finally, the dataset is shared with active telecom professionals, whose performance is subsequently benchmarked against that of the LLMs. The findings illustrate that LLMs can rival the performance of active professionals in telecom knowledge, thanks to their capacity to process vast amounts of information, underscoring the potential of LLMs within this domain. The dataset has been made publicly accessible on GitHub.

{{</citation>}}


## cs.SE (2)



### (193/208) Leveraging Deep Learning for Abstractive Code Summarization of Unofficial Documentation (AmirHossein Naghshzan et al., 2023)

{{<citation>}}

AmirHossein Naghshzan, Latifa Guerrouj, Olga Baysal. (2023)  
**Leveraging Deep Learning for Abstractive Code Summarization of Unofficial Documentation**  

---
Primary Category: cs.SE  
Categories: cs-LG, cs-SE, cs.SE  
Keywords: BLEU, Summarization  
[Paper Link](http://arxiv.org/abs/2310.15015v1)  

---


**ABSTRACT**  
Usually, programming languages have official documentation to guide developers with APIs, methods, and classes. However, researchers identified insufficient or inadequate documentation examples and flaws with the API's complex structure as barriers to learning an API. As a result, developers may consult other sources (StackOverflow, GitHub, etc.) to learn more about an API. Recent research studies have shown that unofficial documentation is a valuable source of information for generating code summaries. We, therefore, have been motivated to leverage such a type of documentation along with deep learning techniques towards generating high-quality summaries for APIs discussed in informal documentation.   This paper proposes an automatic approach using the BART algorithm, a state-of-the-art transformer model, to generate summaries for APIs discussed in StackOverflow. We built an oracle of human-generated summaries to evaluate our approach against it using ROUGE and BLEU metrics which are the most widely used evaluation metrics in text summarization. Furthermore, we evaluated our summaries empirically against a previous work in terms of quality. Our findings demonstrate that using deep learning algorithms can improve summaries' quality and outperform the previous work by an average of %57 for Precision, %66 for Recall, and %61 for F-measure, and it runs 4.4 times faster.

{{</citation>}}


### (194/208) End-to-End Software Construction using ChatGPT: An Experience Report (Mauricio Monteiro et al., 2023)

{{<citation>}}

Mauricio Monteiro, Bruno Castelo Branco, Samuel Silvestre, Guilherme Avelino, Marco Tulio Valente. (2023)  
**End-to-End Software Construction using ChatGPT: An Experience Report**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2310.14843v1)  

---


**ABSTRACT**  
In this paper, we explore the application of Large Language Models (LLMs) in the particular context of end-to-end software construction, i.e., in contexts where software developers have a set of requirements and have to design, implement, test, and validate a new software system. Particularly, we report an experiment where we asked three software developers to use ChatGPT to fully implement a Web-based application using mainstream software architectures and technologies. After that, we compare the apps produced by ChatGPT with a reference implementation that we manually implemented for our research. As a result, we document four categories of prompts that can be used by developers in similar contexts, including initialization prompts, feature requests, bug-fixing, and layout prompts. Additionally, we discuss the advantages and disadvantages of two prompt construction approaches: top-down (where we start with a high-level description of the target software, typically in the form of user stories) and bottom-up (where we request the construction of the system feature by feature).

{{</citation>}}


## eess.SY (4)



### (195/208) Elemantra: An End-to-End Automated Framework Empowered with AI and IoT for Tackling Human-Elephant Conflict in Elephant-Range Countries (Nuwan Sriyantha Bandara et al., 2023)

{{<citation>}}

Nuwan Sriyantha Bandara, Dilshan Pramudith Bandara. (2023)  
**Elemantra: An End-to-End Automated Framework Empowered with AI and IoT for Tackling Human-Elephant Conflict in Elephant-Range Countries**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.15012v1)  

---


**ABSTRACT**  
The cohabitation of elephants and humans has evolved into a human-elephant conflict (HEC) due to the increasing loss of historical elephant habitations. Since HEC is a substantial threat to both species, advanced sensing methods are utilized to develop HEC prevention frameworks which still lack unification. Here, we propose an end-to-end automated framework for HEC prevention consisting of three main modules: a distributed deep learning-assisted elephant detection module using infrared and seismic sensing, an on-site repelling system with time-varying acoustic and light deterrents and a mesh network for device communication. The framework is equipped with novel decision-making pipelines and algorithms such that it has the potential to operate with no human intervention. The preliminary results from each module confirm that the proposed framework is effective in performing their individual tasks towards collaboratively achieving the prevention of HEC. The codes are publicly available at https://github.com/nuwansribandara/elemantra.

{{</citation>}}


### (196/208) Comparison of path following in ships using modern and traditional controllers (Sanjeev Kumar Ramkumar Sudha et al., 2023)

{{<citation>}}

Sanjeev Kumar Ramkumar Sudha, Md Shadab Alam, Bindusara Reddy, Abhilash Sharma Somayajula. (2023)  
**Comparison of path following in ships using modern and traditional controllers**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.14940v1)  

---


**ABSTRACT**  
Vessel navigation is difficult in restricted waterways and in the presence of static and dynamic obstacles. This difficulty can be attributed to the high-level decisions taken by humans during these maneuvers, which is evident from the fact that 85% of the reported marine accidents are traced back to human errors. Artificial intelligence-based methods offer us a way to eliminate human intervention in vessel navigation. Newer methods like Deep Reinforcement Learning (DRL) can optimize multiple objectives like path following and collision avoidance at the same time while being computationally cheaper to implement in comparison to traditional approaches. Before addressing the challenge of collision avoidance along with path following, the performance of DRL-based controllers on the path following task alone must be established. Therefore, this study trains a DRL agent using Proximal Policy Optimization (PPO) algorithm and tests it against a traditional PD controller guided by an Integral Line of Sight (ILOS) guidance system. The Krisco Container Ship (KCS) is chosen to test the different controllers. The ship dynamics are mathematically simulated using the Maneuvering Modelling Group (MMG) model developed by the Japanese. The simulation environment is used to train the deep reinforcement learning-based controller and is also used to tune the gains of the traditional PD controller. The effectiveness of the controllers in the presence of wind is also investigated.

{{</citation>}}


### (197/208) AI on the Water: Applying DRL to Autonomous Vessel Navigation (Md Shadab Alam et al., 2023)

{{<citation>}}

Md Shadab Alam, Sanjeev Kumar Ramkumar Sudha, Abhilash Somayajula. (2023)  
**AI on the Water: Applying DRL to Autonomous Vessel Navigation**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.14938v1)  

---


**ABSTRACT**  
Human decision-making errors cause a majority of globally reported marine accidents. As a result, automation in the marine industry has been gaining more attention in recent years. Obstacle avoidance becomes very challenging for an autonomous surface vehicle in an unknown environment. We explore the feasibility of using Deep Q-Learning (DQN), a deep reinforcement learning approach, for controlling an underactuated autonomous surface vehicle to follow a known path while avoiding collisions with static and dynamic obstacles. The ship's motion is described using a three-degree-of-freedom (3-DOF) dynamic model. The KRISO container ship (KCS) is chosen for this study because it is a benchmark hull used in several studies, and its hydrodynamic coefficients are readily available for numerical modelling. This study shows that Deep Reinforcement Learning (DRL) can achieve path following and collision avoidance successfully and can be a potential candidate that may be investigated further to achieve human-level or even better decision-making for autonomous marine vehicles.

{{</citation>}}


### (198/208) Navigating the Ocean with DRL: Path following for marine vessels (Joel Jose et al., 2023)

{{<citation>}}

Joel Jose, Md Shadab Alam, Abhilash Sharma Somayajula. (2023)  
**Navigating the Ocean with DRL: Path following for marine vessels**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.14932v1)  

---


**ABSTRACT**  
Human error is a substantial factor in marine accidents, accounting for 85% of all reported incidents. By reducing the need for human intervention in vessel navigation, AI-based methods can potentially reduce the risk of accidents. AI techniques, such as Deep Reinforcement Learning (DRL), have the potential to improve vessel navigation in challenging conditions, such as in restricted waterways and in the presence of obstacles. This is because DRL algorithms can optimize multiple objectives, such as path following and collision avoidance, while being more efficient to implement compared to traditional methods. In this study, a DRL agent is trained using the Deep Deterministic Policy Gradient (DDPG) algorithm for path following and waypoint tracking. Furthermore, the trained agent is evaluated against a traditional PD controller with an Integral Line of Sight (ILOS) guidance system for the same. This study uses the Kriso Container Ship (KCS) as a test case for evaluating the performance of different controllers. The ship's dynamics are modeled using the maneuvering Modelling Group (MMG) model. This mathematical simulation is used to train a DRL-based controller and to tune the gains of a traditional PD controller. The simulation environment is also used to assess the controller's effectiveness in the presence of wind.

{{</citation>}}


## cs.NE (1)



### (199/208) LC-TTFS: Towards Lossless Network Conversion for Spiking Neural Networks with TTFS Coding (Qu Yang et al., 2023)

{{<citation>}}

Qu Yang, Malu Zhang, Jibin Wu, Kay Chen Tan, Haizhou Li. (2023)  
**LC-TTFS: Towards Lossless Network Conversion for Spiking Neural Networks with TTFS Coding**  

---
Primary Category: cs.NE  
Categories: cs-NE, cs.NE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.14978v1)  

---


**ABSTRACT**  
The biological neurons use precise spike times, in addition to the spike firing rate, to communicate with each other. The time-to-first-spike (TTFS) coding is inspired by such biological observation. However, there is a lack of effective solutions for training TTFS-based spiking neural network (SNN). In this paper, we put forward a simple yet effective network conversion algorithm, which is referred to as LC-TTFS, by addressing two main problems that hinder an effective conversion from a high-performance artificial neural network (ANN) to a TTFS-based SNN. We show that our algorithm can achieve a near-perfect mapping between the activation values of an ANN and the spike times of an SNN on a number of challenging AI tasks, including image classification, image reconstruction, and speech enhancement. With TTFS coding, we can achieve up to orders of magnitude saving in computation over ANN and other rate-based SNNs. The study, therefore, paves the way for deploying ultra-low-power TTFS-based SNNs on power-constrained edge computing platforms.

{{</citation>}}


## cs.DS (1)



### (200/208) Bipartite ShockHash: Pruning ShockHash Search for Efficient Perfect Hashing (Hans-Peter Lehmann et al., 2023)

{{<citation>}}

Hans-Peter Lehmann, Peter Sanders, Stefan Walzer. (2023)  
**Bipartite ShockHash: Pruning ShockHash Search for Efficient Perfect Hashing**  

---
Primary Category: cs.DS  
Categories: cs-DS, cs.DS  
Keywords: Pruning  
[Paper Link](http://arxiv.org/abs/2310.14959v1)  

---


**ABSTRACT**  
A minimal perfect hash function (MPHF) maps a set of n keys to the first n integers without collisions. Representing this bijection needs at least $\log_2(e) \approx 1.443$ bits per key, and there is a wide range of practical implementations achieving about 2 bits per key. Minimal perfect hashing is a key ingredient in many compact data structures such as updatable retrieval data structures and approximate membership data structures.   A simple implementation reaching the space lower bound is to sample random hash functions using brute-force, which needs about $e^n \approx 2.718^n$ tries in expectation. ShockHash recently reduced that to about $(e/2)^n \approx 1.359^n$ tries in expectation by sampling random graphs. With bipartite ShockHash, we now sample random bipartite graphs. In this paper, we describe the general algorithmic ideas of bipartite ShockHash and give an experimental evaluation. The key insight is that we can try all combinations of two hash functions, each mapping into one half of the output range. This reduces the number of sampled hash functions to only about $(\sqrt{e/2})^n \approx 1.166^n$ in expectation. In itself, this does not reduce the asymptotic running time much because all combinations still need to be tested. However, by filtering the candidates before combining them, we can reduce this to less than $1.175^n$ combinations in expectation.   Our implementation of bipartite ShockHash is up to 3 orders of magnitude faster than original ShockHash. Inside the RecSplit framework, bipartite ShockHash-RS enables significantly larger base cases, leading to a construction that is, depending on the allotted space budget, up to 20 times faster. In our most extreme configuration, ShockHash-RS can build an MPHF for 10 million keys with 1.489 bits per key (within 3.3% of the lower bound) in about half an hour, pushing the limits of what is possible.

{{</citation>}}


## cs.SD (1)



### (201/208) Key Frame Mechanism For Efficient Conformer Based End-to-end Speech Recognition (Peng Fan et al., 2023)

{{<citation>}}

Peng Fan, Changhao Shan, Jianwei Zhang, Sining Sun, Qing Yang. (2023)  
**Key Frame Mechanism For Efficient Conformer Based End-to-end Speech Recognition**  

---
Primary Category: cs.SD  
Categories: cs-CL, cs-SD, cs.SD, eess-AS  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2310.14954v1)  

---


**ABSTRACT**  
Recently, Conformer as a backbone network for end-to-end automatic speech recognition achieved state-of-the-art performance. The Conformer block leverages a self-attention mechanism to capture global information, along with a convolutional neural network to capture local information, resulting in improved performance. However, the Conformer-based model encounters an issue with the self-attention mechanism, as computational complexity grows quadratically with the length of the input sequence. Inspired by previous Connectionist Temporal Classification (CTC) guided blank skipping during decoding, we introduce intermediate CTC outputs as guidance into the downsampling procedure of the Conformer encoder. We define the frame with non-blank output as key frame. Specifically, we introduce the key frame-based self-attention (KFSA) mechanism, a novel method to reduce the computation of the self-attention mechanism using key frames. The structure of our proposed approach comprises two encoders. Following the initial encoder, we introduce an intermediate CTC loss function to compute the label frame, enabling us to extract the key frames and blank frames for KFSA. Furthermore, we introduce the key frame-based downsampling (KFDS) mechanism to operate on high-dimensional acoustic features directly and drop the frames corresponding to blank labels, which results in new acoustic feature sequences as input to the second encoder. By using the proposed method, which achieves comparable or higher performance than vanilla Conformer and other similar work such as Efficient Conformer. Meantime, our proposed method can discard more than 60\% useless frames during model training and inference, which will accelerate the inference speed significantly. This work code is available in {https://github.com/scufan1990/Key-Frame-Mechanism-For-Efficient-Conformer}

{{</citation>}}


## cs.MM (1)



### (202/208) Intuitive Multilingual Audio-Visual Speech Recognition with a Single-Trained Model (Joanna Hong et al., 2023)

{{<citation>}}

Joanna Hong, Se Jin Park, Yong Man Ro. (2023)  
**Intuitive Multilingual Audio-Visual Speech Recognition with a Single-Trained Model**  

---
Primary Category: cs.MM  
Categories: cs-MM, cs-SD, cs.MM, eess-AS  
Keywords: Multilingual, Speech Recognition  
[Paper Link](http://arxiv.org/abs/2310.14946v1)  

---


**ABSTRACT**  
We present a novel approach to multilingual audio-visual speech recognition tasks by introducing a single model on a multilingual dataset. Motivated by a human cognitive system where humans can intuitively distinguish different languages without any conscious effort or guidance, we propose a model that can capture which language is given as an input speech by distinguishing the inherent similarities and differences between languages. To do so, we design a prompt fine-tuning technique into the largely pre-trained audio-visual representation model so that the network can recognize the language class as well as the speech with the corresponding language. Our work contributes to developing robust and efficient multilingual audio-visual speech recognition systems, reducing the need for language-specific models.

{{</citation>}}


## cs.IR (1)



### (203/208) Budgeted Embedding Table For Recommender Systems (Yunke Qu et al., 2023)

{{<citation>}}

Yunke Qu, Tong Chen, Quoc Viet Hung Nguyen, Hongzhi Yin. (2023)  
**Budgeted Embedding Table For Recommender Systems**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2310.14884v1)  

---


**ABSTRACT**  
At the heart of contemporary recommender systems (RSs) are latent factor models that provide quality recommendation experience to users. These models use embedding vectors, which are typically of a uniform and fixed size, to represent users and items. As the number of users and items continues to grow, this design becomes inefficient and hard to scale. Recent lightweight embedding methods have enabled different users and items to have diverse embedding sizes, but are commonly subject to two major drawbacks. Firstly, they limit the embedding size search to optimizing a heuristic balancing the recommendation quality and the memory complexity, where the trade-off coefficient needs to be manually tuned for every memory budget requested. The implicitly enforced memory complexity term can even fail to cap the parameter usage, making the resultant embedding table fail to meet the memory budget strictly. Secondly, most solutions, especially reinforcement learning based ones derive and optimize the embedding size for each each user/item on an instance-by-instance basis, which impedes the search efficiency. In this paper, we propose Budgeted Embedding Table (BET), a novel method that generates table-level actions (i.e., embedding sizes for all users and items) that is guaranteed to meet pre-specified memory budgets. Furthermore, by leveraging a set-based action formulation and engaging set representation learning, we present an innovative action search strategy powered by an action fitness predictor that efficiently evaluates each table-level action. Experiments have shown state-of-the-art performance on two real-world datasets when BET is paired with three popular recommender models under different memory budgets.

{{</citation>}}


## q-bio.GN (1)



### (204/208) Predicting Transcription Factor Binding Sites using Transformer based Capsule Network (Nimisha Ghosh et al., 2023)

{{<citation>}}

Nimisha Ghosh, Daniele Santoni, Indrajit Saha, Giovanni Felici. (2023)  
**Predicting Transcription Factor Binding Sites using Transformer based Capsule Network**  

---
Primary Category: q-bio.GN  
Categories: cs-AI, cs-LG, q-bio-GN, q-bio.GN  
Keywords: BERT, Transformer  
[Paper Link](http://arxiv.org/abs/2310.15202v1)  

---


**ABSTRACT**  
Prediction of binding sites for transcription factors is important to understand how they regulate gene expression and how this regulation can be modulated for therapeutic purposes. Although in the past few years there are significant works addressing this issue, there is still space for improvement. In this regard, a transformer based capsule network viz. DNABERT-Cap is proposed in this work to predict transcription factor binding sites mining ChIP-seq datasets. DNABERT-Cap is a bidirectional encoder pre-trained with large number of genomic DNA sequences, empowered with a capsule layer responsible for the final prediction. The proposed model builds a predictor for transcription factor binding sites using the joint optimisation of features encompassing both bidirectional encoder and capsule layer, along with convolutional and bidirectional long-short term memory layers. To evaluate the efficiency of the proposed approach, we use a benchmark ChIP-seq datasets of five cell lines viz. A549, GM12878, Hep-G2, H1-hESC and Hela, available in the ENCODE repository. The results show that the average area under the receiver operating characteristic curve score exceeds 0.91 for all such five cell lines. DNABERT-Cap is also compared with existing state-of-the-art deep learning based predictors viz. DeepARC, DeepTF, CNN-Zeng and DeepBind, and is seen to outperform them.

{{</citation>}}


## cs.DB (1)



### (205/208) SeLeP: Learning Based Semantic Prefetching for Exploratory Database Workloads (Farzaneh Zirak et al., 2023)

{{<citation>}}

Farzaneh Zirak, Farhana Choudhury, Renata Borovica-Gajic. (2023)  
**SeLeP: Learning Based Semantic Prefetching for Exploratory Database Workloads**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs.DB  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2310.14666v1)  

---


**ABSTRACT**  
Prefetching is a crucial technique employed in traditional databases to enhance interactivity, particularly in the context of data exploitation. Data exploration is a query processing paradigm in which users search for insights buried in the data, often not knowing what exactly they are looking for. Data exploratory tools deal with multiple challenges such as the need for interactivity with no a priori knowledge being present to help with the system tuning. The state-of-the-art prefetchers are specifically designed for navigational workloads only, where the number of possible actions is limited. The prefetchers that work with SQL-based workloads, on the other hand, mainly rely on data logical addresses rather than the data semantics. They fail to predict complex access patterns in cases where the database size is substantial, resulting in an extensive address space, or when there is frequent co-accessing of data. In this paper, we propose SeLeP, a semantic prefetcher that makes prefetching decisions for both types of workloads, based on the encoding of the data values contained inside the accessed blocks. Following the popular path of using machine learning approaches to automatically learn the hidden patterns, we formulate the prefetching task as a time-series forecasting problem and use an encoder-decoder LSTM architecture to learn the data access pattern. Our extensive experiments, across real-life exploratory workloads, demonstrate that SeLeP improves the hit ratio up to 40% and reduces I/O time up to 45% compared to the state-of-the-art, attaining impressive 95% hit ratio and 80% I/O reduction on average.

{{</citation>}}


## cs.SI (1)



### (206/208) Detecting Changes in Crowdsourced Social Media Images (Muhammad Umair et al., 2023)

{{<citation>}}

Muhammad Umair, Athman Bouguettaya, Abdallah Lakhdari. (2023)  
**Detecting Changes in Crowdsourced Social Media Images**  

---
Primary Category: cs.SI  
Categories: cs-SI, cs.SI  
Keywords: Social Media  
[Paper Link](http://arxiv.org/abs/2310.16848v1)  

---


**ABSTRACT**  
We propose a novel service framework to detect changes in crowdsourced images. We use a service-oriented approach to model and represent crowdsourced images as image services. Non-functional attributes of an image service are leveraged to detect changes in an image. The changes are reported in form of a version tree. The version tree is constructed in a way that it reflects the extent of changes introduced in different versions. Afterwards, we find semantic differences in between different versions to determine the extent of changes introduced in a specific version. Preliminary experimental results demonstrate the effectiveness of the proposed approach.

{{</citation>}}


## q-bio.QM (1)



### (207/208) K-Nearest-Neighbors Induced Topological PCA for scRNA Sequence Data Analysis (Sean Cottrell et al., 2023)

{{<citation>}}

Sean Cottrell, Yuta Hozumi, Guo-Wei Wei. (2023)  
**K-Nearest-Neighbors Induced Topological PCA for scRNA Sequence Data Analysis**  

---
Primary Category: q-bio.QM  
Categories: cs-LG, math-AT, q-bio-QM, q-bio.QM  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2310.14521v1)  

---


**ABSTRACT**  
Single-cell RNA sequencing (scRNA-seq) is widely used to reveal heterogeneity in cells, which has given us insights into cell-cell communication, cell differentiation, and differential gene expression. However, analyzing scRNA-seq data is a challenge due to sparsity and the large number of genes involved. Therefore, dimensionality reduction and feature selection are important for removing spurious signals and enhancing downstream analysis. Traditional PCA, a main workhorse in dimensionality reduction, lacks the ability to capture geometrical structure information embedded in the data, and previous graph Laplacian regularizations are limited by the analysis of only a single scale. We propose a topological Principal Components Analysis (tPCA) method by the combination of persistent Laplacian (PL) technique and L$_{2,1}$ norm regularization to address multiscale and multiclass heterogeneity issues in data. We further introduce a k-Nearest-Neighbor (kNN) persistent Laplacian technique to improve the robustness of our persistent Laplacian method. The proposed kNN-PL is a new algebraic topology technique which addresses the many limitations of the traditional persistent homology. Rather than inducing filtration via the varying of a distance threshold, we introduced kNN-tPCA, where filtrations are achieved by varying the number of neighbors in a kNN network at each step, and find that this framework has significant implications for hyper-parameter tuning. We validate the efficacy of our proposed tPCA and kNN-tPCA methods on 11 diverse benchmark scRNA-seq datasets, and showcase that our methods outperform other unsupervised PCA enhancements from the literature, as well as popular Uniform Manifold Approximation (UMAP), t-Distributed Stochastic Neighbor Embedding (tSNE), and Projection Non-Negative Matrix Factorization (NMF) by significant margins.

{{</citation>}}


## physics.ed-ph (1)



### (208/208) Reforming Physics Exams Using Openly Accessible Large Isomorphic Problem Banks created with the assistance of Generative AI: an Explorative Study (Zhongzhou Chen et al., 2023)

{{<citation>}}

Zhongzhou Chen, Emily Frederick, Colleen Cui, Munaimah Khan, Christopher Klatt, Mercedith Huang, Shiyang Su. (2023)  
**Reforming Physics Exams Using Openly Accessible Large Isomorphic Problem Banks created with the assistance of Generative AI: an Explorative Study**  

---
Primary Category: physics.ed-ph  
Categories: cs-CY, physics-ed-ph, physics.ed-ph  
Keywords: AI, GPT, Generative AI  
[Paper Link](http://arxiv.org/abs/2310.14498v1)  

---


**ABSTRACT**  
This paper explores using large isomorphic problem banks to overcome many challenges of traditional exams in large STEM classes, especially the threat of content sharing websites and generative AI to the security of exam items. We first introduce an efficient procedure for creating large numbers of isomorphic physics problems, assisted by the large language model GPT-3 and several other open-source tools. We then propose that if exam items are randomly drawn from large enough problem banks, then giving students open access to problem banks prior to the exam will not dramatically impact students' performance on the exam or lead to wide-spread rote-memorization of solutions. We tested this hypothesis on two mid-term physics exams, comparing students' performance on problems drawn from open isomorphic problem banks to similar transfer problems that were not accessible to students prior to the exam. We found that on both exams, both open bank and transfer problems had the highest difficulty. The differences in percent correct were between 5% to 10%, which is comparable to the differences between different isomorphic versions of the same problem type. Item response theory analysis found that both types of problem have high discrimination (>1.5) with no significant differences. Student performance on open-bank and transfer problems are highly correlated with each other, and the correlations are stronger than average correlations between problems on the exam. Exploratory factor analysis also found that open-bank and transfer problems load on the same factor, and even formed their own factor on the second exam. Those observations all suggest that giving students open access to large isomorphic problem banks only had a small impact on students' performance on the exam but could have significant potential in reforming traditional classroom exams.

{{</citation>}}
