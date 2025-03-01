---
draft: false
title: "arXiv @ 2023.11.25"
date: 2023-11-25
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.11.25"
    identifier: arxiv_20231125
    parent: 202311_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [eess.IV (3)](#eessiv-3)
- [cs.LG (10)](#cslg-10)
- [stat.ML (1)](#statml-1)
- [cs.CV (19)](#cscv-19)
- [cs.SI (1)](#cssi-1)
- [cs.CL (17)](#cscl-17)
- [hep-ex (1)](#hep-ex-1)
- [cs.RO (2)](#csro-2)
- [cs.AI (8)](#csai-8)
- [cs.HC (2)](#cshc-2)
- [cs.IR (1)](#csir-1)
- [q-fin.ST (1)](#q-finst-1)
- [math.NA (2)](#mathna-2)
- [cs.CR (4)](#cscr-4)
- [eess.SY (1)](#eesssy-1)
- [cs.SE (2)](#csse-2)
- [cs.NI (1)](#csni-1)
- [quant-ph (1)](#quant-ph-1)
- [eess.SP (1)](#eesssp-1)
- [q-fin.CP (1)](#q-fincp-1)

## eess.IV (3)



### (1/79) Robust and Interpretable COVID-19 Diagnosis on Chest X-ray Images using Adversarial Training (Karina Yang et al., 2023)

{{<citation>}}

Karina Yang, Alexis Bennett, Dominique Duncan. (2023)  
**Robust and Interpretable COVID-19 Diagnosis on Chest X-ray Images using Adversarial Training**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: AI, Adversarial Training  
[Paper Link](http://arxiv.org/abs/2311.14227v1)  

---


**ABSTRACT**  
The novel 2019 Coronavirus disease (COVID-19) global pandemic is a defining health crisis. Recent efforts have been increasingly directed towards achieving quick and accurate detection of COVID-19 across symptomatic patients to mitigate the intensity and spread of the disease. Artificial intelligence (AI) algorithms applied to chest X-ray (CXR) images have emerged as promising diagnostic tools, and previous work has demonstrated impressive classification performances. However, such methods have faced criticisms from physicians due to their black-box reasoning process and unpredictable nature. In contrast to professional radiologist diagnosis, AI systems often lack generalizability, explainability, and robustness in the clinical decision making process. In our work, we address these issues by first proposing an extensive baseline study, training and evaluating 21 convolutional neural network (CNN) models on a diverse set of 33,000+ CXR images to classify between healthy, COVID-19, and non-COVID-19 pneumonia CXRs. Our resulting models achieved a 3-way classification accuracy, recall, and precision of up to 97.03\%, 97.97\%, and 99.95\%, respectively. Next, we investigate the effectiveness of adversarial training on model robustness and explainability via Gradient-weighted Class Activation Mapping (Grad-CAM) heatmaps. We find that adversarially trained models not only significantly outperform their standard counterparts on classifying perturbed images, but also yield saliency maps that 1) better specify clinically relevant features, 2) are robust against extraneous artifacts, and 3) agree considerably more with expert radiologist findings.

{{</citation>}}


### (2/79) Automated 3D Tumor Segmentation using Temporal Cubic PatchGAN (TCuP-GAN) (Kameswara Bharadwaj Mantha et al., 2023)

{{<citation>}}

Kameswara Bharadwaj Mantha, Ramanakumar Sankar, Lucy Fortson. (2023)  
**Automated 3D Tumor Segmentation using Temporal Cubic PatchGAN (TCuP-GAN)**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2311.14148v1)  

---


**ABSTRACT**  
Development of robust general purpose 3D segmentation frameworks using the latest deep learning techniques is one of the active topics in various bio-medical domains. In this work, we introduce Temporal Cubic PatchGAN (TCuP-GAN), a volume-to-volume translational model that marries the concepts of a generative feature learning framework with Convolutional Long Short-Term Memory Networks (LSTMs), for the task of 3D segmentation. We demonstrate the capabilities of our TCuP-GAN on the data from four segmentation challenges (Adult Glioma, Meningioma, Pediatric Tumors, and Sub-Saharan Africa subset) featured within the 2023 Brain Tumor Segmentation (BraTS) Challenge and quantify its performance using LesionWise Dice similarity and $95\%$ Hausdorff Distance metrics. We demonstrate the successful learning of our framework to predict robust multi-class segmentation masks across all the challenges. This benchmarking work serves as a stepping stone for future efforts towards applying TCuP-GAN on other multi-class tasks such as multi-organelle segmentation in electron microscopy imaging.

{{</citation>}}


### (3/79) Predicting Recovery or Decease of COVID-19 Patients with Clinical and RT-PCR Using Machine Learning Classification Algorithms (Mohammad Dehghani et al., 2023)

{{<citation>}}

Mohammad Dehghani, Zahra Yazdanparast. (2023)  
**Predicting Recovery or Decease of COVID-19 Patients with Clinical and RT-PCR Using Machine Learning Classification Algorithms**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: Clinical  
[Paper Link](http://arxiv.org/abs/2311.13925v1)  

---


**ABSTRACT**  
The COVID-19 pandemic has disrupted the global economy and people's daily lives in unprecedented ways. To make appropriate decisions, it is necessary to diagnose COVID-19 rapidly and accurately. Clinical decision making is influenced by data collected from patients. With the aid of artificial intelligence, COVID-19 has been diagnosed quickly by analyzing symptoms, polymerase chain reaction (PCR), computed tomography scans, chest X-rays, routine laboratory blood tests and even cough sounds. Furthermore, these data can be used to predict a patient's morality, although there is a question about which data makes the most accurate predictions. Therefore, this study consists of two parts. Our first objective is to examine whether machine learning algorithms can predict the outcome of COVID-19 cases (recovery or death), based on the features present in the dataset. In the second part of the research, we investigated the impact of clinical and RT-PCR on prediction of recovery and decease to determine which one is more reliable. We defined four stages with different feature sets and use six machine learning methods to build prediction model. With an accuracy of 78.7%, random forest showed promising results for predicting death and recovery of patients. Based on this, it appears that recovery and decease of patients are predictable using machine learning. For second objective, results indicate that clinical alone (without using RT-PCR), trained with AdaBoost algorithm, is the most accurate with an accuracy of 82.1%. This study can provide guidance for medical professionals in the event of a crisis or outbreak similar to COVID-19.

{{</citation>}}


## cs.LG (10)



### (4/79) Extending Variability-Aware Model Selection with Bias Detection in Machine Learning Projects (Cristina Tavares et al., 2023)

{{<citation>}}

Cristina Tavares, Nathalia Nascimento, Paulo Alencar, Donald Cowan. (2023)  
**Extending Variability-Aware Model Selection with Bias Detection in Machine Learning Projects**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-SE, cs.LG  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2311.14214v1)  

---


**ABSTRACT**  
Data science projects often involve various machine learning (ML) methods that depend on data, code, and models. One of the key activities in these projects is the selection of a model or algorithm that is appropriate for the data analysis at hand. ML model selection depends on several factors, which include data-related attributes such as sample size, functional requirements such as the prediction algorithm type, and non-functional requirements such as performance and bias. However, the factors that influence such selection are often not well understood and explicitly represented. This paper describes ongoing work on extending an adaptive variability-aware model selection method with bias detection in ML projects. The method involves: (i) modeling the variability of the factors that affect model selection using feature models based on heuristics proposed in the literature; (ii) instantiating our variability model with added features related to bias (e.g., bias-related metrics); and (iii) conducting experiments that illustrate the method in a specific case study to illustrate our approach based on a heart failure prediction project. The proposed approach aims to advance the state of the art by making explicit factors that influence model selection, particularly those related to bias, as well as their interactions. The provided representations can transform model selection in ML projects into a non ad hoc, adaptive, and explainable process.

{{</citation>}}


### (5/79) Shortcut Bias Mitigation via Ensemble Diversity Using Diffusion Probabilistic Models (Luca Scimeca et al., 2023)

{{<citation>}}

Luca Scimeca, Alexander Rubinstein, Damien Teney, Seong Joon Oh, Armand Mihai Nicolicioiu, Yoshua Bengio. (2023)  
**Shortcut Bias Mitigation via Ensemble Diversity Using Diffusion Probabilistic Models**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs.LG  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2311.16176v1)  

---


**ABSTRACT**  
Spurious correlations in the data, where multiple cues are predictive of the target labels, often lead to a phenomenon known as simplicity bias, where a model relies on erroneous, easy-to-learn cues while ignoring reliable ones. In this work, we propose an ensemble diversification framework exploiting Diffusion Probabilistic Models (DPMs) for shortcut bias mitigation. We show that at particular training intervals, DPMs can generate images with novel feature combinations, even when trained on images displaying correlated input features. We leverage this crucial property to generate synthetic counterfactuals to increase model diversity via ensemble disagreement. We show that DPM-guided diversification is sufficient to remove dependence on primary shortcut cues, without a need for additional supervised signals. We further empirically quantify its efficacy on several diversification objectives, and finally show improved generalization and diversification performance on par with prior work that relies on auxiliary data collection.

{{</citation>}}


### (6/79) ExCeL : Combined Extreme and Collective Logit Information for Enhancing Out-of-Distribution Detection (Naveen Karunanayake et al., 2023)

{{<citation>}}

Naveen Karunanayake, Suranga Seneviratne, Sanjay Chawla. (2023)  
**ExCeL : Combined Extreme and Collective Logit Information for Enhancing Out-of-Distribution Detection**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2311.14754v1)  

---


**ABSTRACT**  
Deep learning models often exhibit overconfidence in predicting out-of-distribution (OOD) data, underscoring the crucial role of OOD detection in ensuring reliability in predictions. Among various OOD detection approaches, post-hoc detectors have gained significant popularity, primarily due to their ease of use and implementation. However, the effectiveness of most post-hoc OOD detectors has been constrained as they rely solely either on extreme information, such as the maximum logit, or on the collective information (i.e., information spanned across classes or training samples) embedded within the output layer. In this paper, we propose ExCeL that combines both extreme and collective information within the output layer for enhanced accuracy in OOD detection. We leverage the logit of the top predicted class as the extreme information (i.e., the maximum logit), while the collective information is derived in a novel approach that involves assessing the likelihood of other classes appearing in subsequent ranks across various training samples. Our idea is motivated by the observation that, for in-distribution (ID) data, the ranking of classes beyond the predicted class is more deterministic compared to that in OOD data. Experiments conducted on CIFAR100 and ImageNet-200 datasets demonstrate that ExCeL consistently is among the five top-performing methods out of twenty-one existing post-hoc baselines when the joint performance on near-OOD and far-OOD is considered (i.e., in terms of AUROC and FPR95). Furthermore, ExCeL shows the best overall performance across both datasets, unlike other baselines that work best on one dataset but has a performance drop in the other.

{{</citation>}}


### (7/79) RankFeat&RankWeight: Rank-1 Feature/Weight Removal for Out-of-distribution Detection (Yue Song et al., 2023)

{{<citation>}}

Yue Song, Nicu Sebe, Wei Wang. (2023)  
**RankFeat&RankWeight: Rank-1 Feature/Weight Removal for Out-of-distribution Detection**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2311.13959v2)  

---


**ABSTRACT**  
The task of out-of-distribution (OOD) detection is crucial for deploying machine learning models in real-world settings. In this paper, we observe that the singular value distributions of the in-distribution (ID) and OOD features are quite different: the OOD feature matrix tends to have a larger dominant singular value than the ID feature, and the class predictions of OOD samples are largely determined by it. This observation motivates us to propose \texttt{RankFeat}, a simple yet effective \emph{post hoc} approach for OOD detection by removing the rank-1 matrix composed of the largest singular value and the associated singular vectors from the high-level feature. \texttt{RankFeat} achieves \emph{state-of-the-art} performance and reduces the average false positive rate (FPR95) by 17.90\% compared with the previous best method. The success of \texttt{RankFeat} motivates us to investigate whether a similar phenomenon would exist in the parameter matrices of neural networks. We thus propose \texttt{RankWeight} which removes the rank-1 weight from the parameter matrices of a single deep layer. Our \texttt{RankWeight}is also \emph{post hoc} and only requires computing the rank-1 matrix once. As a standalone approach, \texttt{RankWeight} has very competitive performance against other methods across various backbones. Moreover, \texttt{RankWeight} enjoys flexible compatibility with a wide range of OOD detection methods. The combination of \texttt{RankWeight} and \texttt{RankFeat} refreshes the new \emph{state-of-the-art} performance, achieving the FPR95 as low as 16.13\% on the ImageNet-1k benchmark. Extensive ablation studies and comprehensive theoretical analyses are presented to support the empirical results.

{{</citation>}}


### (8/79) Learning Uniform Clusters on Hypersphere for Deep Graph-level Clustering (Mengling Hu et al., 2023)

{{<citation>}}

Mengling Hu, Chaochao Chen, Weiming Liu, Xinyi Zhang, Xinting Liao, Xiaolin Zheng. (2023)  
**Learning Uniform Clusters on Hypersphere for Deep Graph-level Clustering**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2311.13953v1)  

---


**ABSTRACT**  
Graph clustering has been popularly studied in recent years. However, most existing graph clustering methods focus on node-level clustering, i.e., grouping nodes in a single graph into clusters. In contrast, graph-level clustering, i.e., grouping multiple graphs into clusters, remains largely unexplored. Graph-level clustering is critical in a variety of real-world applications, such as, properties prediction of molecules and community analysis in social networks. However, graph-level clustering is challenging due to the insufficient discriminability of graph-level representations, and the insufficient discriminability makes deep clustering be more likely to obtain degenerate solutions (cluster collapse). To address the issue, we propose a novel deep graph-level clustering method called Uniform Deep Graph Clustering (UDGC). UDGC assigns instances evenly to different clusters and then scatters those clusters on unit hypersphere, leading to a more uniform cluster-level distribution and a slighter cluster collapse. Specifically, we first propose Augmentation-Consensus Optimal Transport (ACOT) for generating uniformly distributed and reliable pseudo labels for partitioning clusters. Then we adopt contrastive learning to scatter those clusters. Besides, we propose Center Alignment Optimal Transport (CAOT) for guiding the model to learn better parameters, which further promotes the cluster performance. Our empirical study on eight well-known datasets demonstrates that UDGC significantly outperforms the state-of-the-art models.

{{</citation>}}


### (9/79) Object Location Prediction in Real-time using LSTM Neural Network and Polynomial Regression (Petar Stojković et al., 2023)

{{<citation>}}

Petar Stojković, Predrag Tadić. (2023)  
**Object Location Prediction in Real-time using LSTM Neural Network and Polynomial Regression**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-RO, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2311.13950v1)  

---


**ABSTRACT**  
This paper details the design and implementation of a system for predicting and interpolating object location coordinates. Our solution is based on processing inertial measurements and global positioning system data through a Long Short-Term Memory (LSTM) neural network and polynomial regression. LSTM is a type of recurrent neural network (RNN) particularly suited for processing data sequences and avoiding the long-term dependency problem. We employed data from real-world vehicles and the global positioning system (GPS) sensors. A critical pre-processing step was developed to address varying sensor frequencies and inconsistent GPS time steps and dropouts. The LSTM-based system's performance was compared with the Kalman Filter. The system was tuned to work in real-time with low latency and high precision. We tested our system on roads under various driving conditions, including acceleration, turns, deceleration, and straight paths. We tested our proposed solution's accuracy and inference time and showed that it could perform in real-time. Our LSTM-based system yielded an average error of 0.11 meters with an inference time of 2 ms. This represents a 76\% reduction in error compared to the traditional Kalman filter method, which has an average error of 0.46 meters with a similar inference time to the LSTM-based system.

{{</citation>}}


### (10/79) Optimal Power Flow in Highly Renewable Power System Based on Attention Neural Networks (Chen Li et al., 2023)

{{<citation>}}

Chen Li, Alexander Kies, Kai Zhou, Markus Schlott, Omar El Sayed, Mariia Bilousova, Horst Stoecker. (2023)  
**Optimal Power Flow in Highly Renewable Power System Based on Attention Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-SY, cs.LG, eess-SY  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2311.13949v1)  

---


**ABSTRACT**  
The Optimal Power Flow (OPF) problem is pivotal for power system operations, guiding generator output and power distribution to meet demand at minimized costs, while adhering to physical and engineering constraints. The integration of renewable energy sources, like wind and solar, however, poses challenges due to their inherent variability. This variability, driven largely by changing weather conditions, demands frequent recalibrations of power settings, thus necessitating recurrent OPF resolutions. This task is daunting using traditional numerical methods, particularly for extensive power systems. In this work, we present a cutting-edge, physics-informed machine learning methodology, trained using imitation learning and historical European weather datasets. Our approach directly correlates electricity demand and weather patterns with power dispatch and generation, circumventing the iterative requirements of traditional OPF solvers. This offers a more expedient solution apt for real-time applications. Rigorous evaluations on aggregated European power systems validate our method's superiority over existing data-driven techniques in OPF solving. By presenting a quick, robust, and efficient solution, this research sets a new standard in real-time OPF resolution, paving the way for more resilient power systems in the era of renewable energy.

{{</citation>}}


### (11/79) L(M)V-IQL: Multiple Intention Inverse Reinforcement Learning for Animal Behavior Characterization (Hao Zhu et al., 2023)

{{<citation>}}

Hao Zhu, Brice De La Crompe, Gabriel Kalweit, Artur Schneider, Maria Kalweit, Ilka Diester, Joschka Boedecker. (2023)  
**L(M)V-IQL: Multiple Intention Inverse Reinforcement Learning for Animal Behavior Characterization**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, q-bio-NC  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.13870v1)  

---


**ABSTRACT**  
In advancing the understanding of decision-making processes, mathematical models, particularly Inverse Reinforcement Learning (IRL), have proven instrumental in reconstructing animal's multiple intentions amidst complex behaviors. Given the recent development of a continuous-time multi-intention IRL framework, there has been persistent inquiry into inferring discrete time-varying reward functions with multiple intention IRL approaches. To tackle the challenge, we introduce the Latent (Markov) Variable Inverse Q-learning (L(M)V-IQL) algorithms, a novel IRL framework tailored for accommodating discrete intrinsic rewards. Leveraging an Expectation-Maximization approach, we cluster observed trajectories into distinct intentions and independently solve the IRL problem for each. Demonstrating the efficacy of L(M)V-IQL through simulated experiments and its application to different real mouse behavior datasets, our approach surpasses current benchmarks in animal behavior prediction, producing interpretable reward functions. This advancement holds promise for neuroscience and psychology, contributing to a deeper understanding of animal decision-making and uncovering underlying brain mechanisms.

{{</citation>}}


### (12/79) Exact Combinatorial Optimization with Temporo-Attentional Graph Neural Networks (Mehdi Seyfi et al., 2023)

{{<citation>}}

Mehdi Seyfi, Amin Banitalebi-Dehkordi, Zirui Zhou, Yong Zhang. (2023)  
**Exact Combinatorial Optimization with Temporo-Attentional Graph Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-MS, cs.LG  
Keywords: Attention, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2311.13843v1)  

---


**ABSTRACT**  
Combinatorial optimization finds an optimal solution within a discrete set of variables and constraints. The field has seen tremendous progress both in research and industry. With the success of deep learning in the past decade, a recent trend in combinatorial optimization has been to improve state-of-the-art combinatorial optimization solvers by replacing key heuristic components with machine learning (ML) models. In this paper, we investigate two essential aspects of machine learning algorithms for combinatorial optimization: temporal characteristics and attention. We argue that for the task of variable selection in the branch-and-bound (B&B) algorithm, incorporating the temporal information as well as the bipartite graph attention improves the solver's performance. We support our claims with intuitions and numerical results over several standard datasets used in the literature and competitions. Code is available at: https://developer.huaweicloud.com/develop/aigallery/notebook/detail?id=047c6cf2-8463-40d7-b92f-7b2ca998e935

{{</citation>}}


### (13/79) Molecular Identification and Peak Assignment: Leveraging Multi-Level Multimodal Alignment on NMR (Hao Xu et al., 2023)

{{<citation>}}

Hao Xu, Zhengyang Zhou, Pengyu Hong. (2023)  
**Molecular Identification and Peak Assignment: Leveraging Multi-Level Multimodal Alignment on NMR**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, physics-chem-ph, q-bio-QM  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.13817v1)  

---


**ABSTRACT**  
Nuclear magnetic resonance (NMR) spectroscopy plays an essential role across various scientific disciplines, providing valuable insights into molecular dynamics and interactions. Despite the promise of AI-enhanced NMR prediction models, challenges persist in the interpretation of spectra for tasks such as molecular retrieval, isomer recognition, and peak assignment. In response, this paper introduces Multi-Level Multimodal Alignment with Knowledge-Guided Instance-Wise Discrimination (K-M3AID) to establish meaningful correspondences between two heterogeneous modalities: molecular graphs (structures) and NMR spectra. In particular, K-M3AID employs a dual-coordinated contrastive learning architecture, and incorporates a graph-level alignment module, a node-level alignment module, and a communication channel. Notably, the framework introduces knowledge-guided instance-wise discrimination into contrastive learning within the node-level alignment module, significantly enhancing accuracy in cross-modal alignment. Additionally, K-M3AID showcases its capability of meta-learning by demonstrating that skills acquired during node-level alignment positively impact graph-level alignment. Empirical validation underscores K-M3AID's effectiveness in addressing multiple zero-shot tasks, offering a promising solution to bridge the gap between structural information and spectral data in complex NMR scenarios.

{{</citation>}}


## stat.ML (1)



### (14/79) Annotation Sensitivity: Training Data Collection Methods Affect Model Performance (Christoph Kern et al., 2023)

{{<citation>}}

Christoph Kern, Stephanie Eckman, Jacob Beck, Rob Chew, Bolei Ma, Frauke Kreuter. (2023)  
**Annotation Sensitivity: Training Data Collection Methods Affect Model Performance**  

---
Primary Category: stat.ML  
Categories: cs-CL, cs-LG, stat-ME, stat-ML, stat.ML  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2311.14212v1)  

---


**ABSTRACT**  
When training data are collected from human annotators, the design of the annotation instrument, the instructions given to annotators, the characteristics of the annotators, and their interactions can impact training data. This study demonstrates that design choices made when creating an annotation instrument also impact the models trained on the resulting annotations.   We introduce the term annotation sensitivity to refer to the impact of annotation data collection methods on the annotations themselves and on downstream model performance and predictions.   We collect annotations of hate speech and offensive language in five experimental conditions of an annotation instrument, randomly assigning annotators to conditions. We then fine-tune BERT models on each of the five resulting datasets and evaluate model performance on a holdout portion of each condition. We find considerable differences between the conditions for 1) the share of hate speech/offensive language annotations, 2) model performance, 3) model predictions, and 4) model learning curves.   Our results emphasize the crucial role played by the annotation instrument which has received little attention in the machine learning literature. We call for additional research into how and why the instrument impacts the annotations to inform the development of best practices in instrument design.

{{</citation>}}


## cs.CV (19)



### (15/79) The 2nd Workshop on Maritime Computer Vision (MaCVi) 2024 (Benjamin Kiefer et al., 2023)

{{<citation>}}

Benjamin Kiefer, Lojze Žust, Matej Kristan, Janez Perš, Matija Teršek, Arnold Wiliem, Martin Messmer, Cheng-Yen Yang, Hsiang-Wei Huang, Zhongyu Jiang, Heng-Cheng Kuo, Jie Mei, Jenq-Neng Hwang, Daniel Stadler, Lars Sommer, Kaer Huang, Aiguo Zheng, Weitu Chong, Kanokphan Lertniphonphan, Jun Xie, Feng Chen, Jian Li, Zhepeng Wang, Luca Zedda, Andrea Loddo, Cecilia Di Ruberto, Tuan-Anh Vu, Hai Nguyen-Truong, Tan-Sang Ha, Quan-Dung Pham, Sai-Kit Yeung, Yuan Feng, Nguyen Thanh Thien, Lixin Tian, Sheng-Yao Kuan, Yuan-Hao Ho, Angel Bueno Rodriguez, Borja Carrillo-Perez, Alexander Klein, Antje Alex, Yannik Steiniger, Felix Sattler, Edgardo Solano-Carrillo, Matej Fabijanić, Magdalena Šumunec, Nadir Kapetanović, Andreas Michel, Wolfgang Gross, Martin Weinmann. (2023)  
**The 2nd Workshop on Maritime Computer Vision (MaCVi) 2024**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Computer Vision  
[Paper Link](http://arxiv.org/abs/2311.14762v1)  

---


**ABSTRACT**  
The 2nd Workshop on Maritime Computer Vision (MaCVi) 2024 addresses maritime computer vision for Unmanned Aerial Vehicles (UAV) and Unmanned Surface Vehicles (USV). Three challenges categories are considered: (i) UAV-based Maritime Object Tracking with Re-identification, (ii) USV-based Maritime Obstacle Segmentation and Detection, (iii) USV-based Maritime Boat Tracking. The USV-based Maritime Obstacle Segmentation and Detection features three sub-challenges, including a new embedded challenge addressing efficicent inference on real-world embedded devices. This report offers a comprehensive overview of the findings from the challenges. We provide both statistical and qualitative analyses, evaluating trends from over 195 submissions. All datasets, evaluation code, and the leaderboard are available to the public at https://macvi.org/workshop/macvi24.

{{</citation>}}


### (16/79) Class Balanced Dynamic Acquisition for Domain Adaptive Semantic Segmentation using Active Learning (Marc Schachtsiek et al., 2023)

{{<citation>}}

Marc Schachtsiek, Simone Rossi, Thomas Hannagan. (2023)  
**Class Balanced Dynamic Acquisition for Domain Adaptive Semantic Segmentation using Active Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV, stat-ML  
Keywords: Active Learning, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2311.14146v1)  

---


**ABSTRACT**  
Domain adaptive active learning is leading the charge in label-efficient training of neural networks. For semantic segmentation, state-of-the-art models jointly use two criteria of uncertainty and diversity to select training labels, combined with a pixel-wise acquisition strategy. However, we show that such methods currently suffer from a class imbalance issue which degrades their performance for larger active learning budgets. We then introduce Class Balanced Dynamic Acquisition (CBDA), a novel active learning method that mitigates this issue, especially in high-budget regimes. The more balanced labels increase minority class performance, which in turn allows the model to outperform the previous baseline by 0.6, 1.7, and 2.4 mIoU for budgets of 5%, 10%, and 20%, respectively. Additionally, the focus on minority classes leads to improvements of the minimum class performance of 0.5, 2.9, and 4.6 IoU respectively. The top-performing model even exceeds the fully supervised baseline, showing that a more balanced label than the entire ground truth can be beneficial.

{{</citation>}}


### (17/79) ACT: Adversarial Consistency Models (Fei Kong et al., 2023)

{{<citation>}}

Fei Kong, Jinhao Duan, Lichao Sun, Hao Cheng, Renjing Xu, Hengtao Shen, Xiaofeng Zhu, Xiaoshuang Shi, Kaidi Xu. (2023)  
**ACT: Adversarial Consistency Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2311.14097v1)  

---


**ABSTRACT**  
Though diffusion models excel in image generation, their step-by-step denoising leads to slow generation speeds. Consistency training addresses this issue with single-step sampling but often produces lower-quality generations and requires high training costs. In this paper, we show that optimizing consistency training loss minimizes the Wasserstein distance between target and generated distributions. As timestep increases, the upper bound accumulates previous consistency training losses. Therefore, larger batch sizes are needed to reduce both current and accumulated losses. We propose Adversarial Consistency Training (ACT), which directly minimizes the Jensen-Shannon (JS) divergence between distributions at each timestep using a discriminator. Theoretically, ACT enhances generation quality, and convergence. By incorporating a discriminator into the consistency training framework, our method achieves improved FID scores on CIFAR10 and ImageNet 64$\times$64, retains zero-shot image inpainting capabilities, and uses less than $1/6$ of the original batch size and fewer than $1/2$ of the model parameters and training steps compared to the baseline method, this leads to a substantial reduction in resource consumption.

{{</citation>}}


### (18/79) Video Anomaly Detection using GAN (Anikeit Sethi et al., 2023)

{{<citation>}}

Anikeit Sethi, Krishanu Saini, Sai Mounika Mididoddi. (2023)  
**Video Anomaly Detection using GAN**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2311.14095v1)  

---


**ABSTRACT**  
Accounting for the increased concern for public safety, automatic abnormal event detection and recognition in a surveillance scene is crucial. It is a current open study subject because of its intricacy and utility. The identification of aberrant events automatically, it's a difficult undertaking because everyone's idea of abnormality is different. A typical occurrence in one circumstance could be seen as aberrant in another. Automatic anomaly identification becomes particularly challenging in the surveillance footage with a large crowd due to congestion and high occlusion. With the use of machine learning techniques, this thesis study aims to offer the solution for this use case so that human resources won't be required to keep an eye out for any unusual activity in the surveillance system records. We have developed a novel generative adversarial network (GAN) based anomaly detection model. This model is trained such that it learns together about constructing a high dimensional picture space and determining the latent space from the video's context. The generator uses a residual Autoencoder architecture made up of a multi-stage channel attention-based decoder and a two-stream, deep convolutional encoder that can realise both spatial and temporal data. We have also offered a technique for refining the GAN model that reduces training time while also generalising the model by utilising transfer learning between datasets. Using a variety of assessment measures, we compare our model to the current state-of-the-art techniques on four benchmark datasets. The empirical findings indicate that, in comparison to existing techniques, our network performs favourably on all datasets.

{{</citation>}}


### (19/79) Point2RBox: Combine Knowledge from Synthetic Visual Patterns for End-to-end Oriented Object Detection with Single Point Supervision (Yu Yi et al., 2023)

{{<citation>}}

Yu Yi, Xue Yang, Qingyun Li, Feipeng Da, Junchi Yan, Jifeng Dai, Yu Qiao. (2023)  
**Point2RBox: Combine Knowledge from Synthetic Visual Patterns for End-to-end Oriented Object Detection with Single Point Supervision**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2311.14758v1)  

---


**ABSTRACT**  
With the rapidly increasing demand for oriented object detection (OOD), recent research involving weakly-supervised detectors for learning rotated box (RBox) from the horizontal box (HBox) has attracted more and more attention. In this paper, we explore a more challenging yet label-efficient setting, namely single point-supervised OOD, and present our approach called Point2RBox. Specifically, we propose to leverage two principles: 1) Synthetic pattern knowledge combination: By sampling around each labelled point on the image, we transfer the object feature to synthetic visual patterns with the known bounding box to provide the knowledge for box regression. 2) Transform self-supervision: With a transformed input image (e.g. scaled/rotated), the output RBoxes are trained to follow the same transformation so that the network can perceive the relative size/rotation between objects. The detector is further enhanced by a few devised techniques to cope with peripheral issues, e.g. the anchor/layer assignment as the size of the object is not available in our point supervision setting. To our best knowledge, Point2RBox is the first end-to-end solution for point-supervised OOD. In particular, our method uses a lightweight paradigm, yet it achieves a competitive performance among point-supervised alternatives, 41.05%/27.62%/80.01% on DOTA/DIOR/HRSC datasets.

{{</citation>}}


### (20/79) PointOBB: Learning Oriented Object Detection via Single Point Supervision (Junwei Luo et al., 2023)

{{<citation>}}

Junwei Luo, Xue Yang, Yi Yu, Qingyun Li, Junchi Yan, Yansheng Li. (2023)  
**PointOBB: Learning Oriented Object Detection via Single Point Supervision**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2311.14757v1)  

---


**ABSTRACT**  
Single point-supervised object detection is gaining attention due to its cost-effectiveness. However, existing approaches focus on generating horizontal bounding boxes (HBBs) while ignoring oriented bounding boxes (OBBs) commonly used for objects in aerial images. This paper proposes PointOBB, the first single Point-based OBB generation method, for oriented object detection. PointOBB operates through the collaborative utilization of three distinctive views: an original view, a resized view, and a rotated/flipped (rot/flp) view. Upon the original view, we leverage the resized and rot/flp views to build a scale augmentation module and an angle acquisition module, respectively. In the former module, a Scale-Sensitive Consistency (SSC) loss is designed to enhance the deep network's ability to perceive the object scale. For accurate object angle predictions, the latter module incorporates self-supervised learning to predict angles, which is associated with a scale-guided Dense-to-Sparse (DS) matching strategy for aggregating dense angles corresponding to sparse objects. The resized and rot/flp views are switched using a progressive multi-view switching strategy during training to achieve coupled optimization of scale and angle. Experimental results on the DIOR-R and DOTA-v1.0 datasets demonstrate that PointOBB achieves promising performance, and significantly outperforms potential point-supervised baselines.

{{</citation>}}


### (21/79) HGCLIP: Exploring Vision-Language Models with Graph Representations for Hierarchical Understanding (Peng Xia et al., 2023)

{{<citation>}}

Peng Xia, Xingtong Yu, Ming Hu, Lie Ju, Zhiyong Wang, Peibo Duan, Zongyuan Ge. (2023)  
**HGCLIP: Exploring Vision-Language Models with Graph Representations for Hierarchical Understanding**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.14064v1)  

---


**ABSTRACT**  
Object categories are typically organized into a multi-granularity taxonomic hierarchy. When classifying categories at different hierarchy levels, traditional uni-modal approaches focus primarily on image features, revealing limitations in complex scenarios. Recent studies integrating Vision-Language Models (VLMs) with class hierarchies have shown promise, yet they fall short of fully exploiting the hierarchical relationships. These efforts are constrained by their inability to perform effectively across varied granularity of categories. To tackle this issue, we propose a novel framework (HGCLIP) that effectively combines CLIP with a deeper exploitation of the Hierarchical class structure via Graph representation learning. We explore constructing the class hierarchy into a graph, with its nodes representing the textual or image features of each category. After passing through a graph encoder, the textual features incorporate hierarchical structure information, while the image features emphasize class-aware features derived from prototypes through the attention mechanism. Our approach demonstrates significant improvements on both generic and fine-grained visual recognition benchmarks. Our codes are fully available at https://github.com/richard-peng-xia/HGCLIP.

{{</citation>}}


### (22/79) Hardware Resilience Properties of Text-Guided Image Classifiers (Syed Talal Wasim et al., 2023)

{{<citation>}}

Syed Talal Wasim, Kabila Haile Saboka, Abdulrahman Mahmoud, Salman Khan, David Brooks, Gu-Yeon Wei. (2023)  
**Hardware Resilience Properties of Text-Guided Image Classifiers**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: GPT  
[Paper Link](http://arxiv.org/abs/2311.14062v1)  

---


**ABSTRACT**  
This paper presents a novel method to enhance the reliability of image classification models during deployment in the face of transient hardware errors. By utilizing enriched text embeddings derived from GPT-3 with question prompts per class and CLIP pretrained text encoder, we investigate their impact as an initialization for the classification layer. Our approach achieves a remarkable $5.5\times$ average increase in hardware reliability (and up to 14x) across various architectures in the most critical layer, with minimal accuracy drop (0.3% on average) compared to baseline PyTorch models. Furthermore, our method seamlessly integrates with any image classification backbone, showcases results across various network architectures, decreases parameter and FLOPs overhead, and follows a consistent training recipe. This research offers a practical and efficient solution to bolster the robustness of image classification models against hardware failures, with potential implications for future studies in this domain. Our code and models are released at https://github.com/TalalWasim/TextGuidedResilience.

{{</citation>}}


### (23/79) EIGEN: Expert-Informed Joint Learning Aggregation for High-Fidelity Information Extraction from Document Images (Abhishek Singh et al., 2023)

{{<citation>}}

Abhishek Singh, Venkatapathy Subramanian, Ayush Maheshwari, Pradeep Narayan, Devi Prasad Shetty, Ganesh Ramakrishnan. (2023)  
**EIGEN: Expert-Informed Joint Learning Aggregation for High-Fidelity Information Extraction from Document Images**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Information Extraction  
[Paper Link](http://arxiv.org/abs/2311.13993v1)  

---


**ABSTRACT**  
Information Extraction (IE) from document images is challenging due to the high variability of layout formats. Deep models such as LayoutLM and BROS have been proposed to address this problem and have shown promising results. However, they still require a large amount of field-level annotations for training these models. Other approaches using rule-based methods have also been proposed based on the understanding of the layout and semantics of a form such as geometric position, or type of the fields, etc. In this work, we propose a novel approach, EIGEN (Expert-Informed Joint Learning aGgrEatioN), which combines rule-based methods with deep learning models using data programming approaches to circumvent the requirement of annotation of large amounts of training data. Specifically, EIGEN consolidates weak labels induced from multiple heuristics through generative models and use them along with a small number of annotated labels to jointly train a deep model. In our framework, we propose the use of labeling functions that include incorporating contextual information thus capturing the visual and language context of a word for accurate categorization. We empirically show that our EIGEN framework can significantly improve the performance of state-of-the-art deep models with the availability of very few labeled data instances. The source code is available at https://github.com/ayushayush591/EIGEN-High-Fidelity-Extraction-Document-Images.

{{</citation>}}


### (24/79) Robustness-Reinforced Knowledge Distillation with Correlation Distance and Network Pruning (Seonghak Kim et al., 2023)

{{<citation>}}

Seonghak Kim, Gyeongdo Ham, Yucheol Cho, Daeshik Kim. (2023)  
**Robustness-Reinforced Knowledge Distillation with Correlation Distance and Network Pruning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet, Knowledge Distillation, Pruning  
[Paper Link](http://arxiv.org/abs/2311.13934v1)  

---


**ABSTRACT**  
The improvement in the performance of efficient and lightweight models (i.e., the student model) is achieved through knowledge distillation (KD), which involves transferring knowledge from more complex models (i.e., the teacher model). However, most existing KD techniques rely on Kullback-Leibler (KL) divergence, which has certain limitations. First, if the teacher distribution has high entropy, the KL divergence's mode-averaging nature hinders the transfer of sufficient target information. Second, when the teacher distribution has low entropy, the KL divergence tends to excessively focus on specific modes, which fails to convey an abundant amount of valuable knowledge to the student. Consequently, when dealing with datasets that contain numerous confounding or challenging samples, student models may struggle to acquire sufficient knowledge, resulting in subpar performance. Furthermore, in previous KD approaches, we observed that data augmentation, a technique aimed at enhancing a model's generalization, can have an adverse impact. Therefore, we propose a Robustness-Reinforced Knowledge Distillation (R2KD) that leverages correlation distance and network pruning. This approach enables KD to effectively incorporate data augmentation for performance improvement. Extensive experiments on various datasets, including CIFAR-100, FGVR, TinyImagenet, and ImageNet, demonstrate our method's superiority over current state-of-the-art methods.

{{</citation>}}


### (25/79) Periodically Exchange Teacher-Student for Source-Free Object Detection (Qipeng Liu et al., 2023)

{{<citation>}}

Qipeng Liu, Luojun Lin, Zhifeng Shen, Zhifeng Yang. (2023)  
**Periodically Exchange Teacher-Student for Source-Free Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2311.13930v1)  

---


**ABSTRACT**  
Source-free object detection (SFOD) aims to adapt the source detector to unlabeled target domain data in the absence of source domain data. Most SFOD methods follow the same self-training paradigm using mean-teacher (MT) framework where the student model is guided by only one single teacher model. However, such paradigm can easily fall into a training instability problem that when the teacher model collapses uncontrollably due to the domain shift, the student model also suffers drastic performance degradation. To address this issue, we propose the Periodically Exchange Teacher-Student (PETS) method, a simple yet novel approach that introduces a multiple-teacher framework consisting of a static teacher, a dynamic teacher, and a student model. During the training phase, we periodically exchange the weights between the static teacher and the student model. Then, we update the dynamic teacher using the moving average of the student model that has already been exchanged by the static teacher. In this way, the dynamic teacher can integrate knowledge from past periods, effectively reducing error accumulation and enabling a more stable training process within the MT-based framework. Further, we develop a consensus mechanism to merge the predictions of two teacher models to provide higher-quality pseudo labels for student model. Extensive experiments on multiple SFOD benchmarks show that the proposed method achieves state-of-the-art performance compared with other related methods, demonstrating the effectiveness and superiority of our method on SFOD task.

{{</citation>}}


### (26/79) Attribute-Aware Representation Rectification for Generalized Zero-Shot Learning (Zhijie Rao et al., 2023)

{{<citation>}}

Zhijie Rao, Jingcai Guo, Xiaocheng Lu, Qihua Zhou, Jie Zhang, Kang Wei, Chenxin Li, Song Guo. (2023)  
**Attribute-Aware Representation Rectification for Generalized Zero-Shot Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2311.14750v1)  

---


**ABSTRACT**  
Generalized Zero-shot Learning (GZSL) has yielded remarkable performance by designing a series of unbiased visual-semantics mappings, wherein, the precision relies heavily on the completeness of extracted visual features from both seen and unseen classes. However, as a common practice in GZSL, the pre-trained feature extractor may easily exhibit difficulty in capturing domain-specific traits of the downstream tasks/datasets to provide fine-grained discriminative features, i.e., domain bias, which hinders the overall recognition performance, especially for unseen classes. Recent studies partially address this issue by fine-tuning feature extractors, while may inevitably incur catastrophic forgetting and overfitting issues. In this paper, we propose a simple yet effective Attribute-Aware Representation Rectification framework for GZSL, dubbed $\mathbf{(AR)^{2}}$, to adaptively rectify the feature extractor to learn novel features while keeping original valuable features. Specifically, our method consists of two key components, i.e., Unseen-Aware Distillation (UAD) and Attribute-Guided Learning (AGL). During training, UAD exploits the prior knowledge of attribute texts that are shared by both seen/unseen classes with attention mechanisms to detect and maintain unseen class-sensitive visual features in a targeted manner, and meanwhile, AGL aims to steer the model to focus on valuable features and suppress them to fit noisy elements in the seen classes by attribute-guided representation learning. Extensive experiments on various benchmark datasets demonstrate the effectiveness of our method.

{{</citation>}}


### (27/79) PointPCA+: Extending PointPCA objective quality assessment metric (Xuemei Zhou et al., 2023)

{{<citation>}}

Xuemei Zhou, Evangelos Alexiou, Irene Viola, Pablo Cesar. (2023)  
**PointPCA+: Extending PointPCA objective quality assessment metric**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV, eess-IV  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2311.13880v1)  

---


**ABSTRACT**  
A computationally-simplified and descriptor-richer Point Cloud Quality Assessment (PCQA) metric, namely PointPCA+, is proposed in this paper, which is an extension of PointPCA. PointPCA proposed a set of perceptually-relevant descriptors based on PCA decomposition that were applied to both the geometry and texture data of point clouds for full reference PCQA. PointPCA+ employs PCA only on the geometry data while enriching existing geometry and texture descriptors, that are computed more efficiently. Similarly to PointPCA, a total quality score is obtained through a learning-based fusion of individual predictions from geometry and texture descriptors that capture local shape and appearance properties, respectively. Before feature fusion, a feature selection module is introduced to choose the most effective features from a proposed super-set. Experimental results show that PointPCA+ achieves high predictive performance against subjective ground truth scores obtained from publicly available datasets. The code is available at \url{https://github.com/cwi-dis/pointpca_suite/}.

{{</citation>}}


### (28/79) Language-guided Few-shot Semantic Segmentation (Jing Wang et al., 2023)

{{<citation>}}

Jing Wang, Yuang Liu, Qiang Zhou, Fan Wang. (2023)  
**Language-guided Few-shot Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2311.13865v1)  

---


**ABSTRACT**  
Few-shot learning is a promising way for reducing the label cost in new categories adaptation with the guidance of a small, well labeled support set. But for few-shot semantic segmentation, the pixel-level annotations of support images are still expensive. In this paper, we propose an innovative solution to tackle the challenge of few-shot semantic segmentation using only language information, i.e.image-level text labels. Our approach involves a vision-language-driven mask distillation scheme, which contains a vision-language pretraining (VLP) model and a mask refiner, to generate high quality pseudo-semantic masks from text prompts. We additionally introduce a distributed prototype supervision method and complementary correlation matching module to guide the model in digging precise semantic relations among support and query images. The experiments on two benchmark datasets demonstrate that our method establishes a new baseline for language-guided few-shot semantic segmentation and achieves competitive results to recent vision-guided methods.

{{</citation>}}


### (29/79) Progressive Learning with Visual Prompt Tuning for Variable-Rate Image Compression (Shiyu Qin et al., 2023)

{{<citation>}}

Shiyu Qin, Yimin Zhou, Jinpeng Wang, Bin Chen, Baoyi An, Tao Dai, Shu-Tao Xia. (2023)  
**Progressive Learning with Visual Prompt Tuning for Variable-Rate Image Compression**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-IT, cs.CV, math-IT  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2311.13846v2)  

---


**ABSTRACT**  
In this paper, we propose a progressive learning paradigm for transformer-based variable-rate image compression. Our approach covers a wide range of compression rates with the assistance of the Layer-adaptive Prompt Module (LPM). Inspired by visual prompt tuning, we use LPM to extract prompts for input images and hidden features at the encoder side and decoder side, respectively, which are fed as additional information into the Swin Transformer layer of a pre-trained transformer-based image compression model to affect the allocation of attention region and the bits, which in turn changes the target compression ratio of the model. To ensure the network is more lightweight, we involves the integration of prompt networks with less convolutional layers. Exhaustive experiments show that compared to methods based on multiple models, which are optimized separately for different target rates, the proposed method arrives at the same performance with 80% savings in parameter storage and 90% savings in datasets. Meanwhile, our model outperforms all current variable bitrate image methods in terms of rate-distortion performance and approaches the state-of-the-art fixed bitrate image compression methods trained from scratch.

{{</citation>}}


### (30/79) HOMOE: A Memory-Based and Composition-Aware Framework for Zero-Shot Learning with Hopfield Network and Soft Mixture of Experts (Do Huu Dat et al., 2023)

{{<citation>}}

Do Huu Dat, Po Yuan Mao, Tien Hoang Nguyen, Wray Buntine, Mohammed Bennamoun. (2023)  
**HOMOE: A Memory-Based and Composition-Aware Framework for Zero-Shot Learning with Hopfield Network and Soft Mixture of Experts**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2311.14747v1)  

---


**ABSTRACT**  
Compositional Zero-Shot Learning (CZSL) has emerged as an essential paradigm in machine learning, aiming to overcome the constraints of traditional zero-shot learning by incorporating compositional thinking into its methodology. Conventional zero-shot learning has difficulty managing unfamiliar combinations of seen and unseen classes because it depends on pre-defined class embeddings. In contrast, Compositional Zero-Shot Learning uses the inherent hierarchies and structural connections among classes, creating new class representations by combining attributes, components, or other semantic elements. In our paper, we propose a novel framework that for the first time combines the Modern Hopfield Network with a Mixture of Experts (HOMOE) to classify the compositions of previously unseen objects. Specifically, the Modern Hopfield Network creates a memory that stores label prototypes and identifies relevant labels for a given input image. Following this, the Mixture of Expert models integrates the image with the fitting prototype to produce the final composition classification. Our approach achieves SOTA performance on several benchmarks, including MIT-States and UT-Zappos. We also examine how each component contributes to improved generalization.

{{</citation>}}


### (31/79) All in One: RGB, RGB-D, and RGB-T Salient Object Detection (Xingzhao Jia et al., 2023)

{{<citation>}}

Xingzhao Jia, Zhongqiu Zhao, Changlei Dongye, Zhao Zhang. (2023)  
**All in One: RGB, RGB-D, and RGB-T Salient Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2311.14746v1)  

---


**ABSTRACT**  
Salient object detection (SOD) aims to identify the most attractive objects within an image. Depending on the type of data being detected, SOD can be categorized into various forms, including RGB, RGB-D (Depth), RGB-T (Thermal) and light field SOD. Previous researches have focused on saliency detection with individual data type. If the RGB-D SOD model is forced to detect RGB-T data it will perform poorly. We propose an innovative model framework that provides a unified solution for the salient object detection task of three types of data (RGB, RGB-D, and RGB-T). The three types of data can be handled in one model (all in one) with the same weight parameters. In this framework, the three types of data are concatenated in an ordered manner within a single input batch, and features are extracted using a transformer network. Based on this framework, we propose an efficient lightweight SOD model, namely AiOSOD, which can detect any RGB, RGB-D, and RGB-T data with high speed (780FPS for RGB data, 485FPS for RGB-D or RGB-T data). Notably, with only 6.25M parameters, AiOSOD achieves excellent performance on RGB, RGB-D, and RGB-T datasets.

{{</citation>}}


### (32/79) Dynamic Compositional Graph Convolutional Network for Efficient Composite Human Motion Prediction (Wanying Zhang et al., 2023)

{{<citation>}}

Wanying Zhang, Shen Zhao, Fanyang Meng, Songtao Wu, Mengyuan Liu. (2023)  
**Dynamic Compositional Graph Convolutional Network for Efficient Composite Human Motion Prediction**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Graph Convolutional Network  
[Paper Link](http://arxiv.org/abs/2311.13781v1)  

---


**ABSTRACT**  
With potential applications in fields including intelligent surveillance and human-robot interaction, the human motion prediction task has become a hot research topic and also has achieved high success, especially using the recent Graph Convolutional Network (GCN). Current human motion prediction task usually focuses on predicting human motions for atomic actions. Observing that atomic actions can happen at the same time and thus formulating the composite actions, we propose the composite human motion prediction task. To handle this task, we first present a Composite Action Generation (CAG) module to generate synthetic composite actions for training, thus avoiding the laborious work of collecting composite action samples. Moreover, we alleviate the effect of composite actions on demand for a more complicated model by presenting a Dynamic Compositional Graph Convolutional Network (DC-GCN). Extensive experiments on the Human3.6M dataset and our newly collected CHAMP dataset consistently verify the efficiency of our DC-GCN method, which achieves state-of-the-art motion prediction accuracies and meanwhile needs few extra computational costs than traditional GCN-based human motion methods.

{{</citation>}}


### (33/79) Towards Transferable Multi-modal Perception Representation Learning for Autonomy: NeRF-Supervised Masked AutoEncoder (Xiaohao Xu, 2023)

{{<citation>}}

Xiaohao Xu. (2023)  
**Towards Transferable Multi-modal Perception Representation Learning for Autonomy: NeRF-Supervised Masked AutoEncoder**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs-RO, cs.CV  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2311.13750v1)  

---


**ABSTRACT**  
This work proposes a unified self-supervised pre-training framework for transferable multi-modal perception representation learning via masked multi-modal reconstruction in Neural Radiance Field (NeRF), namely NeRF-Supervised Masked AutoEncoder (NS-MAE). Specifically, conditioned on certain view directions and locations, multi-modal embeddings extracted from corrupted multi-modal input signals, i.e., Lidar point clouds and images, are rendered into projected multi-modal feature maps via neural rendering. Then, original multi-modal signals serve as reconstruction targets for the rendered multi-modal feature maps to enable self-supervised representation learning. Extensive experiments show that the representation learned via NS-MAE shows promising transferability for diverse multi-modal and single-modal (camera-only and Lidar-only) perception models on diverse 3D perception downstream tasks (3D object detection and BEV map segmentation) with diverse amounts of fine-tuning labeled data. Moreover, we empirically find that NS-MAE enjoys the synergy of both the mechanism of masked autoencoder and neural radiance field. Our code shall be released upon acceptance.

{{</citation>}}


## cs.SI (1)



### (34/79) Prebunking Design as a Defense Mechanism Against Misinformation Propagation on Social Networks (Yigit Ege Bayiz et al., 2023)

{{<citation>}}

Yigit Ege Bayiz, Ufuk Topcu. (2023)  
**Prebunking Design as a Defense Mechanism Against Misinformation Propagation on Social Networks**  

---
Primary Category: cs.SI  
Categories: cs-SI, cs-SY, cs.SI, eess-SY  
Keywords: Social Network  
[Paper Link](http://arxiv.org/abs/2311.14200v1)  

---


**ABSTRACT**  
The growing reliance on social media for news consumption necessitates effective countermeasures to mitigate the rapid spread of misinformation. Prebunking, a proactive method that arms users with accurate information before they come across false content, has garnered support from journalism and psychology experts. We formalize the problem of optimal prebunking as optimizing the timing of delivering accurate information, ensuring users encounter it before receiving misinformation while minimizing the disruption to user experience. Utilizing a susceptible-infected epidemiological process to model the propagation of misinformation, we frame optimal prebunking as a policy synthesis problem with safety constraints. We then propose a policy that approximates the optimal solution to a relaxed problem. The experiments show that this policy cuts the user experience cost of repeated information delivery in half, compared to delivering accurate information immediately after identifying a misinformation propagation.

{{</citation>}}


## cs.CL (17)



### (35/79) Evaluating GPT-4's Vision Capabilities on Brazilian University Admission Exams (Ramon Pires et al., 2023)

{{<citation>}}

Ramon Pires, Thales Sales Almeida, Hugo Abonizio, Rodrigo Nogueira. (2023)  
**Evaluating GPT-4's Vision Capabilities on Brazilian University Admission Exams**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2311.14169v1)  

---


**ABSTRACT**  
Recent advancements in language models have showcased human-comparable performance in academic entrance exams. However, existing studies often overlook questions that require the integration of visual comprehension, thus compromising the full spectrum and complexity inherent in real-world scenarios. To address this gap, we present a comprehensive framework to evaluate language models on entrance exams, which incorporates both textual and visual elements. We evaluate the two most recent editions of Exame Nacional do Ensino M\'edio (ENEM), the main standardized entrance examination adopted by Brazilian universities. Our study not only reaffirms the capabilities of GPT-4 as the state of the art for handling complex multidisciplinary questions, but also pioneers in offering a realistic assessment of multimodal language models on Portuguese examinations. One of the highlights is that text captions transcribing visual content outperform the direct use of images, suggesting that the vision model has room for improvement. Yet, despite improvements afforded by images or captions, mathematical questions remain a challenge for these state-of-the-art models. The code and data used on experiments are available at https://github.com/piresramon/gpt-4-enem.

{{</citation>}}


### (36/79) Towards Auditing Large Language Models: Improving Text-based Stereotype Detection (Wu Zekun et al., 2023)

{{<citation>}}

Wu Zekun, Sahan Bulathwela, Adriano Soares Koshiyama. (2023)  
**Towards Auditing Large Language Models: Improving Text-based Stereotype Detection**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-CY, cs-LG, cs.CL  
Keywords: AI, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2311.14126v1)  

---


**ABSTRACT**  
Large Language Models (LLM) have made significant advances in the recent past becoming more mainstream in Artificial Intelligence (AI) enabled human-facing applications. However, LLMs often generate stereotypical output inherited from historical data, amplifying societal biases and raising ethical concerns. This work introduces i) the Multi-Grain Stereotype Dataset, which includes 52,751 instances of gender, race, profession and religion stereotypic text and ii) a novel stereotype classifier for English text. We design several experiments to rigorously test the proposed model trained on the novel dataset. Our experiments show that training the model in a multi-class setting can outperform the one-vs-all binary counterpart. Consistent feature importance signals from different eXplainable AI tools demonstrate that the new model exploits relevant text features. We utilise the newly created model to assess the stereotypic behaviour of the popular GPT family of models and observe the reduction of bias over time. In summary, our work establishes a robust and practical framework for auditing and evaluating the stereotypic bias in LLM.

{{</citation>}}


### (37/79) Auditing and Mitigating Cultural Bias in LLMs (Yan Tao et al., 2023)

{{<citation>}}

Yan Tao, Olga Viberg, Ryan S. Baker, Rene F. Kizilcec. (2023)  
**Auditing and Mitigating Cultural Bias in LLMs**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Bias, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2311.14096v1)  

---


**ABSTRACT**  
Culture fundamentally shapes people's reasoning, behavior, and communication. Generative artificial intelligence (AI) technologies may cause a shift towards a dominant culture. As people increasingly use AI to expedite and even automate various professional and personal tasks, cultural values embedded in AI models may bias authentic expression. We audit large language models for cultural bias, comparing their responses to nationally representative survey data, and evaluate country-specific prompting as a mitigation strategy. We find that GPT-4, 3.5 and 3 exhibit cultural values resembling English-speaking and Protestant European countries. Our mitigation strategy reduces cultural bias in recent models but not for all countries/territories. To avoid cultural bias in generative AI, especially in high-stakes contexts, we suggest using culture matching and ongoing cultural audits.

{{</citation>}}


### (38/79) Question Answering in Natural Language: the Special Case of Temporal Expressions (Armand Stricker, 2023)

{{<citation>}}

Armand Stricker. (2023)  
**Question Answering in Natural Language: the Special Case of Temporal Expressions**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Question Answering  
[Paper Link](http://arxiv.org/abs/2311.14087v1)  

---


**ABSTRACT**  
Although general question answering has been well explored in recent years, temporal question answering is a task which has not received as much focus. Our work aims to leverage a popular approach used for general question answering, answer extraction, in order to find answers to temporal questions within a paragraph. To train our model, we propose a new dataset, inspired by SQuAD, specifically tailored to provide rich temporal information. We chose to adapt the corpus WikiWars, which contains several documents on history's greatest conflicts. Our evaluation shows that a deep learning model trained to perform pattern matching, often used in general question answering, can be adapted to temporal question answering, if we accept to ask questions whose answers must be directly present within a text.

{{</citation>}}


### (39/79) Searching for Snippets of Open-Domain Dialogue in Task-Oriented Dialogue Datasets (Armand Stricker et al., 2023)

{{<citation>}}

Armand Stricker, Patrick Paroubek. (2023)  
**Searching for Snippets of Open-Domain Dialogue in Task-Oriented Dialogue Datasets**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue  
[Paper Link](http://arxiv.org/abs/2311.14076v1)  

---


**ABSTRACT**  
Most existing dialogue corpora and models have been designed to fit into 2 predominant categories : task-oriented dialogues portray functional goals, such as making a restaurant reservation or booking a plane ticket, while chit-chat/open-domain dialogues focus on holding a socially engaging talk with a user. However, humans tend to seamlessly switch between modes and even use chitchat to enhance task-oriented conversations. To bridge this gap, new datasets have recently been created, blending both communication modes into conversation examples. The approaches used tend to rely on adding chit-chat snippets to pre-existing, human-generated task-oriented datasets. Given the tendencies observed in humans, we wonder however if the latter do not \textit{already} hold chit-chat sequences. By using topic modeling and searching for topics which are most similar to a set of keywords related to social talk, we explore the training sets of Schema-Guided Dialogues and MultiWOZ. Our study shows that sequences related to social talk are indeed naturally present, motivating further research on ways chitchat is combined into task-oriented dialogues.

{{</citation>}}


### (40/79) Enhancing Task-Oriented Dialogues with Chitchat: a Comparative Study Based on Lexical Diversity and Divergence (Armand Stricker et al., 2023)

{{<citation>}}

Armand Stricker, Patrick Paroubek. (2023)  
**Enhancing Task-Oriented Dialogues with Chitchat: a Comparative Study Based on Lexical Diversity and Divergence**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue  
[Paper Link](http://arxiv.org/abs/2311.14067v1)  

---


**ABSTRACT**  
As a recent development, task-oriented dialogues (TODs) have been enriched with chitchat in an effort to make dialogues more diverse and engaging. This enhancement is particularly valuable as TODs are often confined to narrow domains, making the mitigation of repetitive and predictable responses a significant challenge. This paper presents a comparative analysis of three chitchat enhancements, aiming to identify the most effective approach in terms of diversity. Additionally, we quantify the divergence between the added chitchat, the original task-oriented language, and chitchat typically found in chitchat datasets, highlighting the top 20 divergent keywords for each comparison. Our findings drive a discussion on future enhancements for augmenting TODs, emphasizing the importance of grounding dialogues beyond the task to achieve more diverse and natural exchanges.

{{</citation>}}


### (41/79) Probabilistic Tree-of-thought Reasoning for Answering Knowledge-intensive Complex Questions (Shulin Cao et al., 2023)

{{<citation>}}

Shulin Cao, Jiajie Zhang, Jiaxin Shi, Xin Lv, Zijun Yao, Qi Tian, Juanzi Li, Lei Hou. (2023)  
**Probabilistic Tree-of-thought Reasoning for Answering Knowledge-intensive Complex Questions**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: QA, Reasoning  
[Paper Link](http://arxiv.org/abs/2311.13982v1)  

---


**ABSTRACT**  
Large language models (LLMs) are capable of answering knowledge-intensive complex questions with chain-of-thought (CoT) reasoning. However, they tend to generate factually incorrect reasoning steps when the required knowledge is not available or up-to-date in models' parameters. Recent works turn to retrieving external knowledge to augment CoT reasoning. Despite being promising, these chain-based methods suffer from: 1) Negative retrieval. Unnecessary or incorrect retrieval may mislead the reasoning; 2) Limited sight. Lacking the ability to look backward or forward, a local error in one step will propagate along the chain.   In this paper, we propose a novel approach: Probabilistic Tree-of-thought Reasoning (ProbTree). First, LLMs translate a complex question into a query tree, in which each non-root node denotes a sub-question of its parent node. Then, probabilistic reasoning is conducted over the tree, by solving questions from leaf to root considering the confidence of both question decomposing and answering. During reasoning, for leaf nodes, LLMs choose a more confident answer from Closed-book QA that employs parametric knowledge and Open-book QA that employs retrieved external knowledge, thus eliminating the negative retrieval problem. For non-leaf nodes, with the hierarchical structure, LLMs have broader sights and are able to globally reason with the information from child nodes, thus recovering from local errors. The experiments on three Complex QA datasets under the open-domain setting show that our approach outperforms SOTA methods significantly, demonstrating the effect of probabilistic tree-of-thought reasoning.

{{</citation>}}


### (42/79) MLLM-Bench, Evaluating Multi-modal LLMs using GPT-4V (Wentao Ge et al., 2023)

{{<citation>}}

Wentao Ge, Shunian Chen, Guiming Chen, Junying Chen, Zhihong Chen, Shuo Yan, Chenghao Zhu, Ziyue Lin, Wenya Xie, Xidong Wang, Anningzhe Gao, Zhiyi Zhang, Jianquan Li, Xiang Wan, Benyou Wang. (2023)  
**MLLM-Bench, Evaluating Multi-modal LLMs using GPT-4V**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2311.13951v1)  

---


**ABSTRACT**  
In the pursuit of Artificial General Intelligence (AGI), the integration of vision in language models has marked a significant milestone. The advent of vision-language models (MLLMs) like GPT-4V have expanded AI applications, aligning with the multi-modal capabilities of the human brain. However, evaluating the efficacy of MLLMs poses a substantial challenge due to the subjective nature of tasks that lack definitive answers. Existing automatic evaluation methodologies on multi-modal large language models rely on objective queries that have standard answers, inadequately addressing the nuances of creative and associative multi-modal tasks. To address this, we introduce MLLM-Bench, an innovative benchmark inspired by Vicuna, spanning a diverse array of scenarios, including Perception, Understanding, Applying, Analyzing, Evaluating, and Creation along with the ethical consideration. MLLM-Bench is designed to reflect user experience more accurately and provide a more holistic assessment of model performance. Comparative evaluations indicate a significant performance gap between existing open-source models and GPT-4V. We posit that MLLM-Bench will catalyze progress in the open-source community towards developing user-centric vision-language models that meet a broad spectrum of real-world applications. See online leaderboard in \url{https://mllm-bench.llmzoo.com}.

{{</citation>}}


### (43/79) Exploring Methods for Cross-lingual Text Style Transfer: The Case of Text Detoxification (Daryna Dementieva et al., 2023)

{{<citation>}}

Daryna Dementieva, Daniil Moskovskiy, David Dale, Alexander Panchenko. (2023)  
**Exploring Methods for Cross-lingual Text Style Transfer: The Case of Text Detoxification**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Style Transfer  
[Paper Link](http://arxiv.org/abs/2311.13937v1)  

---


**ABSTRACT**  
Text detoxification is the task of transferring the style of text from toxic to neutral. While here are approaches yielding promising results in monolingual setup, e.g., (Dale et al., 2021; Hallinan et al., 2022), cross-lingual transfer for this task remains a challenging open problem (Moskovskiy et al., 2022). In this work, we present a large-scale study of strategies for cross-lingual text detoxification -- given a parallel detoxification corpus for one language; the goal is to transfer detoxification ability to another language for which we do not have such a corpus. Moreover, we are the first to explore a new task where text translation and detoxification are performed simultaneously, providing several strong baselines for this task. Finally, we introduce new automatic detoxification evaluation metrics with higher correlations with human judgments than previous benchmarks. We assess the most promising approaches also with manual markup, determining the answer for the best strategy to transfer the knowledge of text detoxification between languages.

{{</citation>}}


### (44/79) Some Like It Small: Czech Semantic Embedding Models for Industry Applications (Jiří Bednář et al., 2023)

{{<citation>}}

Jiří Bednář, Jakub Náplava, Petra Barančíková, Ondřej Lisický. (2023)  
**Some Like It Small: Czech Semantic Embedding Models for Industry Applications**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-IR, cs.CL  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2311.13921v1)  

---


**ABSTRACT**  
This article focuses on the development and evaluation of Small-sized Czech sentence embedding models. Small models are important components for real-time industry applications in resource-constrained environments. Given the limited availability of labeled Czech data, alternative approaches, including pre-training, knowledge distillation, and unsupervised contrastive fine-tuning, are investigated. Comprehensive intrinsic and extrinsic analyses are conducted, showcasing the competitive performance of our models compared to significantly larger counterparts, with approximately 8 times smaller size and 5 times faster speed than conventional Base-sized models. To promote cooperation and reproducibility, both the models and the evaluation pipeline are made publicly accessible. Ultimately, this article presents practical applications of the developed sentence embedding models in Seznam.cz, the Czech search engine. These models have effectively replaced previous counterparts, enhancing the overall search experience for instance, in organic search, featured snippets, and image search. This transition has yielded improved performance.

{{</citation>}}


### (45/79) Dialogue Quality and Emotion Annotations for Customer Support Conversations (John Mendonça et al., 2023)

{{<citation>}}

John Mendonça, Patrícia Pereira, Miguel Menezes, Vera Cabarrão, Ana C. Farinha, Helena Moniz, João Paulo Carvalho, Alon Lavie, Isabel Trancoso. (2023)  
**Dialogue Quality and Emotion Annotations for Customer Support Conversations**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue, Emotion Recognition, Language Model  
[Paper Link](http://arxiv.org/abs/2311.13910v1)  

---


**ABSTRACT**  
Task-oriented conversational datasets often lack topic variability and linguistic diversity. However, with the advent of Large Language Models (LLMs) pretrained on extensive, multilingual and diverse text data, these limitations seem overcome. Nevertheless, their generalisability to different languages and domains in dialogue applications remains uncertain without benchmarking datasets. This paper presents a holistic annotation approach for emotion and conversational quality in the context of bilingual customer support conversations. By performing annotations that take into consideration the complete instances that compose a conversation, one can form a broader perspective of the dialogue as a whole. Furthermore, it provides a unique and valuable resource for the development of text classification models. To this end, we present benchmarks for Emotion Recognition and Dialogue Quality Estimation and show that further research is needed to leverage these models in a production setting.

{{</citation>}}


### (46/79) General Phrase Debiaser: Debiasing Masked Language Models at a Multi-Token Level (Bingkang Shi et al., 2023)

{{<citation>}}

Bingkang Shi, Xiaodan Zhang, Dehan Kong, Yulei Wu, Zongzhen Liu, Honglei Lyu, Longtao Huang. (2023)  
**General Phrase Debiaser: Debiasing Masked Language Models at a Multi-Token Level**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.13892v1)  

---


**ABSTRACT**  
The social biases and unwelcome stereotypes revealed by pretrained language models are becoming obstacles to their application. Compared to numerous debiasing methods targeting word level, there has been relatively less attention on biases present at phrase level, limiting the performance of debiasing in discipline domains. In this paper, we propose an automatic multi-token debiasing pipeline called \textbf{General Phrase Debiaser}, which is capable of mitigating phrase-level biases in masked language models. Specifically, our method consists of a \textit{phrase filter stage} that generates stereotypical phrases from Wikipedia pages as well as a \textit{model debias stage} that can debias models at the multi-token level to tackle bias challenges on phrases. The latter searches for prompts that trigger model's bias, and then uses them for debiasing. State-of-the-art results on standard datasets and metrics show that our approach can significantly reduce gender biases on both career and multiple disciplines, across models with varying parameter sizes.

{{</citation>}}


### (47/79) Minimizing Factual Inconsistency and Hallucination in Large Language Models (Muneeswaran I et al., 2023)

{{<citation>}}

Muneeswaran I, Shreya Saxena, Siva Prasad, M V Sai Prakash, Advaith Shankar, Varun V, Vishal Vaddina, Saisubramaniam Gopalakrishnan. (2023)  
**Minimizing Factual Inconsistency and Hallucination in Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, GPT, GPT-3.5, Language Model  
[Paper Link](http://arxiv.org/abs/2311.13878v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) are widely used in critical fields such as healthcare, education, and finance due to their remarkable proficiency in various language-related tasks. However, LLMs are prone to generating factually incorrect responses or "hallucinations," which can lead to a loss of credibility and trust among users. To address this issue, we propose a multi-stage framework that generates the rationale first, verifies and refines incorrect ones, and uses them as supporting references to generate the answer. The generated rationale enhances the transparency of the answer and our framework provides insights into how the model arrived at this answer, by using this rationale and the references to the context. In this paper, we demonstrate its effectiveness in improving the quality of responses to drug-related inquiries in the life sciences industry. Our framework improves traditional Retrieval Augmented Generation (RAG) by enabling OpenAI GPT-3.5-turbo to be 14-25% more faithful and 16-22% more accurate on two datasets. Furthermore, fine-tuning samples based on our framework improves the accuracy of smaller open-access LLMs by 33-42% and competes with RAG on commercial models.

{{</citation>}}


### (48/79) Challenges of Large Language Models for Mental Health Counseling (Neo Christopher Chung et al., 2023)

{{<citation>}}

Neo Christopher Chung, George Dyer, Lennart Brocki. (2023)  
**Challenges of Large Language Models for Mental Health Counseling**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-HC, cs.CL  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2311.13857v1)  

---


**ABSTRACT**  
The global mental health crisis is looming with a rapid increase in mental disorders, limited resources, and the social stigma of seeking treatment. As the field of artificial intelligence (AI) has witnessed significant advancements in recent years, large language models (LLMs) capable of understanding and generating human-like text may be used in supporting or providing psychological counseling. However, the application of LLMs in the mental health domain raises concerns regarding the accuracy, effectiveness, and reliability of the information provided. This paper investigates the major challenges associated with the development of LLMs for psychological counseling, including model hallucination, interpretability, bias, privacy, and clinical effectiveness. We explore potential solutions to these challenges that are practical and applicable to the current paradigm of AI. From our experience in developing and deploying LLMs for mental health, AI holds a great promise for improving mental health care, if we can carefully navigate and overcome pitfalls of LLMs.

{{</citation>}}


### (49/79) Grammatical Error Correction via Mixed-Grained Weighted Training (Jiahao Li et al., 2023)

{{<citation>}}

Jiahao Li, Quan Wang, Chiwei Zhu, Zhendong Mao, Yongdong Zhang. (2023)  
**Grammatical Error Correction via Mixed-Grained Weighted Training**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Seq2Seq  
[Paper Link](http://arxiv.org/abs/2311.13848v1)  

---


**ABSTRACT**  
The task of Grammatical Error Correction (GEC) aims to automatically correct grammatical errors in natural texts. Almost all previous works treat annotated training data equally, but inherent discrepancies in data are neglected. In this paper, the inherent discrepancies are manifested in two aspects, namely, accuracy of data annotation and diversity of potential annotations. To this end, we propose MainGEC, which designs token-level and sentence-level training weights based on inherent discrepancies in accuracy and potential diversity of data annotation, respectively, and then conducts mixed-grained weighted training to improve the training effect for GEC. Empirical evaluation shows that whether in the Seq2Seq or Seq2Edit manner, MainGEC achieves consistent and significant performance improvements on two benchmark datasets, demonstrating the effectiveness and superiority of the mixed-grained weighted training. Further ablation experiments verify the effectiveness of designed weights of both granularities in MainGEC.

{{</citation>}}


### (50/79) DaG LLM ver 1.0: Pioneering Instruction-Tuned Language Modeling for Korean NLP (Dongjun Jang et al., 2023)

{{<citation>}}

Dongjun Jang, Sangah Lee, Sungjoo Byun, Jinwoong Kim, Jean Seo, Minseok Kim, Soyeon Kim, Chaeyoung Oh, Jaeyoon Kim, Hyemi Jo, Hyopil Shin. (2023)  
**DaG LLM ver 1.0: Pioneering Instruction-Tuned Language Modeling for Korean NLP**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2311.13784v1)  

---


**ABSTRACT**  
This paper presents the DaG LLM (David and Goliath Large Language Model), a language model specialized for Korean and fine-tuned through Instruction Tuning across 41 tasks within 13 distinct categories.

{{</citation>}}


### (51/79) Transformer-based Named Entity Recognition in Construction Supply Chain Risk Management in Australia (Milad Baghalzadeh Shishehgarkhaneh et al., 2023)

{{<citation>}}

Milad Baghalzadeh Shishehgarkhaneh, Robert C. Moehler, Yihai Fang, Amer A. Hijazi, Hamed Aboutorab. (2023)  
**Transformer-based Named Entity Recognition in Construction Supply Chain Risk Management in Australia**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NER, NLP, Named Entity Recognition, Transformer  
[Paper Link](http://arxiv.org/abs/2311.13755v1)  

---


**ABSTRACT**  
The construction industry in Australia is characterized by its intricate supply chains and vulnerability to myriad risks. As such, effective supply chain risk management (SCRM) becomes imperative. This paper employs different transformer models, and train for Named Entity Recognition (NER) in the context of Australian construction SCRM. Utilizing NER, transformer models identify and classify specific risk-associated entities in news articles, offering a detailed insight into supply chain vulnerabilities. By analysing news articles through different transformer models, we can extract relevant entities and insights related to specific risk taxonomies local (milieu) to the Australian construction landscape. This research emphasises the potential of NLP-driven solutions, like transformer models, in revolutionising SCRM for construction in geo-media specific contexts.

{{</citation>}}


## hep-ex (1)



### (52/79) Efficient and Robust Jet Tagging at the LHC with Knowledge Distillation (Ryan Liu et al., 2023)

{{<citation>}}

Ryan Liu, Abhijith Gandrakota, Jennifer Ngadiuba, Maria Spiropulu, Jean-Roch Vlimant. (2023)  
**Efficient and Robust Jet Tagging at the LHC with Knowledge Distillation**  

---
Primary Category: hep-ex  
Categories: cs-LG, hep-ex, hep-ex  
Keywords: Knowledge Distillation  
[Paper Link](http://arxiv.org/abs/2311.14160v1)  

---


**ABSTRACT**  
The challenging environment of real-time data processing systems at the Large Hadron Collider (LHC) strictly limits the computational complexity of algorithms that can be deployed. For deep learning models, this implies that only models with low computational complexity that have weak inductive bias are feasible. To address this issue, we utilize knowledge distillation to leverage both the performance of large models and the reduced computational complexity of small ones. In this paper, we present an implementation of knowledge distillation, demonstrating an overall boost in the student models' performance for the task of classifying jets at the LHC. Furthermore, by using a teacher model with a strong inductive bias of Lorentz symmetry, we show that we can induce the same inductive bias in the student model which leads to better robustness against arbitrary Lorentz boost.

{{</citation>}}


## cs.RO (2)



### (53/79) Tube-NeRF: Efficient Imitation Learning of Visuomotor Policies from MPC using Tube-Guided Data Augmentation and NeRFs (Andrea Tagliabue et al., 2023)

{{<citation>}}

Andrea Tagliabue, Jonathan P. How. (2023)  
**Tube-NeRF: Efficient Imitation Learning of Visuomotor Policies from MPC using Tube-Guided Data Augmentation and NeRFs**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-LG, cs-RO, cs.RO  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2311.14153v1)  

---


**ABSTRACT**  
Imitation learning (IL) can train computationally-efficient sensorimotor policies from a resource-intensive Model Predictive Controller (MPC), but it often requires many samples, leading to long training times or limited robustness. To address these issues, we combine IL with a variant of robust MPC that accounts for process and sensing uncertainties, and we design a data augmentation (DA) strategy that enables efficient learning of vision-based policies. The proposed DA method, named Tube-NeRF, leverages Neural Radiance Fields (NeRFs) to generate novel synthetic images, and uses properties of the robust MPC (the tube) to select relevant views and to efficiently compute the corresponding actions. We tailor our approach to the task of localization and trajectory tracking on a multirotor, by learning a visuomotor policy that generates control actions using images from the onboard camera as only source of horizontal position. Our evaluations numerically demonstrate learning of a robust visuomotor policy with an 80-fold increase in demonstration efficiency and a 50% reduction in training time over current IL methods. Additionally, our policies successfully transfer to a real multirotor, achieving accurate localization and low tracking errors despite large disturbances, with an onboard inference time of only 1.5 ms.

{{</citation>}}


### (54/79) FViT-Grasp: Grasping Objects With Using Fast Vision Transformers (Arda Sarp Yenicesu et al., 2023)

{{<citation>}}

Arda Sarp Yenicesu, Berk Cicek, Ozgur S. Oguz. (2023)  
**FViT-Grasp: Grasping Objects With Using Fast Vision Transformers**  

---
Primary Category: cs.RO  
Categories: cs-CV, cs-RO, cs.RO  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.13986v1)  

---


**ABSTRACT**  
This study addresses the challenge of manipulation, a prominent issue in robotics. We have devised a novel methodology for swiftly and precisely identifying the optimal grasp point for a robot to manipulate an object. Our approach leverages a Fast Vision Transformer (FViT), a type of neural network designed for processing visual data and predicting the most suitable grasp location. Demonstrating state-of-the-art performance in terms of speed while maintaining a high level of accuracy, our method holds promise for potential deployment in real-time robotic grasping applications. We believe that this study provides a baseline for future research in vision-based robotic grasp applications. Its high speed and accuracy bring researchers closer to real-life applications.

{{</citation>}}


## cs.AI (8)



### (55/79) Scalable AI Safety via Doubly-Efficient Debate (Jonah Brown-Cohen et al., 2023)

{{<citation>}}

Jonah Brown-Cohen, Geoffrey Irving, Georgios Piliouras. (2023)  
**Scalable AI Safety via Doubly-Efficient Debate**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.14125v1)  

---


**ABSTRACT**  
The emergence of pre-trained AI systems with powerful capabilities across a diverse and ever-increasing set of complex domains has raised a critical challenge for AI safety as tasks can become too complicated for humans to judge directly. Irving et al. [2018] proposed a debate method in this direction with the goal of pitting the power of such AI models against each other until the problem of identifying (mis)-alignment is broken down into a manageable subtask. While the promise of this approach is clear, the original framework was based on the assumption that the honest strategy is able to simulate deterministic AI systems for an exponential number of steps, limiting its applicability. In this paper, we show how to address these challenges by designing a new set of debate protocols where the honest strategy can always succeed using a simulation of a polynomial number of steps, whilst being able to verify the alignment of stochastic AI systems, even when the dishonest strategy is allowed to use exponentially many simulation steps.

{{</citation>}}


### (56/79) Boosting the Power of Small Multimodal Reasoning Models to Match Larger Models with Self-Consistency Training (Cheng Tan et al., 2023)

{{<citation>}}

Cheng Tan, Jingxuan Wei, Zhangyang Gao, Linzhuang Sun, Siyuan Li, Xihong Yang, Stan Z. Li. (2023)  
**Boosting the Power of Small Multimodal Reasoning Models to Match Larger Models with Self-Consistency Training**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2311.14109v1)  

---


**ABSTRACT**  
Multimodal reasoning is a challenging task that requires models to reason across multiple modalities to answer questions. Existing approaches have made progress by incorporating language and visual modalities into a two-stage reasoning framework, separating rationale generation from answer inference. However, these approaches often fall short due to the inadequate quality of the generated rationales. In this work, we delve into the importance of rationales in model reasoning. We observe that when rationales are completely accurate, the model's accuracy significantly improves, highlighting the need for high-quality rationale generation. Motivated by this, we propose MC-CoT, a self-consistency training strategy that generates multiple rationales and answers, subsequently selecting the most accurate through a voting process. This approach not only enhances the quality of generated rationales but also leads to more accurate and robust answers. Through extensive experiments, we demonstrate that our approach significantly improves model performance across various benchmarks. Remarkably, we show that even smaller base models, when equipped with our proposed approach, can achieve results comparable to those of larger models, illustrating the potential of our approach in harnessing the power of rationales for improved multimodal reasoning. The code is available at https://github.com/chengtan9907/mc-cot.

{{</citation>}}


### (57/79) Towards Explainable Strategy Templates using NLP Transformers (Pallavi Bagga et al., 2023)

{{<citation>}}

Pallavi Bagga, Kostas Stathis. (2023)  
**Towards Explainable Strategy Templates using NLP Transformers**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: GPT, Language Model, NLP, Natural Language Processing, Reinforcement Learning, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.14061v1)  

---


**ABSTRACT**  
This paper bridges the gap between mathematical heuristic strategies learned from Deep Reinforcement Learning (DRL) in automated agent negotiation, and comprehensible, natural language explanations. Our aim is to make these strategies more accessible to non-experts. By leveraging traditional Natural Language Processing (NLP) techniques and Large Language Models (LLMs) equipped with Transformers, we outline how parts of DRL strategies composed of parts within strategy templates can be transformed into user-friendly, human-like English narratives. To achieve this, we present a top-level algorithm that involves parsing mathematical expressions of strategy templates, semantically interpreting variables and structures, generating rule-based primary explanations, and utilizing a Generative Pre-trained Transformer (GPT) model to refine and contextualize these explanations. Subsequent customization for varied audiences and meticulous validation processes in an example illustrate the applicability and potential of this approach.

{{</citation>}}


### (58/79) Identification for Tree-shaped Structural Causal Models in Polynomial Time (Aaryan Gupta et al., 2023)

{{<citation>}}

Aaryan Gupta, Markus Bläser. (2023)  
**Identification for Tree-shaped Structural Causal Models in Polynomial Time**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-DS, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.14058v1)  

---


**ABSTRACT**  
Linear structural causal models (SCMs) are used to express and analyse the relationships between random variables. Direct causal effects are represented as directed edges and confounding factors as bidirected edges. Identifying the causal parameters from correlations between the nodes is an open problem in artificial intelligence. In this paper, we study SCMs whose directed component forms a tree. Van der Zander et al. (AISTATS'22, PLMR 151, pp. 6770--6792, 2022) give a PSPACE-algorithm for the identification problem in this case, which is a significant improvement over the general Gr\"obner basis approach, which has doubly-exponential time complexity in the number of structural parameters. In this work, we present a randomized polynomial-time algorithm, which solves the identification problem for tree-shaped SCMs. For every structural parameter, our algorithms decides whether it is generically identifiable, generically 2-identifiable, or generically unidentifiable. (No other cases can occur.) In the first two cases, it provides one or two fractional affine square root terms of polynomials (FASTPs) for the corresponding parameter, respectively.

{{</citation>}}


### (59/79) PrivateLoRA For Efficient Privacy Preserving LLM (Yiming Wang et al., 2023)

{{<citation>}}

Yiming Wang, Yu Lin, Xiaodong Zeng, Guannan Zhang. (2023)  
**PrivateLoRA For Efficient Privacy Preserving LLM**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CR, cs.AI  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2311.14030v1)  

---


**ABSTRACT**  
End users face a choice between privacy and efficiency in current Large Language Model (LLM) service paradigms. In cloud-based paradigms, users are forced to compromise data locality for generation quality and processing speed. Conversely, edge device paradigms maintain data locality but fail to deliver satisfactory performance. In this work, we propose a novel LLM service paradigm that distributes privacy-sensitive computation on edge devices and shared computation in the cloud. Only activations are transmitted between the central cloud and edge devices to ensure data locality. Our core innovation, PrivateLoRA, addresses the challenging communication overhead by exploiting the low rank of residual activations, achieving over 95% communication reduction. Consequently, PrivateLoRA effectively maintains data locality and is extremely resource efficient. Under standard 5G networks, PrivateLoRA achieves throughput over 300% of device-only solutions for 7B models and over 80% of an A100 GPU for 33B models. PrivateLoRA also provides tuning performance comparable to LoRA for advanced personalization. Our approach democratizes access to state-of-the-art generative AI for edge devices, paving the way for more tailored LLM experiences for the general public. To our knowledge, our proposed framework is the first efficient and privacy-preserving LLM solution in the literature.

{{</citation>}}


### (60/79) Controlling Large Language Model-based Agents for Large-Scale Decision-Making: An Actor-Critic Approach (Bin Zhang et al., 2023)

{{<citation>}}

Bin Zhang, Hangyu Mao, Jingqing Ruan, Ying Wen, Yang Li, Shao Zhang, Zhiwei Xu, Dapeng Li, Ziyue Li, Rui Zhao, Lijuan Li, Guoliang Fan. (2023)  
**Controlling Large Language Model-based Agents for Large-Scale Decision-Making: An Actor-Critic Approach**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.13884v1)  

---


**ABSTRACT**  
The significant advancements in large language models (LLMs) have presented novel opportunities for tackling planning and decision-making within multi-agent systems. However, as the number of agents increases, the issues of hallucination in LLMs and coordination in multi-agent systems (MAS) have become increasingly pronounced. Additionally, the efficient utilization of tokens becomes a critical consideration when employing LLMs to facilitate the interactions of large numbers of agents. In this paper, we present a novel framework aimed at enhancing coordination and decision-making capabilities of LLMs within large-scale multi-agent environments. Our approach draws inspiration from the actor-critic framework employed in multi-agent reinforcement learning, and we develop a modular and token-efficient solution that effectively addresses challenges presented by LLMs and MAS. Through evaluations conducted in experiments involving system resource allocation and robot grid transportation, we demonstrate the considerable advantages afforded by our proposed approach.

{{</citation>}}


### (61/79) A Cross Attention Approach to Diagnostic Explainability using Clinical Practice Guidelines for Depression (Sumit Dalal et al., 2023)

{{<citation>}}

Sumit Dalal, Deepa Tilwani, Manas Gaur, Sarika Jain, Valerie Shalin, Amit Seth. (2023)  
**A Cross Attention Approach to Diagnostic Explainability using Clinical Practice Guidelines for Depression**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Attention, Clinical, GPT, GPT-3.5  
[Paper Link](http://arxiv.org/abs/2311.13852v1)  

---


**ABSTRACT**  
The lack of explainability using relevant clinical knowledge hinders the adoption of Artificial Intelligence-powered analysis of unstructured clinical dialogue. A wealth of relevant, untapped Mental Health (MH) data is available in online communities, providing the opportunity to address the explainability problem with substantial potential impact as a screening tool for both online and offline applications. We develop a method to enhance attention in popular transformer models and generate clinician-understandable explanations for classification by incorporating external clinical knowledge. Inspired by how clinicians rely on their expertise when interacting with patients, we leverage relevant clinical knowledge to model patient inputs, providing meaningful explanations for classification. This will save manual review time and engender trust. We develop such a system in the context of MH using clinical practice guidelines (CPG) for diagnosing depression, a mental health disorder of global concern. We propose an application-specific language model called ProcesS knowledge-infused cross ATtention (PSAT), which incorporates CPGs when computing attention. Through rigorous evaluation on three expert-curated datasets related to depression, we demonstrate application-relevant explainability of PSAT. PSAT also surpasses the performance of nine baseline models and can provide explanations where other baselines fall short. We transform a CPG resource focused on depression, such as the Patient Health Questionnaire (e.g. PHQ-9) and related questions, into a machine-readable ontology using SNOMED-CT. With this resource, PSAT enhances the ability of models like GPT-3.5 to generate application-relevant explanations.

{{</citation>}}


### (62/79) Scalable AI Generative Content for Vehicular Network Semantic Communication (Hao Feng et al., 2023)

{{<citation>}}

Hao Feng, Yi Yang, Zhu Han. (2023)  
**Scalable AI Generative Content for Vehicular Network Semantic Communication**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.13782v1)  

---


**ABSTRACT**  
Perceiving vehicles in a driver's blind spot is vital for safe driving. The detection of potentially dangerous vehicles in these blind spots can benefit from vehicular network semantic communication technology. However, efficient semantic communication involves a trade-off between accuracy and delay, especially in bandwidth-limited situations. This paper unveils a scalable Artificial Intelligence Generated Content (AIGC) system that leverages an encoder-decoder architecture. This system converts images into textual representations and reconstructs them into quality-acceptable images, optimizing transmission for vehicular network semantic communication. Moreover, when bandwidth allows, auxiliary information is integrated. The encoder-decoder aims to maintain semantic equivalence with the original images across various tasks. Then the proposed approach employs reinforcement learning to enhance the reliability of the generated contents. Experimental results suggest that the proposed method surpasses the baseline in perceiving vehicles in blind spots and effectively compresses communication data. While this method is specifically designed for driving scenarios, this encoder-decoder architecture also holds potential for wide use across various semantic communication scenarios.

{{</citation>}}


## cs.HC (2)



### (63/79) PortfolioMentor: Multimodal Generative AI Companion for Learning and Crafting Interactive Digital Art Portfolios (Tao Long et al., 2023)

{{<citation>}}

Tao Long, Weirui Peng. (2023)  
**PortfolioMentor: Multimodal Generative AI Companion for Learning and Crafting Interactive Digital Art Portfolios**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-CY, cs-HC, cs-MM, cs.HC  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2311.14091v1)  

---


**ABSTRACT**  
Digital art portfolios serve as impactful mediums for artists to convey their visions, weaving together visuals, audio, interactions, and narratives. However, without technical backgrounds, design students often find it challenging to translate creative ideas into tangible codes and designs, given the lack of tailored resources for the non-technical, academic support in art schools, and a comprehensive guiding tool throughout the mentally demanding process. Recognizing the role of companionship in code learning and leveraging generative AI models' capabilities in supporting creative tasks, we present PortfolioMentor, a coding companion chatbot for IDEs. This tool guides and collaborates with students through proactive suggestions and responsible Q&As for learning, inspiration, and support. In detail, the system starts with the understanding of the task and artist's visions, follows the co-creation of visual illustrations, audio or music suggestions and files, click-scroll effects for interactions, and creative vision conceptualization, and finally synthesizes these facets into a polished interactive digital portfolio.

{{</citation>}}


### (64/79) On the Feasibility of Reasoning about the Internal States of Blackbox IoT Devices Using Side-Channel Information (Wei Sun et al., 2023)

{{<citation>}}

Wei Sun, Yuwei Xiao, Haojian Jin, Dinesh Bharadia. (2023)  
**On the Feasibility of Reasoning about the Internal States of Blackbox IoT Devices Using Side-Channel Information**  

---
Primary Category: cs.HC  
Categories: H-5-2, cs-HC, cs.HC  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2311.13761v1)  

---


**ABSTRACT**  
Internet of Things (IoT) devices are typically designed to function in a secure, closed environment, making it difficult for users to comprehend devices' behaviors. This paper shows that a user can leverage side-channel information to reason fine-grained internal states of black box IoT devices. The key enablers for our design are a multi-model sensing technique that fuses power consumption, network traffic, and radio emanations and an annotation interface that helps users form mental models of a black box IoT system. We built a prototype of our design and evaluated the prototype with open-source IoT devices and black-box commercial devices. Our experiments show a false positive rate of 1.44% for open-source IoT devices' state probing, and our participants take an average of 19.8 minutes to reason the internal states of black-box IoT devices.

{{</citation>}}


## cs.IR (1)



### (65/79) AI-Generated Images Introduce Invisible Relevance Bias to Text-Image Retrieval (Shicheng Xu et al., 2023)

{{<citation>}}

Shicheng Xu, Danyang Hou, Liang Pang, Jingcheng Deng, Jun Xu, Huawei Shen, Xueqi Cheng. (2023)  
**AI-Generated Images Introduce Invisible Relevance Bias to Text-Image Retrieval**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-CV, cs-IR, cs.IR  
Keywords: AI, Bias  
[Paper Link](http://arxiv.org/abs/2311.14084v2)  

---


**ABSTRACT**  
With the advancement of generation models, AI-generated content (AIGC) is becoming more realistic, flooding the Internet. A recent study suggests that this phenomenon has elevated the issue of source bias in text retrieval for web searches. Specifically, neural retrieval models tend to rank generated texts higher than human-written texts. In this paper, we extend the study of this bias to cross-modal retrieval. Firstly, we successfully construct a suitable benchmark to explore the existence of the bias. Subsequent extensive experiments on this benchmark reveal that AI-generated images introduce an invisible relevance bias to text-image retrieval models. Specifically, our experiments show that text-image retrieval models tend to rank the AI-generated images higher than the real images, even though the AI-generated images do not exhibit more visually relevant features to the query than real images. This invisible relevance bias is prevalent across retrieval models with varying training data and architectures. Furthermore, our subsequent exploration reveals that the inclusion of AI-generated images in the training data of the retrieval models exacerbates the invisible relevance bias. The above phenomenon triggers a vicious cycle, which makes the invisible relevance bias become more and more serious. To elucidate the potential causes of invisible relevance and address the aforementioned issues, we introduce an effective training method aimed at alleviating the invisible relevance bias. Subsequently, we apply our proposed debiasing method to retroactively identify the causes of invisible relevance, revealing that the AI-generated images induce the image encoder to embed additional information into their representation. This information exhibits a certain consistency across generated images with different semantics and can make the retriever estimate a higher relevance score.

{{</citation>}}


## q-fin.ST (1)



### (66/79) Forecasting Cryptocurrency Prices Using Deep Learning: Integrating Financial, Blockchain, and Text Data (Vincent Gurgul et al., 2023)

{{<citation>}}

Vincent Gurgul, Stefan Lessmann, Wolfgang Karl Härdle. (2023)  
**Forecasting Cryptocurrency Prices Using Deep Learning: Integrating Financial, Blockchain, and Text Data**  

---
Primary Category: q-fin.ST  
Categories: cs-LG, q-fin-ST, q-fin.ST, stat-ML  
Keywords: BERT, Financial, Language Model, NLI, NLP, Natural Language Processing, Twitter  
[Paper Link](http://arxiv.org/abs/2311.14759v1)  

---


**ABSTRACT**  
This paper explores the application of Machine Learning (ML) and Natural Language Processing (NLP) techniques in cryptocurrency price forecasting, specifically Bitcoin (BTC) and Ethereum (ETH). Focusing on news and social media data, primarily from Twitter and Reddit, we analyse the influence of public sentiment on cryptocurrency valuations using advanced deep learning NLP methods. Alongside conventional price regression, we treat cryptocurrency price forecasting as a classification problem. This includes both the prediction of price movements (up or down) and the identification of local extrema. We compare the performance of various ML models, both with and without NLP data integration. Our findings reveal that incorporating NLP data significantly enhances the forecasting performance of our models. We discover that pre-trained models, such as Twitter-RoBERTa and BART MNLI, are highly effective in capturing market sentiment, and that fine-tuning Large Language Models (LLMs) also yields substantial forecasting improvements. Notably, the BART MNLI zero-shot classification model shows considerable proficiency in extracting bullish and bearish signals from textual data. All of our models consistently generate profit across different validation scenarios, with no observed decline in profits or reduction in the impact of NLP data over time. The study highlights the potential of text analysis in improving financial forecasts and demonstrates the effectiveness of various NLP techniques in capturing nuanced market sentiment.

{{</citation>}}


## math.NA (2)



### (67/79) Physics Informed Neural Network Framework for Unsteady Discretized Reduced Order System (Rahul Halder et al., 2023)

{{<citation>}}

Rahul Halder, Giovanni Stabile, Gianluigi Rozza. (2023)  
**Physics Informed Neural Network Framework for Unsteady Discretized Reduced Order System**  

---
Primary Category: math.NA  
Categories: cs-NA, math-NA, math.NA, physics-comp-ph  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2311.14045v1)  

---


**ABSTRACT**  
This work addresses the development of a physics-informed neural network (PINN) with a loss term derived from a discretized time-dependent reduced-order system. In this work, first, the governing equations are discretized using a finite difference scheme (whereas, any other discretization technique can be adopted), then projected on a reduced or latent space using the Proper Orthogonal Decomposition (POD)-Galerkin approach and next, the residual arising from discretized reduced order equation is considered as an additional loss penalty term alongside the data-driven loss term using different variants of deep learning method such as Artificial neural network (ANN), Long Short-Term Memory based neural network (LSTM). The LSTM neural network has been proven to be very effective for time-dependent problems in a purely data-driven environment. The current work demonstrates the LSTM network's potential over ANN networks in physics-informed neural networks (PINN) as well. The potential of using discretized governing equations instead of continuous form lies in the flexibility of input to the PINN. Different sizes of data ranging from small, medium to big datasets are used to assess the potential of discretized-physics-informed neural networks when there is very sparse or no data available. The proposed methods are applied to a pitch-plunge airfoil motion governed by rigid-body dynamics and a one-dimensional viscous Burgers' equation. The current work also demonstrates the prediction capability of various discretized-physics-informed neural networks outside the domain where the data is available or governing equation-based residuals are minimized.

{{</citation>}}


### (68/79) Bias and Multiscale Correction Methods for Variational State Estimation Algorithms (Felipe Galarce et al., 2023)

{{<citation>}}

Felipe Galarce, Joaquin Mura, Alfonso Caiazzo. (2023)  
**Bias and Multiscale Correction Methods for Variational State Estimation Algorithms**  

---
Primary Category: math.NA  
Categories: cs-NA, math-NA, math.NA  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2311.14031v1)  

---


**ABSTRACT**  
The integration of experimental data into mathematical and computational models is crucial for enhancing their predictive power in real-world scenarios. However, the performance of data assimilation algorithms can be significantly degraded when measurements are corrupted by biased noise, altering the signal magnitude, or when the system dynamics lack smoothness, such as in the presence of fast oscillations or discontinuities. This paper focuses on variational state estimation using the so-called Parameterized Background Data Weak method, which relies on a parameterized background by a set of constraints, enabling state estimation by solving a minimization problem on a reduced-order background model, subject to constraints imposed by the input measurements. To address biased noise in observations, a modified formulation is proposed, incorporating a correction mechanism to handle rapid oscillations by treating them as slow-decaying modes based on a two-scale splitting of the classical reconstruction algorithm. The effectiveness of the proposed algorithms is demonstrated through various examples, including discontinuous signals and simulated Doppler ultrasound data.

{{</citation>}}


## cs.CR (4)



### (69/79) Efficient Trigger Word Insertion (Yueqi Zeng et al., 2023)

{{<citation>}}

Yueqi Zeng, Ziqiang Li, Pengfei Xia, Lei Liu, Bin Li. (2023)  
**Efficient Trigger Word Insertion**  

---
Primary Category: cs.CR  
Categories: cs-CL, cs-CR, cs.CR  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2311.13957v1)  

---


**ABSTRACT**  
With the boom in the natural language processing (NLP) field these years, backdoor attacks pose immense threats against deep neural network models. However, previous works hardly consider the effect of the poisoning rate. In this paper, our main objective is to reduce the number of poisoned samples while still achieving a satisfactory Attack Success Rate (ASR) in text backdoor attacks. To accomplish this, we propose an efficient trigger word insertion strategy in terms of trigger word optimization and poisoned sample selection. Extensive experiments on different datasets and models demonstrate that our proposed method can significantly improve attack effectiveness in text classification tasks. Remarkably, our approach achieves an ASR of over 90% with only 10 poisoned samples in the dirty-label setting and requires merely 1.5% of the training data in the clean-label setting.

{{</citation>}}


### (70/79) Adversarial defense based on distribution transfer (Jiahao Chen et al., 2023)

{{<citation>}}

Jiahao Chen, Diqun Yan, Li Dong. (2023)  
**Adversarial defense based on distribution transfer**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2311.13841v1)  

---


**ABSTRACT**  
The presence of adversarial examples poses a significant threat to deep learning models and their applications. Existing defense methods provide certain resilience against adversarial examples, but often suffer from decreased accuracy and generalization performance, making it challenging to achieve a trade-off between robustness and generalization. To address this, our paper interprets the adversarial example problem from the perspective of sample distribution and proposes a defense method based on distribution shift, leveraging the distribution transfer capability of a diffusion model for adversarial defense. The core idea is to exploit the discrepancy between normal and adversarial sample distributions to achieve adversarial defense using a pretrained diffusion model. Specifically, an adversarial sample undergoes a forward diffusion process, moving away from the source distribution, followed by a reverse process guided by the protected model (victim model) output to map it back to the normal distribution. Experimental evaluations on CIFAR10 and ImageNet30 datasets are conducted, comparing with adversarial training and input preprocessing methods. For infinite-norm attacks with 8/255 perturbation, accuracy rates of 78.1% and 83.5% are achieved, respectively. For 2-norm attacks with 128/255 perturbation, accuracy rates are 74.3% and 82.5%. Additional experiments considering perturbation amplitude, diffusion iterations, and adaptive attacks also validate the effectiveness of the proposed method. Results demonstrate that even when the attacker has knowledge of the defense, the proposed distribution-based method effectively withstands adversarial examples. It fills the gaps of traditional approaches, restoring high-quality original samples and showcasing superior performance in model robustness and generalization.

{{</citation>}}


### (71/79) Enhancing Intrusion Detection In Internet Of Vehicles Through Federated Learning (Abhishek Sebastian et al., 2023)

{{<citation>}}

Abhishek Sebastian, Pragna R, Sudhakaran G, Renjith P N, Leela Karthikeyan H. (2023)  
**Enhancing Intrusion Detection In Internet Of Vehicles Through Federated Learning**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CR, cs-LG, cs.CR  
Keywords: Intrusion Detection  
[Paper Link](http://arxiv.org/abs/2311.13800v1)  

---


**ABSTRACT**  
Federated learning is a technique of decentralized machine learning. that allows multiple parties to collaborate and learn a shared model without sharing their raw data. Our paper proposes a federated learning framework for intrusion detection in Internet of Vehicles (IOVs) using the CIC-IDS 2017 dataset. The proposed framework employs SMOTE for handling class imbalance, outlier detection for identifying and removing abnormal observations, and hyperparameter tuning to optimize the model's performance. The authors evaluated the proposed framework using various performance metrics and demonstrated its effectiveness in detecting intrusions with other datasets (KDD-Cup 99 and UNSW- NB-15) and conventional classifiers. Furthermore, the proposed framework can protect sensitive data while achieving high intrusion detection performance.

{{</citation>}}


### (72/79) Security and Privacy Challenges in Deep Learning Models (Gopichandh Golla, 2023)

{{<citation>}}

Gopichandh Golla. (2023)  
**Security and Privacy Challenges in Deep Learning Models**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CR, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2311.13744v1)  

---


**ABSTRACT**  
These days, deep learning models have achieved great success in multiple fields, from autonomous driving to medical diagnosis. These models have expanded the abilities of artificial intelligence by offering great solutions to complex problems that were very difficult to solve earlier. In spite of their unseen success in various, it has been identified, through research conducted, that deep learning models can be subjected to various attacks that compromise model security and data privacy of the Deep Neural Network models. Deep learning models can be subjected to various attacks at different stages of their lifecycle. During the testing phase, attackers can exploit vulnerabilities through different kinds of attacks such as Model Extraction Attacks, Model Inversion attacks, and Adversarial attacks. Model Extraction Attacks are aimed at reverse-engineering a trained deep learning model, with the primary objective of revealing its architecture and parameters. Model inversion attacks aim to compromise the privacy of the data used in the Deep learning model. These attacks are done to compromise the confidentiality of the model by going through the sensitive training data from the model's predictions. By analyzing the model's responses, attackers aim to reconstruct sensitive information. In this way, the model's data privacy is compromised. Adversarial attacks, mainly employed on computer vision models, are made to corrupt models into confidently making incorrect predictions through malicious testing data. These attacks subtly alter the input data, making it look normal but misleading deep learning models to make incorrect decisions. Such attacks can happen during both the model's evaluation and training phases. Data Poisoning Attacks add harmful data to the training set, disrupting the learning process and reducing the reliability of the deep learning mode.

{{</citation>}}


## eess.SY (1)



### (73/79) 5G Edge Vision: Wearable Assistive Technology for People with Blindness and Low Vision (Tommy Azzino et al., 2023)

{{<citation>}}

Tommy Azzino, Marco Mezzavilla, Sundeep Rangan, Yao Wang, John-Ross Rizzo. (2023)  
**5G Edge Vision: Wearable Assistive Technology for People with Blindness and Low Vision**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.13939v1)  

---


**ABSTRACT**  
In an increasingly visual world, people with blindness and low vision (pBLV) face substantial challenges in navigating their surroundings and interpreting visual information. From our previous work, VIS4ION is a smart wearable that helps pBLV in their day-to-day challenges. It enables multiple artificial intelligence (AI)-based microservices such as visual scene processing, navigation, and vision-language inference. These microservices require powerful computational resources and, in some cases, stringent inference times, hence the need to offload computation to edge servers. This paper introduces a novel video streaming platform that improves the capabilities of VIS4ION by providing real-time support of the microservices at the network edge. When video is offloaded wirelessly to the edge, the time-varying nature of the wireless network requires the use of adaptation strategies for a seamless video service. We demonstrate the performance of an adaptive real-time video streaming platform through experimentation with an open-source 5G deployment based on open air interface (OAI). The experiments demonstrate the ability to provide the microservices robustly in time-varying network loads.

{{</citation>}}


## cs.SE (2)



### (74/79) A Multi-solution Study on GDPR AI-enabled Completeness Checking of DPAs (Muhammad Ilyas Azeem et al., 2023)

{{<citation>}}

Muhammad Ilyas Azeem, Sallam Abualhaija. (2023)  
**A Multi-solution Study on GDPR AI-enabled Completeness Checking of DPAs**  

---
Primary Category: cs.SE  
Categories: cs-AI, cs-SE, cs.SE  
Keywords: AI, BERT, LSTM  
[Paper Link](http://arxiv.org/abs/2311.13881v1)  

---


**ABSTRACT**  
Specifying legal requirements for software systems to ensure their compliance with the applicable regulations is a major concern to requirements engineering (RE). Personal data which is collected by an organization is often shared with other organizations to perform certain processing activities. In such cases, the General Data Protection Regulation (GDPR) requires issuing a data processing agreement (DPA) which regulates the processing and further ensures that personal data remains protected. Violating GDPR can lead to huge fines reaching to billions of Euros. Software systems involving personal data processing must adhere to the legal obligations stipulated in GDPR and outlined in DPAs. Requirements engineers can elicit from DPAs legal requirements for regulating the data processing activities in software systems. Checking the completeness of a DPA according to the GDPR provisions is therefore an essential prerequisite to ensure that the elicited requirements are complete. Analyzing DPAs entirely manually is time consuming and requires adequate legal expertise. In this paper, we propose an automation strategy to address the completeness checking of DPAs against GDPR. Specifically, we pursue ten alternative solutions which are enabled by different technologies, namely traditional machine learning, deep learning, language modeling, and few-shot learning. The goal of our work is to empirically examine how these different technologies fare in the legal domain. We computed F2 score on a set of 30 real DPAs. Our evaluation shows that best-performing solutions yield F2 score of 86.7% and 89.7% are based on pre-trained BERT and RoBERTa language models. Our analysis further shows that other alternative solutions based on deep learning (e.g., BiLSTM) and few-shot learning (e.g., SetFit) can achieve comparable accuracy, yet are more efficient to develop.

{{</citation>}}


### (75/79) Legal Requirements Analysis (Sallam Abualhaija et al., 2023)

{{<citation>}}

Sallam Abualhaija, Marcello Ceci, Lionel Briand. (2023)  
**Legal Requirements Analysis**  

---
Primary Category: cs.SE  
Categories: cs-AI, cs-SE, cs.SE  
Keywords: AI, Legal  
[Paper Link](http://arxiv.org/abs/2311.13871v1)  

---


**ABSTRACT**  
Modern software has been an integral part of everyday activities in many disciplines and application contexts. Introducing intelligent automation by leveraging artificial intelligence (AI) led to break-throughs in many fields. The effectiveness of AI can be attributed to several factors, among which is the increasing availability of data. Regulations such as the general data protection regulation (GDPR) in the European Union (EU) are introduced to ensure the protection of personal data. Software systems that collect, process, or share personal data are subject to compliance with such regulations. Developing compliant software depends heavily on addressing legal requirements stipulated in applicable regulations, a central activity in the requirements engineering (RE) phase of the software development process. RE is concerned with specifying and maintaining requirements of a system-to-be, including legal requirements. Legal agreements which describe the policies organizations implement for processing personal data can provide an additional source to regulations for eliciting legal requirements. In this chapter, we explore a variety of methods for analyzing legal requirements and exemplify them on GDPR. Specifically, we describe possible alternatives for creating machine-analyzable representations from regulations, survey the existing automated means for enabling compliance verification against regulations, and further reflect on the current challenges of legal requirements analysis.

{{</citation>}}


## cs.NI (1)



### (76/79) A Deep Reinforcement Learning Approach for Improving Age of Information in Mission-Critical IoT (Hossam Farag et al., 2023)

{{<citation>}}

Hossam Farag, Mikael Gidlund, Cedomir Stefanovic. (2023)  
**A Deep Reinforcement Learning Approach for Improving Age of Information in Mission-Critical IoT**  

---
Primary Category: cs.NI  
Categories: cs-NI, cs.NI, eess-SP  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.13861v1)  

---


**ABSTRACT**  
The emerging mission-critical Internet of Things (IoT) play a vital role in remote healthcare, haptic interaction, and industrial automation, where timely delivery of status updates is crucial. The Age of Information (AoI) is an effective metric to capture and evaluate information freshness at the destination. A system design based solely on the optimization of the average AoI might not be adequate to capture the requirements of mission-critical applications, since averaging eliminates the effects of extreme events. In this paper, we introduce a Deep Reinforcement Learning (DRL)-based algorithm to improve AoI in mission-critical IoT applications. The objective is to minimize an AoI-based metric consisting of the weighted sum of the average AoI and the probability of exceeding an AoI threshold. We utilize the actor-critic method to train the algorithm to achieve optimized scheduling policy to solve the formulated problem. The performance of our proposed method is evaluated in a simulated setup and the results show a significant improvement in terms of the average AoI and the AoI violation probability compared to the related-work.

{{</citation>}}


## quant-ph (1)



### (77/79) Bridging Classical and Quantum Machine Learning: Knowledge Transfer From Classical to Quantum Neural Networks Using Knowledge Distillation (Mohammad Junayed Hasan et al., 2023)

{{<citation>}}

Mohammad Junayed Hasan, M. R. C. Mahdy. (2023)  
**Bridging Classical and Quantum Machine Learning: Knowledge Transfer From Classical to Quantum Neural Networks Using Knowledge Distillation**  

---
Primary Category: quant-ph  
Categories: cs-AI, cs-LG, quant-ph, quant-ph  
Keywords: Knowledge Distillation  
[Paper Link](http://arxiv.org/abs/2311.13810v1)  

---


**ABSTRACT**  
Very recently, studies have shown that quantum neural networks surpass classical neural networks in tasks like image classification when a similar number of learnable parameters are used. However, the development and optimization of quantum models are currently hindered by issues such as qubit instability and limited qubit availability, leading to error-prone systems with weak performance. In contrast, classical models can exhibit high-performance owing to substantial resource availability. As a result, more studies have been focusing on hybrid classical-quantum integration. A line of research particularly focuses on transfer learning through classical-quantum integration or quantum-quantum approaches. Unlike previous studies, this paper introduces a new method to transfer knowledge from classical to quantum neural networks using knowledge distillation, effectively bridging the gap between classical machine learning and emergent quantum computing techniques. We adapt classical convolutional neural network (CNN) architectures like LeNet and AlexNet to serve as teacher networks, facilitating the training of student quantum models by sending supervisory signals during backpropagation through KL-divergence. The approach yields significant performance improvements for the quantum models by solely depending on classical CNNs, with quantum models achieving an average accuracy improvement of 0.80% on the MNIST dataset and 5.40% on the more complex Fashion MNIST dataset. Applying this technique eliminates the cumbersome training of huge quantum models for transfer learning in resource-constrained settings and enables re-using existing pre-trained classical models to improve performance.Thus, this study paves the way for future research in quantum machine learning (QML) by positioning knowledge distillation as a core technique for advancing QML applications.

{{</citation>}}


## eess.SP (1)



### (78/79) Knowledge Distillation Based Semantic Communications For Multiple Users (Chenguang Liu et al., 2023)

{{<citation>}}

Chenguang Liu, Yuxin Zhou, Yunfei Chen, Shuang-Hua Yang. (2023)  
**Knowledge Distillation Based Semantic Communications For Multiple Users**  

---
Primary Category: eess.SP  
Categories: cs-LG, eess-SP, eess.SP  
Keywords: Knowledge Distillation, Transformer  
[Paper Link](http://arxiv.org/abs/2311.13789v1)  

---


**ABSTRACT**  
Deep learning (DL) has shown great potential in revolutionizing the traditional communications system. Many applications in communications have adopted DL techniques due to their powerful representation ability. However, the learning-based methods can be dependent on the training dataset and perform worse on unseen interference due to limited model generalizability and complexity. In this paper, we consider the semantic communication (SemCom) system with multiple users, where there is a limited number of training samples and unexpected interference. To improve the model generalization ability and reduce the model size, we propose a knowledge distillation (KD) based system where Transformer based encoder-decoder is implemented as the semantic encoder-decoder and fully connected neural networks are implemented as the channel encoder-decoder. Specifically, four types of knowledge transfer and model compression are analyzed. Important system and model parameters are considered, including the level of noise and interference, the number of interfering users and the size of the encoder and decoder. Numerical results demonstrate that KD significantly improves the robustness and the generalization ability when applied to unexpected interference, and it reduces the performance loss when compressing the model size.

{{</citation>}}


## q-fin.CP (1)



### (79/79) FinMe: A Performance-Enhanced Large Language Model Trading Agent with Layered Memory and Character Design (Yangyang Yu et al., 2023)

{{<citation>}}

Yangyang Yu, Haohang Li, Zhi Chen, Yuechen Jiang, Yang Li, Denghui Zhang, Rong Liu, Jordan W. Suchow, Khaldoun Khashanah. (2023)  
**FinMe: A Performance-Enhanced Large Language Model Trading Agent with Layered Memory and Character Design**  

---
Primary Category: q-fin.CP  
Categories: cs-AI, cs-CE, cs-LG, q-fin-CP, q-fin.CP  
Keywords: Language Model, QA  
[Paper Link](http://arxiv.org/abs/2311.13743v1)  

---


**ABSTRACT**  
Recent advancements in Large Language Models (LLMs) have exhibited notable efficacy in question-answering (QA) tasks across diverse domains. Their prowess in integrating extensive web knowledge has fueled interest in developing LLM autonomous agents. While LLMs are efficient in decoding human instructions and deriving solutions by holistically processing historical inputs, transitioning to purpose-driven agents requires a supplementary rational architecture to process multi-source information, establish reasoning chains, and prioritize critical tasks. Addressing this, we introduce \textsc{FinMe}, a novel LLM-based agent framework devised for financial decision-making, encompassing three core modules: Profiling, to outline the agent's characteristics; Memory, with layered processing, to aid the agent in assimilating realistic hierarchical financial data; and Decision-making, to convert insights gained from memories into investment decisions. Notably, \textsc{FinMe}'s memory module aligns closely with the cognitive structure of human traders, offering robust interpretability and real-time tuning. Its adjustable cognitive span allows for the retention of critical information beyond human perceptual limits, thereby enhancing trading outcomes. This framework enables the agent to self-evolve its professional knowledge, react agilely to new investment cues, and continuously refine trading decisions in the volatile financial environment. We first compare \textsc{FinMe} with various algorithmic agents on a scalable real-world financial dataset, underscoring its leading trading performance in stocks and funds. We then fine-tuned the agent's perceptual spans to achieve a significant trading performance. Collectively, \textsc{FinMe} presents a cutting-edge LLM agent framework for automated trading, boosting cumulative investment returns.

{{</citation>}}
