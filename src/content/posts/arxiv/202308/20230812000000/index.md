---
draft: false
title: "arXiv @ 2023.08.12"
date: 2023-08-12
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.08.12"
    identifier: arxiv_20230812
    parent: 202308_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.LG (11)](#cslg-11)
- [cs.CV (28)](#cscv-28)
- [cs.SI (5)](#cssi-5)
- [eess.IV (6)](#eessiv-6)
- [cs.SE (3)](#csse-3)
- [cs.HC (1)](#cshc-1)
- [cs.SD (1)](#cssd-1)
- [cs.AI (9)](#csai-9)
- [cs.IR (2)](#csir-2)
- [cs.CL (13)](#cscl-13)
- [cs.NE (1)](#csne-1)
- [stat.ML (1)](#statml-1)
- [cs.DB (1)](#csdb-1)
- [stat.ME (1)](#statme-1)
- [cs.RO (1)](#csro-1)
- [cs.CR (2)](#cscr-2)
- [cs.NI (2)](#csni-2)

## cs.LG (11)



### (1/88) Composable Core-sets for Diversity Approximation on Multi-Dataset Streams (Stephanie Wang et al., 2023)

{{<citation>}}

Stephanie Wang, Michael Flynn, Fangyu Luo. (2023)  
**Composable Core-sets for Diversity Approximation on Multi-Dataset Streams**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05878v1)  

---


**ABSTRACT**  
Core-sets refer to subsets of data that maximize some function that is commonly a diversity or group requirement. These subsets are used in place of the original data to accomplish a given task with comparable or even enhanced performance if biases are removed. Composable core-sets are core-sets with the property that subsets of the core set can be unioned together to obtain an approximation for the original data; lending themselves to be used for streamed or distributed data. Recent work has focused on the use of core-sets for training machine learning models. Preceding solutions such as CRAIG have been proven to approximate gradient descent while providing a reduced training time. In this paper, we introduce a core-set construction algorithm for constructing composable core-sets to summarize streamed data for use in active learning environments. If combined with techniques such as CRAIG and heuristics to enhance construction speed, composable core-sets could be used for real time training of models when the amount of sensor data is large. We provide empirical analysis by considering extrapolated data for the runtime of such a brute force algorithm. This algorithm is then analyzed for efficiency through averaged empirical regression and key results and improvements are suggested for further research on the topic.

{{</citation>}}


### (2/88) Revisiting N-CNN for Clinical Practice (Leonardo Antunes Ferreira et al., 2023)

{{<citation>}}

Leonardo Antunes Ferreira, Lucas Pereira Carlini, Gabriel de Almeida Sá Coutrin, Tatiany Marcondes Heideirich, Marina Carvalho de Moraes Barros, Ruth Guinsburg, Carlos Eduardo Thomaz. (2023)  
**Revisiting N-CNN for Clinical Practice**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Clinical  
[Paper Link](http://arxiv.org/abs/2308.05877v1)  

---


**ABSTRACT**  
This paper revisits the Neonatal Convolutional Neural Network (N-CNN) by optimizing its hyperparameters and evaluating how they affect its classification metrics, explainability and reliability, discussing their potential impact in clinical practice. We have chosen hyperparameters that do not modify the original N-CNN architecture, but mainly modify its learning rate and training regularization. The optimization was done by evaluating the improvement in F1 Score for each hyperparameter individually, and the best hyperparameters were chosen to create a Tuned N-CNN. We also applied soft labels derived from the Neonatal Facial Coding System, proposing a novel approach for training facial expression classification models for neonatal pain assessment. Interestingly, while the Tuned N-CNN results point towards improvements in classification metrics and explainability, these improvements did not directly translate to calibration performance. We believe that such insights might have the potential to contribute to the development of more reliable pain evaluation tools for newborns, aiding healthcare professionals in delivering appropriate interventions and improving patient outcomes.

{{</citation>}}


### (3/88) A Comparison of Classical and Deep Reinforcement Learning Methods for HVAC Control (Marshall Wang et al., 2023)

{{<citation>}}

Marshall Wang, John Willes, Thomas Jiralerspong, Matin Moezzi. (2023)  
**A Comparison of Classical and Deep Reinforcement Learning Methods for HVAC Control**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-SY, cs.LG, eess-SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.05711v1)  

---


**ABSTRACT**  
Reinforcement learning (RL) is a promising approach for optimizing HVAC control. RL offers a framework for improving system performance, reducing energy consumption, and enhancing cost efficiency. We benchmark two popular classical and deep RL methods (Q-Learning and Deep-Q-Networks) across multiple HVAC environments and explore the practical consideration of model hyper-parameter selection and reward tuning. The findings provide insight for configuring RL agents in HVAC systems, promoting energy-efficient and cost-effective operation.

{{</citation>}}


### (4/88) Shadow Datasets, New challenging datasets for Causal Representation Learning (Jiageng Zhu et al., 2023)

{{<citation>}}

Jiageng Zhu, Hanchen Xie, Jianhua Wu, Jiazhi Li, Mahyar Khayatkhoei, Mohamed E. Hussein, Wael AbdAlmageed. (2023)  
**Shadow Datasets, New challenging datasets for Causal Representation Learning**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2308.05707v2)  

---


**ABSTRACT**  
Discovering causal relations among semantic factors is an emergent topic in representation learning. Most causal representation learning (CRL) methods are fully supervised, which is impractical due to costly labeling. To resolve this restriction, weakly supervised CRL methods were introduced. To evaluate CRL performance, four existing datasets, Pendulum, Flow, CelebA(BEARD) and CelebA(SMILE), are utilized. However, existing CRL datasets are limited to simple graphs with few generative factors. Thus we propose two new datasets with a larger number of diverse generative factors and more sophisticated causal graphs. In addition, current real datasets, CelebA(BEARD) and CelebA(SMILE), the originally proposed causal graphs are not aligned with the dataset distributions. Thus, we propose modifications to them.

{{</citation>}}


### (5/88) ReLU and Addition-based Gated RNN (Rickard Brännvall et al., 2023)

{{<citation>}}

Rickard Brännvall, Henrik Forsgren, Fredrik Sandin, Marcus Liwicki. (2023)  
**ReLU and Addition-based Gated RNN**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: AI, LSTM  
[Paper Link](http://arxiv.org/abs/2308.05629v1)  

---


**ABSTRACT**  
We replace the multiplication and sigmoid function of the conventional recurrent gate with addition and ReLU activation. This mechanism is designed to maintain long-term memory for sequence processing but at a reduced computational cost, thereby opening up for more efficient execution or larger models on restricted hardware. Recurrent Neural Networks (RNNs) with gating mechanisms such as LSTM and GRU have been widely successful in learning from sequential data due to their ability to capture long-term dependencies. Conventionally, the update based on current inputs and the previous state history is each multiplied with dynamic weights and combined to compute the next state. However, multiplication can be computationally expensive, especially for certain hardware architectures or alternative arithmetic systems such as homomorphic encryption. It is demonstrated that the novel gating mechanism can capture long-term dependencies for a standard synthetic sequence learning task while significantly reducing computational costs such that execution time is reduced by half on CPU and by one-third under encryption. Experimental results on handwritten text recognition tasks furthermore show that the proposed architecture can be trained to achieve comparable accuracy to conventional GRU and LSTM baselines. The gating mechanism introduced in this paper may enable privacy-preserving AI applications operating under homomorphic encryption by avoiding the multiplication of encrypted variables. It can also support quantization in (unencrypted) plaintext applications, with the potential for substantial performance gains since the addition-based formulation can avoid the expansion to double precision often required for multiplication.

{{</citation>}}


### (6/88) Multi-graph Spatio-temporal Graph Convolutional Network for Traffic Flow Prediction (Weilong Ding et al., 2023)

{{<citation>}}

Weilong Ding, Tianpu Zhang, Jianwu Wang, Zhuofeng Zhao. (2023)  
**Multi-graph Spatio-temporal Graph Convolutional Network for Traffic Flow Prediction**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Graph Convolutional Network  
[Paper Link](http://arxiv.org/abs/2308.05601v1)  

---


**ABSTRACT**  
Inter-city highway transportation is significant for urban life. As one of the key functions in intelligent transportation system (ITS), traffic evaluation always plays significant role nowadays, and daily traffic flow prediction still faces challenges at network-wide toll stations. On the one hand, the data imbalance in practice among various locations deteriorates the performance of prediction. On the other hand, complex correlative spatio-temporal factors cannot be comprehensively employed in long-term duration. In this paper, a prediction method is proposed for daily traffic flow in highway domain through spatio-temporal deep learning. In our method, data normalization strategy is used to deal with data imbalance, due to long-tail distribution of traffic flow at network-wide toll stations. And then, based on graph convolutional network, we construct networks in distinct semantics to capture spatio-temporal features. Beside that, meteorology and calendar features are used by our model in the full connection stage to extra external characteristics of traffic flow. By extensive experiments and case studies in one Chinese provincial highway, our method shows clear improvement in predictive accuracy than baselines and practical benefits in business.

{{</citation>}}


### (7/88) NUPES : Non-Uniform Post-Training Quantization via Power Exponent Search (Edouard Yvinec et al., 2023)

{{<citation>}}

Edouard Yvinec, Arnaud Dapogny, Kevin Bailly. (2023)  
**NUPES : Non-Uniform Post-Training Quantization via Power Exponent Search**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Quantization  
[Paper Link](http://arxiv.org/abs/2308.05600v1)  

---


**ABSTRACT**  
Deep neural network (DNN) deployment has been confined to larger hardware devices due to their expensive computational requirements. This challenge has recently reached another scale with the emergence of large language models (LLMs). In order to reduce both their memory footprint and latency, a promising technique is quantization. It consists in converting floating point representations to low bit-width fixed point representations, usually by assuming a uniform mapping onto a regular grid. This process, referred to in the literature as uniform quantization, may however be ill-suited as most DNN weights and activations follow a bell-shaped distribution. This is even worse on LLMs whose weight distributions are known to exhibit large, high impact, outlier values. In this work, we propose an improvement over the most commonly adopted way to tackle this limitation in deep learning models quantization, namely, non-uniform quantization. NUPES leverages automorphisms to preserve the scalar multiplications. Such transformations are derived from power functions. However, the optimization of the exponent parameter and weight values remains a challenging and novel problem which could not be solved with previous post training optimization techniques which only learn to round up or down weight values in order to preserve the predictive function. We circumvent this limitation with a new paradigm: learning new quantized weights over the entire quantized space. Similarly, we enable the optimization of the power exponent, i.e. the optimization of the quantization operator itself during training by alleviating all the numerical instabilities. The resulting predictive function is compatible with integer-only low-bit inference. We show the ability of the method to achieve state-of-the-art compression rates in both, data-free and data-driven configurations.

{{</citation>}}


### (8/88) AutoGluon-TimeSeries: AutoML for Probabilistic Time Series Forecasting (Oleksandr Shchur et al., 2023)

{{<citation>}}

Oleksandr Shchur, Caner Turkmen, Nick Erickson, Huibin Shen, Alexander Shirkov, Tony Hu, Yuyang Wang. (2023)  
**AutoGluon-TimeSeries: AutoML for Probabilistic Time Series Forecasting**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2308.05566v1)  

---


**ABSTRACT**  
We introduce AutoGluon-TimeSeries - an open-source AutoML library for probabilistic time series forecasting. Focused on ease of use and robustness, AutoGluon-TimeSeries enables users to generate accurate point and quantile forecasts with just 3 lines of Python code. Built on the design philosophy of AutoGluon, AutoGluon-TimeSeries leverages ensembles of diverse forecasting models to deliver high accuracy within a short training time. AutoGluon-TimeSeries combines both conventional statistical models, machine-learning based forecasting approaches, and ensembling techniques. In our evaluation on 29 benchmark datasets, AutoGluon-TimeSeries demonstrates strong empirical performance, outperforming a range of forecasting methods in terms of both point and quantile forecast accuracy, and often even improving upon the best-in-hindsight combination of prior methods.

{{</citation>}}


### (9/88) $\mathcal{G}^2Pxy$: Generative Open-Set Node Classification on Graphs with Proxy Unknowns (Qin Zhang et al., 2023)

{{<citation>}}

Qin Zhang, Zelin Shi, Xiaolin Zhang, Xiaojun Chen, Philippe Fournier-Viger, Shirui Pan. (2023)  
**$\mathcal{G}^2Pxy$: Generative Open-Set Node Classification on Graphs with Proxy Unknowns**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2308.05463v1)  

---


**ABSTRACT**  
Node classification is the task of predicting the labels of unlabeled nodes in a graph. State-of-the-art methods based on graph neural networks achieve excellent performance when all labels are available during training. But in real-life, models are often applied on data with new classes, which can lead to massive misclassification and thus significantly degrade performance. Hence, developing open-set classification methods is crucial to determine if a given sample belongs to a known class. Existing methods for open-set node classification generally use transductive learning with part or all of the features of real unseen class nodes to help with open-set classification. In this paper, we propose a novel generative open-set node classification method, i.e. $\mathcal{G}^2Pxy$, which follows a stricter inductive learning setting where no information about unknown classes is available during training and validation. Two kinds of proxy unknown nodes, inter-class unknown proxies and external unknown proxies are generated via mixup to efficiently anticipate the distribution of novel classes. Using the generated proxies, a closed-set classifier can be transformed into an open-set one, by augmenting it with an extra proxy classifier. Under the constraints of both cross entropy loss and complement entropy loss, $\mathcal{G}^2Pxy$ achieves superior effectiveness for unknown class detection and known class classification, which is validated by experiments on benchmark graph datasets. Moreover, $\mathcal{G}^2Pxy$ does not have specific requirement on the GNN architecture and shows good generalizations.

{{</citation>}}


### (10/88) RTLLM: An Open-Source Benchmark for Design RTL Generation with Large Language Model (Yao Lu et al., 2023)

{{<citation>}}

Yao Lu, Shang Liu, Qijun Zhang, Zhiyao Xie. (2023)  
**RTLLM: An Open-Source Benchmark for Design RTL Generation with Large Language Model**  

---
Primary Category: cs.LG  
Categories: cs-AR, cs-LG, cs.LG  
Keywords: ChatGPT, GPT, GPT-3.5, Language Model  
[Paper Link](http://arxiv.org/abs/2308.05345v1)  

---


**ABSTRACT**  
Inspired by the recent success of large language models (LLMs) like ChatGPT, researchers start to explore the adoption of LLMs for agile hardware design, such as generating design RTL based on natural-language instructions. However, in existing works, their target designs are all relatively simple and in a small scale, and proposed by the authors themselves, making a fair comparison among different LLM solutions challenging. In addition, many prior works only focus on the design correctness, without evaluating the design qualities of generated design RTL. In this work, we propose an open-source benchmark named RTLLM, for generating design RTL with natural language instructions. To systematically evaluate the auto-generated design RTL, we summarized three progressive goals, named syntax goal, functionality goal, and design quality goal. This benchmark can automatically provide a quantitative evaluation of any given LLM-based solution. Furthermore, we propose an easy-to-use yet surprisingly effective prompt engineering technique named self-planning, which proves to significantly boost the performance of GPT-3.5 in our proposed benchmark.

{{</citation>}}


### (11/88) Homophily-enhanced Structure Learning for Graph Clustering (Ming Gu et al., 2023)

{{<citation>}}

Ming Gu, Gaoming Yang, Sheng Zhou, Ning Ma, Jiawei Chen, Qiaoyu Tan, Meihan Liu, Jiajun Bu. (2023)  
**Homophily-enhanced Structure Learning for Graph Clustering**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SI, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2308.05309v2)  

---


**ABSTRACT**  
Graph clustering is a fundamental task in graph analysis, and recent advances in utilizing graph neural networks (GNNs) have shown impressive results. Despite the success of existing GNN-based graph clustering methods, they often overlook the quality of graph structure, which is inherent in real-world graphs due to their sparse and multifarious nature, leading to subpar performance. Graph structure learning allows refining the input graph by adding missing links and removing spurious connections. However, previous endeavors in graph structure learning have predominantly centered around supervised settings, and cannot be directly applied to our specific clustering tasks due to the absence of ground-truth labels. To bridge the gap, we propose a novel method called \textbf{ho}mophily-enhanced structure \textbf{le}arning for graph clustering (HoLe). Our motivation stems from the observation that subtly enhancing the degree of homophily within the graph structure can significantly improve GNNs and clustering outcomes. To realize this objective, we develop two clustering-oriented structure learning modules, i.e., hierarchical correlation estimation and cluster-aware sparsification. The former module enables a more accurate estimation of pairwise node relationships by leveraging guidance from latent and clustering spaces, while the latter one generates a sparsified structure based on the similarity matrix and clustering assignments. Additionally, we devise a joint optimization approach alternating between training the homophily-enhanced structure learning and GNN-based clustering, thereby enforcing their reciprocal effects. Extensive experiments on seven benchmark datasets of various types and scales, across a range of clustering metrics, demonstrate the superiority of HoLe against state-of-the-art baselines.

{{</citation>}}


## cs.CV (28)



### (12/88) Vision Backbone Enhancement via Multi-Stage Cross-Scale Attention (Liang Shang et al., 2023)

{{<citation>}}

Liang Shang, Yanli Liu, Zhengyang Lou, Shuxue Quan, Nagesh Adluru, Bochen Guan, William A. Sethares. (2023)  
**Vision Backbone Enhancement via Multi-Stage Cross-Scale Attention**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2308.05872v2)  

---


**ABSTRACT**  
Convolutional neural networks (CNNs) and vision transformers (ViTs) have achieved remarkable success in various vision tasks. However, many architectures do not consider interactions between feature maps from different stages and scales, which may limit their performance. In this work, we propose a simple add-on attention module to overcome these limitations via multi-stage and cross-scale interactions. Specifically, the proposed Multi-Stage Cross-Scale Attention (MSCSA) module takes feature maps from different stages to enable multi-stage interactions and achieves cross-scale interactions by computing self-attention at different scales based on the multi-stage feature maps. Our experiments on several downstream tasks show that MSCSA provides a significant performance boost with modest additional FLOPs and runtime.

{{</citation>}}


### (13/88) SegDA: Maximum Separable Segment Mask with Pseudo Labels for Domain Adaptive Semantic Segmentation (Anant Khandelwal, 2023)

{{<citation>}}

Anant Khandelwal. (2023)  
**SegDA: Maximum Separable Segment Mask with Pseudo Labels for Domain Adaptive Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2308.05851v1)  

---


**ABSTRACT**  
Unsupervised Domain Adaptation (UDA) aims to solve the problem of label scarcity of the target domain by transferring the knowledge from the label rich source domain. Usually, the source domain consists of synthetic images for which the annotation is easily obtained using the well known computer graphics techniques. However, obtaining annotation for real world images (target domain) require lot of manual annotation effort and is very time consuming because it requires per pixel annotation. To address this problem we propose SegDA module to enhance transfer performance of UDA methods by learning the maximum separable segment representation. This resolves the problem of identifying visually similar classes like pedestrian/rider, sidewalk/road etc. We leveraged Equiangular Tight Frame (ETF) classifier inspired from Neural Collapse for maximal separation between segment classes. This causes the source domain pixel representation to collapse to a single vector forming a simplex vertices which are aligned to the maximal separable ETF classifier. We use this phenomenon to propose the novel architecture for domain adaptation of segment representation for target domain. Additionally, we proposed to estimate the noise in labelling the target domain images and update the decoder for noise correction which encourages the discovery of pixels for classes not identified in pseudo labels. We have used four UDA benchmarks simulating synthetic-to-real, daytime-to-nighttime, clear-to-adverse weather scenarios. Our proposed approach outperforms +2.2 mIoU on GTA -> Cityscapes, +2.0 mIoU on Synthia -> Cityscapes, +5.9 mIoU on Cityscapes -> DarkZurich, +2.6 mIoU on Cityscapes -> ACDC.

{{</citation>}}


### (14/88) Encode-Store-Retrieve: Enhancing Memory Augmentation through Language-Encoded Egocentric Perception (Junxiao Shen et al., 2023)

{{<citation>}}

Junxiao Shen, John Dudley, Per Ola Kristensson. (2023)  
**Encode-Store-Retrieve: Enhancing Memory Augmentation through Language-Encoded Egocentric Perception**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-HC, cs.CV  
Keywords: Augmentation, BLEU, QA  
[Paper Link](http://arxiv.org/abs/2308.05822v1)  

---


**ABSTRACT**  
We depend on our own memory to encode, store, and retrieve our experiences. However, memory lapses can occur. One promising avenue for achieving memory augmentation is through the use of augmented reality head-mounted displays to capture and preserve egocentric videos, a practice commonly referred to as life logging. However, a significant challenge arises from the sheer volume of video data generated through life logging, as the current technology lacks the capability to encode and store such large amounts of data efficiently. Further, retrieving specific information from extensive video archives requires substantial computational power, further complicating the task of quickly accessing desired content. To address these challenges, we propose a memory augmentation system that involves leveraging natural language encoding for video data and storing them in a vector database. This approach harnesses the power of large vision language models to perform the language encoding process. Additionally, we propose using large language models to facilitate natural language querying. Our system underwent extensive evaluation using the QA-Ego4D dataset and achieved state-of-the-art results with a BLEU score of 8.3, outperforming conventional machine learning models that scored between 3.4 and 5.8. Additionally, in a user study, our system received a higher mean response score of 4.13/5 compared to the human participants' score of 2.46/5 on real-life episodic memory tasks.

{{</citation>}}


### (15/88) PlankAssembly: Robust 3D Reconstruction from Three Orthographic Views with Learnt Shape Programs (Wentao Hu et al., 2023)

{{<citation>}}

Wentao Hu, Jia Zheng, Zixin Zhang, Xiaojun Yuan, Jian Yin, Zihan Zhou. (2023)  
**PlankAssembly: Robust 3D Reconstruction from Three Orthographic Views with Learnt Shape Programs**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-GR, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.05744v1)  

---


**ABSTRACT**  
In this paper, we develop a new method to automatically convert 2D line drawings from three orthographic views into 3D CAD models. Existing methods for this problem reconstruct 3D models by back-projecting the 2D observations into 3D space while maintaining explicit correspondence between the input and output. Such methods are sensitive to errors and noises in the input, thus often fail in practice where the input drawings created by human designers are imperfect. To overcome this difficulty, we leverage the attention mechanism in a Transformer-based sequence generation model to learn flexible mappings between the input and output. Further, we design shape programs which are suitable for generating the objects of interest to boost the reconstruction accuracy and facilitate CAD modeling applications. Experiments on a new benchmark dataset show that our method significantly outperforms existing ones when the inputs are noisy or incomplete.

{{</citation>}}


### (16/88) Deformable Mixer Transformer with Gating for Multi-Task Learning of Dense Prediction (Yangyang Xu et al., 2023)

{{<citation>}}

Yangyang Xu, Yibo Yang, Bernard Ghanemm, Lefei Zhang. (2023)  
**Deformable Mixer Transformer with Gating for Multi-Task Learning of Dense Prediction**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2308.05721v2)  

---


**ABSTRACT**  
CNNs and Transformers have their own advantages and both have been widely used for dense prediction in multi-task learning (MTL). Most of the current studies on MTL solely rely on CNN or Transformer. In this work, we present a novel MTL model by combining both merits of deformable CNN and query-based Transformer with shared gating for multi-task learning of dense prediction. This combination may offer a simple and efficient solution owing to its powerful and flexible task-specific learning and advantages of lower cost, less complexity and smaller parameters than the traditional MTL methods. We introduce deformable mixer Transformer with gating (DeMTG), a simple and effective encoder-decoder architecture up-to-date that incorporates the convolution and attention mechanism in a unified network for MTL. It is exquisitely designed to use advantages of each block, and provide deformable and comprehensive features for all tasks from local and global perspective. First, the deformable mixer encoder contains two types of operators: the channel-aware mixing operator leveraged to allow communication among different channels, and the spatial-aware deformable operator with deformable convolution applied to efficiently sample more informative spatial locations. Second, the task-aware gating transformer decoder is used to perform the task-specific predictions, in which task interaction block integrated with self-attention is applied to capture task interaction features, and the task query block integrated with gating attention is leveraged to select corresponding task-specific features. Further, the experiment results demonstrate that the proposed DeMTG uses fewer GFLOPs and significantly outperforms current Transformer-based and CNN-based competitive models on a variety of metrics on three dense prediction datasets. Our code and models are available at https://github.com/yangyangxu0/DeMTG.

{{</citation>}}


### (17/88) Temporally-Adaptive Models for Efficient Video Understanding (Ziyuan Huang et al., 2023)

{{<citation>}}

Ziyuan Huang, Shiwei Zhang, Liang Pan, Zhiwu Qing, Yingya Zhang, Ziwei Liu, Marcelo H. Ang Jr. (2023)  
**Temporally-Adaptive Models for Efficient Video Understanding**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.05787v1)  

---


**ABSTRACT**  
Spatial convolutions are extensively used in numerous deep video models. It fundamentally assumes spatio-temporal invariance, i.e., using shared weights for every location in different frames. This work presents Temporally-Adaptive Convolutions (TAdaConv) for video understanding, which shows that adaptive weight calibration along the temporal dimension is an efficient way to facilitate modeling complex temporal dynamics in videos. Specifically, TAdaConv empowers spatial convolutions with temporal modeling abilities by calibrating the convolution weights for each frame according to its local and global temporal context. Compared to existing operations for temporal modeling, TAdaConv is more efficient as it operates over the convolution kernels instead of the features, whose dimension is an order of magnitude smaller than the spatial resolutions. Further, kernel calibration brings an increased model capacity. Based on this readily plug-in operation TAdaConv as well as its extension, i.e., TAdaConvV2, we construct TAdaBlocks to empower ConvNeXt and Vision Transformer to have strong temporal modeling capabilities. Empirical results show TAdaConvNeXtV2 and TAdaFormer perform competitively against state-of-the-art convolutional and Transformer-based models in various video understanding benchmarks. Our codes and models are released at: https://github.com/alibaba-mmai-research/TAdaConv.

{{</citation>}}


### (18/88) Hard No-Box Adversarial Attack on Skeleton-Based Human Action Recognition with Skeleton-Motion-Informed Gradient (Zhengzhi Lu et al., 2023)

{{<citation>}}

Zhengzhi Lu, He Wang, Ziyi Chang, Guoan Yang, Hubert P. H. Shum. (2023)  
**Hard No-Box Adversarial Attack on Skeleton-Based Human Action Recognition with Skeleton-Motion-Informed Gradient**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: Adversarial Attack  
[Paper Link](http://arxiv.org/abs/2308.05681v1)  

---


**ABSTRACT**  
Recently, methods for skeleton-based human activity recognition have been shown to be vulnerable to adversarial attacks. However, these attack methods require either the full knowledge of the victim (i.e. white-box attacks), access to training data (i.e. transfer-based attacks) or frequent model queries (i.e. black-box attacks). All their requirements are highly restrictive, raising the question of how detrimental the vulnerability is. In this paper, we show that the vulnerability indeed exists. To this end, we consider a new attack task: the attacker has no access to the victim model or the training data or labels, where we coin the term hard no-box attack. Specifically, we first learn a motion manifold where we define an adversarial loss to compute a new gradient for the attack, named skeleton-motion-informed (SMI) gradient. Our gradient contains information of the motion dynamics, which is different from existing gradient-based attack methods that compute the loss gradient assuming each dimension in the data is independent. The SMI gradient can augment many gradient-based attack methods, leading to a new family of no-box attack methods. Extensive evaluation and comparison show that our method imposes a real threat to existing classifiers. They also show that the SMI gradient improves the transferability and imperceptibility of adversarial samples in both no-box and transfer-based black-box settings.

{{</citation>}}


### (19/88) 2D3D-MATR: 2D-3D Matching Transformer for Detection-free Registration between Images and Point Clouds (Minhao Li et al., 2023)

{{<citation>}}

Minhao Li, Zheng Qin, Zhirui Gao, Renjiao Yi, Chenyang Zhu, Yulan Guo, Kai Xu. (2023)  
**2D3D-MATR: 2D-3D Matching Transformer for Detection-free Registration between Images and Point Clouds**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.05667v2)  

---


**ABSTRACT**  
The commonly adopted detect-then-match approach to registration finds difficulties in the cross-modality cases due to the incompatible keypoint detection and inconsistent feature description. We propose, 2D3D-MATR, a detection-free method for accurate and robust registration between images and point clouds. Our method adopts a coarse-to-fine pipeline where it first computes coarse correspondences between downsampled patches of the input image and the point cloud and then extends them to form dense correspondences between pixels and points within the patch region. The coarse-level patch matching is based on transformer which jointly learns global contextual constraints with self-attention and cross-modality correlations with cross-attention. To resolve the scale ambiguity in patch matching, we construct a multi-scale pyramid for each image patch and learn to find for each point patch the best matching image patch at a proper resolution level. Extensive experiments on two public benchmarks demonstrate that 2D3D-MATR outperforms the previous state-of-the-art P2-Net by around $20$ percentage points on inlier ratio and over $10$ points on registration recall. Our code and models are available at https://github.com/minhaolee/2D3DMATR.

{{</citation>}}


### (20/88) Counterfactual Cross-modality Reasoning for Weakly Supervised Video Moment Localization (Zezhong Lv et al., 2023)

{{<citation>}}

Zezhong Lv, Bing Su, Ji-Rong Wen. (2023)  
**Counterfactual Cross-modality Reasoning for Weakly Supervised Video Moment Localization**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2308.05648v1)  

---


**ABSTRACT**  
Video moment localization aims to retrieve the target segment of an untrimmed video according to the natural language query. Weakly supervised methods gains attention recently, as the precise temporal location of the target segment is not always available. However, one of the greatest challenges encountered by the weakly supervised method is implied in the mismatch between the video and language induced by the coarse temporal annotations. To refine the vision-language alignment, recent works contrast the cross-modality similarities driven by reconstructing masked queries between positive and negative video proposals. However, the reconstruction may be influenced by the latent spurious correlation between the unmasked and the masked parts, which distorts the restoring process and further degrades the efficacy of contrastive learning since the masked words are not completely reconstructed from the cross-modality knowledge. In this paper, we discover and mitigate this spurious correlation through a novel proposed counterfactual cross-modality reasoning method. Specifically, we first formulate query reconstruction as an aggregated causal effect of cross-modality and query knowledge. Then by introducing counterfactual cross-modality knowledge into this aggregation, the spurious impact of the unmasked part contributing to the reconstruction is explicitly modeled. Finally, by suppressing the unimodal effect of masked query, we can rectify the reconstructions of video proposals to perform reasonable contrastive learning. Extensive experimental evaluations demonstrate the effectiveness of our proposed method. The code is available at \href{https://github.com/sLdZ0306/CCR}{https://github.com/sLdZ0306/CCR}.

{{</citation>}}


### (21/88) IIHT: Medical Report Generation with Image-to-Indicator Hierarchical Transformer (Keqiang Fan et al., 2023)

{{<citation>}}

Keqiang Fan, Xiaohao Cai, Mahesan Niranjan. (2023)  
**IIHT: Medical Report Generation with Image-to-Indicator Hierarchical Transformer**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs-LG, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.05633v1)  

---


**ABSTRACT**  
Automated medical report generation has become increasingly important in medical analysis. It can produce computer-aided diagnosis descriptions and thus significantly alleviate the doctors' work. Inspired by the huge success of neural machine translation and image captioning, various deep learning methods have been proposed for medical report generation. However, due to the inherent properties of medical data, including data imbalance and the length and correlation between report sequences, the generated reports by existing methods may exhibit linguistic fluency but lack adequate clinical accuracy. In this work, we propose an image-to-indicator hierarchical transformer (IIHT) framework for medical report generation. It consists of three modules, i.e., a classifier module, an indicator expansion module and a generator module. The classifier module first extracts image features from the input medical images and produces disease-related indicators with their corresponding states. The disease-related indicators are subsequently utilised as input for the indicator expansion module, incorporating the "data-text-data" strategy. The transformer-based generator then leverages these extracted features along with image features as auxiliary information to generate final reports. Furthermore, the proposed IIHT method is feasible for radiologists to modify disease indicators in real-world scenarios and integrate the operations into the indicator expansion module for fluent and accurate medical report generation. Extensive experiments and comparisons with state-of-the-art methods under various evaluation metrics demonstrate the great performance of the proposed method.

{{</citation>}}


### (22/88) Self-Supervised Monocular Depth Estimation by Direction-aware Cumulative Convolution Network (Wencheng Han et al., 2023)

{{<citation>}}

Wencheng Han, Junbo Yin, Jianbing Shen. (2023)  
**Self-Supervised Monocular Depth Estimation by Direction-aware Cumulative Convolution Network**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2308.05605v1)  

---


**ABSTRACT**  
Monocular depth estimation is known as an ill-posed task in which objects in a 2D image usually do not contain sufficient information to predict their depth. Thus, it acts differently from other tasks (e.g., classification and segmentation) in many ways. In this paper, we find that self-supervised monocular depth estimation shows a direction sensitivity and environmental dependency in the feature representation. But the current backbones borrowed from other tasks pay less attention to handling different types of environmental information, limiting the overall depth accuracy. To bridge this gap, we propose a new Direction-aware Cumulative Convolution Network (DaCCN), which improves the depth feature representation in two aspects. First, we propose a direction-aware module, which can learn to adjust the feature extraction in each direction, facilitating the encoding of different types of information. Secondly, we design a new cumulative convolution to improve the efficiency for aggregating important environmental information. Experiments show that our method achieves significant improvements on three widely used benchmarks, KITTI, Cityscapes, and Make3D, setting a new state-of-the-art performance on the popular benchmarks with all three types of self-supervision.

{{</citation>}}


### (23/88) Category Feature Transformer for Semantic Segmentation (Quan Tang et al., 2023)

{{<citation>}}

Quan Tang, Chuanjian Liu, Fagui Liu, Yifan Liu, Jun Jiang, Bowen Zhang, Kai Han, Yunhe Wang. (2023)  
**Category Feature Transformer for Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation, Transformer  
[Paper Link](http://arxiv.org/abs/2308.05581v1)  

---


**ABSTRACT**  
Aggregation of multi-stage features has been revealed to play a significant role in semantic segmentation. Unlike previous methods employing point-wise summation or concatenation for feature aggregation, this study proposes the Category Feature Transformer (CFT) that explores the flow of category embedding and transformation among multi-stage features through the prevalent multi-head attention mechanism. CFT learns unified feature embeddings for individual semantic categories from high-level features during each aggregation process and dynamically broadcasts them to high-resolution features. Integrating the proposed CFT into a typical feature pyramid structure exhibits superior performance over a broad range of backbone networks. We conduct extensive experiments on popular semantic segmentation benchmarks. Specifically, the proposed CFT obtains a compelling 55.1% mIoU with greatly reduced model parameters and computations on the challenging ADE20K dataset.

{{</citation>}}


### (24/88) Cross-Domain Product Representation Learning for Rich-Content E-Commerce (Xuehan Bai et al., 2023)

{{<citation>}}

Xuehan Bai, Yan Li, Yanhua Cheng, Wenjie Yang, Quan Chen, Han Li. (2023)  
**Cross-Domain Product Representation Learning for Rich-Content E-Commerce**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2308.05550v1)  

---


**ABSTRACT**  
The proliferation of short video and live-streaming platforms has revolutionized how consumers engage in online shopping. Instead of browsing product pages, consumers are now turning to rich-content e-commerce, where they can purchase products through dynamic and interactive media like short videos and live streams. This emerging form of online shopping has introduced technical challenges, as products may be presented differently across various media domains. Therefore, a unified product representation is essential for achieving cross-domain product recognition to ensure an optimal user search experience and effective product recommendations. Despite the urgent industrial need for a unified cross-domain product representation, previous studies have predominantly focused only on product pages without taking into account short videos and live streams. To fill the gap in the rich-content e-commerce area, in this paper, we introduce a large-scale cRoss-dOmain Product Ecognition dataset, called ROPE. ROPE covers a wide range of product categories and contains over 180,000 products, corresponding to millions of short videos and live streams. It is the first dataset to cover product pages, short videos, and live streams simultaneously, providing the basis for establishing a unified product representation across different media domains. Furthermore, we propose a Cross-dOmain Product rEpresentation framework, namely COPE, which unifies product representations in different domains through multimodal learning including text and vision. Extensive experiments on downstream tasks demonstrate the effectiveness of COPE in learning a joint feature space for all product domains.

{{</citation>}}


### (25/88) Critical Points ++: An Agile Point Cloud Importance Measure for Robust Classification, Adversarial Defense and Explainable AI (Meir Yossef Levi et al., 2023)

{{<citation>}}

Meir Yossef Levi, Guy Gilboa. (2023)  
**Critical Points ++: An Agile Point Cloud Importance Measure for Robust Classification, Adversarial Defense and Explainable AI**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05525v1)  

---


**ABSTRACT**  
The ability to cope accurately and fast with Out-Of-Distribution (OOD) samples is crucial in real-world safety demanding applications. In this work we first study the interplay between critical points of 3D point clouds and OOD samples. Our findings are that common corruptions and outliers are often interpreted as critical points. We generalize the notion of critical points into importance measures. We show that training a classification network based only on less important points dramatically improves robustness, at a cost of minor performance loss on the clean set. We observe that normalized entropy is highly informative for corruption analysis. An adaptive threshold based on normalized entropy is suggested for selecting the set of uncritical points. Our proposed importance measure is extremely fast to compute. We show it can be used for a variety of applications, such as Explainable AI (XAI), Outlier Removal, Uncertainty Estimation, Robust Classification and Adversarial Defense. We reach SOTA results on the two latter tasks.

{{</citation>}}


### (26/88) Look at the Neighbor: Distortion-aware Unsupervised Domain Adaptation for Panoramic Semantic Segmentation (Xu Zheng et al., 2023)

{{<citation>}}

Xu Zheng, Tianbo Pan, Yunhao Luo, Lin Wang. (2023)  
**Look at the Neighbor: Distortion-aware Unsupervised Domain Adaptation for Panoramic Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2308.05493v1)  

---


**ABSTRACT**  
Endeavors have been recently made to transfer knowledge from the labeled pinhole image domain to the unlabeled panoramic image domain via Unsupervised Domain Adaptation (UDA). The aim is to tackle the domain gaps caused by the style disparities and distortion problem from the non-uniformly distributed pixels of equirectangular projection (ERP). Previous works typically focus on transferring knowledge based on geometric priors with specially designed multi-branch network architectures. As a result, considerable computational costs are induced, and meanwhile, their generalization abilities are profoundly hindered by the variation of distortion among pixels. In this paper, we find that the pixels' neighborhood regions of the ERP indeed introduce less distortion. Intuitively, we propose a novel UDA framework that can effectively address the distortion problems for panoramic semantic segmentation. In comparison, our method is simpler, easier to implement, and more computationally efficient. Specifically, we propose distortion-aware attention (DA) capturing the neighboring pixel distribution without using any geometric constraints. Moreover, we propose a class-wise feature aggregation (CFA) module to iteratively update the feature representations with a memory bank. As such, the feature similarity between two domains can be consistently optimized. Extensive experiments show that our method achieves new state-of-the-art performance while remarkably reducing 80% parameters.

{{</citation>}}


### (27/88) YOLO-MS: Rethinking Multi-Scale Representation Learning for Real-time Object Detection (Yuming Chen et al., 2023)

{{<citation>}}

Yuming Chen, Xinbin Yuan, Ruiqi Wu, Jiabao Wang, Qibin Hou, Ming-Ming Cheng. (2023)  
**YOLO-MS: Rethinking Multi-Scale Representation Learning for Real-time Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet, Object Detection, Representation Learning  
[Paper Link](http://arxiv.org/abs/2308.05480v1)  

---


**ABSTRACT**  
We aim at providing the object detection community with an efficient and performant object detector, termed YOLO-MS. The core design is based on a series of investigations on how convolutions with different kernel sizes affect the detection performance of objects at different scales. The outcome is a new strategy that can strongly enhance multi-scale feature representations of real-time object detectors. To verify the effectiveness of our strategy, we build a network architecture, termed YOLO-MS. We train our YOLO-MS on the MS COCO dataset from scratch without relying on any other large-scale datasets, like ImageNet, or pre-trained weights. Without bells and whistles, our YOLO-MS outperforms the recent state-of-the-art real-time object detectors, including YOLO-v7 and RTMDet, when using a comparable number of parameters and FLOPs. Taking the XS version of YOLO-MS as an example, with only 4.5M learnable parameters and 8.7G FLOPs, it can achieve an AP score of 43%+ on MS COCO, which is about 2%+ higher than RTMDet with the same model size. Moreover, our work can also be used as a plug-and-play module for other YOLO models. Typically, our method significantly improves the AP of YOLOv8 from 37%+ to 40%+ with even fewer parameters and FLOPs. Code is available at https://github.com/FishAndWasabi/YOLO-MS.

{{</citation>}}


### (28/88) Benchmarking Algorithmic Bias in Face Recognition: An Experimental Approach Using Synthetic Faces and Human Evaluation (Hao Liang et al., 2023)

{{<citation>}}

Hao Liang, Pietro Perona, Guha Balakrishnan. (2023)  
**Benchmarking Algorithmic Bias in Face Recognition: An Experimental Approach Using Synthetic Faces and Human Evaluation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2308.05441v1)  

---


**ABSTRACT**  
We propose an experimental method for measuring bias in face recognition systems. Existing methods to measure bias depend on benchmark datasets that are collected in the wild and annotated for protected (e.g., race, gender) and non-protected (e.g., pose, lighting) attributes. Such observational datasets only permit correlational conclusions, e.g., "Algorithm A's accuracy is different on female and male faces in dataset X.". By contrast, experimental methods manipulate attributes individually and thus permit causal conclusions, e.g., "Algorithm A's accuracy is affected by gender and skin color."   Our method is based on generating synthetic faces using a neural face generator, where each attribute of interest is modified independently while leaving all other attributes constant. Human observers crucially provide the ground truth on perceptual identity similarity between synthetic image pairs. We validate our method quantitatively by evaluating race and gender biases of three research-grade face recognition models. Our synthetic pipeline reveals that for these algorithms, accuracy is lower for Black and East Asian population subgroups. Our method can also quantify how perceptual changes in attributes affect face identity distances reported by these models. Our large synthetic dataset, consisting of 48,000 synthetic face image pairs (10,200 unique synthetic faces) and 555,000 human annotations (individual attributes and pairwise identity comparisons) is available to researchers in this important area.

{{</citation>}}


### (29/88) Deep Fusion Transformer Network with Weighted Vector-Wise Keypoints Voting for Robust 6D Object Pose Estimation (Jun Zhou et al., 2023)

{{<citation>}}

Jun Zhou, Kai Chen, Linlin Xu, Qi Dou, Jing Qin. (2023)  
**Deep Fusion Transformer Network with Weighted Vector-Wise Keypoints Voting for Robust 6D Object Pose Estimation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.05438v1)  

---


**ABSTRACT**  
One critical challenge in 6D object pose estimation from a single RGBD image is efficient integration of two different modalities, i.e., color and depth. In this work, we tackle this problem by a novel Deep Fusion Transformer~(DFTr) block that can aggregate cross-modality features for improving pose estimation. Unlike existing fusion methods, the proposed DFTr can better model cross-modality semantic correlation by leveraging their semantic similarity, such that globally enhanced features from different modalities can be better integrated for improved information extraction. Moreover, to further improve robustness and efficiency, we introduce a novel weighted vector-wise voting algorithm that employs a non-iterative global optimization strategy for precise 3D keypoint localization while achieving near real-time inference. Extensive experiments show the effectiveness and strong generalization capability of our proposed 3D keypoint voting algorithm. Results on four widely used benchmarks also demonstrate that our method outperforms the state-of-the-art methods by large margins.

{{</citation>}}


### (30/88) Adaptive Low Rank Adaptation of Segment Anything to Salient Object Detection (Ruikai Cui et al., 2023)

{{<citation>}}

Ruikai Cui, Siyuan He, Shi Qiu. (2023)  
**Adaptive Low Rank Adaptation of Segment Anything to Salient Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI, GPT, GPT-4, Google, LLaMA, Object Detection, PaLM  
[Paper Link](http://arxiv.org/abs/2308.05426v1)  

---


**ABSTRACT**  
Foundation models, such as OpenAI's GPT-3 and GPT-4, Meta's LLaMA, and Google's PaLM2, have revolutionized the field of artificial intelligence. A notable paradigm shift has been the advent of the Segment Anything Model (SAM), which has exhibited a remarkable capability to segment real-world objects, trained on 1 billion masks and 11 million images. Although SAM excels in general object segmentation, it lacks the intrinsic ability to detect salient objects, resulting in suboptimal performance in this domain. To address this challenge, we present the Segment Salient Object Model (SSOM), an innovative approach that adaptively fine-tunes SAM for salient object detection by harnessing the low-rank structure inherent in deep learning. Comprehensive qualitative and quantitative evaluations across five challenging RGB benchmark datasets demonstrate the superior performance of our approach, surpassing state-of-the-art methods.

{{</citation>}}


### (31/88) Progressive Spatio-temporal Perception for Audio-Visual Question Answering (Guangyao Li et al., 2023)

{{<citation>}}

Guangyao Li, Wenxuan Hou, Di Hu. (2023)  
**Progressive Spatio-temporal Perception for Audio-Visual Question Answering**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-MM, cs.CV  
Keywords: QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2308.05421v1)  

---


**ABSTRACT**  
Audio-Visual Question Answering (AVQA) task aims to answer questions about different visual objects, sounds, and their associations in videos. Such naturally multi-modal videos are composed of rich and complex dynamic audio-visual components, where most of which could be unrelated to the given questions, or even play as interference in answering the content of interest. Oppositely, only focusing on the question-aware audio-visual content could get rid of influence, meanwhile enabling the model to answer more efficiently. In this paper, we propose a Progressive Spatio-Temporal Perception Network (PSTP-Net), which contains three modules that progressively identify key spatio-temporal regions w.r.t. questions. Specifically, a temporal segment selection module is first introduced to select the most relevant audio-visual segments related to the given question. Then, a spatial region selection module is utilized to choose the most relevant regions associated with the question from the selected temporal segments. To further refine the selection of features, an audio-guided visual attention module is employed to perceive the association between auido and selected spatial regions. Finally, the spatio-temporal features from these modules are integrated for answering the question. Extensive experimental results on the public MUSIC-AVQA and AVQA datasets provide compelling evidence of the effectiveness and efficiency of PSTP-Net. Code is available at: \href{https://github.com/GeWu-Lab/PSTP-Net}{https://github.com/GeWu-Lab/PSTP-Net}

{{</citation>}}


### (32/88) Interaction-aware Joint Attention Estimation Using People Attributes (Chihiro Nakatani et al., 2023)

{{<citation>}}

Chihiro Nakatani, Hiroaki Kawashima, Norimichi Ukita. (2023)  
**Interaction-aware Joint Attention Estimation Using People Attributes**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Transformer  
[Paper Link](http://arxiv.org/abs/2308.05382v1)  

---


**ABSTRACT**  
This paper proposes joint attention estimation in a single image. Different from related work in which only the gaze-related attributes of people are independently employed, (I) their locations and actions are also employed as contextual cues for weighting their attributes, and (ii) interactions among all of these attributes are explicitly modeled in our method. For the interaction modeling, we propose a novel Transformer-based attention network to encode joint attention as low-dimensional features. We introduce a specialized MLP head with positional embedding to the Transformer so that it predicts pixelwise confidence of joint attention for generating the confidence heatmap. This pixelwise prediction improves the heatmap accuracy by avoiding the ill-posed problem in which the high-dimensional heatmap is predicted from the low-dimensional features. The estimated joint attention is further improved by being integrated with general image-based attention estimation. Our method outperforms SOTA methods quantitatively in comparative experiments. Code: https://anonymous.4open.science/r/anonymized_codes-ECA4.

{{</citation>}}


### (33/88) Pseudo-label Alignment for Semi-supervised Instance Segmentation (Jie Hu et al., 2023)

{{<citation>}}

Jie Hu, Chen Chen, Liujuan Cao, Shengchuan Zhang, Annan Shu, Guannan Jiang, Rongrong Ji. (2023)  
**Pseudo-label Alignment for Semi-supervised Instance Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05359v1)  

---


**ABSTRACT**  
Pseudo-labeling is significant for semi-supervised instance segmentation, which generates instance masks and classes from unannotated images for subsequent training. However, in existing pipelines, pseudo-labels that contain valuable information may be directly filtered out due to mismatches in class and mask quality. To address this issue, we propose a novel framework, called pseudo-label aligning instance segmentation (PAIS), in this paper. In PAIS, we devise a dynamic aligning loss (DALoss) that adjusts the weights of semi-supervised loss terms with varying class and mask score pairs. Through extensive experiments conducted on the COCO and Cityscapes datasets, we demonstrate that PAIS is a promising framework for semi-supervised instance segmentation, particularly in cases where labeled data is severely limited. Notably, with just 1\% labeled data, PAIS achieves 21.2 mAP (based on Mask-RCNN) and 19.9 mAP (based on K-Net) on the COCO dataset, outperforming the current state-of-the-art model, \ie, NoisyBoundary with 7.7 mAP, by a margin of over 12 points. Code is available at: \url{https://github.com/hujiecpp/PAIS}.

{{</citation>}}


### (34/88) Towards General and Fast Video Derain via Knowledge Distillation (Defang Cai et al., 2023)

{{<citation>}}

Defang Cai, Pan Mu, Sixian Chan, Zhanpeng Shao, Cong Bai. (2023)  
**Towards General and Fast Video Derain via Knowledge Distillation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV, eess-IV  
Keywords: Knowledge Distillation  
[Paper Link](http://arxiv.org/abs/2308.05346v1)  

---


**ABSTRACT**  
As a common natural weather condition, rain can obscure video frames and thus affect the performance of the visual system, so video derain receives a lot of attention. In natural environments, rain has a wide variety of streak types, which increases the difficulty of the rain removal task. In this paper, we propose a Rain Review-based General video derain Network via knowledge distillation (named RRGNet) that handles different rain streak types with one pre-training weight. Specifically, we design a frame grouping-based encoder-decoder network that makes full use of the temporal information of the video. Further, we use the old task model to guide the current model in learning new rain streak types while avoiding forgetting. To consolidate the network's ability to derain, we design a rain review module to play back data from old tasks for the current model. The experimental results show that our developed general method achieves the best results in terms of running speed and derain effect.

{{</citation>}}


### (35/88) Adv-Inpainting: Generating Natural and Transferable Adversarial Patch via Attention-guided Feature Fusion (Yanjie Li et al., 2023)

{{<citation>}}

Yanjie Li, Mingxing Duan, Bin Xiao. (2023)  
**Adv-Inpainting: Generating Natural and Transferable Adversarial Patch via Attention-guided Feature Fusion**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2308.05320v1)  

---


**ABSTRACT**  
The rudimentary adversarial attacks utilize additive noise to attack facial recognition (FR) models. However, because manipulating the total face is impractical in the physical setting, most real-world FR attacks are based on adversarial patches, which limit perturbations to a small area. Previous adversarial patch attacks often resulted in unnatural patterns and clear boundaries that were easily noticeable. In this paper, we argue that generating adversarial patches with plausible content can result in stronger transferability than using additive noise or directly sampling from the latent space. To generate natural-looking and highly transferable adversarial patches, we propose an innovative two-stage coarse-to-fine attack framework called Adv-Inpainting. In the first stage, we propose an attention-guided StyleGAN (Att-StyleGAN) that adaptively combines texture and identity features based on the attention map to generate high-transferable and natural adversarial patches. In the second stage, we design a refinement network with a new boundary variance loss to further improve the coherence between the patch and its surrounding area. Experiment results demonstrate that Adv-Inpainting is stealthy and can produce adversarial patches with stronger transferability and improved visual quality than previous adversarial patch attacks.

{{</citation>}}


### (36/88) RLSAC: Reinforcement Learning enhanced Sample Consensus for End-to-End Robust Estimation (Chang Nie et al., 2023)

{{<citation>}}

Chang Nie, Guangming Wang, Zhe Liu, Luca Cavalli, Marc Pollefeys, Hesheng Wang. (2023)  
**RLSAC: Reinforcement Learning enhanced Sample Consensus for End-to-End Robust Estimation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.05318v1)  

---


**ABSTRACT**  
Robust estimation is a crucial and still challenging task, which involves estimating model parameters in noisy environments. Although conventional sampling consensus-based algorithms sample several times to achieve robustness, these algorithms cannot use data features and historical information effectively. In this paper, we propose RLSAC, a novel Reinforcement Learning enhanced SAmple Consensus framework for end-to-end robust estimation. RLSAC employs a graph neural network to utilize both data and memory features to guide exploring directions for sampling the next minimum set. The feedback of downstream tasks serves as the reward for unsupervised training. Therefore, RLSAC can avoid differentiating to learn the features and the feedback of downstream tasks for end-to-end robust estimation. In addition, RLSAC integrates a state transition module that encodes both data and memory features. Our experimental results demonstrate that RLSAC can learn from features to gradually explore a better hypothesis. Through analysis, it is apparent that RLSAC can be easily transferred to other sampling consensus-based robust estimation tasks. To the best of our knowledge, RLSAC is also the first method that uses reinforcement learning to sample consensus for end-to-end robust estimation. We release our codes at https://github.com/IRMVLab/RLSAC.

{{</citation>}}


### (37/88) Double-chain Constraints for 3D Human Pose Estimation in Images and Videos (Hongbo Kang et al., 2023)

{{<citation>}}

Hongbo Kang, Yong Wang, Mengyuan Liu, Doudou Wu, Peng Liu, Wenming Yang. (2023)  
**Double-chain Constraints for 3D Human Pose Estimation in Images and Videos**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.05298v1)  

---


**ABSTRACT**  
Reconstructing 3D poses from 2D poses lacking depth information is particularly challenging due to the complexity and diversity of human motion. The key is to effectively model the spatial constraints between joints to leverage their inherent dependencies. Thus, we propose a novel model, called Double-chain Graph Convolutional Transformer (DC-GCT), to constrain the pose through a double-chain design consisting of local-to-global and global-to-local chains to obtain a complex representation more suitable for the current human pose. Specifically, we combine the advantages of GCN and Transformer and design a Local Constraint Module (LCM) based on GCN and a Global Constraint Module (GCM) based on self-attention mechanism as well as a Feature Interaction Module (FIM). The proposed method fully captures the multi-level dependencies between human body joints to optimize the modeling capability of the model. Moreover, we propose a method to use temporal information into the single-frame model by guiding the video sequence embedding through the joint embedding of the target frame, with negligible increase in computational cost. Experimental results demonstrate that DC-GCT achieves state-of-the-art performance on two challenging datasets (Human3.6M and MPI-INF-3DHP). Notably, our model achieves state-of-the-art performance on all action categories in the Human3.6M dataset using detected 2D poses from CPN, and our code is available at: https://github.com/KHB1698/DC-GCT.

{{</citation>}}


### (38/88) Fine-Grained Self-Supervised Learning with Jigsaw Puzzles for Medical Image Classification (Wongi Park et al., 2023)

{{<citation>}}

Wongi Park, Jongbin Ryu. (2023)  
**Fine-Grained Self-Supervised Learning with Jigsaw Puzzles for Medical Image Classification**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Image Classification, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2308.05770v1)  

---


**ABSTRACT**  
Classifying fine-grained lesions is challenging due to minor and subtle differences in medical images. This is because learning features of fine-grained lesions with highly minor differences is very difficult in training deep neural networks. Therefore, in this paper, we introduce Fine-Grained Self-Supervised Learning(FG-SSL) method for classifying subtle lesions in medical images. The proposed method progressively learns the model through hierarchical block such that the cross-correlation between the fine-grained Jigsaw puzzle and regularized original images is close to the identity matrix. We also apply hierarchical block for progressive fine-grained learning, which extracts different information in each step, to supervised learning for discovering subtle differences. Our method does not require an asymmetric model, nor does a negative sampling strategy, and is not sensitive to batch size. We evaluate the proposed fine-grained self-supervised learning method on comprehensive experiments using various medical image recognition datasets. In our experiments, the proposed method performs favorably compared to existing state-of-the-art approaches on the widely-used ISIC2018, APTOS2019, and ISIC2017 datasets.

{{</citation>}}


### (39/88) Informative Scene Graph Generation via Debiasing (Lianli Gao et al., 2023)

{{<citation>}}

Lianli Gao, Xinyu Lyu, Yuyu Guo, Yuxuan Hu, Yuan-Fang Li, Lu Xu, Heng Tao Shen, Jingkuan Song. (2023)  
**Informative Scene Graph Generation via Debiasing**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: QA, Transformer  
[Paper Link](http://arxiv.org/abs/2308.05286v1)  

---


**ABSTRACT**  
Scene graph generation aims to detect visual relationship triplets, (subject, predicate, object). Due to biases in data, current models tend to predict common predicates, e.g. "on" and "at", instead of informative ones, e.g. "standing on" and "looking at". This tendency results in the loss of precise information and overall performance. If a model only uses "stone on road" rather than "stone blocking road" to describe an image, it may be a grave misunderstanding. We argue that this phenomenon is caused by two imbalances: semantic space level imbalance and training sample level imbalance. For this problem, we propose DB-SGG, an effective framework based on debiasing but not the conventional distribution fitting. It integrates two components: Semantic Debiasing (SD) and Balanced Predicate Learning (BPL), for these imbalances. SD utilizes a confusion matrix and a bipartite graph to construct predicate relationships. BPL adopts a random undersampling strategy and an ambiguity removing strategy to focus on informative predicates. Benefiting from the model-agnostic process, our method can be easily applied to SGG models and outperforms Transformer by 136.3%, 119.5%, and 122.6% on mR@20 at three SGG sub-tasks on the SGG-VG dataset. Our method is further verified on another complex SGG dataset (SGG-GQA) and two downstream tasks (sentence-to-graph retrieval and image captioning).

{{</citation>}}


## cs.SI (5)



### (40/88) Using Twitter Data to Determine Hurricane Category: An Experiment (Songhui Yue et al., 2023)

{{<citation>}}

Songhui Yue, Jyothsna Kondari, Aibek Musaev, Randy K. Smith, Songqing Yue. (2023)  
**Using Twitter Data to Determine Hurricane Category: An Experiment**  

---
Primary Category: cs.SI  
Categories: cs-LG, cs-SI, cs.SI  
Keywords: Twitter  
[Paper Link](http://arxiv.org/abs/2308.05866v1)  

---


**ABSTRACT**  
Social media posts contain an abundant amount of information about public opinion on major events, especially natural disasters such as hurricanes. Posts related to an event, are usually published by the users who live near the place of the event at the time of the event. Special correlation between the social media data and the events can be obtained using data mining approaches. This paper presents research work to find the mappings between social media data and the severity level of a disaster. Specifically, we have investigated the Twitter data posted during hurricanes Harvey and Irma, and attempted to find the correlation between the Twitter data of a specific area and the hurricane level in that area. Our experimental results indicate a positive correlation between them. We also present a method to predict the hurricane category for a specific area using relevant Twitter data.

{{</citation>}}


### (41/88) Complex Network Effects on the Robustness of Graph Convolutional Networks (Benjamin A. Miller et al., 2023)

{{<citation>}}

Benjamin A. Miller, Kevin Chan, Tina Eliassi-Rad. (2023)  
**Complex Network Effects on the Robustness of Graph Convolutional Networks**  

---
Primary Category: cs.SI  
Categories: cs-SI, cs.SI  
Keywords: Graph Convolutional Network  
[Paper Link](http://arxiv.org/abs/2308.05498v1)  

---


**ABSTRACT**  
Vertex classification -- the problem of identifying the class labels of nodes in a graph -- has applicability in a wide variety of domains. Examples include classifying subject areas of papers in citation networks or roles of machines in a computer network. Vertex classification using graph convolutional networks is susceptible to targeted poisoning attacks, in which both graph structure and node attributes can be changed in an attempt to misclassify a target node. This vulnerability decreases users' confidence in the learning method and can prevent adoption in high-stakes contexts. Defenses have also been proposed, focused on filtering edges before creating the model or aggregating information from neighbors more robustly. This paper considers an alternative: we leverage network characteristics in the training data selection process to improve robustness of vertex classifiers.   We propose two alternative methods of selecting training data: (1) to select the highest-degree nodes and (2) to iteratively select the node with the most neighbors minimally connected to the training set. In the datasets on which the original attack was demonstrated, we show that changing the training set can make the network much harder to attack. To maintain a given probability of attack success, the adversary must use far more perturbations; often a factor of 2--4 over the random training baseline. These training set selection methods often work in conjunction with the best recently published defenses to provide even greater robustness. While increasing the amount of randomly selected training data sometimes results in a more robust classifier, the proposed methods increase robustness substantially more. We also run a simulation study in which we demonstrate conditions under which each of the two methods outperforms the other, controlling for the graph topology, homophily of the labels, and node attributes.

{{</citation>}}


### (42/88) Preemptive Detection of Fake Accounts on Social Networks via Multi-Class Preferential Attachment Classifiers (Adam Breuer et al., 2023)

{{<citation>}}

Adam Breuer, Nazanin Khosravani, Michael Tingley, Bradford Cottel. (2023)  
**Preemptive Detection of Fake Accounts on Social Networks via Multi-Class Preferential Attachment Classifiers**  

---
Primary Category: cs.SI  
Categories: cs-CR, cs-LG, cs-SI, cs.SI  
Keywords: Social Network  
[Paper Link](http://arxiv.org/abs/2308.05353v1)  

---


**ABSTRACT**  
In this paper, we describe a new algorithm called Preferential Attachment k-class Classifier (PreAttacK) for detecting fake accounts in a social network. Recently, several algorithms have obtained high accuracy on this problem. However, they have done so by relying on information about fake accounts' friendships or the content they share with others--the very things we seek to prevent. PreAttacK represents a significant departure from these approaches. We provide some of the first detailed distributional analyses of how new fake (and real) accounts first attempt to request friends after joining a major network (Facebook). We show that even before a new account has made friends or shared content, these initial friend request behaviors evoke a natural multi-class extension of the canonical Preferential Attachment model of social network growth. We use this model to derive a new algorithm, PreAttacK. We prove that in relevant problem instances, PreAttacK near-optimally approximates the posterior probability that a new account is fake under this multi-class Preferential Attachment model of new accounts' (not-yet-answered) friend requests. These are the first provable guarantees for fake account detection that apply to new users, and that do not require strong homophily assumptions. This principled approach also makes PreAttacK the only algorithm with provable guarantees that obtains state-of-the-art performance on new users on the global Facebook network, where it converges to AUC=0.9 after new users send + receive a total of just 20 not-yet-answered friend requests. For comparison, state-of-the-art benchmarks do not obtain this AUC even after observing additional data on new users' first 100 friend requests. Thus, unlike mainstream algorithms, PreAttacK converges before the median new fake account has made a single friendship (accepted friend request) with a human.

{{</citation>}}


### (43/88) DegUIL: Degree-aware Graph Neural Networks for Long-tailed User Identity Linkage (Meixiu Long et al., 2023)

{{<citation>}}

Meixiu Long, Siyuan Chen, Xin Du, Jiahai Wang. (2023)  
**DegUIL: Degree-aware Graph Neural Networks for Long-tailed User Identity Linkage**  

---
Primary Category: cs.SI  
Categories: cs-SI, cs.SI  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2308.05322v1)  

---


**ABSTRACT**  
User identity linkage (UIL), matching accounts of a person on different social networks, is a fundamental task in cross-network data mining. Recent works have achieved promising results by exploiting graph neural networks (GNNs) to capture network structure. However, they rarely analyze the realistic node-level bottlenecks that hinder UIL's performance. First, node degrees in a graph vary widely and are long-tailed. A significant fraction of tail nodes with small degrees are underrepresented due to limited structural information, degrading linkage performance seriously. The second bottleneck usually overlooked is super head nodes. It is commonly accepted that head nodes perform well. However, we find that some of them with super high degrees also have difficulty aligning counterparts, due to noise introduced by the randomness of following friends in real-world social graphs. In pursuit of learning ideal representations for these two groups of nodes, this paper proposes a degree-aware model named DegUIL to narrow the degree gap. To this end, our model complements missing neighborhoods for tail nodes and discards redundant structural information for super head nodes in embeddings respectively. Specifically, the neighboring bias is predicted and corrected locally by two modules, which are trained using the knowledge from structurally adequate head nodes. As a result, ideal neighborhoods are obtained for meaningful aggregation in GNNs. Extensive experiments demonstrate the superiority of our model. Our data and code can be found at https://github.com/Longmeix/DegUIL.

{{</citation>}}


### (44/88) Investigating disaster response through social media data and the Susceptible-Infected-Recovered (SIR) model: A case study of 2020 Western U.S. wildfire season (Zihui Ma et al., 2023)

{{<citation>}}

Zihui Ma, Lingyao Li, Libby Hemphill, Gregory B. Baecher. (2023)  
**Investigating disaster response through social media data and the Susceptible-Infected-Recovered (SIR) model: A case study of 2020 Western U.S. wildfire season**  

---
Primary Category: cs.SI  
Categories: cs-CL, cs-IR, cs-LG, cs-SI, cs.SI  
Keywords: BERT, Transformer, Transformers, Twitter  
[Paper Link](http://arxiv.org/abs/2308.05281v1)  

---


**ABSTRACT**  
Effective disaster response is critical for affected communities. Responders and decision-makers would benefit from reliable, timely measures of the issues impacting their communities during a disaster, and social media offers a potentially rich data source. Social media can reflect public concerns and demands during a disaster, offering valuable insights for decision-makers to understand evolving situations and optimize resource allocation. We used Bidirectional Encoder Representations from Transformers (BERT) topic modeling to cluster topics from Twitter data. Then, we conducted a temporal-spatial analysis to examine the distribution of these topics across different regions during the 2020 western U.S. wildfire season. Our results show that Twitter users mainly focused on three topics:"health impact," "damage," and "evacuation." We used the Susceptible-Infected-Recovered (SIR) theory to explore the magnitude and velocity of topic diffusion on Twitter. The results displayed a clear relationship between topic trends and wildfire propagation patterns. The estimated parameters obtained from the SIR model in selected cities revealed that residents exhibited a high level of several concerns during the wildfire. Our study details how the SIR model and topic modeling using social media data can provide decision-makers with a quantitative approach to measure disaster response and support their decision-making processes.

{{</citation>}}


## eess.IV (6)



### (45/88) The Multi-modality Cell Segmentation Challenge: Towards Universal Solutions (Jun Ma et al., 2023)

{{<citation>}}

Jun Ma, Ronald Xie, Shamini Ayyadhury, Cheng Ge, Anubha Gupta, Ritu Gupta, Song Gu, Yao Zhang, Gihun Lee, Joonkee Kim, Wei Lou, Haofeng Li, Eric Upschulte, Timo Dickscheid, José Guilherme de Almeida, Yixin Wang, Lin Han, Xin Yang, Marco Labagnara, Sahand Jamal Rahi, Carly Kempster, Alice Pollitt, Leon Espinosa, Tâm Mignot, Jan Moritz Middeke, Jan-Niklas Eckardt, Wangkai Li, Zhaoyang Li, Xiaochen Cai, Bizhe Bai, Noah F. Greenwald, David Van Valen, Erin Weisbart, Beth A. Cimini, Zhuoshi Li, Chao Zuo, Oscar Brück, Gary D. Bader, Bo Wang. (2023)  
**The Multi-modality Cell Segmentation Challenge: Towards Universal Solutions**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV, q-bio-QM  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.05864v1)  

---


**ABSTRACT**  
Cell segmentation is a critical step for quantitative single-cell analysis in microscopy images. Existing cell segmentation methods are often tailored to specific modalities or require manual interventions to specify hyperparameters in different experimental settings. Here, we present a multi-modality cell segmentation benchmark, comprising over 1500 labeled images derived from more than 50 diverse biological experiments. The top participants developed a Transformer-based deep-learning algorithm that not only exceeds existing methods, but can also be applied to diverse microscopy images across imaging platforms and tissue types without manual parameter adjustments. This benchmark and the improved algorithm offer promising avenues for more accurate and versatile cell analysis in microscopy imaging.

{{</citation>}}


### (46/88) Unleashing the Strengths of Unlabeled Data in Pan-cancer Abdominal Organ Quantification: the FLARE22 Challenge (Jun Ma et al., 2023)

{{<citation>}}

Jun Ma, Yao Zhang, Song Gu, Cheng Ge, Shihao Ma, Adamo Young, Cheng Zhu, Kangkang Meng, Xin Yang, Ziyan Huang, Fan Zhang, Wentao Liu, YuanKe Pan, Shoujin Huang, Jiacheng Wang, Mingze Sun, Weixin Xu, Dengqiang Jia, Jae Won Choi, Natália Alves, Bram de Wilde, Gregor Koehler, Yajun Wu, Manuel Wiesenfarth, Qiongjie Zhu, Guoqiang Dong, Jian He, the FLARE Challenge Consortium, Bo Wang. (2023)  
**Unleashing the Strengths of Unlabeled Data in Pan-cancer Abdominal Organ Quantification: the FLARE22 Challenge**  

---
Primary Category: eess.IV  
Categories: cs-AI, cs-CV, eess-IV, eess.IV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05862v1)  

---


**ABSTRACT**  
Quantitative organ assessment is an essential step in automated abdominal disease diagnosis and treatment planning. Artificial intelligence (AI) has shown great potential to automatize this process. However, most existing AI algorithms rely on many expert annotations and lack a comprehensive evaluation of accuracy and efficiency in real-world multinational settings. To overcome these limitations, we organized the FLARE 2022 Challenge, the largest abdominal organ analysis challenge to date, to benchmark fast, low-resource, accurate, annotation-efficient, and generalized AI algorithms. We constructed an intercontinental and multinational dataset from more than 50 medical groups, including Computed Tomography (CT) scans with different races, diseases, phases, and manufacturers. We independently validated that a set of AI algorithms achieved a median Dice Similarity Coefficient (DSC) of 90.0\% by using 50 labeled scans and 2000 unlabeled scans, which can significantly reduce annotation requirements. The best-performing algorithms successfully generalized to holdout external validation sets, achieving a median DSC of 89.5\%, 90.9\%, and 88.3\% on North American, European, and Asian cohorts, respectively. They also enabled automatic extraction of key organ biology features, which was labor-intensive with traditional manual measurements. This opens the potential to use unlabeled data to boost performance and alleviate annotation shortages for modern AI models.

{{</citation>}}


### (47/88) Leverage Weakly Annotation to Pixel-wise Annotation via Zero-shot Segment Anything Model for Molecular-empowered Learning (Xueyuan Li et al., 2023)

{{<citation>}}

Xueyuan Li, Ruining Deng, Yucheng Tang, Shunxing Bao, Haichun Yang, Yuankai Huo. (2023)  
**Leverage Weakly Annotation to Pixel-wise Annotation via Zero-shot Segment Anything Model for Molecular-empowered Learning**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05785v1)  

---


**ABSTRACT**  
Precise identification of multiple cell classes in high-resolution Giga-pixel whole slide imaging (WSI) is critical for various clinical scenarios. Building an AI model for this purpose typically requires pixel-level annotations, which are often unscalable and must be done by skilled domain experts (e.g., pathologists). However, these annotations can be prone to errors, especially when distinguishing between intricate cell types (e.g., podocytes and mesangial cells) using only visual inspection. Interestingly, a recent study showed that lay annotators, when using extra immunofluorescence (IF) images for reference (referred to as molecular-empowered learning), can sometimes outperform domain experts in labeling. Despite this, the resource-intensive task of manual delineation remains a necessity during the annotation process. In this paper, we explore the potential of bypassing pixel-level delineation by employing the recent segment anything model (SAM) on weak box annotation in a zero-shot learning approach. Specifically, we harness SAM's ability to produce pixel-level annotations from box annotations and utilize these SAM-generated labels to train a segmentation model. Our findings show that the proposed SAM-assisted molecular-empowered learning (SAM-L) can diminish the labeling efforts for lay annotators by only requiring weak box annotations. This is achieved without compromising annotation accuracy or the performance of the deep learning-based segmentation. This research represents a significant advancement in democratizing the annotation process for training pathological image segmentation, relying solely on non-expert annotators.

{{</citation>}}


### (48/88) Attention-based 3D CNN with Multi-layer Features for Alzheimer's Disease Diagnosis using Brain Images (Yanteng Zhang et al., 2023)

{{<citation>}}

Yanteng Zhang, Qizhi Teng, Xiaohai He, Tong Niu, Lipei Zhang, Yan Liu, Chao Ren. (2023)  
**Attention-based 3D CNN with Multi-layer Features for Alzheimer's Disease Diagnosis using Brain Images**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2308.05655v1)  

---


**ABSTRACT**  
Structural MRI and PET imaging play an important role in the diagnosis of Alzheimer's disease (AD), showing the morphological changes and glucose metabolism changes in the brain respectively. The manifestations in the brain image of some cognitive impairment patients are relatively inconspicuous, for example, it still has difficulties in achieving accurate diagnosis through sMRI in clinical practice. With the emergence of deep learning, convolutional neural network (CNN) has become a valuable method in AD-aided diagnosis, but some CNN methods cannot effectively learn the features of brain image, making the diagnosis of AD still presents some challenges. In this work, we propose an end-to-end 3D CNN framework for AD diagnosis based on ResNet, which integrates multi-layer features obtained under the effect of the attention mechanism to better capture subtle differences in brain images. The attention maps showed our model can focus on key brain regions related to the disease diagnosis. Our method was verified in ablation experiments with two modality images on 792 subjects from the ADNI database, where AD diagnostic accuracies of 89.71% and 91.18% were achieved based on sMRI and PET respectively, and also outperformed some state-of-the-art methods.

{{</citation>}}


### (49/88) TriDo-Former: A Triple-Domain Transformer for Direct PET Reconstruction from Low-Dose Sinograms (Jiaqi Cui et al., 2023)

{{<citation>}}

Jiaqi Cui, Pinxian Zeng, Xinyi Zeng, Peng Wang, Xi Wu, Jiliu Zhou, Yan Wang, Dinggang Shen. (2023)  
**TriDo-Former: A Triple-Domain Transformer for Direct PET Reconstruction from Low-Dose Sinograms**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.05365v1)  

---


**ABSTRACT**  
To obtain high-quality positron emission tomography (PET) images while minimizing radiation exposure, various methods have been proposed for reconstructing standard-dose PET (SPET) images from low-dose PET (LPET) sinograms directly. However, current methods often neglect boundaries during sinogram-to-image reconstruction, resulting in high-frequency distortion in the frequency domain and diminished or fuzzy edges in the reconstructed images. Furthermore, the convolutional architectures, which are commonly used, lack the ability to model long-range non-local interactions, potentially leading to inaccurate representations of global structures. To alleviate these problems, we propose a transformer-based model that unites triple domains of sinogram, image, and frequency for direct PET reconstruction, namely TriDo-Former. Specifically, the TriDo-Former consists of two cascaded networks, i.e., a sinogram enhancement transformer (SE-Former) for denoising the input LPET sinograms and a spatial-spectral reconstruction transformer (SSR-Former) for reconstructing SPET images from the denoised sinograms. Different from the vanilla transformer that splits an image into 2D patches, based specifically on the PET imaging mechanism, our SE-Former divides the sinogram into 1D projection view angles to maintain its inner-structure while denoising, preventing the noise in the sinogram from prorogating into the image domain. Moreover, to mitigate high-frequency distortion and improve reconstruction details, we integrate global frequency parsers (GFPs) into SSR-Former. The GFP serves as a learnable frequency filter that globally adjusts the frequency components in the frequency domain, enforcing the network to restore high-frequency details resembling real SPET images. Validations on a clinical dataset demonstrate that our TriDo-Former outperforms the state-of-the-art methods qualitatively and quantitatively.

{{</citation>}}


### (50/88) From CNN to Transformer: A Review of Medical Image Segmentation Models (Wenjian Yao et al., 2023)

{{<citation>}}

Wenjian Yao, Jiajun Bai, Wei Liao, Yuheng Chen, Mengjuan Liu, Yao Xie. (2023)  
**From CNN to Transformer: A Review of Medical Image Segmentation Models**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2308.05305v1)  

---


**ABSTRACT**  
Medical image segmentation is an important step in medical image analysis, especially as a crucial prerequisite for efficient disease diagnosis and treatment. The use of deep learning for image segmentation has become a prevalent trend. The widely adopted approach currently is U-Net and its variants. Additionally, with the remarkable success of pre-trained models in natural language processing tasks, transformer-based models like TransUNet have achieved desirable performance on multiple medical image segmentation datasets. In this paper, we conduct a survey of the most representative four medical image segmentation models in recent years. We theoretically analyze the characteristics of these models and quantitatively evaluate their performance on two benchmark datasets (i.e., Tuberculosis Chest X-rays and ovarian tumors). Finally, we discuss the main challenges and future trends in medical image segmentation. Our work can assist researchers in the related field to quickly establish medical segmentation models tailored to specific regions.

{{</citation>}}


## cs.SE (3)



### (51/88) Proposing a Dynamic Executive Microservices Architecture Model for AI Systems (Mahyar Karimi et al., 2023)

{{<citation>}}

Mahyar Karimi, Ahmad Abdollahzadeh Barfroush. (2023)  
**Proposing a Dynamic Executive Microservices Architecture Model for AI Systems**  

---
Primary Category: cs.SE  
Categories: cs-DC, cs-SE, cs.SE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05833v1)  

---


**ABSTRACT**  
Microservices architecture is one of the new architectural styles that has improved in recent years. It has become a popular architectural style among system architects and developers. This popularity increased with the advent of new technologies and technological advancements in cloud computing. These advancements caused the emergence of new design and development challenges for service-based software systems. The increasing use of microservices architecture in large organizations and teams has increased the need to find appropriate solutions for architecture challenges. Orchestration of the components in the microservices architecture is one of the main challenges in distributed systems and affects the software quality in factors such as efficiency, compatibility, stability, and reusability. In such systems, software architecture consists of fine-grained components. Due to the increasing number of microservices in a large-scale system, proper management and communication orchestration of microservice components can become a point of failure. In this article, the challenges of Microservices architecture have been identified. To resolve the component orchestration challenges, an appropriate model to maintain and improve quality is proposed. The presented model, as a pattern, can be used at the both design and development level of the system. The Dynamicity of software at runtime is the main achievement of this pattern. In this model, microservice components orchestration tasks are performed by using a BPMN-based workflow engine as the orchestrator component. The orchestrator design gives the ability to create, track and modify new composite microservices without the need to change platform infrastructure.

{{</citation>}}


### (52/88) Test Case Minimization with Quantum Annealers (Xinyi Wang et al., 2023)

{{<citation>}}

Xinyi Wang, Asmar Muqeet, Tao Yue, Shaukat Ali, Paolo Arcaini. (2023)  
**Test Case Minimization with Quantum Annealers**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2308.05505v1)  

---


**ABSTRACT**  
Quantum annealers are specialized quantum computers for solving combinatorial optimization problems using special characteristics of quantum computing (QC), such as superposition, entanglement, and quantum tunneling. Theoretically, quantum annealers can outperform classical computers. However, the currently available quantum annealers are small-scale, i.e., they have limited quantum bits (qubits); hence, they currently cannot demonstrate the quantum advantage. Nonetheless, research is warranted to develop novel mechanisms to formulate combinatorial optimization problems for quantum annealing (QA). However, solving combinatorial problems with QA in software engineering remains unexplored. Toward this end, we propose BootQA, the very first effort at solving the test case minimization (TCM) problem with QA. In BootQA, we provide a novel formulation of TCM for QA, followed by devising a mechanism to incorporate bootstrap sampling to QA to optimize the use of qubits. We also implemented our TCM formulation in three other optimization processes: classical simulated annealing (SA), QA without problem decomposition, and QA with an existing D-Wave problem decomposition strategy, and conducted an empirical evaluation with three real-world TCM datasets. Results show that BootQA outperforms QA without problem decomposition and QA with the existing decomposition strategy in terms of effectiveness. Moreover, BootQA's effectiveness is similar to SA. Finally, BootQA has higher efficiency in terms of time when solving large TCM problems than the other three optimization processes.

{{</citation>}}


### (53/88) A Preliminary Evaluation of LLM-Based Fault Localization (Sungmin Kang et al., 2023)

{{<citation>}}

Sungmin Kang, Gabin An, Shin Yoo. (2023)  
**A Preliminary Evaluation of LLM-Based Fault Localization**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2308.05487v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have shown a surprising level of performance on multiple software engineering problems. However, they have not yet been applied to fault localization (FL), in which one must find the code element responsible for a bug from a potentially vast software repository. Nonetheless, LLM application to FL has the potential to benefit developers both in terms of performance and explainability. In this work, we present AutoFL, an automated fault localization technique that only requires a single failing test, and in its fault localization process generates an explanation about why the given test fails. Using the function call API of the ChatGPT large language model, we provide tools that allow it to explore a large source code repository, which would otherwise pose a significant challenge as it would be impossible to fit all the source code within the limited prompt length. Our results indicate that on the widely used Defects4J benchmark, AutoFL could identify the faulty method on the first try more often than all standalone techniques we compared against from prior work. Nonetheless, there is ample room to improve performance, and we encourage the further experimentation of language model-based fault localization as a promising research area.

{{</citation>}}


## cs.HC (1)



### (54/88) DiLogics: Creating Web Automation Programs With Diverse Logics (Kevin Pu et al., 2023)

{{<citation>}}

Kevin Pu, Jim Yang, Angel Yuan, Minyi Ma, Rui Dong, Xinyu Wang, Yan Chen, Tovi Grossman. (2023)  
**DiLogics: Creating Web Automation Programs With Diverse Logics**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-HC, cs-PL, cs.HC  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2308.05828v1)  

---


**ABSTRACT**  
Knowledge workers frequently encounter repetitive web data entry tasks, like updating records or placing orders. Web automation increases productivity, but translating tasks to web actions accurately and extending to new specifications is challenging. Existing tools can automate tasks that perform the same logical trace of UI actions (e.g., input text in each field in order), but do not support tasks requiring different executions based on varied input conditions. We present DiLogics, a programming-by-demonstration system that utilizes NLP to assist users in creating web automation programs that handle diverse specifications. DiLogics first semantically segments input data to structured task steps. By recording user demonstrations for each step, DiLogics generalizes the web macros to novel but semantically similar task requirements. Our evaluation showed that non-experts can effectively use DiLogics to create automation programs that fulfill diverse input instructions. DiLogics provides an efficient, intuitive, and expressive method for developing web automation programs satisfying diverse specifications.

{{</citation>}}


## cs.SD (1)



### (55/88) AudioLDM 2: Learning Holistic Audio Generation with Self-supervised Pretraining (Haohe Liu et al., 2023)

{{<citation>}}

Haohe Liu, Qiao Tian, Yi Yuan, Xubo Liu, Xinhao Mei, Qiuqiang Kong, Yuping Wang, Wenwu Wang, Yuxuan Wang, Mark D. Plumbley. (2023)  
**AudioLDM 2: Learning Holistic Audio Generation with Self-supervised Pretraining**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-MM, cs-SD, cs.SD, eess-AS, eess-SP  
Keywords: GPT  
[Paper Link](http://arxiv.org/abs/2308.05734v1)  

---


**ABSTRACT**  
Although audio generation shares commonalities across different types of audio, such as speech, music, and sound effects, designing models for each type requires careful consideration of specific objectives and biases that can significantly differ from those of other types. To bring us closer to a unified perspective of audio generation, this paper proposes a framework that utilizes the same learning method for speech, music, and sound effect generation. Our framework introduces a general representation of audio, called language of audio (LOA). Any audio can be translated into LOA based on AudioMAE, a self-supervised pre-trained representation learning model. In the generation process, we translate any modalities into LOA by using a GPT-2 model, and we perform self-supervised audio generation learning with a latent diffusion model conditioned on LOA. The proposed framework naturally brings advantages such as in-context learning abilities and reusable self-supervised pretrained AudioMAE and latent diffusion models. Experiments on the major benchmarks of text-to-audio, text-to-music, and text-to-speech demonstrate new state-of-the-art or competitive performance to previous approaches. Our demo and code are available at https://audioldm.github.io/audioldm2.

{{</citation>}}


## cs.AI (9)



### (56/88) Testing GPT-4 with Wolfram Alpha and Code Interpreter plug-ins on math and science problems (Ernest Davis et al., 2023)

{{<citation>}}

Ernest Davis, Scott Aaronson. (2023)  
**Testing GPT-4 with Wolfram Alpha and Code Interpreter plug-ins on math and science problems**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI, math-HO, physics-pop-ph  
Keywords: GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2308.05713v2)  

---


**ABSTRACT**  
This report describes a test of the large language model GPT-4 with the Wolfram Alpha and the Code Interpreter plug-ins on 105 original problems in science and math, at the high school and college levels, carried out in June-August 2023. Our tests suggest that the plug-ins significantly enhance GPT's ability to solve these problems. Having said that, there are still often "interface" failures; that is, GPT often has trouble formulating problems in a way that elicits useful answers from the plug-ins. Fixing these interface failures seems like a central challenge in making GPT a reliable tool for college-level calculation problems.

{{</citation>}}


### (57/88) Exploring the Potential of World Models for Anomaly Detection in Autonomous Driving (Daniel Bogdoll et al., 2023)

{{<citation>}}

Daniel Bogdoll, Lukas Bosch, Tim Joseph, Helen Gremmelmaier, Yitian Yang, J. Marius Zöllner. (2023)  
**Exploring the Potential of World Models for Anomaly Detection in Autonomous Driving**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-RO, cs.AI  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2308.05701v1)  

---


**ABSTRACT**  
In recent years there have been remarkable advancements in autonomous driving. While autonomous vehicles demonstrate high performance in closed-set conditions, they encounter difficulties when confronted with unexpected situations. At the same time, world models emerged in the field of model-based reinforcement learning as a way to enable agents to predict the future depending on potential actions. This led to outstanding results in sparse reward and complex control tasks. This work provides an overview of how world models can be leveraged to perform anomaly detection in the domain of autonomous driving. We provide a characterization of world models and relate individual components to previous works in anomaly detection to facilitate further research in the field.

{{</citation>}}


### (58/88) Proximal Policy Optimization Actual Combat: Manipulating Output Tokenizer Length (Miao Fan et al., 2023)

{{<citation>}}

Miao Fan, Chen Hu, Shuchang Zhou. (2023)  
**Proximal Policy Optimization Actual Combat: Manipulating Output Tokenizer Length**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.05585v1)  

---


**ABSTRACT**  
The Reinforcement Learning from Human Feedback (RLHF) plays a pivotal role in shaping the impact of large language models (LLMs), contributing significantly to controlling output toxicity and selecting output styles, particularly as LLMs often harbor misleading content, highlighting the urgency to align them with human values for secure AI systems. The RLHF, characterized by complexity, instability, and sensitivity to hyperparameters, makes the evaluation of the reward model for complex tasks challenging, thereby further complicating the use of Proximal Policy Optimization (PPO). In this paper, we introduce a simple task designed to employ Gloden as a reward model that validates the effectiveness of PPO and inspires it, primarily explaining the task of utilizing PPO to manipulate the tokenizer length of the output generated by the model. Experiments confirm that PPO is not only effective in manipulating the output tokenizer length to a certain extent in this type of task but also exhibits facilitated training once the influence of the reward model effect is excluded, making it an exciting development.

{{</citation>}}


### (59/88) C5: Towards Better Conversation Comprehension and Contextual Continuity for ChatGPT (Pan Liang et al., 2023)

{{<citation>}}

Pan Liang, Danwei Ye, Zihao Zhu, Yunchao Wang, Wang Xia, Ronghua Liang, Guodao Sun. (2023)  
**C5: Towards Better Conversation Comprehension and Contextual Continuity for ChatGPT**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2308.05567v1)  

---


**ABSTRACT**  
Large language models (LLMs), such as ChatGPT, have demonstrated outstanding performance in various fields, particularly in natural language understanding and generation tasks. In complex application scenarios, users tend to engage in multi-turn conversations with ChatGPT to keep contextual information and obtain comprehensive responses. However, human forgetting and model contextual forgetting remain prominent issues in multi-turn conversation scenarios, which challenge the users' conversation comprehension and contextual continuity for ChatGPT. To address these challenges, we propose an interactive conversation visualization system called C5, which includes Global View, Topic View, and Context-associated Q\&A View. The Global View uses the GitLog diagram metaphor to represent the conversation structure, presenting the trend of conversation evolution and supporting the exploration of locally salient features. The Topic View is designed to display all the question and answer nodes and their relationships within a topic using the structure of a knowledge graph, thereby display the relevance and evolution of conversations. The Context-associated Q\&A View consists of three linked views, which allow users to explore individual conversations deeply while providing specific contextual information when posing questions. The usefulness and effectiveness of C5 were evaluated through a case study and a user study.

{{</citation>}}


### (60/88) More Than Meets the Eye: Analyzing Anesthesiologists' Visual Attention in the Operating Room Using Deep Learning Models (Sapir Gershov et al., 2023)

{{<citation>}}

Sapir Gershov, Fadi Mahameed, Aeyal Raz, Shlomi Laufer. (2023)  
**More Than Meets the Eye: Analyzing Anesthesiologists' Visual Attention in the Operating Room Using Deep Learning Models**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2308.05501v1)  

---


**ABSTRACT**  
Patient's vital signs, which are displayed on monitors, make the anesthesiologist's visual attention (VA) a key component in the safe management of patients under general anesthesia; moreover, the distribution of said VA and the ability to acquire specific cues throughout the anesthetic, may have a direct impact on patient's outcome. Currently, most studies employ wearable eye-tracking technologies to analyze anesthesiologists' visual patterns. Albeit being able to produce meticulous data, wearable devices are not a sustainable solution for large-scale or long-term use for data collection in the operating room (OR). Thus, by utilizing a novel eye-tracking method in the form of deep learning models that process monitor-mounted webcams, we collected continuous behavioral data and gained insight into the anesthesiologist's VA distribution with minimal disturbance to their natural workflow. In this study, we collected OR video recordings using the proposed framework and compared different visual behavioral patterns. We distinguished between baseline VA distribution during uneventful periods to patterns associated with active phases or during critical, unanticipated incidents. In the future, such a platform may serve as a crucial component of context-aware assistive technologies in the OR.

{{</citation>}}


### (61/88) Exploring XAI for the Arts: Explaining Latent Space in Generative Music (Nick Bryan-Kinns et al., 2023)

{{<citation>}}

Nick Bryan-Kinns, Berker Banar, Corey Ford, Courtney N. Reed, Yixiao Zhang, Simon Colton, Jack Armitage. (2023)  
**Exploring XAI for the Arts: Explaining Latent Space in Generative Music**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-HC, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05496v1)  

---


**ABSTRACT**  
Explainable AI has the potential to support more interactive and fluid co-creative AI systems which can creatively collaborate with people. To do this, creative AI models need to be amenable to debugging by offering eXplainable AI (XAI) features which are inspectable, understandable, and modifiable. However, currently there is very little XAI for the arts. In this work, we demonstrate how a latent variable model for music generation can be made more explainable; specifically we extend MeasureVAE which generates measures of music. We increase the explainability of the model by: i) using latent space regularisation to force some specific dimensions of the latent space to map to meaningful musical attributes, ii) providing a user interface feedback loop to allow people to adjust dimensions of the latent space and observe the results of these changes in real-time, iii) providing a visualisation of the musical attributes in the latent space to help people understand and predict the effect of changes to latent space dimensions. We suggest that in doing so we bridge the gap between the latent space and the generated musical outcomes in a meaningful way which makes the model and its outputs more explainable and more debuggable.

{{</citation>}}


### (62/88) Explainable AI applications in the Medical Domain: a systematic review (Nicoletta Prentzas et al., 2023)

{{<citation>}}

Nicoletta Prentzas, Antonis Kakas, Constantinos S. Pattichis. (2023)  
**Explainable AI applications in the Medical Domain: a systematic review**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05411v1)  

---


**ABSTRACT**  
Artificial Intelligence in Medicine has made significant progress with emerging applications in medical imaging, patient care, and other areas. While these applications have proven successful in retrospective studies, very few of them were applied in practice.The field of Medical AI faces various challenges, in terms of building user trust, complying with regulations, using data ethically.Explainable AI (XAI) aims to enable humans understand AI and trust its results. This paper presents a literature review on the recent developments of XAI solutions for medical decision support, based on a representative sample of 198 articles published in recent years. The systematic synthesis of the relevant articles resulted in several findings. (1) model-agnostic XAI techniques were mostly employed in these solutions, (2) deep learning models are utilized more than other types of machine learning models, (3) explainability was applied to promote trust, but very few works reported the physicians participation in the loop, (4) visual and interactive user interface is more useful in understanding the explanation and the recommendation of the system. More research is needed in collaboration between medical and AI experts, that could guide the development of suitable frameworks for the design, implementation, and evaluation of XAI solutions in medicine.

{{</citation>}}


### (63/88) Enhancing Trust in LLM-Based AI Automation Agents: New Considerations and Future Challenges (Sivan Schwartz et al., 2023)

{{<citation>}}

Sivan Schwartz, Avi Yaeli, Segev Shlomov. (2023)  
**Enhancing Trust in LLM-Based AI Automation Agents: New Considerations and Future Challenges**  

---
Primary Category: cs.AI  
Categories: 68T01, cs-AI, cs.AI  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2308.05391v1)  

---


**ABSTRACT**  
Trust in AI agents has been extensively studied in the literature, resulting in significant advancements in our understanding of this field. However, the rapid advancements in Large Language Models (LLMs) and the emergence of LLM-based AI agent frameworks pose new challenges and opportunities for further research. In the field of process automation, a new generation of AI-based agents has emerged, enabling the execution of complex tasks. At the same time, the process of building automation has become more accessible to business users via user-friendly no-code tools and training mechanisms. This paper explores these new challenges and opportunities, analyzes the main aspects of trust in AI agents discussed in existing literature, and identifies specific considerations and challenges relevant to this new generation of automation agents. We also evaluate how nascent products in this category address these considerations. Finally, we highlight several challenges that the research community should address in this evolving landscape.

{{</citation>}}


### (64/88) Trustworthy LLMs: a Survey and Guideline for Evaluating Large Language Models' Alignment (Yang Liu et al., 2023)

{{<citation>}}

Yang Liu, Yuanshun Yao, Jean-Francois Ton, Xiaoying Zhang, Ruocheng Guo, Hao Cheng, Yegor Klochkov, Muhammad Faaiz Taufiq, Hang Li. (2023)  
**Trustworthy LLMs: a Survey and Guideline for Evaluating Large Language Models' Alignment**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: AI, GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2308.05374v1)  

---


**ABSTRACT**  
Ensuring alignment, which refers to making models behave in accordance with human intentions [1,2], has become a critical task before deploying large language models (LLMs) in real-world applications. For instance, OpenAI devoted six months to iteratively aligning GPT-4 before its release [3]. However, a major challenge faced by practitioners is the lack of clear guidance on evaluating whether LLM outputs align with social norms, values, and regulations. This obstacle hinders systematic iteration and deployment of LLMs. To address this issue, this paper presents a comprehensive survey of key dimensions that are crucial to consider when assessing LLM trustworthiness. The survey covers seven major categories of LLM trustworthiness: reliability, safety, fairness, resistance to misuse, explainability and reasoning, adherence to social norms, and robustness. Each major category is further divided into several sub-categories, resulting in a total of 29 sub-categories. Additionally, a subset of 8 sub-categories is selected for further investigation, where corresponding measurement studies are designed and conducted on several widely-used LLMs. The measurement results indicate that, in general, more aligned models tend to perform better in terms of overall trustworthiness. However, the effectiveness of alignment varies across the different trustworthiness categories considered. This highlights the importance of conducting more fine-grained analyses, testing, and making continuous improvements on LLM alignment. By shedding light on these key dimensions of LLM trustworthiness, this paper aims to provide valuable insights and guidance to practitioners in the field. Understanding and addressing these concerns will be crucial in achieving reliable and ethically sound deployment of LLMs in various applications.

{{</citation>}}


## cs.IR (2)



### (65/88) SSLRec: A Self-Supervised Learning Library for Recommendation (Xubin Ren et al., 2023)

{{<citation>}}

Xubin Ren, Lianghao Xia, Yuhao Yang, Wei Wei, Tianle Wang, Xuheng Cai, Chao Huang. (2023)  
**SSLRec: A Self-Supervised Learning Library for Recommendation**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs.IR  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2308.05697v1)  

---


**ABSTRACT**  
Self-supervised learning (SSL) has gained significant interest in recent years as a solution to address the challenges posed by sparse and noisy data in recommender systems. Despite the growing number of SSL algorithms designed to provide state-of-the-art performance in various recommendation scenarios (e.g., graph collaborative filtering, sequential recommendation, social recommendation, KG-enhanced recommendation), there is still a lack of unified frameworks that integrate recommendation algorithms across different domains. Such a framework could serve as the cornerstone for self-supervised recommendation algorithms, unifying the validation of existing methods and driving the design of new ones. To address this gap, we introduce SSLRec, a novel benchmark platform that provides a standardized, flexible, and comprehensive framework for evaluating various SSL-enhanced recommenders. The SSLRec library features a modular architecture that allows users to easily evaluate state-of-the-art models and a complete set of data augmentation and self-supervised toolkits to help create SSL recommendation models with specific needs. Furthermore, SSLRec simplifies the process of training and evaluating different recommendation models with consistent and fair settings. Our SSLRec platform covers a comprehensive set of state-of-the-art SSL-enhanced recommendation models across different scenarios, enabling researchers to evaluate these cutting-edge models and drive further innovation in the field. Our implemented SSLRec framework is available at the source code repository https://github.com/HKUDS/SSLRec.

{{</citation>}}


### (66/88) Multi-domain Recommendation with Embedding Disentangling and Domain Alignment (Wentao Ning et al., 2023)

{{<citation>}}

Wentao Ning, Xiao Yan, Weiwen Liu, Reynold Cheng, Rui Zhang, Bo Tang. (2023)  
**Multi-domain Recommendation with Embedding Disentangling and Domain Alignment**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs.IR  
Keywords: Amazon, Embedding  
[Paper Link](http://arxiv.org/abs/2308.05508v2)  

---


**ABSTRACT**  
Multi-domain recommendation (MDR) aims to provide recommendations for different domains (e.g., types of products) with overlapping users/items and is common for platforms such as Amazon, Facebook, and LinkedIn that host multiple services. Existing MDR models face two challenges: First, it is difficult to disentangle knowledge that generalizes across domains (e.g., a user likes cheap items) and knowledge specific to a single domain (e.g., a user likes blue clothing but not blue cars). Second, they have limited ability to transfer knowledge across domains with small overlaps. We propose a new MDR method named EDDA with two key components, i.e., embedding disentangling recommender and domain alignment, to tackle the two challenges respectively. In particular, the embedding disentangling recommender separates both the model and embedding for the inter-domain part and the intra-domain part, while most existing MDR methods only focus on model-level disentangling. The domain alignment leverages random walks from graph processing to identify similar user/item pairs from different domains and encourages similar user/item pairs to have similar embeddings, enhancing knowledge transfer. We compare EDDA with 12 state-of-the-art baselines on 3 real datasets. The results show that EDDA consistently outperforms the baselines on all datasets and domains. All datasets and codes are available at https://github.com/Stevenn9981/EDDA.

{{</citation>}}


## cs.CL (13)



### (67/88) Finding Already Debunked Narratives via Multistage Retrieval: Enabling Cross-Lingual, Cross-Dataset and Zero-Shot Learning (Iknoor Singh et al., 2023)

{{<citation>}}

Iknoor Singh, Carolina Scarton, Xingyi Song, Kalina Bontcheva. (2023)  
**Finding Already Debunked Narratives via Multistage Retrieval: Enabling Cross-Lingual, Cross-Dataset and Zero-Shot Learning**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CY, cs-IR, cs-LG, cs-SI, cs.CL  
Keywords: Transformer, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2308.05680v1)  

---


**ABSTRACT**  
The task of retrieving already debunked narratives aims to detect stories that have already been fact-checked. The successful detection of claims that have already been debunked not only reduces the manual efforts of professional fact-checkers but can also contribute to slowing the spread of misinformation. Mainly due to the lack of readily available data, this is an understudied problem, particularly when considering the cross-lingual task, i.e. the retrieval of fact-checking articles in a language different from the language of the online post being checked. This paper fills this gap by (i) creating a novel dataset to enable research on cross-lingual retrieval of already debunked narratives, using tweets as queries to a database of fact-checking articles; (ii) presenting an extensive experiment to benchmark fine-tuned and off-the-shelf multilingual pre-trained Transformer models for this task; and (iii) proposing a novel multistage framework that divides this cross-lingual debunk retrieval task into refinement and re-ranking stages. Results show that the task of cross-lingual retrieval of already debunked narratives is challenging and off-the-shelf Transformer models fail to outperform a strong lexical-based baseline (BM25). Nevertheless, our multistage retrieval framework is robust, outperforming BM25 in most scenarios and enabling cross-domain and zero-shot learning, without significantly harming the model's performance.

{{</citation>}}


### (68/88) AST-MHSA : Code Summarization using Multi-Head Self-Attention (Yeshwanth Nagaraj et al., 2023)

{{<citation>}}

Yeshwanth Nagaraj, Ujjwal Gupta. (2023)  
**AST-MHSA : Code Summarization using Multi-Head Self-Attention**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs-PL, cs-SE, cs.CL  
Keywords: Attention, Self-Attention, Summarization  
[Paper Link](http://arxiv.org/abs/2308.05646v1)  

---


**ABSTRACT**  
Code summarization aims to generate concise natural language descriptions for source code. The prevailing approaches adopt transformer-based encoder-decoder architectures, where the Abstract Syntax Tree (AST) of the source code is utilized for encoding structural information. However, ASTs are much longer than the corresponding source code, and existing methods ignore this size constraint by directly feeding the entire linearized AST into the encoders. This simplistic approach makes it challenging to extract truly valuable dependency relations from the overlong input sequence and leads to significant computational overhead due to self-attention applied to all nodes in the AST.   To address this issue effectively and efficiently, we present a model, AST-MHSA that uses multi-head attention to extract the important semantic information from the AST. The model consists of two main components: an encoder and a decoder. The encoder takes as input the abstract syntax tree (AST) of the code and generates a sequence of hidden states. The decoder then takes these hidden states as input and generates a natural language summary of the code.   The multi-head attention mechanism allows the model to learn different representations of the input code, which can be combined to generate a more comprehensive summary. The model is trained on a dataset of code and summaries, and the parameters of the model are optimized to minimize the loss between the generated summaries and the ground-truth summaries.

{{</citation>}}


### (69/88) LASIGE and UNICAGE solution to the NASA LitCoin NLP Competition (Pedro Ruas et al., 2023)

{{<citation>}}

Pedro Ruas, Diana F. Sousa, André Neves, Carlos Cruz, Francisco M. Couto. (2023)  
**LASIGE and UNICAGE solution to the NASA LitCoin NLP Competition**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-IR, cs-PF, cs.CL  
Keywords: NER, NLP, Named Entity Recognition, Natural Language Processing, Relation Extraction  
[Paper Link](http://arxiv.org/abs/2308.05609v1)  

---


**ABSTRACT**  
Biomedical Natural Language Processing (NLP) tends to become cumbersome for most researchers, frequently due to the amount and heterogeneity of text to be processed. To address this challenge, the industry is continuously developing highly efficient tools and creating more flexible engineering solutions. This work presents the integration between industry data engineering solutions for efficient data processing and academic systems developed for Named Entity Recognition (LasigeUnicage\_NER) and Relation Extraction (BiOnt). Our design reflects an integration of those components with external knowledge in the form of additional training data from other datasets and biomedical ontologies. We used this pipeline in the 2022 LitCoin NLP Challenge, where our team LasigeUnicage was awarded the 7th Prize out of approximately 200 participating teams, reflecting a successful collaboration between the academia (LASIGE) and the industry (Unicage). The software supporting this work is available at \url{https://github.com/lasigeBioTM/Litcoin-Lasige_Unicage}.

{{</citation>}}


### (70/88) You Only Prompt Once: On the Capabilities of Prompt Learning on Large Language Models to Tackle Toxic Content (Xinlei He et al., 2023)

{{<citation>}}

Xinlei He, Savvas Zannettou, Yun Shen, Yang Zhang. (2023)  
**You Only Prompt Once: On the Capabilities of Prompt Learning on Large Language Models to Tackle Toxic Content**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SI, cs.CL  
Keywords: GPT, Language Model, T5  
[Paper Link](http://arxiv.org/abs/2308.05596v1)  

---


**ABSTRACT**  
The spread of toxic content online is an important problem that has adverse effects on user experience online and in our society at large. Motivated by the importance and impact of the problem, research focuses on developing solutions to detect toxic content, usually leveraging machine learning (ML) models trained on human-annotated datasets. While these efforts are important, these models usually do not generalize well and they can not cope with new trends (e.g., the emergence of new toxic terms). Currently, we are witnessing a shift in the approach to tackling societal issues online, particularly leveraging large language models (LLMs) like GPT-3 or T5 that are trained on vast corpora and have strong generalizability. In this work, we investigate how we can use LLMs and prompt learning to tackle the problem of toxic content, particularly focusing on three tasks; 1) Toxicity Classification, 2) Toxic Span Detection, and 3) Detoxification. We perform an extensive evaluation over five model architectures and eight datasets demonstrating that LLMs with prompt learning can achieve similar or even better performance compared to models trained on these specific tasks. We find that prompt learning achieves around 10\% improvement in the toxicity classification task compared to the baselines, while for the toxic span detection task we find better performance to the best baseline (0.643 vs. 0.640 in terms of $F_1$-score). Finally, for the detoxification task, we find that prompt learning can successfully reduce the average toxicity score (from 0.775 to 0.213) while preserving semantic meaning.

{{</citation>}}


### (71/88) Do Language Models Refer? (Matthew Mandelkern et al., 2023)

{{<citation>}}

Matthew Mandelkern, Tal Linzen. (2023)  
**Do Language Models Refer?**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2308.05576v1)  

---


**ABSTRACT**  
What do language models (LMs) do with language? Everyone agrees that they produce sequences of (mostly) coherent sentences. But are they saying anything with those strings or simply babbling in a convincing simulacrum of language use? This is a vague question, and there are many ways of making it precise. Here we will address one aspect of the question, namely, whether LMs' words refer: that is, whether the outputs of LMs achieve "word-to-world" connections. There is prima facie reason to think they do not since LMs do not interact with the world in the way that ordinary language users do. Drawing on insights from the externalist tradition in philosophy of language, we argue that appearances are misleading and that there is good reason to think that LMs can refer.

{{</citation>}}


### (72/88) Exploring Linguistic Similarity and Zero-Shot Learning for Multilingual Translation of Dravidian Languages (Danish Ebadulla et al., 2023)

{{<citation>}}

Danish Ebadulla, Rahul Raman, S. Natarajan, Hridhay Kiran Shetty, Ashish Harish Shenoy. (2023)  
**Exploring Linguistic Similarity and Zero-Shot Learning for Multilingual Translation of Dravidian Languages**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CV, cs.CL  
Keywords: BLEU, Multilingual, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2308.05574v1)  

---


**ABSTRACT**  
Current research in zero-shot translation is plagued by several issues such as high compute requirements, increased training time and off target translations. Proposed remedies often come at the cost of additional data or compute requirements. Pivot based neural machine translation is preferred over a single-encoder model for most settings despite the increased training and evaluation time. In this work, we overcome the shortcomings of zero-shot translation by taking advantage of transliteration and linguistic similarity. We build a single encoder-decoder neural machine translation system for Dravidian-Dravidian multilingual translation and perform zero-shot translation. We compare the data vs zero-shot accuracy tradeoff and evaluate the performance of our vanilla method against the current state of the art pivot based method. We also test the theory that morphologically rich languages require large vocabularies by restricting the vocabulary using an optimal transport based technique. Our model manages to achieves scores within 3 BLEU of large-scale pivot-based models when it is trained on 50\% of the language directions.

{{</citation>}}


### (73/88) Bringing order into the realm of Transformer-based language models for artificial intelligence and law (Candida M. Greco et al., 2023)

{{<citation>}}

Candida M. Greco, Andrea Tagarelli. (2023)  
**Bringing order into the realm of Transformer-based language models for artificial intelligence and law**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-IR, cs-NE, cs.CL, physics-soc-ph  
Keywords: AI, BERT, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2308.05502v1)  

---


**ABSTRACT**  
Transformer-based language models (TLMs) have widely been recognized to be a cutting-edge technology for the successful development of deep-learning-based solutions to problems and applications that require natural language processing and understanding. Like for other textual domains, TLMs have indeed pushed the state-of-the-art of AI approaches for many tasks of interest in the legal domain. Despite the first Transformer model being proposed about six years ago, there has been a rapid progress of this technology at an unprecedented rate, whereby BERT and related models represent a major reference, also in the legal domain. This article provides the first systematic overview of TLM-based methods for AI-driven problems and tasks in the legal sphere. A major goal is to highlight research advances in this field so as to understand, on the one hand, how the Transformers have contributed to the success of AI in supporting legal processes, and on the other hand, what are the current limitations and opportunities for further research development.

{{</citation>}}


### (74/88) Exploring Machine Learning and Transformer-based Approaches for Deceptive Text Classification: A Comparative Analysis (Anusuya Krishnan, 2023)

{{<citation>}}

Anusuya Krishnan. (2023)  
**Exploring Machine Learning and Transformer-based Approaches for Deceptive Text Classification: A Comparative Analysis**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: BERT, Text Classification, Transformer  
[Paper Link](http://arxiv.org/abs/2308.05476v2)  

---


**ABSTRACT**  
Deceptive text classification is a critical task in natural language processing that aims to identify deceptive o fraudulent content. This study presents a comparative analysis of machine learning and transformer-based approaches for deceptive text classification. We investigate the effectiveness of traditional machine learning algorithms and state-of-the-art transformer models, such as BERT, XLNET, DistilBERT, and RoBERTa, in detecting deceptive text. A labeled dataset consisting of deceptive and non-deceptive texts is used for training and evaluation purposes. Through extensive experimentation, we compare the performance metrics, including accuracy, precision, recall, and F1 score, of the different approaches. The results of this study shed light on the strengths and limitations of machine learning and transformer-based methods for deceptive text classification, enabling researchers and practitioners to make informed decisions when dealing with deceptive content.

{{</citation>}}


### (75/88) WeaverBird: Empowering Financial Decision-Making with Large Language Model, Knowledge Base, and Search Engine (Siqiao Xue et al., 2023)

{{<citation>}}

Siqiao Xue, Fan Zhou, Yi Xu, Hongyu Zhao, Shuo Xie, Caigao Jiang, James Zhang, Jun Zhou, Peng Xu, Dacheng Xiu, Hongyuan Mei. (2023)  
**WeaverBird: Empowering Financial Decision-Making with Large Language Model, Knowledge Base, and Search Engine**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Financial, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2308.05361v1)  

---


**ABSTRACT**  
We present WeaverBird, an intelligent dialogue system designed specifically for the finance domain. Our system harnesses a large language model of GPT architecture that has been tuned using extensive corpora of finance-related text. As a result, our system possesses the capability to understand complex financial queries, such as "How should I manage my investments during inflation?", and provide informed responses. Furthermore, our system incorporates a local knowledge base and a search engine to retrieve relevant information. The final responses are conditioned on the search results and include proper citations to the sources, thus enjoying an enhanced credibility. Through a range of finance-related questions, we have demonstrated the superior performance of our system compared to other models. To experience our system firsthand, users can interact with our live demo at https://weaverbird.ttic.edu, as well as watch our 2-min video illustration at https://www.youtube.com/watch?v=yofgeqnlrMc.

{{</citation>}}


### (76/88) Metacognitive Prompting Improves Understanding in Large Language Models (Yuqing Wang et al., 2023)

{{<citation>}}

Yuqing Wang, Yun Zhao. (2023)  
**Metacognitive Prompting Improves Understanding in Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GLUE, GPT, GPT-3.5, GPT-4, Language Model, NLU, PaLM, SuperGLUE  
[Paper Link](http://arxiv.org/abs/2308.05342v1)  

---


**ABSTRACT**  
In Large Language Models (LLMs), there have been consistent advancements in task-specific performance, largely influenced by effective prompt design. While recent research on prompting has enhanced the reasoning capabilities of LLMs, a gap remains in further improving their understanding abilities. In this study, we introduce metacognitive prompting (MP), a strategy inspired by human introspective reasoning processes. Using MP, LLMs undergo a systematic series of structured, self-aware evaluations, drawing on both their vast inherent knowledge and new insights. Our experiments involve five prevalent LLMs: Llama2, Vicuna, PaLM, GPT-3.5, and GPT-4, all of which span various general natural language understanding (NLU) tasks from the GLUE and SuperGLUE benchmarks. Results indicate that, although GPT-4 consistently excels in most tasks, PaLM, when equipped with MP, approaches its performance level. Furthermore, across models and datasets, MP consistently outperforms existing prompting methods, including standard and chain-of-thought prompting. This study underscores the potential to amplify the understanding abilities of LLMs and highlights the benefits of mirroring human introspective reasoning in NLU tasks.

{{</citation>}}


### (77/88) Classification of Human- and AI-Generated Texts: Investigating Features for ChatGPT (Lorenz Mindner et al., 2023)

{{<citation>}}

Lorenz Mindner, Tim Schlippe, Kristina Schaaff. (2023)  
**Classification of Human- and AI-Generated Texts: Investigating Features for ChatGPT**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2308.05341v1)  

---


**ABSTRACT**  
Recently, generative AIs like ChatGPT have become available to the wide public. These tools can for instance be used by students to generate essays or whole theses. But how does a teacher know whether a text is written by a student or an AI? In our work, we explore traditional and new features to (1) detect text generated by AI from scratch and (2) text rephrased by AI. Since we found that classification is more difficult when the AI has been instructed to create the text in a way that a human would not recognize that it was generated by an AI, we also investigate this more advanced case. For our experiments, we produced a new text corpus covering 10 school topics. Our best systems to classify basic and advanced human-generated/AI-generated texts have F1-scores of over 96%. Our best systems for classifying basic and advanced human-generated/AI-rephrased texts have F1-scores of more than 78%. The systems use a combination of perplexity, semantic, list lookup, error-based, readability, AI feedback, and text vector features. Our results show that the new features substantially help to improve the performance of many classifiers. Our best basic text rephrasing detection system even outperforms GPTZero by 183.8% relative in F1-score.

{{</citation>}}


### (78/88) Few-Shot Data-to-Text Generation via Unified Representation and Multi-Source Learning (Alexander Hanbo Li et al., 2023)

{{<citation>}}

Alexander Hanbo Li, Mingyue Shang, Evangelia Spiliopoulou, Jie Ma, Patrick Ng, Zhiguo Wang, Bonan Min, William Wang, Kathleen McKeown, Vittorio Castelli, Dan Roth, Bing Xiang. (2023)  
**Few-Shot Data-to-Text Generation via Unified Representation and Multi-Source Learning**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BLEU, Few-Shot, Text Generation  
[Paper Link](http://arxiv.org/abs/2308.05317v1)  

---


**ABSTRACT**  
We present a novel approach for structured data-to-text generation that addresses the limitations of existing methods that primarily focus on specific types of structured data. Our proposed method aims to improve performance in multi-task training, zero-shot and few-shot scenarios by providing a unified representation that can handle various forms of structured data such as tables, knowledge graph triples, and meaning representations. We demonstrate that our proposed approach can effectively adapt to new structured forms, and can improve performance in comparison to current methods. For example, our method resulted in a 66% improvement in zero-shot BLEU scores when transferring models trained on table inputs to a knowledge graph dataset. Our proposed method is an important step towards a more general data-to-text generation framework.

{{</citation>}}


### (79/88) A Novel Self-training Approach for Low-resource Speech Recognition (Satwinder Singh et al., 2023)

{{<citation>}}

Satwinder Singh, Feng Hou, Ruili Wang. (2023)  
**A Novel Self-training Approach for Low-resource Speech Recognition**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2308.05269v1)  

---


**ABSTRACT**  
In this paper, we propose a self-training approach for automatic speech recognition (ASR) for low-resource settings. While self-training approaches have been extensively developed and evaluated for high-resource languages such as English, their applications to low-resource languages like Punjabi have been limited, despite the language being spoken by millions globally. The scarcity of annotated data has hindered the development of accurate ASR systems, especially for low-resource languages (e.g., Punjabi and M\=aori languages). To address this issue, we propose an effective self-training approach that generates highly accurate pseudo-labels for unlabeled low-resource speech. Our experimental analysis demonstrates that our approach significantly improves word error rate, achieving a relative improvement of 14.94% compared to a baseline model across four real speech datasets. Further, our proposed approach reports the best results on the Common Voice Punjabi dataset.

{{</citation>}}


## cs.NE (1)



### (80/88) A Comparative Visual Analytics Framework for Evaluating Evolutionary Processes in Multi-objective Optimization (Yansong Huang et al., 2023)

{{<citation>}}

Yansong Huang, Zherui Zhang, Ao Jiao, Yuxin Ma, Ran Cheng. (2023)  
**A Comparative Visual Analytics Framework for Evaluating Evolutionary Processes in Multi-objective Optimization**  

---
Primary Category: cs.NE  
Categories: cs-NE, cs.NE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05640v1)  

---


**ABSTRACT**  
Evolutionary multi-objective optimization (EMO) algorithms have been demonstrated to be effective in solving multi-criteria decision-making problems. In real-world applications, analysts often employ several algorithms concurrently and compare their solution sets to gain insight into the characteristics of different algorithms and explore a broader range of feasible solutions. However, EMO algorithms are typically treated as black boxes, leading to difficulties in performing detailed analysis and comparisons between the internal evolutionary processes. Inspired by the successful application of visual analytics tools in explainable AI, we argue that interactive visualization can significantly enhance the comparative analysis between multiple EMO algorithms. In this paper, we present a visual analytics framework that enables the exploration and comparison of evolutionary processes in EMO algorithms. Guided by a literature review and expert interviews, the proposed framework addresses various analytical tasks and establishes a multi-faceted visualization design to support the comparative analysis of intermediate generations in the evolution as well as solution sets. We demonstrate the effectiveness of our framework through case studies on benchmarking and real-world multi-objective optimization problems to elucidate how analysts can leverage our framework to inspect and compare diverse algorithms.

{{</citation>}}


## stat.ML (1)



### (81/88) Updating Clinical Risk Stratification Models Using Rank-Based Compatibility: Approaches for Evaluating and Optimizing Clinician-Model Team Performance (Erkin Ötleş et al., 2023)

{{<citation>}}

Erkin Ötleş, Brian T. Denton, Jenna Wiens. (2023)  
**Updating Clinical Risk Stratification Models Using Rank-Based Compatibility: Approaches for Evaluating and Optimizing Clinician-Model Team Performance**  

---
Primary Category: stat.ML  
Categories: cs-AI, cs-LG, stat-ML, stat.ML  
Keywords: Clinical  
[Paper Link](http://arxiv.org/abs/2308.05619v1)  

---


**ABSTRACT**  
As data shift or new data become available, updating clinical machine learning models may be necessary to maintain or improve performance over time. However, updating a model can introduce compatibility issues when the behavior of the updated model does not align with user expectations, resulting in poor user-model team performance. Existing compatibility measures depend on model decision thresholds, limiting their applicability in settings where models are used to generate rankings based on estimated risk. To address this limitation, we propose a novel rank-based compatibility measure, $C^R$, and a new loss function that aims to optimize discriminative performance while encouraging good compatibility. Applied to a case study in mortality risk stratification leveraging data from MIMIC, our approach yields more compatible models while maintaining discriminative performance compared to existing model selection techniques, with an increase in $C^R$ of $0.019$ ($95\%$ confidence interval: $0.005$, $0.035$). This work provides new tools to analyze and update risk stratification models used in clinical care.

{{</citation>}}


## cs.DB (1)



### (82/88) LLM As DBA (Xuanhe Zhou et al., 2023)

{{<citation>}}

Xuanhe Zhou, Guoliang Li, Zhiyuan Liu. (2023)  
**LLM As DBA**  

---
Primary Category: cs.DB  
Categories: cs-AI, cs-CL, cs-DB, cs-LG, cs.DB  
Keywords: GPT  
[Paper Link](http://arxiv.org/abs/2308.05481v2)  

---


**ABSTRACT**  
Database administrators (DBAs) play a crucial role in managing, maintaining and optimizing a database system to ensure data availability, performance, and reliability. However, it is hard and tedious for DBAs to manage a large number of database instances (e.g., millions of instances on the cloud databases). Recently large language models (LLMs) have shown great potential to understand valuable documents and accordingly generate reasonable answers. Thus, we propose D-Bot, a LLM-based database administrator that can continuously acquire database maintenance experience from textual sources, and provide reasonable, well-founded, in-time diagnosis and optimization advice for target databases. This paper presents a revolutionary LLM-centric framework for database maintenance, including (i) database maintenance knowledge detection from documents and tools, (ii) tree of thought reasoning for root cause analysis, and (iii) collaborative diagnosis among multiple LLMs. Our preliminary experimental results that D-Bot can efficiently and effectively diagnose the root causes and our code is available at github.com/TsinghuaDatabaseGroup/DB-GPT.

{{</citation>}}


## stat.ME (1)



### (83/88) A Forecaster's Review of Judea Pearl's Causality: Models, Reasoning and Inference, Second Edition, 2009 (Feng Li, 2023)

{{<citation>}}

Feng Li. (2023)  
**A Forecaster's Review of Judea Pearl's Causality: Models, Reasoning and Inference, Second Edition, 2009**  

---
Primary Category: stat.ME  
Categories: cs-LG, stat-AP, stat-ME, stat.ME  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2308.05451v1)  

---


**ABSTRACT**  
With the big popularity and success of Judea Pearl's original causality book, this review covers the main topics updated in the second edition in 2009 and illustrates an easy-to-follow causal inference strategy in a forecast scenario. It further discusses some potential benefits and challenges for causal inference with time series forecasting when modeling the counterfactuals, estimating the uncertainty and incorporating prior knowledge to estimate causal effects in different forecasting scenarios.

{{</citation>}}


## cs.RO (1)



### (84/88) Occupancy Grid Map to Pose Graph-based Map: Robust BIM-based 2D-LiDAR Localization for Lifelong Indoor Navigation in Changing and Dynamic Environments (Miguel Arturo Vega Torres et al., 2023)

{{<citation>}}

Miguel Arturo Vega Torres, Alexander Braun, André Borrmann. (2023)  
**Occupancy Grid Map to Pose Graph-based Map: Robust BIM-based 2D-LiDAR Localization for Lifelong Indoor Navigation in Changing and Dynamic Environments**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2308.05443v1)  

---


**ABSTRACT**  
Several studies rely on the de facto standard Adaptive Monte Carlo Localization (AMCL) method to localize a robot in an Occupancy Grid Map (OGM) extracted from a building information model (BIM model). However, most of these studies assume that the BIM model precisely represents the real world, which is rarely true. Discrepancies between the reference BIM model and the real world (Scan-BIM deviations) are not only due to furniture or clutter but also the usual as-planned and as-built deviations that exist with any model created in the design phase. These deviations affect the accuracy of AMCL drastically. This paper proposes an open-source method to generate appropriate Pose Graph-based maps from BIM models for robust 2D-LiDAR localization in changing and dynamic environments. First, 2D OGMs are automatically generated from complex BIM models. These OGMs only represent structural elements allowing indoor autonomous robot navigation. Then, an efficient technique converts these 2D OGMs into Pose Graph-based maps enabling more accurate robot pose tracking. Finally, we leverage the different map representations for accurate, robust localization with a combination of state-of-the-art algorithms. Moreover, we provide a quantitative comparison of various state-of-the-art localization algorithms in three simulated scenarios with varying levels of Scan-BIM deviations and dynamic agents. More precisely, we compare two Particle Filter (PF) algorithms: AMCL and General Monte Carlo Localization (GMCL); and two Graph-based Localization (GBL) methods: Google's Cartographer and SLAM Toolbox, solving the global localization and pose tracking problems. The numerous experiments demonstrate that the proposed method contributes to a robust localization with an as-designed BIM model or a sparse OGM in changing and dynamic environments, outperforming the conventional AMCL in accuracy and robustness.

{{</citation>}}


## cs.CR (2)



### (85/88) Your DRM Can Watch You Too: Exploring the Privacy Implications of Browsers (mis)Implementations of Widevine EME (Gwendal Patat et al., 2023)

{{<citation>}}

Gwendal Patat, Mohamed Sabt, Pierre-Alain Fouque. (2023)  
**Your DRM Can Watch You Too: Exploring the Privacy Implications of Browsers (mis)Implementations of Widevine EME**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2308.05416v1)  

---


**ABSTRACT**  
Thanks to HTML5, users can now view videos on Web browsers without installing plug-ins or relying on specific devices. In 2017, W3C published Encrypted Media Extensions (EME) as the first official Web standard for Digital Rights Management (DRM), with the overarching goal of allowing seamless integration of DRM systems on browsers. EME has prompted numerous voices of dissent with respect to the inadequate protection of users. Of particular interest, privacy concerns were articulated, especially that DRM systems inherently require uniquely identifying information on users' devices to control content distribution better. Despite this anecdotal evidence, we lack a comprehensive overview of how browsers have supported EME in practice and what privacy implications are caused by their implementations. In this paper, we fill this gap by investigating privacy leakage caused by EME relying on proprietary and closed-source DRM systems. We focus on Google Widevine because of its versatility and wide adoption. We conduct empirical experiments to show that browsers diverge when complying EME privacy guidelines, which might undermine users' privacy. For instance, we find that many browsers gladly give away the identifying Widevine Client ID with no or little explicit consent from users. Moreover, we characterize the privacy risks of users tracking when browsers miss applying EME guidelines regarding privacy. Because of being closed-source, our work involves reverse engineering to dissect the contents of EME messages as instantiated by Widevine. Finally, we implement EME Track, a tool that automatically exploits bad Widevine-based implementations to break privacy.

{{</citation>}}


### (86/88) FINER: Enhancing State-of-the-art Classifiers with Feature Attribution to Facilitate Security Analysis (Yiling He et al., 2023)

{{<citation>}}

Yiling He, Jian Lou, Zhan Qin, Kui Ren. (2023)  
**FINER: Enhancing State-of-the-art Classifiers with Feature Attribution to Facilitate Security Analysis**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-LG, cs-SE, cs.CR  
Keywords: NER, Security  
[Paper Link](http://arxiv.org/abs/2308.05362v1)  

---


**ABSTRACT**  
Deep learning classifiers achieve state-of-the-art performance in various risk detection applications. They explore rich semantic representations and are supposed to automatically discover risk behaviors. However, due to the lack of transparency, the behavioral semantics cannot be conveyed to downstream security experts to reduce their heavy workload in security analysis. Although feature attribution (FA) methods can be used to explain deep learning, the underlying classifier is still blind to what behavior is suspicious, and the generated explanation cannot adapt to downstream tasks, incurring poor explanation fidelity and intelligibility. In this paper, we propose FINER, the first framework for risk detection classifiers to generate high-fidelity and high-intelligibility explanations. The high-level idea is to gather explanation efforts from model developer, FA designer, and security experts. To improve fidelity, we fine-tune the classifier with an explanation-guided multi-task learning strategy. To improve intelligibility, we engage task knowledge to adjust and ensemble FA methods. Extensive evaluations show that FINER improves explanation quality for risk detection. Moreover, we demonstrate that FINER outperforms a state-of-the-art tool in facilitating malware analysis.

{{</citation>}}


## cs.NI (2)



### (87/88) Beyond Deep Reinforcement Learning: A Tutorial on Generative Diffusion Models in Network Optimization (Hongyang Du et al., 2023)

{{<citation>}}

Hongyang Du, Ruichen Zhang, Yinqiu Liu, Jiacheng Wang, Yijing Lin, Zonghang Li, Dusit Niyato, Jiawen Kang, Zehui Xiong, Shuguang Cui, Bo Ai, Haibo Zhou, Dong In Kim. (2023)  
**Beyond Deep Reinforcement Learning: A Tutorial on Generative Diffusion Models in Network Optimization**  

---
Primary Category: cs.NI  
Categories: cs-NI, cs.NI, eess-SP  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2308.05384v1)  

---


**ABSTRACT**  
Generative Diffusion Models (GDMs) have emerged as a transformative force in the realm of Generative Artificial Intelligence (GAI), demonstrating their versatility and efficacy across a variety of applications. The ability to model complex data distributions and generate high-quality samples has made GDMs particularly effective in tasks such as image generation and reinforcement learning. Furthermore, their iterative nature, which involves a series of noise addition and denoising steps, is a powerful and unique approach to learning and generating data. This paper serves as a comprehensive tutorial on applying GDMs in network optimization tasks. We delve into the strengths of GDMs, emphasizing their wide applicability across various domains, such as vision, text, and audio generation.We detail how GDMs can be effectively harnessed to solve complex optimization problems inherent in networks. The paper first provides a basic background of GDMs and their applications in network optimization. This is followed by a series of case studies, showcasing the integration of GDMs with Deep Reinforcement Learning (DRL), incentive mechanism design, Semantic Communications (SemCom), Internet of Vehicles (IoV) networks, etc. These case studies underscore the practicality and efficacy of GDMs in real-world scenarios, offering insights into network design. We conclude with a discussion on potential future directions for GDM research and applications, providing major insights into how they can continue to shape the future of network optimization.

{{</citation>}}


### (88/88) An Overview of the 3GPP Study on Artificial Intelligence for 5G New Radio (Xingqin Lin, 2023)

{{<citation>}}

Xingqin Lin. (2023)  
**An Overview of the 3GPP Study on Artificial Intelligence for 5G New Radio**  

---
Primary Category: cs.NI  
Categories: cs-NI, cs.NI, eess-SP  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2308.05315v1)  

---


**ABSTRACT**  
Air interface is a fundamental component within any wireless communication system. In Release 18, the 3rd Generation Partnership Project (3GPP) delves into the possibilities of leveraging artificial intelligence (AI)/machine learning (ML) to improve the performance of the fifth-generation (5G) New Radio (NR) air interface. This endeavor marks a pioneering stride within 3GPP's journey in shaping wireless communication standards. This article offers a comprehensive overview of the pivotal themes explored by 3GPP in this domain. Encompassing a general framework for AI/ML and specific use cases such as channel state information feedback, beam management, and positioning, it provides a holistic perspective. Moreover, we highlight the potential trajectory of AI/ML for the NR air interface in 3GPP Release 19, a pathway that paves the journey towards the sixth generation (6G) wireless communication systems that will feature integrated AI and communication as a key usage scenario.

{{</citation>}}
