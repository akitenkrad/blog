---
draft: false
title: "arXiv @ 2024.02.04"
date: 2024-02-04
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2024"]
menu:
  sidebar:
    name: "arXiv @ 2024.02.04"
    identifier: arxiv_20240204
    parent: 202402_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.CL (46)](#cscl-46)
- [cs.CR (4)](#cscr-4)
- [cs.IR (4)](#csir-4)
- [cs.LG (49)](#cslg-49)
- [cs.GT (1)](#csgt-1)
- [cs.HC (2)](#cshc-2)
- [cs.SE (8)](#csse-8)
- [cs.RO (6)](#csro-6)
- [cs.SI (2)](#cssi-2)
- [cs.AI (6)](#csai-6)
- [cs.CY (5)](#cscy-5)
- [cs.SD (6)](#cssd-6)
- [q-bio.BM (1)](#q-biobm-1)
- [eess.AS (4)](#eessas-4)
- [cs.CV (18)](#cscv-18)
- [physics.chem-ph (1)](#physicschem-ph-1)
- [cs.FL (1)](#csfl-1)
- [cs.IT (1)](#csit-1)
- [eess.SY (3)](#eesssy-3)
- [cs.NE (2)](#csne-2)
- [q-bio.GN (1)](#q-biogn-1)
- [stat.ML (2)](#statml-2)
- [eess.SP (1)](#eesssp-1)
- [quant-ph (1)](#quant-ph-1)

## cs.CL (46)



### (1/175) A Case Study on Filtering for End-to-End Speech Translation (Md Mahfuz Ibn Alam et al., 2024)

{{<citation>}}

Md Mahfuz Ibn Alam, Antonios Anastasopoulos. (2024)  
**A Case Study on Filtering for End-to-End Speech Translation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BLEU  
[Paper Link](http://arxiv.org/abs/2402.01945v1)  

---


**ABSTRACT**  
It is relatively easy to mine a large parallel corpus for any machine learning task, such as speech-to-text or speech-to-speech translation. Although these mined corpora are large in volume, their quality is questionable. This work shows that the simplest filtering technique can trim down these big, noisy datasets to a more manageable, clean dataset. We also show that using this clean dataset can improve the model's performance, as in the case of the multilingual-to-English Speech Translation (ST) model, where, on average, we obtain a 4.65 BLEU score improvement.

{{</citation>}}


### (2/175) A Morphologically-Aware Dictionary-based Data Augmentation Technique for Machine Translation of Under-Represented Languages (Md Mahfuz Ibn Alam et al., 2024)

{{<citation>}}

Md Mahfuz Ibn Alam, Sina Ahmadi, Antonios Anastasopoulos. (2024)  
**A Morphologically-Aware Dictionary-based Data Augmentation Technique for Machine Translation of Under-Represented Languages**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Augmentation, Machine Translation  
[Paper Link](http://arxiv.org/abs/2402.01939v1)  

---


**ABSTRACT**  
The availability of parallel texts is crucial to the performance of machine translation models. However, most of the world's languages face the predominant challenge of data scarcity. In this paper, we propose strategies to synthesize parallel data relying on morpho-syntactic information and using bilingual lexicons along with a small amount of seed parallel data. Our methodology adheres to a realistic scenario backed by the small parallel seed data. It is linguistically informed, as it aims to create augmented data that is more likely to be grammatically correct. We analyze how our synthetic data can be combined with raw parallel data and demonstrate a consistent improvement in performance in our experiments on 14 languages (28 English <-> X pairs) ranging from well- to very low-resource ones. Our method leads to improvements even when using only five seed sentences and a bilingual lexicon.

{{</citation>}}


### (3/175) Code Representation Learning At Scale (Dejiao Zhang et al., 2024)

{{<citation>}}

Dejiao Zhang, Wasi Ahmad, Ming Tan, Hantian Ding, Ramesh Nallapati, Dan Roth, Xiaofei Ma, Bing Xiang. (2024)  
**Code Representation Learning At Scale**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2402.01935v1)  

---


**ABSTRACT**  
Recent studies have shown that code language models at scale demonstrate significant performance gains on downstream tasks, i.e., code generation. However, most of the existing works on code representation learning train models at a hundred million parameter scale using very limited pretraining corpora. In this work, we fuel code representation learning with a vast amount of code data via a two-stage pretraining scheme. We first train the encoders via a mix that leverages both randomness in masking language modeling and the structure aspect of programming language. We then enhance the representations via contrastive learning with hard negative and hard positive constructed in an unsupervised manner. We establish an off-the-shelf encoder model that persistently outperforms the existing models on a wide variety of downstream tasks by large margins. To comprehend the factors contributing to successful code representation learning, we conduct detailed ablations and share our findings on (i) a customized and effective token-level denoising scheme for source code; (ii) the importance of hard negatives and hard positives; (iii) how the proposed bimodal contrastive learning boost the cross-lingual semantic search performance; and (iv) how the pretraining schemes decide the downstream task performance scales with the model size.

{{</citation>}}


### (4/175) Whispering in Norwegian: Navigating Orthographic and Dialectic Challenges (Per E Kummervold et al., 2024)

{{<citation>}}

Per E Kummervold, Javier de la Rosa, Freddy Wetjen, Rolv-Arild Braaten, Per Erik Solberg. (2024)  
**Whispering in Norwegian: Navigating Orthographic and Dialectic Challenges**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, Speech Recognition  
[Paper Link](http://arxiv.org/abs/2402.01917v1)  

---


**ABSTRACT**  
This article introduces NB-Whisper, an adaptation of OpenAI's Whisper, specifically fine-tuned for Norwegian language Automatic Speech Recognition (ASR). We highlight its key contributions and summarise the results achieved in converting spoken Norwegian into written forms and translating other languages into Norwegian. We show that we are able to improve the Norwegian Bokm{\aa}l transcription by OpenAI Whisper Large-v3 from a WER of 10.4 to 6.6 on the Fleurs Dataset and from 6.8 to 2.2 on the NST dataset.

{{</citation>}}


### (5/175) LiPO: Listwise Preference Optimization through Learning-to-Rank (Tianqi Liu et al., 2024)

{{<citation>}}

Tianqi Liu, Zhen Qin, Junru Wu, Jiaming Shen, Misha Khalman, Rishabh Joshi, Yao Zhao, Mohammad Saleh, Simon Baumgartner, Jialu Liu, Peter J. Liu, Xuanhui Wang. (2024)  
**LiPO: Listwise Preference Optimization through Learning-to-Rank**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01878v1)  

---


**ABSTRACT**  
Aligning language models (LMs) with curated human feedback is critical to control their behaviors in real-world applications. Several recent policy optimization methods, such as DPO and SLiC, serve as promising alternatives to the traditional Reinforcement Learning from Human Feedback (RLHF) approach. In practice, human feedback often comes in a format of a ranked list over multiple responses to amortize the cost of reading prompt. Multiple responses can also be ranked by reward models or AI feedback. There lacks such a study on directly fitting upon a list of responses. In this work, we formulate the LM alignment as a listwise ranking problem and describe the Listwise Preference Optimization (LiPO) framework, where the policy can potentially learn more effectively from a ranked list of plausible responses given the prompt. This view draws an explicit connection to Learning-to-Rank (LTR), where most existing preference optimization work can be mapped to existing ranking objectives, especially pairwise ones. Following this connection, we provide an examination of ranking objectives that are not well studied for LM alignment withDPO and SLiC as special cases when list size is two. In particular, we highlight a specific method, LiPO-{\lambda}, which leverages a state-of-the-art listwise ranking objective and weights each preference pair in a more advanced manner. We show that LiPO-{\lambda} can outperform DPO and SLiC by a clear margin on two preference alignment tasks.

{{</citation>}}


### (6/175) The RL/LLM Taxonomy Tree: Reviewing Synergies Between Reinforcement Learning and Large Language Models (Moschoula Pternea et al., 2024)

{{<citation>}}

Moschoula Pternea, Prerna Singh, Abir Chakraborty, Yagna Oruganti, Mirco Milletari, Sayli Bapat, Kebei Jiang. (2024)  
**The RL/LLM Taxonomy Tree: Reviewing Synergies Between Reinforcement Learning and Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs-RO, cs.CL  
Keywords: Language Model, Natural Language Processing, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01874v1)  

---


**ABSTRACT**  
In this work, we review research studies that combine Reinforcement Learning (RL) and Large Language Models (LLMs), two areas that owe their momentum to the development of deep neural networks. We propose a novel taxonomy of three main classes based on the way that the two model types interact with each other. The first class, RL4LLM, includes studies where RL is leveraged to improve the performance of LLMs on tasks related to Natural Language Processing. L4LLM is divided into two sub-categories depending on whether RL is used to directly fine-tune an existing LLM or to improve the prompt of the LLM. In the second class, LLM4RL, an LLM assists the training of an RL model that performs a task that is not inherently related to natural language. We further break down LLM4RL based on the component of the RL training framework that the LLM assists or replaces, namely reward shaping, goal generation, and policy function. Finally, in the third class, RL+LLM, an LLM and an RL agent are embedded in a common planning framework without either of them contributing to training or fine-tuning of the other. We further branch this class to distinguish between studies with and without natural language feedback. We use this taxonomy to explore the motivations behind the synergy of LLMs and RL and explain the reasons for its success, while pinpointing potential shortcomings and areas where further research is needed, as well as alternative methodologies that serve the same goal.

{{</citation>}}


### (7/175) TravelPlanner: A Benchmark for Real-World Planning with Language Agents (Jian Xie et al., 2024)

{{<citation>}}

Jian Xie, Kai Zhang, Jiangjie Chen, Tinghui Zhu, Renze Lou, Yuandong Tian, Yanghua Xiao, Yu Su. (2024)  
**TravelPlanner: A Benchmark for Real-World Planning with Language Agents**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2402.01622v2)  

---


**ABSTRACT**  
Planning has been part of the core pursuit for artificial intelligence since its conception, but earlier AI agents mostly focused on constrained settings because many of the cognitive substrates necessary for human-level planning have been lacking. Recently, language agents powered by large language models (LLMs) have shown interesting capabilities such as tool use and reasoning. Are these language agents capable of planning in more complex settings that are out of the reach of prior AI agents? To advance this investigation, we propose TravelPlanner, a new planning benchmark that focuses on travel planning, a common real-world planning scenario. It provides a rich sandbox environment, various tools for accessing nearly four million data records, and 1,225 meticulously curated planning intents and reference plans. Comprehensive evaluations show that the current language agents are not yet capable of handling such complex planning tasks-even GPT-4 only achieves a success rate of 0.6%. Language agents struggle to stay on task, use the right tools to collect information, or keep track of multiple constraints. However, we note that the mere possibility for language agents to tackle such a complex problem is in itself non-trivial progress. TravelPlanner provides a challenging yet meaningful testbed for future language agents.

{{</citation>}}


### (8/175) MAGDi: Structured Distillation of Multi-Agent Interaction Graphs Improves Reasoning in Smaller Language Models (Justin Chih-Yao Chen et al., 2024)

{{<citation>}}

Justin Chih-Yao Chen, Swarnadeep Saha, Elias Stengel-Eskin, Mohit Bansal. (2024)  
**MAGDi: Structured Distillation of Multi-Agent Interaction Graphs Improves Reasoning in Smaller Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, Reasoning  
[Paper Link](http://arxiv.org/abs/2402.01620v1)  

---


**ABSTRACT**  
Multi-agent interactions between Large Language Model (LLM) agents have shown major improvements on diverse reasoning tasks. However, these involve long generations from multiple models across several rounds, making them expensive. Moreover, these multi-agent approaches fail to provide a final, single model for efficient inference. To address this, we introduce MAGDi, a new method for structured distillation of the reasoning interactions between multiple LLMs into smaller LMs. MAGDi teaches smaller models by representing multi-agent interactions as graphs, augmenting a base student model with a graph encoder, and distilling knowledge using three objective functions: next-token prediction, a contrastive loss between correct and incorrect reasoning, and a graph-based objective to model the interaction structure. Experiments on seven widely-used commonsense and math reasoning benchmarks show that MAGDi improves the reasoning capabilities of smaller models, outperforming several methods that distill from a single teacher and multiple teachers. Moreover, MAGDi also demonstrates an order of magnitude higher efficiency over its teachers. We conduct extensive analyses to show that MAGDi (1) enhances the generalizability to out-of-domain tasks, (2) scales positively with the size and strength of the base student model, and (3) obtains larger improvements (via our multi-teacher training) when applying self-consistency - an inference technique that relies on model diversity.

{{</citation>}}


### (9/175) KB-Plugin: A Plug-and-play Framework for Large Language Models to Induce Programs over Low-resourced Knowledge Bases (Jiajie Zhang et al., 2024)

{{<citation>}}

Jiajie Zhang, Shulin Cao, Linmei Hu, Ling Feng, Lei Hou, Juanzi Li. (2024)  
**KB-Plugin: A Plug-and-play Framework for Large Language Models to Induce Programs over Low-resourced Knowledge Bases**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, QA  
[Paper Link](http://arxiv.org/abs/2402.01619v1)  

---


**ABSTRACT**  
Program induction (PI) has become a promising paradigm for using knowledge bases (KBs) to help large language models (LLMs) answer complex knowledge-intensive questions. Nonetheless, PI typically relies on a large number of parallel question-program pairs to make the LLM aware of the schema of the given KB, and is thus challenging for many low-resourced KBs that lack annotated data. To this end, we propose KB-Plugin, a plug-and-play framework that enables LLMs to induce programs over any low-resourced KB. Firstly, KB-Plugin adopts self-supervised learning to encode the detailed schema information of a given KB into a pluggable module, namely schema plugin. Secondly, KB-Plugin utilizes abundant annotated data from a rich-resourced KB to train another pluggable module, namely PI plugin, which can help the LLM extract question-relevant schema information from the schema plugin of any KB and utilize this information to induce programs over this KB. Experiments on five heterogeneous KBQA datasets show that KB-Plugin achieves better or comparable performance with 25$\times$ smaller backbone LLM compared to SoTA PI methods for low-resourced KBs, and even approaches the performance of supervised methods. Our code and data are available at https://github.com/THU-KEG/KB-Plugin.

{{</citation>}}


### (10/175) Style Vectors for Steering Generative Large Language Model (Kai Konen et al., 2024)

{{<citation>}}

Kai Konen, Sophie Jentzsch, Diaoulé Diallo, Peer Schütt, Oliver Bensch, Roxanne El Baff, Dominik Opitz, Tobias Hecking. (2024)  
**Style Vectors for Steering Generative Large Language Model**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01618v1)  

---


**ABSTRACT**  
This research explores strategies for steering the output of large language models (LLMs) towards specific styles, such as sentiment, emotion, or writing style, by adding style vectors to the activations of hidden layers during text generation. We show that style vectors can be simply computed from recorded layer activations for input texts in a specific style in contrast to more complex training-based approaches. Through a series of experiments, we demonstrate the effectiveness of activation engineering using such style vectors to influence the style of generated text in a nuanced and parameterisable way, distinguishing it from prompt engineering. The presented research constitutes a significant step towards developing more adaptive and effective AI-empowered interactive systems.

{{</citation>}}


### (11/175) Nomic Embed: Training a Reproducible Long Context Text Embedder (Zach Nussbaum et al., 2024)

{{<citation>}}

Zach Nussbaum, John X. Morris, Brandon Duderstadt, Andriy Mulyar. (2024)  
**Nomic Embed: Training a Reproducible Long Context Text Embedder**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01613v1)  

---


**ABSTRACT**  
This technical report describes the training of nomic-embed-text-v1, the first fully reproducible, open-source, open-weights, open-data, 8192 context length English text embedding model that outperforms both OpenAI Ada-002 and OpenAI text-embedding-3-small on short and long-context tasks. We release the training code and model weights under an Apache 2 license. In contrast with other open-source models, we release a training data loader with 235 million curated text pairs that allows for the full replication of nomic-embed-text-v1. You can find code and data to replicate the model at https://github.com/nomic-ai/contrastors

{{</citation>}}


### (12/175) Retrieval Augmented End-to-End Spoken Dialog Models (Mingqiu Wang et al., 2024)

{{<citation>}}

Mingqiu Wang, Izhak Shafran, Hagen Soltau, Wei Han, Yuan Cao, Dian Yu, Laurent El Shafey. (2024)  
**Retrieval Augmented End-to-End Spoken Dialog Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: Dialog  
[Paper Link](http://arxiv.org/abs/2402.01828v1)  

---


**ABSTRACT**  
We recently developed SLM, a joint speech and language model, which fuses a pretrained foundational speech model and a large language model (LLM), while preserving the in-context learning capability intrinsic to the pretrained LLM. In this paper, we apply SLM to speech dialog applications where the dialog states are inferred directly from the audio signal.   Task-oriented dialogs often contain domain-specific entities, i.e., restaurants, hotels, train stations, and city names, which are difficult to recognize, however, critical for the downstream applications. Inspired by the RAG (retrieval-augmented generation) paradigm, we propose a retrieval augmented SLM (ReSLM) that overcomes this weakness. We first train a speech retriever to retrieve text entities mentioned in the audio. The retrieved entities are then added as text inputs to the underlying SLM to bias model predictions. We evaluated ReSLM on speech MultiWoz task (DSTC-11 challenge), and found that this retrieval augmentation boosts model performance, achieving joint goal accuracy (38.6% vs 32.7%), slot error rate (20.6% vs 24.8%) and ASR word error rate (5.5% vs 6.7%). While demonstrated on dialog state tracking, our approach is broadly applicable to other speech tasks requiring contextual information or domain-specific entities, such as contextual ASR with biasing capability.

{{</citation>}}


### (13/175) Leveraging Large Language Models for Analyzing Blood Pressure Variations Across Biological Sex from Scientific Literature (Yuting Guo et al., 2024)

{{<citation>}}

Yuting Guo, Seyedeh Somayyeh Mousavi, Reza Sameni, Abeed Sarker. (2024)  
**Leveraging Large Language Models for Analyzing Blood Pressure Variations Across Biological Sex from Scientific Literature**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01826v1)  

---


**ABSTRACT**  
Hypertension, defined as blood pressure (BP) that is above normal, holds paramount significance in the realm of public health, as it serves as a critical precursor to various cardiovascular diseases (CVDs) and significantly contributes to elevated mortality rates worldwide. However, many existing BP measurement technologies and standards might be biased because they do not consider clinical outcomes, comorbidities, or demographic factors, making them inconclusive for diagnostic purposes. There is limited data-driven research focused on studying the variance in BP measurements across these variables. In this work, we employed GPT-35-turbo, a large language model (LLM), to automatically extract the mean and standard deviation values of BP for both males and females from a dataset comprising 25 million abstracts sourced from PubMed. 993 article abstracts met our predefined inclusion criteria (i.e., presence of references to blood pressure, units of blood pressure such as mmHg, and mention of biological sex). Based on the automatically-extracted information from these articles, we conducted an analysis of the variations of BP values across biological sex. Our results showed the viability of utilizing LLMs to study the BP variations across different demographic factors.

{{</citation>}}


### (14/175) Building Guardrails for Large Language Models (Yi Dong et al., 2024)

{{<citation>}}

Yi Dong, Ronghui Mu, Gaojie Jin, Yi Qi, Jinwei Hu, Xingyu Zhao, Jie Meng, Wenjie Ruan, Xiaowei Huang. (2024)  
**Building Guardrails for Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01822v1)  

---


**ABSTRACT**  
As Large Language Models (LLMs) become more integrated into our daily lives, it is crucial to identify and mitigate their risks, especially when the risks can have profound impacts on human users and societies. Guardrails, which filter the inputs or outputs of LLMs, have emerged as a core safeguarding technology. This position paper takes a deep look at current open-source solutions (Llama Guard, Nvidia NeMo, Guardrails AI), and discusses the challenges and the road towards building more complete solutions. Drawing on robust evidence from previous research, we advocate for a systematic approach to construct guardrails for LLMs, based on comprehensive consideration of diverse contexts across various LLMs applications. We propose employing socio-technical methods through collaboration with a multi-disciplinary team to pinpoint precise technical requirements, exploring advanced neural-symbolic implementations to embrace the complexity of the requirements, and developing verification and testing to ensure the utmost quality of the final product.

{{</citation>}}


### (15/175) An Empirical Analysis of Diversity in Argument Summarization (Michiel van der Meer et al., 2024)

{{<citation>}}

Michiel van der Meer, Piek Vossen, Catholijn M. Jonker, Pradeep K. Murukannaiah. (2024)  
**An Empirical Analysis of Diversity in Argument Summarization**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Key Point Analysis, Summarization  
[Paper Link](http://arxiv.org/abs/2402.01535v1)  

---


**ABSTRACT**  
Presenting high-level arguments is a crucial task for fostering participation in online societal discussions. Current argument summarization approaches miss an important facet of this task -- capturing diversity -- which is important for accommodating multiple perspectives. We introduce three aspects of diversity: those of opinions, annotators, and sources. We evaluate approaches to a popular argument summarization task called Key Point Analysis, which shows how these approaches struggle to (1) represent arguments shared by few people, (2) deal with data from various sources, and (3) align with subjectivity in human-provided annotations. We find that both general-purpose LLMs and dedicated KPA models exhibit this behavior, but have complementary strengths. Further, we observe that diversification of training data may ameliorate generalization. Addressing diversity in argument summarization requires a mix of strategies to deal with subjectivity.

{{</citation>}}


### (16/175) K-Level Reasoning with Large Language Models (Yadong Zhang et al., 2024)

{{<citation>}}

Yadong Zhang, Shaoguang Mao, Tao Ge, Xun Wang, Yan Xia, Man Lan, Furu Wei. (2024)  
**K-Level Reasoning with Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model, Reasoning  
[Paper Link](http://arxiv.org/abs/2402.01521v1)  

---


**ABSTRACT**  
While Large Language Models (LLMs) have demonstrated their proficiency in complex reasoning tasks, their performance in dynamic, interactive, and competitive scenarios - such as business strategy and stock market analysis - remains underexplored. To bridge this gap, we formally explore the dynamic reasoning capabilities of LLMs for decision-making in rapidly evolving environments. We introduce two game theory-based pilot challenges that mirror the complexities of real-world dynamic decision-making. These challenges are well-defined, enabling clear, controllable, and precise evaluation of LLMs' dynamic reasoning abilities. Through extensive experiments, we find that existing reasoning methods tend to falter in dynamic settings that require k-level thinking - a key concept not tackled by previous works. To address this, we propose a novel reasoning approach for LLMs, named "K-Level Reasoning". This approach adopts the perspective of rivals to recursively employ k-level thinking based on available historical information, which significantly improves the prediction accuracy of rivals' subsequent moves and informs more strategic decision-making. This research not only sets a robust quantitative benchmark for the assessment of dynamic reasoning but also markedly enhances the proficiency of LLMs in dynamic contexts.

{{</citation>}}


### (17/175) Multilingual Gradient Word-Order Typology from Universal Dependencies (Emi Baylor et al., 2024)

{{<citation>}}

Emi Baylor, Esther Ploeger, Johannes Bjerva. (2024)  
**Multilingual Gradient Word-Order Typology from Universal Dependencies**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Multilingual, NLP  
[Paper Link](http://arxiv.org/abs/2402.01513v1)  

---


**ABSTRACT**  
While information from the field of linguistic typology has the potential to improve performance on NLP tasks, reliable typological data is a prerequisite. Existing typological databases, including WALS and Grambank, suffer from inconsistencies primarily caused by their categorical format. Furthermore, typological categorisations by definition differ significantly from the continuous nature of phenomena, as found in natural language corpora. In this paper, we introduce a new seed dataset made up of continuous-valued data, rather than categorical data, that can better reflect the variability of language. While this initial dataset focuses on word-order typology, we also present the methodology used to create the dataset, which can be easily adapted to generate data for a broader set of features and languages.

{{</citation>}}


### (18/175) A Hybrid Strategy for Chat Transcript Summarization (Pratik K. Biswas, 2024)

{{<citation>}}

Pratik K. Biswas. (2024)  
**A Hybrid Strategy for Chat Transcript Summarization**  

---
Primary Category: cs.CL  
Categories: 68, I-7, cs-CL, cs.CL  
Keywords: Summarization  
[Paper Link](http://arxiv.org/abs/2402.01510v1)  

---


**ABSTRACT**  
Text summarization is the process of condensing a piece of text to fewer sentences, while still preserving its content. Chat transcript, in this context, is a textual copy of a digital or online conversation between a customer (caller) and agent(s). This paper presents an indigenously (locally) developed hybrid method that first combines extractive and abstractive summarization techniques in compressing ill-punctuated or un-punctuated chat transcripts to produce more readable punctuated summaries and then optimizes the overall quality of summarization through reinforcement learning. Extensive testing, evaluations, comparisons, and validation have demonstrated the efficacy of this approach for large-scale deployment of chat transcript summarization, in the absence of manually generated reference (annotated) summaries.

{{</citation>}}


### (19/175) Code-Switched Language Identification is Harder Than You Think (Laurie Burchell et al., 2024)

{{<citation>}}

Laurie Burchell, Alexandra Birch, Robert P. Thompson, Kenneth Heafield. (2024)  
**Code-Switched Language Identification is Harder Than You Think**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Identification  
[Paper Link](http://arxiv.org/abs/2402.01505v1)  

---


**ABSTRACT**  
Code switching (CS) is a very common phenomenon in written and spoken communication but one that is handled poorly by many natural language processing applications. Looking to the application of building CS corpora, we explore CS language identification (LID) for corpus building. We make the task more realistic by scaling it to more languages and considering models with simpler architectures for faster inference. We also reformulate the task as a sentence-level multi-label tagging problem to make it more tractable. Having defined the task, we investigate three reasonable models for this task and define metrics which better reflect desired performance. We present empirical evidence that no current approach is adequate and finally provide recommendations for future work in this area.

{{</citation>}}


### (20/175) A Comparative Analysis of Conversational Large Language Models in Knowledge-Based Text Generation (Phillip Schneider et al., 2024)

{{<citation>}}

Phillip Schneider, Manuel Klettner, Elena Simperl, Florian Matthes. (2024)  
**A Comparative Analysis of Conversational Large Language Models in Knowledge-Based Text Generation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, Text Generation  
[Paper Link](http://arxiv.org/abs/2402.01495v1)  

---


**ABSTRACT**  
Generating natural language text from graph-structured data is essential for conversational information seeking. Semantic triples derived from knowledge graphs can serve as a valuable source for grounding responses from conversational agents by providing a factual basis for the information they communicate. This is especially relevant in the context of large language models, which offer great potential for conversational interaction but are prone to hallucinating, omitting, or producing conflicting information. In this study, we conduct an empirical analysis of conversational large language models in generating natural language text from semantic triples. We compare four large language models of varying sizes with different prompting techniques. Through a series of benchmark experiments on the WebNLG dataset, we analyze the models' performance and identify the most common issues in the generated predictions. Our findings show that the capabilities of large language models in triple verbalization can be significantly improved through few-shot prompting, post-processing, and efficient fine-tuning techniques, particularly for smaller models that exhibit lower zero-shot performance.

{{</citation>}}


### (21/175) The Queen of England is not England's Queen: On the Lack of Factual Coherency in PLMs (Paul Youssef et al., 2024)

{{<citation>}}

Paul Youssef, Jörg Schlötterer, Christin Seifert. (2024)  
**The Queen of England is not England's Queen: On the Lack of Factual Coherency in PLMs**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01453v1)  

---


**ABSTRACT**  
Factual knowledge encoded in Pre-trained Language Models (PLMs) enriches their representations and justifies their use as knowledge bases. Previous work has focused on probing PLMs for factual knowledge by measuring how often they can correctly predict an object entity given a subject and a relation, and improving fact retrieval by optimizing the prompts used for querying PLMs. In this work, we consider a complementary aspect, namely the coherency of factual knowledge in PLMs, i.e., how often can PLMs predict the subject entity given its initial prediction of the object entity. This goes beyond evaluating how much PLMs know, and focuses on the internal state of knowledge inside them. Our results indicate that PLMs have low coherency using manually written, optimized and paraphrased prompts, but including an evidence paragraph leads to substantial improvement. This shows that PLMs fail to model inverse relations and need further enhancements to be able to handle retrieving facts from their parameters in a coherent manner, and to be considered as knowledge bases.

{{</citation>}}


### (22/175) Different Tastes of Entities: Investigating Human Label Variation in Named Entity Annotations (Siyao Peng et al., 2024)

{{<citation>}}

Siyao Peng, Zihang Sun, Sebastian Loftus, Barbara Plank. (2024)  
**Different Tastes of Entities: Investigating Human Label Variation in Named Entity Annotations**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NER, Named Entity Recognition  
[Paper Link](http://arxiv.org/abs/2402.01423v1)  

---


**ABSTRACT**  
Named Entity Recognition (NER) is a key information extraction task with a long-standing tradition. While recent studies address and aim to correct annotation errors via re-labeling efforts, little is known about the sources of human label variation, such as text ambiguity, annotation error, or guideline divergence. This is especially the case for high-quality datasets and beyond English CoNLL03. This paper studies disagreements in expert-annotated named entity datasets for three languages: English, Danish, and Bavarian. We show that text ambiguity and artificial guideline changes are dominant factors for diverse annotations among high-quality revisions. We survey student annotations on a subset of difficult entities and substantiate the feasibility and necessity of manifold annotations for understanding named entity ambiguities from a distributional perspective.

{{</citation>}}


### (23/175) Sequence Shortening for Context-Aware Machine Translation (Paweł Mąka et al., 2024)

{{<citation>}}

Paweł Mąka, Yusuf Can Semerci, Jan Scholtes, Gerasimos Spanakis. (2024)  
**Sequence Shortening for Context-Aware Machine Translation**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: BLEU, Machine Translation  
[Paper Link](http://arxiv.org/abs/2402.01416v1)  

---


**ABSTRACT**  
Context-aware Machine Translation aims to improve translations of sentences by incorporating surrounding sentences as context. Towards this task, two main architectures have been applied, namely single-encoder (based on concatenation) and multi-encoder models. In this study, we show that a special case of multi-encoder architecture, where the latent representation of the source sentence is cached and reused as the context in the next step, achieves higher accuracy on the contrastive datasets (where the models have to rank the correct translation among the provided sentences) and comparable BLEU and COMET scores as the single- and multi-encoder approaches. Furthermore, we investigate the application of Sequence Shortening to the cached representations. We test three pooling-based shortening techniques and introduce two novel methods - Latent Grouping and Latent Selecting, where the network learns to group tokens or selects the tokens to be cached as context. Our experiments show that the two methods achieve competitive BLEU and COMET scores and accuracies on the contrastive datasets to the other tested methods while potentially allowing for higher interpretability and reducing the growth of memory requirements with increased context size.

{{</citation>}}


### (24/175) On Measuring Context Utilization in Document-Level MT Systems (Wafaa Mohammed et al., 2024)

{{<citation>}}

Wafaa Mohammed, Vlad Niculae. (2024)  
**On Measuring Context Utilization in Document-Level MT Systems**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BLEU  
[Paper Link](http://arxiv.org/abs/2402.01404v1)  

---


**ABSTRACT**  
Document-level translation models are usually evaluated using general metrics such as BLEU, which are not informative about the benefits of context. Current work on context-aware evaluation, such as contrastive methods, only measure translation accuracy on words that need context for disambiguation. Such measures cannot reveal whether the translation model uses the correct supporting context. We propose to complement accuracy-based evaluation with measures of context utilization. We find that perturbation-based analysis (comparing models' performance when provided with correct versus random context) is an effective measure of overall context utilization. For a finer-grained phenomenon-specific evaluation, we propose to measure how much the supporting context contributes to handling context-dependent discourse phenomena. We show that automatically-annotated supporting context gives similar conclusions to human-annotated context and can be used as alternative for cases where human annotations are not available. Finally, we highlight the importance of using discourse-rich datasets when assessing context utilization.

{{</citation>}}


### (25/175) Distilling LLMs' Decomposition Abilities into Compact Language Models (Denis Tarasov et al., 2024)

{{<citation>}}

Denis Tarasov, Kumar Shridhar. (2024)  
**Distilling LLMs' Decomposition Abilities into Compact Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01812v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have demonstrated proficiency in their reasoning abilities, yet their large size presents scalability challenges and limits any further customization. In contrast, compact models offer customized training but often fall short in solving complex reasoning tasks. This study focuses on distilling the LLMs' decomposition skills into compact models using offline reinforcement learning. We leverage the advancements in the LLM`s capabilities to provide feedback and generate a specialized task-specific dataset for training compact models. The development of an AI-generated dataset and the establishment of baselines constitute the primary contributions of our work, underscoring the potential of compact models in replicating complex problem-solving skills.

{{</citation>}}


### (26/175) LLM-based NLG Evaluation: Current Status and Challenges (Mingqi Gao et al., 2024)

{{<citation>}}

Mingqi Gao, Xinyu Hu, Jie Ruan, Xiao Pu, Xiaojun Wan. (2024)  
**LLM-based NLG Evaluation: Current Status and Challenges**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2402.01383v1)  

---


**ABSTRACT**  
Evaluating natural language generation (NLG) is a vital but challenging problem in artificial intelligence. Traditional evaluation metrics mainly capturing content (e.g. n-gram) overlap between system outputs and references are far from satisfactory, and large language models (LLMs) such as ChatGPT have demonstrated great potential in NLG evaluation in recent years. Various automatic evaluation methods based on LLMs have been proposed, including metrics derived from LLMs, prompting LLMs, and fine-tuning LLMs with labeled evaluation data. In this survey, we first give a taxonomy of LLM-based NLG evaluation methods, and discuss their pros and cons, respectively. We also discuss human-LLM collaboration for NLG evaluation. Lastly, we discuss several open problems in this area and point out future research directions.

{{</citation>}}


### (27/175) LoTR: Low Tensor Rank Weight Adaptation (Daniel Bershatsky et al., 2024)

{{<citation>}}

Daniel Bershatsky, Daria Cherniuk, Talgat Daulbaev, Aleksandr Mikhalev, Ivan Oseledets. (2024)  
**LoTR: Low Tensor Rank Weight Adaptation**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2402.01376v2)  

---


**ABSTRACT**  
In this paper we generalize and extend an idea of low-rank adaptation (LoRA) of large language models (LLMs) based on Transformer architecture. Widely used LoRA-like methods of fine-tuning LLMs are based on matrix factorization of gradient update. We introduce LoTR, a novel approach for parameter-efficient fine-tuning of LLMs which represents a gradient update to parameters in a form of tensor decomposition. Low-rank adapter for each layer is constructed as a product of three matrices, and tensor structure arises from sharing left and right multipliers of this product among layers. Simultaneous compression of a sequence of layers with low-rank tensor representation allows LoTR to archive even better parameter efficiency then LoRA especially for deep models. Moreover, the core tensor does not depend on original weight dimension and can be made arbitrary small, which allows for extremely cheap and fast downstream fine-tuning.

{{</citation>}}


### (28/175) Continual Learning for Large Language Models: A Survey (Tongtong Wu et al., 2024)

{{<citation>}}

Tongtong Wu, Linhao Luo, Yuan-Fang Li, Shirui Pan, Thuy-Trang Vu, Gholamreza Haffari. (2024)  
**Continual Learning for Large Language Models: A Survey**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01364v2)  

---


**ABSTRACT**  
Large language models (LLMs) are not amenable to frequent re-training, due to high training costs arising from their massive scale. However, updates are necessary to endow LLMs with new skills and keep them up-to-date with rapidly evolving human knowledge. This paper surveys recent works on continual learning for LLMs. Due to the unique nature of LLMs, we catalog continue learning techniques in a novel multi-staged categorization scheme, involving continual pretraining, instruction tuning, and alignment. We contrast continual learning for LLMs with simpler adaptation methods used in smaller models, as well as with other enhancement strategies like retrieval-augmented generation and model editing. Moreover, informed by a discussion of benchmarks and evaluation, we identify several challenges and future work directions for this crucial task.

{{</citation>}}


### (29/175) What Makes Medical Claims (Un)Verifiable? Analyzing Entity and Relation Properties for Fact Verification (Amelie Wührl et al., 2024)

{{<citation>}}

Amelie Wührl, Yarik Menchaca Resendiz, Lara Grimminger, Roman Klinger. (2024)  
**What Makes Medical Claims (Un)Verifiable? Analyzing Entity and Relation Properties for Fact Verification**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Fact Verification  
[Paper Link](http://arxiv.org/abs/2402.01360v1)  

---


**ABSTRACT**  
Biomedical claim verification fails if no evidence can be discovered. In these cases, the fact-checking verdict remains unknown and the claim is unverifiable. To improve upon this, we have to understand if there are any claim properties that impact its verifiability. In this work we assume that entities and relations define the core variables in a biomedical claim's anatomy and analyze if their properties help us to differentiate verifiable from unverifiable claims. In a study with trained annotation experts we prompt them to find evidence for biomedical claims, and observe how they refine search queries for their evidence search. This leads to the first corpus for scientific fact verification annotated with subject-relation-object triplets, evidence documents, and fact-checking verdicts (the BEAR-Fact corpus). We find (1) that discovering evidence for negated claims (e.g., X-does-not-cause-Y) is particularly challenging. Further, we see that annotators process queries mostly by adding constraints to the search and by normalizing entities to canonical names. (2) We compare our in-house annotations with a small crowdsourcing setting where we employ medical experts and laypeople. We find that domain expertise does not have a substantial effect on the reliability of annotations. Finally, (3), we demonstrate that it is possible to reliably estimate the success of evidence retrieval purely from the claim text~(.82\F), whereas identifying unverifiable claims proves more challenging (.27\F). The dataset is available at http://www.ims.uni-stuttgart.de/data/bioclaim.

{{</citation>}}


### (30/175) Beyond the Answers: Reviewing the Rationality of Multiple Choice Question Answering for the Evaluation of Large Language Models (Haochun Wang et al., 2024)

{{<citation>}}

Haochun Wang, Sendong Zhao, Zewen Qiang, Bing Qin, Ting Liu. (2024)  
**Beyond the Answers: Reviewing the Rationality of Multiple Choice Question Answering for the Evaluation of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model, NLP, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2402.01349v1)  

---


**ABSTRACT**  
In the field of natural language processing (NLP), Large Language Models (LLMs) have precipitated a paradigm shift, markedly enhancing performance in natural language generation tasks. Despite these advancements, the comprehensive evaluation of LLMs remains an inevitable challenge for the community. Recently, the utilization of Multiple Choice Question Answering (MCQA) as a benchmark for LLMs has gained considerable traction. This study investigates the rationality of MCQA as an evaluation method for LLMs. If LLMs genuinely understand the semantics of questions, their performance should exhibit consistency across the varied configurations derived from the same questions. Contrary to this expectation, our empirical findings suggest a notable disparity in the consistency of LLM responses, which we define as REsponse VAriability Syndrome (REVAS) of the LLMs, indicating that current MCQA-based benchmarks may not adequately capture the true capabilities of LLMs, which underscores the need for more robust evaluation mechanisms in assessing the performance of LLMs.

{{</citation>}}


### (31/175) HQA-Attack: Toward High Quality Black-Box Hard-Label Adversarial Attack on Text (Han Liu et al., 2024)

{{<citation>}}

Han Liu, Zhi Xu, Xiaotong Zhang, Feng Zhang, Fenglong Ma, Hongyang Chen, Hong Yu, Xianchao Zhang. (2024)  
**HQA-Attack: Toward High Quality Black-Box Hard-Label Adversarial Attack on Text**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Adversarial Attack, QA  
[Paper Link](http://arxiv.org/abs/2402.01806v1)  

---


**ABSTRACT**  
Black-box hard-label adversarial attack on text is a practical and challenging task, as the text data space is inherently discrete and non-differentiable, and only the predicted label is accessible. Research on this problem is still in the embryonic stage and only a few methods are available. Nevertheless, existing methods rely on the complex heuristic algorithm or unreliable gradient estimation strategy, which probably fall into the local optimum and inevitably consume numerous queries, thus are difficult to craft satisfactory adversarial examples with high semantic similarity and low perturbation rate in a limited query budget. To alleviate above issues, we propose a simple yet effective framework to generate high quality textual adversarial examples under the black-box hard-label attack scenarios, named HQA-Attack. Specifically, after initializing an adversarial example randomly, HQA-attack first constantly substitutes original words back as many as possible, thus shrinking the perturbation rate. Then it leverages the synonym set of the remaining changed words to further optimize the adversarial example with the direction which can improve the semantic similarity and satisfy the adversarial condition simultaneously. In addition, during the optimizing procedure, it searches a transition synonym word for each changed word, thus avoiding traversing the whole synonym set and reducing the query number to some extent. Extensive experimental results on five text classification datasets, three natural language inference datasets and two real-world APIs have shown that the proposed HQA-Attack method outperforms other strong baselines significantly.

{{</citation>}}


### (32/175) Exploring the Limitations of Graph Reasoning in Large Language Models (Palaash Agrawal et al., 2024)

{{<citation>}}

Palaash Agrawal, Shavak Vasania, Cheston Tan. (2024)  
**Exploring the Limitations of Graph Reasoning in Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT, GPT-3.5, GPT-4, Language Model, Reasoning  
[Paper Link](http://arxiv.org/abs/2402.01805v1)  

---


**ABSTRACT**  
Pretrained Large Language Models have demonstrated various types of reasoning capabilities through language-based prompts alone. However, in this paper, we test the depth of graph reasoning for 5 different LLMs (GPT-4, GPT-3.5, Claude-2, Llama-2 and Palm-2) through the problems of graph reasoning. In particular, we design 10 distinct problems of graph traversal, each representing increasing levels of complexity. Further, we analyze the performance of models across various settings such as varying sizes of graphs as well as different forms of k-shot prompting. We highlight various limitations, biases, and properties of LLMs through this benchmarking process, such as an inverse relation to the average degrees of freedom of traversal per node in graphs, the overall negative impact of k-shot prompting on graph reasoning tasks, and a positive response bias which prevents LLMs from identifying the absence of a valid solution. Finally, we propose a new prompting technique specially designed for graph traversal tasks, known as PathCompare, which shows a notable increase in the performance of LLMs in comparison to standard prompting and CoT.

{{</citation>}}


### (33/175) The Human and the Mechanical: logos, truthfulness, and ChatGPT (Anastasia Giannakidou et al., 2024)

{{<citation>}}

Anastasia Giannakidou, Alda Mari. (2024)  
**The Human and the Mechanical: logos, truthfulness, and ChatGPT**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2402.01267v1)  

---


**ABSTRACT**  
The paper addresses the question of whether it is appropriate to talk about `mechanical minds' at all, and whether ChatGPT models can indeed be thought of as realizations of that. Our paper adds a semantic argument to the current debate. The act of human assertion requires the formation of a veridicality judgment. Modification of assertions with modals (John must be at home) and the use of subjective elements (John is obviously at home) indicate that the speaker is manipulating her judgments and, in a cooperative context, intends her epistemic state to be transparent to the addressee. Veridicality judgments are formed on the basis of two components: (i) evidence that relates to reality (exogenous evidence) and (ii) endogenous evidence, such as preferences and private beliefs. `Mechanical minds' lack these two components: (i) they do not relate to reality and (ii) do not have endogenous evidence. Therefore they lack the ability to form a belief about the world and a veridicality judgments altogether. They can only mimic that judgment, but the output is not ground in the very foundations for it.

{{</citation>}}


### (34/175) In-Context Learning for Few-Shot Nested Named Entity Recognition (Meishan Zhang et al., 2024)

{{<citation>}}

Meishan Zhang, Bin Wang, Hao Fei, Min Zhang. (2024)  
**In-Context Learning for Few-Shot Nested Named Entity Recognition**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Few-Shot, NER, Named Entity Recognition  
[Paper Link](http://arxiv.org/abs/2402.01182v1)  

---


**ABSTRACT**  
In nested Named entity recognition (NER), entities are nested with each other, and thus requiring more data annotations to address. This leads to the development of few-shot nested NER, where the prevalence of pretrained language models with in-context learning (ICL) offers promising solutions. In this work, we introduce an effective and innovative ICL framework for the setting of few-shot nested NER. We improve the ICL prompt by devising a novel example demonstration selection mechanism, EnDe retriever. In EnDe retriever, we employ contrastive learning to perform three types of representation learning, in terms of semantic similarity, boundary similarity, and label similarity, to generate high-quality demonstration examples. Extensive experiments over three nested NER and four flat NER datasets demonstrate the efficacy of our system.

{{</citation>}}


### (35/175) Towards a Unified Language Model for Knowledge-Intensive Tasks Utilizing External Corpus (Xiaoxi Li et al., 2024)

{{<citation>}}

Xiaoxi Li, Zhicheng Dou, Yujia Zhou, Fangchao Liu. (2024)  
**Towards a Unified Language Model for Knowledge-Intensive Tasks Utilizing External Corpus**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-IR, cs.CL  
Keywords: Language Model, T5  
[Paper Link](http://arxiv.org/abs/2402.01176v1)  

---


**ABSTRACT**  
The advent of large language models (LLMs) has showcased their efficacy across various domains, yet they often hallucinate, especially in knowledge-intensive tasks that require external knowledge sources. To improve factual accuracy of language models, retrieval-augmented generation (RAG) has emerged as a popular solution. However, traditional retrieval modules often rely on large-scale document indexes, which can be disconnected from generative tasks. Through generative retrieval (GR) approach, language models can achieve superior retrieval performance by directly generating relevant document identifiers (DocIDs). However, the relationship between GR and downstream tasks, as well as the potential of LLMs in GR, remains unexplored. In this paper, we present a unified language model that utilizes external corpus to handle various knowledge-intensive tasks by seamlessly integrating generative retrieval, closed-book generation, and RAG. In order to achieve effective retrieval and generation through a unified continuous decoding process, we introduce the following mechanisms: (1) a ranking-oriented DocID decoding strategy, which improves ranking ability by directly learning from a DocID ranking list; (2) a continuous generation strategy to facilitate effective and efficient RAG; (3) well-designed auxiliary DocID understanding tasks to enhance the model's comprehension of DocIDs and their relevance to downstream tasks. Our approach is evaluated on the widely used KILT benchmark using two variants of backbone models: an encoder-decoder T5 model and a decoder-only LLM, Llama2. Experimental results showcase the superior performance of our models in both retrieval and downstream knowledge-intensive tasks.

{{</citation>}}


### (36/175) Efficient Prompt Caching via Embedding Similarity (Hanlin Zhu et al., 2024)

{{<citation>}}

Hanlin Zhu, Banghua Zhu, Jiantao Jiao. (2024)  
**Efficient Prompt Caching via Embedding Similarity**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Embedding, NLP  
[Paper Link](http://arxiv.org/abs/2402.01173v1)  

---


**ABSTRACT**  
Large language models (LLMs) have achieved huge success in numerous natural language process (NLP) tasks. However, it faces the challenge of significant resource consumption during inference. In this paper, we aim to improve the inference efficiency of LLMs by prompt caching, i.e., if the current prompt can be answered by the same response of a previous prompt, one can directly utilize that previous response without calling the LLM. Specifically, we focus on the prediction accuracy of prompt caching for single-round question-answering tasks via embedding similarity. The existing embeddings of prompts mostly focus on whether two prompts are semantically similar, which is not necessarily equivalent to whether the same response can answer them. Therefore, we propose a distillation-based method to fine-tune the existing embeddings for better caching prediction. Theoretically, we provide finite-sample guarantees for the convergence of our method under different types of loss functions. Empirically, we carefully construct a hard dataset based on Kwiatkowski et al. (2019) where the existing embedding model (Wang et al., 2022) only achieves an AUC of 0.51. We then fine-tune the above embedding model, which significantly improves the AUC of caching prediction from 0.51 to 0.81. We also conduct simulations demonstrating that our trained models achieve better caching efficiency than the previous embedding model.

{{</citation>}}


### (37/175) Streaming Sequence Transduction through Dynamic Compression (Weiting Tan et al., 2024)

{{<citation>}}

Weiting Tan, Yunmo Chen, Tongfei Chen, Guanghui Qin, Haoran Xu, Heidi C. Zhang, Benjamin Van Durme, Philipp Koehn. (2024)  
**Streaming Sequence Transduction through Dynamic Compression**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: Speech Recognition, Transformer  
[Paper Link](http://arxiv.org/abs/2402.01172v1)  

---


**ABSTRACT**  
We introduce STAR (Stream Transduction with Anchor Representations), a novel Transformer-based model designed for efficient sequence-to-sequence transduction over streams. STAR dynamically segments input streams to create compressed anchor representations, achieving nearly lossless compression (12x) in Automatic Speech Recognition (ASR) and outperforming existing methods. Moreover, STAR demonstrates superior segmentation and latency-quality trade-offs in simultaneous speech-to-text tasks, optimizing latency, memory footprint, and quality.

{{</citation>}}


### (38/175) LLM-Detector: Improving AI-Generated Chinese Text Detection with Open-Source LLM Instruction Tuning (Rongsheng Wang et al., 2024)

{{<citation>}}

Rongsheng Wang, Haoming Chen, Ruizhe Zhou, Han Ma, Yaofei Duan, Yanlan Kang, Songhua Yang, Baoyu Fan, Tao Tan. (2024)  
**LLM-Detector: Improving AI-Generated Chinese Text Detection with Open-Source LLM Instruction Tuning**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, BERT, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2402.01158v1)  

---


**ABSTRACT**  
ChatGPT and other general large language models (LLMs) have achieved remarkable success, but they have also raised concerns about the misuse of AI-generated texts. Existing AI-generated text detection models, such as based on BERT and RoBERTa, are prone to in-domain over-fitting, leading to poor out-of-domain (OOD) detection performance. In this paper, we first collected Chinese text responses generated by human experts and 9 types of LLMs, for which to multiple domains questions, and further created a dataset that mixed human-written sentences and sentences polished by LLMs. We then proposed LLM-Detector, a novel method for both document-level and sentence-level text detection through Instruction Tuning of LLMs. Our method leverages the wealth of knowledge LLMs acquire during pre-training, enabling them to detect the text they generate. Instruction tuning aligns the model's responses with the user's expected text detection tasks. Experimental results show that previous methods struggle with sentence-level AI-generated text detection and OOD detection. In contrast, our proposed method not only significantly outperforms baseline methods in both sentence-level and document-level text detection but also demonstrates strong generalization capabilities. Furthermore, since LLM-Detector is trained based on open-source LLMs, it is easy to customize for deployment.

{{</citation>}}


### (39/175) CABINET: Content Relevance based Noise Reduction for Table Question Answering (Sohan Patnaik et al., 2024)

{{<citation>}}

Sohan Patnaik, Heril Changwal, Milan Aggarwal, Sumit Bhatia, Yaman Kumar, Balaji Krishnamurthy. (2024)  
**CABINET: Content Relevance based Noise Reduction for Table Question Answering**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, Language Model, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2402.01155v2)  

---


**ABSTRACT**  
Table understanding capability of Large Language Models (LLMs) has been extensively studied through the task of question-answering (QA) over tables. Typically, only a small part of the whole table is relevant to derive the answer for a given question. The irrelevant parts act as noise and are distracting information, resulting in sub-optimal performance due to the vulnerability of LLMs to noise. To mitigate this, we propose CABINET (Content RelevAnce-Based NoIse ReductioN for TablE QuesTion-Answering) - a framework to enable LLMs to focus on relevant tabular data by suppressing extraneous information. CABINET comprises an Unsupervised Relevance Scorer (URS), trained differentially with the QA LLM, that weighs the table content based on its relevance to the input question before feeding it to the question-answering LLM (QA LLM). To further aid the relevance scorer, CABINET employs a weakly supervised module that generates a parsing statement describing the criteria of rows and columns relevant to the question and highlights the content of corresponding table cells. CABINET significantly outperforms various tabular LLM baselines, as well as GPT3-based in-context learning methods, is more robust to noise, maintains outperformance on tables of varying sizes, and establishes new SoTA performance on WikiTQ, FeTaQA, and WikiSQL datasets. We release our code and datasets at https://github.com/Sohanpatnaik106/CABINET_QA.

{{</citation>}}


### (40/175) AccentFold: A Journey through African Accents for Zero-Shot ASR Adaptation to Target Accents (Abraham Toluwase Owodunni et al., 2024)

{{<citation>}}

Abraham Toluwase Owodunni, Aditya Yadavalli, Chris Chinenye Emezue, Tobi Olatunji, Clinton C Mbataku. (2024)  
**AccentFold: A Journey through African Accents for Zero-Shot ASR Adaptation to Target Accents**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: Speech Recognition, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2402.01152v2)  

---


**ABSTRACT**  
Despite advancements in speech recognition, accented speech remains challenging. While previous approaches have focused on modeling techniques or creating accented speech datasets, gathering sufficient data for the multitude of accents, particularly in the African context, remains impractical due to their sheer diversity and associated budget constraints. To address these challenges, we propose AccentFold, a method that exploits spatial relationships between learned accent embeddings to improve downstream Automatic Speech Recognition (ASR). Our exploratory analysis of speech embeddings representing 100+ African accents reveals interesting spatial accent relationships highlighting geographic and genealogical similarities, capturing consistent phonological, and morphological regularities, all learned empirically from speech. Furthermore, we discover accent relationships previously uncharacterized by the Ethnologue. Through empirical evaluation, we demonstrate the effectiveness of AccentFold by showing that, for out-of-distribution (OOD) accents, sampling accent subsets for training based on AccentFold information outperforms strong baselines a relative WER improvement of 4.6%. AccentFold presents a promising approach for improving ASR performance on accented speech, particularly in the context of African accents, where data scarcity and budget constraints pose significant challenges. Our findings emphasize the potential of leveraging linguistic relationships to improve zero-shot ASR adaptation to target accents.

{{</citation>}}


### (41/175) DTS-SQL: Decomposed Text-to-SQL with Small Large Language Models (Mohammadreza Pourreza et al., 2024)

{{<citation>}}

Mohammadreza Pourreza, Davood Rafiei. (2024)  
**DTS-SQL: Decomposed Text-to-SQL with Small Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-DB, cs-HC, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01117v1)  

---


**ABSTRACT**  
Leading models for the text-to-SQL task heavily rely on proprietary Large Language Models (LLMs), posing concerns over data privacy. Closing the performance gap between small open-source models and large proprietary models is crucial to mitigate this reliance. To this end, we introduce a novel two-stage fine-tuning approach that decomposes the task into two simpler tasks. Through comprehensive evaluation on two large cross-domain datasets and two small LLMs, we show that this approach improves execution accuracy by 3 to 7 percent, effectively aligning the performance of open-source models with their proprietary counterparts.

{{</citation>}}


### (42/175) Interpretation of Intracardiac Electrograms Through Textual Representations (William Jongwon Han et al., 2024)

{{<citation>}}

William Jongwon Han, Diana Gomez, Avi Alok, Chaojing Duan, Michael A. Rosenberg, Douglas Weber, Emerson Liu, Ding Zhao. (2024)  
**Interpretation of Intracardiac Electrograms Through Textual Representations**  

---
Primary Category: cs.CL  
Categories: I-2-7; J-3, cs-CL, cs.CL, eess-SP  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01115v1)  

---


**ABSTRACT**  
Understanding the irregular electrical activity of atrial fibrillation (AFib) has been a key challenge in electrocardiography. For serious cases of AFib, catheter ablations are performed to collect intracardiac electrograms (EGMs). EGMs offer intricately detailed and localized electrical activity of the heart and are an ideal modality for interpretable cardiac studies. Recent advancements in artificial intelligence (AI) has allowed some works to utilize deep learning frameworks to interpret EGMs during AFib. Additionally, language models (LMs) have shown exceptional performance in being able to generalize to unseen domains, especially in healthcare. In this study, we are the first to leverage pretrained LMs for finetuning of EGM interpolation and AFib classification via masked language modeling. We formulate the EGM as a textual sequence and present competitive performances on AFib classification compared against other representations. Lastly, we provide a comprehensive interpretability study to provide a multi-perspective intuition of the model's behavior, which could greatly benefit the clinical use.

{{</citation>}}


### (43/175) Reasoning Capacity in Multi-Agent Systems: Limitations, Challenges and Human-Centered Solutions (Pouya Pezeshkpour et al., 2024)

{{<citation>}}

Pouya Pezeshkpour, Eser Kandogan, Nikita Bhutani, Sajjadur Rahman, Tom Mitchell, Estevam Hruschka. (2024)  
**Reasoning Capacity in Multi-Agent Systems: Limitations, Challenges and Human-Centered Solutions**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2402.01108v1)  

---


**ABSTRACT**  
Remarkable performance of large language models (LLMs) in a variety of tasks brings forth many opportunities as well as challenges of utilizing them in production settings. Towards practical adoption of LLMs, multi-agent systems hold great promise to augment, integrate, and orchestrate LLMs in the larger context of enterprise platforms that use existing proprietary data and models to tackle complex real-world tasks. Despite the tremendous success of these systems, current approaches rely on narrow, single-focus objectives for optimization and evaluation, often overlooking potential constraints in real-world scenarios, including restricted budgets, resources and time. Furthermore, interpreting, analyzing, and debugging these systems requires different components to be evaluated in relation to one another. This demand is currently not feasible with existing methodologies. In this postion paper, we introduce the concept of reasoning capacity as a unifying criterion to enable integration of constraints during optimization and establish connections among different components within the system, which also enable a more holistic and comprehensive approach to evaluation. We present a formal definition of reasoning capacity and illustrate its utility in identifying limitations within each component of the system. We then argue how these limitations can be addressed with a self-reflective process wherein human-feedback is used to alleviate shortcomings in reasoning and enhance overall consistency of the system.

{{</citation>}}


### (44/175) LitLLM: A Toolkit for Scientific Literature Review (Shubham Agarwal et al., 2024)

{{<citation>}}

Shubham Agarwal, Issam H. Laradji, Laurent Charlin, Christopher Pal. (2024)  
**LitLLM: A Toolkit for Scientific Literature Review**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-IR, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01788v1)  

---


**ABSTRACT**  
Conducting literature reviews for scientific papers is essential for understanding research, its limitations, and building on existing work. It is a tedious task which makes an automatic literature review generator appealing. Unfortunately, many existing works that generate such reviews using Large Language Models (LLMs) have significant limitations. They tend to hallucinate-generate non-actual information-and ignore the latest research they have not been trained on. To address these limitations, we propose a toolkit that operates on Retrieval Augmented Generation (RAG) principles, specialized prompting and instructing techniques with the help of LLMs. Our system first initiates a web search to retrieve relevant papers by summarizing user-provided abstracts into keywords using an off-the-shelf LLM. Authors can enhance the search by supplementing it with relevant papers or keywords, contributing to a tailored retrieval process. Second, the system re-ranks the retrieved papers based on the user-provided abstract. Finally, the related work section is generated based on the re-ranked results and the abstract. There is a substantial reduction in time and effort for literature review compared to traditional methods, establishing our toolkit as an efficient alternative. Our open-source toolkit is accessible at https://github.com/shubhamagarwal92/LitLLM and Huggingface space (https://huggingface.co/spaces/shubhamagarwal92/LitLLM) with the video demo at https://youtu.be/E2ggOZBAFw0.

{{</citation>}}


### (45/175) Let's Negotiate! A Survey of Negotiation Dialogue Systems (Haolan Zhan et al., 2024)

{{<citation>}}

Haolan Zhan, Yufei Wang, Tao Feng, Yuncheng Hua, Suraj Sharma, Zhuang Li, Lizhen Qu, Zhaleh Semnani Azad, Ingrid Zukerman, Gholamreza Haffari. (2024)  
**Let's Negotiate! A Survey of Negotiation Dialogue Systems**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue  
[Paper Link](http://arxiv.org/abs/2402.01097v1)  

---


**ABSTRACT**  
Negotiation is a crucial ability in human communication. Recently, there has been a resurgent research interest in negotiation dialogue systems, whose goal is to create intelligent agents that can assist people in resolving conflicts or reaching agreements. Although there have been many explorations into negotiation dialogue systems, a systematic review of this task has not been performed to date. We aim to fill this gap by investigating recent studies in the field of negotiation dialogue systems, and covering benchmarks, evaluations and methodologies within the literature. We also discuss potential future directions, including multi-modal, multi-party and cross-cultural negotiation scenarios. Our goal is to provide the community with a systematic overview of negotiation dialogue systems and to inspire future research.

{{</citation>}}


### (46/175) Reading Between the Tweets: Deciphering Ideological Stances of Interconnected Mixed-Ideology Communities (Zihao He et al., 2024)

{{<citation>}}

Zihao He, Ashwin Rao, Siyi Guo, Negar Mokhberian, Kristina Lerman. (2024)  
**Reading Between the Tweets: Deciphering Ideological Stances of Interconnected Mixed-Ideology Communities**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CY, cs-SI, cs.CL  
Keywords: NLP, Twitter  
[Paper Link](http://arxiv.org/abs/2402.01091v1)  

---


**ABSTRACT**  
Recent advances in NLP have improved our ability to understand the nuanced worldviews of online communities. Existing research focused on probing ideological stances treats liberals and conservatives as separate groups. However, this fails to account for the nuanced views of the organically formed online communities and the connections between them. In this paper, we study discussions of the 2020 U.S. election on Twitter to identify complex interacting communities. Capitalizing on this interconnectedness, we introduce a novel approach that harnesses message passing when finetuning language models (LMs) to probe the nuanced ideologies of these communities. By comparing the responses generated by LMs and real-world survey results, our method shows higher alignment than existing baselines, highlighting the potential of using LMs in revealing complex ideologies within and across interconnected mixed-ideology communities.

{{</citation>}}


## cs.CR (4)



### (47/175) Guarantees in Software Security (Marcel Böhme, 2024)

{{<citation>}}

Marcel Böhme. (2024)  
**Guarantees in Software Security**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-SE, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2402.01944v1)  

---


**ABSTRACT**  
We review general approaches to reason about the security of a software system and reflect upon the guarantees they provide. We introduce a taxonomy of fundamental challenges towards the provision of guarantees, and discuss how these challenges are routinely exploited to attack a system in spite of credible assurances about the absence of such bugs. It is only when we identify, study, and acknowledge the flaws in our current reasoning systems today that we can develop effective mitigation strategies in the future. To this end, we finally propose a research programme whose goal it is to tackle the software security challenges of this decade.

{{</citation>}}


### (48/175) AOC-IDS: Autonomous Online Framework with Contrastive Learning for Intrusion Detection (Xinchen Zhang et al., 2024)

{{<citation>}}

Xinchen Zhang, Running Zhao, Zhihan Jiang, Zhicong Sun, Yulong Ding, Edith C. H. Ngai, Shuang-Hua Yang. (2024)  
**AOC-IDS: Autonomous Online Framework with Contrastive Learning for Intrusion Detection**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Contrastive Learning, Intrusion Detection  
[Paper Link](http://arxiv.org/abs/2402.01807v1)  

---


**ABSTRACT**  
The rapid expansion of the Internet of Things (IoT) has raised increasing concern about targeted cyber attacks. Previous research primarily focused on static Intrusion Detection Systems (IDSs), which employ offline training to safeguard IoT systems. However, such static IDSs struggle with real-world scenarios where IoT system behaviors and attack strategies can undergo rapid evolution, necessitating dynamic and adaptable IDSs. In response to this challenge, we propose AOC-IDS, a novel online IDS that features an autonomous anomaly detection module (ADM) and a labor-free online framework for continual adaptation. In order to enhance data comprehension, the ADM employs an Autoencoder (AE) with a tailored Cluster Repelling Contrastive (CRC) loss function to generate distinctive representation from limited or incrementally incoming data in the online setting. Moreover, to reduce the burden of manual labeling, our online framework leverages pseudo-labels automatically generated from the decision-making process in the ADM to facilitate periodic updates of the ADM. The elimination of human intervention for labeling and decision-making boosts the system's compatibility and adaptability in the online setting to remain synchronized with dynamic environments. Experimental validation using the NSL-KDD and UNSW-NB15 datasets demonstrates the superior performance and adaptability of AOC-IDS, surpassing the state-of-the-art solutions. The code is released at https://github.com/xinchen930/AOC-IDS.

{{</citation>}}


### (49/175) AI Code Generators for Security: Friend or Foe? (Roberto Natella et al., 2024)

{{<citation>}}

Roberto Natella, Pietro Liguori, Cristina Improta, Bojan Cukic, Domenico Cotroneo. (2024)  
**AI Code Generators for Security: Friend or Foe?**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CR, cs-SE, cs.CR  
Keywords: AI, Security  
[Paper Link](http://arxiv.org/abs/2402.01219v1)  

---


**ABSTRACT**  
Recent advances of artificial intelligence (AI) code generators are opening new opportunities in software security research, including misuse by malicious actors. We review use cases for AI code generators for security and introduce an evaluation benchmark.

{{</citation>}}


### (50/175) Salsa Fresca: Angular Embeddings and Pre-Training for ML Attacks on Learning With Errors (Samuel Stevens et al., 2024)

{{<citation>}}

Samuel Stevens, Emily Wenger, Cathy Li, Niklas Nolte, Eshika Saxena, François Charton, Kristin Lauter. (2024)  
**Salsa Fresca: Angular Embeddings and Pre-Training for ML Attacks on Learning With Errors**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-LG, cs.CR  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2402.01082v1)  

---


**ABSTRACT**  
Learning with Errors (LWE) is a hard math problem underlying recently standardized post-quantum cryptography (PQC) systems for key exchange and digital signatures. Prior work proposed new machine learning (ML)-based attacks on LWE problems with small, sparse secrets, but these attacks require millions of LWE samples to train on and take days to recover secrets. We propose three key methods -- better preprocessing, angular embeddings and model pre-training -- to improve these attacks, speeding up preprocessing by $25\times$ and improving model sample efficiency by $10\times$. We demonstrate for the first time that pre-training improves and reduces the cost of ML attacks on LWE. Our architecture improvements enable scaling to larger-dimension LWE problems: this work is the first instance of ML attacks recovering sparse binary secrets in dimension $n=1024$, the smallest dimension used in practice for homomorphic encryption applications of LWE where sparse binary secrets are proposed.

{{</citation>}}


## cs.IR (4)



### (51/175) Clarifying the Path to User Satisfaction: An Investigation into Clarification Usefulness (Hossein A. Rahmani et al., 2024)

{{<citation>}}

Hossein A. Rahmani, Xi Wang, Mohammad Aliannejadi, Mohammadmehdi Naghiaei, Emine Yilmaz. (2024)  
**Clarifying the Path to User Satisfaction: An Investigation into Clarification Usefulness**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2402.01934v1)  

---


**ABSTRACT**  
Clarifying questions are an integral component of modern information retrieval systems, directly impacting user satisfaction and overall system performance. Poorly formulated questions can lead to user frustration and confusion, negatively affecting the system's performance. This research addresses the urgent need to identify and leverage key features that contribute to the classification of clarifying questions, enhancing user satisfaction. To gain deeper insights into how different features influence user satisfaction, we conduct a comprehensive analysis, considering a broad spectrum of lexical, semantic, and statistical features, such as question length and sentiment polarity. Our empirical results provide three main insights into the qualities of effective query clarification: (1) specific questions are more effective than generic ones; (2) the subjectivity and emotional tone of a question play a role; and (3) shorter and more ambiguous queries benefit significantly from clarification. Based on these insights, we implement feature-integrated user satisfaction prediction using various classifiers, both traditional and neural-based, including random forest, BERT, and large language models. Our experiments show a consistent and significant improvement, particularly in traditional classifiers, with a minimum performance boost of 45\%. This study presents invaluable guidelines for refining the formulation of clarifying questions and enhancing both user satisfaction and system performance.

{{</citation>}}


### (52/175) Improving Sequential Recommendations with LLMs (Artun Boz et al., 2024)

{{<citation>}}

Artun Boz, Wouter Zorgdrager, Zoe Kotti, Jesse Harte, Panos Louridas, Dietmar Jannach, Marios Fragkoulis. (2024)  
**Improving Sequential Recommendations with LLMs**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: AI, BERT, GPT, Google, Language Model, PaLM  
[Paper Link](http://arxiv.org/abs/2402.01339v1)  

---


**ABSTRACT**  
The sequential recommendation problem has attracted considerable research attention in the past few years, leading to the rise of numerous recommendation models. In this work, we explore how Large Language Models (LLMs), which are nowadays introducing disruptive effects in many AI-based applications, can be used to build or improve sequential recommendation approaches. Specifically, we design three orthogonal approaches and hybrids of those to leverage the power of LLMs in different ways. In addition, we investigate the potential of each approach by focusing on its comprising technical aspects and determining an array of alternative choices for each one. We conduct extensive experiments on three datasets and explore a large variety of configurations, including different language models and baseline recommendation models, to obtain a comprehensive picture of the performance of each approach. Among other observations, we highlight that initializing state-of-the-art sequential recommendation models such as BERT4Rec or SASRec with embeddings obtained from an LLM can lead to substantial performance gains in terms of accuracy. Furthermore, we find that fine-tuning an LLM for recommendation tasks enables it to learn not only the tasks, but also concepts of a domain to some extent. We also show that fine-tuning OpenAI GPT leads to considerably better performance than fine-tuning Google PaLM 2. Overall, our extensive experiments indicate a huge potential value of leveraging LLMs in future recommendation approaches. We publicly share the code and data of our experiments to ensure reproducibility.

{{</citation>}}


### (53/175) A Multi-Agent Conversational Recommender System (Jiabao Fang et al., 2024)

{{<citation>}}

Jiabao Fang, Shen Gao, Pengjie Ren, Xiuying Chen, Suzan Verberne, Zhaochun Ren. (2024)  
**A Multi-Agent Conversational Recommender System**  

---
Primary Category: cs.IR  
Categories: cs-CL, cs-IR, cs.IR  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01135v1)  

---


**ABSTRACT**  
Due to strong capabilities in conducting fluent, multi-turn conversations with users, Large Language Models (LLMs) have the potential to further improve the performance of Conversational Recommender System (CRS). Unlike the aimless chit-chat that LLM excels at, CRS has a clear target. So it is imperative to control the dialogue flow in the LLM to successfully recommend appropriate items to the users. Furthermore, user feedback in CRS can assist the system in better modeling user preferences, which has been ignored by existing studies. However, simply prompting LLM to conduct conversational recommendation cannot address the above two key challenges.   In this paper, we propose Multi-Agent Conversational Recommender System (MACRS) which contains two essential modules. First, we design a multi-agent act planning framework, which can control the dialogue flow based on four LLM-based agents. This cooperative multi-agent framework will generate various candidate responses based on different dialogue acts and then choose the most appropriate response as the system response, which can help MACRS plan suitable dialogue acts. Second, we propose a user feedback-aware reflection mechanism which leverages user feedback to reason errors made in previous turns to adjust the dialogue act planning, and higher-level user information from implicit semantics. We conduct extensive experiments based on user simulator to demonstrate the effectiveness of MACRS in recommendation and user preferences collection. Experimental results illustrate that MACRS demonstrates an improvement in user interaction experience compared to directly using LLMs.

{{</citation>}}


### (54/175) TransFR: Transferable Federated Recommendation with Pre-trained Language Models (Honglei Zhang et al., 2024)

{{<citation>}}

Honglei Zhang, He Liu, Haoxuan Li, Yidong Li. (2024)  
**TransFR: Transferable Federated Recommendation with Pre-trained Language Models**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01124v1)  

---


**ABSTRACT**  
Federated recommendations (FRs), facilitating multiple local clients to collectively learn a global model without disclosing user private data, have emerged as a prevalent architecture for privacy-preserving recommendations. In conventional FRs, a dominant paradigm is to utilize discrete identities to represent users/clients and items, which are subsequently mapped to domain-specific embeddings to participate in model training. Despite considerable performance, we reveal three inherent limitations that can not be ignored in federated settings, i.e., non-transferability across domains, unavailability in cold-start settings, and potential privacy violations during federated training. To this end, we propose a transferable federated recommendation model with universal textual representations, TransFR, which delicately incorporates the general capabilities empowered by pre-trained language models and the personalized abilities by fine-tuning local private data. Specifically, it first learns domain-agnostic representations of items by exploiting pre-trained models with public textual corpora. To tailor for federated recommendation, we further introduce an efficient federated fine-tuning and a local training mechanism. This facilitates personalized local heads for each client by utilizing their private behavior data. By incorporating pre-training and fine-tuning within FRs, it greatly improves the adaptation efficiency transferring to a new domain and the generalization capacity to address cold-start issues. Through extensive experiments on several datasets, we demonstrate that our TransFR model surpasses several state-of-the-art FRs in terms of accuracy, transferability, and privacy.

{{</citation>}}


## cs.LG (49)



### (55/175) Digits micro-model for accurate and secure transactions (Chirag Chhablani et al., 2024)

{{<citation>}}

Chirag Chhablani, Nikhita Sharma, Jordan Hosier, Vijay K. Gurbani. (2024)  
**Digits micro-model for accurate and secure transactions**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs-SD, cs.LG, eess-AS  
Keywords: AI, Amazon, Google, Speech Recognition  
[Paper Link](http://arxiv.org/abs/2402.01931v1)  

---


**ABSTRACT**  
Automatic Speech Recognition (ASR) systems are used in the financial domain to enhance the caller experience by enabling natural language understanding and facilitating efficient and intuitive interactions. Increasing use of ASR systems requires that such systems exhibit very low error rates. The predominant ASR models to collect numeric data are large, general-purpose commercial models -- Google Speech-to-text (STT), or Amazon Transcribe -- or open source (OpenAI's Whisper). Such ASR models are trained on hundreds of thousands of hours of audio data and require considerable resources to run. Despite recent progress large speech recognition models, we highlight the potential of smaller, specialized "micro" models. Such light models can be trained perform well on number recognition specific tasks, competing with general models like Whisper or Google STT while using less than 80 minutes of training time and occupying at least an order of less memory resources. Also, unlike larger speech recognition models, micro-models are trained on carefully selected and curated datasets, which makes them highly accurate, agile, and easy to retrain, while using low compute resources. We present our work on creating micro models for multi-digit number recognition that handle diverse speaking styles reflecting real-world pronunciation patterns. Our work contributes to domain-specific ASR models, improving digit recognition accuracy, and privacy of data. An added advantage, their low resource consumption allows them to be hosted on-premise, keeping private data local instead uploading to an external cloud. Our results indicate that our micro-model makes less errors than the best-of-breed commercial or open-source ASRs in recognizing digits (1.8% error rate of our best micro-model versus 5.8% error rate of Whisper), and has a low memory footprint (0.66 GB VRAM for our model versus 11 GB VRAM for Whisper).

{{</citation>}}


### (56/175) From PEFT to DEFT: Parameter Efficient Finetuning for Reducing Activation Density in Transformers (Bharat Runwal et al., 2024)

{{<citation>}}

Bharat Runwal, Tejaswini Pedapati, Pin-Yu Chen. (2024)  
**From PEFT to DEFT: Parameter Efficient Finetuning for Reducing Activation Density in Transformers**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: BERT, GLUE, Language Model, Pretrained Language Models, QA, T5, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2402.01911v1)  

---


**ABSTRACT**  
Pretrained Language Models (PLMs) have become the de facto starting point for fine-tuning on downstream tasks. However, as model sizes continue to increase, traditional fine-tuning of all parameters becomes challenging. To address this, parameter-efficient fine-tuning (PEFT) methods have gained popularity as a means to adapt PLMs effectively. In parallel, recent studies have revealed the presence of activation sparsity within the intermediate outputs of the multilayer perception (MLP) blocks in transformers. Low activation density enables efficient model inference on sparsity-aware hardware. Building upon this insight, in this work, we propose a novel density loss that encourages higher activation sparsity (equivalently, lower activation density) in the pre-trained models. We demonstrate the effectiveness of our approach by utilizing mainstream PEFT techniques including QLoRA, LoRA, Adapter, Prompt/Prefix Tuning to facilitate efficient model adaptation across diverse downstream tasks. Experiments show that our proposed method DEFT, Density-Efficient Fine-Tuning, can reduce the activation density consistently and up to $\boldsymbol{50.72\%}$ on RoBERTa$_\mathrm{Large}$, and $\boldsymbol {53.19\%}$ (encoder density) and $\boldsymbol{90.60\%}$ (decoder density) on Flan-T5$_\mathrm{XXL}$ ($\boldsymbol{11B}$) compared to PEFT using GLUE and QA (SQuAD) benchmarks respectively while maintaining competitive performance on downstream tasks. We also showcase that DEFT works complementary with quantized and pruned models

{{</citation>}}


### (57/175) On Catastrophic Inheritance of Large Foundation Models (Hao Chen et al., 2024)

{{<citation>}}

Hao Chen, Bhiksha Raj, Xing Xie, Jindong Wang. (2024)  
**On Catastrophic Inheritance of Large Foundation Models**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CY, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01909v1)  

---


**ABSTRACT**  
Large foundation models (LFMs) are claiming incredible performances. Yet great concerns have been raised about their mythic and uninterpreted potentials not only in machine learning, but also in various other disciplines. In this position paper, we propose to identify a neglected issue deeply rooted in LFMs: Catastrophic Inheritance, describing the weaknesses and limitations inherited from biased large-scale pre-training data to behaviors of LFMs on the downstream tasks, including samples that are corrupted, long-tailed, noisy, out-of-distributed, to name a few. Such inheritance can potentially cause catastrophes to downstream applications, such as bias, lack of generalization, deteriorated performance, security vulnerability, privacy leakage, and value misalignment. We discuss the challenges behind this issue and propose UIM, a framework to Understand the catastrophic inheritance of LFMs from both pre-training and downstream adaptation, Interpret the implications of catastrophic inheritance on downstream tasks, and how to Mitigate it. UIM aims to unite both the machine learning and social sciences communities for more responsible and promising AI development and deployment.

{{</citation>}}


### (58/175) EBV: Electronic Bee-Veterinarian for Principled Mining and Forecasting of Honeybee Time Series (Mst. Shamima Hossain et al., 2024)

{{<citation>}}

Mst. Shamima Hossain, Christos Faloutsos, Boris Baer, Hyoseung Kim, Vassilis J. Tsotras. (2024)  
**EBV: Electronic Bee-Veterinarian for Principled Mining and Forecasting of Honeybee Time Series**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2402.01902v1)  

---


**ABSTRACT**  
Honeybees are vital for pollination and food production. Among many factors, extreme temperature (e.g., due to climate change) is particularly dangerous for bee health. Anticipating such extremities would allow beekeepers to take early preventive action. Thus, given sensor (temperature) time series data from beehives, how can we find patterns and do forecasting? Forecasting is crucial as it helps spot unexpected behavior and thus issue warnings to the beekeepers. In that case, what are the right models for forecasting? ARIMA, RNNs, or something else?   We propose the EBV (Electronic Bee-Veterinarian) method, which has the following desirable properties: (i) principled: it is based on a) diffusion equations from physics and b) control theory for feedback-loop controllers; (ii) effective: it works well on multiple, real-world time sequences, (iii) explainable: it needs only a handful of parameters (e.g., bee strength) that beekeepers can easily understand and trust, and (iv) scalable: it performs linearly in time. We applied our method to multiple real-world time sequences, and found that it yields accurate forecasting (up to 49% improvement in RMSE compared to baselines), and segmentation. Specifically, discontinuities detected by EBV mostly coincide with domain expert's opinions, showcasing our approach's potential and practical feasibility. Moreover, EBV is scalable and fast, taking about 20 minutes on a stock laptop for reconstructing two months of sensor data.

{{</citation>}}


### (59/175) Inverse Reinforcement Learning by Estimating Expertise of Demonstrators (Mark Beliaev et al., 2024)

{{<citation>}}

Mark Beliaev, Ramtin Pedarsani. (2024)  
**Inverse Reinforcement Learning by Estimating Expertise of Demonstrators**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01886v1)  

---


**ABSTRACT**  
In Imitation Learning (IL), utilizing suboptimal and heterogeneous demonstrations presents a substantial challenge due to the varied nature of real-world data. However, standard IL algorithms consider these datasets as homogeneous, thereby inheriting the deficiencies of suboptimal demonstrators. Previous approaches to this issue typically rely on impractical assumptions like high-quality data subsets, confidence rankings, or explicit environmental knowledge. This paper introduces IRLEED, Inverse Reinforcement Learning by Estimating Expertise of Demonstrators, a novel framework that overcomes these hurdles without prior knowledge of demonstrator expertise. IRLEED enhances existing Inverse Reinforcement Learning (IRL) algorithms by combining a general model for demonstrator suboptimality to address reward bias and action variance, with a Maximum Entropy IRL framework to efficiently derive the optimal policy from diverse, suboptimal demonstrations. Experiments in both online and offline IL settings, with simulated and human-generated data, demonstrate IRLEED's adaptability and effectiveness, making it a versatile solution for learning from suboptimal demonstrations.

{{</citation>}}


### (60/175) Large Language Model Agent for Hyper-Parameter Optimization (Siyi Liu et al., 2024)

{{<citation>}}

Siyi Liu, Chen Gao, Yong Li. (2024)  
**Large Language Model Agent for Hyper-Parameter Optimization**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01881v2)  

---


**ABSTRACT**  
Hyperparameter optimization is critical in modern machine learning, requiring expert knowledge, numerous trials, and high computational and human resources. Despite the advancements in Automated Machine Learning (AutoML), challenges in terms of trial efficiency, setup complexity, and interoperability still persist. To address these issues, we introduce a novel paradigm leveraging Large Language Models (LLMs) to automate hyperparameter optimization across diverse machine learning tasks, which is named AgentHPO (short for LLM Agent-based Hyperparameter Optimization). Specifically, AgentHPO processes the task information autonomously, conducts experiments with specific hyperparameters (HPs), and iteratively optimizes them based on historical trials. This human-like optimization process largely reduces the number of required trials, simplifies the setup process, and enhances interpretability and user trust, compared to traditional AutoML methods. Extensive empirical experiments conducted on 12 representative machine-learning tasks indicate that AgentHPO not only matches but also often surpasses the best human trials in terms of performance while simultaneously providing explainable results. Further analysis sheds light on the strategies employed by the LLM in optimizing these tasks, highlighting its effectiveness and adaptability in various scenarios.

{{</citation>}}


### (61/175) $σ$-zero: Gradient-based Optimization of $\ell_0$-norm Adversarial Examples (Antonio Emanuele Cinà et al., 2024)

{{<citation>}}

Antonio Emanuele Cinà, Francesco Villani, Maura Pintor, Lea Schönherr, Battista Biggio, Marcello Pelillo. (2024)  
**$σ$-zero: Gradient-based Optimization of $\ell_0$-norm Adversarial Examples**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-CV, cs-LG, cs.LG  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2402.01879v1)  

---


**ABSTRACT**  
Evaluating the adversarial robustness of deep networks to gradient-based attacks is challenging. While most attacks consider $\ell_2$- and $\ell_\infty$-norm constraints to craft input perturbations, only a few investigate sparse $\ell_1$- and $\ell_0$-norm attacks. In particular, $\ell_0$-norm attacks remain the least studied due to the inherent complexity of optimizing over a non-convex and non-differentiable constraint. However, evaluating adversarial robustness under these attacks could reveal weaknesses otherwise left untested with more conventional $\ell_2$- and $\ell_\infty$-norm attacks. In this work, we propose a novel $\ell_0$-norm attack, called $\sigma$-zero, which leverages an ad hoc differentiable approximation of the $\ell_0$ norm to facilitate gradient-based optimization, and an adaptive projection operator to dynamically adjust the trade-off between loss minimization and perturbation sparsity. Extensive evaluations using MNIST, CIFAR10, and ImageNet datasets, involving robust and non-robust models, show that $\sigma$-zero finds minimum $\ell_0$-norm adversarial examples without requiring any time-consuming hyperparameter tuning, and that it outperforms all competing sparse attacks in terms of success rate, perturbation size, and scalability.

{{</citation>}}


### (62/175) APIServe: Efficient API Support for Large-Language Model Inferencing (Reyna Abhyankar et al., 2024)

{{<citation>}}

Reyna Abhyankar, Zijian He, Vikranth Srivatsa, Hao Zhang, Yiying Zhang. (2024)  
**APIServe: Efficient API Support for Large-Language Model Inferencing**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-DC, cs-LG, cs.LG  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01869v1)  

---


**ABSTRACT**  
Large language models are increasingly integrated with external tools and APIs like ChatGPT plugins to extend their capability beyond language-centric tasks. However, today's LLM inference systems are designed for standalone LLMs. They treat API calls as new requests, causing unnecessary recomputation of already computed contexts, which accounts for 37-40% of total model forwarding time. This paper presents APIServe, the first LLM inference framework targeting API-augmented LLMs. APISERVE minimizes the GPU resource waste caused by API calls and dedicates saved memory for serving more requests. APISERVE improves the overall serving throughput by 1.6x and completes 2x more requests per second compared to the state-of-the-art LLM inference systems.

{{</citation>}}


### (63/175) Leveraging Large Language Models for Structure Learning in Prompted Weak Supervision (Jinyan Su et al., 2024)

{{<citation>}}

Jinyan Su, Peilin Yu, Jieyu Zhang, Stephen H. Bach. (2024)  
**Leveraging Large Language Models for Structure Learning in Prompted Weak Supervision**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01867v1)  

---


**ABSTRACT**  
Prompted weak supervision (PromptedWS) applies pre-trained large language models (LLMs) as the basis for labeling functions (LFs) in a weak supervision framework to obtain large labeled datasets. We further extend the use of LLMs in the loop to address one of the key challenges in weak supervision: learning the statistical dependency structure among supervision sources. In this work, we ask the LLM how similar are these prompted LFs. We propose a Structure Refining Module, a simple yet effective first approach based on the similarities of the prompts by taking advantage of the intrinsic structure in the embedding space. At the core of Structure Refining Module are Labeling Function Removal (LaRe) and Correlation Structure Generation (CosGen). Compared to previous methods that learn the dependencies from weak labels, our method finds the dependencies which are intrinsic to the LFs and less dependent on the data. We show that our Structure Refining Module improves the PromptedWS pipeline by up to 12.7 points on the benchmark tasks. We also explore the trade-offs between efficiency and performance with comprehensive ablation experiments and analysis. Code for this project can be found in https://github.com/BatsResearch/su-bigdata23-code.

{{</citation>}}


### (64/175) What Will My Model Forget? Forecasting Forgotten Examples in Language Model Refinement (Xisen Jin et al., 2024)

{{<citation>}}

Xisen Jin, Xiang Ren. (2024)  
**What Will My Model Forget? Forecasting Forgotten Examples in Language Model Refinement**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG, stat-ML  
Keywords: Language Model, T5  
[Paper Link](http://arxiv.org/abs/2402.01865v1)  

---


**ABSTRACT**  
Language models deployed in the wild make errors. However, simply updating the model with the corrected error instances causes catastrophic forgetting -- the updated model makes errors on instances learned during the instruction tuning or upstream training phase. Randomly replaying upstream data yields unsatisfactory performance and often comes with high variance and poor controllability. To this end, we try to forecast upstream examples that will be forgotten due to a model update for improved controllability of the replay process and interpretability. We train forecasting models given a collection of online learned examples and corresponding forgotten upstream pre-training examples. We propose a partially interpretable forecasting model based on the observation that changes in pre-softmax logit scores of pretraining examples resemble that of online learned examples, which performs decently on BART but fails on T5 models. We further show a black-box classifier based on inner products of example representations achieves better forecasting performance over a series of setups. Finally, we show that we reduce forgetting of upstream pretraining examples by replaying examples that are forecasted to be forgotten, demonstrating the practical utility of forecasting example forgetting.

{{</citation>}}


### (65/175) L2G2G: a Scalable Local-to-Global Network Embedding with Graph Autoencoders (Ruikang Ouyang et al., 2024)

{{<citation>}}

Ruikang Ouyang, Andrew Elliott, Stratis Limnios, Mihai Cucuringu, Gesine Reinert. (2024)  
**L2G2G: a Scalable Local-to-Global Network Embedding with Graph Autoencoders**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SI, cs.LG, stat-ML  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2402.01614v1)  

---


**ABSTRACT**  
For analysing real-world networks, graph representation learning is a popular tool. These methods, such as a graph autoencoder (GAE), typically rely on low-dimensional representations, also called embeddings, which are obtained through minimising a loss function; these embeddings are used with a decoder for downstream tasks such as node classification and edge prediction. While GAEs tend to be fairly accurate, they suffer from scalability issues. For improved speed, a Local2Global approach, which combines graph patch embeddings based on eigenvector synchronisation, was shown to be fast and achieve good accuracy. Here we propose L2G2G, a Local2Global method which improves GAE accuracy without sacrificing scalability. This improvement is achieved by dynamically synchronising the latent node representations, while training the GAEs. It also benefits from the decoder computing an only local patch loss. Hence, aligning the local embeddings in each epoch utilises more information from the graph than a single post-training alignment does, while maintaining scalability. We illustrate on synthetic benchmarks, as well as real-world examples, that L2G2G achieves higher accuracy than the standard Local2Global approach and scales efficiently on the larger data sets. We find that for large and dense networks, it even outperforms the slow, but assumed more accurate, GAEs.

{{</citation>}}


### (66/175) Decoding Speculative Decoding (Minghao Yan et al., 2024)

{{<citation>}}

Minghao Yan, Saurabh Agarwal, Shivaram Venkataraman. (2024)  
**Decoding Speculative Decoding**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: LLaMA, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01528v1)  

---


**ABSTRACT**  
Speculative Decoding is a widely used technique to speed up inference for Large Language Models (LLMs) without modifying its outcome. When performing inference on an LLM, speculative decoding uses a smaller draft model which generates speculative tokens and then uses the target LLM to verify those draft tokens. The speedup provided by speculative decoding heavily depends on the choice of the draft model. It has been widely suggested to select a draft model that provides a high probability of the generated token being accepted by the LLM to achieve the highest throughput. However, our experiments indicate the contrary with throughput diminishing as the probability of generated tokens to be accepted by the target model increases. To understand this phenomenon, we perform extensive experiments to characterize the different factors that affect speculative decoding and how those factors interact and affect the speedups. Based on our experiments we describe an analytical model which can be used to decide the right draft model for a given workload. Further, using our insights we design a new draft model for LLaMA-65B which can provide 30% higher throughput than existing draft models.

{{</citation>}}


### (67/175) Self-Attention through Kernel-Eigen Pair Sparse Variational Gaussian Processes (Yingyi Chen et al., 2024)

{{<citation>}}

Yingyi Chen, Qinghua Tao, Francesco Tonin, Johan A. K. Suykens. (2024)  
**Self-Attention through Kernel-Eigen Pair Sparse Variational Gaussian Processes**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs.LG, stat-ML  
Keywords: Attention, Self-Attention, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2402.01476v1)  

---


**ABSTRACT**  
While the great capability of Transformers significantly boosts prediction accuracy, it could also yield overconfident predictions and require calibrated uncertainty estimation, which can be commonly tackled by Gaussian processes (GPs). Existing works apply GPs with symmetric kernels under variational inference to the attention kernel; however, omitting the fact that attention kernels are in essence asymmetric. Moreover, the complexity of deriving the GP posteriors remains high for large-scale data. In this work, we propose Kernel-Eigen Pair Sparse Variational Gaussian Processes (KEP-SVGP) for building uncertainty-aware self-attention where the asymmetry of attention kernels is tackled by Kernel SVD (KSVD) and a reduced complexity is acquired. Through KEP-SVGP, i) the SVGP pair induced by the two sets of singular vectors from KSVD w.r.t. the attention kernel fully characterizes the asymmetry; ii) using only a small set of adjoint eigenfunctions from KSVD, the derivation of SVGP posteriors can be based on the inversion of a diagonal matrix containing singular values, contributing to a reduction in time complexity; iii) an evidence lower bound is derived so that variational parameters can be optimized towards this objective. Experiments verify our excellent performances and efficiency on in-distribution, distribution-shift and out-of-distribution benchmarks.

{{</citation>}}


### (68/175) Integrating Large Language Models in Causal Discovery: A Statistical Causal Approach (Masayuki Takayama et al., 2024)

{{<citation>}}

Masayuki Takayama, Tadahisa Okuda, Thong Pham, Tatsuyoshi Ikenoue, Shingo Fukuma, Shohei Shimizu, Akiyoshi Sannai. (2024)  
**Integrating Large Language Models in Causal Discovery: A Statistical Causal Approach**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ME, stat-ML  
Keywords: GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01454v1)  

---


**ABSTRACT**  
In practical statistical causal discovery (SCD), embedding domain expert knowledge as constraints into the algorithm is widely accepted as significant for creating consistent meaningful causal models, despite the recognized challenges in systematic acquisition of the background knowledge. To overcome these challenges, this paper proposes a novel methodology for causal inference, in which SCD methods and knowledge based causal inference (KBCI) with a large language model (LLM) are synthesized through "statistical causal prompting (SCP)" for LLMs and prior knowledge augmentation for SCD. Experiments have revealed that GPT-4 can cause the output of the LLM-KBCI and the SCD result with prior knowledge from LLM-KBCI to approach the ground truth, and that the SCD result can be further improved, if GPT-4 undergoes SCP. Furthermore, it has been clarified that an LLM can improve SCD with its background knowledge, even if the LLM does not contain information on the dataset. The proposed approach can thus address challenges such as dataset biases and limitations, illustrating the potential of LLMs to improve data-driven causal inference across diverse scientific domains.

{{</citation>}}


### (69/175) Few-Shot Learning on Graphs: from Meta-learning to Pre-training and Prompting (Xingtong Yu et al., 2024)

{{<citation>}}

Xingtong Yu, Yuan Fang, Zemin Liu, Yuxia Wu, Zhihao Wen, Jianyuan Bo, Xinming Zhang, Steven C. H. Hoi. (2024)  
**Few-Shot Learning on Graphs: from Meta-learning to Pre-training and Prompting**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SI, cs.LG  
Keywords: Few-Shot  
[Paper Link](http://arxiv.org/abs/2402.01440v1)  

---


**ABSTRACT**  
Graph representation learning, a critical step in graph-centric tasks, has seen significant advancements. Earlier techniques often operate in an end-to-end setting, where performance heavily relies on the availability of ample labeled data. This constraint has spurred the emergence of few-shot learning on graphs, where only a few task-specific labels are available for each task. Given the extensive literature in this field, this survey endeavors to synthesize recent developments, provide comparative insights, and identify future directions. We systematically categorize existing studies into three major families: meta-learning approaches, pre-training approaches, and hybrid approaches, with a finer-grained classification in each family to aid readers in their method selection process. Within each category, we analyze the relationships among these methods and compare their strengths and limitations. Finally, we outline prospective future directions for few-shot learning on graphs to catalyze continued innovation in this field.

{{</citation>}}


### (70/175) From Words to Molecules: A Survey of Large Language Models in Chemistry (Chang Liao et al., 2024)

{{<citation>}}

Chang Liao, Yemin Yu, Yu Mei, Ying Wei. (2024)  
**From Words to Molecules: A Survey of Large Language Models in Chemistry**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, q-bio-BM, q-bio-QM  
Keywords: Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2402.01439v1)  

---


**ABSTRACT**  
In recent years, Large Language Models (LLMs) have achieved significant success in natural language processing (NLP) and various interdisciplinary areas. However, applying LLMs to chemistry is a complex task that requires specialized domain knowledge. This paper provides a thorough exploration of the nuanced methodologies employed in integrating LLMs into the field of chemistry, delving into the complexities and innovations at this interdisciplinary juncture. Specifically, our analysis begins with examining how molecular information is fed into LLMs through various representation and tokenization methods. We then categorize chemical LLMs into three distinct groups based on the domain and modality of their input data, and discuss approaches for integrating these inputs for LLMs. Furthermore, this paper delves into the pretraining objectives with adaptations to chemical LLMs. After that, we explore the diverse applications of LLMs in chemistry, including novel paradigms for their application in chemistry tasks. Finally, we identify promising research directions, including further integration with chemical knowledge, advancements in continual learning, and improvements in model interpretability, paving the way for groundbreaking developments in the field.

{{</citation>}}


### (71/175) Climbing the Ladder of Interpretability with Counterfactual Concept Bottleneck Models (Gabriele Dominici et al., 2024)

{{<citation>}}

Gabriele Dominici, Pietro Barbiero, Francesco Giannini, Martin Gjoreski, Giuseppe Marra, Marc Langheinrich. (2024)  
**Climbing the Ladder of Interpretability with Counterfactual Concept Bottleneck Models**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01408v1)  

---


**ABSTRACT**  
Current deep learning models are not designed to simultaneously address three fundamental questions: predict class labels to solve a given classification task (the "What?"), explain task predictions (the "Why?"), and imagine alternative scenarios that could result in different predictions (the "What if?"). The inability to answer these questions represents a crucial gap in deploying reliable AI agents, calibrating human trust, and deepening human-machine interaction. To bridge this gap, we introduce CounterFactual Concept Bottleneck Models (CF-CBMs), a class of models designed to efficiently address the above queries all at once without the need to run post-hoc searches. Our results show that CF-CBMs produce: accurate predictions (the "What?"), simple explanations for task predictions (the "Why?"), and interpretable counterfactuals (the "What if?"). CF-CBMs can also sample or estimate the most probable counterfactual to: (i) explain the effect of concept interventions on tasks, (ii) show users how to get a desired class label, and (iii) propose concept interventions via "task-driven" interventions.

{{</citation>}}


### (72/175) Zero-Shot Machine Unlearning at Scale via Lipschitz Regularization (Jack Foster et al., 2024)

{{<citation>}}

Jack Foster, Kyle Fogarty, Stefan Schoepf, Cengiz Öztireli, Alexandra Brintrup. (2024)  
**Zero-Shot Machine Unlearning at Scale via Lipschitz Regularization**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ML  
Keywords: AI, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2402.01401v2)  

---


**ABSTRACT**  
To comply with AI and data regulations, the need to forget private or copyrighted information from trained machine learning models is increasingly important. The key challenge in unlearning is forgetting the necessary data in a timely manner, while preserving model performance. In this work, we address the zero-shot unlearning scenario, whereby an unlearning algorithm must be able to remove data given only a trained model and the data to be forgotten. Under such a definition, existing state-of-the-art methods are insufficient. Building on the concepts of Lipschitz continuity, we present a method that induces smoothing of the forget sample's output, with respect to perturbations of that sample. We show this smoothing successfully results in forgetting while preserving general model performance. We perform extensive empirical evaluation of our method over a range of contemporary benchmarks, verifying that our method achieves state-of-the-art performance under the strict constraints of zero-shot unlearning.

{{</citation>}}


### (73/175) A Probabilistic Model to explain Self-Supervised Representation Learning (Alice Bizeul et al., 2024)

{{<citation>}}

Alice Bizeul, Bernhard Schölkopf, Carl Allen. (2024)  
**A Probabilistic Model to explain Self-Supervised Representation Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ML  
Keywords: Representation Learning, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2402.01399v1)  

---


**ABSTRACT**  
Self-supervised learning (SSL) learns representations by leveraging an auxiliary unsupervised task, such as classifying semantically related samples, e.g. different data augmentations or modalities. Of the many approaches to SSL, contrastive methods, e.g. SimCLR, CLIP and VicREG, have gained attention for learning representations that achieve downstream performance close to that of supervised learning. However, a theoretical understanding of the mechanism behind these methods eludes. We propose a generative latent variable model for the data and show that several families of discriminative self-supervised algorithms, including contrastive methods, approximately induce its latent structure over representations, providing a unifying theoretical framework. We also justify links to mutual information and the use of a projection head. Fitting our model generatively, as SimVE, improves performance over previous VAE methods on common benchmarks (e.g. FashionMNIST, CIFAR10, CelebA), narrows the gap to discriminative methods on _content_ classification and, as our analysis predicts, outperforms them where _style_ information is required, taking a step toward task-agnostic representations.

{{</citation>}}


### (74/175) To the Max: Reinventing Reward in Reinforcement Learning (Grigorii Veviurko et al., 2024)

{{<citation>}}

Grigorii Veviurko, Wendelin Böhmer, Mathijs de Weerdt. (2024)  
**To the Max: Reinventing Reward in Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01361v1)  

---


**ABSTRACT**  
In reinforcement learning (RL), different rewards can define the same optimal policy but result in drastically different learning performance. For some, the agent gets stuck with a suboptimal behavior, and for others, it solves the task efficiently. Choosing a good reward function is hence an extremely important yet challenging problem. In this paper, we explore an alternative approach to using rewards for learning. We introduce max-reward RL, where an agent optimizes the maximum rather than the cumulative reward. Unlike earlier works, our approach works for deterministic and stochastic environments and can be easily combined with state-of-the-art RL algorithms. In the experiments, we study the performance of max-reward RL algorithms in two goal-reaching environments from Gymnasium-Robotics and demonstrate its benefits over standard RL. The code is publicly available.

{{</citation>}}


### (75/175) TESSERACT: Eliminating Experimental Bias in Malware Classification across Space and Time (Extended Version) (Zeliang Kan et al., 2024)

{{<citation>}}

Zeliang Kan, Shae McFadden, Daniel Arp, Feargus Pendlebury, Roberto Jordaney, Johannes Kinder, Fabio Pierazzi, Lorenzo Cavallaro. (2024)  
**TESSERACT: Eliminating Experimental Bias in Malware Classification across Space and Time (Extended Version)**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs-PF, cs.LG  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2402.01359v1)  

---


**ABSTRACT**  
Machine learning (ML) plays a pivotal role in detecting malicious software. Despite the high F1-scores reported in numerous studies reaching upwards of 0.99, the issue is not completely solved. Malware detectors often experience performance decay due to constantly evolving operating systems and attack methods, which can render previously learned knowledge insufficient for accurate decision-making on new inputs. This paper argues that commonly reported results are inflated due to two pervasive sources of experimental bias in the detection task: spatial bias caused by data distributions that are not representative of a real-world deployment; and temporal bias caused by incorrect time splits of data, leading to unrealistic configurations. To address these biases, we introduce a set of constraints for fair experiment design, and propose a new metric, AUT, for classifier robustness in real-world settings. We additionally propose an algorithm designed to tune training data to enhance classifier performance. Finally, we present TESSERACT, an open-source framework for realistic classifier comparison. Our evaluation encompasses both traditional ML and deep learning methods, examining published works on an extensive Android dataset with 259,230 samples over a five-year span. Additionally, we conduct case studies in the Windows PE and PDF domains. Our findings identify the existence of biases in previous studies and reveal that significant performance enhancements are possible through appropriate, periodic tuning. We explore how mitigation strategies may support in achieving a more stable and better performance over time by employing multiple strategies to delay performance decay.

{{</citation>}}


### (76/175) Preference-free Alignment Learning with Regularized Relevance Reward (Sungdong Kim et al., 2024)

{{<citation>}}

Sungdong Kim, Minjoon Seo. (2024)  
**Preference-free Alignment Learning with Regularized Relevance Reward**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.03469v1)  

---


**ABSTRACT**  
Learning from human preference has been considered key to aligning Large Language Models (LLMs) with human values. However, contrary to popular belief, our preliminary study reveals that reward models trained on human preference datasets tend to give higher scores to long off-topic responses than short on-topic ones. Motivated by this observation, we explore a preference-free approach utilizing `relevance' as a key objective for alignment. On our first attempt, we find that the relevance score obtained by a retriever alone is vulnerable to reward hacking, i.e., overoptimizing to undesired shortcuts, when we utilize the score as a reward for reinforcement learning. To mitigate it, we integrate effective inductive biases into the vanilla relevance to regularize each other, resulting in a mixture of reward functions: Regularized Relevance Reward ($R^3$). $R^3$ significantly improves performance on preference benchmarks by providing a robust reward signal. Notably, $R^3$ does not require any human preference datasets (i.e., preference-free), outperforming open-source reward models in improving human preference. Our analysis demonstrates that $R^3$ has advantages in elevating human preference while minimizing its side effects. Finally, we show the generalizability of $R^3$, consistently improving instruction-tuned models in various backbones and sizes without additional dataset cost. Our code is available at https://github.com/naver-ai/RRR.

{{</citation>}}


### (77/175) Shapelet-based Model-agnostic Counterfactual Local Explanations for Time Series Classification (Qi Huang et al., 2024)

{{<citation>}}

Qi Huang, Wei Chen, Thomas Bäck, Niki van Stein. (2024)  
**Shapelet-based Model-agnostic Counterfactual Local Explanations for Time Series Classification**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2402.01343v1)  

---


**ABSTRACT**  
In this work, we propose a model-agnostic instance-based post-hoc explainability method for time series classification. The proposed algorithm, namely Time-CF, leverages shapelets and TimeGAN to provide counterfactual explanations for arbitrary time series classifiers. We validate the proposed method on several real-world univariate time series classification tasks from the UCR Time Series Archive. The results indicate that the counterfactual instances generated by Time-CF when compared to state-of-the-art methods, demonstrate better performance in terms of four explainability metrics: closeness, sensibility, plausibility, and sparsity.

{{</citation>}}


### (78/175) SignSGD with Federated Defense: Harnessing Adversarial Attacks through Gradient Sign Decoding (Chanho Park et al., 2024)

{{<citation>}}

Chanho Park, Namyoon Lee. (2024)  
**SignSGD with Federated Defense: Harnessing Adversarial Attacks through Gradient Sign Decoding**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs.LG, eess-SP  
Keywords: Adversarial Attack  
[Paper Link](http://arxiv.org/abs/2402.01340v1)  

---


**ABSTRACT**  
Distributed learning is an effective approach to accelerate model training using multiple workers. However, substantial communication delays emerge between workers and a parameter server due to massive costs associated with communicating gradients. SignSGD with majority voting (signSGD-MV) is a simple yet effective optimizer that reduces communication costs through one-bit quantization, yet the convergence rates considerably decrease as adversarial workers increase. In this paper, we show that the convergence rate is invariant as the number of adversarial workers increases, provided that the number of adversarial workers is smaller than that of benign workers. The key idea showing this counter-intuitive result is our novel signSGD with federated defense (signSGD-FD). Unlike the traditional approaches, signSGD-FD exploits the gradient information sent by adversarial workers with the proper weights, which are obtained through gradient sign decoding. Experimental results demonstrate signSGD-FD achieves superior convergence rates over traditional algorithms in various adversarial attack scenarios.

{{</citation>}}


### (79/175) Can MLLMs Perform Text-to-Image In-Context Learning? (Yuchen Zeng et al., 2024)

{{<citation>}}

Yuchen Zeng, Wonjun Kang, Yicong Chen, Hyung Il Koo, Kangwook Lee. (2024)  
**Can MLLMs Perform Text-to-Image In-Context Learning?**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01293v1)  

---


**ABSTRACT**  
The evolution from Large Language Models (LLMs) to Multimodal Large Language Models (MLLMs) has spurred research into extending In-Context Learning (ICL) to its multimodal counterpart. Existing such studies have primarily concentrated on image-to-text ICL. However, the Text-to-Image ICL (T2I-ICL), with its unique characteristics and potential applications, remains underexplored. To address this gap, we formally define the task of T2I-ICL and present CoBSAT, the first T2I-ICL benchmark dataset, encompassing ten tasks. Utilizing our dataset to benchmark six state-of-the-art MLLMs, we uncover considerable difficulties MLLMs encounter in solving T2I-ICL. We identify the primary challenges as the inherent complexity of multimodality and image generation. To overcome these challenges, we explore strategies like fine-tuning and Chain-of-Thought prompting, demonstrating notable improvements. Our code and dataset are available at \url{https://github.com/UW-Madison-Lee-Lab/CoBSAT}.

{{</citation>}}


### (80/175) A Differentiable Partially Observable Generalized Linear Model with Forward-Backward Message Passing (Chengrui Li et al., 2024)

{{<citation>}}

Chengrui Li, Weihan Li, Yule Wang, Anqi Wu. (2024)  
**A Differentiable Partially Observable Generalized Linear Model with Forward-Backward Message Passing**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, q-bio-NC  
Keywords: GLM  
[Paper Link](http://arxiv.org/abs/2402.01263v2)  

---


**ABSTRACT**  
The partially observable generalized linear model (POGLM) is a powerful tool for understanding neural connectivity under the assumption of existing hidden neurons. With spike trains only recorded from visible neurons, existing works use variational inference to learn POGLM meanwhile presenting the difficulty of learning this latent variable model. There are two main issues: (1) the sampled Poisson hidden spike count hinders the use of the pathwise gradient estimator in VI; and (2) the existing design of the variational model is neither expressive nor time-efficient, which further affects the performance. For (1), we propose a new differentiable POGLM, which enables the pathwise gradient estimator, better than the score function gradient estimator used in existing works. For (2), we propose the forward-backward message-passing sampling scheme for the variational model. Comprehensive experiments show that our differentiable POGLMs with our forward-backward message passing produce a better performance on one synthetic and two real-world datasets. Furthermore, our new method yields more interpretable parameters, underscoring its significance in neuroscience.

{{</citation>}}


### (81/175) TEDDY: Trimming Edges with Degree-based Discrimination strategY (Hyunjin Seo et al., 2024)

{{<citation>}}

Hyunjin Seo, Jihun Yun, Eunho Yang. (2024)  
**TEDDY: Trimming Edges with Degree-based Discrimination strategY**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2402.01261v1)  

---


**ABSTRACT**  
Since the pioneering work on the lottery ticket hypothesis for graph neural networks (GNNs) was proposed in Chen et al. (2021), the study on finding graph lottery tickets (GLT) has become one of the pivotal focus in the GNN community, inspiring researchers to discover sparser GLT while achieving comparable performance to original dense networks. In parallel, the graph structure has gained substantial attention as a crucial factor in GNN training dynamics, also elucidated by several recent studies. Despite this, contemporary studies on GLT, in general, have not fully exploited inherent pathways in the graph structure and identified tickets in an iterative manner, which is time-consuming and inefficient. To address these limitations, we introduce TEDDY, a one-shot edge sparsification framework that leverages structural information by incorporating edge-degree information. Following edge sparsification, we encourage the parameter sparsity during training via simple projected gradient descent on the $\ell_0$ ball. Given the target sparsity levels for both the graph structure and the model parameters, our TEDDY facilitates efficient and rapid realization of GLT within a single training. Remarkably, our experimental results demonstrate that TEDDY significantly surpasses conventional iterative approaches in generalization, even when conducting one-shot sparsification that solely utilizes graph structures, without taking node features into account.

{{</citation>}}


### (82/175) Two Heads Are Better Than One: Boosting Graph Sparse Training via Semantic and Topological Awareness (Guibin Zhang et al., 2024)

{{<citation>}}

Guibin Zhang, Yanwei Yue, Kun Wang, Junfeng Fang, Yongduo Sui, Kai Wang, Yuxuan Liang, Dawei Cheng, Shirui Pan, Tianlong Chen. (2024)  
**Two Heads Are Better Than One: Boosting Graph Sparse Training via Semantic and Topological Awareness**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2402.01242v1)  

---


**ABSTRACT**  
Graph Neural Networks (GNNs) excel in various graph learning tasks but face computational challenges when applied to large-scale graphs. A promising solution is to remove non-essential edges to reduce the computational overheads in GNN. Previous literature generally falls into two categories: topology-guided and semantic-guided. The former maintains certain graph topological properties yet often underperforms on GNNs due to low integration with neural network training. The latter performs well at lower sparsity on GNNs but faces performance collapse at higher sparsity levels. With this in mind, we take the first step to propose a new research line and concept termed Graph Sparse Training (GST), which dynamically manipulates sparsity at the data level. Specifically, GST initially constructs a topology & semantic anchor at a low training cost, followed by performing dynamic sparse training to align the sparse graph with the anchor. We introduce the Equilibria Sparsification Principle to guide this process, effectively balancing the preservation of both topological and semantic information. Ultimately, GST produces a sparse graph with maximum topological integrity and no performance degradation. Extensive experiments on 6 datasets and 5 backbones showcase that GST (I) identifies subgraphs at higher graph sparsity levels (1.67%~15.85% $\uparrow$) than state-of-the-art sparsification methods, (II) preserves more key spectral properties, (III) achieves 1.27-3.42$\times$ speedup in GNN inference and (IV) successfully helps graph adversarial defense and graph lottery tickets.

{{</citation>}}


### (83/175) Unveiling Delay Effects in Traffic Forecasting: A Perspective from Spatial-Temporal Delay Differential Equations (Qingqing Long et al., 2024)

{{<citation>}}

Qingqing Long, Zheng Fang, Chen Fang, Chong Chen, Pengfei Wang, Yuanchun Zhou. (2024)  
**Unveiling Delay Effects in Traffic Forecasting: A Perspective from Spatial-Temporal Delay Differential Equations**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2402.01231v1)  

---


**ABSTRACT**  
Traffic flow forecasting is a fundamental research issue for transportation planning and management, which serves as a canonical and typical example of spatial-temporal predictions. In recent years, Graph Neural Networks (GNNs) and Recurrent Neural Networks (RNNs) have achieved great success in capturing spatial-temporal correlations for traffic flow forecasting. Yet, two non-ignorable issues haven't been well solved: 1) The message passing in GNNs is immediate, while in reality the spatial message interactions among neighboring nodes can be delayed. The change of traffic flow at one node will take several minutes, i.e., time delay, to influence its connected neighbors. 2) Traffic conditions undergo continuous changes. The prediction frequency for traffic flow forecasting may vary based on specific scenario requirements. Most existing discretized models require retraining for each prediction horizon, restricting their applicability. To tackle the above issues, we propose a neural Spatial-Temporal Delay Differential Equation model, namely STDDE. It includes both delay effects and continuity into a unified delay differential equation framework, which explicitly models the time delay in spatial information propagation. Furthermore, theoretical proofs are provided to show its stability. Then we design a learnable traffic-graph time-delay estimator, which utilizes the continuity of the hidden states to achieve the gradient backward process. Finally, we propose a continuous output module, allowing us to accurately predict traffic flow at various frequencies, which provides more flexibility and adaptability to different scenarios. Extensive experiments show the superiority of the proposed STDDE along with competitive computational efficiency.

{{</citation>}}


### (84/175) Efficient Causal Graph Discovery Using Large Language Models (Thomas Jiralerspong et al., 2024)

{{<citation>}}

Thomas Jiralerspong, Xiaoyin Chen, Yash More, Vedant Shah, Yoshua Bengio. (2024)  
**Efficient Causal Graph Discovery Using Large Language Models**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ME  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01207v2)  

---


**ABSTRACT**  
We propose a novel framework that leverages LLMs for full causal graph discovery. While previous LLM-based methods have used a pairwise query approach, this requires a quadratic number of queries which quickly becomes impractical for larger causal graphs. In contrast, the proposed framework uses a breadth-first search (BFS) approach which allows it to use only a linear number of queries. We also show that the proposed method can easily incorporate observational data when available, to improve performance. In addition to being more time and data-efficient, the proposed framework achieves state-of-the-art results on real-world causal graphs of varying sizes. The results demonstrate the effectiveness and efficiency of the proposed method in discovering causal relationships, showcasing its potential for broad applicability in causal graph discovery tasks across different domains.

{{</citation>}}


### (85/175) A Survey on Self-Supervised Learning for Non-Sequential Tabular Data (Wei-Yao Wang et al., 2024)

{{<citation>}}

Wei-Yao Wang, Wei-Wei Du, Derek Xu, Wei Wang, Wen-Chih Peng. (2024)  
**A Survey on Self-Supervised Learning for Non-Sequential Tabular Data**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2402.01204v2)  

---


**ABSTRACT**  
Self-supervised learning (SSL) has been incorporated into many state-of-the-art models in various domains, where SSL defines pretext tasks based on unlabeled datasets to learn contextualized and robust representations. Recently, SSL has been a new trend in exploring the representation learning capability in the realm of tabular data, which is more challenging due to not having explicit relations for learning descriptive representations. This survey aims to systematically review and summarize the recent progress and challenges of SSL for non-sequential tabular data (SSL4NS-TD). We first present a formal definition of NS-TD and clarify its correlation to related studies. Then, these approaches are categorized into three groups -- predictive learning, contrastive learning, and hybrid learning, with their motivations and strengths of representative methods within each direction. On top of this, application issues of SSL4NS-TD are presented, including automatic data engineering, cross-table transferability, and domain knowledge integration. In addition, we elaborate on existing benchmarks and datasets for NS-TD applications to discuss the performance of existing tabular models. Finally, we discuss the challenges of SSL4NS-TD and provide potential directions for future research. We expect our work to be useful in terms of encouraging more research on lowering the barrier to entry SSL for the tabular domain and improving the foundations for implicit tabular data.

{{</citation>}}


### (86/175) Structured World Modeling via Semantic Vector Quantization (Yi-Fu Wu et al., 2024)

{{<citation>}}

Yi-Fu Wu, Minseung Lee, Sungjin Ahn. (2024)  
**Structured World Modeling via Semantic Vector Quantization**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Quantization  
[Paper Link](http://arxiv.org/abs/2402.01203v1)  

---


**ABSTRACT**  
Neural discrete representations are crucial components of modern neural networks. However, their main limitation is that the primary strategies such as VQ-VAE can only provide representations at the patch level. Therefore, one of the main goals of representation learning, acquiring structured, semantic, and compositional abstractions such as the color and shape of an object, remains elusive. In this paper, we present the first approach to semantic neural discrete representation learning. The proposed model, called Semantic Vector-Quantized Variational Autoencoder (SVQ), leverages recent advances in unsupervised object-centric learning to address this limitation. Specifically, we observe that a simple approach quantizing at the object level poses a significant challenge and propose constructing scene representations hierarchically, from low-level discrete concept schemas to object representations. Additionally, we suggest a novel method for structured semantic world modeling by training a prior over these representations, enabling the ability to generate images by sampling the semantic properties of the objects in the scene. In experiments on various 2D and 3D object-centric datasets, we find that our model achieves superior generation performance compared to non-semantic vector quantization methods such as VQ-VAE and previous object-centric generative models. Furthermore, we find that the semantic discrete representations can solve downstream scene understanding tasks that require reasoning about the properties of different objects in the scene.

{{</citation>}}


### (87/175) Few-Shot Class-Incremental Learning with Prior Knowledge (Wenhao Jiang et al., 2024)

{{<citation>}}

Wenhao Jiang, Duo Li, Menghan Hu, Guangtao Zhai, Xiaokang Yang, Xiao-Ping Zhang. (2024)  
**Few-Shot Class-Incremental Learning with Prior Knowledge**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Few-Shot  
[Paper Link](http://arxiv.org/abs/2402.01201v1)  

---


**ABSTRACT**  
To tackle the issues of catastrophic forgetting and overfitting in few-shot class-incremental learning (FSCIL), previous work has primarily concentrated on preserving the memory of old knowledge during the incremental phase. The role of pre-trained model in shaping the effectiveness of incremental learning is frequently underestimated in these studies. Therefore, to enhance the generalization ability of the pre-trained model, we propose Learning with Prior Knowledge (LwPK) by introducing nearly free prior knowledge from a few unlabeled data of subsequent incremental classes. We cluster unlabeled incremental class samples to produce pseudo-labels, then jointly train these with labeled base class samples, effectively allocating embedding space for both old and new class data. Experimental results indicate that LwPK effectively enhances the model resilience against catastrophic forgetting, with theoretical analysis based on empirical risk minimization and class distance measurement corroborating its operational principles. The source code of LwPK is publicly available at: \url{https://github.com/StevenJ308/LwPK}.

{{</citation>}}


### (88/175) Conditional Normalizing Flows for Active Learning of Coarse-Grained Molecular Representations (Henrik Schopmans et al., 2024)

{{<citation>}}

Henrik Schopmans, Pascal Friederich. (2024)  
**Conditional Normalizing Flows for Active Learning of Coarse-Grained Molecular Representations**  

---
Primary Category: cs.LG  
Categories: I-2-0, cs-AI, cs-LG, cs.LG, physics-chem-ph  
Keywords: Active Learning  
[Paper Link](http://arxiv.org/abs/2402.01195v1)  

---


**ABSTRACT**  
Efficient sampling of the Boltzmann distribution of molecular systems is a long-standing challenge. Recently, instead of generating long molecular dynamics simulations, generative machine learning methods such as normalizing flows have been used to learn the Boltzmann distribution directly, without samples. However, this approach is susceptible to mode collapse and thus often does not explore the full configurational space. In this work, we address this challenge by separating the problem into two levels, the fine-grained and coarse-grained degrees of freedom. A normalizing flow conditioned on the coarse-grained space yields a probabilistic connection between the two levels. To explore the configurational space, we employ coarse-grained simulations with active learning which allows us to update the flow and make all-atom potential energy evaluations only when necessary. Using alanine dipeptide as an example, we show that our methods obtain a speedup to molecular dynamics simulations of approximately 15.9 to 216.2 compared to the speedup of 4.5 of the current state-of-the-art machine learning approach.

{{</citation>}}


### (89/175) Large Language Models for Time Series: A Survey (Xiyuan Zhang et al., 2024)

{{<citation>}}

Xiyuan Zhang, Ranak Roy Chowdhury, Rajesh K. Gupta, Jingbo Shang. (2024)  
**Large Language Models for Time Series: A Survey**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: Language Model, Time Series  
[Paper Link](http://arxiv.org/abs/2402.01801v2)  

---


**ABSTRACT**  
Large Language Models (LLMs) have seen significant use in domains such as natural language processing and computer vision. Going beyond text, image and graphics, LLMs present a significant potential for analysis of time series data, benefiting domains such as climate, IoT, healthcare, traffic, audio and finance. This survey paper provides an in-depth exploration and a detailed taxonomy of the various methodologies employed to harness the power of LLMs for time series analysis. We address the inherent challenge of bridging the gap between LLMs' original text data training and the numerical nature of time series data, and explore strategies for transferring and distilling knowledge from LLMs to numerical time series analysis. We detail various methodologies, including (1) direct prompting of LLMs, (2) time series quantization, (3) alignment techniques, (4) utilization of the vision modality as a bridging mechanism, and (5) the combination of LLMs with tools. Additionally, this survey offers a comprehensive overview of the existing multimodal time series and text datasets and delves into the challenges and future opportunities of this emerging field. We maintain an up-to-date Github repository which includes all the papers and datasets discussed in the survey.

{{</citation>}}


### (90/175) Faster and Lighter LLMs: A Survey on Current Challenges and Way Forward (Arnav Chavan et al., 2024)

{{<citation>}}

Arnav Chavan, Raghav Magazine, Shubham Kushwaha, Mérouane Debbah, Deepak Gupta. (2024)  
**Faster and Lighter LLMs: A Survey on Current Challenges and Way Forward**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: AI, LLaMA  
[Paper Link](http://arxiv.org/abs/2402.01799v1)  

---


**ABSTRACT**  
Despite the impressive performance of LLMs, their widespread adoption faces challenges due to substantial computational and memory requirements during inference. Recent advancements in model compression and system-level optimization methods aim to enhance LLM inference. This survey offers an overview of these methods, emphasizing recent developments. Through experiments on LLaMA(/2)-7B, we evaluate various compression techniques, providing practical insights for efficient LLM deployment in a unified setting. The empirical analysis on LLaMA(/2)-7B highlights the effectiveness of these methods. Drawing from survey insights, we identify current limitations and discuss potential future directions to improve LLM inference efficiency. We release the codebase to reproduce the results presented in this paper at https://github.com/nyunAI/Faster-LLM-Survey

{{</citation>}}


### (91/175) Improved Quantization Strategies for Managing Heavy-tailed Gradients in Distributed Learning (Guangfeng Yan et al., 2024)

{{<citation>}}

Guangfeng Yan, Tan Li, Yuanzhang Xiao, Hanxu Hou, Linqi Song. (2024)  
**Improved Quantization Strategies for Managing Heavy-tailed Gradients in Distributed Learning**  

---
Primary Category: cs.LG  
Categories: cs-DC, cs-LG, cs.LG  
Keywords: Quantization  
[Paper Link](http://arxiv.org/abs/2402.01798v1)  

---


**ABSTRACT**  
Gradient compression has surfaced as a key technique to address the challenge of communication efficiency in distributed learning. In distributed deep learning, however, it is observed that gradient distributions are heavy-tailed, with outliers significantly influencing the design of compression strategies. Existing parameter quantization methods experience performance degradation when this heavy-tailed feature is ignored. In this paper, we introduce a novel compression scheme specifically engineered for heavy-tailed gradients, which effectively combines gradient truncation with quantization. This scheme is adeptly implemented within a communication-limited distributed Stochastic Gradient Descent (SGD) framework. We consider a general family of heavy-tail gradients that follow a power-law distribution, we aim to minimize the error resulting from quantization, thereby determining optimal values for two critical parameters: the truncation threshold and the quantization density. We provide a theoretical analysis on the convergence error bound under both uniform and non-uniform quantization scenarios. Comparative experiments with other benchmarks demonstrate the effectiveness of our proposed method in managing the heavy-tailed gradients in a distributed learning environment.

{{</citation>}}


### (92/175) Truncated Non-Uniform Quantization for Distributed SGD (Guangfeng Yan et al., 2024)

{{<citation>}}

Guangfeng Yan, Tan Li, Yuanzhang Xiao, Congduan Li, Linqi Song. (2024)  
**Truncated Non-Uniform Quantization for Distributed SGD**  

---
Primary Category: cs.LG  
Categories: cs-DC, cs-LG, cs.LG  
Keywords: Quantization  
[Paper Link](http://arxiv.org/abs/2402.01160v1)  

---


**ABSTRACT**  
To address the communication bottleneck challenge in distributed learning, our work introduces a novel two-stage quantization strategy designed to enhance the communication efficiency of distributed Stochastic Gradient Descent (SGD). The proposed method initially employs truncation to mitigate the impact of long-tail noise, followed by a non-uniform quantization of the post-truncation gradients based on their statistical characteristics. We provide a comprehensive convergence analysis of the quantized distributed SGD, establishing theoretical guarantees for its performance. Furthermore, by minimizing the convergence error, we derive optimal closed-form solutions for the truncation threshold and non-uniform quantization levels under given communication constraints. Both theoretical insights and extensive experimental evaluations demonstrate that our proposed algorithm outperforms existing quantization schemes, striking a superior balance between communication efficiency and convergence performance.

{{</citation>}}


### (93/175) Efficient Reinforcement Learning for Routing Jobs in Heterogeneous Queueing Systems (Neharika Jali et al., 2024)

{{<citation>}}

Neharika Jali, Guannan Qu, Weina Wang, Gauri Joshi. (2024)  
**Efficient Reinforcement Learning for Routing Jobs in Heterogeneous Queueing Systems**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-PF, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01147v1)  

---


**ABSTRACT**  
We consider the problem of efficiently routing jobs that arrive into a central queue to a system of heterogeneous servers. Unlike homogeneous systems, a threshold policy, that routes jobs to the slow server(s) when the queue length exceeds a certain threshold, is known to be optimal for the one-fast-one-slow two-server system. But an optimal policy for the multi-server system is unknown and non-trivial to find. While Reinforcement Learning (RL) has been recognized to have great potential for learning policies in such cases, our problem has an exponentially large state space size, rendering standard RL inefficient. In this work, we propose ACHQ, an efficient policy gradient based algorithm with a low dimensional soft threshold policy parameterization that leverages the underlying queueing structure. We provide stationary-point convergence guarantees for the general case and despite the low-dimensional parameterization prove that ACHQ converges to an approximate global optimum for the special case of two servers. Simulations demonstrate an improvement in expected response time of up to ~30% over the greedy policy that routes to the fastest available server.

{{</citation>}}


### (94/175) Double-Dip: Thwarting Label-Only Membership Inference Attacks with Transfer Learning and Randomization (Arezoo Rajabi et al., 2024)

{{<citation>}}

Arezoo Rajabi, Reeya Pimple, Aiswarya Janardhanan, Surudhi Asokraj, Bhaskar Ramasubramanian, Radha Poovendran. (2024)  
**Double-Dip: Thwarting Label-Only Membership Inference Attacks with Transfer Learning and Randomization**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CR, cs-LG, cs.LG  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2402.01114v1)  

---


**ABSTRACT**  
Transfer learning (TL) has been demonstrated to improve DNN model performance when faced with a scarcity of training samples. However, the suitability of TL as a solution to reduce vulnerability of overfitted DNNs to privacy attacks is unexplored. A class of privacy attacks called membership inference attacks (MIAs) aim to determine whether a given sample belongs to the training dataset (member) or not (nonmember). We introduce Double-Dip, a systematic empirical study investigating the use of TL (Stage-1) combined with randomization (Stage-2) to thwart MIAs on overfitted DNNs without degrading classification accuracy. Our study examines the roles of shared feature space and parameter values between source and target models, number of frozen layers, and complexity of pretrained models. We evaluate Double-Dip on three (Target, Source) dataset paris: (i) (CIFAR-10, ImageNet), (ii) (GTSRB, ImageNet), (iii) (CelebA, VGGFace2). We consider four publicly available pretrained DNNs: (a) VGG-19, (b) ResNet-18, (c) Swin-T, and (d) FaceNet. Our experiments demonstrate that Stage-1 reduces adversary success while also significantly increasing classification accuracy of nonmembers against an adversary with either white-box or black-box DNN model access, attempting to carry out SOTA label-only MIAs. After Stage-2, success of an adversary carrying out a label-only MIA is further reduced to near 50%, bringing it closer to a random guess and showing the effectiveness of Double-Dip. Stage-2 of Double-Dip also achieves lower ASR and higher classification accuracy than regularization and differential privacy-based methods.

{{</citation>}}


### (95/175) Near-Optimal Reinforcement Learning with Self-Play under Adaptivity Constraints (Dan Qiao et al., 2024)

{{<citation>}}

Dan Qiao, Yu-Xiang Wang. (2024)  
**Near-Optimal Reinforcement Learning with Self-Play under Adaptivity Constraints**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-MA, cs.LG, stat-ML  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01111v1)  

---


**ABSTRACT**  
We study the problem of multi-agent reinforcement learning (MARL) with adaptivity constraints -- a new problem motivated by real-world applications where deployments of new policies are costly and the number of policy updates must be minimized. For two-player zero-sum Markov Games, we design a (policy) elimination based algorithm that achieves a regret of $\widetilde{O}(\sqrt{H^3 S^2 ABK})$, while the batch complexity is only $O(H+\log\log K)$. In the above, $S$ denotes the number of states, $A,B$ are the number of actions for the two players respectively, $H$ is the horizon and $K$ is the number of episodes. Furthermore, we prove a batch complexity lower bound $\Omega(\frac{H}{\log_{A}K}+\log\log K)$ for all algorithms with $\widetilde{O}(\sqrt{K})$ regret bound, which matches our upper bound up to logarithmic factors. As a byproduct, our techniques naturally extend to learning bandit games and reward-free MARL within near optimal batch complexity. To the best of our knowledge, these are the first line of results towards understanding MARL with low adaptivity.

{{</citation>}}


### (96/175) Vaccine: Perturbation-aware Alignment for Large Language Model (Tiansheng Huang et al., 2024)

{{<citation>}}

Tiansheng Huang, Sihao Hu, Ling Liu. (2024)  
**Vaccine: Perturbation-aware Alignment for Large Language Model**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01109v1)  

---


**ABSTRACT**  
The new paradigm of finetuning-as-a-service introduces a new attack surface for Large Language Models (LLMs): a few harmful data uploaded by users can easily trick the finetuning to produce an alignment-broken model. We conduct an empirical analysis and uncover a \textit{harmful embedding drift} phenomenon, showing a probable cause of the alignment-broken effect. Inspired by our findings, we propose Vaccine, a perturbation-aware alignment technique to mitigate the security risk of users finetuning. The core idea of Vaccine is to produce invariant hidden embeddings by progressively adding crafted perturbation to them in the alignment phase. This enables the embeddings to withstand harmful perturbation from un-sanitized user data in the finetuning phase. Our results on open source mainstream LLMs (e.g., Llama2, Opt, Vicuna) demonstrate that Vaccine can boost the robustness of alignment against harmful prompts induced embedding drift while reserving reasoning ability towards benign prompts. Our code is available at \url{https://github.com/git-disl/Vaccine}.

{{</citation>}}


### (97/175) An introduction to graphical tensor notation for mechanistic interpretability (Jordan K. Taylor, 2024)

{{<citation>}}

Jordan K. Taylor. (2024)  
**An introduction to graphical tensor notation for mechanistic interpretability**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2402.01790v1)  

---


**ABSTRACT**  
Graphical tensor notation is a simple way of denoting linear operations on tensors, originating from physics. Modern deep learning consists almost entirely of operations on or between tensors, so easily understanding tensor operations is quite important for understanding these systems. This is especially true when attempting to reverse-engineer the algorithms learned by a neural network in order to understand its behavior: a field known as mechanistic interpretability. It's often easy to get confused about which operations are happening between tensors and lose sight of the overall structure, but graphical tensor notation makes it easier to parse things at a glance and see interesting equivalences. The first half of this document introduces the notation and applies it to some decompositions (SVD, CP, Tucker, and tensor network decompositions), while the second half applies it to some existing some foundational approaches for mechanistically understanding language models, loosely following ``A Mathematical Framework for Transformer Circuits'', then constructing an example ``induction head'' circuit in graphical tensor notation.

{{</citation>}}


### (98/175) Simulation of Graph Algorithms with Looped Transformers (Artur Back de Luca et al., 2024)

{{<citation>}}

Artur Back de Luca, Kimon Fountoulakis. (2024)  
**Simulation of Graph Algorithms with Looped Transformers**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-DS, cs-LG, cs.LG  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2402.01107v1)  

---


**ABSTRACT**  
The execution of graph algorithms using neural networks has recently attracted significant interest due to promising empirical progress. This motivates further understanding of how neural networks can replicate reasoning steps with relational data. In this work, we study the ability of transformer networks to simulate algorithms on graphs from a theoretical perspective. The architecture that we utilize is a looped transformer with extra attention heads that interact with the graph. We prove by construction that this architecture can simulate algorithms such as Dijkstra's shortest path algorithm, Breadth- and Depth-First Search, and Kosaraju's strongly connected components algorithm. The width of the network does not increase with the size of the input graph, which implies that the network can simulate the above algorithms for any graph. Despite this property, we show that there is a limit to simulation in our solution due to finite precision. Finally, we show a Turing Completeness result with constant width when the extra attention heads are utilized.

{{</citation>}}


### (99/175) Compositional Generative Modeling: A Single Model is Not All You Need (Yilun Du et al., 2024)

{{<citation>}}

Yilun Du, Leslie Kaelbling. (2024)  
**Compositional Generative Modeling: A Single Model is Not All You Need**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs-RO, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01103v1)  

---


**ABSTRACT**  
Large monolithic generative models trained on massive amounts of data have become an increasingly dominant approach in AI research. In this paper, we argue that we should instead construct large generative systems by composing smaller generative models together. We show how such a compositional generative approach enables us to learn distributions in a more data-efficient manner, enabling generalization to parts of the data distribution unseen at training time. We further show how this enables us to program and construct new generative models for tasks completely unseen at training. Finally, we show that in many cases, we can discover separate compositional components from data.

{{</citation>}}


### (100/175) Trustworthy Distributed AI Systems: Robustness, Privacy, and Governance (Wenqi Wei et al., 2024)

{{<citation>}}

Wenqi Wei, Ling Liu. (2024)  
**Trustworthy Distributed AI Systems: Robustness, Privacy, and Governance**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CR, cs-DC, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01096v1)  

---


**ABSTRACT**  
Emerging Distributed AI systems are revolutionizing big data computing and data processing capabilities with growing economic and societal impact. However, recent studies have identified new attack surfaces and risks caused by security, privacy, and fairness issues in AI systems. In this paper, we review representative techniques, algorithms, and theoretical foundations for trustworthy distributed AI through robustness guarantee, privacy protection, and fairness awareness in distributed learning. We first provide a brief overview of alternative architectures for distributed learning, discuss inherent vulnerabilities for security, privacy, and fairness of AI algorithms in distributed learning, and analyze why these problems are present in distributed learning regardless of specific architectures. Then we provide a unique taxonomy of countermeasures for trustworthy distributed AI, covering (1) robustness to evasion attacks and irregular queries at inference, and robustness to poisoning attacks, Byzantine attacks, and irregular data distribution during training; (2) privacy protection during distributed learning and model inference at deployment; and (3) AI fairness and governance with respect to both data and models. We conclude with a discussion on open challenges and future research directions toward trustworthy distributed AI, such as the need for trustworthy AI policy guidelines, the AI responsibility-utility co-design, and incentives and compliance.

{{</citation>}}


### (101/175) Specialized Language Models with Cheap Inference from Limited Domain Data (David Grangier et al., 2024)

{{<citation>}}

David Grangier, Angelos Katharopoulos, Pierre Ablin, Awni Hannun. (2024)  
**Specialized Language Models with Cheap Inference from Limited Domain Data**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01093v1)  

---


**ABSTRACT**  
Large language models have emerged as a versatile tool but are challenging to apply to tasks lacking large inference budgets and large in-domain training sets. This work formalizes these constraints and distinguishes four important variables: the pretraining budget (for training before the target domain is known), the specialization budget (for training after the target domain is known), the inference budget, and the in-domain training set size. Across these settings, we compare different approaches from the machine learning literature. Limited by inference cost, we find better alternatives to the standard practice of training very large vanilla transformer models. In particular, we show that hyper-networks and mixture of experts have better perplexity for large pretraining budgets, while small models trained on importance sampled datasets are attractive for large specialization budgets.

{{</citation>}}


### (102/175) DoseGNN: Improving the Performance of Deep Learning Models in Adaptive Dose-Volume Histogram Prediction through Graph Neural Networks (Zehao Dong et al., 2024)

{{<citation>}}

Zehao Dong, Yixin Chen, Tianyu Zhao. (2024)  
**DoseGNN: Improving the Performance of Deep Learning Models in Adaptive Dose-Volume Histogram Prediction through Graph Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2402.01076v1)  

---


**ABSTRACT**  
Dose-Volume Histogram (DVH) prediction is fundamental in radiation therapy that facilitate treatment planning, dose evaluation, plan comparison and etc. It helps to increase the ability to deliver precise and effective radiation treatments while managing potential toxicities to healthy tissues as needed to reduce the risk of complications. This paper extends recently disclosed research findings presented on AAPM (AAPM 65th Annual Meeting $\&$ Exhibition) and includes necessary technique details. The objective is to design efficient deep learning models for DVH prediction on general radiotherapy platform equipped with high performance CBCT system, where input CT images and target dose images to predict may have different origins, spacing and sizes. Deep learning models widely-adopted in DVH prediction task are evaluated on the novel radiotherapy platform, and graph neural networks (GNNs) are shown to be the ideal architecture to construct a plug-and-play framework to improve predictive performance of base deep learning models in the adaptive setting.

{{</citation>}}


### (103/175) Chameleon: Foundation Models for Fairness-aware Multi-modal Data Augmentation to Enhance Coverage of Minorities (Mahdi Erfanian et al., 2024)

{{<citation>}}

Mahdi Erfanian, H. V. Jagadish, Abolfazl Asudeh. (2024)  
**Chameleon: Foundation Models for Fairness-aware Multi-modal Data Augmentation to Enhance Coverage of Minorities**  

---
Primary Category: cs.LG  
Categories: cs-CY, cs-DB, cs-LG, cs.LG  
Keywords: AI, Augmentation  
[Paper Link](http://arxiv.org/abs/2402.01071v1)  

---


**ABSTRACT**  
The potential harms of the under-representation of minorities in training data, particularly in multi-modal settings, is a well-recognized concern. While there has been extensive effort in detecting such under-representation, resolution has remained a challenge. With recent advancements in generative AI, large language models and foundation models have emerged as versatile tools across various domains. In this paper, we propose Chameleon, a system that efficiently utilizes these tools to augment a data set with a minimal addition of synthetically generated tuples, in order to enhance the coverage of the under-represented groups. Our system follows a rejection sampling approach to ensure the generated tuples have a high quality and follow the underlying distribution. In order to minimize the rejection chance of the generated tuples, we propose multiple strategies for providing a guide for the foundation model. Our experiment results, in addition to confirming the efficiency of our proposed algorithms, illustrate the effectiveness of our approach, as the unfairness of the model in a downstream task significantly dropped after data repair using Chameleon.

{{</citation>}}


## cs.GT (1)



### (104/175) Reducing Optimism Bias in Incomplete Cooperative Games (Filip Úradník et al., 2024)

{{<citation>}}

Filip Úradník, David Sychrovský, Jakub Černý, Martin Černý. (2024)  
**Reducing Optimism Bias in Incomplete Cooperative Games**  

---
Primary Category: cs.GT  
Categories: cs-GT, cs-LG, cs.GT  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2402.01930v1)  

---


**ABSTRACT**  
Cooperative game theory has diverse applications in contemporary artificial intelligence, including domains like interpretable machine learning, resource allocation, and collaborative decision-making. However, specifying a cooperative game entails assigning values to exponentially many coalitions, and obtaining even a single value can be resource-intensive in practice. Yet simply leaving certain coalition values undisclosed introduces ambiguity regarding individual contributions to the collective grand coalition. This ambiguity often leads to players holding overly optimistic expectations, stemming from either inherent biases or strategic considerations, frequently resulting in collective claims exceeding the actual grand coalition value. In this paper, we present a framework aimed at optimizing the sequence for revealing coalition values, with the overarching goal of efficiently closing the gap between players' expectations and achievable outcomes in cooperative games. Our contributions are threefold: (i) we study the individual players' optimistic completions of games with missing coalition values along with the arising gap, and investigate its analytical characteristics that facilitate more efficient optimization; (ii) we develop methods to minimize this gap over classes of games with a known prior by disclosing values of additional coalitions in both offline and online fashion; and (iii) we empirically demonstrate the algorithms' performance in practical scenarios, together with an investigation into the typical order of revealing coalition values.

{{</citation>}}


## cs.HC (2)



### (105/175) Mathemyths: Leveraging Large Language Models to Teach Mathematical Language through Child-AI Co-Creative Storytelling (Chao Zhang et al., 2024)

{{<citation>}}

Chao Zhang, Xuechen Liu, Katherine Ziska, Soobin Jeon, Chi-Lin Yu, Ying Xu. (2024)  
**Mathemyths: Leveraging Large Language Models to Teach Mathematical Language through Child-AI Co-Creative Storytelling**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01927v1)  

---


**ABSTRACT**  
Mathematical language is a cornerstone of a child's mathematical development, and children can effectively acquire this language through storytelling with a knowledgeable and engaging partner. In this study, we leverage the recent advances in large language models to conduct free-form, creative conversations with children. Consequently, we developed Mathemyths, a joint storytelling agent that takes turns co-creating stories with children while integrating mathematical terms into the evolving narrative. This paper details our development process, illustrating how prompt-engineering can optimize LLMs for educational contexts. Through a user study involving 35 children aged 4-8 years, our results suggest that when children interacted with Mathemyths, their learning of mathematical language was comparable to those who co-created stories with a human partner. However, we observed differences in how children engaged with co-creation partners of different natures. Overall, we believe that LLM applications, like Mathemyths, offer children a unique conversational experience pertaining to focused learning objectives.

{{</citation>}}


### (106/175) Homogenization Effects of Large Language Models on Human Creative Ideation (Barrett R. Anderson et al., 2024)

{{<citation>}}

Barrett R. Anderson, Jash Hemant Shah, Max Kreminski. (2024)  
**Homogenization Effects of Large Language Models on Human Creative Ideation**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-HC, cs.HC  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01536v1)  

---


**ABSTRACT**  
Large language models (LLMs) are now being used in a wide variety of contexts, including as creativity support tools (CSTs) intended to help their users come up with new ideas. But do LLMs actually support user creativity? We hypothesized that the use of an LLM as a CST might make the LLM's users feel more creative, and even broaden the range of ideas suggested by each individual user, but also homogenize the ideas suggested by different users. We conducted a 36-participant comparative user study and found, in accordance with the homogenization hypothesis, that different users tended to produce less semantically distinct ideas with ChatGPT than with an alternative CST. Additionally, ChatGPT users generated a greater number of more detailed ideas, but felt less responsible for the ideas they generated. We discuss potential implications of these findings for users, designers, and developers of LLM-based CSTs.

{{</citation>}}


## cs.SE (8)



### (107/175) Are You a Real Software Engineer? Best Practices in Online Recruitment for Software Engineering Studies (Adam Alami et al., 2024)

{{<citation>}}

Adam Alami, Mansooreh Zahedi, Neil Ernst. (2024)  
**Are You a Real Software Engineer? Best Practices in Online Recruitment for Software Engineering Studies**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01925v1)  

---


**ABSTRACT**  
Online research platforms, such as Prolific, offer rapid access to diverse participant pools but also pose unique challenges in participant qualification and skill verification. Previous studies reported mixed outcomes and challenges in leveraging online platforms for the recruitment of qualified software engineers. Drawing from our experience in conducting three different studies using Prolific, we propose best practices for recruiting and screening participants to enhance the quality and relevance of both qualitative and quantitative software engineering (SE) research samples. We propose refined best practices for recruitment in SE research on Prolific. (1) Iterative and controlled prescreening, enabling focused and manageable assessment of submissions (2) task-oriented and targeted questions that assess technical skills, knowledge of basic SE concepts, and professional engagement. (3) AI detection to verify the authenticity of free-text responses. (4) Qualitative and manual assessment of responses, ensuring authenticity and relevance in participant answers (5) Additional layers of prescreening are necessary when necessary to collect data relevant to the topic of the study. (6) Fair or generous compensation post-qualification to incentivize genuine participation. By sharing our experiences and lessons learned, we contribute to the development of effective and rigorous methods for SE empirical research. particularly the ongoing effort to establish guidelines to ensure reliable data collection. These practices have the potential to transferability to other participant recruitment platforms.

{{</citation>}}


### (108/175) FuzzSlice: Pruning False Positives in Static Analysis Warnings Through Function-Level Fuzzing (Aniruddhan Murali et al., 2024)

{{<citation>}}

Aniruddhan Murali, Noble Saji Mathews, Mahmoud Alfadel, Meiyappan Nagappan, Meng Xu. (2024)  
**FuzzSlice: Pruning False Positives in Static Analysis Warnings Through Function-Level Fuzzing**  

---
Primary Category: cs.SE  
Categories: cs-CR, cs-SE, cs.SE  
Keywords: Pruning  
[Paper Link](http://arxiv.org/abs/2402.01923v1)  

---


**ABSTRACT**  
Manual confirmation of static analysis reports is a daunting task. This is due to both the large number of warnings and the high density of false positives among them. Fuzzing techniques have been proposed to verify static analysis warnings. However, a major limitation is that fuzzing the whole project to reach all static analysis warnings is not feasible. This can take several days and exponential machine time to increase code coverage linearly. Therefore, we propose FuzzSlice, a novel framework that automatically prunes possible false positives among static analysis warnings. Unlike prior work that mostly focuses on confirming true positives among static analysis warnings, which requires end-to-end fuzzing, FuzzSlice focuses on ruling out potential false positives, which are the majority in static analysis reports. The key insight that we base our work on is that a warning that does not yield a crash when fuzzed at the function level in a given time budget is a possible false positive. To achieve this, FuzzSlice first aims to generate compilable code slices at the function level and then fuzzes these code slices instead of the entire binary. FuzzSlice is also unlikely to misclassify a true bug as a false positive because the crashing input can be reproduced by a fuzzer at the function level as well. We evaluate FuzzSlice on the Juliet synthetic dataset and real-world complex C projects. Our evaluation shows that the ground truth in the Juliet dataset had 864 false positives which were all detected by FuzzSlice. For the open-source repositories, we were able to get the developers from two of these open-source repositories to independently label these warnings. FuzzSlice automatically identifies 33 out of 53 false positives confirmed by developers in these two repositories. Thus FuzzSlice reduces false positives by 62.26% in the open-source repositories and by 100% in the Juliet dataset.

{{</citation>}}


### (109/175) COMET: Generating Commit Messages using Delta Graph Context Representation (Abhinav Reddy Mandli et al., 2024)

{{<citation>}}

Abhinav Reddy Mandli, Saurabhsingh Rajput, Tushar Sharma. (2024)  
**COMET: Generating Commit Messages using Delta Graph Context Representation**  

---
Primary Category: cs.SE  
Categories: cs-AI, cs-CL, cs-SE, cs.SE  
Keywords: GPT  
[Paper Link](http://arxiv.org/abs/2402.01841v1)  

---


**ABSTRACT**  
Commit messages explain code changes in a commit and facilitate collaboration among developers. Several commit message generation approaches have been proposed; however, they exhibit limited success in capturing the context of code changes. We propose Comet (Context-Aware Commit Message Generation), a novel approach that captures context of code changes using a graph-based representation and leverages a transformer-based model to generate high-quality commit messages. Our proposed method utilizes delta graph that we developed to effectively represent code differences. We also introduce a customizable quality assurance module to identify optimal messages, mitigating subjectivity in commit messages. Experiments show that Comet outperforms state-of-the-art techniques in terms of bleu-norm and meteor metrics while being comparable in terms of rogue-l. Additionally, we compare the proposed approach with the popular gpt-3.5-turbo model, along with gpt-4-turbo; the most capable GPT model, over zero-shot, one-shot, and multi-shot settings. We found Comet outperforming the GPT models, on five and four metrics respectively and provide competitive results with the two other metrics. The study has implications for researchers, tool developers, and software developers. Software developers may utilize Comet to generate context-aware commit messages. Researchers and tool developers can apply the proposed delta graph technique in similar contexts, like code review summarization.

{{</citation>}}


### (110/175) Exploring the Effect of Multiple Natural Languages on Code Suggestion Using GitHub Copilot (Kei Koyanagi et al., 2024)

{{<citation>}}

Kei Koyanagi, Dong Wang, Kotaro Noguchi, Masanari Kondo, Alexander Serebrenik, Yasutaka Kamei, Naoyasu Ubayashi. (2024)  
**Exploring the Effect of Multiple Natural Languages on Code Suggestion Using GitHub Copilot**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: AI, NLP  
[Paper Link](http://arxiv.org/abs/2402.01438v1)  

---


**ABSTRACT**  
GitHub Copilot is an AI-enabled tool that automates program synthesis. It has gained significant attention since its launch in 2021. Recent studies have extensively examined Copilot's capabilities in various programming tasks, as well as its security issues. However, little is known about the effect of different natural languages on code suggestion. Natural language is considered a social bias in the field of NLP, and this bias could impact the diversity of software engineering. To address this gap, we conducted an empirical study to investigate the effect of three popular natural languages (English, Japanese, and Chinese) on Copilot. We used 756 questions of varying difficulty levels from AtCoder contests for evaluation purposes. The results highlight that the capability varies across natural languages, with Chinese achieving the worst performance. Furthermore, regardless of the type of natural language, the performance decreases significantly as the difficulty of questions increases. Our work represents the initial step in comprehending the significance of natural languages in Copilot's capability and introduces promising opportunities for future endeavors.

{{</citation>}}


### (111/175) CodePori: Large Scale Model for Autonomous Software Development by Using Multi-Agents (Zeeshan Rasheed et al., 2024)

{{<citation>}}

Zeeshan Rasheed, Muhammad Waseem, Mika Saari, Kari Systä, Pekka Abrahamsson. (2024)  
**CodePori: Large Scale Model for Autonomous Software Development by Using Multi-Agents**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: AI, GPT, Language Model, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2402.01411v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) and Generative Pre-trained Transformers (GPTs) are reshaping the field of Software Engineering (SE). Existing LLM-based multi-agent systems have successfully resolved simple dialogue tasks. However, the potential of LLMs for more complex tasks, such as automated code generation for large and complex projects, have been explored in only a few existing works. This paper introduces CodePori, a novel model designed to automate code generation for extensive and complex software projects based on natural language prompts. We employ LLM-based multi-AI agents to handle creative and challenging tasks in autonomous software development. Each agent engages with a specific task, including system design, code development, code review, code verification, and test engineering. We show in the paper that CodePori is able to generate running code for large-scale projects, completing the entire software development process in minutes rather than hours, and at a cost of a few dollars. It identifies and mitigates potential security vulnerabilities and corrects errors while maintaining a solid code performance level. We also conducted an evaluation of CodePori against existing solutions using HumanEval and the Massively Multitask Benchmark for Python (MBPP) benchmark. The results indicate that CodePori improves upon the benchmarks in terms of code accuracy, efficiency, and overall performance. For example, CodePori improves the pass@1 metric on HumanEval to 87.5% and on MBPP to 86.5%, representing a clear improvement over the existing models. We also assessed CodePori's performance through practitioner evaluations, with 91% expressing satisfaction with the model's performance.

{{</citation>}}


### (112/175) StepCoder: Improve Code Generation with Reinforcement Learning from Compiler Feedback (Shihan Dou et al., 2024)

{{<citation>}}

Shihan Dou, Yan Liu, Haoxiang Jia, Limao Xiong, Enyu Zhou, Wei Shen, Junjie Shan, Caishuang Huang, Xiao Wang, Xiaoran Fan, Zhiheng Xi, Yuhao Zhou, Tao Ji, Rui Zheng, Qi Zhang, Xuanjing Huang, Tao Gui. (2024)  
**StepCoder: Improve Code Generation with Reinforcement Learning from Compiler Feedback**  

---
Primary Category: cs.SE  
Categories: cs-CL, cs-SE, cs.SE  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01391v2)  

---


**ABSTRACT**  
The advancement of large language models (LLMs) has significantly propelled the field of code generation. Previous work integrated reinforcement learning (RL) with compiler feedback for exploring the output space of LLMs to enhance code generation quality. However, the lengthy code generated by LLMs in response to complex human requirements makes RL exploration a challenge. Also, since the unit tests may not cover the complicated code, optimizing LLMs by using these unexecuted code snippets is ineffective. To tackle these challenges, we introduce StepCoder, a novel RL framework for code generation, consisting of two main components: CCCS addresses the exploration challenge by breaking the long sequences code generation task into a Curriculum of Code Completion Subtasks, while FGO only optimizes the model by masking the unexecuted code segments to provide Fine-Grained Optimization. In addition, we furthermore construct the APPS+ dataset for RL training, which is manually verified to ensure the correctness of unit tests. Experimental results show that our method improves the ability to explore the output space and outperforms state-of-the-art approaches in corresponding benchmarks. Our dataset APPS+ and StepCoder are available online.

{{</citation>}}


### (113/175) Can Large Language Models Serve as Data Analysts? A Multi-Agent Assisted Approach for Qualitative Data Analysis (Zeeshan Rasheed et al., 2024)

{{<citation>}}

Zeeshan Rasheed, Muhammad Waseem, Aakash Ahmad, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Pekka Abrahamsson. (2024)  
**Can Large Language Models Serve as Data Analysts? A Multi-Agent Assisted Approach for Qualitative Data Analysis**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01386v1)  

---


**ABSTRACT**  
Recent advancements in Large Language Models (LLMs) have enabled collaborative human-bot interactions in Software Engineering (SE), similar to many other professions. However, the potential benefits and implications of incorporating LLMs into qualitative data analysis in SE have not been completely explored. For instance, conducting qualitative data analysis manually can be a time-consuming, effort-intensive, and error-prone task for researchers. LLM-based solutions, such as generative AI models trained on massive datasets, can be utilized to automate tasks in software development as well as in qualitative data analysis. To this end, we utilized LLMs to automate and expedite the qualitative data analysis processes. We employed a multi-agent model, where each agent was tasked with executing distinct, individual research related activities. Our proposed model interpreted large quantities of textual documents and interview transcripts to perform several common tasks used in qualitative analysis. The results show that this technical assistant speeds up significantly the data analysis process, enabling researchers to manage larger datasets much more effectively. Furthermore, this approach introduces a new dimension of scalability and accuracy in qualitative research, potentially transforming data interpretation methodologies in SE.

{{</citation>}}


### (114/175) An Empirical Study on Low Code Programming using Traditional vs Large Language Model Support (Yongkun Liu et al., 2024)

{{<citation>}}

Yongkun Liu, Jiachi Chen, Tingting Bi, John Grundy, Yanlin Wang, Ting Chen, Yutian Tang, Zibin Zheng. (2024)  
**An Empirical Study on Low Code Programming using Traditional vs Large Language Model Support**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01156v1)  

---


**ABSTRACT**  
Low-code programming (LCP) refers to programming using models at higher levels of abstraction, resulting in less manual and more efficient programming, and reduced learning effort for amateur developers. Many LCP tools have rapidly evolved and have benefited from the concepts of visual programming languages (VPLs) and programming by demonstration (PBD). With huge increase in interest in using large language models (LLMs) in software engineering, LLM-based LCP has began to become increasingly important. However, the technical principles and application scenarios of traditional approaches to LCP and LLM-based LCP are significantly different. Understanding these key differences and characteristics in the application of the two approaches to LCP by users is crucial for LCP providers in improving existing and developing new LCP tools, and in better assisting users in choosing the appropriate LCP technology. We conducted an empirical study of both traditional LCP and LLM-based LCP. We analyzed developers' discussions on Stack Overflow (SO) over the past three years and then explored the similarities and differences between traditional LCP and LLM-based LCP features and developer feedback. Our findings reveal that while traditional LCP and LLM-based LCP share common primary usage scenarios, they significantly differ in scope, limitations and usage throughout the software development lifecycle, particularly during the implementation phase. We also examine how LLMs impact and integrate with LCP, discussing the latest technological developments in LLM-based LCP, such as its integration with VPLs and the application of LLM Agents in software engineering.

{{</citation>}}


## cs.RO (6)



### (115/175) TartanDrive 2.0: More Modalities and Better Infrastructure to Further Self-Supervised Learning Research in Off-Road Driving Tasks (Matthew Sivaprakasam et al., 2024)

{{<citation>}}

Matthew Sivaprakasam, Parv Maheshwari, Mateo Guaman Castro, Samuel Triest, Micah Nye, Steve Willits, Andrew Saba, Wenshan Wang, Sebastian Scherer. (2024)  
**TartanDrive 2.0: More Modalities and Better Infrastructure to Further Self-Supervised Learning Research in Off-Road Driving Tasks**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2402.01913v1)  

---


**ABSTRACT**  
We present TartanDrive 2.0, a large-scale off-road driving dataset for self-supervised learning tasks. In 2021 we released TartanDrive 1.0, which is one of the largest datasets for off-road terrain. As a follow-up to our original dataset, we collected seven hours of data at speeds of up to 15m/s with the addition of three new LiDAR sensors alongside the original camera, inertial, GPS, and proprioceptive sensors. We also release the tools we use for collecting, processing, and querying the data, including our metadata system designed to further the utility of our data. Custom infrastructure allows end users to reconfigure the data to cater to their own platforms. These tools and infrastructure alongside the dataset are useful for a variety of tasks in the field of off-road autonomy and, by releasing them, we encourage collaborative data aggregation. These resources lower the barrier to entry to utilizing large-scale datasets, thereby helping facilitate the advancement of robotics in areas such as self-supervised learning, multi-modal perception, inverse reinforcement learning, and representation learning. The dataset is available at https://github.com/castacks/tartan drive 2.0.

{{</citation>}}


### (116/175) Dynamic Occupancy Grids for Object Detection: A Radar-Centric Approach (Max Peter Ronecker et al., 2024)

{{<citation>}}

Max Peter Ronecker, Markus Schratter, Lukas Kuschnig, Daniel Watzenig. (2024)  
**Dynamic Occupancy Grids for Object Detection: A Radar-Centric Approach**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2402.01488v1)  

---


**ABSTRACT**  
Dynamic Occupancy Grid Mapping is a technique used to generate a local map of the environment containing both static and dynamic information. Typically, these maps are primarily generated using lidar measurements. However, with improvements in radar sensing, resulting in better accuracy and higher resolution, radar is emerging as a viable alternative to lidar as the primary sensor for mapping. In this paper, we propose a radar-centric dynamic occupancy grid mapping algorithm with adaptations to the state computation, inverse sensor model, and field-of-view computation tailored to the specifics of radar measurements. We extensively evaluate our approach using real data to demonstrate its effectiveness and establish the first benchmark for radar-based dynamic occupancy grid mapping using the publicly available Radarscenes dataset.

{{</citation>}}


### (117/175) A Reinforcement Learning-Boosted Motion Planning Framework: Comprehensive Generalization Performance in Autonomous Driving (Rainer Trauth et al., 2024)

{{<citation>}}

Rainer Trauth, Alexander Hobmeier, Johannes Betz. (2024)  
**A Reinforcement Learning-Boosted Motion Planning Framework: Comprehensive Generalization Performance in Autonomous Driving**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01465v1)  

---


**ABSTRACT**  
This study introduces a novel approach to autonomous motion planning, informing an analytical algorithm with a reinforcement learning (RL) agent within a Frenet coordinate system. The combination directly addresses the challenges of adaptability and safety in autonomous driving. Motion planning algorithms are essential for navigating dynamic and complex scenarios. Traditional methods, however, lack the flexibility required for unpredictable environments, whereas machine learning techniques, particularly reinforcement learning (RL), offer adaptability but suffer from instability and a lack of explainability. Our unique solution synergizes the predictability and stability of traditional motion planning algorithms with the dynamic adaptability of RL, resulting in a system that efficiently manages complex situations and adapts to changing environmental conditions. Evaluation of our integrated approach shows a significant reduction in collisions, improved risk management, and improved goal success rates across multiple scenarios. The code used in this research is publicly available as open-source software and can be accessed at the following link: https://github.com/TUM-AVS/Frenetix-RL.

{{</citation>}}


### (118/175) LimSim++: A Closed-Loop Platform for Deploying Multimodal LLMs in Autonomous Driving (Daocheng Fu et al., 2024)

{{<citation>}}

Daocheng Fu, Wenjie Lei, Licheng Wen, Pinlong Cai, Song Mao, Min Dou, Botian Shi, Yu Qiao. (2024)  
**LimSim++: A Closed-Loop Platform for Deploying Multimodal LLMs in Autonomous Driving**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs-SY, cs.RO, eess-SY  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01246v1)  

---


**ABSTRACT**  
The emergence of Multimodal Large Language Models ((M)LLMs) has ushered in new avenues in artificial intelligence, particularly for autonomous driving by offering enhanced understanding and reasoning capabilities. This paper introduces LimSim++, an extended version of LimSim designed for the application of (M)LLMs in autonomous driving. Acknowledging the limitations of existing simulation platforms, LimSim++ addresses the need for a long-term closed-loop infrastructure supporting continuous learning and improved generalization in autonomous driving. The platform offers extended-duration, multi-scenario simulations, providing crucial information for (M)LLM-driven vehicles. Users can engage in prompt engineering, model evaluation, and framework enhancement, making LimSim++ a versatile tool for research and practice. This paper additionally introduces a baseline (M)LLM-driven framework, systematically validated through quantitative experiments across diverse scenarios. The open-source resources of LimSim++ are available at: https://pjlab-adg.github.io/limsim_plus/.

{{</citation>}}


### (119/175) Scalable Multi-modal Model Predictive Control via Duality-based Interaction Predictions (Hansung Kim et al., 2024)

{{<citation>}}

Hansung Kim, Siddharth H. Nair, Francesco Borrelli. (2024)  
**Scalable Multi-modal Model Predictive Control via Duality-based Interaction Predictions**  

---
Primary Category: cs.RO  
Categories: cs-LG, cs-RO, cs-SY, cs.RO, eess-SY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01116v1)  

---


**ABSTRACT**  
We propose a hierarchical architecture designed for scalable real-time Model Predictive Control (MPC) in complex, multi-modal traffic scenarios. This architecture comprises two key components: 1) RAID-Net, a novel attention-based Recurrent Neural Network that predicts relevant interactions along the MPC prediction horizon between the autonomous vehicle and the surrounding vehicles using Lagrangian duality, and 2) a reduced Stochastic MPC problem that eliminates irrelevant collision avoidance constraints, enhancing computational efficiency. Our approach is demonstrated in a simulated traffic intersection with interactive surrounding vehicles, showcasing a 12x speed-up in solving the motion planning problem. A video demonstrating the proposed architecture in multiple complex traffic scenarios can be found here: https://youtu.be/-TcMeolCLWc

{{</citation>}}


### (120/175) Learning Which Side to Scan: Multi-View Informed Active Perception with Side Scan Sonar for Autonomous Underwater Vehicles (Advaith V. Sethuraman et al., 2024)

{{<citation>}}

Advaith V. Sethuraman, Philip Baldoni, Katherine A. Skinner, James McMahon. (2024)  
**Learning Which Side to Scan: Multi-View Informed Active Perception with Side Scan Sonar for Autonomous Underwater Vehicles**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2402.01106v1)  

---


**ABSTRACT**  
Autonomous underwater vehicles often perform surveys that capture multiple views of targets in order to provide more information for human operators or automatic target recognition algorithms. In this work, we address the problem of choosing the most informative views that minimize survey time while maximizing classifier accuracy. We introduce a novel active perception framework for multi-view adaptive surveying and reacquisition using side scan sonar imagery. Our framework addresses this challenge by using a graph formulation for the adaptive survey task. We then use Graph Neural Networks (GNNs) to both classify acquired sonar views and to choose the next best view based on the collected data. We evaluate our method using simulated surveys in a high-fidelity side scan sonar simulator. Our results demonstrate that our approach is able to surpass the state-of-the-art in classification accuracy and survey efficiency. This framework is a promising approach for more efficient autonomous missions involving side scan sonar, such as underwater exploration, marine archaeology, and environmental monitoring.

{{</citation>}}


## cs.SI (2)



### (121/175) Carthago Delenda Est: Co-opetitive Indirect Information Diffusion Model for Influence Operations on Online Social Media (Jwen Fai Low et al., 2024)

{{<citation>}}

Jwen Fai Low, Benjamin C. M. Fung, Farkhund Iqbal, Claude Fachkha. (2024)  
**Carthago Delenda Est: Co-opetitive Indirect Information Diffusion Model for Influence Operations on Online Social Media**  

---
Primary Category: cs.SI  
Categories: cs-CY, cs-MA, cs-SI, cs.SI  
Keywords: Social Media, Twitter  
[Paper Link](http://arxiv.org/abs/2402.01905v2)  

---


**ABSTRACT**  
For a state or non-state actor whose credibility is bankrupt, relying on bots to conduct non-attributable, non-accountable, and seemingly-grassroots-but-decentralized-in-actuality influence/information operations (info ops) on social media can help circumvent the issue of trust deficit while advancing its interests. Planning and/or defending against decentralized info ops can be aided by computational simulations in lieu of ethically-fraught live experiments on social media. In this study, we introduce Diluvsion, an agent-based model for contested information propagation efforts on Twitter-like social media. The model emphasizes a user's belief in an opinion (stance) being impacted by the perception of potentially illusory popular support from constant incoming floods of indirect information, floods that can be cooperatively engineered in an uncoordinated manner by bots as they compete to spread their stances. Our model, which has been validated against real-world data, is an advancement over previous models because we account for engagement metrics in influencing stance adoption, non-social tie spreading of information, neutrality as a stance that can be spread, and themes that are analogous to media's framing effect and are symbiotic with respect to stance propagation. The strengths of the Diluvsion model are demonstrated in simulations of orthodox info ops, e.g., maximizing adoption of one stance; creating echo chambers; inducing polarization; and unorthodox info ops, e.g., simultaneous support of multiple stances as a Trojan horse tactic for the dissemination of a theme.

{{</citation>}}


### (122/175) Examining Rail Transportation Route of Crude Oil in the US Using Crowdsourced Social Media Data (Yuandong Liu et al., 2024)

{{<citation>}}

Yuandong Liu, Majbah Uddin, Shih-Miao Chin, Ho-Ling Hwang, Jiaoli Chen. (2024)  
**Examining Rail Transportation Route of Crude Oil in the US Using Crowdsourced Social Media Data**  

---
Primary Category: cs.SI  
Categories: cs-SI, cs.SI  
Keywords: Social Media  
[Paper Link](http://arxiv.org/abs/2402.04020v1)  

---


**ABSTRACT**  
Safety issues associated with transporting crude oil by rail have been a concern since the boom of US domestic shale oil production in 2012. During the last decade, over 300 crude oil by rail incidents have occurred in the US. Some of them have caused adverse consequences including fire and hazardous materials leakage. However, only limited information on the routes of crude-on-rail and their associated risks is available to the public. To this end, this study proposes an unconventional way to reconstruct the crude-on-rail routes using geotagged photos harvested from the Flickr website. The proposed method links the geotagged photos of crude oil trains posted online with national railway networks to identify potential railway segments those crude oil trains were traveling on. A shortest path-based method was then applied to infer the complete crude-on-rail routes, by utilizing the confirmed railway segments as well as their movement direction information. Validation of the inferred routes was performed using a public map and official crude oil incident data. Results suggested that the inferred routes based on geotagged photos have high coverage, with approximately 96% of the documented crude oil incidents aligned with the reconstructed crude-on-rail network. The inferred crude oil train routes were found to pass through many metropolitan areas with dense populations, who are exposed to potential risk. This finding could improve situation awareness for policymakers and transportation planners. In addition, with the inferred routes, this study establishes a good foundation for future crude oil train risk analysis along the rail route.

{{</citation>}}


## cs.AI (6)



### (123/175) The Role of Foundation Models in Neuro-Symbolic Learning and Reasoning (Daniel Cunnington et al., 2024)

{{<citation>}}

Daniel Cunnington, Mark Law, Jorge Lobo, Alessandra Russo. (2024)  
**The Role of Foundation Models in Neuro-Symbolic Learning and Reasoning**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: AI, GPT, Reasoning  
[Paper Link](http://arxiv.org/abs/2402.01889v1)  

---


**ABSTRACT**  
Neuro-Symbolic AI (NeSy) holds promise to ensure the safe deployment of AI systems, as interpretable symbolic techniques provide formal behaviour guarantees. The challenge is how to effectively integrate neural and symbolic computation, to enable learning and reasoning from raw data. Existing pipelines that train the neural and symbolic components sequentially require extensive labelling, whereas end-to-end approaches are limited in terms of scalability, due to the combinatorial explosion in the symbol grounding problem. In this paper, we leverage the implicit knowledge within foundation models to enhance the performance in NeSy tasks, whilst reducing the amount of data labelling and manual engineering. We introduce a new architecture, called NeSyGPT, which fine-tunes a vision-language foundation model to extract symbolic features from raw data, before learning a highly expressive answer set program to solve a downstream task. Our comprehensive evaluation demonstrates that NeSyGPT has superior accuracy over various baselines, and can scale to complex NeSy tasks. Finally, we highlight the effective use of a large language model to generate the programmatic interface between the neural and symbolic components, significantly reducing the amount of manual engineering required.

{{</citation>}}


### (124/175) Foundation Model Sherpas: Guiding Foundation Models through Knowledge and Reasoning (Debarun Bhattacharjya et al., 2024)

{{<citation>}}

Debarun Bhattacharjya, Junkyu Lee, Don Joven Agravante, Balaji Ganesan, Radu Marinescu. (2024)  
**Foundation Model Sherpas: Guiding Foundation Models through Knowledge and Reasoning**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI, Reasoning  
[Paper Link](http://arxiv.org/abs/2402.01602v1)  

---


**ABSTRACT**  
Foundation models (FMs) such as large language models have revolutionized the field of AI by showing remarkable performance in various tasks. However, they exhibit numerous limitations that prevent their broader adoption in many real-world systems, which often require a higher bar for trustworthiness and usability. Since FMs are trained using loss functions aimed at reconstructing the training corpus in a self-supervised manner, there is no guarantee that the model's output aligns with users' preferences for a specific task at hand. In this survey paper, we propose a conceptual framework that encapsulates different modes by which agents could interact with FMs and guide them suitably for a set of tasks, particularly through knowledge augmentation and reasoning. Our framework elucidates agent role categories such as updating the underlying FM, assisting with prompting the FM, and evaluating the FM output. We also categorize several state-of-the-art approaches into agent interaction protocols, highlighting the nature and extent of involvement of the various agent roles. The proposed framework provides guidance for future directions to further realize the power of FMs in practical AI systems.

{{</citation>}}


### (125/175) Developing and Evaluating a Design Method for Positive Artificial Intelligence (Willem van der Maden et al., 2024)

{{<citation>}}

Willem van der Maden, Derek Lomas, Paul Hekkert. (2024)  
**Developing and Evaluating a Design Method for Positive Artificial Intelligence**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01499v1)  

---


**ABSTRACT**  
As artificial intelligence (AI) continues advancing, ensuring positive societal impacts becomes critical, especially as AI systems become increasingly ubiquitous in various aspects of life. However, developing "AI for good" poses substantial challenges around aligning systems with complex human values. Presently, we lack mature methods for addressing these challenges. This article presents and evaluates the Positive AI design method aimed at addressing this gap. The method provides a human-centered process to translate wellbeing aspirations into concrete practices. First, we explain the method's four key steps: contextualizing, operationalizing, optimizing, and implementing wellbeing supported by continuous measurement for feedback cycles. We then present a multiple case study where novice designers applied the method, revealing strengths and weaknesses related to efficacy and usability. Next, an expert evaluation study assessed the quality of the resulting concepts, rating them moderately high for feasibility, desirability, and plausibility of achieving intended wellbeing benefits. Together, these studies provide preliminary validation of the method's ability to improve AI design, while surfacing areas needing refinement like developing support for complex steps. Proposed adaptations such as examples and evaluation heuristics could address weaknesses. Further research should examine sustained application over multiple projects. This human-centered approach shows promise for realizing the vision of 'AI for Wellbeing' that does not just avoid harm, but actively benefits humanity.

{{</citation>}}


### (126/175) LLMs Can't Plan, But Can Help Planning in LLM-Modulo Frameworks (Subbarao Kambhampati et al., 2024)

{{<citation>}}

Subbarao Kambhampati, Karthik Valmeekam, Lin Guan, Kaya Stechly, Mudit Verma, Siddhant Bhambri, Lucas Saldyt, Anil Murthy. (2024)  
**LLMs Can't Plan, But Can Help Planning in LLM-Modulo Frameworks**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01817v2)  

---


**ABSTRACT**  
There is considerable confusion about the role of Large Language Models (LLMs) in planning and reasoning tasks. On one side are over-optimistic claims that LLMs can indeed do these tasks with just the right prompting or self-verification strategies. On the other side are perhaps over-pessimistic claims that all that LLMs are good for in planning/reasoning tasks are as mere translators of the problem specification from one syntactic format to another, and ship the problem off to external symbolic solvers. In this position paper, we take the view that both these extremes are misguided. We argue that auto-regressive LLMs cannot, by themselves, do planning or self-verification (which is after all a form of reasoning), and shed some light on the reasons for misunderstandings in the literature. We will also argue that LLMs should be viewed as universal approximate knowledge sources that have much more meaningful roles to play in planning/reasoning tasks beyond simple front-end/back-end format translators. We present a vision of {\bf LLM-Modulo Frameworks} that combine the strengths of LLMs with external model-based verifiers in a tighter bi-directional interaction regime. We will show how the models driving the external verifiers themselves can be acquired with the help of LLMs. We will also argue that rather than simply pipelining LLMs and symbolic components, this LLM-Modulo Framework provides a better neuro-symbolic approach that offers tighter integration between LLMs and symbolic components, and allows extending the scope of model-based planning/reasoning regimes towards more flexible knowledge, problem and preference specifications.

{{</citation>}}


### (127/175) Towards the new XAI: A Hypothesis-Driven Approach to Decision Support Using Evidence (Thao Le et al., 2024)

{{<citation>}}

Thao Le, Tim Miller, Ronal Singh, Liz Sonenberg. (2024)  
**Towards the new XAI: A Hypothesis-Driven Approach to Decision Support Using Evidence**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-HC, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01292v1)  

---


**ABSTRACT**  
Prior research on AI-assisted human decision-making has explored several different explainable AI (XAI) approaches. A recent paper has proposed a paradigm shift calling for hypothesis-driven XAI through a conceptual framework called evaluative AI that gives people evidence that supports or refutes hypotheses without necessarily giving a decision-aid recommendation. In this paper we describe and evaluate an approach for hypothesis-driven XAI based on the Weight of Evidence (WoE) framework, which generates both positive and negative evidence for a given hypothesis. Through human behavioural experiments, we show that our hypothesis-driven approach increases decision accuracy, reduces reliance compared to a recommendation-driven approach and an AI-explanation-only baseline, but with a small increase in under-reliance compared to the recommendation-driven approach. Further, we show that participants used our hypothesis-driven approach in a materially different way to the two baselines.

{{</citation>}}


### (128/175) PokéLLMon: A Human-Parity Agent for Pokémon Battles with Large Language Models (Sihao Hu et al., 2024)

{{<citation>}}

Sihao Hu, Tiansheng Huang, Ling Liu. (2024)  
**PokéLLMon: A Human-Parity Agent for Pokémon Battles with Large Language Models**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01118v1)  

---


**ABSTRACT**  
We introduce \textsc{Pok\'eLLMon}, the first LLM-embodied agent that achieves human-parity performance in tactical battle games, as demonstrated in Pok\'emon battles. The design of \textsc{Pok\'eLLMon} incorporates three key strategies: (i) In-context reinforcement learning that instantly consumes text-based feedback derived from battles to iteratively refine the policy; (ii) Knowledge-augmented generation that retrieves external knowledge to counteract hallucination and enables the agent to act timely and properly; (iii) Consistent action generation to mitigate the \textit{panic switching} phenomenon when the agent faces a powerful opponent and wants to elude the battle. We show that online battles against human demonstrates \textsc{Pok\'eLLMon}'s human-like battle strategies and just-in-time decision making, achieving 49\% of win rate in the Ladder competitions and 56\% of win rate in the invited battles. Our implementation and playable battle logs are available at: \url{https://github.com/git-disl/PokeLLMon}.

{{</citation>}}


## cs.CY (5)



### (129/175) (A)I Am Not a Lawyer, But...: Engaging Legal Experts towards Responsible LLM Policies for Legal Advice (Inyoung Cheong et al., 2024)

{{<citation>}}

Inyoung Cheong, King Xia, K. J. Kevin Feng, Quan Ze Chen, Amy X. Zhang. (2024)  
**(A)I Am Not a Lawyer, But...: Engaging Legal Experts towards Responsible LLM Policies for Legal Advice**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs.CY  
Keywords: AI, Legal  
[Paper Link](http://arxiv.org/abs/2402.01864v1)  

---


**ABSTRACT**  
The rapid proliferation of large language models (LLMs) as general purpose chatbots available to the public raises hopes around expanding access to professional guidance in law, medicine, and finance, while triggering concerns about public reliance on LLMs for high-stakes circumstances. Prior research has speculated on high-level ethical considerations but lacks concrete criteria determining when and why LLM chatbots should or should not provide professional assistance. Through examining the legal domain, we contribute a structured expert analysis to uncover nuanced policy considerations around using LLMs for professional advice, using methods inspired by case-based reasoning. We convened workshops with 20 legal experts and elicited dimensions on appropriate AI assistance for sample user queries (``cases''). We categorized our expert dimensions into: (1) user attributes, (2) query characteristics, (3) AI capabilities, and (4) impacts. Beyond known issues like hallucinations, experts revealed novel legal problems, including that users' conversations with LLMs are not protected by attorney-client confidentiality or bound to professional ethics that guard against conflicted counsel or poor quality advice. This accountability deficit led participants to advocate for AI systems to help users polish their legal questions and relevant facts, rather than recommend specific actions. More generally, we highlight the potential of case-based expert deliberation as a method of responsibly translating professional integrity and domain knowledge into design requirements to inform appropriate AI behavior when generating advice in professional domains.

{{</citation>}}


### (130/175) Generative AI for Education (GAIED): Advances, Opportunities, and Challenges (Paul Denny et al., 2024)

{{<citation>}}

Paul Denny, Sumit Gulwani, Neil T. Heffernan, Tanja Käser, Steven Moore, Anna N. Rafferty, Adish Singla. (2024)  
**Generative AI for Education (GAIED): Advances, Opportunities, and Challenges**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs.CY  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2402.01580v2)  

---


**ABSTRACT**  
This survey article has grown out of the GAIED (pronounced "guide") workshop organized by the authors at the NeurIPS 2023 conference. We organized the GAIED workshop as part of a community-building effort to bring together researchers, educators, and practitioners to explore the potential of generative AI for enhancing education. This article aims to provide an overview of the workshop activities and highlight several future research directions in the area of GAIED.

{{</citation>}}


### (131/175) Deep Active Learning for Data Mining from Conflict Text Corpora (Mihai Croicu, 2024)

{{<citation>}}

Mihai Croicu. (2024)  
**Deep Active Learning for Data Mining from Conflict Text Corpora**  

---
Primary Category: cs.CY  
Categories: cs-CL, cs-CY, cs.CY, stat-ML  
Keywords: Active Learning  
[Paper Link](http://arxiv.org/abs/2402.01577v1)  

---


**ABSTRACT**  
High-resolution event data on armed conflict and related processes have revolutionized the study of political contention with datasets like UCDP GED, ACLED etc. However, most of these datasets limit themselves to collecting spatio-temporal (high-resolution) and intensity data. Information on dynamics, such as targets, tactics, purposes etc. are rarely collected owing to the extreme workload of collecting data. However, most datasets rely on a rich corpus of textual data allowing further mining of further information connected to each event. This paper proposes one such approach that is inexpensive and high performance, leveraging active learning - an iterative process of improving a machine learning model based on sequential (guided) human input. Active learning is employed to then step-wise train (fine-tuning) of a large, encoder-only language model adapted for extracting sub-classes of events relating to conflict dynamics. The approach shows performance similar to human (gold-standard) coding while reducing the amount of required human annotation by as much as 99%.

{{</citation>}}


### (132/175) An Educational Tool for Learning about Social Media Tracking, Profiling, and Recommendation (Nicolas Pope et al., 2024)

{{<citation>}}

Nicolas Pope, Juho Kahila, Jari Laru, Henriikka Vartiainen, Teemu Roos, Matti Tedre. (2024)  
**An Educational Tool for Learning about Social Media Tracking, Profiling, and Recommendation**  

---
Primary Category: cs.CY  
Categories: cs-CY, cs.CY  
Keywords: AI, Social Media  
[Paper Link](http://arxiv.org/abs/2402.01813v1)  

---


**ABSTRACT**  
This paper introduces an educational tool for classroom use, based on explainable AI (XAI), designed to demystify key social media mechanisms - tracking, profiling, and content recommendation - for novice learners. The tool provides a familiar, interactive interface that resonates with learners' experiences with popular social media platforms, while also offering the means to "peek under the hood" and exposing basic mechanisms of datafication. Learners gain first-hand experience of how even the slightest actions, such as pausing to view content, are captured and recorded in their digital footprint, and further distilled into a personal profile. The tool uses real-time visualizations and verbal explanations to create a sense of immediacy: each time the user acts, the resulting changes in their engagement history and their profile are displayed in a visually engaging and understandable manner. This paper discusses the potential of XAI and educational technology in transforming data and digital literacy education and in fostering the growth of children's privacy and security mindsets.

{{</citation>}}


### (133/175) The Political Preferences of LLMs (David Rozado, 2024)

{{<citation>}}

David Rozado. (2024)  
**The Political Preferences of LLMs**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CL, cs-CY, cs.CY  
Keywords: Language Model, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01789v1)  

---


**ABSTRACT**  
We report here a comprehensive analysis about the political preferences embedded in Large Language Models (LLMs). Namely, we administer 11 political orientation tests, designed to identify the political preferences of the test taker, to 24 state-of-the-art conversational LLMs, both close and open source. The results indicate that when probed with questions/statements with political connotations most conversational LLMs tend to generate responses that are diagnosed by most political test instruments as manifesting preferences for left-of-center viewpoints. We note that this is not the case for base (i.e. foundation) models upon which LLMs optimized for conversation with humans are built. However, base models' suboptimal performance at coherently answering questions suggests caution when interpreting their classification by political orientation tests. Though not conclusive, our results provide preliminary evidence for the intriguing hypothesis that the embedding of political preferences into LLMs might be happening mostly post-pretraining. Namely, during the supervised fine-tuning (SFT) and/or Reinforcement Learning (RL) stages of the conversational LLMs training pipeline. We provide further support for this hypothesis by showing that LLMs are easily steerable into target locations of the political spectrum via SFT requiring only modest compute and custom data, illustrating the ability of SFT to imprint political preferences onto LLMs. As LLMs have started to displace more traditional information sources such as search engines or Wikipedia, the implications of political biases embedded in LLMs has important societal ramifications.

{{</citation>}}


## cs.SD (6)



### (134/175) Audio Flamingo: A Novel Audio Language Model with Few-Shot Learning and Dialogue Abilities (Zhifeng Kong et al., 2024)

{{<citation>}}

Zhifeng Kong, Arushi Goel, Rohan Badlani, Wei Ping, Rafael Valle, Bryan Catanzaro. (2024)  
**Audio Flamingo: A Novel Audio Language Model with Few-Shot Learning and Dialogue Abilities**  

---
Primary Category: cs.SD  
Categories: cs-LG, cs-SD, cs.SD, eess-AS  
Keywords: Dialog, Dialogue, Few-Shot, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01831v1)  

---


**ABSTRACT**  
Augmenting large language models (LLMs) to understand audio -- including non-speech sounds and non-verbal speech -- is critically important for diverse real-world applications of LLMs. In this paper, we propose Audio Flamingo, a novel audio language model with 1) strong audio understanding abilities, 2) the ability to quickly adapt to unseen tasks via in-context learning and retrieval, and 3) strong multi-turn dialogue abilities. We introduce a series of training techniques, architecture design, and data strategies to enhance our model with these abilities. Extensive evaluations across various audio understanding tasks confirm the efficacy of our method, setting new state-of-the-art benchmarks.

{{</citation>}}


### (135/175) Low-Resource Cross-Domain Singing Voice Synthesis via Reduced Self-Supervised Speech Representations (Panos Kakoulidis et al., 2024)

{{<citation>}}

Panos Kakoulidis, Nikolaos Ellinas, Georgios Vamvoukakis, Myrsini Christidou, Alexandra Vioni, Georgia Maniati, Junkwang Oh, Gunu Jho, Inchul Hwang, Pirros Tsiakoulis, Aimilios Chalamandaris. (2024)  
**Low-Resource Cross-Domain Singing Voice Synthesis via Reduced Self-Supervised Speech Representations**  

---
Primary Category: cs.SD  
Categories: cs-LG, cs-SD, cs.SD, eess-AS  
Keywords: Low-Resource, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2402.01520v1)  

---


**ABSTRACT**  
In this paper, we propose a singing voice synthesis model, Karaoker-SSL, that is trained only on text and speech data as a typical multi-speaker acoustic model. It is a low-resource pipeline that does not utilize any singing data end-to-end, since its vocoder is also trained on speech data. Karaoker-SSL is conditioned by self-supervised speech representations in an unsupervised manner. We preprocess these representations by selecting only a subset of their task-correlated dimensions. The conditioning module is indirectly guided to capture style information during training by multi-tasking. This is achieved with a Conformer-based module, which predicts the pitch from the acoustic model's output. Thus, Karaoker-SSL allows singing voice synthesis without reliance on hand-crafted and domain-specific features. There are also no requirements for text alignments or lyrics timestamps. To refine the voice quality, we employ a U-Net discriminator that is conditioned on the target speaker and follows a Diffusion GAN training scheme.

{{</citation>}}


### (136/175) A Data-Driven Analysis of Robust Automatic Piano Transcription (Drew Edwards et al., 2024)

{{<citation>}}

Drew Edwards, Simon Dixon, Emmanouil Benetos, Akira Maezawa, Yuta Kusaka. (2024)  
**A Data-Driven Analysis of Robust Automatic Piano Transcription**  

---
Primary Category: cs.SD  
Categories: cs-LG, cs-SD, cs.SD, eess-AS  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2402.01424v1)  

---


**ABSTRACT**  
Algorithms for automatic piano transcription have improved dramatically in recent years due to new datasets and modeling techniques. Recent developments have focused primarily on adapting new neural network architectures, such as the Transformer and Perceiver, in order to yield more accurate systems. In this work, we study transcription systems from the perspective of their training data. By measuring their performance on out-of-distribution annotated piano data, we show how these models can severely overfit to acoustic properties of the training data. We create a new set of audio for the MAESTRO dataset, captured automatically in a professional studio recording environment via Yamaha Disklavier playback. Using various data augmentation techniques when training with the original and re-performed versions of the MAESTRO dataset, we achieve state-of-the-art note-onset accuracy of 88.4 F1-score on the MAPS dataset, without seeing any of its training data. We subsequently analyze these data augmentation techniques in a series of ablation studies to better understand their influence on the resulting models.

{{</citation>}}


### (137/175) Bass Accompaniment Generation via Latent Diffusion (Marco Pasini et al., 2024)

{{<citation>}}

Marco Pasini, Maarten Grachten, Stefan Lattner. (2024)  
**Bass Accompaniment Generation via Latent Diffusion**  

---
Primary Category: cs.SD  
Categories: cs-LG, cs-SD, cs.SD, eess-AS  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01412v1)  

---


**ABSTRACT**  
The ability to automatically generate music that appropriately matches an arbitrary input track is a challenging task. We present a novel controllable system for generating single stems to accompany musical mixes of arbitrary length. At the core of our method are audio autoencoders that efficiently compress audio waveform samples into invertible latent representations, and a conditional latent diffusion model that takes as input the latent encoding of a mix and generates the latent encoding of a corresponding stem. To provide control over the timbre of generated samples, we introduce a technique to ground the latent space to a user-provided reference style during diffusion sampling. For further improving audio quality, we adapt classifier-free guidance to avoid distortions at high guidance strengths when generating an unbounded latent space. We train our model on a dataset of pairs of mixes and matching bass stems. Quantitative experiments demonstrate that, given an input mix, the proposed system can generate basslines with user-specified timbres. Our controllable conditional audio generation framework represents a significant step forward in creating generative AI tools to assist musicians in music production.

{{</citation>}}


### (138/175) On the Transferability of Large-Scale Self-Supervision to Few-Shot Audio Classification (Calum Heggan et al., 2024)

{{<citation>}}

Calum Heggan, Sam Budgett, Timothy Hosepedales, Mehrdad Yeghoobi. (2024)  
**On the Transferability of Large-Scale Self-Supervision to Few-Shot Audio Classification**  

---
Primary Category: cs.SD  
Categories: cs-LG, cs-SD, cs.SD, eess-AS  
Keywords: Few-Shot  
[Paper Link](http://arxiv.org/abs/2402.01274v1)  

---


**ABSTRACT**  
In recent years, self-supervised learning has excelled for its capacity to learn robust feature representations from unlabelled data. Networks pretrained through self-supervision serve as effective feature extractors for downstream tasks, including Few-Shot Learning. While the evaluation of unsupervised approaches for few-shot learning is well-established in imagery, it is notably absent in acoustics. This study addresses this gap by assessing large-scale self-supervised models' performance in few-shot audio classification. Additionally, we explore the relationship between a model's few-shot learning capability and other downstream task benchmarks. Our findings reveal state-of-the-art performance in some few-shot problems such as SpeechCommandsv2, as well as strong correlations between speech-based few-shot problems and various downstream audio tasks.

{{</citation>}}


### (139/175) STAA-Net: A Sparse and Transferable Adversarial Attack for Speech Emotion Recognition (Yi Chang et al., 2024)

{{<citation>}}

Yi Chang, Zhao Ren, Zixing Zhang, Xin Jing, Kun Qian, Xi Shao, Bin Hu, Tanja Schultz, Björn W. Schuller. (2024)  
**STAA-Net: A Sparse and Transferable Adversarial Attack for Speech Emotion Recognition**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-HC, cs-SD, cs.SD, eess-AS  
Keywords: Adversarial Attack, Emotion Recognition  
[Paper Link](http://arxiv.org/abs/2402.01227v1)  

---


**ABSTRACT**  
Speech contains rich information on the emotions of humans, and Speech Emotion Recognition (SER) has been an important topic in the area of human-computer interaction. The robustness of SER models is crucial, particularly in privacy-sensitive and reliability-demanding domains like private healthcare. Recently, the vulnerability of deep neural networks in the audio domain to adversarial attacks has become a popular area of research. However, prior works on adversarial attacks in the audio domain primarily rely on iterative gradient-based techniques, which are time-consuming and prone to overfitting the specific threat model. Furthermore, the exploration of sparse perturbations, which have the potential for better stealthiness, remains limited in the audio domain. To address these challenges, we propose a generator-based attack method to generate sparse and transferable adversarial examples to deceive SER models in an end-to-end and efficient manner. We evaluate our method on two widely-used SER datasets, Database of Elicited Mood in Speech (DEMoS) and Interactive Emotional dyadic MOtion CAPture (IEMOCAP), and demonstrate its ability to generate successful sparse adversarial examples in an efficient manner. Moreover, our generated adversarial examples exhibit model-agnostic transferability, enabling effective adversarial attacks on advanced victim models.

{{</citation>}}


## q-bio.BM (1)



### (140/175) Predicting ATP binding sites in protein sequences using Deep Learning and Natural Language Processing (Shreyas V et al., 2024)

{{<citation>}}

Shreyas V, Swati Agarwal. (2024)  
**Predicting ATP binding sites in protein sequences using Deep Learning and Natural Language Processing**  

---
Primary Category: q-bio.BM  
Categories: cs-CL, cs-LG, q-bio-BM, q-bio.BM  
Keywords: BERT, NLP, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2402.01829v1)  

---


**ABSTRACT**  
Predicting ATP-Protein Binding sites in genes is of great significance in the field of Biology and Medicine. The majority of research in this field has been conducted through time- and resource-intensive 'wet experiments' in laboratories. Over the years, researchers have been investigating computational methods computational methods to accomplish the same goals, utilising the strength of advanced Deep Learning and NLP algorithms. In this paper, we propose to develop methods to classify ATP-Protein binding sites. We conducted various experiments mainly using PSSMs and several word embeddings as features. We used 2D CNNs and LightGBM classifiers as our chief Deep Learning Algorithms. The MP3Vec and BERT models have also been subjected to testing in our study. The outcomes of our experiments demonstrated improvement over the state-of-the-art benchmarks.

{{</citation>}}


## eess.AS (4)



### (141/175) BAT: Learning to Reason about Spatial Sounds with Large Language Models (Zhisheng Zheng et al., 2024)

{{<citation>}}

Zhisheng Zheng, Puyuan Peng, Ziyang Ma, Xie Chen, Eunsol Choi, David Harwath. (2024)  
**BAT: Learning to Reason about Spatial Sounds with Large Language Models**  

---
Primary Category: eess.AS  
Categories: cs-AI, cs-CL, cs-SD, eess-AS, eess.AS  
Keywords: LLaMA, Language Model, QA, Transformer  
[Paper Link](http://arxiv.org/abs/2402.01591v1)  

---


**ABSTRACT**  
Spatial sound reasoning is a fundamental human skill, enabling us to navigate and interpret our surroundings based on sound. In this paper we present BAT, which combines the spatial sound perception ability of a binaural acoustic scene analysis model with the natural language reasoning capabilities of a large language model (LLM) to replicate this innate ability. To address the lack of existing datasets of in-the-wild spatial sounds, we synthesized a binaural audio dataset using AudioSet and SoundSpaces 2.0. Next, we developed SpatialSoundQA, a spatial sound-based question-answering dataset, offering a range of QA tasks that train BAT in various aspects of spatial sound perception and reasoning. The acoustic front end encoder of BAT is a novel spatial audio encoder named Spatial Audio Spectrogram Transformer, or Spatial-AST, which by itself achieves strong performance across sound event detection, spatial localization, and distance estimation. By integrating Spatial-AST with LLaMA-2 7B model, BAT transcends standard Sound Event Localization and Detection (SELD) tasks, enabling the model to reason about the relationships between the sounds in its environment. Our experiments demonstrate BAT's superior performance on both spatial sound perception and reasoning, showcasing the immense potential of LLMs in navigating and interpreting complex spatial audio environments.

{{</citation>}}


### (142/175) How Paralingual are Paralinguistic Representations? A Case Study in Speech Emotion Recognition (Orchid Chetia Phukan et al., 2024)

{{<citation>}}

Orchid Chetia Phukan, Gautam Siddharth Kashyap, Arun Balaji Buduru, Rajesh Sharma. (2024)  
**How Paralingual are Paralinguistic Representations? A Case Study in Speech Emotion Recognition**  

---
Primary Category: eess.AS  
Categories: cs-CL, cs-SD, eess-AS, eess.AS  
Keywords: Emotion Recognition  
[Paper Link](http://arxiv.org/abs/2402.01579v1)  

---


**ABSTRACT**  
Pre-trained Models (PTMs) have facilitated substantial progress in the field of Speech Emotion Recognition (SER). SER is an area with applications ranging from HumanComputer Interaction to Healthcare. Recent studies have leveraged various PTM representations as input features for downstream models for SER. PTM specifically pre-trained for paralinguistic tasks have obtained state-of-the-art (SOTA) performance for SER. However, such PTM haven't been evaluated for SER in multilingual settings and experimented only with English. So, we fill this gap, by performing a comprehensive comparative study of five PTMs (TRILLsson, wav2vec2, XLS-R, x-vector, Whisper) for assessing the effectiveness of paralingual PTM (TRILLsson) for SER across multiple languages. Representations from TRILLsson achieved the best performance among all the PTMs. This demonstrates that TRILLsson is able to effectively capture the various paralinguistic features from speech data for better SER. We also show that downstream models using TRILLsson representations achieve SOTA performance in terms of accuracy across various multi-lingual datasets.

{{</citation>}}


### (143/175) Exploring transfer learning for pathological speech feature prediction: Impact of layer selection (Daniela A. Wiepert et al., 2024)

{{<citation>}}

Daniela A. Wiepert, Rene L. Utianski, Joseph R. Duffy, John L. Stricker, Leland R. Barnard, David T. Jones, Hugo Botha. (2024)  
**Exploring transfer learning for pathological speech feature prediction: Impact of layer selection**  

---
Primary Category: eess.AS  
Categories: cs-CL, cs-LG, eess-AS, eess.AS  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01796v1)  

---


**ABSTRACT**  
There is interest in leveraging AI to conduct automatic, objective assessments of clinical speech, in turn facilitating diagnosis and treatment of speech disorders. We explore transfer learning, focusing on the impact of layer selection, for the downstream task of predicting the presence of pathological speech. We find that selecting an optimal layer offers large performance improvements (12.4% average increase in balanced accuracy), though the best layer varies by predicted feature and does not always generalize well to unseen data. A learned weighted sum offers comparable performance to the average best layer in-distribution and has better generalization for out-of-distribution data.

{{</citation>}}


### (144/175) Evaluation of Google's Voice Recognition and Sentence Classification for Health Care Applications (Majbah Uddin et al., 2024)

{{<citation>}}

Majbah Uddin, Nathan Huynh, Jose M Vidal, Kevin M Taaffe, Lawrence D Fredendall, Joel S Greenstein. (2024)  
**Evaluation of Google's Voice Recognition and Sentence Classification for Health Care Applications**  

---
Primary Category: eess.AS  
Categories: cs-CL, cs-LG, cs-SD, eess-AS, eess.AS  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2402.03369v1)  

---


**ABSTRACT**  
This study examined the use of voice recognition technology in perioperative services (Periop) to enable Periop staff to record workflow milestones using mobile technology. The use of mobile technology to improve patient flow and quality of care could be facilitated if such voice recognition technology could be made robust. The goal of this experiment was to allow the Periop staff to provide care without being interrupted with data entry and querying tasks. However, the results are generalizable to other situations where an engineering manager attempts to improve communication performance using mobile technology. This study enhanced Google's voice recognition capability by using post-processing classifiers (i.e., bag-of-sentences, support vector machine, and maximum entropy). The experiments investigated three factors (original phrasing, reduced phrasing, and personalized phrasing) at three levels (zero training repetition, 5 training repetitions, and 10 training repetitions). Results indicated that personal phrasing yielded the highest correctness and that training the device to recognize an individual's voice improved correctness as well. Although simplistic, the bag-of-sentences classifier significantly improved voice recognition correctness. The classification efficiency of the maximum entropy and support vector machine algorithms was found to be nearly identical. These results suggest that engineering managers could significantly enhance Google's voice recognition technology by using post-processing techniques, which would facilitate its use in health care and other applications.

{{</citation>}}


## cs.CV (18)



### (145/175) SLYKLatent, a Learning Framework for Facial Features Estimation (Samuel Adebayo et al., 2024)

{{<citation>}}

Samuel Adebayo, Joost C. Dessing, Seán McLoone. (2024)  
**SLYKLatent, a Learning Framework for Facial Features Estimation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-HC, cs.CV, eess-IV  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2402.01555v1)  

---


**ABSTRACT**  
In this research, we present SLYKLatent, a novel approach for enhancing gaze estimation by addressing appearance instability challenges in datasets due to aleatoric uncertainties, covariant shifts, and test domain generalization. SLYKLatent utilizes Self-Supervised Learning for initial training with facial expression datasets, followed by refinement with a patch-based tri-branch network and an inverse explained variance-weighted training loss function. Our evaluation on benchmark datasets achieves an 8.7% improvement on Gaze360, rivals top MPIIFaceGaze results, and leads on a subset of ETH-XGaze by 13%, surpassing existing methods by significant margins. Adaptability tests on RAF-DB and Affectnet show 86.4% and 60.9% accuracies, respectively. Ablation studies confirm the effectiveness of SLYKLatent's novel components. This approach has strong potential in human-robot interaction.

{{</citation>}}


### (146/175) Cross-view Masked Diffusion Transformers for Person Image Synthesis (Trung X. Pham et al., 2024)

{{<citation>}}

Trung X. Pham, Zhang Kang, Chang D. Yoo. (2024)  
**Cross-view Masked Diffusion Transformers for Person Image Synthesis**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2402.01516v1)  

---


**ABSTRACT**  
We present X-MDPT (Cross-view Masked Diffusion Prediction Transformers), a novel diffusion model designed for pose-guided human image generation. X-MDPT distinguishes itself by employing masked diffusion transformers that operate on latent patches, a departure from the commonly-used Unet structures in existing works. The model comprises three key modules: 1) a denoising diffusion Transformer, 2) an aggregation network that consolidates conditions into a single vector for the diffusion process, and 3) a mask cross-prediction module that enhances representation learning with semantic information from the reference image. X-MDPT demonstrates scalability, improving FID, SSIM, and LPIPS with larger models. Despite its simple design, our model outperforms state-of-the-art approaches on the DeepFashion dataset while exhibiting efficiency in terms of training parameters, training time, and inference speed. Our compact 33MB model achieves an FID of 7.42, surpassing a prior Unet latent diffusion approach (FID 8.07) using only $11\times$ fewer parameters. Our best model surpasses the pixel-based diffusion with $\frac{2}{3}$ of the parameters and achieves $5.43 \times$ faster inference.

{{</citation>}}


### (147/175) Synthetic Data for the Mitigation of Demographic Biases in Face Recognition (Pietro Melzi et al., 2024)

{{<citation>}}

Pietro Melzi, Christian Rathgeb, Ruben Tolosana, Ruben Vera-Rodriguez, Aythami Morales, Dominik Lawatsch, Florian Domin, Maxim Schaubert. (2024)  
**Synthetic Data for the Mitigation of Demographic Biases in Face Recognition**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2402.01472v1)  

---


**ABSTRACT**  
This study investigates the possibility of mitigating the demographic biases that affect face recognition technologies through the use of synthetic data. Demographic biases have the potential to impact individuals from specific demographic groups, and can be identified by observing disparate performance of face recognition systems across demographic groups. They primarily arise from the unequal representations of demographic groups in the training data. In recent times, synthetic data have emerged as a solution to some problems that affect face recognition systems. In particular, during the generation process it is possible to specify the desired demographic and facial attributes of images, in order to control the demographic distribution of the synthesized dataset, and fairly represent the different demographic groups. We propose to fine-tune with synthetic data existing face recognition systems that present some demographic biases. We use synthetic datasets generated with GANDiffFace, a novel framework able to synthesize datasets for face recognition with controllable demographic distribution and realistic intra-class variations. We consider multiple datasets representing different demographic groups for training and evaluation. Also, we fine-tune different face recognition systems, and evaluate their demographic fairness with different metrics. Our results support the proposed approach and the use of synthetic data to mitigate demographic biases in face recognition.

{{</citation>}}


### (148/175) XAI for Skin Cancer Detection with Prototypes and Non-Expert Supervision (Miguel Correia et al., 2024)

{{<citation>}}

Miguel Correia, Alceu Bissoto, Carlos Santiago, Catarina Barata. (2024)  
**XAI for Skin Cancer Detection with Prototypes and Non-Expert Supervision**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01410v1)  

---


**ABSTRACT**  
Skin cancer detection through dermoscopy image analysis is a critical task. However, existing models used for this purpose often lack interpretability and reliability, raising the concern of physicians due to their black-box nature. In this paper, we propose a novel approach for the diagnosis of melanoma using an interpretable prototypical-part model. We introduce a guided supervision based on non-expert feedback through the incorporation of: 1) binary masks, obtained automatically using a segmentation network; and 2) user-refined prototypes. These two distinct information pathways aim to ensure that the learned prototypes correspond to relevant areas within the skin lesion, excluding confounding factors beyond its boundaries. Experimental results demonstrate that, even without expert supervision, our approach achieves superior performance and generalization compared to non-interpretable models.

{{</citation>}}


### (149/175) ALERT-Transformer: Bridging Asynchronous and Synchronous Machine Learning for Real-Time Event-based Spatio-Temporal Data (Carmen Martin-Turrero et al., 2024)

{{<citation>}}

Carmen Martin-Turrero, Maxence Bouvier, Manuel Breitenstein, Pietro Zanuttigh, Vincent Parret. (2024)  
**ALERT-Transformer: Bridging Asynchronous and Synchronous Machine Learning for Real-Time Event-based Spatio-Temporal Data**  

---
Primary Category: cs.CV  
Categories: 68T05, I-2-6; I-2-10; I-4-8; I-4-10; D-2-2; D-1-4, cs-CV, cs-LG, cs-NE, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2402.01393v2)  

---


**ABSTRACT**  
We seek to enable classic processing of continuous ultra-sparse spatiotemporal data generated by event-based sensors with dense machine learning models. We propose a novel hybrid pipeline composed of asynchronous sensing and synchronous processing that combines several ideas: (1) an embedding based on PointNet models -- the ALERT module -- that can continuously integrate new and dismiss old events thanks to a leakage mechanism, (2) a flexible readout of the embedded data that allows to feed any downstream model with always up-to-date features at any sampling rate, (3) exploiting the input sparsity in a patch-based approach inspired by Vision Transformer to optimize the efficiency of the method. These embeddings are then processed by a transformer model trained for object and gesture recognition. Using this approach, we achieve performances at the state-of-the-art with a lower latency than competitors. We also demonstrate that our asynchronous model can operate at any desired sampling rate.

{{</citation>}}


### (150/175) LIR: Efficient Degradation Removal for Lightweight Image Restoration (Dongqi Fan et al., 2024)

{{<citation>}}

Dongqi Fan, Ting Yue, Xin Zhao, Liang Chang. (2024)  
**LIR: Efficient Degradation Removal for Lightweight Image Restoration**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2402.01368v1)  

---


**ABSTRACT**  
Recently, there have been significant advancements in Image Restoration based on CNN and transformer. However, the inherent characteristics of the Image Restoration task are often overlooked in many works. These works often focus on the basic block design and stack numerous basic blocks to the model, leading to redundant parameters and unnecessary computations and hindering the efficiency of the image restoration. In this paper, we propose a Lightweight Image Restoration network called LIR to efficiently remove degradation (blur, rain, noise, haze, etc.). A key component in LIR is the Efficient Adaptive Attention (EAA) Block, which is mainly composed of Adaptive Filters and Attention Blocks. It is capable of adaptively sharpening contours, removing degradation, and capturing global information in various image restoration scenes in an efficient and computation-friendly manner. In addition, through a simple structural design, LIR addresses the degradations existing in the local and global residual connections that are ignored by modern networks. Extensive experiments demonstrate that our LIR achieves comparable performance to state-of-the-art networks on most benchmarks with fewer parameters and computations. It is worth noting that our LIR produces better visual results than state-of-the-art networks that are more in line with the human aesthetic.

{{</citation>}}


### (151/175) FindingEmo: An Image Dataset for Emotion Recognition in the Wild (Laurent Mertens et al., 2024)

{{<citation>}}

Laurent Mertens, Elahe' Yargholi, Hans Op de Beeck, Jan Van den Stock, Joost Vennekens. (2024)  
**FindingEmo: An Image Dataset for Emotion Recognition in the Wild**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Emotion Recognition  
[Paper Link](http://arxiv.org/abs/2402.01355v1)  

---


**ABSTRACT**  
We introduce FindingEmo, a new image dataset containing annotations for 25k images, specifically tailored to Emotion Recognition. Contrary to existing datasets, it focuses on complex scenes depicting multiple people in various naturalistic, social settings, with images being annotated as a whole, thereby going beyond the traditional focus on faces or single individuals. Annotated dimensions include Valence, Arousal and Emotion label, with annotations gathered using Prolific. Together with the annotations, we release the list of URLs pointing to the original images, as well as all associated source code.

{{</citation>}}


### (152/175) Skip \n: A Simple Method to Reduce Hallucination in Large Vision-Language Models (Zongbo Han et al., 2024)

{{<citation>}}

Zongbo Han, Zechen Bai, Haiyang Mei, Qianli Xu, Changqing Zhang, Mike Zheng Shou. (2024)  
**Skip \n: A Simple Method to Reduce Hallucination in Large Vision-Language Models**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CL, cs-CV, cs-LG, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01345v3)  

---


**ABSTRACT**  
Recent advancements in large vision-language models (LVLMs) have demonstrated impressive capability in visual information understanding with human language. Despite these advances, LVLMs still face challenges with multimodal hallucination, such as generating text descriptions of objects that are not present in the visual information. However, the underlying fundamental reasons of multimodal hallucinations remain poorly explored. In this paper, we propose a new perspective, suggesting that the inherent biases in LVLMs might be a key factor in hallucinations. Specifically, we systematically identify a semantic shift bias related to paragraph breaks (\n\n), where the content before and after '\n\n' in the training data frequently exhibit significant semantic changes. This pattern leads the model to infer that the contents following '\n\n' should be obviously different from the preceding contents with less hallucinatory descriptions, thereby increasing the probability of hallucinatory descriptions subsequent to the '\n\n'. We have validated this hypothesis on multiple publicly available LVLMs. Besides, we find that deliberately inserting '\n\n' at the generated description can induce more hallucinations. A simple method is proposed to effectively mitigate the hallucination of LVLMs by skipping the output of '\n'.

{{</citation>}}


### (153/175) Phrase Grounding-based Style Transfer for Single-Domain Generalized Object Detection (Hao Li et al., 2024)

{{<citation>}}

Hao Li, Wei Wang, Cong Wang, Zhigang Luo, Xinwang Liu, Kenli Li, Xiaochun Cao. (2024)  
**Phrase Grounding-based Style Transfer for Single-Domain Generalized Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection, Style Transfer  
[Paper Link](http://arxiv.org/abs/2402.01304v2)  

---


**ABSTRACT**  
Single-domain generalized object detection aims to enhance a model's generalizability to multiple unseen target domains using only data from a single source domain during training. This is a practical yet challenging task as it requires the model to address domain shift without incorporating target domain data into training. In this paper, we propose a novel phrase grounding-based style transfer (PGST) approach for the task. Specifically, we first define textual prompts to describe potential objects for each unseen target domain. Then, we leverage the grounded language-image pre-training (GLIP) model to learn the style of these target domains and achieve style transfer from the source to the target domain. The style-transferred source visual features are semantically rich and could be close to imaginary counterparts in the target domain. Finally, we employ these style-transferred visual features to fine-tune GLIP. By introducing imaginary counterparts, the detector could be effectively generalized to unseen target domains using only a single source domain for training. Extensive experimental results on five diverse weather driving benchmarks demonstrate our proposed approach achieves state-of-the-art performance, even surpassing some domain adaptive methods that incorporate target domain images into the training process.The source codes and pre-trained models will be made available.

{{</citation>}}


### (154/175) Spiking CenterNet: A Distillation-boosted Spiking Neural Network for Object Detection (Lennard Bodden et al., 2024)

{{<citation>}}

Lennard Bodden, Franziska Schwaiger, Duc Bach Ha, Lars Kreuzberg, Sven Behnke. (2024)  
**Spiking CenterNet: A Distillation-boosted Spiking Neural Network for Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs-NE, cs.CV  
Keywords: AI, Object Detection  
[Paper Link](http://arxiv.org/abs/2402.01287v1)  

---


**ABSTRACT**  
In the era of AI at the edge, self-driving cars, and climate change, the need for energy-efficient, small, embedded AI is growing. Spiking Neural Networks (SNNs) are a promising approach to address this challenge, with their event-driven information flow and sparse activations. We propose Spiking CenterNet for object detection on event data. It combines an SNN CenterNet adaptation with an efficient M2U-Net-based decoder. Our model significantly outperforms comparable previous work on Prophesee's challenging GEN1 Automotive Detection Dataset while using less than half the energy. Distilling the knowledge of a non-spiking teacher into our SNN further increases performance. To the best of our knowledge, our work is the first approach that takes advantage of knowledge distillation in the field of spiking object detection.

{{</citation>}}


### (155/175) Spectrum-guided Feature Enhancement Network for Event Person Re-Identification (Hongchen Tan et al., 2024)

{{<citation>}}

Hongchen Tan, Yi Zhang, Xiuping Liu, Baocai Yin, Nan Ma, Xin Li, Huchuan Lu. (2024)  
**Spectrum-guided Feature Enhancement Network for Event Person Re-Identification**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2402.01269v1)  

---


**ABSTRACT**  
As a cutting-edge biosensor, the event camera holds significant potential in the field of computer vision, particularly regarding privacy preservation. However, compared to traditional cameras, event streams often contain noise and possess extremely sparse semantics, posing a formidable challenge for event-based person re-identification (event Re-ID). To address this, we introduce a novel event person re-identification network: the Spectrum-guided Feature Enhancement Network (SFE-Net). This network consists of two innovative components: the Multi-grain Spectrum Attention Mechanism (MSAM) and the Consecutive Patch Dropout Module (CPDM). MSAM employs a fourier spectrum transform strategy to filter event noise, while also utilizing an event-guided multi-granularity attention strategy to enhance and capture discriminative person semantics. CPDM employs a consecutive patch dropout strategy to generate multiple incomplete feature maps, encouraging the deep Re-ID model to equally perceive each effective region of the person's body and capture robust person descriptors. Extensive experiments on Event Re-ID datasets demonstrate that our SFE-Net achieves the best performance in this task.

{{</citation>}}


### (156/175) Can Shape-Infused Joint Embeddings Improve Image-Conditioned 3D Diffusion? (Cristian Sbrolli et al., 2024)

{{<citation>}}

Cristian Sbrolli, Paolo Cudrano, Matteo Matteucci. (2024)  
**Can Shape-Infused Joint Embeddings Improve Image-Conditioned 3D Diffusion?**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2402.01241v1)  

---


**ABSTRACT**  
Recent advancements in deep generative models, particularly with the application of CLIP (Contrastive Language Image Pretraining) to Denoising Diffusion Probabilistic Models (DDPMs), have demonstrated remarkable effectiveness in text to image generation. The well structured embedding space of CLIP has also been extended to image to shape generation with DDPMs, yielding notable results. Despite these successes, some fundamental questions arise: Does CLIP ensure the best results in shape generation from images? Can we leverage conditioning to bring explicit 3D knowledge into the generative process and obtain better quality? This study introduces CISP (Contrastive Image Shape Pre training), designed to enhance 3D shape synthesis guided by 2D images. CISP aims to enrich the CLIP framework by aligning 2D images with 3D shapes in a shared embedding space, specifically capturing 3D characteristics potentially overlooked by CLIP's text image focus. Our comprehensive analysis assesses CISP's guidance performance against CLIP guided models, focusing on generation quality, diversity, and coherence of the produced shapes with the conditioning image. We find that, while matching CLIP in generation quality and diversity, CISP substantially improves coherence with input images, underscoring the value of incorporating 3D knowledge into generative models. These findings suggest a promising direction for advancing the synthesis of 3D visual content by integrating multimodal systems with 3D representations.

{{</citation>}}


### (157/175) Delving into Decision-based Black-box Attacks on Semantic Segmentation (Zhaoyu Chen et al., 2024)

{{<citation>}}

Zhaoyu Chen, Zhengyang Shan, Jingwen Chang, Kaixun Jiang, Dingkang Yang, Yiting Cheng, Wenqiang Zhang. (2024)  
**Delving into Decision-based Black-box Attacks on Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CR, cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2402.01220v1)  

---


**ABSTRACT**  
Semantic segmentation is a fundamental visual task that finds extensive deployment in applications with security-sensitive considerations. Nonetheless, recent work illustrates the adversarial vulnerability of semantic segmentation models to white-box attacks. However, its adversarial robustness against black-box attacks has not been fully explored. In this paper, we present the first exploration of black-box decision-based attacks on semantic segmentation. First, we analyze the challenges that semantic segmentation brings to decision-based attacks through the case study. Then, to address these challenges, we first propose a decision-based attack on semantic segmentation, called Discrete Linear Attack (DLA). Based on random search and proxy index, we utilize the discrete linear noises for perturbation exploration and calibration to achieve efficient attack efficiency. We conduct adversarial robustness evaluation on 5 models from Cityscapes and ADE20K under 8 attacks. DLA shows its formidable power on Cityscapes by dramatically reducing PSPNet's mIoU from an impressive 77.83% to a mere 2.14% with just 50 queries.

{{</citation>}}


### (158/175) Faster Inference of Integer SWIN Transformer by Removing the GELU Activation (Mohammadreza Tayaranian et al., 2024)

{{<citation>}}

Mohammadreza Tayaranian, Seyyed Hasan Mozafari, James J. Clark, Brett Meyer, Warren Gross. (2024)  
**Faster Inference of Integer SWIN Transformer by Removing the GELU Activation**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: ImageNet, Transformer  
[Paper Link](http://arxiv.org/abs/2402.01169v1)  

---


**ABSTRACT**  
SWIN transformer is a prominent vision transformer model that has state-of-the-art accuracy in image classification tasks. Despite this success, its unique architecture causes slower inference compared with similar deep neural networks. Integer quantization of the model is one of the methods used to improve its inference latency. However, state-of-the-art has not been able to fully quantize the model. In this work, we improve upon the inference latency of the state-of-the-art methods by removing the floating-point operations, which are associated with the GELU activation in Swin Transformer. While previous work proposed to replace the non-integer operations with linear approximation functions, we propose to replace GELU with ReLU activation. The advantage of ReLU over previous methods is its low memory and computation complexity. We use iterative knowledge distillation to compensate for the lost accuracy due to replacing GELU with ReLU. We quantize our GELU-less SWIN transformer and show that on an RTX 4090 NVIDIA GPU we can improve the inference latency of the quantized SWIN transformer by at least $11\%$ while maintaining an accuracy drop of under $0.5\%$ on the ImageNet evaluation dataset.

{{</citation>}}


### (159/175) A Comprehensive Survey on 3D Content Generation (Jian Liu et al., 2024)

{{<citation>}}

Jian Liu, Xiaoshui Huang, Tianyu Huang, Lu Chen, Yuenan Hou, Shixiang Tang, Ziwei Liu, Wanli Ouyang, Wangmeng Zuo, Junjun Jiang, Xianming Liu. (2024)  
**A Comprehensive Survey on 3D Content Generation**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01166v1)  

---


**ABSTRACT**  
Recent years have witnessed remarkable advances in artificial intelligence generated content(AIGC), with diverse input modalities, e.g., text, image, video, audio and 3D. The 3D is the most close visual modality to real-world 3D environment and carries enormous knowledge. The 3D content generation shows both academic and practical values while also presenting formidable technical challenges. This review aims to consolidate developments within the burgeoning domain of 3D content generation. Specifically, a new taxonomy is proposed that categorizes existing approaches into three types: 3D native generative methods, 2D prior-based 3D generative methods, and hybrid 3D generative methods. The survey covers approximately 60 papers spanning the major techniques. Besides, we discuss limitations of current 3D content generation techniques, and point out open challenges as well as promising directions for future work. Accompanied with this survey, we have established a project website where the resources on 3D content generation research are provided. The project page is available at https://github.com/hitcslj/Awesome-AIGC-3D.

{{</citation>}}


### (160/175) Enhanced Urban Region Profiling with Adversarial Self-Supervised Learning (Weiliang Chan et al., 2024)

{{<citation>}}

Weiliang Chan, Qianqian Ren, Jinbao Li. (2024)  
**Enhanced Urban Region Profiling with Adversarial Self-Supervised Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2402.01163v1)  

---


**ABSTRACT**  
Urban region profiling is pivotal for smart cities, but mining fine-grained semantics from noisy and incomplete urban data remains challenging. In response, we propose a novel self-supervised graph collaborative filtering model for urban region embedding called EUPAS. Specifically, region heterogeneous graphs containing human mobility data, point of interests (POIs) information, and geographic neighborhood details for each region are fed into the model, which generates region embeddings that preserve intra-region and inter-region dependencies through GCNs and multi-head attention. Meanwhile, we introduce spatial perturbation augmentation to generate positive samples that are semantically similar and spatially close to the anchor, preparing for subsequent contrastive learning. Furthermore, adversarial training is employed to construct an effective pretext task by generating strong positive pairs and mining hard negative pairs for the region embeddings. Finally, we jointly optimize supervised and self-supervised learning to encourage the model to capture the high-level semantics of region embeddings while ignoring the noisy and unimportant details. Extensive experiments on real-world datasets demonstrate the superiority of our model over state-of-the-art methods.

{{</citation>}}


### (161/175) 2AFC Prompting of Large Multimodal Models for Image Quality Assessment (Hanwei Zhu et al., 2024)

{{<citation>}}

Hanwei Zhu, Xiangjie Sui, Baoliang Chen, Xuelin Liu, Peilin Chen, Yuming Fang, Shiqi Wang. (2024)  
**2AFC Prompting of Large Multimodal Models for Image Quality Assessment**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2402.01162v1)  

---


**ABSTRACT**  
While abundant research has been conducted on improving high-level visual understanding and reasoning capabilities of large multimodal models~(LMMs), their visual quality assessment~(IQA) ability has been relatively under-explored. Here we take initial steps towards this goal by employing the two-alternative forced choice~(2AFC) prompting, as 2AFC is widely regarded as the most reliable way of collecting human opinions of visual quality. Subsequently, the global quality score of each image estimated by a particular LMM can be efficiently aggregated using the maximum a posterior estimation. Meanwhile, we introduce three evaluation criteria: consistency, accuracy, and correlation, to provide comprehensive quantifications and deeper insights into the IQA capability of five LMMs. Extensive experiments show that existing LMMs exhibit remarkable IQA ability on coarse-grained quality comparison, but there is room for improvement on fine-grained quality discrimination. The proposed dataset sheds light on the future development of IQA models based on LMMs. The codes will be made publicly available at https://github.com/h4nwei/2AFC-LMMs.

{{</citation>}}


### (162/175) A Single Simple Patch is All You Need for AI-generated Image Detection (Jiaxuan Chen et al., 2024)

{{<citation>}}

Jiaxuan Chen, Jieteng Yao, Li Niu. (2024)  
**A Single Simple Patch is All You Need for AI-generated Image Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01123v1)  

---


**ABSTRACT**  
The recent development of generative models unleashes the potential of generating hyper-realistic fake images. To prevent the malicious usage of fake images, AI-generated image detection aims to distinguish fake images from real images. Nevertheless, existing methods usually suffer from poor generalizability across different generators. In this work, we propose an embarrassingly simple approach named SSP, i.e., feeding the noise pattern of a Single Simple Patch (SSP) to a binary classifier, which could achieve 14.6% relative improvement over the recent method on GenImage dataset. Our SSP method is very robust and generalizable, which could serve as a simple and competitive baseline for the future methods.

{{</citation>}}


## physics.chem-ph (1)



### (163/175) Learning Collective Variables for Protein Folding with Labeled Data Augmentation through Geodesic Interpolation (Soojung Yang et al., 2024)

{{<citation>}}

Soojung Yang, Juno Nam, Johannes C. B. Dietschreit, Rafael Gómez-Bombarelli. (2024)  
**Learning Collective Variables for Protein Folding with Labeled Data Augmentation through Geodesic Interpolation**  

---
Primary Category: physics.chem-ph  
Categories: cs-LG, physics-chem-ph, physics.chem-ph, q-bio-BM  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2402.01542v1)  

---


**ABSTRACT**  
In molecular dynamics (MD) simulations, rare events, such as protein folding, are typically studied by means of enhanced sampling techniques, most of which rely on the definition of a collective variable (CV) along which the acceleration occurs. Obtaining an expressive CV is crucial, but often hindered by the lack of information about the particular event, e.g., the transition from unfolded to folded conformation. We propose a simulation-free data augmentation strategy using physics-inspired metrics to generate geodesic interpolations resembling protein folding transitions, thereby improving sampling efficiency without true transition state samples. Leveraging interpolation progress parameters, we introduce a regression-based learning scheme for CV models, which outperforms classifier-based methods when transition state data is limited and noisy

{{</citation>}}


## cs.FL (1)



### (164/175) Backward Responsibility in Transition Systems Using General Power Indices (Christel Baier et al., 2024)

{{<citation>}}

Christel Baier, Roxane van den Bossche, Sascha Klüppelholz, Johannes Lehmann, Jakob Piribauer. (2024)  
**Backward Responsibility in Transition Systems Using General Power Indices**  

---
Primary Category: cs.FL  
Categories: cs-FL, cs.FL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01539v1)  

---


**ABSTRACT**  
To improve reliability and the understanding of AI systems, there is increasing interest in the use of formal methods, e.g. model checking. Model checking tools produce a counterexample when a model does not satisfy a property. Understanding these counterexamples is critical for efficient debugging, as it allows the developer to focus on the parts of the program that caused the issue.   To this end, we present a new technique that ascribes a responsibility value to each state in a transition system that does not satisfy a given safety property. The value is higher if the non-deterministic choices in a state have more power to change the outcome, given the behaviour observed in the counterexample. For this, we employ a concept from cooperative game theory -- namely general power indices, such as the Shapley value -- to compute the responsibility of the states.   We present an optimistic and pessimistic version of responsibility that differ in how they treat the states that do not lie on the counterexample. We give a characterisation of optimistic responsibility that leads to an efficient algorithm for it and show computational hardness of the pessimistic version. We also present a tool to compute responsibility and show how a stochastic algorithm can be used to approximate responsibility in larger models. These methods can be deployed in the design phase, at runtime and at inspection time to gain insights on causal relations within the behavior of AI systems.

{{</citation>}}


## cs.IT (1)



### (165/175) Non-Linear Analog Processing Gains in Task-Based Quantization (Marian Temprana Alonso et al., 2024)

{{<citation>}}

Marian Temprana Alonso, Farhad Shirani, Neil Irwin Bernardo, Yonina C. Eldar. (2024)  
**Non-Linear Analog Processing Gains in Task-Based Quantization**  

---
Primary Category: cs.IT  
Categories: cs-IT, cs.IT, eess-SP, math-IT  
Keywords: Quantization  
[Paper Link](http://arxiv.org/abs/2402.01525v1)  

---


**ABSTRACT**  
In task-based quantization, a multivariate analog signal is transformed into a digital signal using a limited number of low-resolution analog-to-digital converters (ADCs). This process aims to minimize a fidelity criterion, which is assessed against an unobserved task variable that is correlated with the analog signal. The scenario models various applications of interest such as channel estimation, medical imaging applications, and object localization. This work explores the integration of analog processing components -- such as analog delay elements, polynomial operators, and envelope detectors -- prior to ADC quantization. Specifically, four scenarios, involving different collections of analog processing operators are considered: (i) arbitrary polynomial operators with analog delay elements, (ii) limited-degree polynomial operators, excluding delay elements, (iii) sequences of envelope detectors, and (iv) a combination of analog delay elements and linear combiners. For each scenario, the minimum achievable distortion is quantified through derivation of computable expressions in various statistical settings. It is shown that analog processing can significantly reduce the distortion in task reconstruction. Numerical simulations in a Gaussian example are provided to give further insights into the aforementioned analog processing gains.

{{</citation>}}


## eess.SY (3)



### (166/175) Active Support of Inverters for Improving Short-Term Voltage Security in 100% IBRsPenetrated Power Systems (Yinhong Lin et al., 2024)

{{<citation>}}

Yinhong Lin, Bin Wang, Qinglai Guo, Haotian Zhao, Hongbin Sun. (2024)  
**Active Support of Inverters for Improving Short-Term Voltage Security in 100% IBRsPenetrated Power Systems**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2402.01523v1)  

---


**ABSTRACT**  
Due to the energy crisis and environmental pollution, the installed capacity of inverter-based resources (IBRs) in power grids is rapidly increasing, and grid-following control (GFL) is the most prevalent at present. Meanwhile, grid-forming control-based (GFM) devices have been installed in the grid to provide active support for frequency and voltage. In the future GFL devices combined with GFM will be promising, especially in power systems with high penetration or 100% IBRs. When a short-circuit fault occurs in the grid, the controlled current source characteristic of the GFL devices leads to insufficient dynamic voltage support (DVS), while the GFM devices usually reduce the internal voltage to limit the current. Thus, deep voltage sags and undesired disconnections of IBRs may occur. Moreover, due to the dispersed locations and the control strategies' diversity of IBRs, the voltage support of different devices may not be fully coordinated, which is not conducive to short-term voltage security (STVS). To address this issue, a control scheme based on the simulation of transient characteristics of synchronous machines (SMs) is proposed. Then, a new fault ride-through strategy (FRT) is proposed based on the characteristic differences between GFL and GFM devices, and an optimization model of multi-device control parameters is formulated to meet the short-term voltage security constraints (SVSCs) and device capacity constraints. Finally, a fast solution method based on analytical modeling is proposed for the model. Test results based on the doublegenerator-one-load system, the IEEE 14-bus system, and other systems of different sizes show that the proposed method can effectively enhance the active support capability of GFL and GFM to the grid voltage, and avoid the large-scale disconnection of IBRs

{{</citation>}}


### (167/175) Brain-Like Replay Naturally Emerges in Reinforcement Learning Agents (Jiyi Wang et al., 2024)

{{<citation>}}

Jiyi Wang, Likai Tang, Huimiao Chen, Sen Song. (2024)  
**Brain-Like Replay Naturally Emerges in Reinforcement Learning Agents**  

---
Primary Category: eess.SY  
Categories: cs-AI, cs-CE, cs-NE, cs-SY, eess-SY, eess.SY, q-bio-NC  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2402.01467v1)  

---


**ABSTRACT**  
Can replay, as a widely observed neural activity pattern in brain regions, particularly in the hippocampus and neocortex, emerge in an artificial agent? If yes, does it contribute to the tasks? In this work, without heavy dependence on complex assumptions, we discover naturally emergent replay under task-optimized paradigm using a recurrent neural network-based reinforcement learning model, which mimics the hippocampus and prefrontal cortex, as well as their intercommunication and the sensory cortex input. The emergent replay in the hippocampus, which results from the episodic memory and cognitive map as well as environment observations, well resembles animal experimental data and serves as an effective indicator of high task performance. The model also successfully reproduces local and nonlocal replay, which matches the human experimental data. Our work provides a new avenue for understanding the mechanisms behind replay.

{{</citation>}}


### (168/175) Few-Shot Scenario Testing for Autonomous Vehicles Based on Neighborhood Coverage and Similarity (Shu Li et al., 2024)

{{<citation>}}

Shu Li, Jingxuan Yang, Honglin He, Yi Zhang, Jianming Hu, Shuo Feng. (2024)  
**Few-Shot Scenario Testing for Autonomous Vehicles Based on Neighborhood Coverage and Similarity**  

---
Primary Category: eess.SY  
Categories: cs-LG, cs-RO, cs-SE, cs-SY, eess-SY, eess.SY  
Keywords: Few-Shot  
[Paper Link](http://arxiv.org/abs/2402.01795v1)  

---


**ABSTRACT**  
Testing and evaluating the safety performance of autonomous vehicles (AVs) is essential before the large-scale deployment. Practically, the acceptable cost of testing specific AV model can be restricted within an extremely small limit because of testing cost or time. With existing testing methods, the limitations imposed by strictly restricted testing numbers often result in significant uncertainties or challenges in quantifying testing results. In this paper, we formulate this problem for the first time the "few-shot testing" (FST) problem and propose a systematic FST framework to address this challenge. To alleviate the considerable uncertainty inherent in a small testing scenario set and optimize scenario utilization, we frame the FST problem as an optimization problem and search for a small scenario set based on neighborhood coverage and similarity. By leveraging the prior information on surrogate models (SMs), we dynamically adjust the testing scenario set and the contribution of each scenario to the testing result under the guidance of better generalization ability on AVs. With certain hypotheses on SMs, a theoretical upper bound of testing error is established to verify the sufficiency of testing accuracy within given limited number of tests. The experiments of the cut-in scenario using FST method demonstrate a notable reduction in testing error and variance compared to conventional testing methods, especially for situations with a strict limitation on the number of scenarios.

{{</citation>}}


## cs.NE (2)



### (169/175) cmaes : A Simple yet Practical Python Library for CMA-ES (Masahiro Nomura et al., 2024)

{{<citation>}}

Masahiro Nomura, Masashi Shibata. (2024)  
**cmaes : A Simple yet Practical Python Library for CMA-ES**  

---
Primary Category: cs.NE  
Categories: cs-MS, cs-NE, cs.NE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01373v1)  

---


**ABSTRACT**  
The covariance matrix adaptation evolution strategy (CMA-ES) has been highly effective in black-box continuous optimization, as demonstrated by its success in both benchmark problems and various real-world applications. To address the need for an accessible yet potent tool in this domain, we developed cmaes, a simple and practical Python library for CMA-ES. cmaes is characterized by its simplicity, offering intuitive use and high code readability. This makes it suitable for quickly using CMA-ES, as well as for educational purposes and seamless integration into other libraries. Despite its simplistic design, cmaes maintains enhanced functionality. It incorporates recent advancements in CMA-ES, such as learning rate adaptation for challenging scenarios, transfer learning, and mixed-integer optimization capabilities. These advanced features are accessible through a user-friendly API, ensuring that cmaes can be easily adopted in practical applications. We regard cmaes as the first choice for a Python CMA-ES library among practitioners. The software is available under the MIT license at https://github.com/CyberAgentAILab/cmaes.

{{</citation>}}


### (170/175) ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution (Haoran Ye et al., 2024)

{{<citation>}}

Haoran Ye, Jiarui Wang, Zhiguang Cao, Guojie Song. (2024)  
**ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution**  

---
Primary Category: cs.NE  
Categories: cs-AI, cs-NE, cs.NE  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01145v1)  

---


**ABSTRACT**  
The omnipresence of NP-hard combinatorial optimization problems (COPs) compels domain experts to engage in trial-and-error heuristic design process. The long-standing endeavor of design automation has gained new momentum with the rise of large language models (LLMs). This paper introduces Language Hyper-Heuristics (LHHs), an emerging variant of Hyper-Heuristics that leverages LLMs for heuristic generation, featuring minimal manual intervention and open-ended heuristic spaces. To empower LHHs, we present Reflective Evolution (ReEvo), a generic searching framework that emulates the reflective design approach of human experts while far surpassing human capabilities with its scalable LLM inference, Internet-scale domain knowledge, and powerful evolutionary search. Evaluations across 12 COP settings show that 1) verbal reflections for evolution lead to smoother fitness landscapes, explicit inference of black-box COP settings, and better search results; 2) heuristics generated by ReEvo in minutes can outperform state-of-the-art human designs and neural solvers; 3) LHHs enable efficient algorithm design automation even when challenged with black-box COPs, demonstrating its potential for complex and novel real-world applications. Our code is available: https://github.com/ai4co/LLM-as-HH.

{{</citation>}}


## q-bio.GN (1)



### (171/175) PhenoLinker: Phenotype-Gene Link Prediction and Explanation using Heterogeneous Graph Neural Networks (Jose L. Mellina Andreu et al., 2024)

{{<citation>}}

Jose L. Mellina Andreu, Luis Bernal, Antonio F. Skarmeta, Mina Ryten, Sara Álvarez, Alejandro Cisterna García, Juan A. Botía. (2024)  
**PhenoLinker: Phenotype-Gene Link Prediction and Explanation using Heterogeneous Graph Neural Networks**  

---
Primary Category: q-bio.GN  
Categories: I-2-1; J-3, cs-LG, q-bio-GN, q-bio.GN  
Keywords: Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2402.01809v1)  

---


**ABSTRACT**  
The association of a given human phenotype to a genetic variant remains a critical challenge for biology. We present a novel system called PhenoLinker capable of associating a score to a phenotype-gene relationship by using heterogeneous information networks and a convolutional neural network-based model for graphs, which can provide an explanation for the predictions. This system can aid in the discovery of new associations and in the understanding of the consequences of human genetic variation.

{{</citation>}}


## stat.ML (2)



### (172/175) Transformers Learn Nonlinear Features In Context: Nonconvex Mean-field Dynamics on the Attention Landscape (Juno Kim et al., 2024)

{{<citation>}}

Juno Kim, Taiji Suzuki. (2024)  
**Transformers Learn Nonlinear Features In Context: Nonconvex Mean-field Dynamics on the Attention Landscape**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: Attention, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2402.01258v1)  

---


**ABSTRACT**  
Large language models based on the Transformer architecture have demonstrated impressive capabilities to learn in context. However, existing theoretical studies on how this phenomenon arises are limited to the dynamics of a single layer of attention trained on linear regression tasks. In this paper, we study the optimization of a Transformer consisting of a fully connected layer followed by a linear attention layer. The MLP acts as a common nonlinear representation or feature map, greatly enhancing the power of in-context learning. We prove in the mean-field and two-timescale limit that the infinite-dimensional loss landscape for the distribution of parameters, while highly nonconvex, becomes quite benign. We also analyze the second-order stability of mean-field dynamics and show that Wasserstein gradient flow almost always avoids saddle points. Furthermore, we establish novel methods for obtaining concrete improvement rates both away from and near critical points. This represents the first saddle point analysis of mean-field dynamics in general and the techniques are of independent interest.

{{</citation>}}


### (173/175) No Free Prune: Information-Theoretic Barriers to Pruning at Initialization (Tanishq Kumar et al., 2024)

{{<citation>}}

Tanishq Kumar, Kevin Luo, Mark Sellke. (2024)  
**No Free Prune: Information-Theoretic Barriers to Pruning at Initialization**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: Pruning  
[Paper Link](http://arxiv.org/abs/2402.01089v1)  

---


**ABSTRACT**  
The existence of "lottery tickets" arXiv:1803.03635 at or near initialization raises the tantalizing question of whether large models are necessary in deep learning, or whether sparse networks can be quickly identified and trained without ever training the dense models that contain them. However, efforts to find these sparse subnetworks without training the dense model ("pruning at initialization") have been broadly unsuccessful arXiv:2009.08576. We put forward a theoretical explanation for this, based on the model's effective parameter count, $p_\text{eff}$, given by the sum of the number of non-zero weights in the final network and the mutual information between the sparsity mask and the data. We show the Law of Robustness of arXiv:2105.12806 extends to sparse networks with the usual parameter count replaced by $p_\text{eff}$, meaning a sparse neural network which robustly interpolates noisy data requires a heavily data-dependent mask. We posit that pruning during and after training outputs masks with higher mutual information than those produced by pruning at initialization. Thus two networks may have the same sparsities, but differ in effective parameter count based on how they were trained. This suggests that pruning near initialization may be infeasible and explains why lottery tickets exist, but cannot be found fast (i.e. without training the full network). Experiments on neural networks confirm that information gained during training may indeed affect model capacity.

{{</citation>}}


## eess.SP (1)



### (174/175) Graph Neural Networks in EEG-based Emotion Recognition: A Survey (Chenyu Liu et al., 2024)

{{<citation>}}

Chenyu Liu, Xinliang Zhou, Yihao Wu, Ruizhi Yang, Liming Zhai, Ziyu Jia, Yang Liu. (2024)  
**Graph Neural Networks in EEG-based Emotion Recognition: A Survey**  

---
Primary Category: eess.SP  
Categories: cs-LG, eess-SP, eess.SP  
Keywords: Emotion Recognition, GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2402.01138v1)  

---


**ABSTRACT**  
Compared to other modalities, EEG-based emotion recognition can intuitively respond to the emotional patterns in the human brain and, therefore, has become one of the most concerning tasks in the brain-computer interfaces field. Since dependencies within brain regions are closely related to emotion, a significant trend is to develop Graph Neural Networks (GNNs) for EEG-based emotion recognition. However, brain region dependencies in emotional EEG have physiological bases that distinguish GNNs in this field from those in other time series fields. Besides, there is neither a comprehensive review nor guidance for constructing GNNs in EEG-based emotion recognition. In the survey, our categorization reveals the commonalities and differences of existing approaches under a unified framework of graph construction. We analyze and categorize methods from three stages in the framework to provide clear guidance on constructing GNNs in EEG-based emotion recognition. In addition, we discuss several open challenges and future directions, such as Temporal full-connected graph and Graph condensation.

{{</citation>}}


## quant-ph (1)



### (175/175) Variational Quantum Circuits Enhanced Generative Adversarial Network (Runqiu Shu et al., 2024)

{{<citation>}}

Runqiu Shu, Xusheng Xu, Man-Hong Yung, Wei Cui. (2024)  
**Variational Quantum Circuits Enhanced Generative Adversarial Network**  

---
Primary Category: quant-ph  
Categories: cs-AI, cs-ET, cs-LG, quant-ph, quant-ph  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01791v1)  

---


**ABSTRACT**  
Generative adversarial network (GAN) is one of the widely-adopted machine-learning frameworks for a wide range of applications such as generating high-quality images, video, and audio contents. However, training a GAN could become computationally expensive for large neural networks. In this work, we propose a hybrid quantum-classical architecture for improving GAN (denoted as QC-GAN). The performance was examed numerically by benchmarking with a classical GAN using MindSpore Quantum on the task of hand-written image generation. The generator of the QC-GAN consists of a quantum variational circuit together with a one-layer neural network, and the discriminator consists of a traditional neural network. Leveraging the entangling and expressive power of quantum circuits, our hybrid architecture achieved better performance (Frechet Inception Distance) than the classical GAN, with much fewer training parameters and number of iterations for convergence. We have also demonstrated the superiority of QC-GAN over an alternative quantum GAN, namely pathGAN, which could hardly generate 16$\times$16 or larger images. This work demonstrates the value of combining ideas from quantum computing with machine learning for both areas of Quantum-for-AI and AI-for-Quantum.

{{</citation>}}
