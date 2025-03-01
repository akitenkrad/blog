---
draft: false
title: "arXiv @ 2023.10.03"
date: 2023-10-03
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.10.03"
    identifier: arxiv_20231003
    parent: 202310_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.LG (22)](#cslg-22)
- [cs.CL (21)](#cscl-21)
- [stat.ML (2)](#statml-2)
- [cs.CV (13)](#cscv-13)
- [cs.DB (4)](#csdb-4)
- [cs.SI (1)](#cssi-1)
- [cs.AI (2)](#csai-2)
- [cs.RO (2)](#csro-2)
- [q-fin.PM (1)](#q-finpm-1)
- [cs.CY (2)](#cscy-2)
- [cs.CR (4)](#cscr-4)
- [cs.SD (1)](#cssd-1)
- [cs.SE (1)](#csse-1)
- [cs.NI (1)](#csni-1)
- [eess.AS (1)](#eessas-1)
- [cs.IR (1)](#csir-1)

## cs.LG (22)



### (1/79) Determining the Optimal Number of Clusters for Time Series Datasets with Symbolic Pattern Forest (Md Nishat Raihan, 2023)

{{<citation>}}

Md Nishat Raihan. (2023)  
**Determining the Optimal Number of Clusters for Time Series Datasets with Symbolic Pattern Forest**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2310.00820v1)  

---


**ABSTRACT**  
Clustering algorithms are among the most widely used data mining methods due to their exploratory power and being an initial preprocessing step that paves the way for other techniques. But the problem of calculating the optimal number of clusters (say k) is one of the significant challenges for such methods. The most widely used clustering algorithms like k-means and k-shape in time series data mining also need the ground truth for the number of clusters that need to be generated. In this work, we extended the Symbolic Pattern Forest algorithm, another time series clustering algorithm, to determine the optimal number of clusters for the time series datasets. We used SPF to generate the clusters from the datasets and chose the optimal number of clusters based on the Silhouette Coefficient, a metric used to calculate the goodness of a clustering technique. Silhouette was calculated on both the bag of word vectors and the tf-idf vectors generated from the SAX words of each time series. We tested our approach on the UCR archive datasets, and our experimental results so far showed significant improvement over the baseline.

{{</citation>}}


### (2/79) Sparse Backpropagation for MoE Training (Liyuan Liu et al., 2023)

{{<citation>}}

Liyuan Liu, Jianfeng Gao, Weizhu Chen. (2023)  
**Sparse Backpropagation for MoE Training**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-CV, cs-LG, cs.LG  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2310.00811v1)  

---


**ABSTRACT**  
One defining characteristic of Mixture-of-Expert (MoE) models is their capacity for conducting sparse computation via expert routing, leading to remarkable scalability. However, backpropagation, the cornerstone of deep learning, requires dense computation, thereby posting challenges in MoE gradient computations. Here, we introduce SparseMixer, a scalable gradient estimator that bridges the gap between backpropagation and sparse expert routing. Unlike typical MoE training which strategically neglects certain gradient terms for the sake of sparse computation and scalability, SparseMixer provides scalable gradient approximations for these terms, enabling reliable gradient estimation in MoE training. Grounded in a numerical ODE framework, SparseMixer harnesses the mid-point method, a second-order ODE solver, to deliver precise gradient approximations with negligible computational overhead. Applying SparseMixer to Switch Transformer on both pre-training and machine translation tasks, SparseMixer showcases considerable performance gain, accelerating training convergence up to 2 times.

{{</citation>}}


### (3/79) Towards Causal Foundation Model: on Duality between Causal Inference and Attention (Jiaqi Zhang et al., 2023)

{{<citation>}}

Jiaqi Zhang, Joel Jennings, Cheng Zhang, Chao Ma. (2023)  
**Towards Causal Foundation Model: on Duality between Causal Inference and Attention**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ME, stat-ML  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2310.00809v1)  

---


**ABSTRACT**  
Foundation models have brought changes to the landscape of machine learning, demonstrating sparks of human-level intelligence across a diverse array of tasks. However, a gap persists in complex tasks such as causal inference, primarily due to challenges associated with intricate reasoning steps and high numerical precision requirements. In this work, we take a first step towards building causally-aware foundation models for complex tasks. We propose a novel, theoretically sound method called Causal Inference with Attention (CInA), which utilizes multiple unlabeled datasets to perform self-supervised causal learning, and subsequently enables zero-shot causal inference on unseen tasks with new data. This is based on our theoretical results that demonstrate the primal-dual connection between optimal covariate balancing and self-attention, facilitating zero-shot causal inference through the final layer of a trained transformer-type architecture. We demonstrate empirically that our approach CInA effectively generalizes to out-of-distribution datasets and various real-world datasets, matching or even surpassing traditional per-dataset causal inference methodologies.

{{</citation>}}


### (4/79) GraphPatcher: Mitigating Degree Bias for Graph Neural Networks via Test-time Augmentation (Mingxuan Ju et al., 2023)

{{<citation>}}

Mingxuan Ju, Tong Zhao, Wenhao Yu, Neil Shah, Yanfang Ye. (2023)  
**GraphPatcher: Mitigating Degree Bias for Graph Neural Networks via Test-time Augmentation**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Augmentation, Bias, GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2310.00800v1)  

---


**ABSTRACT**  
Recent studies have shown that graph neural networks (GNNs) exhibit strong biases towards the node degree: they usually perform satisfactorily on high-degree nodes with rich neighbor information but struggle with low-degree nodes. Existing works tackle this problem by deriving either designated GNN architectures or training strategies specifically for low-degree nodes. Though effective, these approaches unintentionally create an artificial out-of-distribution scenario, where models mainly or even only observe low-degree nodes during the training, leading to a downgraded performance for high-degree nodes that GNNs originally perform well at. In light of this, we propose a test-time augmentation framework, namely GraphPatcher, to enhance test-time generalization of any GNNs on low-degree nodes. Specifically, GraphPatcher iteratively generates virtual nodes to patch artificially created low-degree nodes via corruptions, aiming at progressively reconstructing target GNN's predictions over a sequence of increasingly corrupted nodes. Through this scheme, GraphPatcher not only learns how to enhance low-degree nodes (when the neighborhoods are heavily corrupted) but also preserves the original superior performance of GNNs on high-degree nodes (when lightly corrupted). Additionally, GraphPatcher is model-agnostic and can also mitigate the degree bias for either self-supervised or supervised GNNs. Comprehensive experiments are conducted over seven benchmark datasets and GraphPatcher consistently enhances common GNNs' overall performance by up to 3.6% and low-degree performance by up to 6.5%, significantly outperforming state-of-the-art baselines. The source code is publicly available at https://github.com/jumxglhf/GraphPatcher.

{{</citation>}}


### (5/79) Going Beyond Familiar Features for Deep Anomaly Detection (Sarath Sivaprasad et al., 2023)

{{<citation>}}

Sarath Sivaprasad, Mario Fritz. (2023)  
**Going Beyond Familiar Features for Deep Anomaly Detection**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2310.00797v1)  

---


**ABSTRACT**  
Anomaly Detection (AD) is a critical task that involves identifying observations that do not conform to a learned model of normality. Prior work in deep AD is predominantly based on a familiarity hypothesis, where familiar features serve as the reference in a pre-trained embedding space. While this strategy has proven highly successful, it turns out that it causes consistent false negatives when anomalies consist of truly novel features that are not well captured by the pre-trained encoding. We propose a novel approach to AD using explainability to capture novel features as unexplained observations in the input space. We achieve strong performance across a wide range of anomaly benchmarks by combining similarity and novelty in a hybrid approach. Our approach establishes a new state-of-the-art across multiple benchmarks, handling diverse anomaly types while eliminating the need for expensive background models and dense matching. In particular, we show that by taking account of novel features, we reduce false negative anomalies by up to 40% on challenging benchmarks compared to the state-of-the-art. Our method gives visually inspectable explanations for pixel-level anomalies.

{{</citation>}}


### (6/79) A Comprehensive Review of Generative AI in Healthcare (Yasin Shokrollahi et al., 2023)

{{<citation>}}

Yasin Shokrollahi, Sahar Yarmohammadtoosky, Matthew M. Nikahd, Pengfei Dong, Xianqi Li, Linxia Gu. (2023)  
**A Comprehensive Review of Generative AI in Healthcare**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2310.00795v1)  

---


**ABSTRACT**  
The advancement of Artificial Intelligence (AI) has catalyzed revolutionary changes across various sectors, notably in healthcare. Among the significant developments in this field are the applications of generative AI models, specifically transformers and diffusion models. These models have played a crucial role in analyzing diverse forms of data, including medical imaging (encompassing image reconstruction, image-to-image translation, image generation, and image classification), protein structure prediction, clinical documentation, diagnostic assistance, radiology interpretation, clinical decision support, medical coding, and billing, as well as drug design and molecular representation. Such applications have enhanced clinical diagnosis, data reconstruction, and drug synthesis. This review paper aims to offer a thorough overview of the generative AI applications in healthcare, focusing on transformers and diffusion models. Additionally, we propose potential directions for future research to tackle the existing limitations and meet the evolving demands of the healthcare sector. Intended to serve as a comprehensive guide for researchers and practitioners interested in the healthcare applications of generative AI, this review provides valuable insights into the current state of the art, challenges faced, and prospective future directions.

{{</citation>}}


### (7/79) Analyzing and Mitigating Object Hallucination in Large Vision-Language Models (Yiyang Zhou et al., 2023)

{{<citation>}}

Yiyang Zhou, Chenhang Cui, Jaehong Yoon, Linjun Zhang, Zhun Deng, Chelsea Finn, Mohit Bansal, Huaxiu Yao. (2023)  
**Analyzing and Mitigating Object Hallucination in Large Vision-Language Models**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-CV, cs-LG, cs.LG  
Keywords: GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2310.00754v1)  

---


**ABSTRACT**  
Large vision-language models (LVLMs) have shown remarkable abilities in understanding visual information with human languages. However, LVLMs still suffer from object hallucination, which is the problem of generating descriptions that include objects that do not actually exist in the images. This can negatively impact many vision-language tasks, such as visual summarization and reasoning. To address this issue, we propose a simple yet powerful algorithm, LVLM Hallucination Revisor (LURE), to post-hoc rectify object hallucination in LVLMs by reconstructing less hallucinatory descriptions. LURE is grounded in a rigorous statistical analysis of the key factors underlying object hallucination, including co-occurrence (the frequent appearance of certain objects alongside others in images), uncertainty (objects with higher uncertainty during LVLM decoding), and object position (hallucination often appears in the later part of the generated text). LURE can also be seamlessly integrated with any LVLMs. We evaluate LURE on six open-source LVLMs, achieving a 23% improvement in general object hallucination evaluation metrics over the previous best approach. In both GPT and human evaluations, LURE consistently ranks at the top. Our data and code are available at https://github.com/YiyangZhou/LURE.

{{</citation>}}


### (8/79) Physics-Informed Graph Neural Network for Dynamic Reconfiguration of Power Systems (Jules Authier et al., 2023)

{{<citation>}}

Jules Authier, Rabab Haider, Anuradha Annaswamy, Florian Dorfler. (2023)  
**Physics-Informed Graph Neural Network for Dynamic Reconfiguration of Power Systems**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-SY, cs.LG, eess-SY, math-OC, stat-ML  
Keywords: GNN, Graph Neural Network  
[Paper Link](http://arxiv.org/abs/2310.00728v1)  

---


**ABSTRACT**  
To maintain a reliable grid we need fast decision-making algorithms for complex problems like Dynamic Reconfiguration (DyR). DyR optimizes distribution grid switch settings in real-time to minimize grid losses and dispatches resources to supply loads with available generation. DyR is a mixed-integer problem and can be computationally intractable to solve for large grids and at fast timescales. We propose GraPhyR, a Physics-Informed Graph Neural Network (GNNs) framework tailored for DyR. We incorporate essential operational and connectivity constraints directly within the GNN framework and train it end-to-end. Our results show that GraPhyR is able to learn to optimize the DyR task.

{{</citation>}}


### (9/79) Improving Length-Generalization in Transformers via Task Hinting (Pranjal Awasthi et al., 2023)

{{<citation>}}

Pranjal Awasthi, Anupam Gupta. (2023)  
**Improving Length-Generalization in Transformers via Task Hinting**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ML  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2310.00726v1)  

---


**ABSTRACT**  
It has been observed in recent years that transformers have problems with length generalization for certain types of reasoning and arithmetic tasks. In particular, the performance of a transformer model trained on tasks (say addition) up to a certain length (e.g., 5 digit numbers) drops sharply when applied to longer instances of the same problem. This work proposes an approach based on task hinting towards addressing length generalization. Our key idea is that while training the model on task-specific data, it is helpful to simultaneously train the model to solve a simpler but related auxiliary task as well.   We study the classical sorting problem as a canonical example to evaluate our approach. We design a multitask training framework and show that task hinting significantly improve length generalization. For sorting we show that it is possible to train models on data consisting of sequences having length at most $20$, and improve the test accuracy on sequences of length $100$ from less than 1% (for standard training) to more than 92% (via task hinting).   Our study uncovers several interesting aspects of length generalization. We observe that while several auxiliary tasks may seem natural a priori, their effectiveness in improving length generalization differs dramatically. We further use probing and visualization-based techniques to understand the internal mechanisms via which the model performs the task, and propose a theoretical construction consistent with the observed learning behaviors of the model. Based on our construction, we show that introducing a small number of length dependent parameters into the training procedure can further boost the performance on unseen lengths. Finally, we also show the efficacy of our task hinting based approach beyond sorting, giving hope that these techniques will be applicable in broader contexts.

{{</citation>}}


### (10/79) Learning How to Propagate Messages in Graph Neural Networks (Teng Xiao et al., 2023)

{{<citation>}}

Teng Xiao, Zhengyu Chen, Donglin Wang, Suhang Wang. (2023)  
**Learning How to Propagate Messages in Graph Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2310.00697v1)  

---


**ABSTRACT**  
This paper studies the problem of learning message propagation strategies for graph neural networks (GNNs). One of the challenges for graph neural networks is that of defining the propagation strategy. For instance, the choices of propagation steps are often specialized to a single graph and are not personalized to different nodes. To compensate for this, in this paper, we present learning to propagate, a general learning framework that not only learns the GNN parameters for prediction but more importantly, can explicitly learn the interpretable and personalized propagate strategies for different nodes and various types of graphs. We introduce the optimal propagation steps as latent variables to help find the maximum-likelihood estimation of the GNN parameters in a variational Expectation-Maximization (VEM) framework. Extensive experiments on various types of graph benchmarks demonstrate that our proposed framework can significantly achieve better performance compared with the state-of-the-art methods, and can effectively learn personalized and interpretable propagate strategies of messages in GNNs.

{{</citation>}}


### (11/79) A General Offline Reinforcement Learning Framework for Interactive Recommendation (Teng Xiao et al., 2023)

{{<citation>}}

Teng Xiao, Donglin Wang. (2023)  
**A General Offline Reinforcement Learning Framework for Interactive Recommendation**  

---
Primary Category: cs.LG  
Categories: cs-IR, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.00678v1)  

---


**ABSTRACT**  
This paper studies the problem of learning interactive recommender systems from logged feedbacks without any exploration in online environments. We address the problem by proposing a general offline reinforcement learning framework for recommendation, which enables maximizing cumulative user rewards without online exploration. Specifically, we first introduce a probabilistic generative model for interactive recommendation, and then propose an effective inference algorithm for discrete and stochastic policy learning based on logged feedbacks. In order to perform offline learning more effectively, we propose five approaches to minimize the distribution mismatch between the logging policy and recommendation policy: support constraints, supervised regularization, policy constraints, dual constraints and reward extrapolation. We conduct extensive experiments on two public real-world datasets, demonstrating that the proposed methods can achieve superior performance over existing supervised learning and reinforcement learning methods for recommendation.

{{</citation>}}


### (12/79) Learning Type Inference for Enhanced Dataflow Analysis (Lukas Seidel et al., 2023)

{{<citation>}}

Lukas Seidel, Sedick David Baker Effendi, Xavier Pinho, Konrad Rieck, Brink van der Merwe, Fabian Yamaguchi. (2023)  
**Learning Type Inference for Enhanced Dataflow Analysis**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs.LG  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2310.00673v2)  

---


**ABSTRACT**  
Statically analyzing dynamically-typed code is a challenging endeavor, as even seemingly trivial tasks such as determining the targets of procedure calls are non-trivial without knowing the types of objects at compile time. Addressing this challenge, gradual typing is increasingly added to dynamically-typed languages, a prominent example being TypeScript that introduces static typing to JavaScript. Gradual typing improves the developer's ability to verify program behavior, contributing to robust, secure and debuggable programs. In practice, however, users only sparsely annotate types directly. At the same time, conventional type inference faces performance-related challenges as program size grows. Statistical techniques based on machine learning offer faster inference, but although recent approaches demonstrate overall improved accuracy, they still perform significantly worse on user-defined types than on the most common built-in types. Limiting their real-world usefulness even more, they rarely integrate with user-facing applications. We propose CodeTIDAL5, a Transformer-based model trained to reliably predict type annotations. For effective result retrieval and re-integration, we extract usage slices from a program's code property graph. Comparing our approach against recent neural type inference systems, our model outperforms the current state-of-the-art by 7.85% on the ManyTypes4TypeScript benchmark, achieving 71.27% accuracy overall. Furthermore, we present JoernTI, an integration of our approach into Joern, an open source static analysis tool, and demonstrate that the analysis benefits from the additional type information. As our model allows for fast inference times even on commodity CPUs, making our system available through Joern leads to high accessibility and facilitates security research.

{{</citation>}}


### (13/79) PatchMixer: A Patch-Mixing Architecture for Long-Term Time Series Forecasting (Zeying Gong et al., 2023)

{{<citation>}}

Zeying Gong, Yujin Tang, Junwei Liang. (2023)  
**PatchMixer: A Patch-Mixing Architecture for Long-Term Time Series Forecasting**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2310.00655v1)  

---


**ABSTRACT**  
Although the Transformer has been the dominant architecture for time series forecasting tasks in recent years, a fundamental challenge remains: the permutation-invariant self-attention mechanism within Transformers leads to a loss of temporal information. To tackle these challenges, we propose PatchMixer, a novel CNN-based model. It introduces a permutation-variant convolutional structure to preserve temporal information. Diverging from conventional CNNs in this field, which often employ multiple scales or numerous branches, our method relies exclusively on depthwise separable convolutions. This allows us to extract both local features and global correlations using a single-scale architecture. Furthermore, we employ dual forecasting heads that encompass both linear and nonlinear components to better model future curve trends and details. Our experimental results on seven time-series forecasting benchmarks indicate that compared with the state-of-the-art method and the best-performing CNN, PatchMixer yields $3.9\%$ and $21.2\%$ relative improvements, respectively, while being 2-3x faster than the most advanced method. We will release our code and model.

{{</citation>}}


### (14/79) WASA: WAtermark-based Source Attribution for Large Language Model-Generated Data (Jingtan Wang et al., 2023)

{{<citation>}}

Jingtan Wang, Xinyang Lu, Zitong Zhao, Zhongxiang Dai, Chuan-Sheng Foo, See-Kiong Ng, Bryan Kian Hsiang Low. (2023)  
**WASA: WAtermark-based Source Attribution for Large Language Model-Generated Data**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ML  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.00646v1)  

---


**ABSTRACT**  
The impressive performances of large language models (LLMs) and their immense potential for commercialization have given rise to serious concerns over the intellectual property (IP) of their training data. In particular, the synthetic texts generated by LLMs may infringe the IP of the data being used to train the LLMs. To this end, it is imperative to be able to (a) identify the data provider who contributed to the generation of a synthetic text by an LLM (source attribution) and (b) verify whether the text data from a data provider has been used to train an LLM (data provenance). In this paper, we show that both problems can be solved by watermarking, i.e., by enabling an LLM to generate synthetic texts with embedded watermarks that contain information about their source(s). We identify the key properties of such watermarking frameworks (e.g., source attribution accuracy, robustness against adversaries), and propose a WAtermarking for Source Attribution (WASA) framework that satisfies these key properties due to our algorithmic designs. Our WASA framework enables an LLM to learn an accurate mapping from the texts of different data providers to their corresponding unique watermarks, which sets the foundation for effective source attribution (and hence data provenance). Extensive empirical evaluations show that our WASA framework achieves effective source attribution and data provenance.

{{</citation>}}


### (15/79) From Bandits Model to Deep Deterministic Policy Gradient, Reinforcement Learning with Contextual Information (Zhendong Shi et al., 2023)

{{<citation>}}

Zhendong Shi, Xiaoli Wei, Ercan E. Kuruoglu. (2023)  
**From Bandits Model to Deep Deterministic Policy Gradient, Reinforcement Learning with Contextual Information**  

---
Primary Category: cs.LG  
Categories: 93A16, I-2-11; G-3, cs-AI, cs-LG, cs-MA, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.00642v1)  

---


**ABSTRACT**  
The problem of how to take the right actions to make profits in sequential process continues to be difficult due to the quick dynamics and a significant amount of uncertainty in many application scenarios. In such complicated environments, reinforcement learning (RL), a reward-oriented strategy for optimum control, has emerged as a potential technique to address this strategic decision-making issue. However, reinforcement learning also has some shortcomings that make it unsuitable for solving many financial problems, excessive resource consumption, and inability to quickly obtain optimal solutions, making it unsuitable for quantitative trading markets. In this study, we use two methods to overcome the issue with contextual information: contextual Thompson sampling and reinforcement learning under supervision which can accelerate the iterations in search of the best answer. In order to investigate strategic trading in quantitative markets, we merged the earlier financial trading strategy known as constant proportion portfolio insurance (CPPI) into deep deterministic policy gradient (DDPG). The experimental results show that both methods can accelerate the progress of reinforcement learning to obtain the optimal solution.

{{</citation>}}


### (16/79) A Survey of Robustness and Safety of 2D and 3D Deep Learning Models Against Adversarial Attacks (Yanjie Li et al., 2023)

{{<citation>}}

Yanjie Li, Bin Xie, Songtao Guo, Yuanyuan Yang, Bin Xiao. (2023)  
**A Survey of Robustness and Safety of 2D and 3D Deep Learning Models Against Adversarial Attacks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI, Adversarial Attack  
[Paper Link](http://arxiv.org/abs/2310.00633v1)  

---


**ABSTRACT**  
Benefiting from the rapid development of deep learning, 2D and 3D computer vision applications are deployed in many safe-critical systems, such as autopilot and identity authentication. However, deep learning models are not trustworthy enough because of their limited robustness against adversarial attacks. The physically realizable adversarial attacks further pose fatal threats to the application and human safety. Lots of papers have emerged to investigate the robustness and safety of deep learning models against adversarial attacks. To lead to trustworthy AI, we first construct a general threat model from different perspectives and then comprehensively review the latest progress of both 2D and 3D adversarial attacks. We extend the concept of adversarial examples beyond imperceptive perturbations and collate over 170 papers to give an overview of deep learning model robustness against various adversarial attacks. To the best of our knowledge, we are the first to systematically investigate adversarial attacks for 3D models, a flourishing field applied to many real-world applications. In addition, we examine physical adversarial attacks that lead to safety violations. Last but not least, we summarize present popular topics, give insights on challenges, and shed light on future research on trustworthy AI.

{{</citation>}}


### (17/79) On the Onset of Robust Overfitting in Adversarial Training (Chaojian Yu et al., 2023)

{{<citation>}}

Chaojian Yu, Xiaolong Shi, Jun Yu, Bo Han, Tongliang Liu. (2023)  
**On the Onset of Robust Overfitting in Adversarial Training**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Adversarial Training  
[Paper Link](http://arxiv.org/abs/2310.00607v1)  

---


**ABSTRACT**  
Adversarial Training (AT) is a widely-used algorithm for building robust neural networks, but it suffers from the issue of robust overfitting, the fundamental mechanism of which remains unclear. In this work, we consider normal data and adversarial perturbation as separate factors, and identify that the underlying causes of robust overfitting stem from the normal data through factor ablation in AT. Furthermore, we explain the onset of robust overfitting as a result of the model learning features that lack robust generalization, which we refer to as non-effective features. Specifically, we provide a detailed analysis of the generation of non-effective features and how they lead to robust overfitting. Additionally, we explain various empirical behaviors observed in robust overfitting and revisit different techniques to mitigate robust overfitting from the perspective of non-effective features, providing a comprehensive understanding of the robust overfitting phenomenon. This understanding inspires us to propose two measures, attack strength and data augmentation, to hinder the learning of non-effective features by the neural network, thereby alleviating robust overfitting. Extensive experiments conducted on benchmark datasets demonstrate the effectiveness of the proposed methods in mitigating robust overfitting and enhancing adversarial robustness.

{{</citation>}}


### (18/79) Consistency Trajectory Models: Learning Probability Flow ODE Trajectory of Diffusion (Dongjun Kim et al., 2023)

{{<citation>}}

Dongjun Kim, Chieh-Hsin Lai, Wei-Hsiang Liao, Naoki Murata, Yuhta Takida, Toshimitsu Uesaka, Yutong He, Yuki Mitsufuji, Stefano Ermon. (2023)  
**Consistency Trajectory Models: Learning Probability Flow ODE Trajectory of Diffusion**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs.LG, stat-ML  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2310.02279v1)  

---


**ABSTRACT**  
Consistency Models (CM) (Song et al., 2023) accelerate score-based diffusion model sampling at the cost of sample quality but lack a natural way to trade-off quality for speed. To address this limitation, we propose Consistency Trajectory Model (CTM), a generalization encompassing CM and score-based models as special cases. CTM trains a single neural network that can -- in a single forward pass -- output scores (i.e., gradients of log-density) and enables unrestricted traversal between any initial and final time along the Probability Flow Ordinary Differential Equation (ODE) in a diffusion process. CTM enables the efficient combination of adversarial training and denoising score matching loss to enhance performance and achieves new state-of-the-art FIDs for single-step diffusion model sampling on CIFAR-10 (FID 1.73) and ImageNet at 64X64 resolution (FID 2.06). CTM also enables a new family of sampling schemes, both deterministic and stochastic, involving long jumps along the ODE solution trajectories. It consistently improves sample quality as computational budgets increase, avoiding the degradation seen in CM. Furthermore, CTM's access to the score accommodates all diffusion model inference techniques, including exact likelihood computation.

{{</citation>}}


### (19/79) Understanding the Robustness of Randomized Feature Defense Against Query-Based Adversarial Attacks (Quang H. Nguyen et al., 2023)

{{<citation>}}

Quang H. Nguyen, Yingjie Lao, Tung Pham, Kok-Seng Wong, Khoa D. Doan. (2023)  
**Understanding the Robustness of Randomized Feature Defense Against Query-Based Adversarial Attacks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs.LG  
Keywords: Adversarial Attack  
[Paper Link](http://arxiv.org/abs/2310.00567v1)  

---


**ABSTRACT**  
Recent works have shown that deep neural networks are vulnerable to adversarial examples that find samples close to the original image but can make the model misclassify. Even with access only to the model's output, an attacker can employ black-box attacks to generate such adversarial examples. In this work, we propose a simple and lightweight defense against black-box attacks by adding random noise to hidden features at intermediate layers of the model at inference time. Our theoretical analysis confirms that this method effectively enhances the model's resilience against both score-based and decision-based black-box attacks. Importantly, our defense does not necessitate adversarial training and has minimal impact on accuracy, rendering it applicable to any pre-trained model. Our analysis also reveals the significance of selectively adding noise to different parts of the model based on the gradient of the adversarial objective function, which can be varied during the attack. We demonstrate the robustness of our defense against multiple black-box attacks through extensive empirical experiments involving diverse models with various architectures.

{{</citation>}}


### (20/79) Empowering Many, Biasing a Few: Generalist Credit Scoring through Large Language Models (Duanyu Feng et al., 2023)

{{<citation>}}

Duanyu Feng, Yongfu Dai, Jimin Huang, Yifang Zhang, Qianqian Xie, Weiguang Han, Alejandro Lopez-Lira, Hao Wang. (2023)  
**Empowering Many, Biasing a Few: Generalist Credit Scoring through Large Language Models**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-CY, cs-LG, cs.LG  
Keywords: Bias, Language Model  
[Paper Link](http://arxiv.org/abs/2310.00566v1)  

---


**ABSTRACT**  
Credit and risk assessments are cornerstones of the financial landscape, impacting both individual futures and broader societal constructs. Existing credit scoring models often exhibit limitations stemming from knowledge myopia and task isolation. In response, we formulate three hypotheses and undertake an extensive case study to investigate LLMs' viability in credit assessment. Our empirical investigations unveil LLMs' ability to overcome the limitations inherent in conventional models. We introduce a novel benchmark curated for credit assessment purposes, fine-tune a specialized Credit and Risk Assessment Large Language Model (CALM), and rigorously examine the biases that LLMs may harbor. Our findings underscore LLMs' potential in revolutionizing credit assessment, showcasing their adaptability across diverse financial evaluations, and emphasizing the critical importance of impartial decision-making in the financial sector. Our datasets, models, and benchmarks are open-sourced for other researchers.

{{</citation>}}


### (21/79) JoMA: Demystifying Multilayer Transformers via JOint Dynamics of MLP and Attention (Yuandong Tian et al., 2023)

{{<citation>}}

Yuandong Tian, Yiping Wang, Zhenyu Zhang, Beidi Chen, Simon Du. (2023)  
**JoMA: Demystifying Multilayer Transformers via JOint Dynamics of MLP and Attention**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: Attention, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2310.00535v2)  

---


**ABSTRACT**  
We propose Joint MLP/Attention (JoMA) dynamics, a novel mathematical framework to understand the training procedure of multilayer Transformer architectures. This is achieved by integrating out the self-attention layer in Transformers, producing a modified dynamics of MLP layers only. JoMA removes unrealistic assumptions in previous analysis (e.g., lack of residual connection) and predicts that the attention first becomes sparse (to learn salient tokens), then dense (to learn less salient tokens) in the presence of nonlinear activations, while in the linear case, it is consistent with existing works that show attention becomes sparse over time. We leverage JoMA to qualitatively explains how tokens are combined to form hierarchies in multilayer Transformers, when the input tokens are generated by a latent hierarchical generative model. Experiments on models trained from real-world dataset (Wikitext2/Wikitext103) and various pre-trained models (OPT, Pythia) verify our theoretical findings.

{{</citation>}}


### (22/79) Are Graph Neural Networks Optimal Approximation Algorithms? (Morris Yau et al., 2023)

{{<citation>}}

Morris Yau, Eric Lu, Nikolaos Karalias, Jessica Xu, Stefanie Jegelka. (2023)  
**Are Graph Neural Networks Optimal Approximation Algorithms?**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-DM, cs-DS, cs-LG, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2310.00526v2)  

---


**ABSTRACT**  
In this work we design graph neural network architectures that can be used to obtain optimal approximation algorithms for a large class of combinatorial optimization problems using powerful algorithmic tools from semidefinite programming (SDP). Concretely, we prove that polynomial-sized message passing algorithms can represent the most powerful polynomial time algorithms for Max Constraint Satisfaction Problems assuming the Unique Games Conjecture. We leverage this result to construct efficient graph neural network architectures, OptGNN, that obtain high-quality approximate solutions on landmark combinatorial optimization problems such as Max Cut and maximum independent set. Our approach achieves strong empirical results across a wide range of real-world and synthetic datasets against both neural baselines and classical algorithms. Finally, we take advantage of OptGNN's ability to capture convex relaxations to design an algorithm for producing dual certificates of optimality (bounds on the optimal solution) from the learned embeddings of OptGNN.

{{</citation>}}


## cs.CL (21)



### (23/79) Parameter-Efficient Tuning Helps Language Model Alignment (Tianci Xue et al., 2023)

{{<citation>}}

Tianci Xue, Ziqi Wang, Heng Ji. (2023)  
**Parameter-Efficient Tuning Helps Language Model Alignment**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.00819v1)  

---


**ABSTRACT**  
Aligning large language models (LLMs) with human preferences is essential for safe and useful LLMs. Previous works mainly adopt reinforcement learning (RLHF) and direct preference optimization (DPO) with human feedback for alignment. Nevertheless, they have certain drawbacks. One such limitation is that they can only align models with one preference at the training time (e.g., they cannot learn to generate concise responses when the preference data prefers detailed responses), or have certain constraints for the data format (e.g., DPO only supports pairwise preference data). To this end, prior works incorporate controllable generations for alignment to make language models learn multiple preferences and provide outputs with different preferences during inference if asked. Controllable generation also offers more flexibility with regard to data format (e.g., it supports pointwise preference data). Specifically, it uses different control tokens for different preferences during training and inference, making LLMs behave differently when required. Current controllable generation methods either use a special token or hand-crafted prompts as control tokens, and optimize them together with LLMs. As control tokens are typically much lighter than LLMs, this optimization strategy may not effectively optimize control tokens. To this end, we first use parameter-efficient tuning (e.g., prompting tuning and low-rank adaptation) to optimize control tokens and then fine-tune models for controllable generations, similar to prior works. Our approach, alignMEnt with parameter-Efficient Tuning (MEET), improves the quality of control tokens, thus improving controllable generation quality consistently by an apparent margin on two well-recognized datasets compared with prior works.

{{</citation>}}


### (24/79) Injecting a Structural Inductive Bias into a Seq2Seq Model by Simulation (Matthias Lindemann et al., 2023)

{{<citation>}}

Matthias Lindemann, Alexander Koller, Ivan Titov. (2023)  
**Injecting a Structural Inductive Bias into a Seq2Seq Model by Simulation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Bias, NLP, Seq2Seq, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2310.00796v1)  

---


**ABSTRACT**  
Strong inductive biases enable learning from little data and help generalization outside of the training distribution. Popular neural architectures such as Transformers lack strong structural inductive biases for seq2seq NLP tasks on their own. Consequently, they struggle with systematic generalization beyond the training distribution, e.g. with extrapolating to longer inputs, even when pre-trained on large amounts of text. We show how a structural inductive bias can be injected into a seq2seq model by pre-training it to simulate structural transformations on synthetic data. Specifically, we inject an inductive bias towards Finite State Transducers (FSTs) into a Transformer by pre-training it to simulate FSTs given their descriptions. Our experiments show that our method imparts the desired inductive bias, resulting in improved systematic generalization and better few-shot learning for FST-like tasks.

{{</citation>}}


### (25/79) Testing the Limits of Unified Sequence to Sequence LLM Pretraining on Diverse Table Data Tasks (Soumajyoti Sarkar et al., 2023)

{{<citation>}}

Soumajyoti Sarkar, Leonard Lausen. (2023)  
**Testing the Limits of Unified Sequence to Sequence LLM Pretraining on Diverse Table Data Tasks**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: QA, T5  
[Paper Link](http://arxiv.org/abs/2310.00789v1)  

---


**ABSTRACT**  
Tables stored in databases and tables which are present in web pages and articles account for a large part of semi-structured data that is available on the internet. It then becomes pertinent to develop a modeling approach with large language models (LLMs) that can be used to solve diverse table tasks such as semantic parsing, question answering as well as classification problems. Traditionally, there existed separate models specialized for each task individually. It raises the question of how far can we go to build a unified model that works well on some table tasks without significant degradation on others. To that end, we attempt at creating a shared modeling approach in the pretraining stage with encoder-decoder style LLMs that can cater to diverse tasks. We evaluate our approach that continually pretrains and finetunes different model families of T5 with data from tables and surrounding context, on these downstream tasks at different model scales. Through multiple ablation studies, we observe that our pretraining with self-supervised objectives can significantly boost the performance of the models on these tasks. As an example of one improvement, we observe that the instruction finetuned public models which come specialized on text question answering (QA) and have been trained on table data still have room for improvement when it comes to table specific QA. Our work is the first attempt at studying the advantages of a unified approach to table specific pretraining when scaled from 770M to 11B sequence to sequence models while also comparing the instruction finetuned variants of the models.

{{</citation>}}


### (26/79) BooookScore: A systematic exploration of book-length summarization in the era of LLMs (Yapei Chang et al., 2023)

{{<citation>}}

Yapei Chang, Kyle Lo, Tanya Goyal, Mohit Iyyer. (2023)  
**BooookScore: A systematic exploration of book-length summarization in the era of LLMs**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: GPT, GPT-4, LLaMA  
[Paper Link](http://arxiv.org/abs/2310.00785v1)  

---


**ABSTRACT**  
Summarizing book-length documents (>100K tokens) that exceed the context window size of large language models (LLMs) requires first breaking the input document into smaller chunks and then prompting an LLM to merge, update, and compress chunk-level summaries. Despite the complexity and importance of this task, it has yet to be meaningfully studied due to the challenges of evaluation: existing book-length summarization datasets (e.g., BookSum) are in the pretraining data of most public LLMs, and existing evaluation methods struggle to capture errors made by modern LLM summarizers. In this paper, we present the first study of the coherence of LLM-based book-length summarizers implemented via two prompting workflows: (1) hierarchically merging chunk-level summaries, and (2) incrementally updating a running summary. We obtain 1193 fine-grained human annotations on GPT-4 generated summaries of 100 recently-published books and identify eight common types of coherence errors made by LLMs. Because human evaluation is expensive and time-consuming, we develop an automatic metric, BooookScore, that measures the proportion of sentences in a summary that do not contain any of the identified error types. BooookScore has high agreement with human annotations and allows us to systematically evaluate the impact of many other critical parameters (e.g., chunk size, base LLM) while saving $15K and 500 hours in human evaluation costs. We find that closed-source LLMs such as GPT-4 and Claude 2 produce summaries with higher BooookScore than the oft-repetitive ones generated by LLaMA 2. Incremental updating yields lower BooookScore but higher level of detail than hierarchical merging, a trade-off sometimes preferred by human annotators. We release code and annotations after blind review to spur more principled research on book-length summarization.

{{</citation>}}


### (27/79) TIGERScore: Towards Building Explainable Metric for All Text Generation Tasks (Dongfu Jiang et al., 2023)

{{<citation>}}

Dongfu Jiang, Yishan Li, Ge Zhang, Wenhao Huang, Bill Yuchen Lin, Wenhu Chen. (2023)  
**TIGERScore: Towards Building Explainable Metric for All Text Generation Tasks**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: LLaMA, Text Generation  
[Paper Link](http://arxiv.org/abs/2310.00752v1)  

---


**ABSTRACT**  
We present TIGERScore, a \textbf{T}rained metric that follows \textbf{I}nstruction \textbf{G}uidance to perform \textbf{E}xplainable, and \textbf{R}eference-free evaluation over a wide spectrum of text generation tasks. Different from other automatic evaluation methods that only provide arcane scores, TIGERScore is guided by the natural language instruction to provide error analysis to pinpoint the mistakes in the generated text. Our metric is based on LLaMA, trained on our meticulously curated instruction-tuning dataset MetricInstruct which covers 6 text generation tasks and 23 text generation datasets. The dataset consists of 48K quadruple in the form of (instruction, input, system output $\rightarrow$ error analysis). We collected the `system outputs' through diverse channels to cover different types of errors. To quantitatively assess our metric, we evaluate its correlation with human ratings on 5 held-in datasets, 2 held-out datasets and show that TIGERScore can achieve the highest overall Spearman's correlation with human ratings across these datasets and outperforms other metrics significantly. As a reference-free metric, its correlation can even surpass the best existing reference-based metrics. To further qualitatively assess the rationale generated by our metric, we conduct human evaluation on the generated explanations and found that the explanations are 70.8\% accurate. Through these experimental results, we believe TIGERScore demonstrates the possibility of building universal explainable metrics to evaluate any text generation task.

{{</citation>}}


### (28/79) RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models (Zekun Moore Wang et al., 2023)

{{<citation>}}

Zekun Moore Wang, Zhongyuan Peng, Haoran Que, Jiaheng Liu, Wangchunshu Zhou, Yuhan Wu, Hongcheng Guo, Ruitong Gan, Zehao Ni, Man Zhang, Zhaoxiang Zhang, Wanli Ouyang, Ke Xu, Wenhu Chen, Jie Fu, Junran Peng. (2023)  
**RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GLM, GPT, GPT-4, LLaMA, Language Model  
[Paper Link](http://arxiv.org/abs/2310.00746v1)  

---


**ABSTRACT**  
The advent of Large Language Models (LLMs) has paved the way for complex tasks such as role-playing, which enhances user interactions by enabling models to imitate various characters. However, the closed-source nature of state-of-the-art LLMs and their general-purpose training limit role-playing optimization. In this paper, we introduce RoleLLM, a framework to benchmark, elicit, and enhance role-playing abilities in LLMs. RoleLLM comprises four stages: (1) Role Profile Construction for 100 roles; (2) Context-Based Instruction Generation (Context-Instruct) for role-specific knowledge extraction; (3) Role Prompting using GPT (RoleGPT) for speaking style imitation; and (4) Role-Conditioned Instruction Tuning (RoCIT) for fine-tuning open-source models along with role customization. By Context-Instruct and RoleGPT, we create RoleBench, the first systematic and fine-grained character-level benchmark dataset for role-playing with 168,093 samples. Moreover, RoCIT on RoleBench yields RoleLLaMA (English) and RoleGLM (Chinese), significantly enhancing role-playing abilities and even achieving comparable results with RoleGPT (using GPT-4).

{{</citation>}}


### (29/79) FELM: Benchmarking Factuality Evaluation of Large Language Models (Shiqi Chen et al., 2023)

{{<citation>}}

Shiqi Chen, Yiran Zhao, Jinghan Zhang, I-Chun Chern, Siyang Gao, Pengfei Liu, Junxian He. (2023)  
**FELM: Benchmarking Factuality Evaluation of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.00741v1)  

---


**ABSTRACT**  
Assessing factuality of text generated by large language models (LLMs) is an emerging yet crucial research area, aimed at alerting users to potential errors and guiding the development of more reliable LLMs. Nonetheless, the evaluators assessing factuality necessitate suitable evaluation themselves to gauge progress and foster advancements. This direction remains under-explored, resulting in substantial impediments to the progress of factuality evaluators. To mitigate this issue, we introduce a benchmark for Factuality Evaluation of large Language Models, referred to as felm. In this benchmark, we collect responses generated from LLMs and annotate factuality labels in a fine-grained manner. Contrary to previous studies that primarily concentrate on the factuality of world knowledge (e.g.~information from Wikipedia), felm focuses on factuality across diverse domains, spanning from world knowledge to math and reasoning. Our annotation is based on text segments, which can help pinpoint specific factual errors. The factuality annotations are further supplemented by predefined error types and reference links that either support or contradict the statement. In our experiments, we investigate the performance of several LLM-based factuality evaluators on felm, including both vanilla LLMs and those augmented with retrieval mechanisms and chain-of-thought processes. Our findings reveal that while retrieval aids factuality evaluation, current LLMs are far from satisfactory to faithfully detect factual errors.

{{</citation>}}


### (30/79) Robust Sentiment Analysis for Low Resource languages Using Data Augmentation Approaches: A Case Study in Marathi (Aabha Pingle et al., 2023)

{{<citation>}}

Aabha Pingle, Aditya Vyawahare, Isha Joshi, Rahul Tangsali, Geetanjali Kale, Raviraj Joshi. (2023)  
**Robust Sentiment Analysis for Low Resource languages Using Data Augmentation Approaches: A Case Study in Marathi**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Augmentation, BERT, GPT, NLP, Sentiment Analysis  
[Paper Link](http://arxiv.org/abs/2310.00734v1)  

---


**ABSTRACT**  
Sentiment analysis plays a crucial role in understanding the sentiment expressed in text data. While sentiment analysis research has been extensively conducted in English and other Western languages, there exists a significant gap in research efforts for sentiment analysis in low-resource languages. Limited resources, including datasets and NLP research, hinder the progress in this area. In this work, we present an exhaustive study of data augmentation approaches for the low-resource Indic language Marathi. Although domain-specific datasets for sentiment analysis in Marathi exist, they often fall short when applied to generalized and variable-length inputs. To address this challenge, this research paper proposes four data augmentation techniques for sentiment analysis in Marathi. The paper focuses on augmenting existing datasets to compensate for the lack of sufficient resources. The primary objective is to enhance sentiment analysis model performance in both in-domain and cross-domain scenarios by leveraging data augmentation strategies. The data augmentation approaches proposed showed a significant performance improvement for cross-domain accuracies. The augmentation methods include paraphrasing, back-translation; BERT-based random token replacement, named entity replacement, and pseudo-label generation; GPT-based text and label generation. Furthermore, these techniques can be extended to other low-resource languages and for general text classification tasks.

{{</citation>}}


### (31/79) Do the Benefits of Joint Models for Relation Extraction Extend to Document-level Tasks? (Pratik Saini et al., 2023)

{{<citation>}}

Pratik Saini, Tapas Nayak, Indrajit Bhattacharya. (2023)  
**Do the Benefits of Joint Models for Relation Extraction Extend to Document-level Tasks?**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Relation Extraction  
[Paper Link](http://arxiv.org/abs/2310.00696v1)  

---


**ABSTRACT**  
Two distinct approaches have been proposed for relational triple extraction - pipeline and joint. Joint models, which capture interactions across triples, are the more recent development, and have been shown to outperform pipeline models for sentence-level extraction tasks. Document-level extraction is a more challenging setting where interactions across triples can be long-range, and individual triples can also span across sentences. Joint models have not been applied for document-level tasks so far. In this paper, we benchmark state-of-the-art pipeline and joint extraction models on sentence-level as well as document-level datasets. Our experiments show that while joint models outperform pipeline models significantly for sentence-level extraction, their performance drops sharply below that of pipeline models for the document-level dataset.

{{</citation>}}


### (32/79) Meta Semantic Template for Evaluation of Large Language Models (Yachuan Liu et al., 2023)

{{<citation>}}

Yachuan Liu, Liang Chen, Jindong Wang, Qiaozhu Mei, Xing Xie. (2023)  
**Meta Semantic Template for Evaluation of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.01448v1)  

---


**ABSTRACT**  
Do large language models (LLMs) genuinely understand the semantics of the language, or just memorize the training data? The recent concern on potential data contamination of LLMs has raised awareness of the community to conduct research on LLMs evaluation. In this paper, we propose MSTemp, an approach that creates meta semantic templates to evaluate the semantic understanding ability of LLMs. The core of MSTemp is not to perform evaluation directly on existing benchmark datasets, but to generate new out-of-distribution (OOD) evaluation sets using existing datasets as seeds. Specifically, for a given sentence, MSTemp leverages another language model to generate new samples while preserving its semantics. The new samples are called semantic templates to the original sentence. Then, MSTemp generates evaluation samples via sentence parsing and random word replacement on the semantic templates. MSTemp is highly flexible, dynamic, and cost-effective. Our initial experiments show that MSTemp-generated samples can significantly reduce the performance of LLMs using existing datasets as seeds. We hope this initial work can shed light on future research of LLMs evaluation.

{{</citation>}}


### (33/79) CebuaNER: A New Baseline Cebuano Named Entity Recognition Model (Ma. Beatrice Emanuela Pilar et al., 2023)

{{<citation>}}

Ma. Beatrice Emanuela Pilar, Ellyza Mari Papas, Mary Loise Buenaventura, Dane Dedoroy, Myron Darrel Montefalcon, Jay Rhald Padilla, Lany Maceda, Mideth Abisado, Joseph Marvin Imperial. (2023)  
**CebuaNER: A New Baseline Cebuano Named Entity Recognition Model**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: LSTM, NER, Named Entity Recognition  
[Paper Link](http://arxiv.org/abs/2310.00679v1)  

---


**ABSTRACT**  
Despite being one of the most linguistically diverse groups of countries, computational linguistics and language processing research in Southeast Asia has struggled to match the level of countries from the Global North. Thus, initiatives such as open-sourcing corpora and the development of baseline models for basic language processing tasks are important stepping stones to encourage the growth of research efforts in the field. To answer this call, we introduce CebuaNER, a new baseline model for named entity recognition (NER) in the Cebuano language. Cebuano is the second most-used native language in the Philippines, with over 20 million speakers. To build the model, we collected and annotated over 4,000 news articles, the largest of any work in the language, retrieved from online local Cebuano platforms to train algorithms such as Conditional Random Field and Bidirectional LSTM. Our findings show promising results as a new baseline model, achieving over 70% performance on precision, recall, and F1 across all entity tags, as well as potential efficacy in a crosslingual setup with Tagalog.

{{</citation>}}


### (34/79) Adaptive-Solver Framework for Dynamic Strategy Selection in Large Language Model Reasoning (Jianpeng Zhou et al., 2023)

{{<citation>}}

Jianpeng Zhou, Wanjun Zhong, Yanlin Wang, Jiahai Wang. (2023)  
**Adaptive-Solver Framework for Dynamic Strategy Selection in Large Language Model Reasoning**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model, Reasoning  
[Paper Link](http://arxiv.org/abs/2310.01446v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) are showcasing impressive ability in handling complex reasoning tasks. In real-world situations, problems often span a spectrum of complexities. Humans inherently adjust their problem-solving approaches based on task complexity. However, most methodologies that leverage LLMs tend to adopt a uniform approach: utilizing consistent models, prompting methods, and degrees of problem decomposition, regardless of the problem complexity. Inflexibility of them can bring unnecessary computational overhead or sub-optimal performance. To address this problem, we introduce an Adaptive-Solver framework. It strategically modulates solving strategies based on the difficulties of the problems. Given an initial solution, the framework functions with two primary modules. The initial evaluation module assesses the adequacy of the current solution. If improvements are needed, the subsequent adaptation module comes into play. Within this module, three key adaptation strategies are employed: (1) Model Adaptation: Switching to a stronger LLM when a weaker variant is inadequate. (2) Prompting Method Adaptation: Alternating between different prompting techniques to suit the problem's nuances. (3) Decomposition Granularity Adaptation: Breaking down a complex problem into more fine-grained sub-questions to enhance solvability. Through such dynamic adaptations, our framework not only enhances computational efficiency but also elevates the overall performance. This dual-benefit ensures both the efficiency of the system for simpler tasks and the precision required for more complex questions. Experimental results from complex reasoning tasks reveal that the prompting method adaptation and decomposition granularity adaptation enhance performance across all tasks. Furthermore, the model adaptation approach significantly reduces API costs (up to 50%) while maintaining superior performance.

{{</citation>}}


### (35/79) Adapting LLM Agents Through Communication (Kuan Wang et al., 2023)

{{<citation>}}

Kuan Wang, Yadong Lu, Michael Santacroce, Yeyun Gong, Chao Zhang, Yelong Shen. (2023)  
**Adapting LLM Agents Through Communication**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Dialog, Dialogue, LLaMA, PaLM, QA  
[Paper Link](http://arxiv.org/abs/2310.01444v1)  

---


**ABSTRACT**  
Recent advancements in large language models (LLMs) have shown potential for human-like agents. To help these agents adapt to new tasks without extensive human supervision, we propose the Learning through Communication (LTC) paradigm, a novel training approach enabling LLM agents to improve continuously through interactions with their environments and other agents. Recent advancements in large language models (LLMs) have shown potential for human-like agents. To help these agents adapt to new tasks without extensive human supervision, we propose the Learning through Communication (LTC) paradigm, a novel training approach enabling LLM agents to improve continuously through interactions with their environments and other agents. Through iterative exploration and PPO training, LTC empowers the agent to assimilate short-term experiences into long-term memory. To optimize agent interactions for task-specific learning, we introduce three structured communication patterns: Monologue, Dialogue, and Analogue-tailored for common tasks such as decision-making, knowledge-intensive reasoning, and numerical reasoning. We evaluated LTC on three datasets: ALFWorld (decision-making), HotpotQA (knowledge-intensive reasoning), and GSM8k (numerical reasoning). On ALFWorld, it exceeds the instruction tuning baseline by 12% in success rate. On HotpotQA, LTC surpasses the instruction-tuned LLaMA-7B agent by 5.1% in EM score, and it outperforms the instruction-tuned 9x larger PaLM-62B agent by 0.6%. On GSM8k, LTC outperforms the CoT-Tuning baseline by 3.6% in accuracy. The results showcase the versatility and efficiency of the LTC approach across diverse domains. We will open-source our code to promote further development of the community.

{{</citation>}}


### (36/79) Faithful Explanations of Black-box NLP Models Using LLM-generated Counterfactuals (Yair Gat et al., 2023)

{{<citation>}}

Yair Gat, Nitay Calderon, Amir Feder, Alexander Chapanin, Amit Sharma, Roi Reichart. (2023)  
**Faithful Explanations of Black-box NLP Models Using LLM-generated Counterfactuals**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2310.00603v1)  

---


**ABSTRACT**  
Causal explanations of the predictions of NLP systems are essential to ensure safety and establish trust. Yet, existing methods often fall short of explaining model predictions effectively or efficiently and are often model-specific. In this paper, we address model-agnostic explanations, proposing two approaches for counterfactual (CF) approximation. The first approach is CF generation, where a large language model (LLM) is prompted to change a specific text concept while keeping confounding concepts unchanged. While this approach is demonstrated to be very effective, applying LLM at inference-time is costly. We hence present a second approach based on matching, and propose a method that is guided by an LLM at training-time and learns a dedicated embedding space. This space is faithful to a given causal graph and effectively serves to identify matches that approximate CFs. After showing theoretically that approximating CFs is required in order to construct faithful explanations, we benchmark our approaches and explain several models, including LLMs with billions of parameters. Our empirical results demonstrate the excellent performance of CF generation models as model-agnostic explainers. Moreover, our matching approach, which requires far less test-time resources, also provides effective explanations, surpassing many baselines. We also find that Top-K techniques universally improve every tested method. Finally, we showcase the potential of LLMs in constructing new benchmarks for model explanation and subsequently validate our conclusions. Our work illuminates new pathways for efficient and accurate approaches to interpreting NLP systems.

{{</citation>}}


### (37/79) A Novel Computational and Modeling Foundation for Automatic Coherence Assessment (Aviya Maimon et al., 2023)

{{<citation>}}

Aviya Maimon, Reut Tsarfaty. (2023)  
**A Novel Computational and Modeling Foundation for Automatic Coherence Assessment**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, NLP  
[Paper Link](http://arxiv.org/abs/2310.00598v1)  

---


**ABSTRACT**  
Coherence is an essential property of well-written texts, that refers to the way textual units relate to one another. In the era of generative AI, coherence assessment is essential for many NLP tasks; summarization, generation, long-form question-answering, and more. However, in NLP {coherence} is an ill-defined notion, not having a formal definition or evaluation metrics, that would allow for large-scale automatic and systematic coherence assessment. To bridge this gap, in this work we employ the formal linguistic definition of \citet{Reinhart:1980} of what makes a discourse coherent, consisting of three conditions -- {\em cohesion, consistency} and {\em relevance} -- and formalize these conditions as respective computational tasks. We hypothesize that (i) a model trained on all of these tasks will learn the features required for coherence detection, and that (ii) a joint model for all tasks will exceed the performance of models trained on each task individually. On two benchmarks for coherence scoring rated by humans, one containing 500 automatically-generated short stories and another containing 4k real-world texts, our experiments confirm that jointly training on the proposed tasks leads to better performance on each task compared with task-specific models, and to better performance on assessing coherence overall, compared with strong baselines. We conclude that the formal and computational setup of coherence as proposed here provides a solid foundation for advanced methods of large-scale automatic assessment of coherence.

{{</citation>}}


### (38/79) A Task-oriented Dialog Model with Task-progressive and Policy-aware Pre-training (Lucen Zhong et al., 2023)

{{<citation>}}

Lucen Zhong, Hengtong Lu, Caixia Yuan, Xiaojie Wang, Jiashen Sun, Ke Zeng, Guanglu Wan. (2023)  
**A Task-oriented Dialog Model with Task-progressive and Policy-aware Pre-training**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog  
[Paper Link](http://arxiv.org/abs/2310.00597v1)  

---


**ABSTRACT**  
Pre-trained conversation models (PCMs) have achieved promising progress in recent years. However, existing PCMs for Task-oriented dialog (TOD) are insufficient for capturing the sequential nature of the TOD-related tasks, as well as for learning dialog policy information. To alleviate these problems, this paper proposes a task-progressive PCM with two policy-aware pre-training tasks. The model is pre-trained through three stages where TOD-related tasks are progressively employed according to the task logic of the TOD system. A global policy consistency task is designed to capture the multi-turn dialog policy sequential relation, and an act-based contrastive learning task is designed to capture similarities among samples with the same dialog policy. Our model achieves better results on both MultiWOZ and In-Car end-to-end dialog modeling benchmarks with only 18\% parameters and 25\% pre-training data compared to the previous state-of-the-art PCM, GALAXY.

{{</citation>}}


### (39/79) Nine-year-old children outperformed ChatGPT in emotion: Evidence from Chinese writing (Siyi Cao et al., 2023)

{{<citation>}}

Siyi Cao, Tongquan Zhou, Siruo Zhou. (2023)  
**Nine-year-old children outperformed ChatGPT in emotion: Evidence from Chinese writing**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2310.00578v1)  

---


**ABSTRACT**  
ChatGPT has been demonstrated to possess significant capabilities in generating intricate, human-like text, and recent studies have established that its performance in theory of mind tasks is comparable to that of a nine-year-old child. However, it remains uncertain whether ChatGPT surpasses nine-year-old children in Chinese writing proficiency. To explore this, our study juxtaposed the Chinese writing performance of ChatGPT and nine-year-old children on both narrative and scientific topics, aiming to uncover the relative strengths and weaknesses of ChatGPT in writing.   The collected data were analyzed across five linguistic dimensions: fluency, accuracy, complexity, cohesion, and emotion. Each dimension underwent assessment through precise indices. The findings revealed that nine-year-old children excelled beyond ChatGPT in terms of fluency and cohesion within their writing. In contrast, ChatGPT manifested a superior performance in accuracy compared to the children. Concerning complexity, children exhibited superior skills in science-themed writing, while ChatGPT prevailed in nature-themed writing. Significantly, this research is pioneering in revealing that nine-year-old children convey stronger emotions than ChatGPT in their Chinese compositions.

{{</citation>}}


### (40/79) GrowLength: Accelerating LLMs Pretraining by Progressively Growing Training Length (Hongye Jin et al., 2023)

{{<citation>}}

Hongye Jin, Xiaotian Han, Jingfeng Yang, Zhimeng Jiang, Chia-Yuan Chang, Xia Hu. (2023)  
**GrowLength: Accelerating LLMs Pretraining by Progressively Growing Training Length**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.00576v1)  

---


**ABSTRACT**  
The evolving sophistication and intricacies of Large Language Models (LLMs) yield unprecedented advancements, yet they simultaneously demand considerable computational resources and incur significant costs. To alleviate these challenges, this paper introduces a novel, simple, and effective method named ``\growlength'' to accelerate the pretraining process of LLMs. Our method progressively increases the training length throughout the pretraining phase, thereby mitigating computational costs and enhancing efficiency. For instance, it begins with a sequence length of 128 and progressively extends to 4096. This approach enables models to process a larger number of tokens within limited time frames, potentially boosting their performance. In other words, the efficiency gain is derived from training with shorter sequences optimizing the utilization of resources. Our extensive experiments with various state-of-the-art LLMs have revealed that models trained using our method not only converge more swiftly but also exhibit superior performance metrics compared to those trained with existing methods. Furthermore, our method for LLMs pretraining acceleration does not require any additional engineering efforts, making it a practical solution in the realm of LLMs.

{{</citation>}}


### (41/79) Colloquial Persian POS (CPPOS) Corpus: A Novel Corpus for Colloquial Persian Part of Speech Tagging (Leyla Rabiei et al., 2023)

{{<citation>}}

Leyla Rabiei, Farzaneh Rahmani, Mohammad Khansari, Zeinab Rajabi, Moein Salimi. (2023)  
**Colloquial Persian POS (CPPOS) Corpus: A Novel Corpus for Colloquial Persian Part of Speech Tagging**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: LSTM, Twitter  
[Paper Link](http://arxiv.org/abs/2310.00572v1)  

---


**ABSTRACT**  
Introduction: Part-of-Speech (POS) Tagging, the process of classifying words into their respective parts of speech (e.g., verb or noun), is essential in various natural language processing applications. POS tagging is a crucial preprocessing task for applications like machine translation, question answering, sentiment analysis, etc. However, existing corpora for POS tagging in Persian mainly consist of formal texts, such as daily news and newspapers. As a result, smart POS tools, machine learning models, and deep learning models trained on these corpora may not perform optimally for processing colloquial text in social network analysis. Method: This paper introduces a novel corpus, "Colloquial Persian POS" (CPPOS), specifically designed to support colloquial Persian text. The corpus includes formal and informal text collected from various domains such as political, social, and commercial on Telegram, Twitter, and Instagram more than 520K labeled tokens. After collecting posts from these social platforms for one year, special preprocessing steps were conducted, including normalization, sentence tokenizing, and word tokenizing for social text. The tokens and sentences were then manually annotated and verified by a team of linguistic experts. This study also defines a POS tagging guideline for annotating the data and conducting the annotation process. Results: To evaluate the quality of CPPOS, various deep learning models, such as the RNN family, were trained using the constructed corpus. A comparison with another well-known Persian POS corpus named "Bijankhan" and the Persian Hazm POS tool trained on Bijankhan revealed that our model trained on CPPOS outperforms them. With the new corpus and the BiLSTM deep neural model, we achieved a 14% improvement over the previous dataset.

{{</citation>}}


### (42/79) Siamese Representation Learning for Unsupervised Relation Extraction (Guangxin Zhang et al., 2023)

{{<citation>}}

Guangxin Zhang, Shu Chen. (2023)  
**Siamese Representation Learning for Unsupervised Relation Extraction**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Relation Extraction, Representation Learning  
[Paper Link](http://arxiv.org/abs/2310.00552v1)  

---


**ABSTRACT**  
Unsupervised relation extraction (URE) aims at discovering underlying relations between named entity pairs from open-domain plain text without prior information on relational distribution. Existing URE models utilizing contrastive learning, which attract positive samples and repulse negative samples to promote better separation, have got decent effect. However, fine-grained relational semantic in relationship makes spurious negative samples, damaging the inherent hierarchical structure and hindering performances. To tackle this problem, we propose Siamese Representation Learning for Unsupervised Relation Extraction -- a novel framework to simply leverage positive pairs to representation learning, possessing the capability to effectively optimize relation representation of instances and retain hierarchical information in relational feature space. Experimental results show that our model significantly advances the state-of-the-art results on two benchmark datasets and detailed analyses demonstrate the effectiveness and robustness of our proposed model on unsupervised relation extraction.

{{</citation>}}


### (43/79) SELF: Language-Driven Self-Evolution for Large Language Model (Jianqiao Lu et al., 2023)

{{<citation>}}

Jianqiao Lu, Wanjun Zhong, Wenyong Huang, Yufei Wang, Fei Mi, Baojun Wang, Weichao Wang, Lifeng Shang, Qun Liu. (2023)  
**SELF: Language-Driven Self-Evolution for Large Language Model**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2310.00533v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have showcased remarkable versatility across diverse domains. However, the pathway toward autonomous model development, a cornerstone for achieving human-level learning and advancing autonomous AI, remains largely uncharted. We introduce an innovative approach, termed "SELF" (Self-Evolution with Language Feedback). This methodology empowers LLMs to undergo continual self-evolution. Furthermore, SELF employs language-based feedback as a versatile and comprehensive evaluative tool, pinpointing areas for response refinement and bolstering the stability of self-evolutionary training. Initiating with meta-skill learning, SELF acquires foundational meta-skills with a focus on self-feedback and self-refinement. These meta-skills are critical, guiding the model's subsequent self-evolution through a cycle of perpetual training with self-curated data, thereby enhancing its intrinsic abilities. Given unlabeled instructions, SELF equips the model with the capability to autonomously generate and interactively refine responses. This synthesized training data is subsequently filtered and utilized for iterative fine-tuning, enhancing the model's capabilities. Experimental results on representative benchmarks substantiate that SELF can progressively advance its inherent abilities without the requirement of human intervention, thereby indicating a viable pathway for autonomous model evolution. Additionally, SELF can employ online self-refinement strategy to produce responses of superior quality. In essence, the SELF framework signifies a progressive step towards autonomous LLM development, transforming the LLM from a mere passive recipient of information into an active participant in its own evolution.

{{</citation>}}


## stat.ML (2)



### (44/79) Learning to Make Adherence-Aware Advice (Guanting Chen et al., 2023)

{{<citation>}}

Guanting Chen, Xiaocheng Li, Chunlin Sun, Hanzhao Wang. (2023)  
**Learning to Make Adherence-Aware Advice**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.00817v1)  

---


**ABSTRACT**  
As artificial intelligence (AI) systems play an increasingly prominent role in human decision-making, challenges surface in the realm of human-AI interactions. One challenge arises from the suboptimal AI policies due to the inadequate consideration of humans disregarding AI recommendations, as well as the need for AI to provide advice selectively when it is most pertinent. This paper presents a sequential decision-making model that (i) takes into account the human's adherence level (the probability that the human follows/rejects machine advice) and (ii) incorporates a defer option so that the machine can temporarily refrain from making advice. We provide learning algorithms that learn the optimal advice policy and make advice only at critical time stamps. Compared to problem-agnostic reinforcement learning algorithms, our specialized learning algorithms not only enjoy better theoretical convergence properties but also show strong empirical performance.

{{</citation>}}


### (45/79) Thompson Exploration with Best Challenger Rule in Best Arm Identification (Jongyeong Lee et al., 2023)

{{<citation>}}

Jongyeong Lee, Junya Honda, Masashi Sugiyama. (2023)  
**Thompson Exploration with Best Challenger Rule in Best Arm Identification**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.00539v1)  

---


**ABSTRACT**  
This paper studies the fixed-confidence best arm identification (BAI) problem in the bandit framework in the canonical single-parameter exponential models. For this problem, many policies have been proposed, but most of them require solving an optimization problem at every round and/or are forced to explore an arm at least a certain number of times except those restricted to the Gaussian model. To address these limitations, we propose a novel policy that combines Thompson sampling with a computationally efficient approach known as the best challenger rule. While Thompson sampling was originally considered for maximizing the cumulative reward, we demonstrate that it can be used to naturally explore arms in BAI without forcing it. We show that our policy is asymptotically optimal for any two-armed bandit problems and achieves near optimality for general $K$-armed bandit problems for $K\geq 3$. Nevertheless, in numerical experiments, our policy shows competitive performance compared to asymptotically optimal policies in terms of sample complexity while requiring less computation cost. In addition, we highlight the advantages of our policy by comparing it to the concept of $\beta$-optimality, a relaxed notion of asymptotic optimality commonly considered in the analysis of a class of policies including the proposed one.

{{</citation>}}


## cs.CV (13)



### (46/79) Sharingan: A Transformer-based Architecture for Gaze Following (Samy Tafasca et al., 2023)

{{<citation>}}

Samy Tafasca, Anshul Gupta, Jean-Marc Odobez. (2023)  
**Sharingan: A Transformer-based Architecture for Gaze Following**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Transformer  
[Paper Link](http://arxiv.org/abs/2310.00816v1)  

---


**ABSTRACT**  
Gaze is a powerful form of non-verbal communication and social interaction that humans develop from an early age. As such, modeling this behavior is an important task that can benefit a broad set of application domains ranging from robotics to sociology. In particular, Gaze Following is defined as the prediction of the pixel-wise 2D location where a person in the image is looking. Prior efforts in this direction have focused primarily on CNN-based architectures to perform the task. In this paper, we introduce a novel transformer-based architecture for 2D gaze prediction. We experiment with 2 variants: the first one retains the same task formulation of predicting a gaze heatmap for one person at a time, while the second one casts the problem as a 2D point regression and allows us to perform multi-person gaze prediction with a single forward pass. This new architecture achieves state-of-the-art results on the GazeFollow and VideoAttentionTarget datasets. The code for this paper will be made publicly available.

{{</citation>}}


### (47/79) Propagating Semantic Labels in Video Data (David Balaban et al., 2023)

{{<citation>}}

David Balaban, Justin Medich, Pranay Gosar, Justin Hart. (2023)  
**Propagating Semantic Labels in Video Data**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2310.00783v1)  

---


**ABSTRACT**  
Semantic Segmentation combines two sub-tasks: the identification of pixel-level image masks and the application of semantic labels to those masks. Recently, so-called Foundation Models have been introduced; general models trained on very large datasets which can be specialized and applied to more specific tasks. One such model, the Segment Anything Model (SAM), performs image segmentation. Semantic segmentation systems such as CLIPSeg and MaskRCNN are trained on datasets of paired segments and semantic labels. Manual labeling of custom data, however, is time-consuming. This work presents a method for performing segmentation for objects in video. Once an object has been found in a frame of video, the segment can then be propagated to future frames; thus reducing manual annotation effort. The method works by combining SAM with Structure from Motion (SfM). The video input to the system is first reconstructed into 3D geometry using SfM. A frame of video is then segmented using SAM. Segments identified by SAM are then projected onto the the reconstructed 3D geometry. In subsequent video frames, the labeled 3D geometry is reprojected into the new perspective, allowing SAM to be invoked fewer times. System performance is evaluated, including the contributions of the SAM and SfM components. Performance is evaluated over three main metrics: computation time, mask IOU with manual labels, and the number of tracking losses. Results demonstrate that the system has substantial computation time improvements over human performance for tracking objects over video frames, but suffers in performance.

{{</citation>}}


### (48/79) Mind the Gap: Federated Learning Broadens Domain Generalization in Diagnostic AI Models (Soroosh Tayebi Arasteh et al., 2023)

{{<citation>}}

Soroosh Tayebi Arasteh, Christiane Kuhl, Marwin-Jonathan Saehn, Peter Isfort, Daniel Truhn, Sven Nebelung. (2023)  
**Mind the Gap: Federated Learning Broadens Domain Generalization in Diagnostic AI Models**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV, eess-IV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.00757v1)  

---


**ABSTRACT**  
Developing robust artificial intelligence (AI) models that generalize well to unseen datasets is challenging and usually requires large and variable datasets, preferably from multiple institutions. In federated learning (FL), a model is trained collaboratively at numerous sites that hold local datasets without exchanging them. So far, the impact of training strategy, i.e., local versus collaborative, on the diagnostic on-domain and off-domain performance of AI models interpreting chest radiographs has not been assessed. Consequently, using 610,000 chest radiographs from five institutions across the globe, we assessed diagnostic performance as a function of training strategy (i.e., local vs. collaborative), network architecture (i.e., convolutional vs. transformer-based), generalization performance (i.e., on-domain vs. off-domain), imaging finding (i.e., cardiomegaly, pleural effusion, pneumonia, atelectasis, consolidation, pneumothorax, and no abnormality), dataset size (i.e., from n=18,000 to 213,921 radiographs), and dataset diversity. Large datasets not only showed minimal performance gains with FL but, in some instances, even exhibited decreases. In contrast, smaller datasets revealed marked improvements. Thus, on-domain performance was mainly driven by training data size. However, off-domain performance leaned more on training diversity. When trained collaboratively across diverse external institutions, AI models consistently surpassed models trained locally for off-domain tasks, emphasizing FL's potential in leveraging data diversity. In conclusion, FL can bolster diagnostic privacy, reproducibility, and off-domain reliability of AI models and, potentially, optimize healthcare outcomes.

{{</citation>}}


### (49/79) HOH: Markerless Multimodal Human-Object-Human Handover Dataset with Large Object Count (Noah Wiederhold et al., 2023)

{{<citation>}}

Noah Wiederhold, Ava Megyeri, DiMaggio Paris, Sean Banerjee, Natasha Kholgade Banerjee. (2023)  
**HOH: Markerless Multimodal Human-Object-Human Handover Dataset with Large Object Count**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.00723v1)  

---


**ABSTRACT**  
We present the HOH (Human-Object-Human) Handover Dataset, a large object count dataset with 136 objects, to accelerate data-driven research on handover studies, human-robot handover implementation, and artificial intelligence (AI) on handover parameter estimation from 2D and 3D data of person interactions. HOH contains multi-view RGB and depth data, skeletons, fused point clouds, grasp type and handedness labels, object, giver hand, and receiver hand 2D and 3D segmentations, giver and receiver comfort ratings, and paired object metadata and aligned 3D models for 2,720 handover interactions spanning 136 objects and 20 giver-receiver pairs-40 with role-reversal-organized from 40 participants. We also show experimental results of neural networks trained using HOH to perform grasp, orientation, and trajectory prediction. As the only fully markerless handover capture dataset, HOH represents natural human-human handover interactions, overcoming challenges with markered datasets that require specific suiting for body tracking, and lack high-resolution hand tracking. To date, HOH is the largest handover dataset in number of objects, participants, pairs with role reversal accounted for, and total interactions captured.

{{</citation>}}


### (50/79) Logical Bias Learning for Object Relation Prediction (Xinyu Zhou et al., 2023)

{{<citation>}}

Xinyu Zhou, Zihan Ji, Anna Zhu. (2023)  
**Logical Bias Learning for Object Relation Prediction**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2310.00712v1)  

---


**ABSTRACT**  
Scene graph generation (SGG) aims to automatically map an image into a semantic structural graph for better scene understanding. It has attracted significant attention for its ability to provide object and relation information, enabling graph reasoning for downstream tasks. However, it faces severe limitations in practice due to the biased data and training method. In this paper, we present a more rational and effective strategy based on causal inference for object relation prediction. To further evaluate the superiority of our strategy, we propose an object enhancement module to conduct ablation studies. Experimental results on the Visual Gnome 150 (VG-150) dataset demonstrate the effectiveness of our proposed method. These contributions can provide great potential for foundation models for decision-making.

{{</citation>}}


### (51/79) You Do Not Need Additional Priors in Camouflage Object Detection (Yuchen Dong et al., 2023)

{{<citation>}}

Yuchen Dong, Heng Zhou, Chengyang Li, Junjie Xie, Yongqiang Xie, Zhongbo Li. (2023)  
**You Do Not Need Additional Priors in Camouflage Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2310.00702v1)  

---


**ABSTRACT**  
Camouflage object detection (COD) poses a significant challenge due to the high resemblance between camouflaged objects and their surroundings. Although current deep learning methods have made significant progress in detecting camouflaged objects, many of them heavily rely on additional prior information. However, acquiring such additional prior information is both expensive and impractical in real-world scenarios. Therefore, there is a need to develop a network for camouflage object detection that does not depend on additional priors. In this paper, we propose a novel adaptive feature aggregation method that effectively combines multi-layer feature information to generate guidance information. In contrast to previous approaches that rely on edge or ranking priors, our method directly leverages information extracted from image features to guide model training. Through extensive experimental results, we demonstrate that our proposed method achieves comparable or superior performance when compared to state-of-the-art approaches.

{{</citation>}}


### (52/79) A Hierarchical Graph-based Approach for Recognition and Description Generation of Bimanual Actions in Videos (Fatemeh Ziaeetabar et al., 2023)

{{<citation>}}

Fatemeh Ziaeetabar, Reza Safabakhsh, Saeedeh Momtazi, Minija Tamosiunaite, Florentin Wörgötter. (2023)  
**A Hierarchical Graph-based Approach for Recognition and Description Generation of Bimanual Actions in Videos**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Graph Attention Network  
[Paper Link](http://arxiv.org/abs/2310.00670v1)  

---


**ABSTRACT**  
Nuanced understanding and the generation of detailed descriptive content for (bimanual) manipulation actions in videos is important for disciplines such as robotics, human-computer interaction, and video content analysis. This study describes a novel method, integrating graph based modeling with layered hierarchical attention mechanisms, resulting in higher precision and better comprehensiveness of video descriptions. To achieve this, we encode, first, the spatio-temporal inter dependencies between objects and actions with scene graphs and we combine this, in a second step, with a novel 3-level architecture creating a hierarchical attention mechanism using Graph Attention Networks (GATs). The 3-level GAT architecture allows recognizing local, but also global contextual elements. This way several descriptions with different semantic complexity can be generated in parallel for the same video clip, enhancing the discriminative accuracy of action recognition and action description. The performance of our approach is empirically tested using several 2D and 3D datasets. By comparing our method to the state of the art we consistently obtain better performance concerning accuracy, precision, and contextual relevance when evaluating action recognition as well as description generation. In a large set of ablation experiments we also assess the role of the different components of our model. With our multi-level approach the system obtains different semantic description depths, often observed in descriptions made by different people, too. Furthermore, better insight into bimanual hand-object interactions as achieved by our model may portend advancements in the field of robotics, enabling the emulation of intricate human actions with heightened precision.

{{</citation>}}


### (53/79) Liveness Detection Competition -- Noncontact-based Fingerprint Algorithms and Systems (LivDet-2023 Noncontact Fingerprint) (Sandip Purnapatra et al., 2023)

{{<citation>}}

Sandip Purnapatra, Humaira Rezaie, Bhavin Jawade, Yu Liu, Yue Pan, Luke Brosell, Mst Rumana Sumi, Lambert Igene, Alden Dimarco, Srirangaraj Setlur, Soumyabrata Dey, Stephanie Schuckers, Marco Huber, Jan Niklas Kolf, Meiling Fang, Naser Damer, Banafsheh Adami, Raul Chitic, Karsten Seelert, Vishesh Mistry, Rahul Parthe, Umit Kacar. (2023)  
**Liveness Detection Competition -- Noncontact-based Fingerprint Algorithms and Systems (LivDet-2023 Noncontact Fingerprint)**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.00659v1)  

---


**ABSTRACT**  
Liveness Detection (LivDet) is an international competition series open to academia and industry with the objec-tive to assess and report state-of-the-art in Presentation Attack Detection (PAD). LivDet-2023 Noncontact Fingerprint is the first edition of the noncontact fingerprint-based PAD competition for algorithms and systems. The competition serves as an important benchmark in noncontact-based fingerprint PAD, offering (a) independent assessment of the state-of-the-art in noncontact-based fingerprint PAD for algorithms and systems, and (b) common evaluation protocol, which includes finger photos of a variety of Presentation Attack Instruments (PAIs) and live fingers to the biometric research community (c) provides standard algorithm and system evaluation protocols, along with the comparative analysis of state-of-the-art algorithms from academia and industry with both old and new android smartphones. The winning algorithm achieved an APCER of 11.35% averaged overall PAIs and a BPCER of 0.62%. The winning system achieved an APCER of 13.0.4%, averaged over all PAIs tested over all the smartphones, and a BPCER of 1.68% over all smartphones tested. Four-finger systems that make individual finger-based PAD decisions were also tested. The dataset used for competition will be available 1 to all researchers as per data share protocol

{{</citation>}}


### (54/79) Reformulating Vision-Language Foundation Models and Datasets Towards Universal Multimodal Assistants (Tianyu Yu et al., 2023)

{{<citation>}}

Tianyu Yu, Jinyi Hu, Yuan Yao, Haoye Zhang, Yue Zhao, Chongyi Wang, Shan Wang, Yinxv Pan, Jiao Xue, Dahai Li, Zhiyuan Liu, Hai-Tao Zheng, Maosong Sun. (2023)  
**Reformulating Vision-Language Foundation Models and Datasets Towards Universal Multimodal Assistants**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.00653v1)  

---


**ABSTRACT**  
Recent Multimodal Large Language Models (MLLMs) exhibit impressive abilities to perceive images and follow open-ended instructions. The capabilities of MLLMs depend on two crucial factors: the model architecture to facilitate the feature alignment of visual modules and large language models; the multimodal instruction tuning datasets for human instruction following. (i) For the model architecture, most existing models introduce an external bridge module to connect vision encoders with language models, which needs an additional feature-alignment pre-training. In this work, we discover that compact pre-trained vision language models can inherently serve as ``out-of-the-box'' bridges between vision and language. Based on this, we propose Muffin framework, which directly employs pre-trained vision-language models to act as providers of visual signals. (ii) For the multimodal instruction tuning datasets, existing methods omit the complementary relationship between different datasets and simply mix datasets from different tasks. Instead, we propose UniMM-Chat dataset which explores the complementarities of datasets to generate 1.1M high-quality and diverse multimodal instructions. We merge information describing the same image from diverse datasets and transforms it into more knowledge-intensive conversation data. Experimental results demonstrate the effectiveness of the Muffin framework and UniMM-Chat dataset. Muffin achieves state-of-the-art performance on a wide range of vision-language tasks, significantly surpassing state-of-the-art models like LLaVA and InstructBLIP. Our model and dataset are all accessible at https://github.com/thunlp/muffin.

{{</citation>}}


### (55/79) Beyond Task Performance: Evaluating and Reducing the Flaws of Large Multimodal Models with In-Context Learning (Mustafa Shukor et al., 2023)

{{<citation>}}

Mustafa Shukor, Alexandre Rame, Corentin Dancette, Matthieu Cord. (2023)  
**Beyond Task Performance: Evaluating and Reducing the Flaws of Large Multimodal Models with In-Context Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-MM, cs.CV  
Keywords: Language Model, QA  
[Paper Link](http://arxiv.org/abs/2310.00647v1)  

---


**ABSTRACT**  
Following the success of Large Language Models (LLMs), Large Multimodal Models (LMMs), such as the Flamingo model and its subsequent competitors, have started to emerge as natural steps towards generalist agents. However, interacting with recent LMMs reveals major limitations that are hardly captured by the current evaluation benchmarks. Indeed, task performances (e.g., VQA accuracy) alone do not provide enough clues to understand their real capabilities, limitations, and to which extent such models are aligned to human expectations. To refine our understanding of those flaws, we deviate from the current evaluation paradigm and propose the EvALign-ICL framework, in which we (1) evaluate 8 recent open-source LMMs (based on the Flamingo architecture such as OpenFlamingo and IDEFICS) on 5 different axes; hallucinations, abstention, compositionality, explainability and instruction following. Our evaluation on these axes reveals major flaws in LMMs. To efficiently address these problems, and inspired by the success of in-context learning (ICL) in LLMs, (2) we explore ICL as a solution and study how it affects these limitations. Based on our ICL study, (3) we push ICL further and propose new multimodal ICL approaches such as; Multitask-ICL, Chain-of-Hindsight-ICL, and Self-Correcting-ICL. Our findings are as follows; (1) Despite their success, LMMs have flaws that remain unsolved with scaling alone. (2) The effect of ICL on LMMs flaws is nuanced; despite its effectiveness for improved explainability, abstention, and instruction following, ICL does not improve compositional abilities, and actually even amplifies hallucinations. (3) The proposed ICL variants are promising as post-hoc approaches to efficiently tackle some of those flaws. The code is available here: https://evalign-icl.github.io/

{{</citation>}}


### (56/79) Win-Win: Training High-Resolution Vision Transformers from Two Windows (Vincent Leroy et al., 2023)

{{<citation>}}

Vincent Leroy, Jerome Revaud, Thomas Lucas, Philippe Weinzaepfel. (2023)  
**Win-Win: Training High-Resolution Vision Transformers from Two Windows**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2310.00632v1)  

---


**ABSTRACT**  
Transformers have become the standard in state-of-the-art vision architectures, achieving impressive performance on both image-level and dense pixelwise tasks. However, training vision transformers for high-resolution pixelwise tasks has a prohibitive cost. Typical solutions boil down to hierarchical architectures, fast and approximate attention, or training on low-resolution crops. This latter solution does not constrain architectural choices, but it leads to a clear performance drop when testing at resolutions significantly higher than that used for training, thus requiring ad-hoc and slow post-processing schemes. In this paper, we propose a novel strategy for efficient training and inference of high-resolution vision transformers: the key principle is to mask out most of the high-resolution inputs during training, keeping only N random windows. This allows the model to learn local interactions between tokens inside each window, and global interactions between tokens from different windows. As a result, the model can directly process the high-resolution input at test time without any special trick. We show that this strategy is effective when using relative positional embedding such as rotary embeddings. It is 4 times faster to train than a full-resolution network, and it is straightforward to use at test time compared to existing approaches. We apply this strategy to the dense monocular task of semantic segmentation, and find that a simple setting with 2 windows performs best, hence the name of our method: Win-Win. To demonstrate the generality of our contribution, we further extend it to the binocular task of optical flow, reaching state-of-the-art performance on the Spring benchmark that contains Full-HD images with an inference time an order of magnitude faster than the best competitor.

{{</citation>}}


### (57/79) Pink: Unveiling the Power of Referential Comprehension for Multi-modal LLMs (Shiyu Xuan et al., 2023)

{{<citation>}}

Shiyu Xuan, Qingpei Guo, Ming Yang, Shiliang Zhang. (2023)  
**Pink: Unveiling the Power of Referential Comprehension for Multi-modal LLMs**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.00582v1)  

---


**ABSTRACT**  
Multi-modal Large Language Models (MLLMs) have shown remarkable capabilities in many vision-language tasks. Nevertheless, most MLLMs still lack the Referential Comprehension (RC) ability to identify a specific object or area in images, limiting their application in fine-grained perception tasks. This paper proposes a novel method to enhance the RC capability for MLLMs. Our model represents the referring object in the image using the coordinates of its bounding box and converts the coordinates into texts in a specific format. This allows the model to treat the coordinates as natural language. Moreover, we construct the instruction tuning dataset with various designed RC tasks at a low cost by unleashing the potential of annotations in existing datasets. To further boost the RC ability of the model, we propose a self-consistent bootstrapping method that extends dense object annotations of a dataset into high-quality referring-expression-bounding-box pairs. The model is trained end-to-end with a parameter-efficient tuning framework that allows both modalities to benefit from multi-modal instruction tuning. This framework requires fewer trainable parameters and less training data. Experimental results on conventional vision-language and RC tasks demonstrate the superior performance of our method. For instance, our model exhibits a 12.0% absolute accuracy improvement over Instruct-BLIP on VSR and surpasses Kosmos-2 by 24.7% on RefCOCO_val under zero-shot settings. We also attain the top position on the leaderboard of MMBench. The models, datasets, and codes are publicly available at https://github.com/SY-Xuan/Pink

{{</citation>}}


### (58/79) Self-supervised Learning of Contextualized Local Visual Embeddings (Thalles Santos Silva et al., 2023)

{{<citation>}}

Thalles Santos Silva, Helio Pedrini, Adín Ramírez Rivera. (2023)  
**Self-supervised Learning of Contextualized Local Visual Embeddings**  

---
Primary Category: cs.CV  
Categories: I-4-6; I-4-7, cs-CV, cs.CV  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2310.00527v3)  

---


**ABSTRACT**  
We present Contextualized Local Visual Embeddings (CLoVE), a self-supervised convolutional-based method that learns representations suited for dense prediction tasks. CLoVE deviates from current methods and optimizes a single loss function that operates at the level of contextualized local embeddings learned from output feature maps of convolution neural network (CNN) encoders. To learn contextualized embeddings, CLoVE proposes a normalized mult-head self-attention layer that combines local features from different parts of an image based on similarity. We extensively benchmark CLoVE's pre-trained representations on multiple datasets. CLoVE reaches state-of-the-art performance for CNN-based architectures in 4 dense prediction downstream tasks, including object detection, instance segmentation, keypoint detection, and dense pose estimation.

{{</citation>}}


## cs.DB (4)



### (59/79) ReAcTable: Enhancing ReAct for Table Question Answering (Yunjia Zhang et al., 2023)

{{<citation>}}

Yunjia Zhang, Jordan Henkel, Avrilia Floratou, Joyce Cahoon, Shaleen Deep, Jignesh M. Patel. (2023)  
**ReAcTable: Enhancing ReAct for Table Question Answering**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs.DB  
Keywords: Language Model, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2310.00815v1)  

---


**ABSTRACT**  
Table Question Answering (TQA) presents a substantial challenge at the intersection of natural language processing and data analytics. This task involves answering natural language (NL) questions on top of tabular data, demanding proficiency in logical reasoning, understanding of data semantics, and fundamental analytical capabilities. Due to its significance, a substantial volume of research has been dedicated to exploring a wide range of strategies aimed at tackling this challenge including approaches that leverage Large Language Models (LLMs) through in-context learning or Chain-of-Thought (CoT) prompting as well as approaches that train and fine-tune custom models.   Nonetheless, a conspicuous gap exists in the research landscape, where there is limited exploration of how innovative foundational research, which integrates incremental reasoning with external tools in the context of LLMs, as exemplified by the ReAct paradigm, could potentially bring advantages to the TQA task. In this paper, we aim to fill this gap, by introducing ReAcTable (ReAct for Table Question Answering tasks), a framework inspired by the ReAct paradigm that is carefully enhanced to address the challenges uniquely appearing in TQA tasks such as interpreting complex data semantics, dealing with errors generated by inconsistent data and generating intricate data transformations. ReAcTable relies on external tools such as SQL and Python code executors, to progressively enhance the data by generating intermediate data representations, ultimately transforming it into a more accessible format for answering the questions with greater ease. We demonstrate that ReAcTable achieves remarkable performance even when compared to fine-tuned approaches. In particular, it outperforms the best prior result on the WikiTQ benchmark, achieving an accuracy of 68.0% without requiring training a new model or fine-tuning.

{{</citation>}}


### (60/79) SEED: Simple, Efficient, and Effective Data Management via Large Language Models (Zui CHen et al., 2023)

{{<citation>}}

Zui CHen, Lei Cao, Sam Madden, Ju Fan, Nan Tang, Zihui Gu, Zeyuan Shang, Chunwei Liu, Michael Cafarella, Tim Kraska. (2023)  
**SEED: Simple, Efficient, and Effective Data Management via Large Language Models**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs-LG, cs.DB  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.00749v1)  

---


**ABSTRACT**  
We introduce SEED, an LLM-centric system that allows users to easily create efficient, and effective data management applications. SEED comprises three main components: code generation, model generation, and augmented LLM query to address the challenges that LLM services are computationally and economically expensive and do not always work well on all cases for a given data management task. SEED addresses the expense challenge by localizing LLM computation as much as possible. This includes replacing most of LLM calls with local code, local models, and augmenting LLM queries with batching and data access tools, etc. To ensure effectiveness, SEED features a bunch of optimization techniques to enhance the localized solution and the LLM queries, including automatic code validation, code ensemble, model representatives selection, selective tool usages, etc. Moreover, with SEED users are able to easily construct a data management solution customized to their applications. It allows the users to configure each component and compose an execution pipeline in natural language. SEED then automatically compiles it into an executable program. We showcase the efficiency and effectiveness of SEED using diverse data management tasks such as data imputation, NL2SQL translation, etc., achieving state-of-the-art few-shot performance while significantly reducing the number of required LLM calls.

{{</citation>}}


### (61/79) Automatic Data Repair: Are We Ready to Deploy? (Wei Ni et al., 2023)

{{<citation>}}

Wei Ni, Xiaoye Miao, Xiangyu Zhao, Yangyang Wu, Jianwei Yin. (2023)  
**Automatic Data Repair: Are We Ready to Deploy?**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs.DB  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.00711v1)  

---


**ABSTRACT**  
Data quality is paramount in today's data-driven world, especially in the era of generative AI. Dirty data with errors and inconsistencies usually leads to flawed insights, unreliable decision-making, and biased or low-quality outputs from generative models. The study of repairing erroneous data has gained significant importance. Existing data repair algorithms differ in information utilization, problem settings, and are tested in limited scenarios. In this paper, we initially compare and summarize these algorithms using a new guided information-based taxonomy. We then systematically conduct a comprehensive evaluation of 12 mainstream data repair algorithms under the settings of various data error rates, error types, and downstream analysis tasks, assessing their error reduction performance with a novel metric. Also, we develop an effective and unified repair optimization strategy that substantially benefits the state of the arts, as empirically confirmed. We demonstrate that, the pure clean data may not necessarily yield the best performance in data analysis tasks and data is always worth repairing regardless of error rate. Based on the found observations and insights, we provide some practical guidelines for 5 scenarios and 2 main data analysis tasks. We anticipate this paper enabling researchers and users to well understand and deploy data repair algorithms in practice. Finally, we outline research challenges and promising future directions in the data repair field.

{{</citation>}}


### (62/79) CityFM: City Foundation Models to Solve Urban Challenges (Pasquale Balsebre et al., 2023)

{{<citation>}}

Pasquale Balsebre, Weiming Huang, Gao Cong, Yi Li. (2023)  
**CityFM: City Foundation Models to Solve Urban Challenges**  

---
Primary Category: cs.DB  
Categories: cs-AI, cs-DB, cs.DB  
Keywords: Computer Vision, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2310.00583v1)  

---


**ABSTRACT**  
Pre-trained Foundation Models (PFMs) have ushered in a paradigm-shift in Artificial Intelligence, due to their ability to learn general-purpose representations that can be readily employed in a wide range of downstream tasks. While PFMs have been successfully adopted in various fields such as Natural Language Processing and Computer Vision, their capacity in handling geospatial data and answering urban questions remains limited. This can be attributed to the intrinsic heterogeneity of geospatial data, which encompasses different data types, including points, segments and regions, as well as multiple information modalities, such as a spatial position, visual characteristics and textual annotations. The proliferation of Volunteered Geographic Information initiatives, and the ever-increasing availability of open geospatial data sources, like OpenStreetMap, which is freely accessible globally, unveil a promising opportunity to bridge this gap. In this paper, we present CityFM, a self-supervised framework to train a foundation model within a selected geographical area of interest, such as a city. CityFM relies solely on open data from OSM, and produces multimodal representations of entities of different types, incorporating spatial, visual, and textual information. We analyse the entity representations generated using our foundation models from a qualitative perspective, and conduct quantitative experiments on road, building, and region-level downstream tasks. We compare its results to algorithms tailored specifically for the respective applications. In all the experiments, CityFM achieves performance superior to, or on par with, the baselines.

{{</citation>}}


## cs.SI (1)



### (63/79) Revisiting Link Prediction: A Data Perspective (Haitao Mao et al., 2023)

{{<citation>}}

Haitao Mao, Juanhui Li, Harry Shomer, Bingheng Li, Wenqi Fan, Yao Ma, Tong Zhao, Neil Shah, Jiliang Tang. (2023)  
**Revisiting Link Prediction: A Data Perspective**  

---
Primary Category: cs.SI  
Categories: cs-AI, cs-SI, cs.SI  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2310.00793v1)  

---


**ABSTRACT**  
Link prediction, a fundamental task on graphs, has proven indispensable in various applications, e.g., friend recommendation, protein analysis, and drug interaction prediction. However, since datasets span a multitude of domains, they could have distinct underlying mechanisms of link formation. Evidence in existing literature underscores the absence of a universally best algorithm suitable for all datasets. In this paper, we endeavor to explore principles of link prediction across diverse datasets from a data-centric perspective. We recognize three fundamental factors critical to link prediction: local structural proximity, global structural proximity, and feature proximity. We then unearth relationships among those factors where (i) global structural proximity only shows effectiveness when local structural proximity is deficient. (ii) The incompatibility can be found between feature and structural proximity. Such incompatibility leads to GNNs for Link Prediction (GNN4LP) consistently underperforming on edges where the feature proximity factor dominates. Inspired by these new insights from a data perspective, we offer practical instruction for GNN4LP model design and guidelines for selecting appropriate benchmark datasets for more comprehensive evaluations.

{{</citation>}}


## cs.AI (2)



### (64/79) Pre-training with Synthetic Data Helps Offline Reinforcement Learning (Zecheng Wang et al., 2023)

{{<citation>}}

Zecheng Wang, Che Wang, Zixuan Dong, Keith Ross. (2023)  
**Pre-training with Synthetic Data Helps Offline Reinforcement Learning**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: Reinforcement Learning, Transformer  
[Paper Link](http://arxiv.org/abs/2310.00771v1)  

---


**ABSTRACT**  
Recently, it has been shown that for offline deep reinforcement learning (DRL), pre-training Decision Transformer with a large language corpus can improve downstream performance (Reid et al., 2022). A natural question to ask is whether this performance gain can only be achieved with language pre-training, or can be achieved with simpler pre-training schemes which do not involve language. In this paper, we first show that language is not essential for improved performance, and indeed pre-training with synthetic IID data for a small number of updates can match the performance gains from pre-training with a large language corpus; moreover, pre-training with data generated by a one-step Markov chain can further improve the performance. Inspired by these experimental results, we then consider pre-training Conservative Q-Learning (CQL), a popular offline DRL algorithm, which is Q-learning-based and typically employs a Multi-Layer Perceptron (MLP) backbone. Surprisingly, pre-training with simple synthetic data for a small number of updates can also improve CQL, providing consistent performance improvement on D4RL Gym locomotion datasets. The results of this paper not only illustrate the importance of pre-training for offline DRL but also show that the pre-training data can be synthetic and generated with remarkably simple mechanisms.

{{</citation>}}


### (65/79) Knowledge Engineering using Large Language Models (Bradley P. Allen et al., 2023)

{{<citation>}}

Bradley P. Allen, Lise Stork, Paul Groth. (2023)  
**Knowledge Engineering using Large Language Models**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2310.00637v1)  

---


**ABSTRACT**  
Knowledge engineering is a discipline that focuses on the creation and maintenance of processes that generate and apply knowledge. Traditionally, knowledge engineering approaches have focused on knowledge expressed in formal languages. The emergence of large language models and their capabilities to effectively work with natural language, in its broadest sense, raises questions about the foundations and practice of knowledge engineering. Here, we outline the potential role of LLMs in knowledge engineering, identifying two central directions: 1) creating hybrid neuro-symbolic knowledge systems; and 2) enabling knowledge engineering in natural language. Additionally, we formulate key open research questions to tackle these directions.

{{</citation>}}


## cs.RO (2)



### (66/79) Uncertainty-aware hybrid paradigm of nonlinear MPC and model-based RL for offroad navigation: Exploration of transformers in the predictive model (Faraz Lotfi et al., 2023)

{{<citation>}}

Faraz Lotfi, Khalil Virji, Farnoosh Faraji, Lucas Berry, Andrew Holliday, David Meger, Gregory Dudek. (2023)  
**Uncertainty-aware hybrid paradigm of nonlinear MPC and model-based RL for offroad navigation: Exploration of transformers in the predictive model**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2310.00760v1)  

---


**ABSTRACT**  
In this paper, we investigate a hybrid scheme that combines nonlinear model predictive control (MPC) and model-based reinforcement learning (RL) for navigation planning of an autonomous model car across offroad, unstructured terrains without relying on predefined maps. Our innovative approach takes inspiration from BADGR, an LSTM-based network that primarily concentrates on environment modeling, but distinguishes itself by substituting LSTM modules with transformers to greatly elevate the performance our model. Addressing uncertainty within the system, we train an ensemble of predictive models and estimate the mutual information between model weights and outputs, facilitating dynamic horizon planning through the introduction of variable speeds. Further enhancing our methodology, we incorporate a nonlinear MPC controller that accounts for the intricacies of the vehicle's model and states. The model-based RL facet produces steering angles and quantifies inherent uncertainty. At the same time, the nonlinear MPC suggests optimal throttle settings, striking a balance between goal attainment speed and managing model uncertainty influenced by velocity. In the conducted studies, our approach excels over the existing baseline by consistently achieving higher metric values in predicting future events and seamlessly integrating the vehicle's kinematic model for enhanced decision-making. The code and the evaluation data are available at https://github.com/FARAZLOTFI/offroad_autonomous_navigation/).

{{</citation>}}


### (67/79) Active Anomaly Detection in Confined Spaces Using Ergodic Traversal of Directed Region Graphs (Benjamin Wong et al., 2023)

{{<citation>}}

Benjamin Wong, Tyler M. Paine, Santosh Devasia, Ashis G. Banerjee. (2023)  
**Active Anomaly Detection in Confined Spaces Using Ergodic Traversal of Directed Region Graphs**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2310.00588v1)  

---


**ABSTRACT**  
We provide the first step toward developing a hierarchical control-estimation framework to actively plan robot trajectories for anomaly detection in confined spaces. The space is represented globally using a directed region graph, where a region is a landmark that needs to be visited (inspected). We devise a fast mixing Markov chain to find an ergodic route that traverses this graph so that the region visitation frequency is proportional to its anomaly detection uncertainty, while satisfying the edge directionality (region transition) constraint(s). Preliminary simulation results show fast convergence to the ergodic solution and confident estimation of the presence of anomalies in the inspected regions.

{{</citation>}}


## q-fin.PM (1)



### (68/79) NoxTrader: LSTM-Based Stock Return Momentum Prediction (Hsiang-Hui Liu et al., 2023)

{{<citation>}}

Hsiang-Hui Liu, Han-Jay Shu, Wei-Ning Chiu. (2023)  
**NoxTrader: LSTM-Based Stock Return Momentum Prediction**  

---
Primary Category: q-fin.PM  
Categories: cs-AI, q-fin-PM, q-fin.PM  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2310.00747v1)  

---


**ABSTRACT**  
We introduce NoxTrader, which is designed for portfolio construction and trading execution, aims at generating profitable outcomes. The primary focus of NoxTrader is on stock market trading with an emphasis on cultivating moderate to long-term profits. The underlying learning process of NoxTrader hinges on the assimilation of insights gleaned from historical trading data, primarily hinging on time-series analysis due to the inherent nature of the employed dataset. We delineate the sequential progression encompassing data acquisition, feature engineering, predictive modeling, parameter configuration, establishment of a rigorous backtesting framework, and ultimately position NoxTrader as a testament to the prospective viability of algorithmic trading models within real-world trading scenarios.

{{</citation>}}


## cs.CY (2)



### (69/79) GenAI Against Humanity: Nefarious Applications of Generative Artificial Intelligence and Large Language Models (Emilio Ferrara, 2023)

{{<citation>}}

Emilio Ferrara. (2023)  
**GenAI Against Humanity: Nefarious Applications of Generative Artificial Intelligence and Large Language Models**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CL, cs-CY, cs-HC, cs.CY  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2310.00737v1)  

---


**ABSTRACT**  
Generative Artificial Intelligence (GenAI) and Large Language Models (LLMs) are marvels of technology; celebrated for their prowess in natural language processing and multimodal content generation, they promise a transformative future. But as with all powerful tools, they come with their shadows. Picture living in a world where deepfakes are indistinguishable from reality, where synthetic identities orchestrate malicious campaigns, and where targeted misinformation or scams are crafted with unparalleled precision. Welcome to the darker side of GenAI applications.   This article is not just a journey through the meanders of potential misuse of GenAI and LLMs, but also a call to recognize the urgency of the challenges ahead. As we navigate the seas of misinformation campaigns, malicious content generation, and the eerie creation of sophisticated malware, we'll uncover the societal implications that ripple through the GenAI revolution we are witnessing. From AI-powered botnets on social media platforms to the unnerving potential of AI to generate fabricated identities, or alibis made of synthetic realities, the stakes have never been higher.   The lines between the virtual and the real worlds are blurring, and the consequences of potential GenAI's nefarious applications impact us all. This article serves both as a synthesis of rigorous research presented on the risks of GenAI and misuse of LLMs and as a thought-provoking vision of the different types of harmful GenAI applications we might encounter in the near future, and some ways we can prepare for them.

{{</citation>}}


### (70/79) The Robots are Here: Navigating the Generative AI Revolution in Computing Education (James Prather et al., 2023)

{{<citation>}}

James Prather, Paul Denny, Juho Leinonen, Brett A. Becker, Ibrahim Albluwi, Michelle Craig, Hieke Keuning, Natalie Kiesler, Tobias Kohn, Andrew Luxton-Reilly, Stephen MacNeil, Andrew Peterson, Raymond Pettit, Brent N. Reeves, Jaromir Savelka. (2023)  
**The Robots are Here: Navigating the Generative AI Revolution in Computing Education**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs-HC, cs.CY  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2310.00658v1)  

---


**ABSTRACT**  
Recent advancements in artificial intelligence (AI) are fundamentally reshaping computing, with large language models (LLMs) now effectively being able to generate and interpret source code and natural language instructions. These emergent capabilities have sparked urgent questions in the computing education community around how educators should adapt their pedagogy to address the challenges and to leverage the opportunities presented by this new technology. In this working group report, we undertake a comprehensive exploration of LLMs in the context of computing education and make five significant contributions. First, we provide a detailed review of the literature on LLMs in computing education and synthesise findings from 71 primary articles. Second, we report the findings of a survey of computing students and instructors from across 20 countries, capturing prevailing attitudes towards LLMs and their use in computing education contexts. Third, to understand how pedagogy is already changing, we offer insights collected from in-depth interviews with 22 computing educators from five continents who have already adapted their curricula and assessments. Fourth, we use the ACM Code of Ethics to frame a discussion of ethical issues raised by the use of large language models in computing education, and we provide concrete advice for policy makers, educators, and students. Finally, we benchmark the performance of LLMs on various computing education datasets, and highlight the extent to which the capabilities of current models are rapidly improving. Our aim is that this report will serve as a focal point for both researchers and practitioners who are exploring, adapting, using, and evaluating LLMs and LLM-based tools in computing classrooms.

{{</citation>}}


## cs.CR (4)



### (71/79) How well does LLM generate security tests? (Ying Zhang et al., 2023)

{{<citation>}}

Ying Zhang, Wenjia Song, Zhengjie Ji, Danfeng, Yao, Na Meng. (2023)  
**How well does LLM generate security tests?**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-SE, cs.CR  
Keywords: ChatGPT, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2310.00710v2)  

---


**ABSTRACT**  
Developers often build software on top of third-party libraries (Libs) to improve programmer productivity and software quality. The libraries may contain vulnerabilities exploitable by hackers to attack the applications (Apps) built on top of them. People refer to such attacks as supply chain attacks, the documented number of which has increased 742% in 2022. People created tools to mitigate such attacks, by scanning the library dependencies of Apps, identifying the usage of vulnerable library versions, and suggesting secure alternatives to vulnerable dependencies. However, recent studies show that many developers do not trust the reports by these tools; they ask for code or evidence to demonstrate how library vulnerabilities lead to security exploits, in order to assess vulnerability severity and modification necessity. Unfortunately, manually crafting demos of application-specific attacks is challenging and time-consuming, and there is insufficient tool support to automate that procedure.   In this study, we used ChatGPT-4.0 to generate security tests, and to demonstrate how vulnerable library dependencies facilitate the supply chain attacks to given Apps. We explored various prompt styles/templates, and found that ChatGPT-4.0 generated tests for all 55 Apps, demonstrating 24 attacks successfully. It outperformed two state-of-the-art security test generators -- TRANSFER and SIEGE -- by generating a lot more tests and achieving more exploits. ChatGPT-4.0 worked better when prompts described more on the vulnerabilities, possible exploits, and code context. Our research will shed light on new research in security test generation. The generated tests will help developers create secure by design and secure by default software.

{{</citation>}}


### (72/79) Streamlining Attack Tree Generation: A Fragment-Based Approach (Irdin Pekaric et al., 2023)

{{<citation>}}

Irdin Pekaric, Markus Frick, Jubril Gbolahan Adigun, Raffaela Groner, Thomas Witte, Alexander Raschke, Michael Felderer, Matthias Tichy. (2023)  
**Streamlining Attack Tree Generation: A Fragment-Based Approach**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-IR, cs.CR  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.00654v1)  

---


**ABSTRACT**  
Attack graphs are a tool for analyzing security vulnerabilities that capture different and prospective attacks on a system. As a threat modeling tool, it shows possible paths that an attacker can exploit to achieve a particular goal. However, due to the large number of vulnerabilities that are published on a daily basis, they have the potential to rapidly expand in size. Consequently, this necessitates a significant amount of resources to generate attack graphs. In addition, generating composited attack models for complex systems such as self-adaptive or AI is very difficult due to their nature to continuously change. In this paper, we present a novel fragment-based attack graph generation approach that utilizes information from publicly available information security databases. Furthermore, we also propose a domain-specific language for attack modeling, which we employ in the proposed attack graph generation approach. Finally, we present a demonstrator example showcasing the attack generator's capability to replicate a verified attack chain, as previously confirmed by security experts.

{{</citation>}}


### (73/79) Performance evaluation of Machine learning algorithms for Intrusion Detection System (Sudhanshu Sekhar Tripathy et al., 2023)

{{<citation>}}

Sudhanshu Sekhar Tripathy, Bichitrananda Behera. (2023)  
**Performance evaluation of Machine learning algorithms for Intrusion Detection System**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Intrusion Detection  
[Paper Link](http://arxiv.org/abs/2310.00594v1)  

---


**ABSTRACT**  
The escalation of hazards to safety and hijacking of digital networks are among the strongest perilous difficulties that must be addressed in the present day. Numerous safety procedures were set up to track and recognize any illicit activity on the network's infrastructure. IDS are the best way to resist and recognize intrusions on internet connections and digital technologies. To classify network traffic as normal or anomalous, Machine Learning (ML) classifiers are increasingly utilized. An IDS with machine learning increases the accuracy with which security attacks are detected. This paper focuses on intrusion detection systems (IDSs) analysis using ML techniques. IDSs utilizing ML techniques are efficient and precise at identifying network assaults. In data with large dimensional spaces, however, the efficacy of these systems degrades. correspondingly, the case is essential to execute a feasible feature removal technique capable of getting rid of characteristics that have little effect on the classification process. In this paper, we analyze the KDD CUP-'99' intrusion detection dataset used for training and validating ML models. Then, we implement ML classifiers such as Logistic Regression, Decision Tree, K-Nearest Neighbour, Naive Bayes, Bernoulli Naive Bayes, Multinomial Naive Bayes, XG-Boost Classifier, Ada-Boost, Random Forest, SVM, Rocchio classifier, Ridge, Passive-Aggressive classifier, ANN besides Perceptron (PPN), the optimal classifiers are determined by comparing the results of Stochastic Gradient Descent and back-propagation neural networks for IDS, Conventional categorization indicators, such as "accuracy, precision, recall, and the f1-measure, have been used to evaluate the performance of the ML classification algorithms.

{{</citation>}}


### (74/79) Horizontal Class Backdoor to Deep Learning (Hua Ma et al., 2023)

{{<citation>}}

Hua Ma, Shang Wang, Yansong Gao. (2023)  
**Horizontal Class Backdoor to Deep Learning**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-LG, cs.CR  
Keywords: AI, MNT, Pruning  
[Paper Link](http://arxiv.org/abs/2310.00542v1)  

---


**ABSTRACT**  
All existing backdoor attacks to deep learning (DL) models belong to the vertical class backdoor (VCB). That is, any sample from a class will activate the implanted backdoor in the presence of the secret trigger, regardless of source-class-agnostic or source-class-specific backdoor. Current trends of existing defenses are overwhelmingly devised for VCB attacks especially the source-class-agnostic backdoor, which essentially neglects other potential simple but general backdoor types, thus giving false security implications. It is thus urgent to discover unknown backdoor types.   This work reveals a new, simple, and general horizontal class backdoor (HCB) attack. We show that the backdoor can be naturally bounded with innocuous natural features that are common and pervasive in the real world. Note that an innocuous feature (e.g., expression) is irrelevant to the main task of the model (e.g., recognizing a person from one to another). The innocuous feature spans across classes horizontally but is exhibited by partial samples per class -- satisfying the horizontal class (HC) property. Only when the trigger is concurrently presented with the HC innocuous feature, can the backdoor be effectively activated. Extensive experiments on attacking performance in terms of high attack success rates with tasks of 1) MNIST, 2) facial recognition, 3) traffic sign recognition, and 4) object detection demonstrate that the HCB is highly efficient and effective. We extensively evaluate the HCB evasiveness against a (chronologically) series of 9 influential countermeasures of Fine-Pruning (RAID 18'), STRIP (ACSAC 19'), Neural Cleanse (Oakland 19'), ABS (CCS 19'), Februus (ACSAC 20'), MNTD (Oakland 21'), SCAn (USENIX SEC 21'), MOTH (Oakland 22'), and Beatrix (NDSS 23'), where none of them can succeed even when a simplest trigger is used.

{{</citation>}}


## cs.SD (1)



### (75/79) UniAudio: An Audio Foundation Model Toward Universal Audio Generation (Dongchao Yang et al., 2023)

{{<citation>}}

Dongchao Yang, Jinchuan Tian, Xu Tan, Rongjie Huang, Songxiang Liu, Xuankai Chang, Jiatong Shi, Sheng Zhao, Jiang Bian, Xixin Wu, Zhou Zhao, Helen Meng. (2023)  
**UniAudio: An Audio Foundation Model Toward Universal Audio Generation**  

---
Primary Category: cs.SD  
Categories: cs-SD, cs.SD, eess-AS  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2310.00704v2)  

---


**ABSTRACT**  
Large Language models (LLM) have demonstrated the capability to handle a variety of generative tasks. This paper presents the UniAudio system, which, unlike prior task-specific approaches, leverages LLM techniques to generate multiple types of audio (including speech, sounds, music, and singing) with given input conditions. UniAudio 1) first tokenizes all types of target audio along with other condition modalities, 2) concatenates source-target pair as a single sequence, and 3) performs next-token prediction using LLM. Also, a multi-scale Transformer model is proposed to handle the overly long sequences caused by the residual vector quantization based neural codec in tokenization. Training of UniAudio is scaled up to 165K hours of audio and 1B parameters, based on all generative tasks, aiming to obtain sufficient prior knowledge not only in the intrinsic properties of audio but also the inter-relationship between audio and other modalities. Therefore, the trained UniAudio model has the potential to become a foundation model for universal audio generation: it shows strong capability in all trained tasks and can seamlessly support new audio generation tasks after simple fine-tuning. Experiments demonstrate that UniAudio achieves state-of-the-art or at least competitive results on most of the 11 tasks. Demo and code are released at https://github.com/yangdongchao/UniAudio

{{</citation>}}


## cs.SE (1)



### (76/79) A Roadmap towards Intelligent Operations for Reliable Cloud Computing Systems (Yintong Huo et al., 2023)

{{<citation>}}

Yintong Huo, Cheryl Lee, Jinyang Liu, Tianyi Yang, Michael R. Lyu. (2023)  
**A Roadmap towards Intelligent Operations for Reliable Cloud Computing Systems**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2310.00677v1)  

---


**ABSTRACT**  
The increasing complexity and usage of cloud systems have made it challenging for service providers to ensure reliability. This paper highlights two main challenges, namely internal and external factors, that affect the reliability of cloud microservices. Afterward, we discuss the data-driven approach that can resolve these challenges from four key aspects: ticket management, log management, multimodal analysis, and the microservice resilience testing approach. The experiments conducted show that the proposed data-driven AIOps solution significantly enhances system reliability from multiple angles.

{{</citation>}}


## cs.NI (1)



### (77/79) Reinforcement Learning Based Neighbour Selection for VANET with Adaptive Trust Management (Orvila Sarker et al., 2023)

{{<citation>}}

Orvila Sarker, Hong Shen, M. Ali Babar. (2023)  
**Reinforcement Learning Based Neighbour Selection for VANET with Adaptive Trust Management**  

---
Primary Category: cs.NI  
Categories: cs-NI, cs.NI  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2310.00635v1)  

---


**ABSTRACT**  
Successful information propagation from source to destination in Vehicular Adhoc Network (VANET) can be hampered by the presence of neighbouring attacker nodes causing unwanted packet dropping. Potential attackers change their behaviour over time and remain undetected due to the ad-hoc nature of VANET. Capturing the dynamic attacker behaviour and updating the corresponding neighbourhood information without compromising the quality of service requirements is an ongoing challenge. This work proposes a Reinforcement Learning (RL) based neighbour selection framework for VANET with an adaptive trust management system to capture the behavioural changes of potential attackers and to dynamically update the neighbourhood information. In contrast to existing works, we consider trust and link-life time in unison as neighbour selection criteria to achieve trustworthy communication. Our adaptive trust model takes into account the social relationship, time and confidence in trust observation to avoid four types of attackers. To update the neighbourhood information, our framework sets the learning rate of the RL agent according to the velocities of the neighbour nodes to improve the model's adaptability to network topology changes. Results demonstrate that our method can take less number of hops to the destination for large network sizes while can response is up to 54 percent faster compared to a baseline method. Also, the proposed model can outperform the other baseline method by reducing the packet dropping rate up to 57 percent caused by the attacker.

{{</citation>}}


## eess.AS (1)



### (78/79) Wavelet Scattering Transform for Improving Generalization in Low-Resourced Spoken Language Identification (Spandan Dey et al., 2023)

{{<citation>}}

Spandan Dey, Premjeet Singh, Goutam Saha. (2023)  
**Wavelet Scattering Transform for Improving Generalization in Low-Resourced Spoken Language Identification**  

---
Primary Category: eess.AS  
Categories: cs-CL, eess-AS, eess.AS  
Keywords: Language Identification, Low-Resource  
[Paper Link](http://arxiv.org/abs/2310.00602v2)  

---


**ABSTRACT**  
Commonly used features in spoken language identification (LID), such as mel-spectrogram or MFCC, lose high-frequency information due to windowing. The loss further increases for longer temporal contexts. To improve generalization of the low-resourced LID systems, we investigate an alternate feature representation, wavelet scattering transform (WST), that compensates for the shortcomings. To our knowledge, WST is not explored earlier in LID tasks. We first optimize WST features for multiple South Asian LID corpora. We show that LID requires low octave resolution and frequency-scattering is not useful. Further, cross-corpora evaluations show that the optimal WST hyper-parameters depend on both train and test corpora. Hence, we develop fused ECAPA-TDNN based LID systems with different sets of WST hyper-parameters to improve generalization for unknown data. Compared to MFCC, EER is reduced upto 14.05% and 6.40% for same-corpora and blind VoxLingua107 evaluations, respectively.

{{</citation>}}


## cs.IR (1)



### (79/79) TDCGL: Two-Level Debiased Contrastive Graph Learning for Recommendation (Yubo Gao et al., 2023)

{{<citation>}}

Yubo Gao, Haotian Wu. (2023)  
**TDCGL: Two-Level Debiased Contrastive Graph Learning for Recommendation**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs.IR  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2310.00569v1)  

---


**ABSTRACT**  
knowledge graph-based recommendation methods have achieved great success in the field of recommender systems. However, over-reliance on high-quality knowledge graphs is a bottleneck for such methods. Specifically, the long-tailed distribution of entities of KG and noise issues in the real world will make item-entity dependent relations deviate from reflecting true characteristics and significantly harm the performance of modeling user preference. Contrastive learning, as a novel method that is employed for data augmentation and denoising, provides inspiration to fill this research gap. However, the mainstream work only focuses on the long-tail properties of the number of items clicked, while ignoring that the long-tail properties of total number of clicks per user may also affect the performance of the recommendation model. Therefore, to tackle these problems, motivated by the Debiased Contrastive Learning of Unsupervised Sentence Representations (DCLR), we propose Two-Level Debiased Contrastive Graph Learning (TDCGL) model. Specifically, we design the Two-Level Debiased Contrastive Learning (TDCL) and deploy it in the KG, which is conducted not only on User-Item pairs but also on User-User pairs for modeling higher-order relations. Also, to reduce the bias caused by random sampling in contrastive learning, with the exception of the negative samples obtained by random sampling, we add a noise-based generation of negation to ensure spatial uniformity. Considerable experiments on open-source datasets demonstrate that our method has excellent anti-noise capability and significantly outperforms state-of-the-art baselines. In addition, ablation studies about the necessity for each level of TDCL are conducted.

{{</citation>}}
