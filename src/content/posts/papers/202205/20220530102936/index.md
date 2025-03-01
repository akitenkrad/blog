---
draft: false
title: "Neural Machine Translation of Rare Words with Subword Units"
date: 2022-05-30
author: "akitenkrad"
description: ""
tags: ["At:Round-1", "Published:2015", "Machine Translation", "Byte Pair Encoding", "Embedding", "DS:WMT2015"]
menu:
  sidebar:
    name: "Neural Machine Translation of Rare Words with Subword Units"
    identifier: 20220530
    parent: 202205
    weight: 10
math: true
---

- [x] Round-1: Overview
- [ ] Round-2: Model Implementation Details
- [ ] Round-3: Experiments

## Citation

{{< citation >}}
Sennrich, R., Haddow, B., & Birch, A. (2015).  
Neural Machine Translation of Rare Words with Subword Units.  
https://doi.org/10.48550/arxiv.1508.07909
{{< /citation >}}

## Abstract

> Neural machine translation (NMT) models typically operate with a fixed
> vocabulary, but translation is an open-vocabulary problem. Previous work
> addresses the translation of out-of-vocabulary words by backing off to a
> dictionary. In this paper, we introduce a simpler and more effective approach,
> making the NMT model capable of open-vocabulary translation by encoding rare
> and unknown words as sequences of subword units. This is based on the intuition
> that various word classes are translatable via smaller units than words, for
> instance names (via character copying or transliteration), compounds (via
> compositional translation), and cognates and loanwords (via phonological and
> morphological transformations). We discuss the suitability of different word
> segmentation techniques, including simple character n-gram models and a
> segmentation based on the byte pair encoding compression algorithm, and
> empirically show that subword models improve over a back-off dictionary
> baseline for the WMT 15 translation tasks English-German and English-Russian by
> 1.1 and 1.3 BLEU, respectively.

## Background & Wat's New
- Machine Translationは本来Open-Vocabularyなタスクだが，従来の研究の多くは事前に辞書を構築された辞書を使ってモデルを構築している．したがって，辞書に存在しない単語を翻訳することができない．そこで，単語をさらに粒度の小さなサブワードに分割することで出現頻度の低い単語や新出単語に対応する手法を提案した．
  - n-gramモデル
  - byte pair encoding
- 提案手法にて，WMT15タスクにおけるEnglish→German，English→Russianの翻訳でBLEUを改善することに成功した．

## Dataset

{{< ci-details summary="EMNLP 2015 TENTH WORKSHOP ON STATISTICAL MACHINE TRANSLATION" >}}
https://www.statmt.org/wmt15/index.html  
17-18 September 2015  
Lisbon, Portugal  
{{< /ci-details>}}

<br/>

**Dataset Details**  
<img src="table-1.png" />

## Model Description

### Training Settings

## Results

#### English → German
<img src="table-2.png" />

#### English → Russian
<img src="table-3.png" />

#### Translation using subword examples

{{< split 6 6 >}}
<img src="table-4.png" />
---
<img src="table-5.png" />
{{< /split>}}

## References


{{< ci-details summary="Learning Phrase Representations using RNN Encoder–Decoder for Statistical Machine Translation (Kyunghyun Cho et al., 2014)">}}

Kyunghyun Cho, Bart van Merrienboer, Çaglar Gülçehre, Dzmitry Bahdanau, Fethi Bougares, Holger Schwenk, Yoshua Bengio. (2014)  
**Learning Phrase Representations using RNN Encoder–Decoder for Statistical Machine Translation**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/0b544dfe355a5070b60986319a3f51fb45d1348e)  
Influential Citation Count (2602), SS-ID (0b544dfe355a5070b60986319a3f51fb45d1348e)  

**ABSTRACT**  
In this paper, we propose a novel neural network model called RNN Encoder‐ Decoder that consists of two recurrent neural networks (RNN). One RNN encodes a sequence of symbols into a fixedlength vector representation, and the other decodes the representation into another sequence of symbols. The encoder and decoder of the proposed model are jointly trained to maximize the conditional probability of a target sequence given a source sequence. The performance of a statistical machine translation system is empirically found to improve by using the conditional probabilities of phrase pairs computed by the RNN Encoder‐Decoder as an additional feature in the existing log-linear model. Qualitatively, we show that the proposed model learns a semantically and syntactically meaningful representation of linguistic phrases.

{{< /ci-details >}}

{{< ci-details summary="Unsupervised Discovery of Morphemes (Mathias Creutz et al., 2002)">}}

Mathias Creutz, K. Lagus. (2002)  
**Unsupervised Discovery of Morphemes**  
SIGMORPHON  
[Paper Link](https://www.semanticscholar.org/paper/0c5043108eda7d2fa467fe91e3c47d4ba08e0b48)  
Influential Citation Count (52), SS-ID (0c5043108eda7d2fa467fe91e3c47d4ba08e0b48)  

**ABSTRACT**  
We present two methods for unsupervised segmentation of words into morpheme-like units. The model utilized is especially suited for languages with a rich morphology, such as Finnish. The first method is based on the Minimum Description Length (MDL) principle and works online. In the second method, Maximum Likelihood (ML) optimization is used. The quality of the segmentations is measured using an evaluation method that compares the segmentations produced to an existing morphological analysis. Experiments on both Finnish and English corpora show that the presented methods perform well compared to a current state-of-the-art system.

{{< /ci-details >}}

{{< ci-details summary="On Using Very Large Target Vocabulary for Neural Machine Translation (Sébastien Jean et al., 2014)">}}

Sébastien Jean, Kyunghyun Cho, R. Memisevic, Yoshua Bengio. (2014)  
**On Using Very Large Target Vocabulary for Neural Machine Translation**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/1938624bb9b0f999536dcc8d8f519810bb4e1b3b)  
Influential Citation Count (75), SS-ID (1938624bb9b0f999536dcc8d8f519810bb4e1b3b)  

**ABSTRACT**  
Neural machine translation, a recently proposed approach to machine translation based purely on neural networks, has shown promising results compared to the existing approaches such as phrase-based statistical machine translation. Despite its recent success, neural machine translation has its limitation in handling a larger vocabulary, as training complexity as well as decoding complexity increase proportionally to the number of target words. In this paper, we propose a method based on importance sampling that allows us to use a very large target vocabulary without increasing training complexity. We show that decoding can be efficiently done even with the model having a very large target vocabulary by selecting only a small subset of the whole target vocabulary. The models trained by the proposed approach are empirically found to outperform the baseline models with a small vocabulary as well as the LSTM-based neural machine translation models. Furthermore, when we use the ensemble of a few models with very large target vocabularies, we achieve the state-of-the-art translation performance (measured by BLEU) on the English!German translation and almost as high performance as state-of-the-art English!French translation system.

{{< /ci-details >}}

{{< ci-details summary="Addressing the Rare Word Problem in Neural Machine Translation (Thang Luong et al., 2014)">}}

Thang Luong, Ilya Sutskever, Quoc V. Le, Oriol Vinyals, Wojciech Zaremba. (2014)  
**Addressing the Rare Word Problem in Neural Machine Translation**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/1956c239b3552e030db1b78951f64781101125ed)  
Influential Citation Count (85), SS-ID (1956c239b3552e030db1b78951f64781101125ed)  

**ABSTRACT**  
Neural Machine Translation (NMT) is a new approach to machine translation that has shown promising results that are comparable to traditional approaches. A significant weakness in conventional NMT systems is their inability to correctly translate very rare words: end-to-end NMTs tend to have relatively small vocabularies with a single unk symbol that represents every possible out-of-vocabulary (OOV) word. In this paper, we propose and implement an effective technique to address this problem. We train an NMT system on data that is augmented by the output of a word alignment algorithm, allowing the NMT system to emit, for each OOV word in the target sentence, the position of its corresponding word in the source sentence. This information is later utilized in a post-processing step that translates every OOV word using a dictionary. Our experiments on the WMT’14 English to French translation task show that this method provides a substantial improvement of up to 2.8 BLEU points over an equivalent NMT system that does not use this technique. With 37.5 BLEU points, our NMT system is the first to surpass the best result achieved on a WMT’14 contest task.

{{< /ci-details >}}

{{< ci-details summary="A new algorithm for data compression (Philip Gage, 1994)">}}

Philip Gage. (1994)  
**A new algorithm for data compression**  
  
[Paper Link](https://www.semanticscholar.org/paper/1aa9c0045f1fe8c79cce03c7c14ef4b4643a21f8)  
Influential Citation Count (85), SS-ID (1aa9c0045f1fe8c79cce03c7c14ef4b4643a21f8)  

**ABSTRACT**  
Data compression is becoming increasingly important as a way to stretch disk space and speed up data transfers. This article describes a simple general-purpose data compression algorithm, called Byte Pair Encoding (BPE), which provides almost as much compression as the popular Lempel, Ziv, and Welch (LZW) method [3, 2]. (I mention the LZW method in particular because it delivers good overall performance and is widely used.) BPE’s compression speed is somewhat slower than LZW’s, but BPE’s expansion is faster. The main advantage of BPE is the small, fast expansion routine, ideal for applications with limited memory. The accompanying C code provides an efficient implementation of the algorithm.

{{< /ci-details >}}

{{< ci-details summary="SUBWORD LANGUAGE MODELING WITH NEURAL NETWORKS (Tomas Mikolov et al., 2011)">}}

Tomas Mikolov, Ilya Sutskever, Anoop Deoras, H. Le, Stefan Kombrink, J. Cernocký. (2011)  
**SUBWORD LANGUAGE MODELING WITH NEURAL NETWORKS**  
  
[Paper Link](https://www.semanticscholar.org/paper/1fd7fc06653723b05abe5f3d1de393ddcf6bdddb)  
Influential Citation Count (17), SS-ID (1fd7fc06653723b05abe5f3d1de393ddcf6bdddb)  

**ABSTRACT**  
We explore the performance of several types of language mode ls on the word-level and the character-level language modelin g tasks. This includes two recently proposed recurrent neural netwo rk architectures, a feedforward neural network model, a maximum ent ropy model and the usual smoothed n-gram models. We then propose a simple technique for learning sub-word level units from th e data, and show that it combines advantages of both character and wo rdlevel models. Finally, we show that neural network based lan gu ge models can be order of magnitude smaller than compressed n-g ram models, at the same level of performance when applied to a Bro dcast news RT04 speech recognition task. By using sub-word un its, the size can be reduced even more.

{{< /ci-details >}}

{{< ci-details summary="Montreal Neural Machine Translation Systems for WMT’15 (Sébastien Jean et al., 2015)">}}

Sébastien Jean, Orhan Firat, Kyunghyun Cho, R. Memisevic, Yoshua Bengio. (2015)  
**Montreal Neural Machine Translation Systems for WMT’15**  
WMT@EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/25eb839f39507fe6983ad3e692b2f8d93a5cb0cc)  
Influential Citation Count (13), SS-ID (25eb839f39507fe6983ad3e692b2f8d93a5cb0cc)  

**ABSTRACT**  
Neural machine translation (NMT) systems have recently achieved results comparable to the state of the art on a few translation tasks, including English→French and English→German. The main purpose of the Montreal Institute for Learning Algorithms (MILA) submission to WMT’15 is to evaluate this new approach on a greater variety of language pairs. Furthermore, the human evaluation campaign may help us and the research community to better understand the behaviour of our systems. We use the RNNsearch architecture, which adds an attention mechanism to the encoderdecoder. We also leverage some of the recent developments in NMT, including the use of large vocabularies, unknown word replacement and, to a limited degree, the inclusion of monolingual language models.

{{< /ci-details >}}

{{< ci-details summary="chrF: character n-gram F-score for automatic MT evaluation (Maja Popovic, 2015)">}}

Maja Popovic. (2015)  
**chrF: character n-gram F-score for automatic MT evaluation**  
WMT@EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/285c165c81fc9275955147a892b9a039ec8b1052)  
Influential Citation Count (63), SS-ID (285c165c81fc9275955147a892b9a039ec8b1052)  

**ABSTRACT**  
We propose the use of character n-gram F-score for automatic evaluation of machine translation output. Character ngrams have already been used as a part of more complex metrics, but their individual potential has not been investigated yet. We report system-level correlations with human rankings for 6-gram F1-score (CHRF) on the WMT12, WMT13 and WMT14 data as well as segment-level correlation for 6gram F1 (CHRF) and F3-scores (CHRF3) on WMT14 data for all available target languages. The results are very promising, especially for the CHRF3 score – for translation from English, this variant showed the highest segment-level correlations outperforming even the best metrics on the WMT14 shared evaluation task.

{{< /ci-details >}}

{{< ci-details summary="Unsupervised Multilingual Learning for Morphological Segmentation (Benjamin Snyder et al., 2008)">}}

Benjamin Snyder, R. Barzilay. (2008)  
**Unsupervised Multilingual Learning for Morphological Segmentation**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/36ffcc1cc218ca36de384a107fb48e5abe2e6359)  
Influential Citation Count (8), SS-ID (36ffcc1cc218ca36de384a107fb48e5abe2e6359)  

**ABSTRACT**  
For centuries, the deep connection between languages has brought about major discoveries about human communication. In this paper we investigate how this powerful source of information can be exploited for unsupervised language learning. In particular, we study the task of morphological segmentation of multiple languages. We present a nonparametric Bayesian model that jointly induces morpheme segmentations of each language under consideration and at the same time identifies cross-lingual morpheme patterns, or abstract morphemes. We apply our model to three Semitic languages: Arabic, Hebrew, Aramaic, as well as to English. Our results demonstrate that learning morphological models in tandem reduces error by up to 24% relative to monolingual models. Furthermore, we provide evidence that our joint model achieves better performance when applied to languages from the same family.

{{< /ci-details >}}

{{< ci-details summary="Improving SMT quality with morpho-syntactic analysis (S. Nießen et al., 2000)">}}

S. Nießen, H. Ney. (2000)  
**Improving SMT quality with morpho-syntactic analysis**  
COLING  
[Paper Link](https://www.semanticscholar.org/paper/3dffe5ebf00f10dd137beff00d94952f1af658c3)  
Influential Citation Count (3), SS-ID (3dffe5ebf00f10dd137beff00d94952f1af658c3)  

**ABSTRACT**  
In the framework of statistical machine translation (SMT), correspondences between the words in the source and the target language are learned from bilingual corpora on the basis of so-called alignment models. Many of the statistical systems use little or no linguistic knowledge to structure the underlying models. In this paper we argue that training data is typically not large enough to sufficiently represent the range of different phenomena in natural languages and that SMT can take advantage of the explicit introduction of some knowledge about the languages under consideration. The improvement of the translation results is demonstrated on two different German-English corpora.

{{< /ci-details >}}

{{< ci-details summary="Compositional Morphology for Word Representations and Language Modelling (Jan A. Botha et al., 2014)">}}

Jan A. Botha, P. Blunsom. (2014)  
**Compositional Morphology for Word Representations and Language Modelling**  
ICML  
[Paper Link](https://www.semanticscholar.org/paper/46f418bf6fab132f193661226c5c27d67f870ea5)  
Influential Citation Count (22), SS-ID (46f418bf6fab132f193661226c5c27d67f870ea5)  

**ABSTRACT**  
This paper presents a scalable method for integrating compositional morphological representations into a vector-based probabilistic language model. Our approach is evaluated in the context of log-bilinear language models, rendered suitably efficient for implementation inside a machine translation decoder by factoring the vocabulary. We perform both intrinsic and extrinsic evaluations, presenting results on a range of languages which demonstrate that our model learns morphological representations that both perform well on word similarity tasks and lead to substantial reductions in perplexity. When used for translation into morphologically rich languages with large vocabularies, our models obtain improvements of up to 1.2 BLEU points relative to a baseline system using back-off n-gram models.

{{< /ci-details >}}

{{< ci-details summary="Moses: Open Source Toolkit for Statistical Machine Translation (Philipp Koehn et al., 2007)">}}

Philipp Koehn, Hieu T. Hoang, Alexandra Birch, Chris Callison-Burch, Marcello Federico, N. Bertoldi, Brooke Cowan, Wade Shen, C. Moran, R. Zens, Chris Dyer, Ondrej Bojar, Alexandra Constantin, Evan Herbst. (2007)  
**Moses: Open Source Toolkit for Statistical Machine Translation**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/4ee2eab4c298c1824a9fb8799ad8eed21be38d21)  
Influential Citation Count (807), SS-ID (4ee2eab4c298c1824a9fb8799ad8eed21be38d21)  

**ABSTRACT**  
We describe an open-source toolkit for statistical machine translation whose novel contributions are (a) support for linguistically motivated factors, (b) confusion network decoding, and (c) efficient data formats for translation models and language models. In addition to the SMT decoder, the toolkit also includes a wide variety of tools for training, tuning and applying the system to many translation tasks.

{{< /ci-details >}}

{{< ci-details summary="Better Word Representations with Recursive Neural Networks for Morphology (Thang Luong et al., 2013)">}}

Thang Luong, R. Socher, Christopher D. Manning. (2013)  
**Better Word Representations with Recursive Neural Networks for Morphology**  
CoNLL  
[Paper Link](https://www.semanticscholar.org/paper/53ab89807caead278d3deb7b6a4180b277d3cb77)  
Influential Citation Count (70), SS-ID (53ab89807caead278d3deb7b6a4180b277d3cb77)  

**ABSTRACT**  
Vector-space word representations have been very successful in recent years at improving performance across a variety of NLP tasks. However, common to most existing work, words are regarded as independent entities without any explicit relationship among morphologically related words being modeled. As a result, rare and complex words are often poorly estimated, and all unknown words are represented in a rather crude way using only one or a few vectors. This paper addresses this shortcoming by proposing a novel model that is capable of building representations for morphologically complex words from their morphemes. We combine recursive neural networks (RNNs), where each morpheme is a basic unit, with neural language models (NLMs) to consider contextual information in learning morphologicallyaware word representations. Our learned models outperform existing word representations by a good margin on word similarity tasks across many datasets, including a new dataset we introduce focused on rare words to complement existing ones in an interesting way.

{{< /ci-details >}}

{{< ci-details summary="Association for Computational Linguistics (D. Litman et al., 2001)">}}

D. Litman, J. Hirschberg, M. Swerts, Scott Miller, L. Ramshaw, R. Weischedel, Eugene Charniak, Lillian Lee. (2001)  
**Association for Computational Linguistics**  
  
[Paper Link](https://www.semanticscholar.org/paper/566eb7be43b8a2b2daff82b03711098a84859b2a)  
Influential Citation Count (67), SS-ID (566eb7be43b8a2b2daff82b03711098a84859b2a)  

**ABSTRACT**  


{{< /ci-details >}}

{{< ci-details summary="Unsupervised Morphology Rivals Supervised Morphology for Arabic MT (D. Stallard et al., 2012)">}}

D. Stallard, Jacob Devlin, Michael Kayser, Yoong Keok Lee, R. Barzilay. (2012)  
**Unsupervised Morphology Rivals Supervised Morphology for Arabic MT**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/5ab5cc1c135a1af68fdea604474b70f4121db623)  
Influential Citation Count (1), SS-ID (5ab5cc1c135a1af68fdea604474b70f4121db623)  

**ABSTRACT**  
If unsupervised morphological analyzers could approach the effectiveness of supervised ones, they would be a very attractive choice for improving MT performance on low-resource inflected languages. In this paper, we compare performance gains for state-of-the-art supervised vs. unsupervised morphological analyzers, using a state-of-the-art Arabic-to-English MT system. We apply maximum marginal decoding to the unsupervised analyzer, and show that this yields the best published segmentation accuracy for Arabic, while also making segmentation output more stable. Our approach gives an 18% relative BLEU gain for Levantine dialectal Arabic. Furthermore, it gives higher gains for Modern Standard Arabic (MSA), as measured on NIST MT-08, than does MADA (Habash and Rambow, 2005), a leading supervised MSA segmenter.

{{< /ci-details >}}

{{< ci-details summary="Results of the WMT13 Metrics Shared Task (Ondrej Bojar et al., 2016)">}}

Ondrej Bojar, Yvette Graham, Amir Kamran, Miloš Stanojević. (2016)  
**Results of the WMT13 Metrics Shared Task**  
WMT@EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/626331a8284feaa059555d4ea808b78ace5de4a5)  
Influential Citation Count (10), SS-ID (626331a8284feaa059555d4ea808b78ace5de4a5)  

**ABSTRACT**  
This paper presents the results of the WMT16 Metrics Shared Task. We asked participants of this task to score the outputs of the MT systems involved in the WMT16 Shared Translation Task. We collected scores of 16 metrics from 9 research groups. In addition to that, we computed scores of 9 standard metrics (BLEU, SentBLEU, NIST, WER, PER, TER and CDER) as baselines. The collected scores were evaluated in terms of system-level correlation (how well each metric’s scores correlate with WMT16 official manual ranking of systems) and in terms of segment level correlation (how often a metric agrees with humans in comparing two translations of a particular sentence). This year there are several additions to the setup: large number of language pairs (18 in total), datasets from different domains (news, IT and medical), and different kinds of judgments: relative ranking (RR), direct assessment (DA) and HUME manual semantic judgments. Finally, generation of large number of hybrid systems was trialed for provision of more conclusive system-level metric rankings.

{{< /ci-details >}}

{{< ci-details summary="Word hy-phen-a-tion by com-put-er (hyphenation, computer) (Franklin Mark Liang, 1983)">}}

Franklin Mark Liang. (1983)  
**Word hy-phen-a-tion by com-put-er (hyphenation, computer)**  
  
[Paper Link](https://www.semanticscholar.org/paper/6c0f01c67f43e35859025d3424e0268b4d1ee2f1)  
Influential Citation Count (14), SS-ID (6c0f01c67f43e35859025d3424e0268b4d1ee2f1)  

**ABSTRACT**  
This thesis describes research leading to an improved word hyphenation algorithm for the T(,E)X82 typesetting system. Hyphenation is viewed primarily as a data compression problem, where we are given a dictionary of words with allowable division points, and try to devise methods that take advantage of the large amount of redundancy present.  The new hyphenation algorithm is based on the idea of hyphenating and inhibiting patterns. These are simply strings of letters that, when they match in a word, give us information about hyphenation at some point in the pattern. For example, '-tion' and 'c-c' are good hyphenating patterns. An important feature of this method is that a suitable set of patterns can be extracted automatically from the dictionary.  In order to represent the set of patterns in a compact form that is also reasonably efficient for searching, the author has developed a new data structure called a packed trie. This data structure allows the very fast search times characteristic of indexed tries, but in many cases it entirely eliminates the wasted space for null links usually present in such tries. We demonstrate the versatility and practical advantages of this data structure by using a variant of it as the critical component of the program that generates the patterns from the dictionary.  The resulting hyphenation algorithm uses about 4500 patterns that compile into a packed trie occupying 25K bytes of storage. These patterns find 89% of the hyphens in a pocket dictionary word list, with essentially no error. By comparison, the uncompressed dictionary occupies over 500K bytes.

{{< /ci-details >}}

{{< ci-details summary="Finding Function in Form: Compositional Character Models for Open Vocabulary Word Representation (Wang Ling et al., 2015)">}}

Wang Ling, Chris Dyer, A. Black, I. Trancoso, Ramón Fernández Astudillo, Silvio Amir, Luís Marujo, T. Luís. (2015)  
**Finding Function in Form: Compositional Character Models for Open Vocabulary Word Representation**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/6dab1c6491929d396e9e5463bc2e87af88602aa2)  
Influential Citation Count (78), SS-ID (6dab1c6491929d396e9e5463bc2e87af88602aa2)  

**ABSTRACT**  
We introduce a model for constructing vector representations of words by composing characters using bidirectional LSTMs. Relative to traditional word representation models that have independent vectors for each word type, our model requires only a single vector per character type and a fixed set of parameters for the compositional model. Despite the compactness of this model and, more importantly, the arbitrary nature of the form‐function relationship in language, our “composed” word representations yield state-of-the-art results in language modeling and part-of-speech tagging. Benefits over traditional baselines are particularly pronounced in morphologically rich languages (e.g., Turkish).

{{< /ci-details >}}

{{< ci-details summary="Character-Based PSMT for Closely Related Languages (J. Tiedemann, 2009)">}}

J. Tiedemann. (2009)  
**Character-Based PSMT for Closely Related Languages**  
EAMT  
[Paper Link](https://www.semanticscholar.org/paper/71088c81d1fb157844c61ac24fb1dd2a70d0e59f)  
Influential Citation Count (4), SS-ID (71088c81d1fb157844c61ac24fb1dd2a70d0e59f)  

**ABSTRACT**  
Translating unknown words between related languages using a character-based statistical machine translation model can be beneficial. In this paper, we describe a simple method to combine character-based models with standard word-based models to increase the coverage of a phrase-based SMT system. Using this approach, we can show a modest improvement when translating between Norwegian and Swedish. The potentials of applying character-based models to closely related languages is also illustrated by applying the character model on its own. The performance of such an approach is similar to the word-level baseline and closer to the reference in terms of string similarity.

{{< /ci-details >}}

{{< ci-details summary="A Joint Dependency Model of Morphological and Syntactic Structure for Statistical Machine Translation (Rico Sennrich et al., 2015)">}}

Rico Sennrich, B. Haddow. (2015)  
**A Joint Dependency Model of Morphological and Syntactic Structure for Statistical Machine Translation**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/726244c312dc1145e9e9ee32ce641ab8dd9c6e74)  
Influential Citation Count (0), SS-ID (726244c312dc1145e9e9ee32ce641ab8dd9c6e74)  

**ABSTRACT**  
When translating between two languages that differ in their degree of morphological synthesis, syntactic structures in one language may be realized as morphological structures in the other, and SMT models need a mechanism to learn such translations. Prior work has used morpheme splitting with flat representations that do not encode the hierarchical structure between morphemes, but this structure is relevant for learning morphosyntactic constraints and selectional preferences. We propose to model syntactic and morphological structure jointly in a dependency translation model, allowing the system to generalize to the level of morphemes. We present a dependency representation of German compounds and particle verbs that results in improvements in translation quality of 1.4‐1.8 BLEU in the WMT English‐German translation task.

{{< /ci-details >}}

{{< ci-details summary="A Simple, Fast, and Effective Reparameterization of IBM Model 2 (Chris Dyer et al., 2013)">}}

Chris Dyer, Victor Chahuneau, Noah A. Smith. (2013)  
**A Simple, Fast, and Effective Reparameterization of IBM Model 2**  
NAACL  
[Paper Link](https://www.semanticscholar.org/paper/7b5e31257f01aba987f16e175a3e49e00a5bd3bb)  
Influential Citation Count (106), SS-ID (7b5e31257f01aba987f16e175a3e49e00a5bd3bb)  

**ABSTRACT**  
We present a simple log-linear reparameterization of IBM Model 2 that overcomes problems arising from Model 1’s strong assumptions and Model 2’s overparameterization. Efficient inference, likelihood evaluation, and parameter estimation algorithms are provided. Training the model is consistently ten times faster than Model 4. On three large-scale translation tasks, systems built using our alignment model outperform IBM Model 4. An open-source implementation of the alignment model described in this paper is available from http://github.com/clab/fast align .

{{< /ci-details >}}

{{< ci-details summary="On the difficulty of training recurrent neural networks (Razvan Pascanu et al., 2012)">}}

Razvan Pascanu, Tomas Mikolov, Yoshua Bengio. (2012)  
**On the difficulty of training recurrent neural networks**  
ICML  
[Paper Link](https://www.semanticscholar.org/paper/84069287da0a6b488b8c933f3cb5be759cb6237e)  
Influential Citation Count (285), SS-ID (84069287da0a6b488b8c933f3cb5be759cb6237e)  

**ABSTRACT**  
There are two widely known issues with properly training recurrent neural networks, the vanishing and the exploding gradient problems detailed in Bengio et al. (1994). In this paper we attempt to improve the understanding of the underlying issues by exploring these problems from an analytical, a geometric and a dynamical systems perspective. Our analysis is used to justify a simple yet effective solution. We propose a gradient norm clipping strategy to deal with exploding gradients and a soft constraint for the vanishing gradients problem. We validate empirically our hypothesis and proposed solutions in the experimental section.

{{< /ci-details >}}

{{< ci-details summary="ADADELTA: An Adaptive Learning Rate Method (Matthew D. Zeiler, 2012)">}}

Matthew D. Zeiler. (2012)  
**ADADELTA: An Adaptive Learning Rate Method**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/8729441d734782c3ed532a7d2d9611b438c0a09a)  
Influential Citation Count (784), SS-ID (8729441d734782c3ed532a7d2d9611b438c0a09a)  

**ABSTRACT**  
We present a novel per-dimension learning rate method for gradient descent called ADADELTA. The method dynamically adapts over time using only first order information and has minimal computational overhead beyond vanilla stochastic gradient descent. The method requires no manual tuning of a learning rate and appears robust to noisy gradient information, different model architecture choices, various data modalities and selection of hyperparameters. We show promising results compared to other methods on the MNIST digit classification task using a single machine and on a large scale voice dataset in a distributed cluster environment.

{{< /ci-details >}}

{{< ci-details summary="Machine Translation without Words through Substring Alignment (Graham Neubig et al., 2012)">}}

Graham Neubig, Taro Watanabe, Shinsuke Mori, Tatsuya Kawahara. (2012)  
**Machine Translation without Words through Substring Alignment**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/88b66f705a329da8292e7b8aa4bfe26de4759cfa)  
Influential Citation Count (1), SS-ID (88b66f705a329da8292e7b8aa4bfe26de4759cfa)  

**ABSTRACT**  
In this paper, we demonstrate that accurate machine translation is possible without the concept of "words," treating MT as a problem of transformation between character strings. We achieve this result by applying phrasal inversion transduction grammar alignment techniques to character strings to train a character-based translation model, and using this in the phrase-based MT framework. We also propose a look-ahead parsing algorithm and substring-informed prior probabilities to achieve more effective and efficient alignment. In an evaluation, we demonstrate that character-based translation can achieve results that compare to word-based systems while effectively translating unknown and uncommon words over several language pairs.

{{< /ci-details >}}

{{< ci-details summary="Character-Aware Neural Language Models (Yoon Kim et al., 2015)">}}

Yoon Kim, Yacine Jernite, D. Sontag, Alexander M. Rush. (2015)  
**Character-Aware Neural Language Models**  
AAAI  
[Paper Link](https://www.semanticscholar.org/paper/891ce1687e2befddd19f54e4eef1d3f39c8dbaf7)  
Influential Citation Count (166), SS-ID (891ce1687e2befddd19f54e4eef1d3f39c8dbaf7)  

**ABSTRACT**  
We describe a simple neural language model that relies only on character-level inputs. Predictions are still made at the word-level. Our model employs a convolutional neural network (CNN) and a highway network over characters, whose output is given to a long short-term memory (LSTM) recurrent neural network language model (RNN-LM). On the English Penn Treebank the model is on par with the existing state-of-the-art despite having 60% fewer parameters. On languages with rich morphology (Arabic, Czech, French, German, Spanish, Russian), the model outperforms word-level/morpheme-level LSTM baselines, again with fewer parameters. The results suggest that on many languages, character inputs are sufficient for language modeling. Analysis of word representations obtained from the character composition part of the model reveals that the model is able to encode, from characters only, both semantic and orthographic information.

{{< /ci-details >}}

{{< ci-details summary="Variable length word encodings for neural translation models (Jiameng Gao, 2016)">}}

Jiameng Gao. (2016)  
**Variable length word encodings for neural translation models**  
  
[Paper Link](https://www.semanticscholar.org/paper/8c3cf30db12d17638b01e0e464e09d6b58a88187)  
Influential Citation Count (0), SS-ID (8c3cf30db12d17638b01e0e464e09d6b58a88187)  

**ABSTRACT**  
As described by Zipf’s law, vast proportions of words in most natural languages occur very infrequently, meaning that in a statistical learning framework these words would be poorly modelled for any given corpus of practical, finite size. This is known as the rare word problem. This is often worsened by the implementation of neural networks, since neural networks make use of softmax functions in the output layer. Evaluating these functions for each word in the vocabulary becomes computationally expensive in both training and runtime, as the normalisation constant is a summation of exponentials in the order O(|V|), where V is the output vocabulary. A simple method to counteract this is to label rare and infrequent words in the training corpus as an unknown word token, thereby limiting the size of the vocabulary. Nevertheless, doing so only worsens the fact that, for a given translation corpus, the vocabulary may not include all words in the natural languages involved. This is an issue in agglutinative languages, where unseen, legitimate words can be formed from known constituent words, making them di cult to model. This is known as the unknown word problem. We attempt to implement LSTM recurrent neural network language models based on Zaremba et al. (2014) for rescoring in the Syntactical-Guided Neural Machine Translation system by Stahlberg et al. (2016). Further, we compare methods to compress the vocabulary of a language through certain coding schemes, in order to reduce the impact of the computationally expensive softmax layer, and investigate there are better ways to represent natural language in neural network structures other than using tokens on the word level. Previous work have focused on word encodings for end-to-end translation systems, while we primarily focus on the more general application of language modelling. We implement byte-pair encoding, Hu↵man coding and character decomposition, and compare their performance in a SMT setting to a truncated vocabulary that is standard for neural network language models. We find that BPE is better than character-level decomposition as it is more e cient, especially for the most frequent words, and it gives higher BLEU scores than Hu↵man coding and is able to decompose new words in the language. We also show that by using byte-pair encoding we can improve the BLEU score performance for SMT systems over that of a truncated vocabulary, investigating whether this is due to the e cient decomposition or the enlarged vocabulary.

{{< /ci-details >}}

{{< ci-details summary="Effective Approaches to Attention-based Neural Machine Translation (Thang Luong et al., 2015)">}}

Thang Luong, Hieu Pham, Christopher D. Manning. (2015)  
**Effective Approaches to Attention-based Neural Machine Translation**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/93499a7c7f699b6630a86fad964536f9423bb6d0)  
Influential Citation Count (605), SS-ID (93499a7c7f699b6630a86fad964536f9423bb6d0)  

**ABSTRACT**  
An attentional mechanism has lately been used to improve neural machine translation (NMT) by selectively focusing on parts of the source sentence during translation. However, there has been little work exploring useful architectures for attention-based NMT. This paper examines two simple and effective classes of attentional mechanism: a global approach which always attends to all source words and a local one that only looks at a subset of source words at a time. We demonstrate the effectiveness of both approaches on the WMT translation tasks between English and German in both directions. With local attention, we achieve a significant gain of 5.0 BLEU points over non-attentional systems that already incorporate known techniques such as dropout. Our ensemble model using different attention architectures yields a new state-of-the-art result in the WMT’15 English to German translation task with 25.9 BLEU points, an improvement of 1.0 BLEU points over the existing best system backed by NMT and an n-gram reranker. 1

{{< /ci-details >}}

{{< ci-details summary="Variable-Length Word Encodings for Neural Translation Models (Rohan Chitnis et al., 2015)">}}

Rohan Chitnis, John DeNero. (2015)  
**Variable-Length Word Encodings for Neural Translation Models**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/93a9694b6a4149e815c30a360347593b75860761)  
Influential Citation Count (6), SS-ID (93a9694b6a4149e815c30a360347593b75860761)  

**ABSTRACT**  
Recent work in neural machine translation has shown promising performance, but the most eective architectures do not scale naturally to large vocabulary sizes. We propose and compare three variable-length encoding schemes that represent a large vocabulary corpus using a much smaller vocabulary with no loss in information. Common words are unaected by our encoding, but rare words are encoded using a sequence of two pseudo-words. Our method is simple and eective: it requires no complete dictionaries, learning procedures, increased training time, changes to the model, or new parameters. Compared to a baseline that replaces all rare words with an unknown word symbol, our best variable-length encoding strategy improves WMT English-French translation performance by up to 1.7 BLEU.

{{< /ci-details >}}

{{< ci-details summary="Recurrent Continuous Translation Models (Nal Kalchbrenner et al., 2013)">}}

Nal Kalchbrenner, P. Blunsom. (2013)  
**Recurrent Continuous Translation Models**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/944a1cfd79dbfb6fef460360a0765ba790f4027a)  
Influential Citation Count (87), SS-ID (944a1cfd79dbfb6fef460360a0765ba790f4027a)  

**ABSTRACT**  
We introduce a class of probabilistic continuous translation models called Recurrent Continuous Translation Models that are purely based on continuous representations for words, phrases and sentences and do not rely on alignments or phrasal translation units. The models have a generation and a conditioning aspect. The generation of the translation is modelled with a target Recurrent Language Model, whereas the conditioning on the source sentence is modelled with a Convolutional Sentence Model. Through various experiments, we show first that our models obtain a perplexity with respect to gold translations that is > 43% lower than that of stateof-the-art alignment-based translation models. Secondly, we show that they are remarkably sensitive to the word order, syntax, and meaning of the source sentence despite lacking alignments. Finally we show that they match a state-of-the-art system when rescoring n-best lists of translations.

{{< /ci-details >}}

{{< ci-details summary="Character-Based Pivot Translation for Under-Resourced Languages and Domains (J. Tiedemann, 2012)">}}

J. Tiedemann. (2012)  
**Character-Based Pivot Translation for Under-Resourced Languages and Domains**  
EACL  
[Paper Link](https://www.semanticscholar.org/paper/b0b3c2e5e924621b234a24037fa4f4410b478b49)  
Influential Citation Count (6), SS-ID (b0b3c2e5e924621b234a24037fa4f4410b478b49)  

**ABSTRACT**  
In this paper we investigate the use of character-level translation models to support the translation from and to under-resourced languages and textual domains via closely related pivot languages. Our experiments show that these low-level models can be successful even with tiny amounts of training data. We test the approach on movie subtitles for three language pairs and legal texts for another language pair in a domain adaptation task. Our pivot translations outperform the baselines by a large margin.

{{< /ci-details >}}

{{< ci-details summary="Empirical Methods for Compound Splitting (Philipp Koehn et al., 2003)">}}

Philipp Koehn, Kevin Knight. (2003)  
**Empirical Methods for Compound Splitting**  
EACL  
[Paper Link](https://www.semanticscholar.org/paper/cdaae7a8f0db8b280266606004f1c6f164a13f6d)  
Influential Citation Count (41), SS-ID (cdaae7a8f0db8b280266606004f1c6f164a13f6d)  

**ABSTRACT**  
Compounded words are a challenge for NLP applications such as machine translation (MT). We introduce methods to learn splitting rules from monolingual and parallel corpora. We evaluate them against a gold standard and measure their impact on performance of statistical MT systems. Results show accuracy of 99.1% and performance gains for MT of 0.039 BLEU on a German-English noun phrase translation task.

{{< /ci-details >}}

{{< ci-details summary="Sequence to Sequence Learning with Neural Networks (Ilya Sutskever et al., 2014)">}}

Ilya Sutskever, Oriol Vinyals, Quoc V. Le. (2014)  
**Sequence to Sequence Learning with Neural Networks**  
NIPS  
[Paper Link](https://www.semanticscholar.org/paper/cea967b59209c6be22829699f05b8b1ac4dc092d)  
Influential Citation Count (1289), SS-ID (cea967b59209c6be22829699f05b8b1ac4dc092d)  

**ABSTRACT**  
Deep Neural Networks (DNNs) are powerful models that have achieved excellent performance on difficult learning tasks. Although DNNs work well whenever large labeled training sets are available, they cannot be used to map sequences to sequences. In this paper, we present a general end-to-end approach to sequence learning that makes minimal assumptions on the sequence structure. Our method uses a multilayered Long Short-Term Memory (LSTM) to map the input sequence to a vector of a fixed dimensionality, and then another deep LSTM to decode the target sequence from the vector. Our main result is that on an English to French translation task from the WMT-14 dataset, the translations produced by the LSTM achieve a BLEU score of 34.8 on the entire test set, where the LSTM's BLEU score was penalized on out-of-vocabulary words. Additionally, the LSTM did not have difficulty on long sentences. For comparison, a phrase-based SMT system achieves a BLEU score of 33.3 on the same dataset. When we used the LSTM to rerank the 1000 hypotheses produced by the aforementioned SMT system, its BLEU score increases to 36.5, which is close to the previous state of the art. The LSTM also learned sensible phrase and sentence representations that are sensitive to word order and are relatively invariant to the active and the passive voice. Finally, we found that reversing the order of the words in all source sentences (but not target sentences) improved the LSTM's performance markedly, because doing so introduced many short term dependencies between the source and the target sentence which made the optimization problem easier.

{{< /ci-details >}}

{{< ci-details summary="The Edinburgh/JHU Phrase-based Machine Translation Systems for WMT 2015 (B. Haddow et al., 2015)">}}

B. Haddow, Matthias Huck, Alexandra Birch, Nikolay Bogoychev, Philipp Koehn. (2015)  
**The Edinburgh/JHU Phrase-based Machine Translation Systems for WMT 2015**  
WMT@EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/d8c5e6adf7023def3be0bee91799e18607cf588f)  
Influential Citation Count (0), SS-ID (d8c5e6adf7023def3be0bee91799e18607cf588f)  

**ABSTRACT**  
This paper describes the submission of the University of Edinburgh and the Johns Hopkins University for the shared translation task of the EMNLP 2015 Tenth Workshop on Statistical Machine Translation (WMT 2015). We set up phrase-based statistical machine translation systems for all ten language pairs of this year’s evaluation campaign, which are English paired with Czech, Finnish, French, German, and Russian in both translation directions. Novel research directions we investigated include: neural network language models and bilingual neural network language models, a comprehensive use of word classes, and sparse lexicalized reordering features.

{{< /ci-details >}}

{{< ci-details summary="A New Algorithm For Data Compression (R. Uma, 2013)">}}

R. Uma. (2013)  
**A New Algorithm For Data Compression**  
  
[Paper Link](https://www.semanticscholar.org/paper/db734a0e1dc65fe3fe2eef474aefba6d083f54dd)  
Influential Citation Count (1), SS-ID (db734a0e1dc65fe3fe2eef474aefba6d083f54dd)  

**ABSTRACT**  


{{< /ci-details >}}

{{< ci-details summary="Morphology-aware statistical machine translation based on morphs induced in an unsupervised manner (Sami Virpioja et al., 2007)">}}

Sami Virpioja, Jaakko J. Väyrynen, Mathias Creutz, Markus Sadeniemi. (2007)  
**Morphology-aware statistical machine translation based on morphs induced in an unsupervised manner**  
MTSUMMIT  
[Paper Link](https://www.semanticscholar.org/paper/dca029eafe302034f0e7784b9266403938c55263)  
Influential Citation Count (6), SS-ID (dca029eafe302034f0e7784b9266403938c55263)  

**ABSTRACT**  
In this paper, we apply a method of unsupervised morphology learning to a state-of-the-art phrase-based statistical ma chine translation (SMT) system. In SMT, words are traditionally used as the smallest units of translation. Such a system generalizes poorl y to word forms that do not occur in the training data. In particular, this is problematic for languages that are highly compounding, highly inflecting, or both. An alternative way is to use sub-word units, such as morphemes. We use the Morfessor algorithm to find statistical mo rphemelike units (called morphs) that can be used to reduce the size of the lexicon and improve the ability to generalize. Transl ation and language models are trained directly on morphs instead of words. The approach is tested on three Nordic languages (Danish, Finnish, and Swedish) that are included in the Europarl corpus consisting of the Proceedings of the European Parliament. However, in our experiments we did not obtain higher BLEU scores for the morph model than for the standard word-based approach. Nonetheless, the proposed morph-based solution has clear benefits, as morpho logically well motivated structures (phrases) are learned , and the proportion of words left untranslated is clearly reduced.

{{< /ci-details >}}

{{< ci-details summary="Can We Translate Letters? (David Vilar et al., 2007)">}}

David Vilar, Jan-Thorsten Peter, H. Ney. (2007)  
**Can We Translate Letters?**  
WMT@ACL  
[Paper Link](https://www.semanticscholar.org/paper/e9ad27106dd487893bcc1cc12bbf645168c60f87)  
Influential Citation Count (8), SS-ID (e9ad27106dd487893bcc1cc12bbf645168c60f87)  

**ABSTRACT**  
Current statistical machine translation systems handle the translation process as the transformation of a string of symbols into another string of symbols. Normally the symbols dealt with are the words in different languages, sometimes with some additional information included, like morphological data. In this work we try to push the approach to the limit, working not on the level of words, but treating both the source and target sentences as a string of letters. We try to find out if a nearly unmodified state-of-the-art translation system is able to cope with the problem and whether it is capable to further generalize translation rules, for example at the level of word suffixes and translation of unseen words. Experiments are carried out for the translation of Catalan to Spanish.

{{< /ci-details >}}

{{< ci-details summary="Modelling out-of-vocabulary words for robust speech recognition (Issam Bazzi et al., 2002)">}}

Issam Bazzi, James R. Glass. (2002)  
**Modelling out-of-vocabulary words for robust speech recognition**  
  
[Paper Link](https://www.semanticscholar.org/paper/ec5f929b57cf12b4d624ab125f337c14ad642ab1)  
Influential Citation Count (9), SS-ID (ec5f929b57cf12b4d624ab125f337c14ad642ab1)  

**ABSTRACT**  
This thesis concerns the problem of unknown or out-of-vocabulary (OOV) words in continuous speech recognition.  We propose a novel approach for handling OOV words within a single-stage recognition framework. To achieve this goal, an explicit and detailed model of OOV words is constructed and then used to augment the closed-vocabulary search space of a standard speech recognizer. This OOV model achieves open-vocabulary recognition through the use of more flexible subword units that can be concatenated during recognition to form new phone sequences corresponding to potential new words. Examples of such subword units are phones, syllables, or some automatically-learned multi-phone sequences. Subword units have the attractive property of being a closed set, and thus are able to cover any new words, and can conceivably cover most utterances with partially spoken words as well.  The main challenge with such an approach is ensuring that the OOV model does not absorb portions of the speech signal corresponding to in-vocabulary (IV) words. In dealing with this challenge, we explore several research issues related to designing the subword lexicon, language model, and topology of the OOV model. We present a dictionary-based approach for estimating subword language models. Such language models are utilized within the subword search space to help recognize the underlying phonetic transcription of OOV words. We also propose a data-driven iterative bottom-up procedure for automatically creating a multi-phone subword inventory. Starting with individual phones, this procedure uses the maximum mutual information principle to successively merge phones to obtain longer subword units.  The thesis also extends this OOV approach to modelling multiple classes of OOV words.  In addition, the thesis examines an approach for combining OOV modelling with recognition confidence scoring. (Copies available exclusively from MIT Libraries, Rm. 14-0551, Cambridge, MA 02139-4307. Ph. 617-253-5668; Fax 617-253-1690.)

{{< /ci-details >}}

{{< ci-details summary="Integrating an Unsupervised Transliteration Model into Statistical Machine Translation (Nadir Durrani et al., 2014)">}}

Nadir Durrani, Hassan Sajjad, Hieu Hoang, Philipp Koehn. (2014)  
**Integrating an Unsupervised Transliteration Model into Statistical Machine Translation**  
EACL  
[Paper Link](https://www.semanticscholar.org/paper/fa144b01862baa5de61d22fd3f922a3ddd54ac4d)  
Influential Citation Count (3), SS-ID (fa144b01862baa5de61d22fd3f922a3ddd54ac4d)  

**ABSTRACT**  
We investigate three methods for integrating an unsupervised transliteration model into an end-to-end SMT system. We induce a transliteration model from parallel data and use it to translate OOV words. Our approach is fully unsupervised and language independent. In the methods to integrate transliterations, we observed improvements from 0.23-0.75 ( 0.41) BLEU points across 7 language pairs. We also show that our mined transliteration corpora provide better rule coverage and translation quality compared to the gold standard transliteration corpora.

{{< /ci-details >}}

{{< ci-details summary="Neural Machine Translation by Jointly Learning to Align and Translate (Dzmitry Bahdanau et al., 2014)">}}

Dzmitry Bahdanau, Kyunghyun Cho, Yoshua Bengio. (2014)  
**Neural Machine Translation by Jointly Learning to Align and Translate**  
ICLR  
[Paper Link](https://www.semanticscholar.org/paper/fa72afa9b2cbc8f0d7b05d52548906610ffbb9c5)  
Influential Citation Count (2464), SS-ID (fa72afa9b2cbc8f0d7b05d52548906610ffbb9c5)  

**ABSTRACT**  
Neural machine translation is a recently proposed approach to machine translation. Unlike the traditional statistical machine translation, the neural machine translation aims at building a single neural network that can be jointly tuned to maximize the translation performance. The models proposed recently for neural machine translation often belong to a family of encoder-decoders and consists of an encoder that encodes a source sentence into a fixed-length vector from which a decoder generates a translation. In this paper, we conjecture that the use of a fixed-length vector is a bottleneck in improving the performance of this basic encoder-decoder architecture, and propose to extend this by allowing a model to automatically (soft-)search for parts of a source sentence that are relevant to predicting a target word, without having to form these parts as a hard segment explicitly. With this new approach, we achieve a translation performance comparable to the existing state-of-the-art phrase-based system on the task of English-to-French translation. Furthermore, qualitative analysis reveals that the (soft-)alignments found by the model agree well with our intuition.

{{< /ci-details >}}

{{< ci-details summary="Character-based Neural Machine Translation (Wang Ling et al., 2015)">}}

Wang Ling, I. Trancoso, Chris Dyer, A. Black. (2015)  
**Character-based Neural Machine Translation**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/ff1577528a34a11c2a81d2451d346c412c674c02)  
Influential Citation Count (11), SS-ID (ff1577528a34a11c2a81d2451d346c412c674c02)  

**ABSTRACT**  
We introduce a neural machine translation model that views the input and output sentences as sequences of characters rather than words. Since word-level information provides a crucial source of bias, our input model composes representations of character sequences into representations of words (as determined by whitespace boundaries), and then these are translated using a joint attention/translation model. In the target language, the translation is modeled as a sequence of word vectors, but each word is generated one character at a time, conditional on the previous character generations in each word. As the representation and generation of words is performed at the character level, our model is capable of interpreting and generating unseen word forms. A secondary benefit of this approach is that it alleviates much of the challenges associated with preprocessing/tokenization of the source and target languages. We show that our model can achieve translation results that are on par with conventional word-based models.

{{< /ci-details >}}

