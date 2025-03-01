---
draft: false
title: "arXiv @ 2023.11.08"
date: 2023-11-08
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.11.08"
    identifier: arxiv_20231108
    parent: 202311_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.LG (28)](#cslg-28)
- [cs.CL (37)](#cscl-37)
- [econ.GN (1)](#econgn-1)
- [cs.DS (1)](#csds-1)
- [cs.CR (2)](#cscr-2)
- [eess.SP (1)](#eesssp-1)
- [cs.DB (3)](#csdb-3)
- [cs.CV (24)](#cscv-24)
- [cs.HC (3)](#cshc-3)
- [cs.AI (5)](#csai-5)
- [cs.AR (1)](#csar-1)
- [cs.IR (2)](#csir-2)
- [eess.SY (2)](#eesssy-2)
- [cs.CY (1)](#cscy-1)
- [q-bio.GN (1)](#q-biogn-1)
- [eess.IV (3)](#eessiv-3)
- [quant-ph (2)](#quant-ph-2)
- [cs.RO (6)](#csro-6)
- [cs.SE (2)](#csse-2)
- [cs.NI (1)](#csni-1)
- [cs.MA (1)](#csma-1)
- [physics.soc-ph (1)](#physicssoc-ph-1)
- [cs.CE (2)](#csce-2)

## cs.LG (28)



### (1/130) CAFE: Carbon-Aware Federated Learning in Geographically Distributed Data Centers (Jieming Bian et al., 2023)

{{<citation>}}

Jieming Bian, Shaolei Ren, Jie Xu. (2023)  
**CAFE: Carbon-Aware Federated Learning in Geographically Distributed Data Centers**  

---
Primary Category: cs.LG  
Categories: cs-DC, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03615v1)  

---


**ABSTRACT**  
Training large-scale artificial intelligence (AI) models demands significant computational power and energy, leading to increased carbon footprint with potential environmental repercussions. This paper delves into the challenges of training AI models across geographically distributed (geo-distributed) data centers, emphasizing the balance between learning performance and carbon footprint. We consider Federated Learning (FL) as a solution, which prioritizes model parameter exchange over raw data, ensuring data privacy and compliance with local regulations. Given the variability in carbon intensity across regions, we propose a new framework called CAFE (short for Carbon-Aware Federated Learning) to optimize training within a fixed carbon footprint budget. Our approach incorporates coreset selection to assess learning performance, employs the Lyapunov drift-plus-penalty framework to address the unpredictability of future carbon intensity, and devises an efficient algorithm to address the combinatorial complexity of the data center selection. Through extensive simulations using real-world carbon intensity data, we demonstrate the efficacy of our algorithm, highlighting its superiority over existing methods in optimizing learning performance while minimizing environmental impact.

{{</citation>}}


### (2/130) Measuring Adversarial Datasets (Yuanchen Bai et al., 2023)

{{<citation>}}

Yuanchen Bai, Raoyi Huang, Vijay Viswanathan, Tzu-Sheng Kuo, Tongshuang Wu. (2023)  
**Measuring Adversarial Datasets**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-HC, cs-LG, cs.LG  
Keywords: AI, NLP  
[Paper Link](http://arxiv.org/abs/2311.03566v1)  

---


**ABSTRACT**  
In the era of widespread public use of AI systems across various domains, ensuring adversarial robustness has become increasingly vital to maintain safety and prevent undesirable errors. Researchers have curated various adversarial datasets (through perturbations) for capturing model deficiencies that cannot be revealed in standard benchmark datasets. However, little is known about how these adversarial examples differ from the original data points, and there is still no methodology to measure the intended and unintended consequences of those adversarial transformations. In this research, we conducted a systematic survey of existing quantifiable metrics that describe text instances in NLP tasks, among dimensions of difficulty, diversity, and disagreement. We selected several current adversarial effect datasets and compared the distributions between the original and their adversarial counterparts. The results provide valuable insights into what makes these datasets more challenging from a metrics perspective and whether they align with underlying assumptions.

{{</citation>}}


### (3/130) A Graph-Theoretic Framework for Understanding Open-World Semi-Supervised Learning (Yiyou Sun et al., 2023)

{{<citation>}}

Yiyou Sun, Zhenmei Shi, Yixuan Li. (2023)  
**A Graph-Theoretic Framework for Understanding Open-World Semi-Supervised Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Representation Learning, Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2311.03524v1)  

---


**ABSTRACT**  
Open-world semi-supervised learning aims at inferring both known and novel classes in unlabeled data, by harnessing prior knowledge from a labeled set with known classes. Despite its importance, there is a lack of theoretical foundations for this problem. This paper bridges the gap by formalizing a graph-theoretic framework tailored for the open-world setting, where the clustering can be theoretically characterized by graph factorization. Our graph-theoretic framework illuminates practical algorithms and provides guarantees. In particular, based on our graph formulation, we apply the algorithm called Spectral Open-world Representation Learning (SORL), and show that minimizing our loss is equivalent to performing spectral decomposition on the graph. Such equivalence allows us to derive a provable error bound on the clustering performance for both known and novel classes, and analyze rigorously when labeled data helps. Empirically, SORL can match or outperform several strong baselines on common benchmark datasets, which is appealing for practical usage while enjoying theoretical guarantees.

{{</citation>}}


### (4/130) The Fairness Stitch: Unveiling the Potential of Model Stitching in Neural Network De-Biasing (Modar Sulaiman et al., 2023)

{{<citation>}}

Modar Sulaiman, Kallol Roy. (2023)  
**The Fairness Stitch: Unveiling the Potential of Model Stitching in Neural Network De-Biasing**  

---
Primary Category: cs.LG  
Categories: cs-IT, cs-LG, cs.LG, math-IT  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2311.03532v1)  

---


**ABSTRACT**  
The pursuit of fairness in machine learning models has emerged as a critical research challenge in different applications ranging from bank loan approval to face detection. Despite the widespread adoption of artificial intelligence algorithms across various domains, concerns persist regarding the presence of biases and discrimination within these models. To address this pressing issue, this study introduces a novel method called "The Fairness Stitch (TFS)" to enhance fairness in deep learning models. This method combines model stitching and training jointly, while incorporating fairness constraints. In this research, we assess the effectiveness of our proposed method by conducting a comprehensive evaluation of two well-known datasets, CelebA and UTKFace. We systematically compare the performance of our approach with the existing baseline method. Our findings reveal a notable improvement in achieving a balanced trade-off between fairness and performance, highlighting the promising potential of our method to address bias-related challenges and foster equitable outcomes in machine learning models. This paper poses a challenge to the conventional wisdom of the effectiveness of the last layer in deep learning models for de-biasing.

{{</citation>}}


### (5/130) Brain Networks and Intelligence: A Graph Neural Network Based Approach to Resting State fMRI Data (Bishal Thapaliya et al., 2023)

{{<citation>}}

Bishal Thapaliya, Esra Akbas, Jiayu Chen, Raam Sapkota, Bhaskar Ray, Pranav Suresh, Vince Calhoun, Jingyu Liu. (2023)  
**Brain Networks and Intelligence: A Graph Neural Network Based Approach to Resting State fMRI Data**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, q-bio-NC  
Keywords: Graph Neural Network  
[Paper Link](http://arxiv.org/abs/2311.03520v1)  

---


**ABSTRACT**  
Resting-state functional magnetic resonance imaging (rsfMRI) is a powerful tool for investigating the relationship between brain function and cognitive processes as it allows for the functional organization of the brain to be captured without relying on a specific task or stimuli. In this paper, we present a novel modeling architecture called BrainRGIN for predicting intelligence (fluid, crystallized, and total intelligence) using graph neural networks on rsfMRI derived static functional network connectivity matrices. Extending from the existing graph convolution networks, our approach incorporates a clustering-based embedding and graph isomorphism network in the graph convolutional layer to reflect the nature of the brain sub-network organization and efficient network expression, in combination with TopK pooling and attention-based readout functions. We evaluated our proposed architecture on a large dataset, specifically the Adolescent Brain Cognitive Development Dataset, and demonstrated its effectiveness in predicting individual differences in intelligence. Our model achieved lower mean squared errors and higher correlation scores than existing relevant graph architectures and other traditional machine learning models for all of the intelligence prediction tasks. The middle frontal gyrus exhibited a significant contribution to both fluid and crystallized intelligence, suggesting their pivotal role in these cognitive processes. Total composite scores identified a diverse set of brain regions to be relevant which underscores the complex nature of total intelligence.

{{</citation>}}


### (6/130) Uni-O4: Unifying Online and Offline Deep Reinforcement Learning with Multi-Step On-Policy Optimization (Kun Lei et al., 2023)

{{<citation>}}

Kun Lei, Zhengmao He, Chenhao Lu, Kaizhe Hu, Yang Gao, Huazhe Xu. (2023)  
**Uni-O4: Unifying Online and Offline Deep Reinforcement Learning with Multi-Step On-Policy Optimization**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-RO, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.03351v1)  

---


**ABSTRACT**  
Combining offline and online reinforcement learning (RL) is crucial for efficient and safe learning. However, previous approaches treat offline and online learning as separate procedures, resulting in redundant designs and limited performance. We ask: Can we achieve straightforward yet effective offline and online learning without introducing extra conservatism or regularization? In this study, we propose Uni-o4, which utilizes an on-policy objective for both offline and online learning. Owning to the alignment of objectives in two phases, the RL agent can transfer between offline and online learning seamlessly. This property enhances the flexibility of the learning paradigm, allowing for arbitrary combinations of pretraining, fine-tuning, offline, and online learning. In the offline phase, specifically, Uni-o4 leverages diverse ensemble policies to address the mismatch issues between the estimated behavior policy and the offline dataset. Through a simple offline policy evaluation (OPE) approach, Uni-o4 can achieve multi-step policy improvement safely. We demonstrate that by employing the method above, the fusion of these two paradigms can yield superior offline initialization as well as stable and rapid online fine-tuning capabilities. Through real-world robot tasks, we highlight the benefits of this paradigm for rapid deployment in challenging, previously unseen real-world environments. Additionally, through comprehensive evaluations using numerous simulated benchmarks, we substantiate that our method achieves state-of-the-art performance in both offline and offline-to-online fine-tuning learning. Our website: https://lei-kun.github.io/uni-o4/ .

{{</citation>}}


### (7/130) TS-Diffusion: Generating Highly Complex Time Series with Diffusion Models (Yangming Li, 2023)

{{<citation>}}

Yangming Li. (2023)  
**TS-Diffusion: Generating Highly Complex Time Series with Diffusion Models**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2311.03303v1)  

---


**ABSTRACT**  
While current generative models have achieved promising performances in time-series synthesis, they either make strong assumptions on the data format (e.g., regularities) or rely on pre-processing approaches (e.g., interpolations) to simplify the raw data. In this work, we consider a class of time series with three common bad properties, including sampling irregularities, missingness, and large feature-temporal dimensions, and introduce a general model, TS-Diffusion, to process such complex time series. Our model consists of three parts under the framework of point process. The first part is an encoder of the neural ordinary differential equation (ODE) that converts time series into dense representations, with the jump technique to capture sampling irregularities and self-attention mechanism to handle missing values; The second component of TS-Diffusion is a diffusion model that learns from the representation of time series. These time-series representations can have a complex distribution because of their high dimensions; The third part is a decoder of another ODE that generates time series with irregularities and missing values given their representations. We have conducted extensive experiments on multiple time-series datasets, demonstrating that TS-Diffusion achieves excellent results on both conventional and complex time series and significantly outperforms previous baselines.

{{</citation>}}


### (8/130) GQKVA: Efficient Pre-training of Transformers by Grouping Queries, Keys, and Values (Farnoosh Javadi et al., 2023)

{{<citation>}}

Farnoosh Javadi, Walid Ahmed, Habib Hajimolahoseini, Foozhan Ataiefard, Mohammad Hassanpour, Saina Asani, Austin Wen, Omar Mohamed Awad, Kangling Liu, Yang Liu. (2023)  
**GQKVA: Efficient Pre-training of Transformers by Grouping Queries, Keys, and Values**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs.LG  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.03426v1)  

---


**ABSTRACT**  
Massive transformer-based models face several challenges, including slow and computationally intensive pre-training and over-parametrization. This paper addresses these challenges by proposing a versatile method called GQKVA, which generalizes query, key, and value grouping techniques. GQKVA is designed to speed up transformer pre-training while reducing the model size. Our experiments with various GQKVA variants highlight a clear trade-off between performance and model size, allowing for customized choices based on resource and time limitations. Our findings also indicate that the conventional multi-head attention approach is not always the best choice, as there are lighter and faster alternatives available. We tested our method on ViT, which achieved an approximate 0.3% increase in accuracy while reducing the model size by about 4% in the task of image classification. Additionally, our most aggressive model reduction experiment resulted in a reduction of approximately 15% in model size, with only around a 1% drop in accuracy.

{{</citation>}}


### (9/130) Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges (Chenhang Cui et al., 2023)

{{<citation>}}

Chenhang Cui, Yiyang Zhou, Xinyu Yang, Shirley Wu, Linjun Zhang, James Zou, Huaxiu Yao. (2023)  
**Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-CV, cs-LG, cs.LG  
Keywords: Bias, GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2311.03287v2)  

---


**ABSTRACT**  
While GPT-4V(ision) impressively models both visual and textual information simultaneously, it's hallucination behavior has not been systematically assessed. To bridge this gap, we introduce a new benchmark, namely, the Bias and Interference Challenges in Visual Language Models (Bingo). This benchmark is designed to evaluate and shed light on the two common types of hallucinations in visual language models: bias and interference. Here, bias refers to the model's tendency to hallucinate certain types of responses, possibly due to imbalance in its training data. Interference pertains to scenarios where the judgment of GPT-4V(ision) can be disrupted due to how the text prompt is phrased or how the input image is presented. We identify a notable regional bias, whereby GPT-4V(ision) is better at interpreting Western images or images with English writing compared to images from other countries or containing text in other languages. Moreover, GPT-4V(ision) is vulnerable to leading questions and is often confused when interpreting multiple images together. Popular mitigation approaches, such as self-correction and chain-of-thought reasoning, are not effective in resolving these challenges. We also identified similar biases and interference vulnerabilities with LLaVA and Bard. Our results characterize the hallucination challenges in GPT-4V(ision) and state-of-the-art visual-language models, and highlight the need for new solutions. The Bingo benchmark is available at https://github.com/gzcch/Bingo.

{{</citation>}}


### (10/130) Exploiting Latent Attribute Interaction with Transformer on Heterogeneous Information Networks (Zeyuan Zhao et al., 2023)

{{<citation>}}

Zeyuan Zhao, Qingqing Ge, Anfeng Cheng, Yiding Liu, Xiang Li, Shuaiqiang Wang. (2023)  
**Exploiting Latent Attribute Interaction with Transformer on Heterogeneous Information Networks**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-SI, cs.LG  
Keywords: GNN, Transformer  
[Paper Link](http://arxiv.org/abs/2311.03275v1)  

---


**ABSTRACT**  
Heterogeneous graph neural networks (HGNNs) have recently shown impressive capability in modeling heterogeneous graphs that are ubiquitous in real-world applications. Due to the diversity of attributes of nodes in different types, most existing models first align nodes by mapping them into the same low-dimensional space. However, in this way, they lose the type information of nodes. In addition, most of them only consider the interactions between nodes while neglecting the high-order information behind the latent interactions among different node features. To address these problems, in this paper, we propose a novel heterogeneous graph model MULAN, including two major components, i.e., a type-aware encoder and a dimension-aware encoder. Specifically, the type-aware encoder compensates for the loss of node type information and better leverages graph heterogeneity in learning node representations. Built upon transformer architecture, the dimension-aware encoder is capable of capturing the latent interactions among the diverse node features. With these components, the information of graph heterogeneity, node features and graph structure can be comprehensively encoded in node representations. We conduct extensive experiments on six heterogeneous benchmark datasets, which demonstrates the superiority of MULAN over other state-of-the-art competitors and also shows that MULAN is efficient.

{{</citation>}}


### (11/130) An AI-Guided Data Centric Strategy to Detect and Mitigate Biases in Healthcare Datasets (Faris F. Gulamali et al., 2023)

{{<citation>}}

Faris F. Gulamali, Ashwin S. Sawant, Lora Liharska, Carol R. Horowitz, Lili Chan, Patricia H. Kovatch, Ira Hofer, Karandeep Singh, Lynne D. Richardson, Emmanuel Mensah, Alexander W Charney, David L. Reich, Jianying Hu, Girish N. Nadkarni. (2023)  
**An AI-Guided Data Centric Strategy to Detect and Mitigate Biases in Healthcare Datasets**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI, Bias  
[Paper Link](http://arxiv.org/abs/2311.03425v1)  

---


**ABSTRACT**  
The adoption of diagnosis and prognostic algorithms in healthcare has led to concerns about the perpetuation of bias against disadvantaged groups of individuals. Deep learning methods to detect and mitigate bias have revolved around modifying models, optimization strategies, and threshold calibration with varying levels of success. Here, we generate a data-centric, model-agnostic, task-agnostic approach to evaluate dataset bias by investigating the relationship between how easily different groups are learned at small sample sizes (AEquity). We then apply a systematic analysis of AEq values across subpopulations to identify and mitigate manifestations of racial bias in two known cases in healthcare - Chest X-rays diagnosis with deep convolutional neural networks and healthcare utilization prediction with multivariate logistic regression. AEq is a novel and broadly applicable metric that can be applied to advance equity by diagnosing and remediating bias in healthcare datasets.

{{</citation>}}


### (12/130) From Coupled Oscillators to Graph Neural Networks: Reducing Over-smoothing via a Kuramoto Model-based Approach (Tuan Nguyen et al., 2023)

{{<citation>}}

Tuan Nguyen, Tan M. Nguyen, Hirotada Honda, Takashi Sano, Vinh Nguyen, Shugo Nakamura. (2023)  
**From Coupled Oscillators to Graph Neural Networks: Reducing Over-smoothing via a Kuramoto Model-based Approach**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ML  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2311.03260v1)  

---


**ABSTRACT**  
We propose the Kuramoto Graph Neural Network (KuramotoGNN), a novel class of continuous-depth graph neural networks (GNNs) that employs the Kuramoto model to mitigate the over-smoothing phenomenon, in which node features in GNNs become indistinguishable as the number of layers increases. The Kuramoto model captures the synchronization behavior of non-linear coupled oscillators. Under the view of coupled oscillators, we first show the connection between Kuramoto model and basic GNN and then over-smoothing phenomenon in GNNs can be interpreted as phase synchronization in Kuramoto model. The KuramotoGNN replaces this phase synchronization with frequency synchronization to prevent the node features from converging into each other while allowing the system to reach a stable synchronized state. We experimentally verify the advantages of the KuramotoGNN over the baseline GNNs and existing methods in reducing over-smoothing on various graph deep learning benchmark tasks.

{{</citation>}}


### (13/130) p-Laplacian Transformer (Tuan Nguyen et al., 2023)

{{<citation>}}

Tuan Nguyen, Tam Nguyen, Vinh Nguyen, Tan M. Nguyen. (2023)  
**p-Laplacian Transformer**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG, stat-ML  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2311.03235v1)  

---


**ABSTRACT**  
$p$-Laplacian regularization, rooted in graph and image signal processing, introduces a parameter $p$ to control the regularization effect on these data. Smaller values of $p$ promote sparsity and interpretability, while larger values encourage smoother solutions. In this paper, we first show that the self-attention mechanism obtains the minimal Laplacian regularization ($p=2$) and encourages the smoothness in the architecture. However, the smoothness is not suitable for the heterophilic structure of self-attention in transformers where attention weights between tokens that are in close proximity and non-close ones are assigned indistinguishably. From that insight, we then propose a novel class of transformers, namely the $p$-Laplacian Transformer (p-LaT), which leverages $p$-Laplacian regularization framework to harness the heterophilic features within self-attention layers. In particular, low $p$ values will effectively assign higher attention weights to tokens that are in close proximity to the current token being processed. We empirically demonstrate the advantages of p-LaT over the baseline transformers on a wide range of benchmark datasets.

{{</citation>}}


### (14/130) Navigating Scaling Laws: Accelerating Vision Transformer's Training via Adaptive Strategies (Sotiris Anagnostidis et al., 2023)

{{<citation>}}

Sotiris Anagnostidis, Gregor Bachmann, Thomas Hofmann. (2023)  
**Navigating Scaling Laws: Accelerating Vision Transformer's Training via Adaptive Strategies**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.03233v1)  

---


**ABSTRACT**  
In recent years, the state-of-the-art in deep learning has been dominated by very large models that have been pre-trained on vast amounts of data. The paradigm is very simple: Investing more computational resources (optimally) leads to better performance, and even predictably so; neural scaling laws have been derived that accurately forecast the performance of a network for a desired level of compute. This leads to the notion of a "compute-optimal" model, i.e. a model that allocates a given level of compute during training optimally to maximise performance. In this work, we extend the concept of optimality by allowing for an "adaptive" model, i.e. a model that can change its shape during the course of training. By allowing the shape to adapt, we can optimally traverse between the underlying scaling laws, leading to a significant reduction in the required compute to reach a given target performance. We focus on vision tasks and the family of Vision Transformers, where the patch size as well as the width naturally serve as adaptive shape parameters. We demonstrate that, guided by scaling laws, we can design compute-optimal adaptive models that beat their "static" counterparts.

{{</citation>}}


### (15/130) DeepInception: Hypnotize Large Language Model to Be Jailbreaker (Xuan Li et al., 2023)

{{<citation>}}

Xuan Li, Zhanke Zhou, Jianing Zhu, Jiangchao Yao, Tongliang Liu, Bo Han. (2023)  
**DeepInception: Hypnotize Large Language Model to Be Jailbreaker**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs.LG  
Keywords: Falcon, GPT, GPT-3.5, Language Model  
[Paper Link](http://arxiv.org/abs/2311.03191v1)  

---


**ABSTRACT**  
Despite remarkable success in various applications, large language models (LLMs) are vulnerable to adversarial jailbreaks that make the safety guardrails void. However, previous studies for jailbreaks usually resort to brute-force optimization or extrapolations of a high computation cost, which might not be practical or effective. In this paper, inspired by the Milgram experiment that individuals can harm another person if they are told to do so by an authoritative figure, we disclose a lightweight method, termed as DeepInception, which can easily hypnotize LLM to be a jailbreaker and unlock its misusing risks. Specifically, DeepInception leverages the personification ability of LLM to construct a novel nested scene to behave, which realizes an adaptive way to escape the usage control in a normal scenario and provides the possibility for further direct jailbreaks. Empirically, we conduct comprehensive experiments to show its efficacy. Our DeepInception can achieve competitive jailbreak success rates with previous counterparts and realize a continuous jailbreak in subsequent interactions, which reveals the critical weakness of self-losing on both open/closed-source LLMs like Falcon, Vicuna, Llama-2, and GPT-3.5/4/4V. Our investigation appeals that people should pay more attention to the safety aspects of LLMs and a stronger defense against their misuse risks. The code is publicly available at: https://github.com/tmlr-group/DeepInception.

{{</citation>}}


### (16/130) Equivariance Is Not All You Need: Characterizing the Utility of Equivariant Graph Neural Networks for Particle Physics Tasks (Savannah Thais et al., 2023)

{{<citation>}}

Savannah Thais, Daniel Murnane. (2023)  
**Equivariance Is Not All You Need: Characterizing the Utility of Equivariant Graph Neural Networks for Particle Physics Tasks**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, hep-ex  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2311.03094v1)  

---


**ABSTRACT**  
Incorporating inductive biases into ML models is an active area of ML research, especially when ML models are applied to data about the physical world. Equivariant Graph Neural Networks (GNNs) have recently become a popular method for learning from physics data because they directly incorporate the symmetries of the underlying physical system. Drawing from the relevant literature around group equivariant networks, this paper presents a comprehensive evaluation of the proposed benefits of equivariant GNNs by using real-world particle physics reconstruction tasks as an evaluation test-bed. We demonstrate that many of the theoretical benefits generally associated with equivariant networks may not hold for realistic systems and introduce compelling directions for future research that will benefit both the scientific theory of ML and physics applications.

{{</citation>}}


### (17/130) Beyond Words: A Mathematical Framework for Interpreting Large Language Models (Javier González et al., 2023)

{{<citation>}}

Javier González, Aditya V. Nori. (2023)  
**Beyond Words: A Mathematical Framework for Interpreting Large Language Models**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2311.03033v1)  

---


**ABSTRACT**  
Large language models (LLMs) are powerful AI tools that can generate and comprehend natural language text and other complex information. However, the field lacks a mathematical framework to systematically describe, compare and improve LLMs. We propose Hex a framework that clarifies key terms and concepts in LLM research, such as hallucinations, alignment, self-verification and chain-of-thought reasoning. The Hex framework offers a precise and consistent way to characterize LLMs, identify their strengths and weaknesses, and integrate new findings. Using Hex, we differentiate chain-of-thought reasoning from chain-of-thought prompting and establish the conditions under which they are equivalent. This distinction clarifies the basic assumptions behind chain-of-thought prompting and its implications for methods that use it, such as self-verification and prompt programming.   Our goal is to provide a formal framework for LLMs that can help both researchers and practitioners explore new possibilities for generative AI. We do not claim to have a definitive solution, but rather a tool for opening up new research avenues. We argue that our formal definitions and results are crucial for advancing the discussion on how to build generative AI systems that are safe, reliable, fair and robust, especially in domains like healthcare and software engineering.

{{</citation>}}


### (18/130) Federated Learning for Clinical Structured Data: A Benchmark Comparison of Engineering and Statistical Approaches (Siqi Li et al., 2023)

{{<citation>}}

Siqi Li, Di Miao, Qiming Wu, Chuan Hong, Danny D'Agostino, Xin Li, Yilin Ning, Yuqing Shang, Huazhu Fu, Marcus Eng Hock Ong, Hamed Haddadi, Nan Liu. (2023)  
**Federated Learning for Clinical Structured Data: A Benchmark Comparison of Engineering and Statistical Approaches**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Clinical  
[Paper Link](http://arxiv.org/abs/2311.03417v1)  

---


**ABSTRACT**  
Federated learning (FL) has shown promising potential in safeguarding data privacy in healthcare collaborations. While the term "FL" was originally coined by the engineering community, the statistical field has also explored similar privacy-preserving algorithms. Statistical FL algorithms, however, remain considerably less recognized than their engineering counterparts. Our goal was to bridge the gap by presenting the first comprehensive comparison of FL frameworks from both engineering and statistical domains. We evaluated five FL frameworks using both simulated and real-world data. The results indicate that statistical FL algorithms yield less biased point estimates for model coefficients and offer convenient confidence interval estimations. In contrast, engineering-based methods tend to generate more accurate predictions, sometimes surpassing central pooled and statistical FL models. This study underscores the relative strengths and weaknesses of both types of methods, emphasizing the need for increased awareness and their integration in future FL applications.

{{</citation>}}


### (19/130) Strong statistical parity through fair synthetic data (Ivona Krchova et al., 2023)

{{<citation>}}

Ivona Krchova, Michael Platzer, Paul Tiwald. (2023)  
**Strong statistical parity through fair synthetic data**  

---
Primary Category: cs.LG  
Categories: cs-CY, cs-LG, cs.LG, stat-ML  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03000v1)  

---


**ABSTRACT**  
AI-generated synthetic data, in addition to protecting the privacy of original data sets, allows users and data consumers to tailor data to their needs. This paper explores the creation of synthetic data that embodies Fairness by Design, focusing on the statistical parity fairness definition. By equalizing the learned target probability distributions of the synthetic data generator across sensitive attributes, a downstream model trained on such synthetic data provides fair predictions across all thresholds, that is, strong fair predictions even when inferring from biased, original data. This fairness adjustment can be either directly integrated into the sampling process of a synthetic generator or added as a post-processing step. The flexibility allows data consumers to create fair synthetic data and fine-tune the trade-off between accuracy and fairness without any previous assumptions on the data or re-training the synthetic data generator.

{{</citation>}}


### (20/130) PowerFlowNet: Leveraging Message Passing GNNs for Improved Power Flow Approximation (Nan Lin et al., 2023)

{{<citation>}}

Nan Lin, Stavros Orfanoudakis, Nathan Ordonez Cardenas, Juan S. Giraldo, Pedro P. Vergara. (2023)  
**PowerFlowNet: Leveraging Message Passing GNNs for Improved Power Flow Approximation**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SY, cs.LG, eess-SY  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2311.03415v1)  

---


**ABSTRACT**  
Accurate and efficient power flow (PF) analysis is crucial in modern electrical networks' efficient operation and planning. Therefore, there is a need for scalable algorithms capable of handling large-scale power networks that can provide accurate and fast solutions. Graph Neural Networks (GNNs) have emerged as a promising approach for enhancing the speed of PF approximations by leveraging their ability to capture distinctive features from the underlying power network graph. In this study, we introduce PowerFlowNet, a novel GNN architecture for PF approximation that showcases similar performance with the traditional Newton-Raphson method but achieves it 4 times faster in the simple IEEE 14-bus system and 145 times faster in the realistic case of the French high voltage network (6470rte). Meanwhile, it significantly outperforms other traditional approximation methods, such as the DC relaxation method, in terms of performance and execution time; therefore, making PowerFlowNet a highly promising solution for real-world PF analysis. Furthermore, we verify the efficacy of our approach by conducting an in-depth experimental evaluation, thoroughly examining the performance, scalability, interpretability, and architectural dependability of PowerFlowNet. The evaluation provides insights into the behavior and potential applications of GNNs in power system analysis.

{{</citation>}}


### (21/130) Understanding Deep Representation Learning via Layerwise Feature Compression and Discrimination (Peng Wang et al., 2023)

{{<citation>}}

Peng Wang, Xiao Li, Can Yaras, Zhihui Zhu, Laura Balzano, Wei Hu, Qing Qu. (2023)  
**Understanding Deep Representation Learning via Layerwise Feature Compression and Discrimination**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG, math-OC  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2311.02960v1)  

---


**ABSTRACT**  
Over the past decade, deep learning has proven to be a highly effective tool for learning meaningful features from raw data. However, it remains an open question how deep networks perform hierarchical feature learning across layers. In this work, we attempt to unveil this mystery by investigating the structures of intermediate features. Motivated by our empirical findings that linear layers mimic the roles of deep layers in nonlinear networks for feature learning, we explore how deep linear networks transform input data into output by investigating the output (i.e., features) of each layer after training in the context of multi-class classification problems. Toward this goal, we first define metrics to measure within-class compression and between-class discrimination of intermediate features, respectively. Through theoretical analysis of these two metrics, we show that the evolution of features follows a simple and quantitative pattern from shallow to deep layers when the input data is nearly orthogonal and the network weights are minimum-norm, balanced, and approximate low-rank: Each layer of the linear network progressively compresses within-class features at a geometric rate and discriminates between-class features at a linear rate with respect to the number of layers that data have passed through. To the best of our knowledge, this is the first quantitative characterization of feature evolution in hierarchical representations of deep linear networks. Empirically, our extensive experiments not only validate our theoretical results numerically but also reveal a similar pattern in deep nonlinear networks which aligns well with recent empirical studies. Moreover, we demonstrate the practical implications of our results in transfer learning. Our code is available at \url{https://github.com/Heimine/PNC_DLN}.

{{</citation>}}


### (22/130) The Pursuit of Human Labeling: A New Perspective on Unsupervised Learning (Artyom Gadetsky et al., 2023)

{{<citation>}}

Artyom Gadetsky, Maria Brbic. (2023)  
**The Pursuit of Human Labeling: A New Perspective on Unsupervised Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2311.02940v1)  

---


**ABSTRACT**  
We present HUME, a simple model-agnostic framework for inferring human labeling of a given dataset without any external supervision. The key insight behind our approach is that classes defined by many human labelings are linearly separable regardless of the representation space used to represent a dataset. HUME utilizes this insight to guide the search over all possible labelings of a dataset to discover an underlying human labeling. We show that the proposed optimization objective is strikingly well-correlated with the ground truth labeling of the dataset. In effect, we only train linear classifiers on top of pretrained representations that remain fixed during training, making our framework compatible with any large pretrained and self-supervised model. Despite its simplicity, HUME outperforms a supervised linear classifier on top of self-supervised representations on the STL-10 dataset by a large margin and achieves comparable performance on the CIFAR-10 dataset. Compared to the existing unsupervised baselines, HUME achieves state-of-the-art performance on four benchmark image classification datasets including the large-scale ImageNet-1000 dataset. Altogether, our work provides a fundamentally new view to tackle unsupervised learning by searching for consistent labelings between different representation spaces.

{{</citation>}}


### (23/130) Distributed Matrix-Based Sampling for Graph Neural Network Training (Alok Tripathy et al., 2023)

{{<citation>}}

Alok Tripathy, Katherine Yelick, Aydin Buluc. (2023)  
**Distributed Matrix-Based Sampling for Graph Neural Network Training**  

---
Primary Category: cs.LG  
Categories: cs-DC, cs-LG, cs-PF, cs.LG  
Keywords: GNN, Graph Neural Network  
[Paper Link](http://arxiv.org/abs/2311.02909v1)  

---


**ABSTRACT**  
The primary contribution of this paper is new methods for reducing communication in the sampling step for distributed GNN training. Here, we propose a matrix-based bulk sampling approach that expresses sampling as a sparse matrix multiplication (SpGEMM) and samples multiple minibatches at once. When the input graph topology does not fit on a single device, our method distributes the graph and use communication-avoiding SpGEMM algorithms to scale GNN minibatch sampling, enabling GNN training on much larger graphs than those that can fit into a single device memory. When the input graph topology (but not the embeddings) fits in the memory of one GPU, our approach (1) performs sampling without communication, (2) amortizes the overheads of sampling a minibatch, and (3) can represent multiple sampling algorithms by simply using different matrix constructions. In addition to new methods for sampling, we show that judiciously replicating feature data with a simple all-to-all exchange can outperform current methods for the feature extraction step in distributed GNN training. We provide experimental results on the largest Open Graph Benchmark (OGB) datasets on $128$ GPUs, and show that our pipeline is $2.5\times$ faster Quiver (a distributed extension to PyTorch-Geometric) on a $3$-layer GraphSAGE network. On datasets outside of OGB, we show a $8.46\times$ speedup on $128$ GPUs in-per epoch time. Finally, we show scaling when the graph is distributed across GPUs and scaling for both node-wise and layer-wise sampling algorithms

{{</citation>}}


### (24/130) MultiSPANS: A Multi-range Spatial-Temporal Transformer Network for Traffic Forecast via Structural Entropy Optimization (Dongcheng Zou et al., 2023)

{{<citation>}}

Dongcheng Zou, Senzhang Wang, Xuefeng Li, Hao Peng, Yuandong Wang, Chunyang Liu, Kehua Sheng, Bo Zhang. (2023)  
**MultiSPANS: A Multi-range Spatial-Temporal Transformer Network for Traffic Forecast via Structural Entropy Optimization**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.02880v1)  

---


**ABSTRACT**  
Traffic forecasting is a complex multivariate time-series regression task of paramount importance for traffic management and planning. However, existing approaches often struggle to model complex multi-range dependencies using local spatiotemporal features and road network hierarchical knowledge. To address this, we propose MultiSPANS. First, considering that an individual recording point cannot reflect critical spatiotemporal local patterns, we design multi-filter convolution modules for generating informative ST-token embeddings to facilitate attention computation. Then, based on ST-token and spatial-temporal position encoding, we employ the Transformers to capture long-range temporal and spatial dependencies. Furthermore, we introduce structural entropy theory to optimize the spatial attention mechanism. Specifically, The structural entropy minimization algorithm is used to generate optimal road network hierarchies, i.e., encoding trees. Based on this, we propose a relative structural entropy-based position encoding and a multi-head attention masking scheme based on multi-layer encoding trees. Extensive experiments demonstrate the superiority of the presented framework over several state-of-the-art methods in real-world traffic datasets, and the longer historical windows are effectively utilized. The code is available at https://github.com/SELGroup/MultiSPANS.

{{</citation>}}


### (25/130) Exploring Active Learning in Meta-Learning: Enhancing Context Set Labeling (Wonho Bae et al., 2023)

{{<citation>}}

Wonho Bae, Jing Wang, Danica J. Sutherland. (2023)  
**Exploring Active Learning in Meta-Learning: Enhancing Context Set Labeling**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Active Learning  
[Paper Link](http://arxiv.org/abs/2311.02879v1)  

---


**ABSTRACT**  
Most meta-learning methods assume that the (very small) context set used to establish a new task at test time is passively provided. In some settings, however, it is feasible to actively select which points to label; the potential gain from a careful choice is substantial, but the setting requires major differences from typical active learning setups. We clarify the ways in which active meta-learning can be used to label a context set, depending on which parts of the meta-learning process use active learning. Within this framework, we propose a natural algorithm based on fitting Gaussian mixtures for selecting which points to label; though simple, the algorithm also has theoretical motivation. The proposed algorithm outperforms state-of-the-art active learning methods when used with various meta-learning algorithms across several benchmark datasets.

{{</citation>}}


### (26/130) Prioritized Propagation in Graph Neural Networks (Yao Cheng et al., 2023)

{{<citation>}}

Yao Cheng, Minjie Chen, Xiang Li, Caihua Shan, Ming Gao. (2023)  
**Prioritized Propagation in Graph Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2311.02832v1)  

---


**ABSTRACT**  
Graph neural networks (GNNs) have recently received significant attention. Learning node-wise message propagation in GNNs aims to set personalized propagation steps for different nodes in the graph. Despite the success, existing methods ignore node priority that can be reflected by node influence and heterophily. In this paper, we propose a versatile framework PPro, which can be integrated with most existing GNN models and aim to learn prioritized node-wise message propagation in GNNs. Specifically, the framework consists of three components: a backbone GNN model, a propagation controller to determine the optimal propagation steps for nodes, and a weight controller to compute the priority scores for nodes. We design a mutually enhanced mechanism to compute node priority, optimal propagation step and label prediction. We also propose an alternative optimization strategy to learn the parameters in the backbone GNN model and two parametric controllers. We conduct extensive experiments to compare our framework with other 11 state-of-the-art competitors on 8 benchmark datasets. Experimental results show that our framework can lead to superior performance in terms of propagation strategies and node representations.

{{</citation>}}


### (27/130) QualEval: Qualitative Evaluation for Model Improvement (Vishvak Murahari et al., 2023)

{{<citation>}}

Vishvak Murahari, Ameet Deshpande, Peter Clark, Tanmay Rajpurohit, Ashish Sabharwal, Karthik Narasimhan, Ashwin Kalyan. (2023)  
**QualEval: Qualitative Evaluation for Model Improvement**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: Dialog  
[Paper Link](http://arxiv.org/abs/2311.02807v1)  

---


**ABSTRACT**  
Quantitative evaluation metrics have traditionally been pivotal in gauging the advancements of artificial intelligence systems, including large language models (LLMs). However, these metrics have inherent limitations. Given the intricate nature of real-world tasks, a single scalar to quantify and compare is insufficient to capture the fine-grained nuances of model behavior. Metrics serve only as a way to compare and benchmark models, and do not yield actionable diagnostics, thus making the model improvement process challenging. Model developers find themselves amid extensive manual efforts involving sifting through vast datasets and attempting hit-or-miss adjustments to training data or setups. In this work, we address the shortcomings of quantitative metrics by proposing QualEval, which augments quantitative scalar metrics with automated qualitative evaluation as a vehicle for model improvement. QualEval uses a powerful LLM reasoner and our novel flexible linear programming solver to generate human-readable insights that when applied, accelerate model improvement. The insights are backed by a comprehensive dashboard with fine-grained visualizations and human-interpretable analyses. We corroborate the faithfulness of QualEval by demonstrating that leveraging its insights, for example, improves the absolute performance of the Llama 2 model by up to 15% points relative on a challenging dialogue task (DialogSum) when compared to baselines. QualEval successfully increases the pace of model development, thus in essence serving as a data-scientist-in-a-box. Given the focus on critiquing and improving current evaluation metrics, our method serves as a refreshingly new technique for both model evaluation and improvement.

{{</citation>}}


### (28/130) On the Intersection of Self-Correction and Trust in Language Models (Satyapriya Krishna, 2023)

{{<citation>}}

Satyapriya Krishna. (2023)  
**On the Intersection of Self-Correction and Trust in Language Models**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.02801v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have demonstrated remarkable capabilities in performing complex cognitive tasks. However, their complexity and lack of transparency have raised several trustworthiness concerns, including the propagation of misinformation and toxicity. Recent research has explored the self-correction capabilities of LLMs to enhance their performance. In this work, we investigate whether these self-correction capabilities can be harnessed to improve the trustworthiness of LLMs. We conduct experiments focusing on two key aspects of trustworthiness: truthfulness and toxicity. Our findings reveal that self-correction can lead to improvements in toxicity and truthfulness, but the extent of these improvements varies depending on the specific aspect of trustworthiness and the nature of the task. Interestingly, our study also uncovers instances of "self-doubt" in LLMs during the self-correction process, introducing a new set of challenges that need to be addressed.

{{</citation>}}


## cs.CL (37)



### (29/130) GPT4All: An Ecosystem of Open Source Compressed Language Models (Yuvanesh Anand et al., 2023)

{{<citation>}}

Yuvanesh Anand, Zach Nussbaum, Adam Treat, Aaron Miller, Richard Guo, Ben Schmidt, GPT4All Community, Brandon Duderstadt, Andriy Mulyar. (2023)  
**GPT4All: An Ecosystem of Open Source Compressed Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2311.04931v1)  

---


**ABSTRACT**  
Large language models (LLMs) have recently achieved human-level performance on a range of professional and academic benchmarks. The accessibility of these models has lagged behind their performance. State-of-the-art LLMs require costly infrastructure; are only accessible via rate-limited, geo-locked, and censored web interfaces; and lack publicly available code and technical reports. In this paper, we tell the story of GPT4All, a popular open source repository that aims to democratize access to LLMs. We outline the technical details of the original GPT4All model family, as well as the evolution of the GPT4All project from a single model into a fully fledged open source ecosystem. It is our hope that this paper acts as both a technical overview of the original GPT4All models as well as a case study on the subsequent growth of the GPT4All open source ecosystem.

{{</citation>}}


### (30/130) STONYBOOK: A System and Resource for Large-Scale Analysis of Novels (Charuta Pethe et al., 2023)

{{<citation>}}

Charuta Pethe, Allen Kim, Rajesh Prabhakar, Tanzir Pial, Steven Skiena. (2023)  
**STONYBOOK: A System and Resource for Large-Scale Analysis of Novels**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2311.03614v1)  

---


**ABSTRACT**  
Books have historically been the primary mechanism through which narratives are transmitted. We have developed a collection of resources for the large-scale analysis of novels, including: (1) an open source end-to-end NLP analysis pipeline for the annotation of novels into a standard XML format, (2) a collection of 49,207 distinct cleaned and annotated novels, and (3) a database with an associated web interface for the large-scale aggregate analysis of these literary works. We describe the major functionalities provided in the annotation system along with their utilities. We present samples of analysis artifacts from our website, such as visualizations of character occurrences and interactions, similar books, representative vocabulary, part of speech statistics, and readability metrics. We also describe the use of the annotated format in qualitative and quantitative analysis across large corpora of novels.

{{</citation>}}


### (31/130) Dimensions of Online Conflict: Towards Modeling Agonism (Matt Canute et al., 2023)

{{<citation>}}

Matt Canute, Mali Jin, hannah holtzclaw, Alberto Lusoli, Philippa R Adams, Mugdha Pandya, Maite Taboada, Diana Maynard, Wendy Hui Kyong Chun. (2023)  
**Dimensions of Online Conflict: Towards Modeling Agonism**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Twitter  
[Paper Link](http://arxiv.org/abs/2311.03584v1)  

---


**ABSTRACT**  
Agonism plays a vital role in democratic dialogue by fostering diverse perspectives and robust discussions. Within the realm of online conflict there is another type: hateful antagonism, which undermines constructive dialogue. Detecting conflict online is central to platform moderation and monetization. It is also vital for democratic dialogue, but only when it takes the form of agonism. To model these two types of conflict, we collected Twitter conversations related to trending controversial topics. We introduce a comprehensive annotation schema for labelling different dimensions of conflict in the conversations, such as the source of conflict, the target, and the rhetorical strategies deployed. Using this schema, we annotated approximately 4,000 conversations with multiple labels. We then trained both logistic regression and transformer-based models on the dataset, incorporating context from the conversation, including the number of participants and the structure of the interactions. Results show that contextual labels are helpful in identifying conflict and make the models robust to variations in topic. Our research contributes a conceptualization of different dimensions of conflict, a richly annotated dataset, and promising results that can contribute to content moderation.

{{</citation>}}


### (32/130) Context Unlocks Emotions: Text-based Emotion Classification Dataset Auditing with Large Language Models (Daniel Yang et al., 2023)

{{<citation>}}

Daniel Yang, Aditya Kommineni, Mohammad Alshehri, Nilamadhab Mohanty, Vedant Modi, Jonathan Gratch, Shrikanth Narayanan. (2023)  
**Context Unlocks Emotions: Text-based Emotion Classification Dataset Auditing with Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.03551v1)  

---


**ABSTRACT**  
The lack of contextual information in text data can make the annotation process of text-based emotion classification datasets challenging. As a result, such datasets often contain labels that fail to consider all the relevant emotions in the vocabulary. This misalignment between text inputs and labels can degrade the performance of machine learning models trained on top of them. As re-annotating entire datasets is a costly and time-consuming task that cannot be done at scale, we propose to use the expressive capabilities of large language models to synthesize additional context for input text to increase its alignment with the annotated emotional labels. In this work, we propose a formal definition of textual context to motivate a prompting strategy to enhance such contextual information. We provide both human and empirical evaluation to demonstrate the efficacy of the enhanced context. Our method improves alignment between inputs and their human-annotated labels from both an empirical and human-evaluated standpoint.

{{</citation>}}


### (33/130) Quantifying Uncertainty in Natural Language Explanations of Large Language Models (Sree Harsha Tanneru et al., 2023)

{{<citation>}}

Sree Harsha Tanneru, Chirag Agarwal, Himabindu Lakkaraju. (2023)  
**Quantifying Uncertainty in Natural Language Explanations of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2311.03533v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) are increasingly used as powerful tools for several high-stakes natural language processing (NLP) applications. Recent prompting works claim to elicit intermediate reasoning steps and key tokens that serve as proxy explanations for LLM predictions. However, there is no certainty whether these explanations are reliable and reflect the LLMs behavior. In this work, we make one of the first attempts at quantifying the uncertainty in explanations of LLMs. To this end, we propose two novel metrics -- $\textit{Verbalized Uncertainty}$ and $\textit{Probing Uncertainty}$ -- to quantify the uncertainty of generated explanations. While verbalized uncertainty involves prompting the LLM to express its confidence in its explanations, probing uncertainty leverages sample and model perturbations as a means to quantify the uncertainty. Our empirical analysis of benchmark datasets reveals that verbalized uncertainty is not a reliable estimate of explanation confidence. Further, we show that the probing uncertainty estimates are correlated with the faithfulness of an explanation, with lower uncertainty corresponding to explanations with higher faithfulness. Our study provides insights into the challenges and opportunities of quantifying uncertainty in LLM explanations, contributing to the broader discussion of the trustworthiness of foundation models.

{{</citation>}}


### (34/130) Spoken Dialogue System for Medical Prescription Acquisition on Smartphone: Development, Corpus and Evaluation (Ali Can Kocabiyikoglu et al., 2023)

{{<citation>}}

Ali Can Kocabiyikoglu, François Portet, Jean-Marc Babouchkine, Prudence Gibert, Hervé Blanchon, Gaëtan Gavazzi. (2023)  
**Spoken Dialogue System for Medical Prescription Acquisition on Smartphone: Development, Corpus and Evaluation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue  
[Paper Link](http://arxiv.org/abs/2311.03510v1)  

---


**ABSTRACT**  
Hospital information systems (HIS) have become an essential part of healthcare institutions and now incorporate prescribing support software. Prescription support software allows for structured information capture, which improves the safety, appropriateness and efficiency of prescriptions and reduces the number of adverse drug events (ADEs). However, such a system increases the amount of time physicians spend at a computer entering information instead of providing medical care. In addition, any new visiting clinician must learn to manage complex interfaces since each HIS has its own interfaces. In this paper, we present a natural language interface for e-prescribing software in the form of a spoken dialogue system accessible on a smartphone. This system allows prescribers to record their prescriptions verbally, a form of interaction closer to their usual practice. The system extracts the formal representation of the prescription ready to be checked by the prescribing software and uses the dialogue to request mandatory information, correct errors or warn of particular situations. Since, to the best of our knowledge, there is no existing voice-based prescription dialogue system, we present the system developed in a low-resource environment, focusing on dialogue modeling, semantic extraction and data augmentation. The system was evaluated in the wild with 55 participants. This evaluation showed that our system has an average prescription time of 66.15 seconds for physicians and 35.64 seconds for other experts, and a task success rate of 76\% for physicians and 72\% for other experts. All evaluation data were recorded and annotated to form PxCorpus, the first spoken drug prescription corpus that has been made fully available to the community (\url{https://doi.org/10.5281/zenodo.6524162}).

{{</citation>}}


### (35/130) Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation (Rusheb Shah et al., 2023)

{{<citation>}}

Rusheb Shah, Quentin Feuillade--Montixi, Soroush Pour, Arush Tagade, Stephen Casper, Javier Rando. (2023)  
**Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2311.03348v1)  

---


**ABSTRACT**  
Despite efforts to align large language models to produce harmless responses, they are still vulnerable to jailbreak prompts that elicit unrestricted behaviour. In this work, we investigate persona modulation as a black-box jailbreaking method to steer a target model to take on personalities that are willing to comply with harmful instructions. Rather than manually crafting prompts for each persona, we automate the generation of jailbreaks using a language model assistant. We demonstrate a range of harmful completions made possible by persona modulation, including detailed instructions for synthesising methamphetamine, building a bomb, and laundering money. These automated attacks achieve a harmful completion rate of 42.5% in GPT-4, which is 185 times larger than before modulation (0.23%). These prompts also transfer to Claude 2 and Vicuna with harmful completion rates of 61.0% and 35.9%, respectively. Our work reveals yet another vulnerability in commercial large language models and highlights the need for more comprehensive safeguards.

{{</citation>}}


### (36/130) Tackling Concept Shift in Text Classification using Entailment-style Modeling (Sumegh Roychowdhury et al., 2023)

{{<citation>}}

Sumegh Roychowdhury, Karan Gupta, Siva Rajesh Kasa, Prasanna Srinivasa Murthy, Alok Chandra. (2023)  
**Tackling Concept Shift in Text Classification using Entailment-style Modeling**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NLP, Natural Language Processing, Text Classification  
[Paper Link](http://arxiv.org/abs/2311.03320v1)  

---


**ABSTRACT**  
Pre-trained language models (PLMs) have seen tremendous success in text classification (TC) problems in the context of Natural Language Processing (NLP). In many real-world text classification tasks, the class definitions being learned do not remain constant but rather change with time - this is known as Concept Shift. Most techniques for handling concept shift rely on retraining the old classifiers with the newly labelled data. However, given the amount of training data required to fine-tune large DL models for the new concepts, the associated labelling costs can be prohibitively expensive and time consuming. In this work, we propose a reformulation, converting vanilla classification into an entailment-style problem that requires significantly less data to re-train the text classifier to adapt to new concepts. We demonstrate the effectiveness of our proposed method on both real world & synthetic datasets achieving absolute F1 gains upto 7% and 40% respectively in few-shot settings. Further, upon deployment, our solution also helped save 75% of labeling costs overall.

{{</citation>}}


### (37/130) DAIL: Data Augmentation for In-Context Learning via Self-Paraphrase (Dawei Li et al., 2023)

{{<citation>}}

Dawei Li, Yaxuan Li, Dheeraj Mekala, Shuyao Li, Yulin wang, Xueqi Wang, William Hogan, Jingbo Shang. (2023)  
**DAIL: Data Augmentation for In-Context Learning via Self-Paraphrase**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Augmentation, NLP  
[Paper Link](http://arxiv.org/abs/2311.03319v1)  

---


**ABSTRACT**  
In-Context Learning (ICL) combined with pre-trained large language models has achieved promising results on various NLP tasks. However, ICL requires high-quality annotated demonstrations which might not be available in real-world scenarios. To overcome this limitation, we propose \textbf{D}ata \textbf{A}ugmentation for \textbf{I}n-Context \textbf{L}earning (\textbf{DAIL}). DAIL leverages the intuition that large language models are more familiar with the content generated by themselves. It first utilizes the language model to generate paraphrases of the test sample and employs majority voting to determine the final result based on individual predictions. Our extensive empirical evaluation shows that DAIL outperforms the standard ICL method and other ensemble-based methods in the low-resource scenario. Additionally, we explore the use of voting consistency as a confidence score of the model when the logits of predictions are inaccessible. We believe our work will stimulate further research on ICL in low-resource settings.

{{</citation>}}


### (38/130) Unraveling Downstream Gender Bias from Large Language Models: A Study on AI Educational Writing Assistance (Thiemo Wambsganss et al., 2023)

{{<citation>}}

Thiemo Wambsganss, Xiaotian Su, Vinitra Swamy, Seyed Parsa Neshaei, Roman Rietsche, Tanja Käser. (2023)  
**Unraveling Downstream Gender Bias from Large Language Models: A Study on AI Educational Writing Assistance**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CY, cs.CL  
Keywords: AI, Bias, Embedding, GPT, GPT-3.5, Language Model, Sentence Embedding, Word Embedding  
[Paper Link](http://arxiv.org/abs/2311.03311v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) are increasingly utilized in educational tasks such as providing writing suggestions to students. Despite their potential, LLMs are known to harbor inherent biases which may negatively impact learners. Previous studies have investigated bias in models and data representations separately, neglecting the potential impact of LLM bias on human writing. In this paper, we investigate how bias transfers through an AI writing support pipeline. We conduct a large-scale user study with 231 students writing business case peer reviews in German. Students are divided into five groups with different levels of writing support: one classroom group with feature-based suggestions and four groups recruited from Prolific -- a control group with no assistance, two groups with suggestions from fine-tuned GPT-2 and GPT-3 models, and one group with suggestions from pre-trained GPT-3.5. Using GenBit gender bias analysis, Word Embedding Association Tests (WEAT), and Sentence Embedding Association Test (SEAT) we evaluate the gender bias at various stages of the pipeline: in model embeddings, in suggestions generated by the models, and in reviews written by students. Our results demonstrate that there is no significant difference in gender bias between the resulting peer reviews of groups with and without LLM suggestions. Our research is therefore optimistic about the use of AI writing support in the classroom, showcasing a context where bias in LLMs does not transfer to students' responses.

{{</citation>}}


### (39/130) Ziya2: Data-centric Learning is All LLMs Need (Ruyi Gan et al., 2023)

{{<citation>}}

Ruyi Gan, Ziwei Wu, Renliang Sun, Junyu Lu, Xiaojun Wu, Dixiang Zhang, Kunhao Pan, Ping Yang, Qi Yang, Jiaxing Zhang, Yan Song. (2023)  
**Ziya2: Data-centric Learning is All LLMs Need**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: LLaMA  
[Paper Link](http://arxiv.org/abs/2311.03301v1)  

---


**ABSTRACT**  
Various large language models (LLMs) have been proposed in recent years, including closed- and open-source ones, continually setting new records on multiple benchmarks. However, the development of LLMs still faces several issues, such as high cost of training models from scratch, and continual pre-training leading to catastrophic forgetting, etc. Although many such issues are addressed along the line of research on LLMs, an important yet practical limitation is that many studies overly pursue enlarging model sizes without comprehensively analyzing and optimizing the use of pre-training data in their learning process, as well as appropriate organization and leveraging of such data in training LLMs under cost-effective settings. In this work, we propose Ziya2, a model with 13 billion parameters adopting LLaMA2 as the foundation model, and further pre-trained on 700 billion tokens, where we focus on pre-training techniques and use data-centric optimization to enhance the learning process of Ziya2 on different stages. Experiments show that Ziya2 significantly outperforms other models in multiple benchmarks especially with promising results compared to representative open-source ones. Ziya2 (Base) is released at https://huggingface.co/IDEA-CCNL/Ziya2-13B-Base and https://modelscope.cn/models/Fengshenbang/Ziya2-13B-Base/summary.

{{</citation>}}


### (40/130) Instructed Language Models with Retrievers Are Powerful Entity Linkers (Zilin Xiao et al., 2023)

{{<citation>}}

Zilin Xiao, Ming Gong, Jie Wu, Xingyao Zhang, Linjun Shou, Jian Pei, Daxin Jiang. (2023)  
**Instructed Language Models with Retrievers Are Powerful Entity Linkers**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.03250v1)  

---


**ABSTRACT**  
Generative approaches powered by large language models (LLMs) have demonstrated emergent abilities in tasks that require complex reasoning abilities. Yet the generative nature still makes the generated content suffer from hallucinations, thus unsuitable for entity-centric tasks like entity linking (EL) requiring precise entity predictions over a large knowledge base. We present Instructed Generative Entity Linker (INSGENEL), the first approach that enables casual language models to perform entity linking over knowledge bases. Several methods to equip language models with EL capability were proposed in this work, including (i) a sequence-to-sequence training EL objective with instruction-tuning, (ii) a novel generative EL framework based on a light-weight potential mention retriever that frees the model from heavy and non-parallelizable decoding, achieving 4$\times$ speedup without compromise on linking metrics. INSGENEL outperforms previous generative alternatives with +6.8 F1 points gain on average, also with a huge advantage in training data efficiency and training compute consumption. In addition, our skillfully engineered in-context learning (ICL) framework for EL still lags behind INSGENEL significantly, reaffirming that the EL task remains a persistent hurdle for general LLMs.

{{</citation>}}


### (41/130) Safurai-Csharp: Harnessing Synthetic Data to improve language-specific Code LLM (Davide Cifarelli et al., 2023)

{{<citation>}}

Davide Cifarelli, Leonardo Boiardi, Alessandro Puppo, Leon Jovanovic. (2023)  
**Safurai-Csharp: Harnessing Synthetic Data to improve language-specific Code LLM**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2311.03243v1)  

---


**ABSTRACT**  
This paper introduces Safurai-Csharp, an open-source model designed to specialize in the generation, completion, and debugging of C# code. Safurai-Csharp is built upon the novel CodeLlama 34B model and leverages the EvolInstruct technique, creating a refined and expanded dataset for its fine-tuning process. The results of its performance, a notable score of 56.33% on the Manual MultiPL-E benchmark (Zero-Shot, Pass@1), signal its high capacity to streamline developers' workflows and aid code learning. It shows promise in setting new stakes in the landscape of open-source C# LLMs and hopes to inspire more inclusive and wide-ranging development in the field of language-specific LLMs.

{{</citation>}}


### (42/130) An Efficient Self-Supervised Cross-View Training For Sentence Embedding (Peerat Limkonchotiwat et al., 2023)

{{<citation>}}

Peerat Limkonchotiwat, Wuttikorn Ponwitayarat, Lalita Lowphansirikul, Can Udomcharoenchaikit, Ekapol Chuangsuwanich, Sarana Nutanong. (2023)  
**An Efficient Self-Supervised Cross-View Training For Sentence Embedding**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Embedding, Self-Supervised, Sentence Embedding, Textual Similarity  
[Paper Link](http://arxiv.org/abs/2311.03228v1)  

---


**ABSTRACT**  
Self-supervised sentence representation learning is the task of constructing an embedding space for sentences without relying on human annotation efforts. One straightforward approach is to finetune a pretrained language model (PLM) with a representation learning method such as contrastive learning. While this approach achieves impressive performance on larger PLMs, the performance rapidly degrades as the number of parameters decreases. In this paper, we propose a framework called Self-supervised Cross-View Training (SCT) to narrow the performance gap between large and small PLMs. To evaluate the effectiveness of SCT, we compare it to 5 baseline and state-of-the-art competitors on seven Semantic Textual Similarity (STS) benchmarks using 5 PLMs with the number of parameters ranging from 4M to 340M. The experimental results show that STC outperforms the competitors for PLMs with less than 100M parameters in 18 of 21 cases.

{{</citation>}}


### (43/130) ALYMPICS: Language Agents Meet Game Theory (Shaoguang Mao et al., 2023)

{{<citation>}}

Shaoguang Mao, Yuzhe Cai, Yan Xia, Wenshan Wu, Xun Wang, Fengyi Wang, Tao Ge, Furu Wei. (2023)  
**ALYMPICS: Language Agents Meet Game Theory**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-GT, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.03220v1)  

---


**ABSTRACT**  
This paper introduces Alympics, a platform that leverages Large Language Model (LLM) agents to facilitate investigations in game theory. By employing LLMs and autonomous agents to simulate human behavior and enable multi-agent collaborations, we can construct realistic and dynamic models of human interactions for game theory hypothesis formulating and testing. To demonstrate this, we present and implement a survival game involving unequal competition for limited resources. Through manipulation of resource availability and agent personalities, we observe how different agents engage in the competition and adapt their strategies. The use of LLM agents in game theory research offers significant advantages, including simulating realistic behavior, providing a controlled, scalable, and reproducible environment. Our work highlights the potential of LLM agents in enhancing the understanding of strategic decision-making within complex socioeconomic contexts. All codes will be made public soon.

{{</citation>}}


### (44/130) Pseudo-Labeling for Domain-Agnostic Bangla Automatic Speech Recognition (Rabindra Nath Nandi et al., 2023)

{{<citation>}}

Rabindra Nath Nandi, Mehadi Hasan Menon, Tareq Al Muntasir, Sagor Sarker, Quazi Sarwar Muhtaseem, Md. Tariqul Islam, Shammur Absar Chowdhury, Firoj Alam. (2023)  
**Pseudo-Labeling for Domain-Agnostic Bangla Automatic Speech Recognition**  

---
Primary Category: cs.CL  
Categories: 68T50, F-2-2; I-2-7, cs-AI, cs-CL, cs.CL  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2311.03196v1)  

---


**ABSTRACT**  
One of the major challenges for developing automatic speech recognition (ASR) for low-resource languages is the limited access to labeled data with domain-specific variations. In this study, we propose a pseudo-labeling approach to develop a large-scale domain-agnostic ASR dataset. With the proposed methodology, we developed a 20k+ hours labeled Bangla speech dataset covering diverse topics, speaking styles, dialects, noisy environments, and conversational scenarios. We then exploited the developed corpus to design a conformer-based ASR system. We benchmarked the trained ASR with publicly available datasets and compared it with other available models. To investigate the efficacy, we designed and developed a human-annotated domain-agnostic test set composed of news, telephony, and conversational data among others. Our results demonstrate the efficacy of the model trained on psuedo-label data for the designed test-set along with publicly-available Bangla datasets. The experimental resources will be publicly available.(https://github.com/hishab-nlp/Pseudo-Labeling-for-Domain-Agnostic-Bangla-ASR)

{{</citation>}}


### (45/130) Model-based Counterfactual Generator for Gender Bias Mitigation (Ewoenam Kwaku Tokpo et al., 2023)

{{<citation>}}

Ewoenam Kwaku Tokpo, Toon Calders. (2023)  
**Model-based Counterfactual Generator for Gender Bias Mitigation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Augmentation, Bias  
[Paper Link](http://arxiv.org/abs/2311.03186v1)  

---


**ABSTRACT**  
Counterfactual Data Augmentation (CDA) has been one of the preferred techniques for mitigating gender bias in natural language models. CDA techniques have mostly employed word substitution based on dictionaries. Although such dictionary-based CDA techniques have been shown to significantly improve the mitigation of gender bias, in this paper, we highlight some limitations of such dictionary-based counterfactual data augmentation techniques, such as susceptibility to ungrammatical compositions, and lack of generalization outside the set of predefined dictionary words. Model-based solutions can alleviate these problems, yet the lack of qualitative parallel training data hinders development in this direction. Therefore, we propose a combination of data processing techniques and a bi-objective training regime to develop a model-based solution for generating counterfactuals to mitigate gender bias. We implemented our proposed solution and performed an empirical evaluation which shows how our model alleviates the shortcomings of dictionary-based solutions.

{{</citation>}}


### (46/130) Nexus at ArAIEval Shared Task: Fine-Tuning Arabic Language Models for Propaganda and Disinformation Detection (Yunze Xiao et al., 2023)

{{<citation>}}

Yunze Xiao, Firoj Alam. (2023)  
**Nexus at ArAIEval Shared Task: Fine-Tuning Arabic Language Models for Propaganda and Disinformation Detection**  

---
Primary Category: cs.CL  
Categories: 68T50, F-2-2; I-2-7, cs-AI, cs-CL, cs-SI, cs.CL  
Keywords: AI, GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2311.03184v1)  

---


**ABSTRACT**  
The spread of disinformation and propagandistic content poses a threat to societal harmony, undermining informed decision-making and trust in reliable sources. Online platforms often serve as breeding grounds for such content, and malicious actors exploit the vulnerabilities of audiences to shape public opinion. Although there have been research efforts aimed at the automatic identification of disinformation and propaganda in social media content, there remain challenges in terms of performance. The ArAIEval shared task aims to further research on these particular issues within the context of the Arabic language. In this paper, we discuss our participation in these shared tasks. We competed in subtasks 1A and 2A, where our submitted system secured positions 9th and 10th, respectively. Our experiments consist of fine-tuning transformer models and using zero- and few-shot learning with GPT-4.

{{</citation>}}


### (47/130) ArAIEval Shared Task: Persuasion Techniques and Disinformation Detection in Arabic Text (Maram Hasanain et al., 2023)

{{<citation>}}

Maram Hasanain, Firoj Alam, Hamdy Mubarak, Samir Abdaljalil, Wajdi Zaghouani, Preslav Nakov, Giovanni Da San Martino, Abed Alhakim Freihat. (2023)  
**ArAIEval Shared Task: Persuasion Techniques and Disinformation Detection in Arabic Text**  

---
Primary Category: cs.CL  
Categories: 68T50, F-2-2; I-2-7, cs-AI, cs-CL, cs.CL  
Keywords: AI, BERT, NLP  
[Paper Link](http://arxiv.org/abs/2311.03179v1)  

---


**ABSTRACT**  
We present an overview of the ArAIEval shared task, organized as part of the first ArabicNLP 2023 conference co-located with EMNLP 2023. ArAIEval offers two tasks over Arabic text: (i) persuasion technique detection, focusing on identifying persuasion techniques in tweets and news articles, and (ii) disinformation detection in binary and multiclass setups over tweets. A total of 20 teams participated in the final evaluation phase, with 14 and 16 teams participating in Tasks 1 and 2, respectively. Across both tasks, we observed that fine-tuning transformer models such as AraBERT was at the core of the majority of the participating systems. We provide a description of the task setup, including a description of the dataset construction and the evaluation setup. We further give a brief overview of the participating systems. All datasets and evaluation scripts from the shared task are released to the research community. (https://araieval.gitlab.io/) We hope this will enable further research on these important tasks in Arabic.

{{</citation>}}


### (48/130) Findings of the WMT 2023 Shared Task on Discourse-Level Literary Translation: A Fresh Orb in the Cosmos of LLMs (Longyue Wang et al., 2023)

{{<citation>}}

Longyue Wang, Zhaopeng Tu, Yan Gu, Siyou Liu, Dian Yu, Qingsong Ma, Chenyang Lyu, Liting Zhou, Chao-Hong Liu, Yufeng Ma, Weiyu Chen, Yvette Graham, Bonnie Webber, Philipp Koehn, Andy Way, Yulin Yuan, Shuming Shi. (2023)  
**Findings of the WMT 2023 Shared Task on Discourse-Level Literary Translation: A Fresh Orb in the Cosmos of LLMs**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03127v1)  

---


**ABSTRACT**  
Translating literary works has perennially stood as an elusive dream in machine translation (MT), a journey steeped in intricate challenges. To foster progress in this domain, we hold a new shared task at WMT 2023, the first edition of the Discourse-Level Literary Translation. First, we (Tencent AI Lab and China Literature Ltd.) release a copyrighted and document-level Chinese-English web novel corpus. Furthermore, we put forth an industry-endorsed criteria to guide human evaluation process. This year, we totally received 14 submissions from 7 academia and industry teams. We employ both automatic and human evaluations to measure the performance of the submitted systems. The official ranking of the systems is based on the overall human judgments. In addition, our extensive analysis reveals a series of interesting findings on literary and discourse-aware MT. We release data, system outputs, and leaderboard at http://www2.statmt.org/wmt23/literary-translation-task.html.

{{</citation>}}


### (49/130) Text Augmentations with R-drop for Classification of Tweets Self Reporting Covid-19 (Sumam Francis et al., 2023)

{{<citation>}}

Sumam Francis, Marie-Francine Moens. (2023)  
**Text Augmentations with R-drop for Classification of Tweets Self Reporting Covid-19**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-IR, cs-LG, cs.CL  
Keywords: Augmentation, Social Media  
[Paper Link](http://arxiv.org/abs/2311.03420v1)  

---


**ABSTRACT**  
This paper presents models created for the Social Media Mining for Health 2023 shared task. Our team addressed the first task, classifying tweets that self-report Covid-19 diagnosis. Our approach involves a classification model that incorporates diverse textual augmentations and utilizes R-drop to augment data and mitigate overfitting, boosting model efficacy. Our leading model, enhanced with R-drop and augmentations like synonym substitution, reserved words, and back translations, outperforms the task mean and median scores. Our system achieves an impressive F1 score of 0.877 on the test set.

{{</citation>}}


### (50/130) Injecting Categorical Labels and Syntactic Information into Biomedical NER (Sumam Francis et al., 2023)

{{<citation>}}

Sumam Francis, Marie-Francine Moens. (2023)  
**Injecting Categorical Labels and Syntactic Information into Biomedical NER**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-IR, cs-LG, cs.CL  
Keywords: BERT, NER  
[Paper Link](http://arxiv.org/abs/2311.03113v1)  

---


**ABSTRACT**  
We present a simple approach to improve biomedical named entity recognition (NER) by injecting categorical labels and Part-of-speech (POS) information into the model. We use two approaches, in the first approach, we first train a sequence-level classifier to classify the sentences into categories to obtain the sentence-level tags (categorical labels). The sequence classifier is modeled as an entailment problem by modifying the labels as a natural language template. This helps to improve the accuracy of the classifier. Further, this label information is injected into the NER model. In this paper, we demonstrate effective ways to represent and inject these labels and POS attributes into the NER model. In the second approach, we jointly learn the categorical labels and NER labels. Here we also inject the POS tags into the model to increase the syntactic context of the model. Experiments on three benchmark datasets show that incorporating categorical label information with syntactic context is quite useful and outperforms baseline BERT-based models.

{{</citation>}}


### (51/130) Language Models are Super Mario: Absorbing Abilities from Homologous Models as a Free Lunch (Le Yu et al., 2023)

{{<citation>}}

Le Yu, Bowen Yu, Haiyang Yu, Fei Huang, Yongbin Li. (2023)  
**Language Models are Super Mario: Absorbing Abilities from Homologous Models as a Free Lunch**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: BERT, GLUE, Language Model  
[Paper Link](http://arxiv.org/abs/2311.03099v1)  

---


**ABSTRACT**  
In this paper, we uncover that Language Models (LMs), either encoder- or decoder-based, can obtain new capabilities by assimilating the parameters of homologous models without retraining or GPUs. Typically, new abilities of LMs can be imparted by Supervised Fine-Tuning (SFT), reflected in the disparity between fine-tuned and pre-trained parameters (i.e., delta parameters). We initially observe that by introducing a novel operation called DARE (Drop And REscale), most delta parameters can be directly set to zeros without affecting the capabilities of SFT LMs and larger models can tolerate a higher proportion of discarded parameters. Based on this observation, we further sparsify delta parameters of multiple SFT homologous models with DARE and subsequently merge them into a single model by parameter averaging. We conduct experiments on eight datasets from the GLUE benchmark with BERT and RoBERTa. We also merge WizardLM, WizardMath, and Code Alpaca based on Llama 2. Experimental results show that: (1) The delta parameter value ranges for SFT models are typically small, often within 0.005, and DARE can eliminate 99% of them effortlessly. However, once the models are continuously pre-trained, the value ranges can grow to around 0.03, making DARE impractical. We have also tried to remove fine-tuned instead of delta parameters and find that a 10% reduction can lead to drastically decreased performance (even to 0). This highlights that SFT merely stimulates the abilities via delta parameters rather than injecting new abilities into LMs; (2) DARE can merge multiple task-specific LMs into one LM with diverse abilities. For instance, the merger of WizardLM and WizardMath improves the GSM8K zero-shot accuracy of WizardLM from 2.2 to 66.3, retaining its instruction-following ability while surpassing WizardMath's original 64.2 performance. Codes are available at https://github.com/yule-BUAA/MergeLM.

{{</citation>}}


### (52/130) A Simple yet Efficient Ensemble Approach for AI-generated Text Detection (Harika Abburi et al., 2023)

{{<citation>}}

Harika Abburi, Kalyani Roy, Michael Suesserman, Nirmala Pudota, Balaji Veeramani, Edward Bowen, Sanmitra Bhattacharya. (2023)  
**A Simple yet Efficient Ensemble Approach for AI-generated Text Detection**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Falcon, GPT, LLaMA, Language Model, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.03084v2)  

---


**ABSTRACT**  
Recent Large Language Models (LLMs) have demonstrated remarkable capabilities in generating text that closely resembles human writing across wide range of styles and genres. However, such capabilities are prone to potential abuse, such as fake news generation, spam email creation, and misuse in academic assignments. Hence, it is essential to build automated approaches capable of distinguishing between artificially generated text and human-authored text. In this paper, we propose a simple yet efficient solution to this problem by ensembling predictions from multiple constituent LLMs. Compared to previous state-of-the-art approaches, which are perplexity-based or uses ensembles with a number of LLMs, our condensed ensembling approach uses only two constituent LLMs to achieve comparable performance. Experiments conducted on four benchmark datasets for generative text classification show performance improvements in the range of 0.5 to 100\% compared to previous state-of-the-art approaches. We also study the influence that the training data from individual LLMs have on model performance. We found that substituting commercially-restrictive Generative Pre-trained Transformer (GPT) data with data generated from other open language models such as Falcon, Large Language Model Meta AI (LLaMA2), and Mosaic Pretrained Transformers (MPT) is a feasible alternative when developing generative text detectors. Furthermore, to demonstrate zero-shot generalization, we experimented with an English essays dataset, and results suggest that our ensembling approach can handle new data effectively.

{{</citation>}}


### (53/130) BanLemma: A Word Formation Dependent Rule and Dictionary Based Bangla Lemmatizer (Sadia Afrin et al., 2023)

{{<citation>}}

Sadia Afrin, Md. Shahad Mahmud Chowdhury, Md. Ekramul Islam, Faisal Ahamed Khan, Labib Imam Chowdhury, MD. Motahar Mahtab, Nazifa Nuha Chowdhury, Massud Forkan, Neelima Kundu, Hakim Arif, Mohammad Mamun Or Rashid, Mohammad Ruhul Amin, Nabeel Mohammed. (2023)  
**BanLemma: A Word Formation Dependent Rule and Dictionary Based Bangla Lemmatizer**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2311.03078v1)  

---


**ABSTRACT**  
Lemmatization holds significance in both natural language processing (NLP) and linguistics, as it effectively decreases data density and aids in comprehending contextual meaning. However, due to the highly inflected nature and morphological richness, lemmatization in Bangla text poses a complex challenge. In this study, we propose linguistic rules for lemmatization and utilize a dictionary along with the rules to design a lemmatizer specifically for Bangla. Our system aims to lemmatize words based on their parts of speech class within a given sentence. Unlike previous rule-based approaches, we analyzed the suffix marker occurrence according to the morpho-syntactic values and then utilized sequences of suffix markers instead of entire suffixes. To develop our rules, we analyze a large corpus of Bangla text from various domains, sources, and time periods to observe the word formation of inflected words. The lemmatizer achieves an accuracy of 96.36% when tested against a manually annotated test dataset by trained linguists and demonstrates competitive performance on three previously published Bangla lemmatization datasets. We are making the code and datasets publicly available at https://github.com/eblict-gigatech/BanLemma in order to contribute to the further advancement of Bangla NLP.

{{</citation>}}


### (54/130) Zero-shot Bilingual App Reviews Mining with Large Language Models (Jialiang Wei et al., 2023)

{{<citation>}}

Jialiang Wei, Anne-Lise Courbis, Thomas Lambolais, Binbin Xu, Pierre Louis Bernard, Gérard Dray. (2023)  
**Zero-shot Bilingual App Reviews Mining with Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2311.03058v1)  

---


**ABSTRACT**  
App reviews from app stores are crucial for improving software requirements. A large number of valuable reviews are continually being posted, describing software problems and expected features. Effectively utilizing user reviews necessitates the extraction of relevant information, as well as their subsequent summarization. Due to the substantial volume of user reviews, manual analysis is arduous. Various approaches based on natural language processing (NLP) have been proposed for automatic user review mining. However, the majority of them requires a manually crafted dataset to train their models, which limits their usage in real-world scenarios. In this work, we propose Mini-BAR, a tool that integrates large language models (LLMs) to perform zero-shot mining of user reviews in both English and French. Specifically, Mini-BAR is designed to (i) classify the user reviews, (ii) cluster similar reviews together, (iii) generate an abstractive summary for each cluster and (iv) rank the user review clusters. To evaluate the performance of Mini-BAR, we created a dataset containing 6,000 English and 6,000 French annotated user reviews and conducted extensive experiments. Preliminary results demonstrate the effectiveness and efficiency of Mini-BAR in requirement engineering by analyzing bilingual app reviews. (Replication package containing the code, dataset, and experiment setups on https://github.com/Jl-wei/mini-bar )

{{</citation>}}


### (55/130) Detecting Agreement in Multi-party Conversational AI (Laura Schauer et al., 2023)

{{<citation>}}

Laura Schauer, Jason Sweeney, Charlie Lyttle, Zein Said, Aron Szeles, Cale Clark, Katie McAskill, Xander Wickham, Tom Byars, Daniel Hernández Garcia, Nancie Gunson, Angus Addlesee, Oliver Lemon. (2023)  
**Detecting Agreement in Multi-party Conversational AI**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03026v1)  

---


**ABSTRACT**  
Today, conversational systems are expected to handle conversations in multi-party settings, especially within Socially Assistive Robots (SARs). However, practical usability remains difficult as there are additional challenges to overcome, such as speaker recognition, addressee recognition, and complex turn-taking. In this paper, we present our work on a multi-party conversational system, which invites two users to play a trivia quiz game. The system detects users' agreement or disagreement on a final answer and responds accordingly. Our evaluation includes both performance and user assessment results, with a focus on detecting user agreement. Our annotated transcripts and the code for the proposed system have been released open-source on GitHub.

{{</citation>}}


### (56/130) Towards a Transformer-Based Reverse Dictionary Model for Quality Estimation of Definitions (Julien Guité-Vinet et al., 2023)

{{<citation>}}

Julien Guité-Vinet, Alexandre Blondin Massé, Fatiha Sadat. (2023)  
**Towards a Transformer-Based Reverse Dictionary Model for Quality Estimation of Definitions**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2311.02985v2)  

---


**ABSTRACT**  
In the last years, several variants of transformers have emerged. In this paper, we compare different transformer-based models for solving the reverse dictionary task and explore their use in the context of a serious game called The Dictionary Game.

{{</citation>}}


### (57/130) Adapting Pre-trained Generative Models for Extractive Question Answering (Prabir Mallick et al., 2023)

{{<citation>}}

Prabir Mallick, Tapas Nayak, Indrajit Bhattacharya. (2023)  
**Adapting Pre-trained Generative Models for Extractive Question Answering**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: QA, Question Answering, T5  
[Paper Link](http://arxiv.org/abs/2311.02961v1)  

---


**ABSTRACT**  
Pre-trained Generative models such as BART, T5, etc. have gained prominence as a preferred method for text generation in various natural language processing tasks, including abstractive long-form question answering (QA) and summarization. However, the potential of generative models in extractive QA tasks, where discriminative models are commonly employed, remains largely unexplored. Discriminative models often encounter challenges associated with label sparsity, particularly when only a small portion of the context contains the answer. The challenge is more pronounced for multi-span answers. In this work, we introduce a novel approach that uses the power of pre-trained generative models to address extractive QA tasks by generating indexes corresponding to context tokens or sentences that form part of the answer. Through comprehensive evaluations on multiple extractive QA datasets, including MultiSpanQA, BioASQ, MASHQA, and WikiQA, we demonstrate the superior performance of our proposed approach compared to existing state-of-the-art models.

{{</citation>}}


### (58/130) In-Context Learning for Knowledge Base Question Answering for Unmanned Systems based on Large Language Models (Yunlong Chen et al., 2023)

{{<citation>}}

Yunlong Chen, Yaming Zhang, Jianfei Yu, Li Yang, Rui Xia. (2023)  
**In-Context Learning for Knowledge Base Question Answering for Unmanned Systems based on Large Language Models**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT, Knowledge Graph, Language Model, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2311.02956v1)  

---


**ABSTRACT**  
Knowledge Base Question Answering (KBQA) aims to answer factoid questions based on knowledge bases. However, generating the most appropriate knowledge base query code based on Natural Language Questions (NLQ) poses a significant challenge in KBQA. In this work, we focus on the CCKS2023 Competition of Question Answering with Knowledge Graph Inference for Unmanned Systems. Inspired by the recent success of large language models (LLMs) like ChatGPT and GPT-3 in many QA tasks, we propose a ChatGPT-based Cypher Query Language (CQL) generation framework to generate the most appropriate CQL based on the given NLQ. Our generative framework contains six parts: an auxiliary model predicting the syntax-related information of CQL based on the given NLQ, a proper noun matcher extracting proper nouns from the given NLQ, a demonstration example selector retrieving similar examples of the input sample, a prompt constructor designing the input template of ChatGPT, a ChatGPT-based generation model generating the CQL, and an ensemble model to obtain the final answers from diversified outputs. With our ChatGPT-based CQL generation framework, we achieved the second place in the CCKS 2023 Question Answering with Knowledge Graph Inference for Unmanned Systems competition, achieving an F1-score of 0.92676.

{{</citation>}}


### (59/130) PhoGPT: Generative Pre-training for Vietnamese (Dat Quoc Nguyen et al., 2023)

{{<citation>}}

Dat Quoc Nguyen, Linh The Nguyen, Chi Tran, Dung Ngoc Nguyen, Nhung Nguyen, Thien Huu Nguyen, Dinh Phung, Hung Bui. (2023)  
**PhoGPT: Generative Pre-training for Vietnamese**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, GPT  
[Paper Link](http://arxiv.org/abs/2311.02945v1)  

---


**ABSTRACT**  
We open-source a state-of-the-art 7.5B-parameter generative model series named PhoGPT for Vietnamese, which includes the base pre-trained monolingual model PhoGPT-7B5 and its instruction-following variant, PhoGPT-7B5-Instruct. In addition, we also demonstrate its superior performance compared to previous open-source models through a human evaluation experiment. GitHub: https://github.com/VinAIResearch/PhoGPT

{{</citation>}}


### (60/130) SQLPrompt: In-Context Text-to-SQL with Minimal Labeled Data (Ruoxi Sun et al., 2023)

{{<citation>}}

Ruoxi Sun, Sercan Ö. Arik, Rajarishi Sinha, Hootan Nakhost, Hanjun Dai, Pengcheng Yin, Tomas Pfister. (2023)  
**SQLPrompt: In-Context Text-to-SQL with Minimal Labeled Data**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.02883v1)  

---


**ABSTRACT**  
Text-to-SQL aims to automate the process of generating SQL queries on a database from natural language text. In this work, we propose "SQLPrompt", tailored to improve the few-shot prompting capabilities of Text-to-SQL for Large Language Models (LLMs). Our methods include innovative prompt design, execution-based consistency decoding strategy which selects the SQL with the most consistent execution outcome among other SQL proposals, and a method that aims to improve performance by diversifying the SQL proposals during consistency selection with different prompt designs ("MixPrompt") and foundation models ("MixLLMs"). We show that \emph{SQLPrompt} outperforms previous approaches for in-context learning with few labeled data by a large margin, closing the gap with finetuning state-of-the-art with thousands of labeled data.

{{</citation>}}


### (61/130) Less than One-shot: Named Entity Recognition via Extremely Weak Supervision (Letian Peng et al., 2023)

{{<citation>}}

Letian Peng, Zihan Wang, Jingbo Shang. (2023)  
**Less than One-shot: Named Entity Recognition via Extremely Weak Supervision**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT, NER, Named Entity Recognition  
[Paper Link](http://arxiv.org/abs/2311.02861v1)  

---


**ABSTRACT**  
We study the named entity recognition (NER) problem under the extremely weak supervision (XWS) setting, where only one example entity per type is given in a context-free way. While one can see that XWS is lighter than one-shot in terms of the amount of supervision, we propose a novel method X-NER that can outperform the state-of-the-art one-shot NER methods. We first mine entity spans that are similar to the example entities from an unlabelled training corpus. Instead of utilizing entity span representations from language models, we find it more effective to compare the context distributions before and after the span is replaced by the entity example. We then leverage the top-ranked spans as pseudo-labels to train an NER tagger. Extensive experiments and analyses on 4 NER datasets show the superior end-to-end NER performance of X-NER, outperforming the state-of-the-art few-shot methods with 1-shot supervision and ChatGPT annotations significantly. Finally, our X-NER possesses several notable properties, such as inheriting the cross-lingual abilities of the underlying language models.

{{</citation>}}


### (62/130) Improving Machine Translation with Large Language Models: A Preliminary Study with Cooperative Decoding (Jiali Zeng et al., 2023)

{{<citation>}}

Jiali Zeng, Fandong Meng, Yongjing Yin, Jie Zhou. (2023)  
**Improving Machine Translation with Large Language Models: A Preliminary Study with Cooperative Decoding**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, Machine Translation  
[Paper Link](http://arxiv.org/abs/2311.02851v1)  

---


**ABSTRACT**  
Contemporary translation engines built upon the encoder-decoder framework have reached a high level of development, while the emergence of Large Language Models (LLMs) has disrupted their position by offering the potential for achieving superior translation quality. Therefore, it is crucial to understand in which scenarios LLMs outperform traditional NMT systems and how to leverage their strengths. In this paper, we first conduct a comprehensive analysis to assess the strengths and limitations of various commercial NMT systems and MT-oriented LLMs. Our findings indicate that neither NMT nor MT-oriented LLMs alone can effectively address all the translation issues, but MT-oriented LLMs can serve as a promising complement to the NMT systems. Building upon these insights, we explore hybrid methods and propose Cooperative Decoding (CoDec), which treats NMT systems as a pretranslation model and MT-oriented LLMs as a supplemental solution to handle complex scenarios beyond the capability of NMT alone. The results on the WMT22 test sets and a newly collected test set WebCrawl demonstrate the effectiveness and efficiency of CoDec, highlighting its potential as a robust solution for combining NMT systems with MT-oriented LLMs in machine translation.

{{</citation>}}


### (63/130) Co-training and Co-distillation for Quality Improvement and Compression of Language Models (Hayeon Lee et al., 2023)

{{<citation>}}

Hayeon Lee, Rui Hou, Jongpil Kim, Davis Liang, Hongbo Zhang, Sung Ju Hwang, Alexander Min. (2023)  
**Co-training and Co-distillation for Quality Improvement and Compression of Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GLUE, Knowledge Distillation, Language Model  
[Paper Link](http://arxiv.org/abs/2311.02849v2)  

---


**ABSTRACT**  
Knowledge Distillation (KD) compresses computationally expensive pre-trained language models (PLMs) by transferring their knowledge to smaller models, allowing their use in resource-constrained or real-time settings. However, most smaller models fail to surpass the performance of the original larger model, resulting in sacrificing performance to improve inference speed. To address this issue, we propose Co-Training and Co-Distillation (CTCD), a novel framework that improves performance and inference speed together by co-training two models while mutually distilling knowledge. The CTCD framework successfully achieves this based on two significant findings: 1) Distilling knowledge from the smaller model to the larger model during co-training improves the performance of the larger model. 2) The enhanced performance of the larger model further boosts the performance of the smaller model. The CTCD framework shows promise as it can be combined with existing techniques like architecture design or data augmentation, replacing one-way KD methods, to achieve further performance improvement. Extensive ablation studies demonstrate the effectiveness of CTCD, and the small model distilled by CTCD outperforms the original larger model by a significant margin of 1.66 on the GLUE benchmark.

{{</citation>}}


### (64/130) Tailoring Self-Rationalizers with Multi-Reward Distillation (Sahana Ramnath et al., 2023)

{{<citation>}}

Sahana Ramnath, Brihi Joshi, Skyler Hallinan, Ximing Lu, Liunian Harold Li, Aaron Chan, Jack Hessel, Yejin Choi, Xiang Ren. (2023)  
**Tailoring Self-Rationalizers with Multi-Reward Distillation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, QA  
[Paper Link](http://arxiv.org/abs/2311.02805v1)  

---


**ABSTRACT**  
Large language models (LMs) are capable of generating free-text rationales to aid question answering. However, prior work 1) suggests that useful self-rationalization is emergent only at significant scales (e.g., 175B parameter GPT-3); and 2) focuses largely on downstream performance, ignoring the semantics of the rationales themselves, e.g., are they faithful, true, and helpful for humans? In this work, we enable small-scale LMs (approx. 200x smaller than GPT-3) to generate rationales that not only improve downstream task performance, but are also more plausible, consistent, and diverse, assessed both by automatic and human evaluation. Our method, MaRio (Multi-rewArd RatIOnalization), is a multi-reward conditioned self-rationalization algorithm that optimizes multiple distinct properties like plausibility, diversity and consistency. Results on five difficult question-answering datasets StrategyQA, QuaRel, OpenBookQA, NumerSense and QASC show that not only does MaRio improve task accuracy, but it also improves the self-rationalization quality of small LMs across the aforementioned axes better than a supervised fine-tuning (SFT) baseline. Extensive human evaluations confirm that MaRio rationales are preferred vs. SFT rationales, as well as qualitative improvements in plausibility and consistency.

{{</citation>}}


### (65/130) Incorporating Worker Perspectives into MTurk Annotation Practices for NLP (Olivia Huang et al., 2023)

{{<citation>}}

Olivia Huang, Eve Fleisig, Dan Klein. (2023)  
**Incorporating Worker Perspectives into MTurk Annotation Practices for NLP**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Amazon, NLP  
[Paper Link](http://arxiv.org/abs/2311.02802v1)  

---


**ABSTRACT**  
Current practices regarding data collection for natural language processing on Amazon Mechanical Turk (MTurk) often rely on a combination of studies on data quality and heuristics shared among NLP researchers. However, without considering the perspectives of MTurk workers, these approaches are susceptible to issues regarding workers' rights and poor response quality. We conducted a critical literature review and a survey of MTurk workers aimed at addressing open questions regarding best practices for fair payment, worker privacy, data quality, and considering worker incentives. We found that worker preferences are often at odds with received wisdom among NLP researchers. Surveyed workers preferred reliable, reasonable payments over uncertain, very high payments; reported frequently lying on demographic questions; and expressed frustration at having work rejected with no explanation. We also found that workers view some quality control methods, such as requiring minimum response times or Master's qualifications, as biased and largely ineffective. Based on the survey results, we provide recommendations on how future NLP studies may better account for MTurk workers' experiences in order to respect workers' rights and improve data quality.

{{</citation>}}


## econ.GN (1)



### (66/130) Brief for the Canada House of Commons Study on the Implications of Artificial Intelligence Technologies for the Canadian Labor Force: Generative Artificial Intelligence Shatters Models of AI and Labor (Morgan R. Frank, 2023)

{{<citation>}}

Morgan R. Frank. (2023)  
**Brief for the Canada House of Commons Study on the Implications of Artificial Intelligence Technologies for the Canadian Labor Force: Generative Artificial Intelligence Shatters Models of AI and Labor**  

---
Primary Category: econ.GN  
Categories: cs-AI, econ-GN, econ.GN, q-fin-EC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03595v1)  

---


**ABSTRACT**  
Exciting advances in generative artificial intelligence (AI) have sparked concern for jobs, education, productivity, and the future of work. As with past technologies, generative AI may not lead to mass unemployment. But, unlike past technologies, generative AI is creative, cognitive, and potentially ubiquitous which makes the usual assumptions of automation predictions ill-suited for today. Existing projections suggest that generative AI will impact workers in occupations that were previously considered immune to automation. As AI's full set of capabilities and applications emerge, policy makers should promote workers' career adaptability. This goal requires improved data on job separations and unemployment by locality and job titles in order to identify early-indicators for the workers facing labor disruption. Further, prudent policy should incentivize education programs to accommodate learning with AI as a tool while preparing students for the demands of the future of work.

{{</citation>}}


## cs.DS (1)



### (67/130) Sketching methods with small window guarantee using minimum decycling sets (Guillaume Marçais et al., 2023)

{{<citation>}}

Guillaume Marçais, Dan DeBlasio, Carl Kingsford. (2023)  
**Sketching methods with small window guarantee using minimum decycling sets**  

---
Primary Category: cs.DS  
Categories: cs-DS, cs.DS, q-bio-GN  
Keywords: Sketch  
[Paper Link](http://arxiv.org/abs/2311.03592v1)  

---


**ABSTRACT**  
Most sequence sketching methods work by selecting specific $k$-mers from sequences so that the similarity between two sequences can be estimated using only the sketches. Estimating sequence similarity is much faster using sketches than using sequence alignment, hence sketching methods are used to reduce the computational requirements of computational biology software packages. Applications using sketches often rely on properties of the $k$-mer selection procedure to ensure that using a sketch does not degrade the quality of the results compared with using sequence alignment. In particular the window guarantee ensures that no long region of the sequence goes unrepresented in the sketch.   A sketching method with a window guarantee corresponds to a Decycling Set, aka an unavoidable sets of $k$-mers. Any long enough sequence must contain a $k$-mer from any decycling set (hence, it is unavoidable). Conversely, a decycling set defines a sketching method by selecting the $k$-mers from the set. Although current methods use one of a small number of sketching method families, the space of decycling sets is much larger, and largely unexplored. Finding decycling sets with desirable characteristics is a promising approach to discovering new sketching methods with improved performance (e.g., with small window guarantee).   The Minimum Decycling Sets (MDSs) are of particular interest because of their small size. Only two algorithms, by Mykkeltveit and Champarnaud, are known to generate two particular MDSs, although there is a vast number of alternative MDSs. We provide a simple method that allows one to explore the space of MDSs and to find sets optimized for desirable properties. We give evidence that the Mykkeltveit sets are close to optimal regarding one particular property, the remaining path length.

{{</citation>}}


## cs.CR (2)



### (68/130) Pinky: A Modern Malware-oriented Dynamic Information Retrieval Tool (Paul Irofti, 2023)

{{<citation>}}

Paul Irofti. (2023)  
**Pinky: A Modern Malware-oriented Dynamic Information Retrieval Tool**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-OS, cs-SE, cs.CR  
Keywords: Information Retrieval  
[Paper Link](http://arxiv.org/abs/2311.03588v1)  

---


**ABSTRACT**  
We present here a reverse engineering tool that can be used for information retrieval and anti-malware techniques. Our main contribution is the design and implementation of an instrumentation framework aimed at providing insight on the emulation process. Sample emulation is achieved via translation of the binary code to an intermediate representation followed by compilation and execution. The design makes this a versatile tool that can be used for multiple task such as information retrieval, reverse engineering, debugging, and integration with anti-malware products.

{{</citation>}}


### (69/130) SoK: Evaluations in Industrial Intrusion Detection Research (Olav Lamberts et al., 2023)

{{<citation>}}

Olav Lamberts, Konrad Wolsing, Eric Wagner, Jan Pennekamp, Jan Bauer, Klaus Wehrle, Martin Henze. (2023)  
**SoK: Evaluations in Industrial Intrusion Detection Research**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Intrusion Detection  
[Paper Link](http://arxiv.org/abs/2311.02929v1)  

---


**ABSTRACT**  
Industrial systems are increasingly threatened by cyberattacks with potentially disastrous consequences. To counter such attacks, industrial intrusion detection systems strive to timely uncover even the most sophisticated breaches. Due to its criticality for society, this fast-growing field attracts researchers from diverse backgrounds, resulting in 130 new detection approaches in 2021 alone. This huge momentum facilitates the exploration of diverse promising paths but likewise risks fragmenting the research landscape and burying promising progress. Consequently, it needs sound and comprehensible evaluations to mitigate this risk and catalyze efforts into sustainable scientific progress with real-world applicability. In this paper, we therefore systematically analyze the evaluation methodologies of this field to understand the current state of industrial intrusion detection research. Our analysis of 609 publications shows that the rapid growth of this research field has positive and negative consequences. While we observe an increased use of public datasets, publications still only evaluate 1.3 datasets on average, and frequently used benchmarking metrics are ambiguous. At the same time, the adoption of newly developed benchmarking metrics sees little advancement. Finally, our systematic analysis enables us to provide actionable recommendations for all actors involved and thus bring the entire research field forward.

{{</citation>}}


## eess.SP (1)



### (70/130) AI-Enabled Unmanned Vehicle-Assisted Reconfigurable Intelligent Surfaces: Deployment, Prototyping, Experiments, and Opportunities (Li-Hsiang Shen et al., 2023)

{{<citation>}}

Li-Hsiang Shen, Kai-Ten Feng, Ta-Sung Lee, Yuan-Chun Lin, Shih-Cheng Lin, Chia-Chan Chang, Sheng-Fuh Chang. (2023)  
**AI-Enabled Unmanned Vehicle-Assisted Reconfigurable Intelligent Surfaces: Deployment, Prototyping, Experiments, and Opportunities**  

---
Primary Category: eess.SP  
Categories: cs-AI, cs-LG, eess-SP, eess.SP  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.04241v1)  

---


**ABSTRACT**  
The requirement of wireless data demands is increasingly high as the sixth-generation (6G) technology evolves. Reconfigurable intelligent surface (RIS) is promisingly deemed to be one of 6G techniques for extending service coverage, reducing power consumption, and enhancing spectral efficiency. In this article, we have provided some fundamentals of RIS deployment in theory and hardware perspectives as well as utilization of artificial intelligence (AI) and machine learning. We conducted an intelligent deployment of RIS (i-Dris) prototype, including dual-band auto-guided vehicle (AGV) assisted RISs associated with an mmWave base station (BS) and a receiver. The RISs are deployed on the AGV with configured incident/reflection angles. While, both the mmWave BS and receiver are associated with an edge server monitoring downlink packets for obtaining system throughput. We have designed a federated multi-agent reinforcement learning scheme associated with several AGV-RIS agents and sub-agents per AGV-RIS consisting of the deployment of position, height, orientation and elevation angles. The experimental results presented the stationary measurement in different aspects and scenarios. The i-Dris can reach up to 980 Mbps transmission throughput under a bandwidth of 100 MHz with comparably low complexity as well as rapid deployment, which outperforms the other existing works. At last, we highlight some opportunities and future issues in leveraging RIS-empowered wireless communication networks.

{{</citation>}}


## cs.DB (3)



### (71/130) Fuzzy Relational Databases via Associative Arrays (Kevin Min et al., 2023)

{{<citation>}}

Kevin Min, Hayden Jananthan, Jeremy Kepner. (2023)  
**Fuzzy Relational Databases via Associative Arrays**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs.DB  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2311.03574v1)  

---


**ABSTRACT**  
The increasing rise in artificial intelligence has made the use of imprecise language in computer programs like ChatGPT more prominent. Fuzzy logic addresses this form of imprecise language by introducing the concept of fuzzy sets, where elements belong to the set with a certain membership value (called the fuzzy value). This paper combines fuzzy data with relational algebra to provide the mathematical foundation for a fuzzy database querying language, describing various useful operations in the language of linear algebra and multiset operations, in addition to rigorously proving key identities.

{{</citation>}}


### (72/130) Lessons Learned from Efforts to Standardize Streaming In SQL (Sabina Petride et al., 2023)

{{<citation>}}

Sabina Petride, Dan Sotolongo, Jan Michels, Andrew Witkowski, Cara Haas, Jim Hughes. (2023)  
**Lessons Learned from Efforts to Standardize Streaming In SQL**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs.DB  
Keywords: Amazon, Google, Microsoft  
[Paper Link](http://arxiv.org/abs/2311.03476v1)  

---


**ABSTRACT**  
Acknowledging the reality of streaming languages and platforms overlapping with SQL and database systems, in 2019 INCTIS Data Management established an Expert Group with the focused mission to initiate the process of standardizing streaming support in SQL. Over time, the roster included companies like Actian, Alibaba, Amazon Web Services, Confluent, dbt Labs, Google, Hazelcast, IBM, Materialize, Microsoft, Oracle, Snowflake, SQLstream and Timeplus. For the span of more than one year, representatives of each company have presented key features of their streaming product or, in some cases, multiple streaming products. These were live technical Q&A sessions accompanied by summary or position papers, which are unquestionably valuable. As expected, substantial time was spent in clarifying what common terms meant in each system and setting up a glossary. These sessions were followed by clarification notes and debates, and decisions that appeared mandatory to allow further progress. This first phase was followed by the next phase, which consisted of the group meetings, in which the expert group (EG) agreed on main exit criteria topics that a streaming solution in SQL must address, and position papers and follow-ups were written and discussed. This paper summarizes these group efforts, up to the summer of 2023.

{{</citation>}}


### (73/130) GPTuner: A Manual-Reading Database Tuning System via GPT-Guided Bayesian Optimization (Jiale Lao et al., 2023)

{{<citation>}}

Jiale Lao, Yibo Wang, Yufei Li, Jianping Wang, Yunjia Zhang, Zhiyuan Cheng, Wanghu Chen, Mingjie Tang, Jianguo Wang. (2023)  
**GPTuner: A Manual-Reading Database Tuning System via GPT-Guided Bayesian Optimization**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs.DB  
Keywords: GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2311.03157v1)  

---


**ABSTRACT**  
Modern database management systems (DBMS) expose hundreds of configurable knobs to control system behaviours. Determining the appropriate values for these knobs to improve DBMS performance is a long-standing problem in the database community. As there is an increasing number of knobs to tune and each knob could be in continuous or categorical values, manual tuning becomes impractical. Recently, automatic tuning systems using machine learning methods have shown great potentials. However, existing approaches still incur significant tuning costs or only yield sub-optimal performance. This is because they either ignore the extensive domain knowledge available (e.g., DBMS manuals and forum discussions) and only rely on the runtime feedback of benchmark evaluations to guide the optimization, or they utilize the domain knowledge in a limited way. Hence, we propose GPTuner, a manual-reading database tuning system. Firstly, we develop a Large Language Model (LLM)-based pipeline to collect and refine heterogeneous knowledge, and propose a prompt ensemble algorithm to unify a structured view of the refined knowledge. Secondly, using the structured knowledge, we (1) design a workload-aware and training-free knob selection strategy, (2) develop a search space optimization technique considering the value range of each knob, and (3) propose a Coarse-to-Fine Bayesian Optimization Framework to explore the optimized space. Finally, we evaluate GPTuner under different benchmarks (TPC-C and TPC-H), metrics (throughput and latency) as well as DBMS (PostgreSQL and MySQL). Compared to the state-of-the-art approaches, GPTuner identifies better configurations in 16x less time on average. Moreover, GPTuner achieves up to 30% performance improvement (higher throughput or lower latency) over the best-performing alternative.

{{</citation>}}


## cs.CV (24)



### (74/130) Cal-DETR: Calibrated Detection Transformer (Muhammad Akhtar Munir et al., 2023)

{{<citation>}}

Muhammad Akhtar Munir, Salman Khan, Muhammad Haris Khan, Mohsen Ali, Fahad Shahbaz Khan. (2023)  
**Cal-DETR: Calibrated Detection Transformer**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2311.03570v1)  

---


**ABSTRACT**  
Albeit revealing impressive predictive performance for several computer vision tasks, deep neural networks (DNNs) are prone to making overconfident predictions. This limits the adoption and wider utilization of DNNs in many safety-critical applications. There have been recent efforts toward calibrating DNNs, however, almost all of them focus on the classification task. Surprisingly, very little attention has been devoted to calibrating modern DNN-based object detectors, especially detection transformers, which have recently demonstrated promising detection performance and are influential in many decision-making systems. In this work, we address the problem by proposing a mechanism for calibrated detection transformers (Cal-DETR), particularly for Deformable-DETR, UP-DETR and DINO. We pursue the train-time calibration route and make the following contributions. First, we propose a simple yet effective approach for quantifying uncertainty in transformer-based object detectors. Second, we develop an uncertainty-guided logit modulation mechanism that leverages the uncertainty to modulate the class logits. Third, we develop a logit mixing approach that acts as a regularizer with detection-specific losses and is also complementary to the uncertainty-guided logit modulation technique to further improve the calibration performance. Lastly, we conduct extensive experiments across three in-domain and four out-domain scenarios. Results corroborate the effectiveness of Cal-DETR against the competing train-time methods in calibrating both in-domain and out-domain detections while maintaining or even improving the detection performance. Our codebase and pre-trained models can be accessed at \url{https://github.com/akhtarvision/cal-detr}.

{{</citation>}}


### (75/130) Sea You Later: Metadata-Guided Long-Term Re-Identification for UAV-Based Multi-Object Tracking (Cheng-Yen Yang et al., 2023)

{{<citation>}}

Cheng-Yen Yang, Hsiang-Wei Huang, Zhongyu Jiang, Heng-Cheng Kuo, Jie Mei, Chung-I Huang, Jenq-Neng Hwang. (2023)  
**Sea You Later: Metadata-Guided Long-Term Re-Identification for UAV-Based Multi-Object Tracking**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Drone  
[Paper Link](http://arxiv.org/abs/2311.03561v1)  

---


**ABSTRACT**  
Re-identification (ReID) in multi-object tracking (MOT) for UAVs in maritime computer vision has been challenging for several reasons. More specifically, short-term re-identification (ReID) is difficult due to the nature of the characteristics of small targets and the sudden movement of the drone's gimbal. Long-term ReID suffers from the lack of useful appearance diversity. In response to these challenges, we present an adaptable motion-based MOT algorithm, called Metadata Guided MOT (MG-MOT). This algorithm effectively merges short-term tracking data into coherent long-term tracks, harnessing crucial metadata from UAVs, including GPS position, drone altitude, and camera orientations. Extensive experiments are conducted to validate the efficacy of our MOT algorithm. Utilizing the challenging SeaDroneSee tracking dataset, which encompasses the aforementioned scenarios, we achieve a much-improved performance in the latest edition of the UAV-based Maritime Object Tracking Challenge with a state-of-the-art HOTA of 69.5% and an IDF1 of 85.9% on the testing split.

{{</citation>}}


### (76/130) Multi Loss-based Feature Fusion and Top Two Voting Ensemble Decision Strategy for Facial Expression Recognition in the Wild (Guangyao Zhou et al., 2023)

{{<citation>}}

Guangyao Zhou, Yuanlun Xie, Wenhong Tian. (2023)  
**Multi Loss-based Feature Fusion and Top Two Voting Ensemble Decision Strategy for Facial Expression Recognition in the Wild**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2311.03478v1)  

---


**ABSTRACT**  
Facial expression recognition (FER) in the wild is a challenging task affected by the image quality and has attracted broad interest in computer vision. There is no research using feature fusion and ensemble strategy for FER simultaneously. Different from previous studies, this paper applies both internal feature fusion for a single model and feature fusion among multiple networks, as well as the ensemble strategy. This paper proposes one novel single model named R18+FAML, as well as one ensemble model named R18+FAML-FGA-T2V to improve the performance of the FER in the wild. Based on the structure of ResNet18 (R18), R18+FAML combines internal Feature fusion and three Attention blocks using Multiple Loss functions (FAML) to improve the diversity of the feature extraction. To improve the performance of R18+FAML, we propose a Feature fusion among networks based on the Genetic Algorithm (FGA), which can fuse the convolution kernels for feature extraction of multiple networks. On the basis of R18+FAML and FGA, we propose one ensemble strategy, i.e., the Top Two Voting (T2V) to support the classification of FER, which can consider more classification information comprehensively. Combining the above strategies, R18+FAML-FGA-T2V can focus on the main expression-aware areas. Extensive experiments demonstrate that our single model R18+FAML and the ensemble model R18+FAML-FGA-T2V achieve the accuracies of $\left( 90.32, 62.17, 65.83 \right)\%$ and $\left( 91.59, 63.27, 66.63 \right)\%$ on three challenging unbalanced FER datasets RAF-DB, AffectNet-8 and AffectNet-7 respectively, both outperforming the state-of-the-art results.

{{</citation>}}


### (77/130) GLaMM: Pixel Grounding Large Multimodal Model (Hanoona Rasheed et al., 2023)

{{<citation>}}

Hanoona Rasheed, Muhammad Maaz, Sahal Shaji, Abdelrahman Shaker, Salman Khan, Hisham Cholakkal, Rao M. Anwer, Erix Xing, Ming-Hsuan Yang, Fahad S. Khan. (2023)  
**GLaMM: Pixel Grounding Large Multimodal Model**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.03356v1)  

---


**ABSTRACT**  
Large Multimodal Models (LMMs) extend Large Language Models to the vision domain. Initial efforts towards LMMs used holistic images and text prompts to generate ungrounded textual responses. Very recently, region-level LMMs have been used to generate visually grounded responses. However, they are limited to only referring a single object category at a time, require users to specify the regions in inputs, or cannot offer dense pixel-wise object grounding. In this work, we present Grounding LMM (GLaMM), the first model that can generate natural language responses seamlessly intertwined with corresponding object segmentation masks. GLaMM not only grounds objects appearing in the conversations but is flexible enough to accept both textual and optional visual prompts (region of interest) as input. This empowers users to interact with the model at various levels of granularity, both in textual and visual domains. Due to the lack of standard benchmarks for the novel setting of generating visually grounded detailed conversations, we introduce a comprehensive evaluation protocol with our curated grounded conversations. Our proposed Grounded Conversation Generation (GCG) task requires densely grounded concepts in natural scenes at a large-scale. To this end, we propose a densely annotated Grounding-anything Dataset (GranD) using our proposed automated annotation pipeline that encompasses 7.5M unique concepts grounded in a total of 810M regions available with segmentation masks. Besides GCG, GLaMM also performs effectively on several downstream tasks e.g., referring expression segmentation, image and region-level captioning and vision-language conversations. Project Page: https://mbzuai-oryx.github.io/groundingLMM.

{{</citation>}}


### (78/130) CoVLM: Composing Visual Entities and Relationships in Large Language Models Via Communicative Decoding (Junyan Li et al., 2023)

{{<citation>}}

Junyan Li, Delin Chen, Yining Hong, Zhenfang Chen, Peihao Chen, Yikang Shen, Chuang Gan. (2023)  
**CoVLM: Composing Visual Entities and Relationships in Large Language Models Via Communicative Decoding**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.03354v1)  

---


**ABSTRACT**  
A remarkable ability of human beings resides in compositional reasoning, i.e., the capacity to make "infinite use of finite means". However, current large vision-language foundation models (VLMs) fall short of such compositional abilities due to their "bag-of-words" behaviors and inability to construct words that correctly represent visual entities and the relations among the entities. To this end, we propose CoVLM, which can guide the LLM to explicitly compose visual entities and relationships among the text and dynamically communicate with the vision encoder and detection network to achieve vision-language communicative decoding. Specifically, we first devise a set of novel communication tokens for the LLM, for dynamic communication between the visual detection system and the language system. A communication token is generated by the LLM following a visual entity or a relation, to inform the detection network to propose regions that are relevant to the sentence generated so far. The proposed regions-of-interests (ROIs) are then fed back into the LLM for better language generation contingent on the relevant regions. The LLM is thus able to compose the visual entities and relationships through the communication tokens. The vision-to-language and language-to-vision communication are iteratively performed until the entire sentence is generated. Our framework seamlessly bridges the gap between visual perception and LLMs and outperforms previous VLMs by a large margin on compositional reasoning benchmarks (e.g., ~20% in HICO-DET mAP, ~14% in Cola top-1 accuracy, and ~3% on ARO top-1 accuracy). We also achieve state-of-the-art performances on traditional vision-language tasks such as referring expression comprehension and visual question answering.

{{</citation>}}


### (79/130) FLOGA: A machine learning ready dataset, a benchmark and a novel deep learning model for burnt area mapping with Sentinel-2 (Maria Sdraka et al., 2023)

{{<citation>}}

Maria Sdraka, Alkinoos Dimakos, Alexandros Malounis, Zisoula Ntasiou, Konstantinos Karantzalos, Dimitrios Michail, Ioannis Papoutsis. (2023)  
**FLOGA: A machine learning ready dataset, a benchmark and a novel deep learning model for burnt area mapping with Sentinel-2**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03339v1)  

---


**ABSTRACT**  
Over the last decade there has been an increasing frequency and intensity of wildfires across the globe, posing significant threats to human and animal lives, ecosystems, and socio-economic stability. Therefore urgent action is required to mitigate their devastating impact and safeguard Earth's natural resources. Robust Machine Learning methods combined with the abundance of high-resolution satellite imagery can provide accurate and timely mappings of the affected area in order to assess the scale of the event, identify the impacted assets and prioritize and allocate resources effectively for the proper restoration of the damaged region. In this work, we create and introduce a machine-learning ready dataset we name FLOGA (Forest wiLdfire Observations for the Greek Area). This dataset is unique as it comprises of satellite imagery acquired before and after a wildfire event, it contains information from Sentinel-2 and MODIS modalities with variable spatial and spectral resolution, and contains a large number of events where the corresponding burnt area ground truth has been annotated by domain experts. FLOGA covers the wider region of Greece, which is characterized by a Mediterranean landscape and climatic conditions. We use FLOGA to provide a thorough comparison of multiple Machine Learning and Deep Learning algorithms for the automatic extraction of burnt areas, approached as a change detection task. We also compare the results to those obtained using standard specialized spectral indices for burnt area mapping. Finally, we propose a novel Deep Learning model, namely BAM-CD. Our benchmark results demonstrate the efficacy of the proposed technique in the automatic extraction of burnt areas, outperforming all other methods in terms of accuracy and robustness. Our dataset and code are publicly available at: https://github.com/Orion-AI-Lab/FLOGA.

{{</citation>}}


### (80/130) Cross-Image Attention for Zero-Shot Appearance Transfer (Yuval Alaluf et al., 2023)

{{<citation>}}

Yuval Alaluf, Daniel Garibi, Or Patashnik, Hadar Averbuch-Elor, Daniel Cohen-Or. (2023)  
**Cross-Image Attention for Zero-Shot Appearance Transfer**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-GR, cs.CV  
Keywords: Attention, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2311.03335v1)  

---


**ABSTRACT**  
Recent advancements in text-to-image generative models have demonstrated a remarkable ability to capture a deep semantic understanding of images. In this work, we leverage this semantic knowledge to transfer the visual appearance between objects that share similar semantics but may differ significantly in shape. To achieve this, we build upon the self-attention layers of these generative models and introduce a cross-image attention mechanism that implicitly establishes semantic correspondences across images. Specifically, given a pair of images -- one depicting the target structure and the other specifying the desired appearance -- our cross-image attention combines the queries corresponding to the structure image with the keys and values of the appearance image. This operation, when applied during the denoising process, leverages the established semantic correspondences to generate an image combining the desired structure and appearance. In addition, to improve the output image quality, we harness three mechanisms that either manipulate the noisy latent codes or the model's internal representations throughout the denoising process. Importantly, our approach is zero-shot, requiring no optimization or training. Experiments show that our method is effective across a wide range of object categories and is robust to variations in shape, size, and viewpoint between the two input images.

{{</citation>}}


### (81/130) TSP-Transformer: Task-Specific Prompts Boosted Transformer for Holistic Scene Understanding (Shuo Wang et al., 2023)

{{<citation>}}

Shuo Wang, Jing Li, Zibo Zhao, Dongze Lian, Binbin Huang, Xiaomei Wang, Zhengxin Li, Shenghua Gao. (2023)  
**TSP-Transformer: Task-Specific Prompts Boosted Transformer for Holistic Scene Understanding**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2311.03427v1)  

---


**ABSTRACT**  
Holistic scene understanding includes semantic segmentation, surface normal estimation, object boundary detection, depth estimation, etc. The key aspect of this problem is to learn representation effectively, as each subtask builds upon not only correlated but also distinct attributes. Inspired by visual-prompt tuning, we propose a Task-Specific Prompts Transformer, dubbed TSP-Transformer, for holistic scene understanding. It features a vanilla transformer in the early stage and tasks-specific prompts transformer encoder in the lateral stage, where tasks-specific prompts are augmented. By doing so, the transformer layer learns the generic information from the shared parts and is endowed with task-specific capacity. First, the tasks-specific prompts serve as induced priors for each task effectively. Moreover, the task-specific prompts can be seen as switches to favor task-specific representation learning for different tasks. Extensive experiments on NYUD-v2 and PASCAL-Context show that our method achieves state-of-the-art performance, validating the effectiveness of our method for holistic scene understanding. We also provide our code in the following link https://github.com/tb2-sy/TSP-Transformer.

{{</citation>}}


### (82/130) Machine Learning-Based Tea Leaf Disease Detection: A Comprehensive Review (Faruk Ahmed et al., 2023)

{{<citation>}}

Faruk Ahmed, Md. Taimur Ahad, Yousuf Rayhan Emon. (2023)  
**Machine Learning-Based Tea Leaf Disease Detection: A Comprehensive Review**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV, eess-IV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2311.03240v1)  

---


**ABSTRACT**  
Tea leaf diseases are a major challenge to agricultural productivity, with far-reaching implications for yield and quality in the tea industry. The rise of machine learning has enabled the development of innovative approaches to combat these diseases. Early detection and diagnosis are crucial for effective crop management. For predicting tea leaf disease, several automated systems have already been developed using different image processing techniques. This paper delivers a systematic review of the literature on machine learning methodologies applied to diagnose tea leaf disease via image classification. It thoroughly evaluates the strengths and constraints of various Vision Transformer models, including Inception Convolutional Vision Transformer (ICVT), GreenViT, PlantXViT, PlantViT, MSCVT, Transfer Learning Model & Vision Transformer (TLMViT), IterationViT, IEM-ViT. Moreover, this paper also reviews models like Dense Convolutional Network (DenseNet), Residual Neural Network (ResNet)-50V2, YOLOv5, YOLOv7, Convolutional Neural Network (CNN), Deep CNN, Non-dominated Sorting Genetic Algorithm (NSGA-II), MobileNetv2, and Lesion-Aware Visual Transformer. These machine-learning models have been tested on various datasets, demonstrating their real-world applicability. This review study not only highlights current progress in the field but also provides valuable insights for future research directions in the machine learning-based detection and classification of tea leaf diseases.

{{</citation>}}


### (83/130) LCPR: A Multi-Scale Attention-Based LiDAR-Camera Fusion Network for Place Recognition (Zijie Zhou et al., 2023)

{{<citation>}}

Zijie Zhou, Jingyi Xu, Guangming Xiong, Junyi Ma. (2023)  
**LCPR: A Multi-Scale Attention-Based LiDAR-Camera Fusion Network for Place Recognition**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2311.03198v1)  

---


**ABSTRACT**  
Place recognition is one of the most crucial modules for autonomous vehicles to identify places that were previously visited in GPS-invalid environments. Sensor fusion is considered an effective method to overcome the weaknesses of individual sensors. In recent years, multimodal place recognition fusing information from multiple sensors has gathered increasing attention. However, most existing multimodal place recognition methods only use limited field-of-view camera images, which leads to an imbalance between features from different modalities and limits the effectiveness of sensor fusion. In this paper, we present a novel neural network named LCPR for robust multimodal place recognition, which fuses LiDAR point clouds with multi-view RGB images to generate discriminative and yaw-rotation invariant representations of the environment. A multi-scale attention-based fusion module is proposed to fully exploit the panoramic views from different modalities of the environment and their correlations. We evaluate our method on the nuScenes dataset, and the experimental results show that our method can effectively utilize multi-view camera and LiDAR data to improve the place recognition performance while maintaining strong robustness to viewpoint changes. Our open-source code and pre-trained models are available at https://github.com/ZhouZijie77/LCPR .

{{</citation>}}


### (84/130) Few-shot Learning using Data Augmentation and Time-Frequency Transformation for Time Series Classification (Hao Zhang et al., 2023)

{{<citation>}}

Hao Zhang, Zhendong Pang, Jiangpeng Wang, Teng Li. (2023)  
**Few-shot Learning using Data Augmentation and Time-Frequency Transformation for Time Series Classification**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Augmentation, Time Series  
[Paper Link](http://arxiv.org/abs/2311.03194v1)  

---


**ABSTRACT**  
Deep neural networks (DNNs) that tackle the time series classification (TSC) task have provided a promising framework in signal processing. In real-world applications, as a data-driven model, DNNs are suffered from insufficient data. Few-shot learning has been studied to deal with this limitation. In this paper, we propose a novel few-shot learning framework through data augmentation, which involves transformation through the time-frequency domain and the generation of synthetic images through random erasing. Additionally, we develop a sequence-spectrogram neural network (SSNN). This neural network model composes of two sub-networks: one utilizing 1D residual blocks to extract features from the input sequence while the other one employing 2D residual blocks to extract features from the spectrogram representation. In the experiments, comparison studies of different existing DNN models with/without data augmentation are conducted on an amyotrophic lateral sclerosis (ALS) dataset and a wind turbine fault (WTF) dataset. The experimental results manifest that our proposed method achieves 93.75% F1 score and 93.33% accuracy on the ALS datasets while 95.48% F1 score and 95.59% accuracy on the WTF datasets. Our methodology demonstrates its applicability of addressing the few-shot problems for time series classification.

{{</citation>}}


### (85/130) 1D-Convolutional transformer for Parkinson disease diagnosis from gait (Safwen Naimi et al., 2023)

{{<citation>}}

Safwen Naimi, Wassim Bouachir, Guillaume-Alexandre Bilodeau. (2023)  
**1D-Convolutional transformer for Parkinson disease diagnosis from gait**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: AI, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.03177v1)  

---


**ABSTRACT**  
This paper presents an efficient deep neural network model for diagnosing Parkinson's disease from gait. More specifically, we introduce a hybrid ConvNet-Transformer architecture to accurately diagnose the disease by detecting the severity stage. The proposed architecture exploits the strengths of both Convolutional Neural Networks and Transformers in a single end-to-end model, where the former is able to extract relevant local features from Vertical Ground Reaction Force (VGRF) signal, while the latter allows to capture long-term spatio-temporal dependencies in data. In this manner, our hybrid architecture achieves an improved performance compared to using either models individually. Our experimental results show that our approach is effective for detecting the different stages of Parkinson's disease from gait data, with a final accuracy of 88%, outperforming other state-of-the-art AI methods on the Physionet gait dataset. Moreover, our method can be generalized and adapted for other classification problems to jointly address the feature relevance and spatio-temporal dependency problems in 1D signals. Our source code and pre-trained models are publicly available at https://github.com/SafwenNaimi/1D-Convolutional-transformer-for-Parkinson-disease-diagnosis-from-gait.

{{</citation>}}


### (86/130) Unified Multi-modal Unsupervised Representation Learning for Skeleton-based Action Understanding (Shengkai Sun et al., 2023)

{{<citation>}}

Shengkai Sun, Daizong Liu, Jianfeng Dong, Xiaoye Qu, Junyu Gao, Xun Yang, Xun Wang, Meng Wang. (2023)  
**Unified Multi-modal Unsupervised Representation Learning for Skeleton-based Action Understanding**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2311.03106v1)  

---


**ABSTRACT**  
Unsupervised pre-training has shown great success in skeleton-based action understanding recently. Existing works typically train separate modality-specific models, then integrate the multi-modal information for action understanding by a late-fusion strategy. Although these approaches have achieved significant performance, they suffer from the complex yet redundant multi-stream model designs, each of which is also limited to the fixed input skeleton modality. To alleviate these issues, in this paper, we propose a Unified Multimodal Unsupervised Representation Learning framework, called UmURL, which exploits an efficient early-fusion strategy to jointly encode the multi-modal features in a single-stream manner. Specifically, instead of designing separate modality-specific optimization processes for uni-modal unsupervised learning, we feed different modality inputs into the same stream with an early-fusion strategy to learn their multi-modal features for reducing model complexity. To ensure that the fused multi-modal features do not exhibit modality bias, i.e., being dominated by a certain modality input, we further propose both intra- and inter-modal consistency learning to guarantee that the multi-modal features contain the complete semantics of each modal via feature decomposition and distinct alignment. In this manner, our framework is able to learn the unified representations of uni-modal or multi-modal skeleton input, which is flexible to different kinds of modality input for robust action understanding in practical cases. Extensive experiments conducted on three large-scale datasets, i.e., NTU-60, NTU-120, and PKU-MMD II, demonstrate that UmURL is highly efficient, possessing the approximate complexity with the uni-modal methods, while achieving new state-of-the-art performance across various downstream task scenarios in skeleton-based action representation learning.

{{</citation>}}


### (87/130) CogVLM: Visual Expert for Pretrained Language Models (Weihan Wang et al., 2023)

{{<citation>}}

Weihan Wang, Qingsong Lv, Wenmeng Yu, Wenyi Hong, Ji Qi, Yan Wang, Junhui Ji, Zhuoyi Yang, Lei Zhao, Xixuan Song, Jiazheng Xu, Bin Xu, Juanzi Li, Yuxiao Dong, Ming Ding, Jie Tang. (2023)  
**CogVLM: Visual Expert for Pretrained Language Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Language Model, NLP, Pretrained Language Models, QA  
[Paper Link](http://arxiv.org/abs/2311.03079v1)  

---


**ABSTRACT**  
We introduce CogVLM, a powerful open-source visual language foundation model. Different from the popular shallow alignment method which maps image features into the input space of language model, CogVLM bridges the gap between the frozen pretrained language model and image encoder by a trainable visual expert module in the attention and FFN layers. As a result, CogVLM enables deep fusion of vision language features without sacrificing any performance on NLP tasks. CogVLM-17B achieves state-of-the-art performance on 10 classic cross-modal benchmarks, including NoCaps, Flicker30k captioning, RefCOCO, RefCOCO+, RefCOCOg, Visual7W, GQA, ScienceQA, VizWiz VQA and TDIUC, and ranks the 2nd on VQAv2, OKVQA, TextVQA, COCO captioning, etc., surpassing or matching PaLI-X 55B. Codes and checkpoints are available at https://github.com/THUDM/CogVLM.

{{</citation>}}


### (88/130) SugarViT -- Multi-objective Regression of UAV Images with Vision Transformers and Deep Label Distribution Learning Demonstrated on Disease Severity Prediction in Sugar Beet (Maurice Günder et al., 2023)

{{<citation>}}

Maurice Günder, Facundo Ramón Ispizua Yamati, Abel Andree Barreto Alcántara, Anne-Katrin Mahlein, Rafet Sifa, Christian Bauckhage. (2023)  
**SugarViT -- Multi-objective Regression of UAV Images with Vision Transformers and Deep Label Distribution Learning Demonstrated on Disease Severity Prediction in Sugar Beet**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.03076v2)  

---


**ABSTRACT**  
Remote sensing and artificial intelligence are pivotal technologies of precision agriculture nowadays. The efficient retrieval of large-scale field imagery combined with machine learning techniques shows success in various tasks like phenotyping, weeding, cropping, and disease control. This work will introduce a machine learning framework for automatized large-scale plant-specific trait annotation for the use case disease severity scoring for Cercospora Leaf Spot (CLS) in sugar beet. With concepts of Deep Label Distribution Learning (DLDL), special loss functions, and a tailored model architecture, we develop an efficient Vision Transformer based model for disease severity scoring called SugarViT. One novelty in this work is the combination of remote sensing data with environmental parameters of the experimental sites for disease severity prediction. Although the model is evaluated on this special use case, it is held as generic as possible to also be applicable to various image-based classification and regression tasks. With our framework, it is even possible to learn models on multi-objective problems as we show by a pretraining on environmental metadata.

{{</citation>}}


### (89/130) OrthoNets: Orthogonal Channel Attention Networks (Hadi Salman et al., 2023)

{{<citation>}}

Hadi Salman, Caleb Parks, Matthew Swan, John Gauch. (2023)  
**OrthoNets: Orthogonal Channel Attention Networks**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, ImageNet  
[Paper Link](http://arxiv.org/abs/2311.03071v2)  

---


**ABSTRACT**  
Designing an effective channel attention mechanism implores one to find a lossy-compression method allowing for optimal feature representation. Despite recent progress in the area, it remains an open problem. FcaNet, the current state-of-the-art channel attention mechanism, attempted to find such an information-rich compression using Discrete Cosine Transforms (DCTs). One drawback of FcaNet is that there is no natural choice of the DCT frequencies. To circumvent this issue, FcaNet experimented on ImageNet to find optimal frequencies. We hypothesize that the choice of frequency plays only a supporting role and the primary driving force for the effectiveness of their attention filters is the orthogonality of the DCT kernels. To test this hypothesis, we construct an attention mechanism using randomly initialized orthogonal filters. Integrating this mechanism into ResNet, we create OrthoNet. We compare OrthoNet to FcaNet (and other attention mechanisms) on Birds, MS-COCO, and Places356 and show superior performance. On the ImageNet dataset, our method competes with or surpasses the current state-of-the-art. Our results imply that an optimal choice of filter is elusive and generalization can be achieved with a sufficiently large number of orthogonal filters. We further investigate other general principles for implementing channel attention, such as its position in the network and channel groupings. Our code is publicly available at https://github.com/hady1011/OrthoNets/

{{</citation>}}


### (90/130) AnyText: Multilingual Visual Text Generation And Editing (Yuxiang Tuo et al., 2023)

{{<citation>}}

Yuxiang Tuo, Wangmeng Xiang, Jun-Yan He, Yifeng Geng, Xuansong Xie. (2023)  
**AnyText: Multilingual Visual Text Generation And Editing**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Multilingual, OCR, Text Generation  
[Paper Link](http://arxiv.org/abs/2311.03054v2)  

---


**ABSTRACT**  
Diffusion model based Text-to-Image has achieved impressive achievements recently. Although current technology for synthesizing images is highly advanced and capable of generating images with high fidelity, it is still possible to give the show away when focusing on the text area in the generated image. To address this issue, we introduce AnyText, a diffusion-based multilingual visual text generation and editing model, that focuses on rendering accurate and coherent text in the image. AnyText comprises a diffusion pipeline with two primary elements: an auxiliary latent module and a text embedding module. The former uses inputs like text glyph, position, and masked image to generate latent features for text generation or editing. The latter employs an OCR model for encoding stroke data as embeddings, which blend with image caption embeddings from the tokenizer to generate texts that seamlessly integrate with the background. We employed text-control diffusion loss and text perceptual loss for training to further enhance writing accuracy. AnyText can write characters in multiple languages, to the best of our knowledge, this is the first work to address multilingual visual text generation. It is worth mentioning that AnyText can be plugged into existing diffusion models from the community for rendering or editing text accurately. After conducting extensive evaluation experiments, our method has outperformed all other approaches by a significant margin. Additionally, we contribute the first large-scale multilingual text images dataset, AnyWord-3M, containing 3 million image-text pairs with OCR annotations in multiple languages. Based on AnyWord-3M dataset, we propose AnyText-benchmark for the evaluation of visual text generation accuracy and quality. Our project will be open-sourced on https://github.com/tyxsspa/AnyText to improve and promote the development of text generation technology.

{{</citation>}}


### (91/130) MixUp-MIL: A Study on Linear & Multilinear Interpolation-Based Data Augmentation for Whole Slide Image Classification (Michael Gadermayr et al., 2023)

{{<citation>}}

Michael Gadermayr, Lukas Koller, Maximilian Tschuchnig, Lea Maria Stangassinger, Christina Kreutzer, Sebastien Couillard-Despres, Gertie Janneke Oostingh, Anton Hittmair. (2023)  
**MixUp-MIL: A Study on Linear & Multilinear Interpolation-Based Data Augmentation for Whole Slide Image Classification**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Augmentation, Image Classification  
[Paper Link](http://arxiv.org/abs/2311.03052v1)  

---


**ABSTRACT**  
For classifying digital whole slide images in the absence of pixel level annotation, typically multiple instance learning methods are applied. Due to the generic applicability, such methods are currently of very high interest in the research community, however, the issue of data augmentation in this context is rarely explored. Here we investigate linear and multilinear interpolation between feature vectors, a data augmentation technique, which proved to be capable of improving the generalization performance classification networks and also for multiple instance learning. Experiments, however, have been performed on only two rather small data sets and one specific feature extraction approach so far and a strong dependence on the data set has been identified. Here we conduct a large study incorporating 10 different data set configurations, two different feature extraction approaches (supervised and self-supervised), stain normalization and two multiple instance learning architectures. The results showed an extraordinarily high variability in the effect of the method. We identified several interesting aspects to bring light into the darkness and identified novel promising fields of research.

{{</citation>}}


### (92/130) GTP-ViT: Efficient Vision Transformers via Graph-based Token Propagation (Xuwei Xu et al., 2023)

{{<citation>}}

Xuwei Xu, Sen Wang, Yudong Chen, Yanping Zheng, Zhewei Wei, Jiajun Liu. (2023)  
**GTP-ViT: Efficient Vision Transformers via Graph-based Token Propagation**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: ImageNet, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.03035v1)  

---


**ABSTRACT**  
Vision Transformers (ViTs) have revolutionized the field of computer vision, yet their deployments on resource-constrained devices remain challenging due to high computational demands. To expedite pre-trained ViTs, token pruning and token merging approaches have been developed, which aim at reducing the number of tokens involved in the computation. However, these methods still have some limitations, such as image information loss from pruned tokens and inefficiency in the token-matching process. In this paper, we introduce a novel Graph-based Token Propagation (GTP) method to resolve the challenge of balancing model efficiency and information preservation for efficient ViTs. Inspired by graph summarization algorithms, GTP meticulously propagates less significant tokens' information to spatially and semantically connected tokens that are of greater importance. Consequently, the remaining few tokens serve as a summarization of the entire token graph, allowing the method to reduce computational complexity while preserving essential information of eliminated tokens. Combined with an innovative token selection strategy, GTP can efficiently identify image tokens to be propagated. Extensive experiments have validated GTP's effectiveness, demonstrating both efficiency and performance improvements. Specifically, GTP decreases the computational complexity of both DeiT-S and DeiT-B by up to 26% with only a minimal 0.3% accuracy drop on ImageNet-1K without finetuning, and remarkably surpasses the state-of-the-art token merging method on various backbones at an even faster inference speed. The source code is available at https://github.com/Ackesnal/GTP-ViT.

{{</citation>}}


### (93/130) Zero-Shot Enhancement of Low-Light Image Based on Retinex Decomposition (Wenchao Li et al., 2023)

{{<citation>}}

Wenchao Li, Bangshu Xiong, Qiaofeng Ou, Xiaoyun Long, Jinhao Zhu, Jiabao Chen, Shuyuan Wen. (2023)  
**Zero-Shot Enhancement of Low-Light Image Based on Retinex Decomposition**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-GR, cs.CV  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2311.02995v1)  

---


**ABSTRACT**  
Two difficulties here make low-light image enhancement a challenging task; firstly, it needs to consider not only luminance restoration but also image contrast, image denoising and color distortion issues simultaneously. Second, the effectiveness of existing low-light enhancement methods depends on paired or unpaired training data with poor generalization performance.   To solve these difficult problems, we propose in this paper a new learning-based Retinex decomposition of zero-shot low-light enhancement method, called ZERRINNet. To this end, we first designed the N-Net network, together with the noise loss term, to be used for denoising the original low-light image by estimating the noise of the low-light image. Moreover, RI-Net is used to estimate the reflection component and illumination component, and in order to solve the color distortion and contrast, we use the texture loss term and segmented smoothing loss to constrain the reflection component and illumination component. Finally, our method is a zero-reference enhancement method that is not affected by the training data of paired and unpaired datasets, so our generalization performance is greatly improved, and in the paper, we have effectively validated it with a homemade real-life low-light dataset and additionally with advanced vision tasks, such as face detection, target recognition, and instance segmentation. We conducted comparative experiments on a large number of public datasets and the results show that the performance of our method is competitive compared to the current state-of-the-art methods. The code is available at:https://github.com/liwenchao0615/ZERRINNet

{{</citation>}}


### (94/130) Deep Image Semantic Communication Model for Artificial Intelligent Internet of Things (Li Ping Qian et al., 2023)

{{<citation>}}

Li Ping Qian, Yi Zhang, Sikai Lyu, Huijie Zhu, Yuan Wu, Xuemin Sherman Shen, Xiaoniu Yang. (2023)  
**Deep Image Semantic Communication Model for Artificial Intelligent Internet of Things**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.02926v2)  

---


**ABSTRACT**  
With the rapid development of Artificial Intelligent Internet of Things (AIoT), the image data from AIoT devices has been witnessing the explosive increasing. In this paper, a novel deep image semantic communication model is proposed for the efficient image communication in AIoT. Particularly, at the transmitter side, a high-precision image semantic segmentation algorithm is proposed to extract the semantic information of the image to achieve significant compression of the image data. At the receiver side, a semantic image restoration algorithm based on Generative Adversarial Network (GAN) is proposed to convert the semantic image to a real scene image with detailed information. Simulation results demonstrate that the proposed image semantic communication model can improve the image compression ratio and recovery accuracy by 71.93% and 25.07% on average in comparison with WebP and CycleGAN, respectively. More importantly, our demo experiment shows that the proposed model reduces the total delay by 95.26% in the image communication, when comparing with the original image transmission.

{{</citation>}}


### (95/130) Stacked Autoencoder Based Feature Extraction and Superpixel Generation for Multifrequency PolSAR Image Classification (Tushar Gadhiya et al., 2023)

{{<citation>}}

Tushar Gadhiya, Sumanth Tangirala, Anil K. Roy. (2023)  
**Stacked Autoencoder Based Feature Extraction and Superpixel Generation for Multifrequency PolSAR Image Classification**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Image Classification  
[Paper Link](http://arxiv.org/abs/2311.02887v1)  

---


**ABSTRACT**  
In this paper we are proposing classification algorithm for multifrequency Polarimetric Synthetic Aperture Radar (PolSAR) image. Using PolSAR decomposition algorithms 33 features are extracted from each frequency band of the given image. Then, a two-layer autoencoder is used to reduce the dimensionality of input feature vector while retaining useful features of the input. This reduced dimensional feature vector is then applied to generate superpixels using simple linear iterative clustering (SLIC) algorithm. Next, a robust feature representation is constructed using both pixel as well as superpixel information. Finally, softmax classifier is used to perform classification task. The advantage of using superpixels is that it preserves spatial information between neighbouring PolSAR pixels and therefore minimises the effect of speckle noise during classification. Experiments have been conducted on Flevoland dataset and the proposed method was found to be superior to other methods available in the literature.

{{</citation>}}


### (96/130) Efficient, Self-Supervised Human Pose Estimation with Inductive Prior Tuning (Nobline Yoo et al., 2023)

{{<citation>}}

Nobline Yoo, Olga Russakovsky. (2023)  
**Efficient, Self-Supervised Human Pose Estimation with Inductive Prior Tuning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2311.02815v1)  

---


**ABSTRACT**  
The goal of 2D human pose estimation (HPE) is to localize anatomical landmarks, given an image of a person in a pose. SOTA techniques make use of thousands of labeled figures (finetuning transformers or training deep CNNs), acquired using labor-intensive crowdsourcing. On the other hand, self-supervised methods re-frame the HPE task as a reconstruction problem, enabling them to leverage the vast amount of unlabeled visual data, though at the present cost of accuracy. In this work, we explore ways to improve self-supervised HPE. We (1) analyze the relationship between reconstruction quality and pose estimation accuracy, (2) develop a model pipeline that outperforms the baseline which inspired our work, using less than one-third the amount of training data, and (3) offer a new metric suitable for self-supervised settings that measures the consistency of predicted body part length proportions. We show that a combination of well-engineered reconstruction losses and inductive priors can help coordinate pose learning alongside reconstruction in a self-supervised paradigm.

{{</citation>}}


### (97/130) Fast and Interpretable Face Identification for Out-Of-Distribution Data Using Vision Transformers (Hai Phan et al., 2023)

{{<citation>}}

Hai Phan, Cindy Le, Vu Le, Yihui He, Anh Totti Nguyen. (2023)  
**Fast and Interpretable Face Identification for Out-Of-Distribution Data Using Vision Transformers**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.02803v1)  

---


**ABSTRACT**  
Most face identification approaches employ a Siamese neural network to compare two images at the image embedding level. Yet, this technique can be subject to occlusion (e.g. faces with masks or sunglasses) and out-of-distribution data. DeepFace-EMD (Phan et al. 2022) reaches state-of-the-art accuracy on out-of-distribution data by first comparing two images at the image level, and then at the patch level. Yet, its later patch-wise re-ranking stage admits a large $O(n^3 \log n)$ time complexity (for $n$ patches in an image) due to the optimal transport optimization. In this paper, we propose a novel, 2-image Vision Transformers (ViTs) that compares two images at the patch level using cross-attention. After training on 2M pairs of images on CASIA Webface (Yi et al. 2014), our model performs at a comparable accuracy as DeepFace-EMD on out-of-distribution data, yet at an inference speed more than twice as fast as DeepFace-EMD (Phan et al. 2022). In addition, via a human study, our model shows promising explainability through the visualization of cross-attention. We believe our work can inspire more explorations in using ViTs for face identification.

{{</citation>}}


## cs.HC (3)



### (98/130) Inclusive Portraits: Race-Aware Human-in-the-Loop Technology (Claudia Flores-Saviaga et al., 2023)

{{<citation>}}

Claudia Flores-Saviaga, Christopher Curtis, Saiph Savage. (2023)  
**Inclusive Portraits: Race-Aware Human-in-the-Loop Technology**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03567v1)  

---


**ABSTRACT**  
AI has revolutionized the processing of various services, including the automatic facial verification of people. Automated approaches have demonstrated their speed and efficiency in verifying a large volume of faces, but they can face challenges when processing content from certain communities, including communities of people of color. This challenge has prompted the adoption of "human-in-the-loop" (HITL) approaches, where human workers collaborate with the AI to minimize errors. However, most HITL approaches do not consider workers' individual characteristics and backgrounds. This paper proposes a new approach, called Inclusive Portraits (IP), that connects with social theories around race to design a racially-aware human-in-the-loop system. Our experiments have provided evidence that incorporating race into human-in-the-loop (HITL) systems for facial verification can significantly enhance performance, especially for services delivered to people of color. Our findings also highlight the importance of considering individual worker characteristics in the design of HITL systems, rather than treating workers as a homogenous group. Our research has significant design implications for developing AI-enhanced services that are more inclusive and equitable.

{{</citation>}}


### (99/130) Fostering Human Learning in Sequential Decision-Making: Understanding the Role of Evaluative Feedback (Piyush Gupta et al., 2023)

{{<citation>}}

Piyush Gupta, Subir Biswas, Vaibhav Srivastava. (2023)  
**Fostering Human Learning in Sequential Decision-Making: Understanding the Role of Evaluative Feedback**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI, Amazon  
[Paper Link](http://arxiv.org/abs/2311.03486v1)  

---


**ABSTRACT**  
Cognitive rehabilitation, STEM skill acquisition, and coaching games such as chess often require tutoring decision-making strategies. The advancement of AI-driven tutoring systems for facilitating human learning requires an understanding of the impact of evaluative feedback on human decision-making and skill development. To this end, we conduct human experiments using Amazon Mechanical Turk to study the influence of evaluative feedback on human decision-making in sequential tasks. In these experiments, participants solve the Tower of Hanoi puzzle and receive AI-generated feedback while solving it. We examine how this feedback affects their learning and skill transfer to related tasks. We also explore various computational models to understand how people incorporate evaluative feedback into their decision-making processes.

{{</citation>}}


### (100/130) AttentioNet: Monitoring Student Attention Type in Learning with EEG-Based Measurement System (Dhruv Verma et al., 2023)

{{<citation>}}

Dhruv Verma, Sejal Bhalla, S. V. Sai Santosh, Saumya Yadav, Aman Parnami, Jainendra Shukla. (2023)  
**AttentioNet: Monitoring Student Attention Type in Learning with EEG-Based Measurement System**  

---
Primary Category: cs.HC  
Categories: I-2-6; K-3-1, cs-HC, cs.HC  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2311.02924v1)  

---


**ABSTRACT**  
Student attention is an indispensable input for uncovering their goals, intentions, and interests, which prove to be invaluable for a multitude of research areas, ranging from psychology to interactive systems. However, most existing methods to classify attention fail to model its complex nature. To bridge this gap, we propose AttentioNet, a novel Convolutional Neural Network-based approach that utilizes Electroencephalography (EEG) data to classify attention into five states: Selective, Sustained, Divided, Alternating, and relaxed state. We collected a dataset of 20 subjects through standard neuropsychological tasks to elicit different attentional states. The average across-student accuracy of our proposed model at this configuration is 92.3% (SD=3.04), which is well-suited for end-user applications. Our transfer learning-based approach for personalizing the model to individual subjects effectively addresses the issue of individual variability in EEG signals, resulting in improved performance and adaptability of the model for real-world applications. This represents a significant advancement in the field of EEG-based classification. Experimental results demonstrate that AttentioNet outperforms a popular EEGnet baseline (p-value < 0.05) in both subject-independent and subject-dependent settings, confirming the effectiveness of our proposed approach despite the limitations of our dataset. These results highlight the promising potential of AttentioNet for attention classification using EEG data.

{{</citation>}}


## cs.AI (5)



### (101/130) Environmental-Impact Based Multi-Agent Reinforcement Learning (Farinaz Alamiyan-Harandi et al., 2023)

{{<citation>}}

Farinaz Alamiyan-Harandi, Pouria Ramazi. (2023)  
**Environmental-Impact Based Multi-Agent Reinforcement Learning**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.04240v1)  

---


**ABSTRACT**  
To promote cooperation and strengthen the individual impact on the collective outcome in social dilemmas, we propose the Environmental-impact Multi-Agent Reinforcement Learning (EMuReL) method where each agent estimates the "environmental impact" of every other agent, that is, the difference in the current environment state compared to the hypothetical environment in the absence of that other agent. Inspired by the Inequity Aversion model, the agent then compares its own reward with those of its fellows multiplied by their environmental impacts. If its reward exceeds the scaled reward of one of its fellows, the agent takes "social responsibility" toward that fellow by reducing its own reward. Therefore, the less influential an agent is in reaching the current state, the more social responsibility is taken by other agents. Experiments in the Cleanup (resp. Harvest) test environment demonstrate that agents trained based on EMuReL learn to cooperate more effectively and obtain $54\%$ ($39\%$) and $20\%$ ($44\%$) more total rewards while preserving the same cooperation levels compared to when they are trained based on the two state-of-the-art reward reshaping methods inequity aversion and social influence.

{{</citation>}}


### (102/130) Kindness in Multi-Agent Reinforcement Learning (Farinaz Alamiyan-Harandi et al., 2023)

{{<citation>}}

Farinaz Alamiyan-Harandi, Mersad Hassanjani, Pouria Ramazi. (2023)  
**Kindness in Multi-Agent Reinforcement Learning**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.04239v1)  

---


**ABSTRACT**  
In human societies, people often incorporate fairness in their decisions and treat reciprocally by being kind to those who act kindly. They evaluate the kindness of others' actions not only by monitoring the outcomes but also by considering the intentions. This behavioral concept can be adapted to train cooperative agents in Multi-Agent Reinforcement Learning (MARL). We propose the KindMARL method, where agents' intentions are measured by counterfactual reasoning over the environmental impact of the actions that were available to the agents. More specifically, the current environment state is compared with the estimation of the current environment state provided that the agent had chosen another action. The difference between each agent's reward, as the outcome of its action, with that of its fellow, multiplied by the intention of the fellow is then taken as the fellow's "kindness". If the result of each reward-comparison confirms the agent's superiority, it perceives the fellow's kindness and reduces its own reward. Experimental results in the Cleanup and Harvest environments show that training based on the KindMARL method enabled the agents to earn 89\% (resp. 37\%) and 44% (resp. 43\%) more total rewards than training based on the Inequity Aversion and Social Influence methods. The effectiveness of KindMARL is further supported by experiments in a traffic light control problem.

{{</citation>}}


### (103/130) Advancing Post Hoc Case Based Explanation with Feature Highlighting (Eoin Kenny et al., 2023)

{{<citation>}}

Eoin Kenny, Eoin Delaney, Mark Keane. (2023)  
**Advancing Post Hoc Case Based Explanation with Feature Highlighting**  

---
Primary Category: cs.AI  
Categories: I-2-6; F-2, cs-AI, cs-HC, cs-LG, cs.AI  
Keywords: AI, ImageNet  
[Paper Link](http://arxiv.org/abs/2311.03246v1)  

---


**ABSTRACT**  
Explainable AI (XAI) has been proposed as a valuable tool to assist in downstream tasks involving human and AI collaboration. Perhaps the most psychologically valid XAI techniques are case based approaches which display 'whole' exemplars to explain the predictions of black box AI systems. However, for such post hoc XAI methods dealing with images, there has been no attempt to improve their scope by using multiple clear feature 'parts' of the images to explain the predictions while linking back to relevant cases in the training data, thus allowing for more comprehensive explanations that are faithful to the underlying model. Here, we address this gap by proposing two general algorithms (latent and super pixel based) which can isolate multiple clear feature parts in a test image, and then connect them to the explanatory cases found in the training data, before testing their effectiveness in a carefully designed user study. Results demonstrate that the proposed approach appropriately calibrates a users feelings of 'correctness' for ambiguous classifications in real world data on the ImageNet dataset, an effect which does not happen when just showing the explanation without feature highlighting.

{{</citation>}}


### (104/130) Retrieval-Augmented Code Generation for Universal Information Extraction (Yucan Guo et al., 2023)

{{<citation>}}

Yucan Guo, Zixuan Li, Xiaolong Jin, Yantao Liu, Yutao Zeng, Wenxuan Liu, Xiang Li, Pan Yang, Long Bai, Jiafeng Guo, Xueqi Cheng. (2023)  
**Retrieval-Augmented Code Generation for Universal Information Extraction**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-IR, cs.AI  
Keywords: Information Extraction, Language Model  
[Paper Link](http://arxiv.org/abs/2311.02962v1)  

---


**ABSTRACT**  
Information Extraction (IE) aims to extract structural knowledge (e.g., entities, relations, events) from natural language texts, which brings challenges to existing methods due to task-specific schemas and complex text expressions. Code, as a typical kind of formalized language, is capable of describing structural knowledge under various schemas in a universal way. On the other hand, Large Language Models (LLMs) trained on both codes and texts have demonstrated powerful capabilities of transforming texts into codes, which provides a feasible solution to IE tasks. Therefore, in this paper, we propose a universal retrieval-augmented code generation framework based on LLMs, called Code4UIE, for IE tasks. Specifically, Code4UIE adopts Python classes to define task-specific schemas of various structural knowledge in a universal way. By so doing, extracting knowledge under these schemas can be transformed into generating codes that instantiate the predefined Python classes with the information in texts. To generate these codes more precisely, Code4UIE adopts the in-context learning mechanism to instruct LLMs with examples. In order to obtain appropriate examples for different tasks, Code4UIE explores several example retrieval strategies, which can retrieve examples semantically similar to the given texts. Extensive experiments on five representative IE tasks across nine datasets demonstrate the effectiveness of the Code4UIE framework.

{{</citation>}}


### (105/130) Can LLMs Follow Simple Rules? (Norman Mu et al., 2023)

{{<citation>}}

Norman Mu, Sarah Chen, Zifan Wang, Sizhe Chen, David Karamardian, Lulwa Aljeraisy, Dan Hendrycks, David Wagner. (2023)  
**Can LLMs Follow Simple Rules?**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-LG, cs.AI  
Keywords: GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2311.04235v1)  

---


**ABSTRACT**  
As Large Language Models (LLMs) are deployed with increasing real-world responsibilities, it is important to be able to specify and constrain the behavior of these systems in a reliable manner. Model developers may wish to set explicit rules for the model, such as "do not generate abusive content", but these may be circumvented by jailbreaking techniques. Evaluating how well LLMs follow developer-provided rules in the face of adversarial inputs typically requires manual review, which slows down monitoring and methods development. To address this issue, we propose Rule-following Language Evaluation Scenarios (RuLES), a programmatic framework for measuring rule-following ability in LLMs. RuLES consists of 15 simple text scenarios in which the model is instructed to obey a set of rules in natural language while interacting with the human user. Each scenario has a concise evaluation program to determine whether the model has broken any rules in a conversation. Through manual exploration of model behavior in our scenarios, we identify 6 categories of attack strategies and collect two suites of test cases: one consisting of unique conversations from manual testing and one that systematically implements strategies from the 6 categories. Across various popular proprietary and open models such as GPT-4 and Llama 2, we find that all models are susceptible to a wide variety of adversarial hand-crafted user inputs, though GPT-4 is the best-performing model. Additionally, we evaluate open models under gradient-based attacks and find significant vulnerabilities. We propose RuLES as a challenging new setting for research into exploring and defending against both manual and automatic attacks on LLMs.

{{</citation>}}


## cs.AR (1)



### (106/130) Leveraging High-Level Synthesis and Large Language Models to Generate, Simulate, and Deploy a Uniform Random Number Generator Hardware Design (James T. Meech, 2023)

{{<citation>}}

James T. Meech. (2023)  
**Leveraging High-Level Synthesis and Large Language Models to Generate, Simulate, and Deploy a Uniform Random Number Generator Hardware Design**  

---
Primary Category: cs.AR  
Categories: cs-AR, cs-LG, cs-PL, cs.AR  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.03489v1)  

---


**ABSTRACT**  
We present a new high-level synthesis methodology for using large language model tools to generate hardware designs. The methodology uses exclusively open-source tools excluding the large language model. As a case study, we use our methodology to generate a permuted congruential random number generator design with a wishbone interface. We verify the functionality and quality of the random number generator design using large language model-generated simulations and the Dieharder randomness test suite. We document all the large language model chat logs, Python scripts, Verilog scripts, and simulation results used in the case study. We believe that our method of hardware design generation coupled with the open source silicon 130 nm design tools will revolutionize application-specific integrated circuit design. Our methodology significantly lowers the bar to entry when building domain-specific computing accelerators for the Internet of Things and proof of concept prototypes for later fabrication in more modern process nodes.

{{</citation>}}


## cs.IR (2)



### (107/130) Multi-Resolution Diffusion for Privacy-Sensitive Recommender Systems (Derek Lilienthal et al., 2023)

{{<citation>}}

Derek Lilienthal, Paul Mello, Magdalini Eirinaki, Stas Tiomkin. (2023)  
**Multi-Resolution Diffusion for Privacy-Sensitive Recommender Systems**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-CR, cs-IR, cs-LG, cs.IR  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03488v1)  

---


**ABSTRACT**  
While recommender systems have become an integral component of the Web experience, their heavy reliance on user data raises privacy and security concerns. Substituting user data with synthetic data can address these concerns, but accurately replicating these real-world datasets has been a notoriously challenging problem. Recent advancements in generative AI have demonstrated the impressive capabilities of diffusion models in generating realistic data across various domains. In this work we introduce a Score-based Diffusion Recommendation Model (SDRM), which captures the intricate patterns of real-world datasets required for training highly accurate recommender systems. SDRM allows for the generation of synthetic data that can replace existing datasets to preserve user privacy, or augment existing datasets to address excessive data sparsity. Our method outperforms competing baselines such as generative adversarial networks, variational autoencoders, and recently proposed diffusion models in synthesizing various datasets to replace or augment the original data by an average improvement of 4.30% in Recall@$n$ and 4.65% in NDCG@$n$.

{{</citation>}}


### (108/130) Contrastive Multi-Level Graph Neural Networks for Session-based Recommendation (Fuyun Wang et al., 2023)

{{<citation>}}

Fuyun Wang, Xingyu Gao, Zhenyu Chen, Lei Lyu. (2023)  
**Contrastive Multi-Level Graph Neural Networks for Session-based Recommendation**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs.IR  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2311.02938v1)  

---


**ABSTRACT**  
Session-based recommendation (SBR) aims to predict the next item at a certain time point based on anonymous user behavior sequences. Existing methods typically model session representation based on simple item transition information. However, since session-based data consists of limited users' short-term interactions, modeling session representation by capturing fixed item transition information from a single dimension suffers from data sparsity. In this paper, we propose a novel contrastive multi-level graph neural networks (CM-GNN) to better exploit complex and high-order item transition information. Specifically, CM-GNN applies local-level graph convolutional network (L-GCN) and global-level network (G-GCN) on the current session and all the sessions respectively, to effectively capture pairwise relations over all the sessions by aggregation strategy. Meanwhile, CM-GNN applies hyper-level graph convolutional network (H-GCN) to capture high-order information among all the item transitions. CM-GNN further introduces an attention-based fusion module to learn pairwise relation-based session representation by fusing the item representations generated by L-GCN and G-GCN. CM-GNN averages the item representations obtained by H-GCN to obtain high-order relation-based session representation. Moreover, to convert the high-order item transition information into the pairwise relation-based session representation, CM-GNN maximizes the mutual information between the representations derived from the fusion module and the average pool layer by contrastive learning paradigm. We conduct extensive experiments on multiple widely used benchmark datasets to validate the efficacy of the proposed method. The encouraging results demonstrate that our proposed method outperforms the state-of-the-art SBR techniques.

{{</citation>}}


## eess.SY (2)



### (109/130) Repairing Learning-Enabled Controllers While Preserving What Works (Pengyuan Lu et al., 2023)

{{<citation>}}

Pengyuan Lu, Matthew Cleaveland, Oleg Sokolsky, Insup Lee, Ivan Ruchkin. (2023)  
**Repairing Learning-Enabled Controllers While Preserving What Works**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03477v1)  

---


**ABSTRACT**  
Learning-enabled controllers have been adopted in various cyber-physical systems (CPS). When a learning-enabled controller fails to accomplish its task from a set of initial states, researchers leverage repair algorithms to fine-tune the controller's parameters. However, existing repair techniques do not preserve previously correct behaviors. Specifically, when modifying the parameters to repair trajectories from a subset of initial states, another subset may be compromised. Therefore, the repair may break previously correct scenarios, introducing new risks that may not be accounted for. Due to this issue, repairing the entire initial state space may be hard or even infeasible. As a response, we formulate the Repair with Preservation (RwP) problem, which calls for preserving the already-correct scenarios during repair. To tackle this problem, we design the Incremental Simulated Annealing Repair (ISAR) algorithm, which leverages simulated annealing on a barriered energy function to safeguard the already-correct initial states while repairing as many additional ones as possible. Moreover, formal verification is utilized to guarantee the repair results. Case studies on an Unmanned Underwater Vehicle (UUV) and OpenAI Gym Mountain Car (MC) show that ISAR not only preserves correct behaviors from previously verified initial state regions, but also repairs 81.4% and 23.5% of broken state spaces in the two benchmarks. Moreover, the average STL robustnesses of the ISAR repaired controllers are larger than those of the controllers repaired using baseline methods.

{{</citation>}}


### (110/130) Estimating Primary Substation Boundaries and the Value of Mapping the Electrical Network Infrastructure of Great Britain (Joseph Day et al., 2023)

{{<citation>}}

Joseph Day, I. A. Grant Wilson, Daniel L. Donaldson, Edward Barbour, Bruno Cárdenas, Christopher R. Jones, Andrew J. Urquhart, Seamus D. Garvey. (2023)  
**Estimating Primary Substation Boundaries and the Value of Mapping the Electrical Network Infrastructure of Great Britain**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2311.03324v1)  

---


**ABSTRACT**  
Localised data aggregation in many countries including Great Britain (GB) is typically done to a geographical level with polygon boundaries that have a robust and trusted governance system in place. At a minimum this will mean there is confidence in a process to create a set of polygons that have unique identifiers coupled to geographical areas, and the ability to have these updated through a defined code of practice. Examples found across many countries are in the delivery of post, such as postcodes and zip codes, and of the definition of census areas and municipal boundaries. The confidence in these boundaries allows different data to be aggregated by third parties, which itself provides greater levels of data over comparable geographical areas to enhance wider analysis and decision making. Here we combine publicly available datasets published from the six regional electricity Distribution Network Operators of GB to produce a new geospatial dataset with 4436 unique polygons defining the areas served by electrical primary substations. An example is also presented of the use of these polygons to link postcode level open government datasets on domestic energy consumption (2015-2020) from the Department of Energy Security and Net Zero (DESNZ). This results in another dataset with energy statistics aggregated to the geographical areas served by each primary substation across Great Britain. Therefore, we believe there is a compelling argument for countries to set up processes to create and update polygons that have a meaningful relationship to energy systems. This would allow more accurate energy systems analysis to be performed, ultimately leading to an accelerated or potentially lower cost transition to a net-zero world.

{{</citation>}}


## cs.CY (1)



### (111/130) Into the LAIONs Den: Investigating Hate in Multimodal Datasets (Abeba Birhane et al., 2023)

{{<citation>}}

Abeba Birhane, Vinay Prabhu, Sang Han, Vishnu Naresh Boddeti, Alexandra Sasha Luccioni. (2023)  
**Into the LAIONs Den: Investigating Hate in Multimodal Datasets**  

---
Primary Category: cs.CY  
Categories: cs-CY, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03449v1)  

---


**ABSTRACT**  
'Scale the model, scale the data, scale the compute' is the reigning sentiment in the world of generative AI today. While the impact of model scaling has been extensively studied, we are only beginning to scratch the surface of data scaling and its consequences. This is especially of critical importance in the context of vision-language datasets such as LAION. These datasets are continually growing in size and are built based on large-scale internet dumps such as the Common Crawl, which is known to have numerous drawbacks ranging from quality, legality, and content. The datasets then serve as the backbone for large generative models, contributing to the operationalization and perpetuation of harmful societal and historical biases and stereotypes. In this paper, we investigate the effect of scaling datasets on hateful content through a comparative audit of two datasets: LAION-400M and LAION-2B. Our results show that hate content increased by nearly 12% with dataset scale, measured both qualitatively and quantitatively using a metric that we term as Hate Content Rate (HCR). We also found that filtering dataset contents based on Not Safe For Work (NSFW) values calculated based on images alone does not exclude all the harmful content in alt-text. Instead, we found that trace amounts of hateful, targeted, and aggressive text remain even when carrying out conservative filtering. We end with a reflection and a discussion of the significance of our results for dataset curation and usage in the AI community. Code and the meta-data assets curated in this paper are publicly available at https://github.com/vinayprabhu/hate_scaling. Content warning: This paper contains examples of hateful text that might be disturbing, distressing, and/or offensive.

{{</citation>}}


## q-bio.GN (1)



### (112/130) ProPath: Disease-Specific Protein Language Model for Variant Pathogenicity (Huixin Zhan et al., 2023)

{{<citation>}}

Huixin Zhan, Zijun Zhang. (2023)  
**ProPath: Disease-Specific Protein Language Model for Variant Pathogenicity**  

---
Primary Category: q-bio.GN  
Categories: cs-AI, cs-LG, q-bio-GN, q-bio.GN  
Keywords: Clinical, Language Model  
[Paper Link](http://arxiv.org/abs/2311.03429v2)  

---


**ABSTRACT**  
Clinical variant classification of pathogenic versus benign genetic variants remains a pivotal challenge in clinical genetics. Recently, the proposition of protein language models has improved the generic variant effect prediction (VEP) accuracy via weakly-supervised or unsupervised training. However, these VEPs are not disease-specific, limiting their adaptation at point-of-care. To address this problem, we propose a disease-specific \textsc{pro}tein language model for variant \textsc{path}ogenicity, termed ProPath, to capture the pseudo-log-likelihood ratio in rare missense variants through a siamese network. We evaluate the performance of ProPath against pre-trained language models, using clinical variant sets in inherited cardiomyopathies and arrhythmias that were not seen during training. Our results demonstrate that ProPath surpasses the pre-trained ESM1b with an over $5\%$ improvement in AUC across both datasets. Furthermore, our model achieved the highest performances across all baselines for both datasets. Thus, our ProPath offers a potent disease-specific variant effect prediction, particularly valuable for disease associations and clinical applicability.

{{</citation>}}


## eess.IV (3)



### (113/130) FATE: Feature-Agnostic Transformer-based Encoder for learning generalized embedding spaces in flow cytometry data (Lisa Weijler et al., 2023)

{{<citation>}}

Lisa Weijler, Florian Kowarsch, Michael Reiter, Pedro Hermosilla, Margarita Maurer-Granofszky, Michael Dworzak. (2023)  
**FATE: Feature-Agnostic Transformer-based Encoder for learning generalized embedding spaces in flow cytometry data**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2311.03314v1)  

---


**ABSTRACT**  
While model architectures and training strategies have become more generic and flexible with respect to different data modalities over the past years, a persistent limitation lies in the assumption of fixed quantities and arrangements of input features. This limitation becomes particularly relevant in scenarios where the attributes captured during data acquisition vary across different samples. In this work, we aim at effectively leveraging data with varying features, without the need to constrain the input space to the intersection of potential feature sets or to expand it to their union. We propose a novel architecture that can directly process data without the necessity of aligned feature modalities by learning a general embedding space that captures the relationship between features across data samples with varying sets of features. This is achieved via a set-transformer architecture augmented by feature-encoder layers, thereby enabling the learning of a shared latent feature space from data originating from heterogeneous feature spaces. The advantages of the model are demonstrated for automatic cancer cell detection in acute myeloid leukemia in flow cytometry data, where the features measured during acquisition often vary between samples. Our proposed architecture's capacity to operate seamlessly across incongruent feature spaces is particularly relevant in this context, where data scarcity arises from the low prevalence of the disease. The code is available for research purposes at https://github.com/lisaweijler/FATE.

{{</citation>}}


### (114/130) Leveraging Transformers to Improve Breast Cancer Classification and Risk Assessment with Multi-modal and Longitudinal Data (Yiqiu Shen et al., 2023)

{{<citation>}}

Yiqiu Shen, Jungkyu Park, Frank Yeung, Eliana Goldberg, Laura Heacock, Farah Shamout, Krzysztof J. Geras. (2023)  
**Leveraging Transformers to Improve Breast Cancer Classification and Risk Assessment with Multi-modal and Longitudinal Data**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.03217v1)  

---


**ABSTRACT**  
Breast cancer screening, primarily conducted through mammography, is often supplemented with ultrasound for women with dense breast tissue. However, existing deep learning models analyze each modality independently, missing opportunities to integrate information across imaging modalities and time. In this study, we present Multi-modal Transformer (MMT), a neural network that utilizes mammography and ultrasound synergistically, to identify patients who currently have cancer and estimate the risk of future cancer for patients who are currently cancer-free. MMT aggregates multi-modal data through self-attention and tracks temporal tissue changes by comparing current exams to prior imaging. Trained on 1.3 million exams, MMT achieves an AUROC of 0.943 in detecting existing cancers, surpassing strong uni-modal baselines. For 5-year risk prediction, MMT attains an AUROC of 0.826, outperforming prior mammography-based risk models. Our research highlights the value of multi-modal and longitudinal imaging in cancer diagnosis and risk stratification.

{{</citation>}}


### (115/130) NEURO HAND: A weakly supervised Hierarchical Attention Network for neuroimaging abnormality Detection (David A. Wood, 2023)

{{<citation>}}

David A. Wood. (2023)  
**NEURO HAND: A weakly supervised Hierarchical Attention Network for neuroimaging abnormality Detection**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Attention, Clinical  
[Paper Link](http://arxiv.org/abs/2311.02992v1)  

---


**ABSTRACT**  
Clinical neuroimaging data is naturally hierarchical. Different magnetic resonance imaging (MRI) sequences within a series, different slices covering the head, and different regions within each slice all confer different information. In this work we present a hierarchical attention network for abnormality detection using MRI scans obtained in a clinical hospital setting. The proposed network is suitable for non-volumetric data (i.e. stacks of high-resolution MRI slices), and can be trained from binary examination-level labels. We show that this hierarchical approach leads to improved classification, while providing interpretability through either coarse inter- and intra-slice abnormality localisation, or giving importance scores for different slices and sequences, making our model suitable for use as an automated triaging system in radiology departments.

{{</citation>}}


## quant-ph (2)



### (116/130) Indirect Quantum Approximate Optimization Algorithms: application to the TSP (Eric Bourreau et al., 2023)

{{<citation>}}

Eric Bourreau, Gerard Fleury, Philippe Lacomme. (2023)  
**Indirect Quantum Approximate Optimization Algorithms: application to the TSP**  

---
Primary Category: quant-ph  
Categories: cs-DM, quant-ph, quant-ph  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2311.03294v1)  

---


**ABSTRACT**  
We propose an Indirect Quantum Approximate Optimization Algorithm (referred to as IQAOA) where the Quantum Alternating Operator Ansatz takes into consideration a general parameterized family of unitary operators to efficiently model the Hamiltonian describing the set of string vectors. This algorithm creates an efficient alternative to QAOA, where: 1) a Quantum parametrized circuit executed on a quantum machine models the set of string vectors; 2) a Classical meta-optimization loop executed on a classical machine; 3) an estimation of the average cost of each string vector computing, using a well know algorithm coming from the OR community that is problem dependent. The indirect encoding defined by dimensional string vector is mapped into a solution by an efficient coding/decoding mechanism. The main advantage is to obtain a quantum circuit with a strongly limited number of gates that could be executed on the noisy current quantum machines. The numerical experiments achieved with IQAOA permits to solve 8-customer instances TSP using the IBM simulator which are to the best of our knowledge the largest TSP ever solved using a QAOA based approach.

{{</citation>}}


### (117/130) Hacking Cryptographic Protocols with Advanced Variational Quantum Attacks (Borja Aizpurua et al., 2023)

{{<citation>}}

Borja Aizpurua, Pablo Bermejo, Josu Etxezarreta Martinez, Roman Orus. (2023)  
**Hacking Cryptographic Protocols with Advanced Variational Quantum Attacks**  

---
Primary Category: quant-ph  
Categories: cs-CR, cs-LG, quant-ph, quant-ph  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2311.02986v1)  

---


**ABSTRACT**  
Here we introduce an improved approach to Variational Quantum Attack Algorithms (VQAA) on crytographic protocols. Our methods provide robust quantum attacks to well-known cryptographic algorithms, more efficiently and with remarkably fewer qubits than previous approaches. We implement simulations of our attacks for symmetric-key protocols such as S-DES, S-AES and Blowfish. For instance, we show how our attack allows a classical simulation of a small 8-qubit quantum computer to find the secret key of one 32-bit Blowfish instance with 24 times fewer number of iterations than a brute-force attack. Our work also shows improvements in attack success rates for lightweight ciphers such as S-DES and S-AES. Further applications beyond symmetric-key cryptography are also discussed, including asymmetric-key protocols and hash functions. In addition, we also comment on potential future improvements of our methods. Our results bring one step closer assessing the vulnerability of large-size classical cryptographic protocols with Noisy Intermediate-Scale Quantum (NISQ) devices, and set the stage for future research in quantum cybersecurity.

{{</citation>}}


## cs.RO (6)



### (118/130) Segmentation of Drone Collision Hazards in Airborne RADAR Point Clouds Using PointNet (Hector Arroyo et al., 2023)

{{<citation>}}

Hector Arroyo, Paul Kier, Dylan Angus, Santiago Matalonga, Svetlozar Georgiev, Mehdi Goli, Gerard Dooly, James Riordan. (2023)  
**Segmentation of Drone Collision Hazards in Airborne RADAR Point Clouds Using PointNet**  

---
Primary Category: cs.RO  
Categories: cs-CV, cs-RO, cs.RO  
Keywords: Drone  
[Paper Link](http://arxiv.org/abs/2311.03221v1)  

---


**ABSTRACT**  
The integration of unmanned aerial vehicles (UAVs) into shared airspace for beyond visual line of sight (BVLOS) operations presents significant challenges but holds transformative potential for sectors like transportation, construction, energy and defense. A critical prerequisite for this integration is equipping UAVs with enhanced situational awareness to ensure safe operations. Current approaches mainly target single object detection or classification, or simpler sensing outputs that offer limited perceptual understanding and lack the rapid end-to-end processing needed to convert sensor data into safety-critical insights. In contrast, our study leverages radar technology for novel end-to-end semantic segmentation of aerial point clouds to simultaneously identify multiple collision hazards. By adapting and optimizing the PointNet architecture and integrating aerial domain insights, our framework distinguishes five distinct classes: mobile drones (DJI M300 and DJI Mini) and airplanes (Ikarus C42), and static returns (ground and infrastructure) which results in enhanced situational awareness for UAVs. To our knowledge, this is the first approach addressing simultaneous identification of multiple collision threats in an aerial setting, achieving a robust 94% accuracy. This work highlights the potential of radar technology to advance situational awareness in UAVs, facilitating safe and efficient BVLOS operations.

{{</citation>}}


### (119/130) Enabling In-Situ Resources Utilisation by leveraging collaborative robotics and astronaut-robot interaction (Silvia Romero-Azpitarte et al., 2023)

{{<citation>}}

Silvia Romero-Azpitarte, Cristina Luna, Alba Guerra, Mercedes Alonso, Pablo Romeo Manrique, Marina L. Seoane, Daniel Olayo, Almudena Moreno, Pablo Castellanos, Fernando Gandía, Gianfranco Visentin. (2023)  
**Enabling In-Situ Resources Utilisation by leveraging collaborative robotics and astronaut-robot interaction**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03146v1)  

---


**ABSTRACT**  
Space exploration and establishing human presence on other planets demand advanced technology and effective collaboration between robots and astronauts. Efficient space resource utilization is also vital for extraterrestrial settlements. The Collaborative In-Situ Resources Utilisation (CISRU) project has developed a software suite comprising five key modules. The first module manages multi-agent autonomy, facilitating communication between agents and mission control. The second focuses on environment perception, employing AI algorithms for tasks like environment segmentation and object pose estimation. The third module ensures safe navigation, covering obstacle avoidance, social navigation with astronauts, and cooperation among robots. The fourth module addresses manipulation functions, including multi-tool capabilities and tool-changer design for diverse tasks in In-Situ Resources Utilization (ISRU) scenarios. Finally, the fifth module controls cooperative behaviour, incorporating astronaut commands, Mixed Reality interfaces, map fusion, task supervision, and error control. The suite was tested using an astronaut-rover interaction dataset in a planetary environment and GMV SPoT analogue environments. Results demonstrate the advantages of E4 autonomy and AI in space systems, benefiting astronaut-robot collaboration. This paper details CISRU's development, field test preparation, and analysis, highlighting its potential to revolutionize planetary exploration through AI-powered technology.

{{</citation>}}


### (120/130) CISRU: a robotics software suite to enable complex rover-rover and astronaut-rover interaction (Silvia Romero-Azpitarte et al., 2023)

{{<citation>}}

Silvia Romero-Azpitarte, Alba Guerra, Mercedes Alonso, Marina L. Seoane, Daniel Olayo, Almudena Moreno, Pablo Castellanos, Cristina Luna, Gianfranco Visentin. (2023)  
**CISRU: a robotics software suite to enable complex rover-rover and astronaut-rover interaction**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03122v1)  

---


**ABSTRACT**  
The CISRU project has focused on the development of a software suite for planetary (and terrestrial) robotics, fully abstracted from the robotic platform and enabling interaction between rovers and astronauts in complex tasks and non-structured scenarios. To achieve this, a high level of autonomy is required, powered by AI and multi-agent autonomous planning systems inherited from ERGO/ADE and the PERASPERA program. This communication presents the system developed in CISRU, focusing on the modules of AI-based perception and the interaction between astronauts and robots.

{{</citation>}}


### (121/130) Reinforcement Learning for Safety Testing: Lessons from A Mobile Robot Case Study (Tom P. Huck et al., 2023)

{{<citation>}}

Tom P. Huck, Martin Kaiser, Constantin Cronrath, Bengt Lennartson, Torsten Kröger, Tamim Asfour. (2023)  
**Reinforcement Learning for Safety Testing: Lessons from A Mobile Robot Case Study**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.02907v1)  

---


**ABSTRACT**  
Safety-critical robot systems need thorough testing to expose design flaws and software bugs which could endanger humans. Testing in simulation is becoming increasingly popular, as it can be applied early in the development process and does not endanger any real-world operators. However, not all safety-critical flaws become immediately observable in simulation. Some may only become observable under certain critical conditions. If these conditions are not covered, safety flaws may remain undetected. Creating critical tests is therefore crucial. In recent years, there has been a trend towards using Reinforcement Learning (RL) for this purpose. Guided by domain-specific reward functions, RL algorithms are used to learn critical test strategies. This paper presents a case study in which the collision avoidance behavior of a mobile robot is subjected to RL-based testing. The study confirms prior research which shows that RL can be an effective testing tool. However, the study also highlights certain challenges associated with RL-based testing, namely (i) a possible lack of diversity in test conditions and (ii) the phenomenon of reward hacking where the RL agent behaves in undesired ways due to a misalignment of reward and test specification. The challenges are illustrated with data and examples from the experiments, and possible mitigation strategies are discussed.

{{</citation>}}


### (122/130) IR-STP: Enhancing Autonomous Driving with Interaction Reasoning in Spatio-Temporal Planning (Yingbing Chen et al., 2023)

{{<citation>}}

Yingbing Chen, Jie Cheng, Lu Gan, Sheng Wang, Hongji Liu, Xiaodong Mei, Ming Liu. (2023)  
**IR-STP: Enhancing Autonomous Driving with Interaction Reasoning in Spatio-Temporal Planning**  

---
Primary Category: cs.RO  
Categories: 68T40, I-0; J-2, cs-RO, cs.RO  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2311.02850v1)  

---


**ABSTRACT**  
Considerable research efforts have been devoted to the development of motion planning algorithms, which form a cornerstone of the autonomous driving system (ADS). However, obtaining an interactive and secure trajectory for the ADS remains a formidable task, especially in scenarios with significant interaction complexities. Many contemporary prediction-based planning methods frequently overlook interaction modeling, leading to less effective planning performance. This paper introduces a novel prediction-based interactive planning framework that explicitly and mathematically models interactions among traffic entities during the planning process. Our method incorporates interaction reasoning into spatio-temporal (s-t) planning by defining interaction conditions and constraints. Furthermore, it records and continually updates interaction relations for each planned state throughout the forward search. We assess the performance of our approach alongside state-of-the-art methods using a series of experiments conducted in both single and multi-modal scenarios. These experiments encompass variations in the accuracy of prediction outcomes and different degrees of planner aggressiveness. The experimental findings demonstrate the effectiveness and robustness of our method, yielding insights applicable to the wider field of autonomous driving. For the community's reference, our code is accessible at https://github.com/ChenYingbing/IR-STP-Planner.

{{</citation>}}


### (123/130) Kinematic-aware Prompting for Generalizable Articulated Object Manipulation with LLMs (Wenke Xia et al., 2023)

{{<citation>}}

Wenke Xia, Dong Wang, Xincheng Pang, Zhigang Wang, Bin Zhao, Di Hu. (2023)  
**Kinematic-aware Prompting for Generalizable Articulated Object Manipulation with LLMs**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-RO, cs.RO  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.02847v2)  

---


**ABSTRACT**  
Generalizable articulated object manipulation is essential for home-assistant robots. Recent efforts focus on imitation learning from demonstrations or reinforcement learning in simulation, however, due to the prohibitive costs of real-world data collection and precise object simulation, it still remains challenging for these works to achieve broad adaptability across diverse articulated objects. Recently, many works have tried to utilize the strong in-context learning ability of Large Language Models (LLMs) to achieve generalizable robotic manipulation, but most of these researches focus on high-level task planning, sidelining low-level robotic control. In this work, building on the idea that the kinematic structure of the object determines how we can manipulate it, we propose a kinematic-aware prompting framework that prompts LLMs with kinematic knowledge of objects to generate low-level motion trajectory waypoints, supporting various object manipulation. To effectively prompt LLMs with the kinematic structure of different objects, we design a unified kinematic knowledge parser, which represents various articulated objects as a unified textual description containing kinematic joints and contact location. Building upon this unified description, a kinematic-aware planner model is proposed to generate precise 3D manipulation waypoints via a designed kinematic-aware chain-of-thoughts prompting method. Our evaluation spanned 48 instances across 16 distinct categories, revealing that our framework not only outperforms traditional methods on 8 seen categories but also shows a powerful zero-shot capability for 8 unseen articulated object categories. Moreover, the real-world experiments on 7 different object categories prove our framework's adaptability in practical scenarios. Code is released at \href{https://github.com/GeWu-Lab/LLM_articulated_object_manipulation/tree/main}{here}.

{{</citation>}}


## cs.SE (2)



### (124/130) Assessing the Maturity of Model Maintenance Techniques for AIOps Solutions (Yingzhe Lyu et al., 2023)

{{<citation>}}

Yingzhe Lyu, Heng Li, Zhen Ming, Jiang, Ahmed E. Hassan. (2023)  
**Assessing the Maturity of Model Maintenance Techniques for AIOps Solutions**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03213v1)  

---


**ABSTRACT**  
AIOps (Artificial Intelligence for IT Operations) solutions leverage the massive data produced during the operations of large-scale systems and machine learning models to assist software engineers in their system operations. As operation data produced in the field are subject to constant evolution from factors like the changing operational environment and user base, the models in AIOps solutions need to be constantly maintained after deployment. While prior works focus on innovative modeling techniques to improve the performance of AIOps models before releasing them into the field, when and how to maintain AIOps models remain an under-investigated topic. In this work, we performed a case study on three large-scale public operation data to assess different model maintenance approaches regarding their performance, maintenance cost, and stability. We observed that active model maintenance approaches achieve better and more stable performance than a stationary approach. Particularly, applying sophisticated model maintenance approaches (e.g., concept drift detection, time-based ensembles, or online learning approaches) could provide better performance, efficiency, and stability than simply retraining AIOps models periodically. In addition, we observed that, although some maintenance approaches (e.g., time-based ensemble and online learning) can save model training time, they significantly sacrifice model testing time, which could hinder their applications in AIOps solutions where the operation data arrive at high speed and volume and where instant predictions are required. Our findings highlight that practitioners should consider the evolution of operation data and actively maintain AIOps models over time. Our observations can also guide researchers and practitioners to investigate more efficient and effective model maintenance techniques that fit in the context of AIOps.

{{</citation>}}


### (125/130) Generate Complete Logging Statements with an Efficient End-to-End Approach (Xiaoyuan Xie et al., 2023)

{{<citation>}}

Xiaoyuan Xie, Zhipeng Cai, Songqiang Chen, Jifeng Xuan. (2023)  
**Generate Complete Logging Statements with an Efficient End-to-End Approach**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: Seq2Seq  
[Paper Link](http://arxiv.org/abs/2311.02862v1)  

---


**ABSTRACT**  
Logs are significant in modern software systems, aiding in various maintenance tasks. To make better use of these logs, many methods have been proposed to help developers draft suitable logging statements. However, these methods only help developers either locate logging positions or write partial content of logging statements, or cannot efficiently help in generating and inserting complete logging statements. To address their limitations, we introduce a new method to better support the automated end-to-end generation of logging statements. Our end-to-end method consists of two steps, first utilizing token classification to locate where to insert a logging statement, and then employing a Seq2Seq model to generate a complete logging statement with a log level and a log message for that position. We evaluate our proposed method on the previously used benchmark and a self-constructed new benchmark. The experimental results show that our method outperforms the state-of-the-art approach a lot regarding both generation speed and quality.

{{</citation>}}


## cs.NI (1)



### (126/130) 5G-CT: Automated Deployment and Over-the-Air Testing of End-to-End Open Radio Access Networks (Leonardo Bonati et al., 2023)

{{<citation>}}

Leonardo Bonati, Michele Polese, Salvatore D'Oro, Pietro Brach del Prever, Tommaso Melodia. (2023)  
**5G-CT: Automated Deployment and Over-the-Air Testing of End-to-End Open Radio Access Networks**  

---
Primary Category: cs.NI  
Categories: cs-NI, cs.NI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.03206v1)  

---


**ABSTRACT**  
Deploying and testing cellular networks is a complex task due to the multitude of components involved-from the core to the Radio Access Network (RAN) and the User Equipments (UEs) -- all of which require integration and constant monitoring. Interference and the inherent randomness of the wireless channel further complicate the issue, posing additional challenges for repeatable and consistent testing. Consequently, both private and public cellular systems still rely heavily on human intervention for operations such as network reconfiguration, performance monitoring, and conducting end-to-end drive tests. This reliance significantly slows the pace of innovation in cellular systems.   To address these challenges, we introduce 5G-CT, an automation framework based on OpenShift and the GitOps workflow, capable of deploying a softwarized end-to-end 5G and O-RAN-compliant system in a matter of seconds. We have deployed 5G-CT to test the integration and performance of popular open-source cellular stacks, including OpenAirInterface (OAI), and have collected months of over-the-air testing results without the need for human intervention. 5G-CT brings cloud-native Continuous Integration (CI) and Continuous Delivery (CD) to the RAN, effectively addressing the complexities associated with managing spectrum, radios, heterogeneous devices, and distributed components. Moreover, it provides much-needed automation and Continuous Testing (CT) for cellular networks.

{{</citation>}}


## cs.MA (1)



### (127/130) A Brain-inspired Theory of Collective Mind Model for Efficient Social Cooperation (Zhuoya Zhao et al., 2023)

{{<citation>}}

Zhuoya Zhao, Feifei Zhao, Shiwen Wang, Yinqian Sun, Yi Zeng. (2023)  
**A Brain-inspired Theory of Collective Mind Model for Efficient Social Cooperation**  

---
Primary Category: cs.MA  
Categories: cs-MA, cs.MA  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.03150v2)  

---


**ABSTRACT**  
Social intelligence manifests the capability, often referred to as the Theory of Mind (ToM), to discern others' behavioral intentions, beliefs, and other mental states. ToM is especially important in multi-agent and human-machine interaction environments because each agent needs to understand the mental states of other agents in order to better respond, interact, and collaborate. Recent research indicates that the ToM model possesses the capability to infer beliefs, intentions, and anticipate future observations and actions; nonetheless, its deployment in tackling intricate tasks remains notably limited. The challenges arise when the number of agents increases, the environment becomes more complex, and interacting with the environment and predicting the mental state of each other becomes difficult and time consuming. To overcome such limits, we take inspiration from the Theory of Collective Mind (ToCM) mechanism, predicting observations of all other agents into a unified but plural representation and discerning how our own actions affect this mental state representation. Based on this foundation, we construct an imaginative space to simulate the multi-agent interaction process, thus improving the efficiency of cooperation among multiple agents in complex decision-making environments. In various cooperative tasks with different numbers of agents, the experimental results highlight the superior cooperative efficiency and performance of our approach compared to the Multi-Agent Reinforcement Learning (MARL) baselines. We achieve consistent boost on SNN- and DNN-based decision networks, and demonstrate that ToCM's inferences about others' mental states can be transferred to new tasks for quickly and flexible adaptation.

{{</citation>}}


## physics.soc-ph (1)



### (128/130) Phase Field Modeling in Social Media Dynamics:Simulation of Opinion Evolution with Feedback, Separation (Yasuko Kawahata, 2023)

{{<citation>}}

Yasuko Kawahata. (2023)  
**Phase Field Modeling in Social Media Dynamics:Simulation of Opinion Evolution with Feedback, Separation**  

---
Primary Category: physics.soc-ph  
Categories: cs-SI, physics-soc-ph, physics.soc-ph  
Keywords: Social Media  
[Paper Link](http://arxiv.org/abs/2311.03137v1)  

---


**ABSTRACT**  
This study introduces a new numerical model to simulate how information is comprehended and processed on social networks, using continuous "Phase Field Modeling" variables (phiA, phiB, phiC) to represent individual users' opinions. It captures the immediate and two-way nature of social media interactions, reproducing the spread and feedback of information. The model incorporates psychological and social factors like confirmation bias and opinion rigidity to analyze information processing and opinion development among users. It also explores the dynamics of opinion segregation and interaction in and out of filter bubbles, offering a quantitative view of opinion dynamics on platforms like social networking services (SNS). This approach combines theoretical models with real-world social network data to study the effects of information concentration on opinion formation and the phenome Phase Field Modeling of opinion polarization and echo chamber effects on SNS.

{{</citation>}}


## cs.CE (2)



### (129/130) Lightweight equivariant interaction graph neural network for accurate and efficient interatomic potential and force predictions (Ziduo Yang et al., 2023)

{{<citation>}}

Ziduo Yang, Xian Wang, Tiejun Dong, Yifan Li, Qiujie Lv, Calvin Yu-Chian Chen, Lei Shen. (2023)  
**Lightweight equivariant interaction graph neural network for accurate and efficient interatomic potential and force predictions**  

---
Primary Category: cs.CE  
Categories: cs-CE, cs.CE  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2311.02869v1)  

---


**ABSTRACT**  
In modern computational materials science, deep learning has shown the capability to predict interatomic potentials, thereby supporting and accelerating conventional simulations. However, existing models typically sacrifice either accuracy or efficiency. Moreover, lightweight models are highly demanded for offering simulating systems on a considerably larger scale at reduced computational costs. A century ago, Felix Bloch demonstrated how leveraging the equivariance of the translation operation on a crystal lattice (with geometric symmetry) could significantly reduce the computational cost of determining wavefunctions and accurately calculate material properties. Here, we introduce a lightweight equivariant interaction graph neural network (LEIGNN) that can enable accurate and efficient interatomic potential and force predictions in crystals. Rather than relying on higher-order representations, LEIGNN employs a scalar-vector dual representation to encode equivariant features. By extracting both local and global structures from vector representations and learning geometric symmetry information, our model remains lightweight while ensuring prediction accuracy and robustness through the equivariance. Our results show that LEIGNN consistently outperforms the prediction performance of the representative baselines and achieves significant efficiency across diverse datasets, which include catalysts, molecules, and organic isomers. Finally, to further validate the predicted interatomic potentials from our model, we conduct classical molecular dynamics (MD) and ab initio MD simulation across various systems, including solid, liquid, and gas. It is found that LEIGNN can achieve the accuracy of ab initio MD and retain the computational efficiency of classical MD across all examined systems, demonstrating its accuracy, efficiency, and universality.

{{</citation>}}


### (130/130) An Exploration of Multimodality and Data Augmentation for Dementia Classification (Kaiying Lin et al., 2023)

{{<citation>}}

Kaiying Lin, Peter Washington. (2023)  
**An Exploration of Multimodality and Data Augmentation for Dementia Classification**  

---
Primary Category: cs.CE  
Categories: cs-CE, cs.CE  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2311.02819v1)  

---


**ABSTRACT**  
Dementia is a progressive neurological disorder that profoundly affects the daily lives of older adults, impairing abilities such as verbal communication and cognitive function. Early diagnosis is essential for enhancing both lifespan and quality of life for affected individuals. Despite its importance, diagnosing dementia is complex and often necessitates a multimodal approach incorporating diverse clinical data types. In this study, we fine-tune Wav2vec and Word2vec baseline models using two distinct data types: audio recordings and text transcripts. We experiment with four conditions: original datasets versus datasets purged of short sentences, each with and without data augmentation. Our results indicate that synonym-based text data augmentation generally enhances model performance, underscoring the importance of data volume for achieving generalizable performance. Additionally, models trained on text data frequently excel and can further improve the performance of other modalities when combined. Audio and timestamp data sometimes offer marginal improvements. We provide a qualitative error analysis of the sentence archetypes that tend to be misclassified under each condition, providing insights into the effects of altering data modality and augmentation decisions.

{{</citation>}}
