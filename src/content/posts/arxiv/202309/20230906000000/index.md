---
draft: false
title: "arXiv @ 2023.09.06"
date: 2023-09-06
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.09.06"
    identifier: arxiv_20230906
    parent: 202309_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.CV (30)](#cscv-30)
- [cs.CR (3)](#cscr-3)
- [cs.CL (20)](#cscl-20)
- [cs.LG (18)](#cslg-18)
- [eess.IV (4)](#eessiv-4)
- [cs.SE (3)](#csse-3)
- [cs.IR (2)](#csir-2)
- [q-bio.GN (1)](#q-biogn-1)
- [cs.DC (2)](#csdc-2)
- [cs.SI (1)](#cssi-1)
- [cs.AI (4)](#csai-4)
- [cs.AR (1)](#csar-1)
- [cs.RO (1)](#csro-1)
- [cs.SD (3)](#cssd-3)
- [cs.LO (1)](#cslo-1)
- [cs.NI (1)](#csni-1)
- [math.OC (1)](#mathoc-1)
- [cs.HC (1)](#cshc-1)
- [cs.SC (1)](#cssc-1)

## cs.CV (30)



### (1/98) Attention-Driven Multi-Modal Fusion: Enhancing Sign Language Recognition and Translation (Zaber Ibn Abdul Hakim et al., 2023)

{{<citation>}}

Zaber Ibn Abdul Hakim, Rasman Mubtasim Swargo, Muhammad Abdullah Adnan. (2023)  
**Attention-Driven Multi-Modal Fusion: Enhancing Sign Language Recognition and Translation**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs-LG, cs.CV  
Keywords: Attention, BLEU  
[Paper Link](http://arxiv.org/abs/2309.01860v2)  

---


**ABSTRACT**  
In this paper, we devise a mechanism for the addition of multi-modal information with an existing pipeline for continuous sign language recognition and translation. In our procedure, we have incorporated optical flow information with RGB images to enrich the features with movement-related information. This work studies the feasibility of such modality inclusion using a cross-modal encoder. The plugin we have used is very lightweight and doesn't need to include a separate feature extractor for the new modality in an end-to-end manner. We have applied the changes in both sign language recognition and translation, improving the result in each case. We have evaluated the performance on the RWTH-PHOENIX-2014 dataset for sign language recognition and the RWTH-PHOENIX-2014T dataset for translation. On the recognition task, our approach reduced the WER by 0.9, and on the translation task, our approach increased most of the BLEU scores by ~0.6 on the test set.

{{</citation>}}


### (2/98) NLLB-CLIP -- train performant multilingual image retrieval model on a budget (Alexander Visheratin, 2023)

{{<citation>}}

Alexander Visheratin. (2023)  
**NLLB-CLIP -- train performant multilingual image retrieval model on a budget**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01859v1)  

---


**ABSTRACT**  
Today, the exponential rise of large models developed by academic and industrial institutions with the help of massive computing resources raises the question of whether someone without access to such resources can make a valuable scientific contribution. To explore this, we tried to solve the challenging task of multilingual image retrieval having a limited budget of $1,000. As a result, we present NLLB-CLIP - CLIP model with a text encoder from the NLLB model. To train the model, we used an automatically created dataset of 106,246 good-quality images with captions in 201 languages derived from the LAION COCO dataset. We trained multiple models using image and text encoders of various sizes and kept different parts of the model frozen during the training. We thoroughly analyzed the trained models using existing evaluation datasets and newly created XTD200 and Flickr30k-200 datasets. We show that NLLB-CLIP is comparable in quality to state-of-the-art models and significantly outperforms them on low-resource languages.

{{</citation>}}


### (3/98) Towards Universal Image Embeddings: A Large-Scale Dataset and Challenge for Generic Image Representations (Nikolaos-Antonios Ypsilantis et al., 2023)

{{<citation>}}

Nikolaos-Antonios Ypsilantis, Kaifeng Chen, Bingyi Cao, Mário Lipovský, Pelin Dogan-Schönberger, Grzegorz Makosa, Boris Bluntschli, Mojtaba Seyedhosseini, Ondřej Chum, André Araujo. (2023)  
**Towards Universal Image Embeddings: A Large-Scale Dataset and Challenge for Generic Image Representations**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2309.01858v1)  

---


**ABSTRACT**  
Fine-grained and instance-level recognition methods are commonly trained and evaluated on specific domains, in a model per domain scenario. Such an approach, however, is impractical in real large-scale applications. In this work, we address the problem of universal image embedding, where a single universal model is trained and used in multiple domains. First, we leverage existing domain-specific datasets to carefully construct a new large-scale public benchmark for the evaluation of universal image embeddings, with 241k query images, 1.4M index images and 2.8M training images across 8 different domains and 349k classes. We define suitable metrics, training and evaluation protocols to foster future research in this area. Second, we provide a comprehensive experimental evaluation on the new dataset, demonstrating that existing approaches and simplistic extensions lead to worse performance than an assembly of models trained for each domain separately. Finally, we conducted a public research competition on this topic, leveraging industrial datasets, which attracted the participation of more than 1k teams worldwide. This exercise generated many interesting research ideas and findings which we present in detail. Project webpage: https://cmp.felk.cvut.cz/univ_emb/

{{</citation>}}


### (4/98) Uncertainty in AI: Evaluating Deep Neural Networks on Out-of-Distribution Images (Jamiu Idowu et al., 2023)

{{<citation>}}

Jamiu Idowu, Ahmed Almasoud. (2023)  
**Uncertainty in AI: Evaluating Deep Neural Networks on Out-of-Distribution Images**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI, Google  
[Paper Link](http://arxiv.org/abs/2309.01850v1)  

---


**ABSTRACT**  
As AI models are increasingly deployed in critical applications, ensuring the consistent performance of models when exposed to unusual situations such as out-of-distribution (OOD) or perturbed data, is important. Therefore, this paper investigates the uncertainty of various deep neural networks, including ResNet-50, VGG16, DenseNet121, AlexNet, and GoogleNet, when dealing with such data. Our approach includes three experiments. First, we used the pretrained models to classify OOD images generated via DALL-E to assess their performance. Second, we built an ensemble from the models' predictions using probabilistic averaging for consensus due to its advantages over plurality or majority voting. The ensemble's uncertainty was quantified using average probabilities, variance, and entropy metrics. Our results showed that while ResNet-50 was the most accurate single model for OOD images, the ensemble performed even better, correctly classifying all images. Third, we tested model robustness by adding perturbations (filters, rotations, etc.) to new epistemic images from DALL-E or real-world captures. ResNet-50 was chosen for this being the best performing model. While it classified 4 out of 5 unperturbed images correctly, it misclassified all of them post-perturbation, indicating a significant vulnerability. These misclassifications, which are clear to human observers, highlight AI models' limitations. Using saliency maps, we identified regions of the images that the model considered important for their decisions.

{{</citation>}}


### (5/98) On the fly Deep Neural Network Optimization Control for Low-Power Computer Vision (Ishmeet Kaur et al., 2023)

{{<citation>}}

Ishmeet Kaur, Adwaita Janardhan Jadhav. (2023)  
**On the fly Deep Neural Network Optimization Control for Low-Power Computer Vision**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Computer Vision  
[Paper Link](http://arxiv.org/abs/2309.01824v1)  

---


**ABSTRACT**  
Processing visual data on mobile devices has many applications, e.g., emergency response and tracking. State-of-the-art computer vision techniques rely on large Deep Neural Networks (DNNs) that are usually too power-hungry to be deployed on resource-constrained edge devices. Many techniques improve the efficiency of DNNs by using sparsity or quantization. However, the accuracy and efficiency of these techniques cannot be adapted for diverse edge applications with different hardware constraints and accuracy requirements. This paper presents a novel technique to allow DNNs to adapt their accuracy and energy consumption during run-time, without the need for any re-training. Our technique called AdaptiveActivation introduces a hyper-parameter that controls the output range of the DNNs' activation function to dynamically adjust the sparsity and precision in the DNN. AdaptiveActivation can be applied to any existing pre-trained DNN to improve their deployability in diverse edge environments. We conduct experiments on popular edge devices and show that the accuracy is within 1.5% of the baseline. We also show that our approach requires 10%--38% less memory than the baseline techniques leading to more accuracy-efficiency tradeoff options

{{</citation>}}


### (6/98) No Data Augmentation? Alternative Regularizations for Effective Training on Small Datasets (Lorenzo Brigato et al., 2023)

{{<citation>}}

Lorenzo Brigato, Stavroula Mougiakakou. (2023)  
**No Data Augmentation? Alternative Regularizations for Effective Training on Small Datasets**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: AI, Augmentation  
[Paper Link](http://arxiv.org/abs/2309.01694v1)  

---


**ABSTRACT**  
Solving image classification tasks given small training datasets remains an open challenge for modern computer vision. Aggressive data augmentation and generative models are among the most straightforward approaches to overcoming the lack of data. However, the first fails to be agnostic to varying image domains, while the latter requires additional compute and careful design. In this work, we study alternative regularization strategies to push the limits of supervised learning on small image classification datasets. In particular, along with the model size and training schedule scaling, we employ a heuristic to select (semi) optimal learning rate and weight decay couples via the norm of model parameters. By training on only 1% of the original CIFAR-10 training set (i.e., 50 images per class) and testing on ciFAIR-10, a variant of the original CIFAR without duplicated images, we reach a test accuracy of 66.5%, on par with the best state-of-the-art methods.

{{</citation>}}


### (7/98) Mask-Attention-Free Transformer for 3D Instance Segmentation (Xin Lai et al., 2023)

{{<citation>}}

Xin Lai, Yuhui Yuan, Ruihang Chu, Yukang Chen, Han Hu, Jiaya Jia. (2023)  
**Mask-Attention-Free Transformer for 3D Instance Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Transformer  
[Paper Link](http://arxiv.org/abs/2309.01692v1)  

---


**ABSTRACT**  
Recently, transformer-based methods have dominated 3D instance segmentation, where mask attention is commonly involved. Specifically, object queries are guided by the initial instance masks in the first cross-attention, and then iteratively refine themselves in a similar manner. However, we observe that the mask-attention pipeline usually leads to slow convergence due to low-recall initial instance masks. Therefore, we abandon the mask attention design and resort to an auxiliary center regression task instead. Through center regression, we effectively overcome the low-recall issue and perform cross-attention by imposing positional prior. To reach this goal, we develop a series of position-aware designs. First, we learn a spatial distribution of 3D locations as the initial position queries. They spread over the 3D space densely, and thus can easily capture the objects in a scene with a high recall. Moreover, we present relative position encoding for the cross-attention and iterative refinement for more accurate position queries. Experiments show that our approach converges 4x faster than existing work, sets a new state of the art on ScanNetv2 3D instance segmentation benchmark, and also demonstrates superior performance across various datasets. Code and models are available at https://github.com/dvlab-research/Mask-Attention-Free-Transformer.

{{</citation>}}


### (8/98) Prior Knowledge Guided Network for Video Anomaly Detection (Zhewen Deng et al., 2023)

{{<citation>}}

Zhewen Deng, Dongyue Chen, Shizhuo Deng. (2023)  
**Prior Knowledge Guided Network for Video Anomaly Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2309.01682v1)  

---


**ABSTRACT**  
Video Anomaly Detection (VAD) involves detecting anomalous events in videos, presenting a significant and intricate task within intelligent video surveillance. Existing studies often concentrate solely on features acquired from limited normal data, disregarding the latent prior knowledge present in extensive natural image datasets. To address this constraint, we propose a Prior Knowledge Guided Network(PKG-Net) for the VAD task. First, an auto-encoder network is incorporated into a teacher-student architecture to learn two designated proxy tasks: future frame prediction and teacher network imitation, which can provide better generalization ability on unknown samples. Second, knowledge distillation on proper feature blocks is also proposed to increase the multi-scale detection ability of the model. In addition, prediction error and teacher-student feature inconsistency are combined to evaluate anomaly scores of inference samples more comprehensively. Experimental results on three public benchmarks validate the effectiveness and accuracy of our method, which surpasses recent state-of-the-arts.

{{</citation>}}


### (9/98) Relay Diffusion: Unifying diffusion process across resolutions for image synthesis (Jiayan Teng et al., 2023)

{{<citation>}}

Jiayan Teng, Wendi Zheng, Ming Ding, Wenyi Hong, Jianqiao Wangni, Zhuoyi Yang, Jie Tang. (2023)  
**Relay Diffusion: Unifying diffusion process across resolutions for image synthesis**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2309.03350v1)  

---


**ABSTRACT**  
Diffusion models achieved great success in image synthesis, but still face challenges in high-resolution generation. Through the lens of discrete cosine transformation, we find the main reason is that \emph{the same noise level on a higher resolution results in a higher Signal-to-Noise Ratio in the frequency domain}. In this work, we present Relay Diffusion Model (RDM), which transfers a low-resolution image or noise into an equivalent high-resolution one for diffusion model via blurring diffusion and block noise. Therefore, the diffusion process can continue seamlessly in any new resolution or model without restarting from pure noise or low-resolution conditioning. RDM achieves state-of-the-art FID on CelebA-HQ and sFID on ImageNet 256$\times$256, surpassing previous works such as ADM, LDM and DiT by a large margin. All the codes and checkpoints are open-sourced at \url{https://github.com/THUDM/RelayDiffusion}.

{{</citation>}}


### (10/98) AGG-Net: Attention Guided Gated-convolutional Network for Depth Image Completion (Dongyue Chen et al., 2023)

{{<citation>}}

Dongyue Chen, Tingxuan Huang, Zhimin Song, Shizhuo Deng, Tong Jia. (2023)  
**AGG-Net: Attention Guided Gated-convolutional Network for Depth Image Completion**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2309.01624v1)  

---


**ABSTRACT**  
Recently, stereo vision based on lightweight RGBD cameras has been widely used in various fields. However, limited by the imaging principles, the commonly used RGB-D cameras based on TOF, structured light, or binocular vision acquire some invalid data inevitably, such as weak reflection, boundary shadows, and artifacts, which may bring adverse impacts to the follow-up work. In this paper, we propose a new model for depth image completion based on the Attention Guided Gated-convolutional Network (AGG-Net), through which more accurate and reliable depth images can be obtained from the raw depth maps and the corresponding RGB images. Our model employs a UNet-like architecture which consists of two parallel branches of depth and color features. In the encoding stage, an Attention Guided Gated-Convolution (AG-GConv) module is proposed to realize the fusion of depth and color features at different scales, which can effectively reduce the negative impacts of invalid depth data on the reconstruction. In the decoding stage, an Attention Guided Skip Connection (AG-SC) module is presented to avoid introducing too many depth-irrelevant features to the reconstruction. The experimental results demonstrate that our method outperforms the state-of-the-art methods on the popular benchmarks NYU-Depth V2, DIML, and SUN RGB-D.

{{</citation>}}


### (11/98) Hindering Adversarial Attacks with Multiple Encrypted Patch Embeddings (AprilPyone MaungMaung et al., 2023)

{{<citation>}}

AprilPyone MaungMaung, Isao Echizen, Hitoshi Kiya. (2023)  
**Hindering Adversarial Attacks with Multiple Encrypted Patch Embeddings**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Adversarial Attack, Embedding, ImageNet  
[Paper Link](http://arxiv.org/abs/2309.01620v1)  

---


**ABSTRACT**  
In this paper, we propose a new key-based defense focusing on both efficiency and robustness. Although the previous key-based defense seems effective in defending against adversarial examples, carefully designed adaptive attacks can bypass the previous defense, and it is difficult to train the previous defense on large datasets like ImageNet. We build upon the previous defense with two major improvements: (1) efficient training and (2) optional randomization. The proposed defense utilizes one or more secret patch embeddings and classifier heads with a pre-trained isotropic network. When more than one secret embeddings are used, the proposed defense enables randomization on inference. Experiments were carried out on the ImageNet dataset, and the proposed defense was evaluated against an arsenal of state-of-the-art attacks, including adaptive ones. The results show that the proposed defense achieves a high robust accuracy and a comparable clean accuracy compared to the previous key-based defense.

{{</citation>}}


### (12/98) On the Query Strategies for Efficient Online Active Distillation (Michele Boldo et al., 2023)

{{<citation>}}

Michele Boldo, Enrico Martini, Mirco De Marchi, Stefano Aldegheri, Nicola Bombieri. (2023)  
**On the Query Strategies for Efficient Online Active Distillation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Active Learning  
[Paper Link](http://arxiv.org/abs/2309.01612v1)  

---


**ABSTRACT**  
Deep Learning (DL) requires lots of time and data, resulting in high computational demands. Recently, researchers employ Active Learning (AL) and online distillation to enhance training efficiency and real-time model adaptation. This paper evaluates a set of query strategies to achieve the best training results. It focuses on Human Pose Estimation (HPE) applications, assessing the impact of selected frames during training using two approaches: a classical offline method and a online evaluation through a continual learning approach employing knowledge distillation, on a popular state-of-the-art HPE dataset. The paper demonstrates the possibility of enabling training at the edge lightweight models, adapting them effectively to new contexts in real-time.

{{</citation>}}


### (13/98) Improving Visual Quality and Transferability of Adversarial Attacks on Face Recognition Simultaneously with Adversarial Restoration (Fengfan Zhou et al., 2023)

{{<citation>}}

Fengfan Zhou, Hefei Ling, Yuxuan Shi, Jiazhong Chen, Ping Li. (2023)  
**Improving Visual Quality and Transferability of Adversarial Attacks on Face Recognition Simultaneously with Adversarial Restoration**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Adversarial Attack  
[Paper Link](http://arxiv.org/abs/2309.01582v2)  

---


**ABSTRACT**  
Adversarial face examples possess two critical properties: Visual Quality and Transferability. However, existing approaches rarely address these properties simultaneously, leading to subpar results. To address this issue, we propose a novel adversarial attack technique known as Adversarial Restoration (AdvRestore), which enhances both visual quality and transferability of adversarial face examples by leveraging a face restoration prior. In our approach, we initially train a Restoration Latent Diffusion Model (RLDM) designed for face restoration. Subsequently, we employ the inference process of RLDM to generate adversarial face examples. The adversarial perturbations are applied to the intermediate features of RLDM. Additionally, by treating RLDM face restoration as a sibling task, the transferability of the generated adversarial face examples is further improved. Our experimental results validate the effectiveness of the proposed attack method.

{{</citation>}}


### (14/98) Locality-Aware Hyperspectral Classification (Fangqin Zhou et al., 2023)

{{<citation>}}

Fangqin Zhou, Mert Kilickaya, Joaquin Vanschoren. (2023)  
**Locality-Aware Hyperspectral Classification**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2309.01561v1)  

---


**ABSTRACT**  
Hyperspectral image classification is gaining popularity for high-precision vision tasks in remote sensing, thanks to their ability to capture visual information available in a wide continuum of spectra. Researchers have been working on automating Hyperspectral image classification, with recent efforts leveraging Vision-Transformers. However, most research models only spectra information and lacks attention to the locality (i.e., neighboring pixels), which may be not sufficiently discriminative, resulting in performance limitations. To address this, we present three contributions: i) We introduce the Hyperspectral Locality-aware Image TransformEr (HyLITE), a vision transformer that models both local and spectral information, ii) A novel regularization function that promotes the integration of local-to-global information, and iii) Our proposed approach outperforms competing baselines by a significant margin, achieving up to 10% gains in accuracy. The trained models and the code are available at HyLITE.

{{</citation>}}


### (15/98) Parameter and Computation Efficient Transfer Learning for Vision-Language Pre-trained Models (Qiong Wu et al., 2023)

{{<citation>}}

Qiong Wu, Wei Yu, Yiyi Zhou, Shubin Huang, Xiaoshuai Sun, Rongrong Ji. (2023)  
**Parameter and Computation Efficient Transfer Learning for Vision-Language Pre-trained Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2309.01479v2)  

---


**ABSTRACT**  
With ever increasing parameters and computation, vision-language pre-trained (VLP) models exhibit prohibitive expenditure in downstream task adaption. Recent endeavors mainly focus on parameter efficient transfer learning (PETL) for VLP models by only updating a small number of parameters. However, excessive computational overhead still plagues the application of VLPs. In this paper, we aim at parameter and computation efficient transfer learning (PCETL) for VLP models. In particular, PCETL not only needs to limit the number of trainable parameters in VLP models, but also to reduce the computational redundancy during inference, thus enabling a more efficient transfer. To approach this target, we propose a novel dynamic architecture skipping (DAS) approach towards effective PCETL. Instead of directly optimizing the intrinsic architectures of VLP models, DAS first observes the significances of their modules to downstream tasks via a reinforcement learning (RL) based process, and then skips the redundant ones with lightweight networks, i.e., adapters, according to the obtained rewards. In this case, the VLP model can well maintain the scale of trainable parameters while speeding up its inference on downstream tasks. To validate DAS, we apply it to two representative VLP models, namely ViLT and METER, and conduct extensive experiments on a bunch of VL tasks. The experimental results not only show the great advantages of DAS in reducing computational complexity, e.g. -11.97% FLOPs of METER on VQA2.0, but also confirm its competitiveness against existing PETL methods in terms of parameter scale and performance. Our source code is given in our appendix.

{{</citation>}}


### (16/98) Large Separable Kernel Attention: Rethinking the Large Kernel Attention Design in CNN (Kin Wai Lau et al., 2023)

{{<citation>}}

Kin Wai Lau, Lai-Man Po, Yasar Abbas Ur Rehman. (2023)  
**Large Separable Kernel Attention: Rethinking the Large Kernel Attention Design in CNN**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, ImageNet, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2309.01439v2)  

---


**ABSTRACT**  
Visual Attention Networks (VAN) with Large Kernel Attention (LKA) modules have been shown to provide remarkable performance, that surpasses Vision Transformers (ViTs), on a range of vision-based tasks. However, the depth-wise convolutional layer in these LKA modules incurs a quadratic increase in the computational and memory footprints with increasing convolutional kernel size. To mitigate these problems and to enable the use of extremely large convolutional kernels in the attention modules of VAN, we propose a family of Large Separable Kernel Attention modules, termed LSKA. LSKA decomposes the 2D convolutional kernel of the depth-wise convolutional layer into cascaded horizontal and vertical 1-D kernels. In contrast to the standard LKA design, the proposed decomposition enables the direct use of the depth-wise convolutional layer with large kernels in the attention module, without requiring any extra blocks. We demonstrate that the proposed LSKA module in VAN can achieve comparable performance with the standard LKA module and incur lower computational complexity and memory footprints. We also find that the proposed LSKA design biases the VAN more toward the shape of the object than the texture with increasing kernel size. Additionally, we benchmark the robustness of the LKA and LSKA in VAN, ViTs, and the recent ConvNeXt on the five corrupted versions of the ImageNet dataset that are largely unexplored in the previous works. Our extensive experimental results show that the proposed LSKA module in VAN provides a significant reduction in computational complexity and memory footprints with increasing kernel size while outperforming ViTs, ConvNeXt, and providing similar performance compared to the LKA module in VAN on object recognition, object detection, semantic segmentation, and robustness tests.

{{</citation>}}


### (17/98) DAT++: Spatially Dynamic Vision Transformer with Deformable Attention (Zhuofan Xia et al., 2023)

{{<citation>}}

Zhuofan Xia, Xuran Pan, Shiji Song, Li Erran Li, Gao Huang. (2023)  
**DAT++: Spatially Dynamic Vision Transformer with Deformable Attention**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, ImageNet, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2309.01430v1)  

---


**ABSTRACT**  
Transformers have shown superior performance on various vision tasks. Their large receptive field endows Transformer models with higher representation power than their CNN counterparts. Nevertheless, simply enlarging the receptive field also raises several concerns. On the one hand, using dense attention in ViT leads to excessive memory and computational cost, and features can be influenced by irrelevant parts that are beyond the region of interests. On the other hand, the handcrafted attention adopted in PVT or Swin Transformer is data agnostic and may limit the ability to model long-range relations. To solve this dilemma, we propose a novel deformable multi-head attention module, where the positions of key and value pairs in self-attention are adaptively allocated in a data-dependent way. This flexible scheme enables the proposed deformable attention to dynamically focus on relevant regions while maintains the representation power of global attention. On this basis, we present Deformable Attention Transformer (DAT), a general vision backbone efficient and effective for visual recognition. We further build an enhanced version DAT++. Extensive experiments show that our DAT++ achieves state-of-the-art results on various visual recognition benchmarks, with 85.9% ImageNet accuracy, 54.5 and 47.0 MS-COCO instance segmentation mAP, and 51.5 ADE20K semantic segmentation mIoU.

{{</citation>}}


### (18/98) Leveraging Self-Supervised Vision Transformers for Neural Transfer Function Design (Dominik Engel et al., 2023)

{{<citation>}}

Dominik Engel, Leon Sick, Timo Ropinski. (2023)  
**Leveraging Self-Supervised Vision Transformers for Neural Transfer Function Design**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-GR, cs-LG, cs.CV  
Keywords: Self-Supervised, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2309.01408v1)  

---


**ABSTRACT**  
In volume rendering, transfer functions are used to classify structures of interest, and to assign optical properties such as color and opacity. They are commonly defined as 1D or 2D functions that map simple features to these optical properties. As the process of designing a transfer function is typically tedious and unintuitive, several approaches have been proposed for their interactive specification. In this paper, we present a novel method to define transfer functions for volume rendering by leveraging the feature extraction capabilities of self-supervised pre-trained vision transformers. To design a transfer function, users simply select the structures of interest in a slice viewer, and our method automatically selects similar structures based on the high-level features extracted by the neural network. Contrary to previous learning-based transfer function approaches, our method does not require training of models and allows for quick inference, enabling an interactive exploration of the volume data. Our approach reduces the amount of necessary annotations by interactively informing the user about the current classification, so they can focus on annotating the structures of interest that still require annotation. In practice, this allows users to design transfer functions within seconds, instead of minutes. We compare our method to existing learning-based approaches in terms of annotation and compute time, as well as with respect to segmentation accuracy. Our accompanying video showcases the interactivity and effectiveness of our method.

{{</citation>}}


### (19/98) SSVOD: Semi-Supervised Video Object Detection with Sparse Annotations (Tanvir Mahmud et al., 2023)

{{<citation>}}

Tanvir Mahmud, Chun-Hao Liu, Burhaneddin Yaman, Diana Marculescu. (2023)  
**SSVOD: Semi-Supervised Video Object Detection with Sparse Annotations**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet, Object Detection, Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2309.01391v1)  

---


**ABSTRACT**  
Despite significant progress in semi-supervised learning for image object detection, several key issues are yet to be addressed for video object detection: (1) Achieving good performance for supervised video object detection greatly depends on the availability of annotated frames. (2) Despite having large inter-frame correlations in a video, collecting annotations for a large number of frames per video is expensive, time-consuming, and often redundant. (3) Existing semi-supervised techniques on static images can hardly exploit the temporal motion dynamics inherently present in videos. In this paper, we introduce SSVOD, an end-to-end semi-supervised video object detection framework that exploits motion dynamics of videos to utilize large-scale unlabeled frames with sparse annotations. To selectively assemble robust pseudo-labels across groups of frames, we introduce \textit{flow-warped predictions} from nearby frames for temporal-consistency estimation. In particular, we introduce cross-IoU and cross-divergence based selection methods over a set of estimated predictions to include robust pseudo-labels for bounding boxes and class labels, respectively. To strike a balance between confirmation bias and uncertainty noise in pseudo-labels, we propose confidence threshold based combination of hard and soft pseudo-labels. Our method achieves significant performance improvements over existing methods on ImageNet-VID, Epic-KITCHENS, and YouTube-VIS datasets. Code and pre-trained models will be released.

{{</citation>}}


### (20/98) Metric Learning for Projections Bias of Generalized Zero-shot Learning (Chong Zhang et al., 2023)

{{<citation>}}

Chong Zhang, Mingyu Jin, Qinkai Yu, Haochen Xue, Xiaobo Jin. (2023)  
**Metric Learning for Projections Bias of Generalized Zero-shot Learning**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2309.01390v1)  

---


**ABSTRACT**  
Generalized zero-shot learning models (GZSL) aim to recognize samples from seen or unseen classes using only samples from seen classes as training data. During inference, GZSL methods are often biased towards seen classes due to the visibility of seen class samples during training. Most current GZSL methods try to learn an accurate projection function (from visual space to semantic space) to avoid bias and ensure the effectiveness of GZSL methods. However, during inference, the computation of distance will be important when we classify the projection of any sample into its nearest class since we may learn a biased projection function in the model. In our work, we attempt to learn a parameterized Mahalanobis distance within the framework of VAEGAN (Variational Autoencoder \& Generative Adversarial Networks), where the weight matrix depends on the network's output. In particular, we improved the network structure of VAEGAN to leverage the discriminative models of two branches to separately predict the seen samples and the unseen samples generated by this seen one. We proposed a new loss function with two branches to help us learn the optimized Mahalanobis distance representation. Comprehensive evaluation benchmarks on four datasets demonstrate the superiority of our method over the state-of-the-art counterparts. Our codes are available at https://anonymous.4open.science/r/111hxr.

{{</citation>}}


### (21/98) LoRA-like Calibration for Multimodal Deception Detection using ATSFace Data (Shun-Wen Hsiao et al., 2023)

{{<citation>}}

Shun-Wen Hsiao, Cheng-Yuan Sun. (2023)  
**LoRA-like Calibration for Multimodal Deception Detection using ATSFace Data**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01383v1)  

---


**ABSTRACT**  
Recently, deception detection on human videos is an eye-catching techniques and can serve lots applications. AI model in this domain demonstrates the high accuracy, but AI tends to be a non-interpretable black box. We introduce an attention-aware neural network addressing challenges inherent in video data and deception dynamics. This model, through its continuous assessment of visual, audio, and text features, pinpoints deceptive cues. We employ a multimodal fusion strategy that enhances accuracy; our approach yields a 92\% accuracy rate on a real-life trial dataset. Most important of all, the model indicates the attention focus in the videos, providing valuable insights on deception cues. Hence, our method adeptly detects deceit and elucidates the underlying process. We further enriched our study with an experiment involving students answering questions either truthfully or deceitfully, resulting in a new dataset of 309 video clips, named ATSFace. Using this, we also introduced a calibration method, which is inspired by Low-Rank Adaptation (LoRA), to refine individual-based deception detection accuracy.

{{</citation>}}


### (22/98) Understanding Video Scenes through Text: Insights from Text-based Video Question Answering (Soumya Jahagirdar et al., 2023)

{{<citation>}}

Soumya Jahagirdar, Minesh Mathew, Dimosthenis Karatzas, C. V. Jawahar. (2023)  
**Understanding Video Scenes through Text: Insights from Text-based Video Question Answering**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: BERT, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2309.01380v1)  

---


**ABSTRACT**  
Researchers have extensively studied the field of vision and language, discovering that both visual and textual content is crucial for understanding scenes effectively. Particularly, comprehending text in videos holds great significance, requiring both scene text understanding and temporal reasoning. This paper focuses on exploring two recently introduced datasets, NewsVideoQA and M4-ViteVQA, which aim to address video question answering based on textual content. The NewsVideoQA dataset contains question-answer pairs related to the text in news videos, while M4-ViteVQA comprises question-answer pairs from diverse categories like vlogging, traveling, and shopping. We provide an analysis of the formulation of these datasets on various levels, exploring the degree of visual understanding and multi-frame comprehension required for answering the questions. Additionally, the study includes experimentation with BERT-QA, a text-only model, which demonstrates comparable performance to the original methods on both datasets, indicating the shortcomings in the formulation of these datasets. Furthermore, we also look into the domain adaptation aspect by examining the effectiveness of training on M4-ViteVQA and evaluating on NewsVideoQA and vice-versa, thereby shedding light on the challenges and potential benefits of out-of-domain training.

{{</citation>}}


### (23/98) Attention as Annotation: Generating Images and Pseudo-masks for Weakly Supervised Semantic Segmentation with Diffusion (Ryota Yoshihashi et al., 2023)

{{<citation>}}

Ryota Yoshihashi, Yuya Otsuka, Kenji Doi, Tomohiro Tanaka. (2023)  
**Attention as Annotation: Generating Images and Pseudo-masks for Weakly Supervised Semantic Segmentation with Diffusion**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, ImageNet, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2309.01369v1)  

---


**ABSTRACT**  
Although recent advancements in diffusion models enabled high-fidelity and diverse image generation, training of discriminative models largely depends on collections of massive real images and their manual annotation. Here, we present a training method for semantic segmentation that neither relies on real images nor manual annotation. The proposed method {\it attn2mask} utilizes images generated by a text-to-image diffusion model in combination with its internal text-to-image cross-attention as supervisory pseudo-masks. Since the text-to-image generator is trained with image-caption pairs but without pixel-wise labels, attn2mask can be regarded as a weakly supervised segmentation method overall. Experiments show that attn2mask achieves promising results in PASCAL VOC for not using real training data for segmentation at all, and it is also useful to scale up segmentation to a more-class scenario, i.e., ImageNet segmentation. It also shows adaptation ability with LoRA-based fine-tuning, which enables the transfer to a distant domain i.e., Cityscapes.

{{</citation>}}


### (24/98) Refined Temporal Pyramidal Compression-and-Amplification Transformer for 3D Human Pose Estimation (Hanbing Liu et al., 2023)

{{<citation>}}

Hanbing Liu, Wangmeng Xiang, Jun-Yan He, Zhi-Qi Cheng, Bin Luo, Yifeng Geng, Xuansong Xie. (2023)  
**Refined Temporal Pyramidal Compression-and-Amplification Transformer for 3D Human Pose Estimation**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.01365v2)  

---


**ABSTRACT**  
Accurately estimating the 3D pose of humans in video sequences requires both accuracy and a well-structured architecture. With the success of transformers, we introduce the Refined Temporal Pyramidal Compression-and-Amplification (RTPCA) transformer. Exploiting the temporal dimension, RTPCA extends intra-block temporal modeling via its Temporal Pyramidal Compression-and-Amplification (TPCA) structure and refines inter-block feature interaction with a Cross-Layer Refinement (XLR) module. In particular, TPCA block exploits a temporal pyramid paradigm, reinforcing key and value representation capabilities and seamlessly extracting spatial semantics from motion sequences. We stitch these TPCA blocks with XLR that promotes rich semantic representation through continuous interaction of queries, keys, and values. This strategy embodies early-stage information with current flows, addressing typical deficits in detail and stability seen in other transformer-based methods. We demonstrate the effectiveness of RTPCA by achieving state-of-the-art results on Human3.6M, HumanEva-I, and MPI-INF-3DHP benchmarks with minimal computational overhead. The source code is available at https://github.com/hbing-l/RTPCA.

{{</citation>}}


### (25/98) Adapting Classifiers To Changing Class Priors During Deployment (Natnael Daba et al., 2023)

{{<citation>}}

Natnael Daba, Bruce McIntosh, Abhijit Mahalanobis. (2023)  
**Adapting Classifiers To Changing Class Priors During Deployment**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2309.01357v1)  

---


**ABSTRACT**  
Conventional classifiers are trained and evaluated using balanced data sets in which all classes are equally present. Classifiers are now trained on large data sets such as ImageNet, and are now able to classify hundreds (if not thousands) of different classes. On one hand, it is desirable to train such general-purpose classifier on a very large number of classes so that it performs well regardless of the settings in which it is deployed. On the other hand, it is unlikely that all classes known to the classifier will occur in every deployment scenario, or that they will occur with the same prior probability. In reality, only a relatively small subset of the known classes may be present in a particular setting or environment. For example, a classifier will encounter mostly animals if its deployed in a zoo or for monitoring wildlife, aircraft and service vehicles at an airport, or various types of automobiles and commercial vehicles if it is used for monitoring traffic. Furthermore, the exact class priors are generally unknown and can vary over time. In this paper, we explore different methods for estimating the class priors based on the output of the classifier itself. We then show that incorporating the estimated class priors in the overall decision scheme enables the classifier to increase its run-time accuracy in the context of its deployment scenario.

{{</citation>}}


### (26/98) Adaptive Parametric Prototype Learning for Cross-Domain Few-Shot Classification (Marzi Heidari et al., 2023)

{{<citation>}}

Marzi Heidari, Abdullah Alchihabi, Qing En, Yuhong Guo. (2023)  
**Adaptive Parametric Prototype Learning for Cross-Domain Few-Shot Classification**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Few-Shot  
[Paper Link](http://arxiv.org/abs/2309.01342v1)  

---


**ABSTRACT**  
Cross-domain few-shot classification induces a much more challenging problem than its in-domain counterpart due to the existence of domain shifts between the training and test tasks. In this paper, we develop a novel Adaptive Parametric Prototype Learning (APPL) method under the meta-learning convention for cross-domain few-shot classification. Different from existing prototypical few-shot methods that use the averages of support instances to calculate the class prototypes, we propose to learn class prototypes from the concatenated features of the support set in a parametric fashion and meta-learn the model by enforcing prototype-based regularization on the query set. In addition, we fine-tune the model in the target domain in a transductive manner using a weighted-moving-average self-training approach on the query instances. We conduct experiments on multiple cross-domain few-shot benchmark datasets. The empirical results demonstrate that APPL yields superior performance than many state-of-the-art cross-domain few-shot learning methods.

{{</citation>}}


### (27/98) Semantic-Constraint Matching Transformer for Weakly Supervised Object Localization (Yiwen Cao et al., 2023)

{{<citation>}}

Yiwen Cao, Yukun Su, Wenjun Wang, Yanxia Liu, Qingyao Wu. (2023)  
**Semantic-Constraint Matching Transformer for Weakly Supervised Object Localization**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.01331v1)  

---


**ABSTRACT**  
Weakly supervised object localization (WSOL) strives to learn to localize objects with only image-level supervision. Due to the local receptive fields generated by convolution operations, previous CNN-based methods suffer from partial activation issues, concentrating on the object's discriminative part instead of the entire entity scope. Benefiting from the capability of the self-attention mechanism to acquire long-range feature dependencies, Vision Transformer has been recently applied to alleviate the local activation drawbacks. However, since the transformer lacks the inductive localization bias that are inherent in CNNs, it may cause a divergent activation problem resulting in an uncertain distinction between foreground and background. In this work, we proposed a novel Semantic-Constraint Matching Network (SCMN) via a transformer to converge on the divergent activation. Specifically, we first propose a local patch shuffle strategy to construct the image pairs, disrupting local patches while guaranteeing global consistency. The paired images that contain the common object in spatial are then fed into the Siamese network encoder. We further design a semantic-constraint matching module, which aims to mine the co-object part by matching the coarse class activation maps (CAMs) extracted from the pair images, thus implicitly guiding and calibrating the transformer network to alleviate the divergent activation. Extensive experimental results conducted on two challenging benchmarks, including CUB-200-2011 and ILSVRC datasets show that our method can achieve the new state-of-the-art performance and outperform the previous method by a large margin.

{{</citation>}}


### (28/98) Can I Trust Your Answer? Visually Grounded Video Question Answering (Junbin Xiao et al., 2023)

{{<citation>}}

Junbin Xiao, Angela Yao, Yicong Li, Tat Seng Chua. (2023)  
**Can I Trust Your Answer? Visually Grounded Video Question Answering**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-MM, cs.CV  
Keywords: QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2309.01327v1)  

---


**ABSTRACT**  
We study visually grounded VideoQA in response to the emerging trends of utilizing pretraining techniques for video-language understanding. Specifically, by forcing vision-language models (VLMs) to answer questions and simultaneously provide visual evidence, we seek to ascertain the extent to which the predictions of such techniques are genuinely anchored in relevant video content, versus spurious correlations from language or irrelevant visual context. Towards this, we construct NExT-GQA -- an extension of NExT-QA with 10.5$K$ temporal grounding (or location) labels tied to the original QA pairs. With NExT-GQA, we scrutinize a variety of state-of-the-art VLMs. Through post-hoc attention analysis, we find that these models are weak in substantiating the answers despite their strong QA performance. This exposes a severe limitation of these models in making reliable predictions. As a remedy, we further explore and suggest a video grounding mechanism via Gaussian mask optimization and cross-modal learning. Experiments with different backbones demonstrate that this grounding mechanism improves both video grounding and QA. Our dataset and code are released. With these efforts, we aim to push towards the reliability of deploying VLMs in VQA systems.

{{</citation>}}


### (29/98) ExMobileViT: Lightweight Classifier Extension for Mobile Vision Transformer (Gyeongdong Yang et al., 2023)

{{<citation>}}

Gyeongdong Yang, Yungwook Kwon, Hyunjin Kim. (2023)  
**ExMobileViT: Lightweight Classifier Extension for Mobile Vision Transformer**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: ImageNet, Transformer  
[Paper Link](http://arxiv.org/abs/2309.01310v1)  

---


**ABSTRACT**  
The paper proposes an efficient structure for enhancing the performance of mobile-friendly vision transformer with small computational overhead. The vision transformer (ViT) is very attractive in that it reaches outperforming results in image classification, compared to conventional convolutional neural networks (CNNs). Due to its need of high computational resources, MobileNet-based ViT models such as MobileViT-S have been developed. However, their performance cannot reach the original ViT model. The proposed structure relieves the above weakness by storing the information from early attention stages and reusing it in the final classifier. This paper is motivated by the idea that the data itself from early attention stages can have important meaning for the final classification. In order to reuse the early information in attention stages, the average pooling results of various scaled features from early attention stages are used to expand channels in the fully-connected layer of the final classifier. It is expected that the inductive bias introduced by the averaged features can enhance the final performance. Because the proposed structure only needs the average pooling of features from the attention stages and channel expansions in the final classifier, its computational and storage overheads are very small, keeping the benefits of low-cost MobileNet-based ViT (MobileViT). Compared with the original MobileViTs on the ImageNet dataset, the proposed ExMobileViT has noticeable accuracy enhancements, having only about 5% additional parameters.

{{</citation>}}


### (30/98) EMR-MSF: Self-Supervised Recurrent Monocular Scene Flow Exploiting Ego-Motion Rigidity (Zijie Jiang et al., 2023)

{{<citation>}}

Zijie Jiang, Masatoshi Okutomi. (2023)  
**EMR-MSF: Self-Supervised Recurrent Monocular Scene Flow Exploiting Ego-Motion Rigidity**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2309.01296v1)  

---


**ABSTRACT**  
Self-supervised monocular scene flow estimation, aiming to understand both 3D structures and 3D motions from two temporally consecutive monocular images, has received increasing attention for its simple and economical sensor setup. However, the accuracy of current methods suffers from the bottleneck of less-efficient network architecture and lack of motion rigidity for regularization. In this paper, we propose a superior model named EMR-MSF by borrowing the advantages of network architecture design under the scope of supervised learning. We further impose explicit and robust geometric constraints with an elaborately constructed ego-motion aggregation module where a rigidity soft mask is proposed to filter out dynamic regions for stable ego-motion estimation using static regions. Moreover, we propose a motion consistency loss along with a mask regularization loss to fully exploit static regions. Several efficient training strategies are integrated including a gradient detachment technique and an enhanced view synthesis process for better performance. Our proposed method outperforms the previous self-supervised works by a large margin and catches up to the performance of supervised methods. On the KITTI scene flow benchmark, our approach improves the SF-all metric of the state-of-the-art self-supervised monocular method by 44% and demonstrates superior performance across sub-tasks including depth and visual odometry, amongst other self-supervised single-task or multi-task methods.

{{</citation>}}


## cs.CR (3)



### (31/98) Designing a Security System Administration Course for Cybersecurity with a Companion Project (Fei Zuo et al., 2023)

{{<citation>}}

Fei Zuo, Junghwan Rhee, Myungah Park, Gang Qian. (2023)  
**Designing a Security System Administration Course for Cybersecurity with a Companion Project**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2309.01839v1)  

---


**ABSTRACT**  
In the past few years, an incident response-oriented cybersecurity program has been constructed at University of Central Oklahoma. As a core course in the newly-established curricula, Secure System Administration focuses on the essential knowledge and skill set for system administration. To enrich students with hands-on experience, we also develop a companion coursework project, named PowerGrader. In this paper, we present the course structure as well as the companion project design. Additionally, we survey the pertinent criterion and curriculum requirements from the widely recognized accreditation units. By this means, we demonstrate the importance of a secure system administration course within the context of cybersecurity education

{{</citation>}}


### (32/98) Secure and Efficient Federated Learning in LEO Constellations using Decentralized Key Generation and On-Orbit Model Aggregation (Mohamed Elmahallawy et al., 2023)

{{<citation>}}

Mohamed Elmahallawy, Tie Luo, Mohamed I. Ibrahem. (2023)  
**Secure and Efficient Federated Learning in LEO Constellations using Decentralized Key Generation and On-Orbit Model Aggregation**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-LG, cs.CR  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01828v1)  

---


**ABSTRACT**  
Satellite technologies have advanced drastically in recent years, leading to a heated interest in launching small satellites into low Earth orbit (LEOs) to collect massive data such as satellite imagery. Downloading these data to a ground station (GS) to perform centralized learning to build an AI model is not practical due to the limited and expensive bandwidth. Federated learning (FL) offers a potential solution but will incur a very large convergence delay due to the highly sporadic and irregular connectivity between LEO satellites and GS. In addition, there are significant security and privacy risks where eavesdroppers or curious servers/satellites may infer raw data from satellites' model parameters transmitted over insecure communication channels. To address these issues, this paper proposes FedSecure, a secure FL approach designed for LEO constellations, which consists of two novel components: (1) decentralized key generation that protects satellite data privacy using a functional encryption scheme, and (2) on-orbit model forwarding and aggregation that generates a partial global model per orbit to minimize the idle waiting time for invisible satellites to enter the visible zone of the GS. Our analysis and results show that FedSecure preserves the privacy of each satellite's data against eavesdroppers, a curious server, or curious satellites. It is lightweight with significantly lower communication and computation overheads than other privacy-preserving FL aggregation approaches. It also reduces convergence delay drastically from days to only a few hours, yet achieving high accuracy of up to 85.35% using realistic satellite images.

{{</citation>}}


### (33/98) Automatic Scam-Baiting Using ChatGPT (Piyush Bajaj et al., 2023)

{{<citation>}}

Piyush Bajaj, Matthew Edwards. (2023)  
**Automatic Scam-Baiting Using ChatGPT**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2309.01586v1)  

---


**ABSTRACT**  
Automatic scam-baiting is an online fraud countermeasure that involves automated systems responding to online fraudsters in order to waste their time and deplete their resources, diverting attackers away from real potential victims. Previous work has demonstrated that text generation systems are capable of engaging with attackers as automatic scam-baiters, but the fluency and coherence of generated text may be a limit to the effectiveness of such systems.   In this paper, we report on the results of a month-long experiment comparing the effectiveness of two ChatGPT-based automatic scam-baiters to a control measure. Within our results, with engagement from over 250 real email fraudsters, we find that ChatGPT-based scam-baiters show a marked increase in scammer response rate and conversation length relative to the control measure, outperforming previous approaches. We discuss the implications of these results and practical considerations for wider deployment of automatic scam-baiting.

{{</citation>}}


## cs.CL (20)



### (34/98) One Wide Feedforward is All You Need (Telmo Pessoa Pires et al., 2023)

{{<citation>}}

Telmo Pessoa Pires, António V. Lopes, Yannick Assogba, Hendra Setiawan. (2023)  
**One Wide Feedforward is All You Need**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Attention, Transformer  
[Paper Link](http://arxiv.org/abs/2309.01826v1)  

---


**ABSTRACT**  
The Transformer architecture has two main non-embedding components: Attention and the Feed Forward Network (FFN). Attention captures interdependencies between words regardless of their position, while the FFN non-linearly transforms each input token independently. In this work we explore the role of the FFN, and find that despite taking up a significant fraction of the model's parameters, it is highly redundant. Concretely, we are able to substantially reduce the number of parameters with only a modest drop in accuracy by removing the FFN on the decoder layers and sharing a single FFN across the encoder. Finally we scale this architecture back to its original size by increasing the hidden dimension of the shared FFN, achieving substantial gains in both accuracy and latency with respect to the original Transformer Big.

{{</citation>}}


### (35/98) Into the Single Cell Multiverse: an End-to-End Dataset for Procedural Knowledge Extraction in Biomedical Texts (Ruth Dannenfelser et al., 2023)

{{<citation>}}

Ruth Dannenfelser, Jeffrey Zhong, Ran Zhang, Vicky Yao. (2023)  
**Into the Single Cell Multiverse: an End-to-End Dataset for Procedural Knowledge Extraction in Biomedical Texts**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NER, NLP  
[Paper Link](http://arxiv.org/abs/2309.01812v1)  

---


**ABSTRACT**  
Many of the most commonly explored natural language processing (NLP) information extraction tasks can be thought of as evaluations of declarative knowledge, or fact-based information extraction. Procedural knowledge extraction, i.e., breaking down a described process into a series of steps, has received much less attention, perhaps in part due to the lack of structured datasets that capture the knowledge extraction process from end-to-end. To address this unmet need, we present FlaMB\'e (Flow annotations for Multiverse Biological entities), a collection of expert-curated datasets across a series of complementary tasks that capture procedural knowledge in biomedical texts. This dataset is inspired by the observation that one ubiquitous source of procedural knowledge that is described as unstructured text is within academic papers describing their methodology. The workflows annotated in FlaMB\'e are from texts in the burgeoning field of single cell research, a research area that has become notorious for the number of software tools and complexity of workflows used. Additionally, FlaMB\'e provides, to our knowledge, the largest manually curated named entity recognition (NER) and disambiguation (NED) datasets for tissue/cell type, a fundamental biological entity that is critical for knowledge extraction in the biomedical research domain. Beyond providing a valuable dataset to enable further development of NLP models for procedural knowledge extraction, automating the process of workflow mining also has important implications for advancing reproducibility in biomedical research.

{{</citation>}}


### (36/98) Are Emergent Abilities in Large Language Models just In-Context Learning? (Sheng Lu et al., 2023)

{{<citation>}}

Sheng Lu, Irina Bigoulaeva, Rachneet Sachdeva, Harish Tayyar Madabushi, Iryna Gurevych. (2023)  
**Are Emergent Abilities in Large Language Models just In-Context Learning?**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2309.01809v1)  

---


**ABSTRACT**  
Large language models have exhibited emergent abilities, demonstrating exceptional performance across diverse tasks for which they were not explicitly trained, including those that require complex reasoning abilities. The emergence of such abilities carries profound implications for the future direction of research in NLP, especially as the deployment of such models becomes more prevalent. However, one key challenge is that the evaluation of these abilities is often confounded by competencies that arise in models through alternative prompting techniques, such as in-context learning and instruction following, which also emerge as the models are scaled up. In this study, we provide the first comprehensive examination of these emergent abilities while accounting for various potentially biasing factors that can influence the evaluation of models. We conduct rigorous tests on a set of 18 models, encompassing a parameter range from 60 million to 175 billion parameters, across a comprehensive set of 22 tasks. Through an extensive series of over 1,000 experiments, we provide compelling evidence that emergent abilities can primarily be ascribed to in-context learning. We find no evidence for the emergence of reasoning abilities, thus providing valuable insights into the underlying mechanisms driving the observed abilities and thus alleviating safety concerns regarding their use.

{{</citation>}}


### (37/98) Interdisciplinary Fairness in Imbalanced Research Proposal Topic Inference: A Hierarchical Transformer-based Method with Selective Interpolation (Meng Xiao et al., 2023)

{{<citation>}}

Meng Xiao, Min Wu, Ziyue Qiao, Yanjie Fu, Zhiyuan Ning, Yi Du, Yuanchun Zhou. (2023)  
**Interdisciplinary Fairness in Imbalanced Research Proposal Topic Inference: A Hierarchical Transformer-based Method with Selective Interpolation**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.01717v1)  

---


**ABSTRACT**  
The objective of topic inference in research proposals aims to obtain the most suitable disciplinary division from the discipline system defined by a funding agency. The agency will subsequently find appropriate peer review experts from their database based on this division. Automated topic inference can reduce human errors caused by manual topic filling, bridge the knowledge gap between funding agencies and project applicants, and improve system efficiency. Existing methods focus on modeling this as a hierarchical multi-label classification problem, using generative models to iteratively infer the most appropriate topic information. However, these methods overlook the gap in scale between interdisciplinary research proposals and non-interdisciplinary ones, leading to an unjust phenomenon where the automated inference system categorizes interdisciplinary proposals as non-interdisciplinary, causing unfairness during the expert assignment. How can we address this data imbalance issue under a complex discipline system and hence resolve this unfairness? In this paper, we implement a topic label inference system based on a Transformer encoder-decoder architecture. Furthermore, we utilize interpolation techniques to create a series of pseudo-interdisciplinary proposals from non-interdisciplinary ones during training based on non-parametric indicators such as cross-topic probabilities and topic occurrence probabilities. This approach aims to reduce the bias of the system during model training. Finally, we conduct extensive experiments on a real-world dataset to verify the effectiveness of the proposed method. The experimental results demonstrate that our training strategy can significantly mitigate the unfairness generated in the topic inference task.

{{</citation>}}


### (38/98) Prompting or Fine-tuning? A Comparative Study of Large Language Models for Taxonomy Construction (Boqi Chen et al., 2023)

{{<citation>}}

Boqi Chen, Fandi Yi, Dániel Varró. (2023)  
**Prompting or Fine-tuning? A Comparative Study of Large Language Models for Taxonomy Construction**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: GPT, Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2309.01715v1)  

---


**ABSTRACT**  
Taxonomies represent hierarchical relations between entities, frequently applied in various software modeling and natural language processing (NLP) activities. They are typically subject to a set of structural constraints restricting their content. However, manual taxonomy construction can be time-consuming, incomplete, and costly to maintain. Recent studies of large language models (LLMs) have demonstrated that appropriate user inputs (called prompting) can effectively guide LLMs, such as GPT-3, in diverse NLP tasks without explicit (re-)training. However, existing approaches for automated taxonomy construction typically involve fine-tuning a language model by adjusting model parameters. In this paper, we present a general framework for taxonomy construction that takes into account structural constraints. We subsequently conduct a systematic comparison between the prompting and fine-tuning approaches performed on a hypernym taxonomy and a novel computer science taxonomy dataset. Our result reveals the following: (1) Even without explicit training on the dataset, the prompting approach outperforms fine-tuning-based approaches. Moreover, the performance gap between prompting and fine-tuning widens when the training dataset is small. However, (2) taxonomies generated by the fine-tuning approach can be easily post-processed to satisfy all the constraints, whereas handling violations of the taxonomies produced by the prompting approach can be challenging. These evaluation findings provide guidance on selecting the appropriate method for taxonomy construction and highlight potential enhancements for both approaches.

{{</citation>}}


### (39/98) MathAttack: Attacking Large Language Models Towards Math Solving Ability (Zihao Zhou et al., 2023)

{{<citation>}}

Zihao Zhou, Qiufeng Wang, Mingyu Jin, Jie Yao, Jianan Ye, Wei Liu, Wei Wang, Xiaowei Huang, Kaizhu Huang. (2023)  
**MathAttack: Attacking Large Language Models Towards Math Solving Ability**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.01686v1)  

---


**ABSTRACT**  
With the boom of Large Language Models (LLMs), the research of solving Math Word Problem (MWP) has recently made great progress. However, there are few studies to examine the security of LLMs in math solving ability. Instead of attacking prompts in the use of LLMs, we propose a MathAttack model to attack MWP samples which are closer to the essence of security in solving math problems. Compared to traditional text adversarial attack, it is essential to preserve the mathematical logic of original MWPs during the attacking. To this end, we propose logical entity recognition to identify logical entries which are then frozen. Subsequently, the remaining text are attacked by adopting a word-level attacker. Furthermore, we propose a new dataset RobustMath to evaluate the robustness of LLMs in math solving ability. Extensive experiments on our RobustMath and two another math benchmark datasets GSM8K and MultiAirth show that MathAttack could effectively attack the math solving ability of LLMs. In the experiments, we observe that (1) Our adversarial samples from higher-accuracy LLMs are also effective for attacking LLMs with lower accuracy (e.g., transfer from larger to smaller-size LLMs, or from few-shot to zero-shot prompts); (2) Complex MWPs (such as more solving steps, longer text, more numbers) are more vulnerable to attack; (3) We can improve the robustness of LLMs by using our adversarial samples in few-shot prompts. Finally, we hope our practice and observation can serve as an important attempt towards enhancing the robustness of LLMs in math solving ability. We will release our code and dataset.

{{</citation>}}


### (40/98) Donkii: Can Annotation Error Detection Methods Find Errors in Instruction-Tuning Datasets? (Leon Weber-Genzel et al., 2023)

{{<citation>}}

Leon Weber-Genzel, Robert Litschko, Ekaterina Artemova, Barbara Plank. (2023)  
**Donkii: Can Annotation Error Detection Methods Find Errors in Instruction-Tuning Datasets?**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.01669v1)  

---


**ABSTRACT**  
Instruction-tuning has become an integral part of training pipelines for Large Language Models (LLMs) and has been shown to yield strong performance gains. In an orthogonal line of research, Annotation Error Detection (AED) has emerged as a tool for detecting quality issues of gold-standard labels. But so far, the application of AED methods is limited to discriminative settings. It is an open question how well AED methods generalize to generative settings which are becoming widespread via generative LLMs. In this work, we present a first and new benchmark for AED on instruction-tuning data: Donkii. It encompasses three instruction-tuning datasets enriched with annotations by experts and semi-automatic methods. We find that all three datasets contain clear-cut errors that sometimes directly propagate into instruction-tuned LLMs. We propose four AED baselines for the generative setting and evaluate them comprehensively on the newly introduced dataset. Our results demonstrate that choosing the right AED method and model size is indeed crucial, thereby deriving practical recommendations. To gain insights, we provide a first case-study to examine how the quality of the instruction-tuning datasets influences downstream performance.

{{</citation>}}


### (41/98) Fine-grained Affective Processing Capabilities Emerging from Large Language Models (Joost Broekens et al., 2023)

{{<citation>}}

Joost Broekens, Bernhard Hilpert, Suzan Verberne, Kim Baraka, Patrick Gebhard, Aske Plaat. (2023)  
**Fine-grained Affective Processing Capabilities Emerging from Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-HC, cs.CL  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2309.01664v1)  

---


**ABSTRACT**  
Large language models, in particular generative pre-trained transformers (GPTs), show impressive results on a wide variety of language-related tasks. In this paper, we explore ChatGPT's zero-shot ability to perform affective computing tasks using prompting alone. We show that ChatGPT a) performs meaningful sentiment analysis in the Valence, Arousal and Dominance dimensions, b) has meaningful emotion representations in terms of emotion categories and these affective dimensions, and c) can perform basic appraisal-based emotion elicitation of situations based on a prompt-based computational implementation of the OCC appraisal model. These findings are highly relevant: First, they show that the ability to solve complex affect processing tasks emerges from language-based token prediction trained on extensive data sets. Second, they show the potential of large language models for simulating, processing and analyzing human emotions, which has important implications for various applications such as sentiment analysis, socially interactive agents, and social robotics.

{{</citation>}}


### (42/98) Unveiling Theory of Mind in Large Language Models: A Parallel to Single Neurons in the Human Brain (Mohsen Jamali et al., 2023)

{{<citation>}}

Mohsen Jamali, Ziv M. Williams, Jing Cai. (2023)  
**Unveiling Theory of Mind in Large Language Models: A Parallel to Single Neurons in the Human Brain**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.01660v1)  

---


**ABSTRACT**  
With their recent development, large language models (LLMs) have been found to exhibit a certain level of Theory of Mind (ToM), a complex cognitive capacity that is related to our conscious mind and that allows us to infer another's beliefs and perspective. While human ToM capabilities are believed to derive from the neural activity of a broadly interconnected brain network, including that of dorsal medial prefrontal cortex (dmPFC) neurons, the precise processes underlying LLM's capacity for ToM or their similarities with that of humans remains largely unknown. In this study, we drew inspiration from the dmPFC neurons subserving human ToM and employed a similar methodology to examine whether LLMs exhibit comparable characteristics. Surprisingly, our analysis revealed a striking resemblance between the two, as hidden embeddings (artificial neurons) within LLMs started to exhibit significant responsiveness to either true- or false-belief trials, suggesting their ability to represent another's perspective. These artificial embedding responses were closely correlated with the LLMs' performance during the ToM tasks, a property that was dependent on the size of the models. Further, the other's beliefs could be accurately decoded using the entire embeddings, indicating the presence of the embeddings' ToM capability at the population level. Together, our findings revealed an emergent property of LLMs' embeddings that modified their activities in response to ToM features, offering initial evidence of a parallel between the artificial model and neurons in the human brain.

{{</citation>}}


### (43/98) Exploring the effectiveness of ChatGPT-based feedback compared with teacher feedback and self-feedback: Evidence from Chinese to English translation (Siyi Cao et al., 2023)

{{<citation>}}

Siyi Cao, Linping Zhong. (2023)  
**Exploring the effectiveness of ChatGPT-based feedback compared with teacher feedback and self-feedback: Evidence from Chinese to English translation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI, BLEU, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2309.01645v1)  

---


**ABSTRACT**  
ChatGPT,a cutting-edge AI-powered Chatbot,can quickly generate responses on given commands. While it was reported that ChatGPT had the capacity to deliver useful feedback, it is still unclear about its effectiveness compared with conventional feedback approaches,such as teacher feedback (TF) and self-feedback (SF). To address this issue, this study compared the revised Chinese to English translation texts produced by Chinese Master of Translation and Interpretation (MTI) students,who learned English as a Second/Foreign Language (ESL/EFL), based on three feedback types (i.e., ChatGPT-based feedback, TF and SF). The data was analyzed using BLEU score to gauge the overall translation quality as well as Coh-Metrix to examine linguistic features across three dimensions: lexicon, syntax, and cohesion.The findings revealed that TF- and SF-guided translation texts surpassed those with ChatGPT-based feedback, as indicated by the BLEU score. In terms of linguistic features,ChatGPT-based feedback demonstrated superiority, particularly in enhancing lexical capability and referential cohesion in the translation texts. However, TF and SF proved more effective in developing syntax-related skills,as it addressed instances of incorrect usage of the passive voice. These diverse outcomes indicate ChatGPT's potential as a supplementary resource, complementing traditional teacher-led methods in translation practice.

{{</citation>}}


### (44/98) Geo-Encoder: A Chunk-Argument Bi-Encoder Framework for Chinese Geographic Re-Ranking (Yong Cao et al., 2023)

{{<citation>}}

Yong Cao, Ruixue Ding, Boli Chen, Xianzhi Li, Min Chen, Daniel Hershcovich, Pengjun Xie, Fei Huang. (2023)  
**Geo-Encoder: A Chunk-Argument Bi-Encoder Framework for Chinese Geographic Re-Ranking**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2309.01606v1)  

---


**ABSTRACT**  
Chinese geographic re-ranking task aims to find the most relevant addresses among retrieved candidates, which is crucial for location-related services such as navigation maps. Unlike the general sentences, geographic contexts are closely intertwined with geographical concepts, from general spans (e.g., province) to specific spans (e.g., road). Given this feature, we propose an innovative framework, namely Geo-Encoder, to more effectively integrate Chinese geographical semantics into re-ranking pipelines. Our methodology begins by employing off-the-shelf tools to associate text with geographical spans, treating them as chunking units. Then, we present a multi-task learning module to simultaneously acquire an effective attention matrix that determines chunk contributions to extra semantic representations. Furthermore, we put forth an asynchronous update mechanism for the proposed addition task, aiming to guide the model capable of effectively focusing on specific chunks. Experiments on two distinct Chinese geographic re-ranking datasets, show that the Geo-Encoder achieves significant improvements when compared to state-of-the-art baselines. Notably, it leads to a substantial improvement in the Hit@1 score of MGEO-BERT, increasing it by 6.22% from 62.76 to 68.98 on the GeoTES dataset.

{{</citation>}}


### (45/98) A Comparative Analysis of Pretrained Language Models for Text-to-Speech (Marcel Granero-Moya et al., 2023)

{{<citation>}}

Marcel Granero-Moya, Penny Karanasou, Sri Karlapati, Bastian Schnell, Nicole Peinelt, Alexis Moinet, Thomas Drugman. (2023)  
**A Comparative Analysis of Pretrained Language Models for Text-to-Speech**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: GLUE, Language Model, NLU, Pretrained Language Models  
[Paper Link](http://arxiv.org/abs/2309.01576v1)  

---


**ABSTRACT**  
State-of-the-art text-to-speech (TTS) systems have utilized pretrained language models (PLMs) to enhance prosody and create more natural-sounding speech. However, while PLMs have been extensively researched for natural language understanding (NLU), their impact on TTS has been overlooked. In this study, we aim to address this gap by conducting a comparative analysis of different PLMs for two TTS tasks: prosody prediction and pause prediction. Firstly, we trained a prosody prediction model using 15 different PLMs. Our findings revealed a logarithmic relationship between model size and quality, as well as significant performance differences between neutral and expressive prosody. Secondly, we employed PLMs for pause prediction and found that the task was less sensitive to small models. We also identified a strong correlation between our empirical results and the GLUE scores obtained for these language models. To the best of our knowledge, this is the first study of its kind to investigate the impact of different PLMs on TTS.

{{</citation>}}


### (46/98) What are Public Concerns about ChatGPT? A Novel Self-Supervised Neural Topic Model Tells You (Rui Wang et al., 2023)

{{<citation>}}

Rui Wang, Xing Liu, Yanan Wang, Haiping Huang. (2023)  
**What are Public Concerns about ChatGPT? A Novel Self-Supervised Neural Topic Model Tells You**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT, Self-Supervised, Topic Model, Twitter  
[Paper Link](http://arxiv.org/abs/2309.01522v1)  

---


**ABSTRACT**  
The recently released artificial intelligence conversational agent, ChatGPT, has gained significant attention in academia and real life. A multitude of early ChatGPT users eagerly explore its capabilities and share their opinions on it via social media. Both user queries and social media posts express public concerns regarding this advanced dialogue system. To mine public concerns about ChatGPT, a novel Self-Supervised neural Topic Model (SSTM), which formalizes topic modeling as a representation learning procedure, is proposed in this paper. Extensive experiments have been conducted on Twitter posts about ChatGPT and queries asked by ChatGPT users. And experimental results demonstrate that the proposed approach could extract higher quality public concerns with improved interpretability and diversity, surpassing the performance of state-of-the-art approaches.

{{</citation>}}


### (47/98) LLM and Infrastructure as a Code use case (Thibault Chanus et al., 2023)

{{<citation>}}

Thibault Chanus, Michael Aubertin. (2023)  
**LLM and Infrastructure as a Code use case**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.01456v1)  

---


**ABSTRACT**  
Cloud computing and the evolution of management methodologies such as Lean Management or Agile entail a profound transformation in both system construction and maintenance approaches. These practices are encompassed within the term "DevOps." This descriptive approach to an information system or application, alongside the configuration of its constituent components, has necessitated the development of descriptive languages paired with specialized engines for automating systems administration tasks. Among these, the tandem of Ansible (engine) and YAML (descriptive language) stands out as the two most prevalent tools in the market, facing notable competition mainly from Terraform. The current document presents an inquiry into a solution for generating and managing Ansible YAML roles and playbooks, utilizing Generative LLMs (Language Models) to translate human descriptions into code. Our efforts are focused on identifying plausible directions and outlining the potential industrial applications.   Note: For the purpose of this experiment, we have opted against the use of Ansible Lightspeed. This is due to its reliance on an IBM Watson model, for which we have not found any publicly available references. Comprehensive information regarding this remarkable technology can be found directly on our partner RedHat's website, https://www.redhat.com/en/about/press-releases/red-hat-introduces-ansible-lightspeed-ai-driven-it-automation

{{</citation>}}


### (48/98) Open Sesame! Universal Black Box Jailbreaking of Large Language Models (Raz Lapid et al., 2023)

{{<citation>}}

Raz Lapid, Ron Langberg, Moshe Sipper. (2023)  
**Open Sesame! Universal Black Box Jailbreaking of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CV, cs-NE, cs.CL  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2309.01446v1)  

---


**ABSTRACT**  
Large language models (LLMs), designed to provide helpful and safe responses, often rely on alignment techniques to align with user intent and social guidelines. Unfortunately, this alignment can be exploited by malicious actors seeking to manipulate an LLM's outputs for unintended purposes. In this paper we introduce a novel approach that employs a genetic algorithm (GA) to manipulate LLMs when model architecture and parameters are inaccessible. The GA attack works by optimizing a universal adversarial prompt that -- when combined with a user's query -- disrupts the attacked model's alignment, resulting in unintended and potentially harmful outputs. Our novel approach systematically reveals a model's limitations and vulnerabilities by uncovering instances where its responses deviate from expected behavior. Through extensive experiments we demonstrate the efficacy of our technique, thus contributing to the ongoing discussion on responsible AI development by providing a diagnostic tool for evaluating and enhancing alignment of LLMs with human intent. To our knowledge this is the first automated universal black box jailbreak attack.

{{</citation>}}


### (49/98) Benchmarking Large Language Models in Retrieval-Augmented Generation (Jiawei Chen et al., 2023)

{{<citation>}}

Jiawei Chen, Hongyu Lin, Xianpei Han, Le Sun. (2023)  
**Benchmarking Large Language Models in Retrieval-Augmented Generation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.01431v1)  

---


**ABSTRACT**  
Retrieval-Augmented Generation (RAG) is a promising approach for mitigating the hallucination of large language models (LLMs). However, existing research lacks rigorous evaluation of the impact of retrieval-augmented generation on different large language models, which make it challenging to identify the potential bottlenecks in the capabilities of RAG for different LLMs. In this paper, we systematically investigate the impact of Retrieval-Augmented Generation on large language models. We analyze the performance of different large language models in 4 fundamental abilities required for RAG, including noise robustness, negative rejection, information integration, and counterfactual robustness. To this end, we establish Retrieval-Augmented Generation Benchmark (RGB), a new corpus for RAG evaluation in both English and Chinese. RGB divides the instances within the benchmark into 4 separate testbeds based on the aforementioned fundamental abilities required to resolve the case. Then we evaluate 6 representative LLMs on RGB to diagnose the challenges of current LLMs when applying RAG. Evaluation reveals that while LLMs exhibit a certain degree of noise robustness, they still struggle significantly in terms of negative rejection, information integration, and dealing with false information. The aforementioned assessment outcomes indicate that there is still a considerable journey ahead to effectively apply RAG to LLMs.

{{</citation>}}


### (50/98) Zero-shot information extraction from radiological reports using ChatGPT (Danqing Hu et al., 2023)

{{<citation>}}

Danqing Hu, Bing Liu, Xiaofeng Zhu, Xudong Lu, Nan Wu. (2023)  
**Zero-shot information extraction from radiological reports using ChatGPT**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT, NLP  
[Paper Link](http://arxiv.org/abs/2309.01398v2)  

---


**ABSTRACT**  
Electronic health records contain an enormous amount of valuable information, but many are recorded in free text. Information extraction is the strategy to transform the sequence of characters into structured data, which can be employed for secondary analysis. However, the traditional information extraction components, such as named entity recognition and relation extraction, require annotated data to optimize the model parameters, which has become one of the major bottlenecks in building information extraction systems. With the large language models achieving good performances on various downstream NLP tasks without parameter tuning, it becomes possible to use large language models for zero-shot information extraction. In this study, we aim to explore whether the most popular large language model, ChatGPT, can extract useful information from the radiological reports. We first design the prompt template for the interested information in the CT reports. Then, we generate the prompts by combining the prompt template with the CT reports as the inputs of ChatGPT to obtain the responses. A post-processing module is developed to transform the responses into structured extraction results. We conducted the experiments with 847 CT reports collected from Peking University Cancer Hospital. The experimental results indicate that ChatGPT can achieve competitive performances for some extraction tasks compared with the baseline information extraction system, but some limitations need to be further improved.

{{</citation>}}


### (51/98) ReOnto: A Neuro-Symbolic Approach for Biomedical Relation Extraction (Monika Jain et al., 2023)

{{<citation>}}

Monika Jain, Kuldeep Singh, Raghava Mutharaju. (2023)  
**ReOnto: A Neuro-Symbolic Approach for Biomedical Relation Extraction**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-IR, cs-LG, cs.CL  
Keywords: Knowledge Graph, Relation Extraction  
[Paper Link](http://arxiv.org/abs/2309.01370v1)  

---


**ABSTRACT**  
Relation Extraction (RE) is the task of extracting semantic relationships between entities in a sentence and aligning them to relations defined in a vocabulary, which is generally in the form of a Knowledge Graph (KG) or an ontology. Various approaches have been proposed so far to address this task. However, applying these techniques to biomedical text often yields unsatisfactory results because it is hard to infer relations directly from sentences due to the nature of the biomedical relations. To address these issues, we present a novel technique called ReOnto, that makes use of neuro symbolic knowledge for the RE task. ReOnto employs a graph neural network to acquire the sentence representation and leverages publicly accessible ontologies as prior knowledge to identify the sentential relation between two entities. The approach involves extracting the relation path between the two entities from the ontology. We evaluate the effect of using symbolic knowledge from ontologies with graph neural networks. Experimental results on two public biomedical datasets, BioRel and ADE, show that our method outperforms all the baselines (approximately by 3\%).

{{</citation>}}


### (52/98) Self-driven Grounding: Large Language Model Agents with Automatical Language-aligned Skill Learning (Shaohui Peng et al., 2023)

{{<citation>}}

Shaohui Peng, Xing Hu, Qi Yi, Rui Zhang, Jiaming Guo, Di Huang, Zikang Tian, Ruizhi Chen, Zidong Du, Qi Guo, Yunji Chen, Ling Li. (2023)  
**Self-driven Grounding: Large Language Model Agents with Automatical Language-aligned Skill Learning**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2309.01352v1)  

---


**ABSTRACT**  
Large language models (LLMs) show their powerful automatic reasoning and planning capability with a wealth of semantic knowledge about the human world. However, the grounding problem still hinders the applications of LLMs in the real-world environment. Existing studies try to fine-tune the LLM or utilize pre-defined behavior APIs to bridge the LLMs and the environment, which not only costs huge human efforts to customize for every single task but also weakens the generality strengths of LLMs. To autonomously ground the LLM onto the environment, we proposed the Self-Driven Grounding (SDG) framework to automatically and progressively ground the LLM with self-driven skill learning. SDG first employs the LLM to propose the hypothesis of sub-goals to achieve tasks and then verify the feasibility of the hypothesis via interacting with the underlying environment. Once verified, SDG can then learn generalized skills with the guidance of these successfully grounded subgoals. These skills can be further utilized to accomplish more complex tasks which fail to pass the verification phase. Verified in the famous instruction following task set-BabyAI, SDG achieves comparable performance in the most challenging tasks compared with imitation learning methods that cost millions of demonstrations, proving the effectiveness of learned skills and showing the feasibility and efficiency of our framework.

{{</citation>}}


### (53/98) UniSA: Unified Generative Framework for Sentiment Analysis (Zaijing Li et al., 2023)

{{<citation>}}

Zaijing Li, Ting-En Lin, Yuchuan Wu, Meng Liu, Fengxiao Tang, Ming Zhao, Yongbin Li. (2023)  
**UniSA: Unified Generative Framework for Sentiment Analysis**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-CV, cs-MM, cs.CL  
Keywords: Sentiment Analysis  
[Paper Link](http://arxiv.org/abs/2309.01339v1)  

---


**ABSTRACT**  
Sentiment analysis is a crucial task that aims to understand people's emotional states and predict emotional categories based on multimodal information. It consists of several subtasks, such as emotion recognition in conversation (ERC), aspect-based sentiment analysis (ABSA), and multimodal sentiment analysis (MSA). However, unifying all subtasks in sentiment analysis presents numerous challenges, including modality alignment, unified input/output forms, and dataset bias. To address these challenges, we propose a Task-Specific Prompt method to jointly model subtasks and introduce a multimodal generative framework called UniSA. Additionally, we organize the benchmark datasets of main subtasks into a new Sentiment Analysis Evaluation benchmark, SAEval. We design novel pre-training tasks and training methods to enable the model to learn generic sentiment knowledge among subtasks to improve the model's multimodal sentiment perception ability. Our experimental results show that UniSA performs comparably to the state-of-the-art on all subtasks and generalizes well to various subtasks in sentiment analysis.

{{</citation>}}


## cs.LG (18)



### (54/98) LoopTune: Optimizing Tensor Computations with Reinforcement Learning (Dejan Grubisic et al., 2023)

{{<citation>}}

Dejan Grubisic, Bram Wasti, Chris Cummins, John Mellor-Crummey, Aleksandar Zlateski. (2023)  
**LoopTune: Optimizing Tensor Computations with Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-PL, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.01825v1)  

---


**ABSTRACT**  
Advanced compiler technology is crucial for enabling machine learning applications to run on novel hardware, but traditional compilers fail to deliver performance, popular auto-tuners have long search times and expert-optimized libraries introduce unsustainable costs. To address this, we developed LoopTune, a deep reinforcement learning compiler that optimizes tensor computations in deep learning models for the CPU. LoopTune optimizes tensor traversal order while using the ultra-fast lightweight code generator LoopNest to perform hardware-specific optimizations. With a novel graph-based representation and action space, LoopTune speeds up LoopNest by 3.2x, generating an order of magnitude faster code than TVM, 2.8x faster than MetaSchedule, and 1.08x faster than AutoTVM, consistently performing at the level of the hand-tuned library Numpy. Moreover, LoopTune tunes code in order of seconds.

{{</citation>}}


### (55/98) Marginalized Importance Sampling for Off-Environment Policy Evaluation (Pulkit Katdare et al., 2023)

{{<citation>}}

Pulkit Katdare, Nan Jiang, Katherine Driggs-Campbell. (2023)  
**Marginalized Importance Sampling for Off-Environment Policy Evaluation**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-RO, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.01807v1)  

---


**ABSTRACT**  
Reinforcement Learning (RL) methods are typically sample-inefficient, making it challenging to train and deploy RL-policies in real world robots. Even a robust policy trained in simulation, requires a real-world deployment to assess their performance. This paper proposes a new approach to evaluate the real-world performance of agent policies without deploying them in the real world. The proposed approach incorporates a simulator along with real-world offline data to evaluate the performance of any policy using the framework of Marginalized Importance Sampling (MIS). Existing MIS methods face two challenges: (1) large density ratios that deviate from a reasonable range and (2) indirect supervision, where the ratio needs to be inferred indirectly, thus exacerbating estimation error. Our approach addresses these challenges by introducing the target policy's occupancy in the simulator as an intermediate variable and learning the density ratio as the product of two terms that can be learned separately. The first term is learned with direct supervision and the second term has a small magnitude, thus making it easier to run. We analyze the sample complexity as well as error propagation of our two step-procedure. Furthermore, we empirically evaluate our approach on Sim2Sim environments such as Cartpole, Reacher and Half-Cheetah. Our results show that our method generalizes well across a variety of Sim2Sim gap, target policies and offline data collection policies. We also demonstrate the performance of our algorithm on a Sim2Real task of validating the performance of a 7 DOF robotic arm using offline data along with a gazebo based arm simulator.

{{</citation>}}


### (56/98) Survival Prediction from Imbalance colorectal cancer dataset using hybrid sampling methods and tree-based classifiers (Sadegh Soleimani et al., 2023)

{{<citation>}}

Sadegh Soleimani, Mahsa Bahrami, Mansour Vali. (2023)  
**Survival Prediction from Imbalance colorectal cancer dataset using hybrid sampling methods and tree-based classifiers**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Clinical  
[Paper Link](http://arxiv.org/abs/2309.01783v1)  

---


**ABSTRACT**  
Background and Objective: Colorectal cancer is a high mortality cancer. Clinical data analysis plays a crucial role in predicting the survival of colorectal cancer patients, enabling clinicians to make informed treatment decisions. However, utilizing clinical data can be challenging, especially when dealing with imbalanced outcomes. This paper focuses on developing algorithms to predict 1-, 3-, and 5-year survival of colorectal cancer patients using clinical datasets, with particular emphasis on the highly imbalanced 1-year survival prediction task. To address this issue, we propose a method that creates a pipeline of some of standard balancing techniques to increase the true positive rate. Evaluation is conducted on a colorectal cancer dataset from the SEER database. Methods: The pre-processing step consists of removing records with missing values and merging categories. The minority class of 1-year and 3-year survival tasks consists of 10% and 20% of the data, respectively. Edited Nearest Neighbor, Repeated edited nearest neighbor (RENN), Synthetic Minority Over-sampling Techniques (SMOTE), and pipelines of SMOTE and RENN approaches were used and compared for balancing the data with tree-based classifiers. Decision Trees, Random Forest, Extra Tree, eXtreme Gradient Boosting, and Light Gradient Boosting (LGBM) are used in this article. Method. Results: The performance evaluation utilizes a 5-fold cross-validation approach. In the case of highly imbalanced datasets (1-year), our proposed method with LGBM outperforms other sampling methods with the sensitivity of 72.30%. For the task of imbalance (3-year survival), the combination of RENN and LGBM achieves a sensitivity of 80.81%, indicating that our proposed method works best for highly imbalanced datasets. Conclusions: Our proposed method significantly improves mortality prediction for the minority class of colorectal cancer patients.

{{</citation>}}


### (57/98) Measuring, Interpreting, and Improving Fairness of Algorithms using Causal Inference and Randomized Experiments (James Enouen et al., 2023)

{{<citation>}}

James Enouen, Tianshu Sun, Yan Liu. (2023)  
**Measuring, Interpreting, and Improving Fairness of Algorithms using Causal Inference and Randomized Experiments**  

---
Primary Category: cs.LG  
Categories: cs-CY, cs-LG, cs.LG, stat-ME  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01780v1)  

---


**ABSTRACT**  
Algorithm fairness has become a central problem for the broad adoption of artificial intelligence. Although the past decade has witnessed an explosion of excellent work studying algorithm biases, achieving fairness in real-world AI production systems has remained a challenging task. Most existing works fail to excel in practical applications since either they have conflicting measurement techniques and/ or heavy assumptions, or require code-access of the production models, whereas real systems demand an easy-to-implement measurement framework and a systematic way to correct the detected sources of bias.   In this paper, we leverage recent advances in causal inference and interpretable machine learning to present an algorithm-agnostic framework (MIIF) to Measure, Interpret, and Improve the Fairness of an algorithmic decision. We measure the algorithm bias using randomized experiments, which enables the simultaneous measurement of disparate treatment, disparate impact, and economic value. Furthermore, using modern interpretability techniques, we develop an explainable machine learning model which accurately interprets and distills the beliefs of a blackbox algorithm. Altogether, these techniques create a simple and powerful toolset for studying algorithm fairness, especially for understanding the cost of fairness in practical applications like e-commerce and targeted advertising, where industry A/B testing is already abundant.

{{</citation>}}


### (58/98) CONFIDERAI: a novel CONFormal Interpretable-by-Design score function for Explainable and Reliable Artificial Intelligence (Alberto Carlevaro et al., 2023)

{{<citation>}}

Alberto Carlevaro, Sara Narteni, Fabrizio Dabbene, Marco Muselli, Maurizio Mongelli. (2023)  
**CONFIDERAI: a novel CONFormal Interpretable-by-Design score function for Explainable and Reliable Artificial Intelligence**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, stat-ML  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01778v2)  

---


**ABSTRACT**  
Everyday life is increasingly influenced by artificial intelligence, and there is no question that machine learning algorithms must be designed to be reliable and trustworthy for everyone. Specifically, computer scientists consider an artificial intelligence system safe and trustworthy if it fulfills five pillars: explainability, robustness, transparency, fairness, and privacy. In addition to these five, we propose a sixth fundamental aspect: conformity, that is, the probabilistic assurance that the system will behave as the machine learner expects. In this paper, we propose a methodology to link conformal prediction with explainable machine learning by defining CONFIDERAI, a new score function for rule-based models that leverages both rules predictive ability and points geometrical position within rules boundaries. We also address the problem of defining regions in the feature space where conformal guarantees are satisfied by exploiting techniques to control the number of non-conformal samples in conformal regions based on support vector data description (SVDD). The overall methodology is tested with promising results on benchmark and real datasets, such as DNS tunneling detection or cardiovascular disease prediction.

{{</citation>}}


### (59/98) Gated recurrent neural networks discover attention (Nicolas Zucchet et al., 2023)

{{<citation>}}

Nicolas Zucchet, Seijin Kobayashi, Yassir Akram, Johannes von Oswald, Maxime Larcher, Angelika Steger, João Sacramento. (2023)  
**Gated recurrent neural networks discover attention**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-NE, cs.LG  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2309.01775v1)  

---


**ABSTRACT**  
Recent architectural developments have enabled recurrent neural networks (RNNs) to reach and even surpass the performance of Transformers on certain sequence modeling tasks. These modern RNNs feature a prominent design pattern: linear recurrent layers interconnected by feedforward paths with multiplicative gating. Here, we show how RNNs equipped with these two design elements can exactly implement (linear) self-attention, the main building block of Transformers. By reverse-engineering a set of trained RNNs, we find that gradient descent in practice discovers our construction. In particular, we examine RNNs trained to solve simple in-context learning tasks on which Transformers are known to excel and find that gradient descent instills in our RNNs the same attention-based in-context learning algorithm used by Transformers. Our findings highlight the importance of multiplicative interactions in neural networks and suggest that certain RNNs might be unexpectedly implementing attention under the hood.

{{</citation>}}


### (60/98) Softmax Bias Correction for Quantized Generative Models (Nilesh Prasad Pandey et al., 2023)

{{<citation>}}

Nilesh Prasad Pandey, Marios Fournarakis, Chirag Patel, Markus Nagel. (2023)  
**Softmax Bias Correction for Quantized Generative Models**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs.LG  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2309.01729v1)  

---


**ABSTRACT**  
Post-training quantization (PTQ) is the go-to compression technique for large generative models, such as stable diffusion or large language models. PTQ methods commonly keep the softmax activation in higher precision as it has been shown to be very sensitive to quantization noise. However, this can lead to a significant runtime and power overhead during inference on resource-constraint edge devices. In this work, we investigate the source of the softmax sensitivity to quantization and show that the quantization operation leads to a large bias in the softmax output, causing accuracy degradation. To overcome this issue, we propose an offline bias correction technique that improves the quantizability of softmax without additional compute during deployment, as it can be readily absorbed into the quantization parameters. We demonstrate the effectiveness of our method on stable diffusion v1.5 and 125M-size OPT language model, achieving significant accuracy improvement for 8-bit quantized softmax.

{{</citation>}}


### (61/98) On the Robustness of Post-hoc GNN Explainers to Label Noise (Zhiqiang Zhong et al., 2023)

{{<citation>}}

Zhiqiang Zhong, Yangqianzi Jiang, Davide Mottin. (2023)  
**On the Robustness of Post-hoc GNN Explainers to Label Noise**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2309.01706v1)  

---


**ABSTRACT**  
Proposed as a solution to the inherent black-box limitations of graph neural networks (GNNs), post-hoc GNN explainers aim to provide precise and insightful explanations of the behaviours exhibited by trained GNNs. Despite their recent notable advancements in academic and industrial contexts, the robustness of post-hoc GNN explainers remains unexplored when confronted with label noise. To bridge this gap, we conduct a systematic empirical investigation to evaluate the efficacy of diverse post-hoc GNN explainers under varying degrees of label noise. Our results reveal several key insights: Firstly, post-hoc GNN explainers are susceptible to label perturbations. Secondly, even minor levels of label noise, inconsequential to GNN performance, harm the quality of generated explanations substantially. Lastly, we engage in a discourse regarding the progressive recovery of explanation effectiveness with escalating noise levels.

{{</citation>}}


### (62/98) Fair Ranking under Disparate Uncertainty (Richa Rastogi et al., 2023)

{{<citation>}}

Richa Rastogi, Thorsten Joachims. (2023)  
**Fair Ranking under Disparate Uncertainty**  

---
Primary Category: cs.LG  
Categories: cs-CY, cs-IR, cs-LG, cs.LG  
Keywords: Amazon  
[Paper Link](http://arxiv.org/abs/2309.01610v1)  

---


**ABSTRACT**  
Ranking is a ubiquitous method for focusing the attention of human evaluators on a manageable subset of options. Its use ranges from surfacing potentially relevant products on an e-commerce site to prioritizing college applications for human review. While ranking can make human evaluation far more effective by focusing attention on the most promising options, we argue that it can introduce unfairness if the uncertainty of the underlying relevance model differs between groups of options. Unfortunately, such disparity in uncertainty appears widespread, since the relevance estimates for minority groups tend to have higher uncertainty due to a lack of data or appropriate features. To overcome this fairness issue, we propose Equal-Opportunity Ranking (EOR) as a new fairness criterion for ranking that provably corrects for the disparity in uncertainty between groups. Furthermore, we present a practical algorithm for computing EOR rankings in time $O(n \log(n))$ and prove its close approximation guarantee to the globally optimal solution. In a comprehensive empirical evaluation on synthetic data, a US Census dataset, and a real-world case study of Amazon search queries, we find that the algorithm reliably guarantees EOR fairness while providing effective rankings.

{{</citation>}}


### (63/98) Rail Crack Propagation Forecasting Using Multi-horizons RNNs (Sara Yasmine Ouerk et al., 2023)

{{<citation>}}

Sara Yasmine Ouerk, Olivier Vo Van, Mouadh Yagoubi. (2023)  
**Rail Crack Propagation Forecasting Using Multi-horizons RNNs**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2309.01569v1)  

---


**ABSTRACT**  
The prediction of rail crack length propagation plays a crucial role in the maintenance and safety assessment of materials and structures. Traditional methods rely on physical models and empirical equations such as Paris law, which often have limitations in capturing the complex nature of crack growth. In recent years, machine learning techniques, particularly Recurrent Neural Networks (RNNs), have emerged as promising methods for time series forecasting. They allow to model time series data, and to incorporate exogenous variables into the model. The proposed approach involves collecting real data on the French rail network that includes historical crack length measurements, along with relevant exogenous factors that may influence crack growth. First, a pre-processing phase was performed to prepare a consistent data set for learning. Then, a suitable Bayesian multi-horizons recurrent architecture was designed to model the crack propagation phenomenon. Obtained results show that the Multi-horizons model outperforms state-of-the-art models such as LSTM and GRU.

{{</citation>}}


### (64/98) Passing Heatmap Prediction Based on Transformer Model and Tracking Data (Yisheng Pei et al., 2023)

{{<citation>}}

Yisheng Pei, Varuna De Silva, Mike Caine. (2023)  
**Passing Heatmap Prediction Based on Transformer Model and Tracking Data**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.01526v1)  

---


**ABSTRACT**  
Although the data-driven analysis of football players' performance has been developed for years, most research only focuses on the on-ball event including shots and passes, while the off-ball movement remains a little-explored area in this domain. Players' contributions to the whole match are evaluated unfairly, those who have more chances to score goals earn more credit than others, while the indirect and unnoticeable impact that comes from continuous movement has been ignored. This research presents a novel deep-learning network architecture which is capable to predict the potential end location of passes and how players' movement before the pass affects the final outcome. Once analysed more than 28,000 pass events, a robust prediction can be achieved with more than 0.7 Top-1 accuracy. And based on the prediction, a better understanding of the pitch control and pass option could be reached to measure players' off-ball movement contribution to defensive performance. Moreover, this model could provide football analysts a better tool and metric to understand how players' movement over time contributes to the game strategy and final victory.

{{</citation>}}


### (65/98) A Blackbox Model Is All You Need to Breach Privacy: Smart Grid Forecasting Models as a Use Case (Hussein Aly et al., 2023)

{{<citation>}}

Hussein Aly, Abdulaziz Al-Ali, Abdullah Al-Ali, Qutaibah Malluhi. (2023)  
**A Blackbox Model Is All You Need to Breach Privacy: Smart Grid Forecasting Models as a Use Case**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2309.01523v1)  

---


**ABSTRACT**  
This paper investigates the potential privacy risks associated with forecasting models, with specific emphasis on their application in the context of smart grids. While machine learning and deep learning algorithms offer valuable utility, concerns arise regarding their exposure of sensitive information. Previous studies have focused on classification models, overlooking risks associated with forecasting models. Deep learning based forecasting models, such as Long Short Term Memory (LSTM), play a crucial role in several applications including optimizing smart grid systems but also introduce privacy risks. Our study analyzes the ability of forecasting models to leak global properties and privacy threats in smart grid systems. We demonstrate that a black box access to an LSTM model can reveal a significant amount of information equivalent to having access to the data itself (with the difference being as low as 1% in Area Under the ROC Curve). This highlights the importance of protecting forecasting models at the same level as the data.

{{</citation>}}


### (66/98) Layer-wise training for self-supervised learning on graphs (Oscar Pina et al., 2023)

{{<citation>}}

Oscar Pina, Verónica Vilaplana. (2023)  
**Layer-wise training for self-supervised learning on graphs**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2309.01503v1)  

---


**ABSTRACT**  
End-to-end training of graph neural networks (GNN) on large graphs presents several memory and computational challenges, and limits the application to shallow architectures as depth exponentially increases the memory and space complexities. In this manuscript, we propose Layer-wise Regularized Graph Infomax, an algorithm to train GNNs layer by layer in a self-supervised manner. We decouple the feature propagation and feature transformation carried out by GNNs to learn node representations in order to derive a loss function based on the prediction of future inputs. We evaluate the algorithm in inductive large graphs and show similar performance to other end to end methods and a substantially increased efficiency, which enables the training of more sophisticated models in one single device. We also show that our algorithm avoids the oversmoothing of the representations, another common challenge of deep GNNs.

{{</citation>}}


### (67/98) FinDiff: Diffusion Models for Financial Tabular Data Generation (Timur Sattarov et al., 2023)

{{<citation>}}

Timur Sattarov, Marco Schreyer, Damian Borth. (2023)  
**FinDiff: Diffusion Models for Financial Tabular Data Generation**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, q-fin-ST  
Keywords: Financial  
[Paper Link](http://arxiv.org/abs/2309.01472v1)  

---


**ABSTRACT**  
The sharing of microdata, such as fund holdings and derivative instruments, by regulatory institutions presents a unique challenge due to strict data confidentiality and privacy regulations. These challenges often hinder the ability of both academics and practitioners to conduct collaborative research effectively. The emergence of generative models, particularly diffusion models, capable of synthesizing data mimicking the underlying distributions of real-world data presents a compelling solution. This work introduces 'FinDiff', a diffusion model designed to generate real-world financial tabular data for a variety of regulatory downstream tasks, for example economic scenario modeling, stress tests, and fraud detection. The model uses embedding encodings to model mixed modality financial data, comprising both categorical and numeric attributes. The performance of FinDiff in generating synthetic tabular financial data is evaluated against state-of-the-art baseline models using three real-world financial datasets (including two publicly available datasets and one proprietary dataset). Empirical results demonstrate that FinDiff excels in generating synthetic tabular financial data with high fidelity, privacy, and utility.

{{</citation>}}


### (68/98) Leveraging Reward Consistency for Interpretable Feature Discovery in Reinforcement Learning (Qisen Yang et al., 2023)

{{<citation>}}

Qisen Yang, Huanqian Wang, Mukun Tong, Wenjie Shi, Gao Huang, Shiji Song. (2023)  
**Leveraging Reward Consistency for Interpretable Feature Discovery in Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.01458v1)  

---


**ABSTRACT**  
The black-box nature of deep reinforcement learning (RL) hinders them from real-world applications. Therefore, interpreting and explaining RL agents have been active research topics in recent years. Existing methods for post-hoc explanations usually adopt the action matching principle to enable an easy understanding of vision-based RL agents. In this paper, it is argued that the commonly used action matching principle is more like an explanation of deep neural networks (DNNs) than the interpretation of RL agents. It may lead to irrelevant or misplaced feature attribution when different DNNs' outputs lead to the same rewards or different rewards result from the same outputs. Therefore, we propose to consider rewards, the essential objective of RL agents, as the essential objective of interpreting RL agents as well. To ensure reward consistency during interpretable feature discovery, a novel framework (RL interpreting RL, denoted as RL-in-RL) is proposed to solve the gradient disconnection from actions to rewards. We verify and evaluate our method on the Atari 2600 games as well as Duckietown, a challenging self-driving car simulator environment. The results show that our method manages to keep reward (or return) consistency and achieves high-quality feature attribution. Further, a series of analytical experiments validate our assumption of the action matching principle's limitations.

{{</citation>}}


### (69/98) On the Consistency and Robustness of Saliency Explanations for Time Series Classification (Chiara Balestra et al., 2023)

{{<citation>}}

Chiara Balestra, Bin Li, Emmanuel Müller. (2023)  
**On the Consistency and Robustness of Saliency Explanations for Time Series Classification**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2309.01457v1)  

---


**ABSTRACT**  
Interpretable machine learning and explainable artificial intelligence have become essential in many applications. The trade-off between interpretability and model performance is the traitor to developing intrinsic and model-agnostic interpretation methods. Although model explanation approaches have achieved significant success in vision and natural language domains, explaining time series remains challenging. The complex pattern in the feature domain, coupled with the additional temporal dimension, hinders efficient interpretation. Saliency maps have been applied to interpret time series windows as images. However, they are not naturally designed for sequential data, thus suffering various issues.   This paper extensively analyzes the consistency and robustness of saliency maps for time series features and temporal attribution. Specifically, we examine saliency explanations from both perturbation-based and gradient-based explanation models in a time series classification task. Our experimental results on five real-world datasets show that they all lack consistent and robust performances to some extent. By drawing attention to the flawed saliency explanation models, we motivate to develop consistent and robust explanations for time series classification.

{{</citation>}}


### (70/98) Effective Multi-Graph Neural Networks for Illicit Account Detection on Cryptocurrency Transaction Networks (Zhihao Ding et al., 2023)

{{<citation>}}

Zhihao Ding, Jieming Shi, Qing Li, Jiannong Cao. (2023)  
**Effective Multi-Graph Neural Networks for Illicit Account Detection on Cryptocurrency Transaction Networks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2309.02460v1)  

---


**ABSTRACT**  
We study illicit account detection on transaction networks of cryptocurrencies that are increasi_testngly important in online financial markets. The surge of illicit activities on cryptocurrencies has resulted in billions of losses from normal users. Existing solutions either rely on tedious feature engineering to get handcrafted features, or are inadequate to fully utilize the rich semantics of cryptocurrency transaction data, and consequently, yield sub-optimal performance. In this paper, we formulate the illicit account detection problem as a classification task over directed multigraphs with edge attributes, and present DIAM, a novel multi-graph neural network model to effectively detect illicit accounts on large transaction networks. First, DIAM includes an Edge2Seq module that automatically learns effective node representations preserving intrinsic transaction patterns of parallel edges, by considering both edge attributes and directed edge sequence dependencies. Then utilizing the multigraph topology, DIAM employs a new Multigraph Discrepancy (MGD) module with a well-designed message passing mechanism to capture the discrepant features between normal and illicit nodes, supported by an attention mechanism. Assembling all techniques, DIAM is trained in an end-to-end manner. Extensive experiments, comparing against 14 existing solutions on 4 large cryptocurrency datasets of Bitcoin and Ethereum, demonstrate that DIAM consistently achieves the best performance to accurately detect illicit accounts, while being efficient. For instance, on a Bitcoin dataset with 20 million nodes and 203 million edges, DIAM achieves F1 score 96.55%, significantly higher than the F1 score 83.92% of the best competitor.

{{</citation>}}


### (71/98) Hundreds Guide Millions: Adaptive Offline Reinforcement Learning with Expert Guidance (Qisen Yang et al., 2023)

{{<citation>}}

Qisen Yang, Shenzhi Wang, Qihang Zhang, Gao Huang, Shiji Song. (2023)  
**Hundreds Guide Millions: Adaptive Offline Reinforcement Learning with Expert Guidance**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.01448v1)  

---


**ABSTRACT**  
Offline reinforcement learning (RL) optimizes the policy on a previously collected dataset without any interactions with the environment, yet usually suffers from the distributional shift problem. To mitigate this issue, a typical solution is to impose a policy constraint on a policy improvement objective. However, existing methods generally adopt a ``one-size-fits-all'' practice, i.e., keeping only a single improvement-constraint balance for all the samples in a mini-batch or even the entire offline dataset. In this work, we argue that different samples should be treated with different policy constraint intensities. Based on this idea, a novel plug-in approach named Guided Offline RL (GORL) is proposed. GORL employs a guiding network, along with only a few expert demonstrations, to adaptively determine the relative importance of the policy improvement and policy constraint for every sample. We theoretically prove that the guidance provided by our method is rational and near-optimal. Extensive experiments on various environments suggest that GORL can be easily installed on most offline RL algorithms with statistically significant performance improvements.

{{</citation>}}


## eess.IV (4)



### (72/98) Multi-dimension unified Swin Transformer for 3D Lesion Segmentation in Multiple Anatomical Locations (Shaoyan Pan et al., 2023)

{{<citation>}}

Shaoyan Pan, Yiqiao Liu, Sarah Halek, Michal Tomaszewski, Shubing Wang, Richard Baumgartner, Jianda Yuan, Gregory Goldmacher, Antong Chen. (2023)  
**Multi-dimension unified Swin Transformer for 3D Lesion Segmentation in Multiple Anatomical Locations**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.01823v1)  

---


**ABSTRACT**  
In oncology research, accurate 3D segmentation of lesions from CT scans is essential for the modeling of lesion growth kinetics. However, following the RECIST criteria, radiologists routinely only delineate each lesion on the axial slice showing the largest transverse area, and delineate a small number of lesions in 3D for research purposes. As a result, we have plenty of unlabeled 3D volumes and labeled 2D images, and scarce labeled 3D volumes, which makes training a deep-learning 3D segmentation model a challenging task. In this work, we propose a novel model, denoted a multi-dimension unified Swin transformer (MDU-ST), for 3D lesion segmentation. The MDU-ST consists of a Shifted-window transformer (Swin-transformer) encoder and a convolutional neural network (CNN) decoder, allowing it to adapt to 2D and 3D inputs and learn the corresponding semantic information in the same encoder. Based on this model, we introduce a three-stage framework: 1) leveraging large amount of unlabeled 3D lesion volumes through self-supervised pretext tasks to learn the underlying pattern of lesion anatomy in the Swin-transformer encoder; 2) fine-tune the Swin-transformer encoder to perform 2D lesion segmentation with 2D RECIST slices to learn slice-level segmentation information; 3) further fine-tune the Swin-transformer encoder to perform 3D lesion segmentation with labeled 3D volumes. The network's performance is evaluated by the Dice similarity coefficient (DSC) and Hausdorff distance (HD) using an internal 3D lesion dataset with 593 lesions extracted from multiple anatomical locations. The proposed MDU-ST demonstrates significant improvement over the competing models. The proposed method can be used to conduct automated 3D lesion segmentation to assist radiomics and tumor growth modeling studies. This paper has been accepted by the IEEE International Symposium on Biomedical Imaging (ISBI) 2023.

{{</citation>}}


### (73/98) An Empirical Analysis for Zero-Shot Multi-Label Classification on COVID-19 CT Scans and Uncurated Reports (Ethan Dack et al., 2023)

{{<citation>}}

Ethan Dack, Lorenzo Brigato, Matthew McMurray, Matthias Fontanellaz, Thomas Frauenfelder, Hanno Hoppe, Aristomenis Exadaktylos, Thomas Geiser, Manuela Funke-Chambour, Andreas Christe, Lukas Ebner, Stavroula Mougiakakou. (2023)  
**An Empirical Analysis for Zero-Shot Multi-Label Classification on COVID-19 CT Scans and Uncurated Reports**  

---
Primary Category: eess.IV  
Categories: cs-CL, cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2309.01740v2)  

---


**ABSTRACT**  
The pandemic resulted in vast repositories of unstructured data, including radiology reports, due to increased medical examinations. Previous research on automated diagnosis of COVID-19 primarily focuses on X-ray images, despite their lower precision compared to computed tomography (CT) scans. In this work, we leverage unstructured data from a hospital and harness the fine-grained details offered by CT scans to perform zero-shot multi-label classification based on contrastive visual language learning. In collaboration with human experts, we investigate the effectiveness of multiple zero-shot models that aid radiologists in detecting pulmonary embolisms and identifying intricate lung details like ground glass opacities and consolidations. Our empirical analysis provides an overview of the possible solutions to target such fine-grained tasks, so far overlooked in the medical multimodal pretraining literature. Our investigation promises future advancements in the medical image analysis community by addressing some challenges associated with unstructured data and fine-grained multi-label classification.

{{</citation>}}


### (74/98) FAU-Net: An Attention U-Net Extension with Feature Pyramid Attention for Prostate Cancer Segmentation (Pablo Cesar Quihui-Rubio et al., 2023)

{{<citation>}}

Pablo Cesar Quihui-Rubio, Daniel Flores-Araiza, Miguel Gonzalez-Mendoza, Christian Mata, Gilberto Ochoa-Ruiz. (2023)  
**FAU-Net: An Attention U-Net Extension with Feature Pyramid Attention for Prostate Cancer Segmentation**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2309.01322v1)  

---


**ABSTRACT**  
This contribution presents a deep learning method for the segmentation of prostate zones in MRI images based on U-Net using additive and feature pyramid attention modules, which can improve the workflow of prostate cancer detection and diagnosis. The proposed model is compared to seven different U-Net-based architectures. The automatic segmentation performance of each model of the central zone (CZ), peripheral zone (PZ), transition zone (TZ) and Tumor were evaluated using Dice Score (DSC), and the Intersection over Union (IoU) metrics. The proposed alternative achieved a mean DSC of 84.15% and IoU of 76.9% in the test set, outperforming most of the studied models in this work except from R2U-Net and attention R2U-Net architectures.

{{</citation>}}


### (75/98) Enhancing Automated and Early Detection of Alzheimer's Disease Using Out-Of-Distribution Detection (Audrey Paleczny et al., 2023)

{{<citation>}}

Audrey Paleczny, Shubham Parab, Maxwell Zhang. (2023)  
**Enhancing Automated and Early Detection of Alzheimer's Disease Using Out-Of-Distribution Detection**  

---
Primary Category: eess.IV  
Categories: I-4-7; I-4-9; J-3, cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01312v1)  

---


**ABSTRACT**  
More than 10.7% of people aged 65 and older are affected by Alzheimer's disease. Early diagnosis and treatment are crucial as most Alzheimer's patients are unaware of having it until the effects become detrimental. AI has been known to use magnetic resonance imaging (MRI) to diagnose Alzheimer's. However, models which produce low rates of false diagnoses are critical to prevent unnecessary treatments. Thus, we trained supervised Random Forest models with segmented brain volumes and Convolutional Neural Network (CNN) outputs to classify different Alzheimer's stages. We then applied out-of-distribution (OOD) detection to the CNN model, enabling it to report OOD if misclassification is likely, thereby reducing false diagnoses. With an accuracy of 98% for detection and 95% for classification, our model based on CNN results outperformed our segmented volume model, which had detection and classification accuracies of 93% and 87%, respectively. Applying OOD detection to the CNN model enabled it to flag brain tumor images as OOD with 96% accuracy and minimal overall accuracy reduction. By using OOD detection to enhance the reliability of MRI classification using CNNs, we lowered the rate of false positives and eliminated a significant disadvantage of using Machine Learning models for healthcare tasks. Source code available upon request.

{{</citation>}}


## cs.SE (3)



### (76/98) Towards Foundational AI Models for Additive Manufacturing: Language Models for G-Code Debugging, Manipulation, and Comprehension (Anushrut Jignasu et al., 2023)

{{<citation>}}

Anushrut Jignasu, Kelly Marshall, Baskar Ganapathysubramanian, Aditya Balu, Chinmay Hegde, Adarsh Krishnamurthy. (2023)  
**Towards Foundational AI Models for Additive Manufacturing: Language Models for G-Code Debugging, Manipulation, and Comprehension**  

---
Primary Category: cs.SE  
Categories: cs-AI, cs-CL, cs-LG, cs-SE, cs.SE  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2309.02465v1)  

---


**ABSTRACT**  
3D printing or additive manufacturing is a revolutionary technology that enables the creation of physical objects from digital models. However, the quality and accuracy of 3D printing depend on the correctness and efficiency of the G-code, a low-level numerical control programming language that instructs 3D printers how to move and extrude material. Debugging G-code is a challenging task that requires a syntactic and semantic understanding of the G-code format and the geometry of the part to be printed. In this paper, we present the first extensive evaluation of six state-of-the-art foundational large language models (LLMs) for comprehending and debugging G-code files for 3D printing. We design effective prompts to enable pre-trained LLMs to understand and manipulate G-code and test their performance on various aspects of G-code debugging and manipulation, including detection and correction of common errors and the ability to perform geometric transformations. We analyze their strengths and weaknesses for understanding complete G-code files. We also discuss the implications and limitations of using LLMs for G-code comprehension.

{{</citation>}}


### (77/98) Hawkeye: Change-targeted Testing for Android Apps based on Deep Reinforcement Learning (Chao Peng et al., 2023)

{{<citation>}}

Chao Peng, Zhengwei Lv, Jiarong Fu, Jiayuan Liang, Zhao Zhang, Ajitha Rajan, Ping Yang. (2023)  
**Hawkeye: Change-targeted Testing for Android Apps based on Deep Reinforcement Learning**  

---
Primary Category: cs.SE  
Categories: cs-LG, cs-SE, cs.SE  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.01519v1)  

---


**ABSTRACT**  
Android Apps are frequently updated to keep up with changing user, hardware, and business demands. Ensuring the correctness of App updates through extensive testing is crucial to avoid potential bugs reaching the end user. Existing Android testing tools generate GUI events focussing on improving the test coverage of the entire App rather than prioritising updates and its impacted elements. Recent research has proposed change-focused testing but relies on random exploration to exercise the updates and impacted GUI elements that is ineffective and slow for large complex Apps with a huge input exploration space. We propose directed testing of App updates with Hawkeye that is able to prioritise executing GUI actions associated with code changes based on deep reinforcement learning from historical exploration data. Our empirical evaluation compares Hawkeye with state-of-the-art model-based and reinforcement learning-based testing tools FastBot2 and ARES using 10 popular open-source and 1 commercial App. We find that Hawkeye is able to generate GUI event sequences targeting changed functions more reliably than FastBot2 and ARES for the open source Apps and the large commercial App. Hawkeye achieves comparable performance on smaller open source Apps with a more tractable exploration space. The industrial deployment of Hawkeye in the development pipeline also shows that Hawkeye is ideal to perform smoke testing for merge requests of a complicated commercial App.

{{</citation>}}


### (78/98) Model Review: A PROMISEing Opportunity (Tim Menzies, 2023)

{{<citation>}}

Tim Menzies. (2023)  
**Model Review: A PROMISEing Opportunity**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01314v2)  

---


**ABSTRACT**  
To make models more understandable and correctable, I propose that the PROMISE community pivots to the problem of model review. Over the years, there have been many reports that very simple models can perform exceptionally well. Yet, where are the researchers asking "say, does that mean that we could make software analytics simpler and more comprehensible?" This is an important question, since humans often have difficulty accurately assessing complex models (leading to unreliable and sometimes dangerous results). Prior PROMISE results have shown that data mining can effectively summarizing large models/ data sets into simpler and smaller ones. Therefore, the PROMISE community has the skills and experience needed to redefine, simplify, and improve the relationship between humans and AI.

{{</citation>}}


## cs.IR (2)



### (79/98) DiscoverPath: A Knowledge Refinement and Retrieval System for Interdisciplinarity on Biomedical Research (Yu-Neng Chuang et al., 2023)

{{<citation>}}

Yu-Neng Chuang, Guanchu Wang, Chia-Yuan Chang, Kwei-Herng Lai, Daochen Zha, Ruixiang Tang, Fan Yang, Alfredo Costilla Reyes, Kaixiong Zhou, Xiaoqian Jiang, Xia Hu. (2023)  
**DiscoverPath: A Knowledge Refinement and Retrieval System for Interdisciplinarity on Biomedical Research**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs-LG, cs.IR  
Keywords: NER, Named Entity Recognition  
[Paper Link](http://arxiv.org/abs/2309.01808v1)  

---


**ABSTRACT**  
The exponential growth in scholarly publications necessitates advanced tools for efficient article retrieval, especially in interdisciplinary fields where diverse terminologies are used to describe similar research. Traditional keyword-based search engines often fall short in assisting users who may not be familiar with specific terminologies. To address this, we present a knowledge graph-based paper search engine for biomedical research to enhance the user experience in discovering relevant queries and articles. The system, dubbed DiscoverPath, employs Named Entity Recognition (NER) and part-of-speech (POS) tagging to extract terminologies and relationships from article abstracts to create a KG. To reduce information overload, DiscoverPath presents users with a focused subgraph containing the queried entity and its neighboring nodes and incorporates a query recommendation system, enabling users to iteratively refine their queries. The system is equipped with an accessible Graphical User Interface that provides an intuitive visualization of the KG, query recommendations, and detailed article information, enabling efficient article retrieval, thus fostering interdisciplinary knowledge exploration. DiscoverPath is open-sourced at https://github.com/ynchuang/DiscoverPath.

{{</citation>}}


### (80/98) AVATAR: Robust Voice Search Engine Leveraging Autoregressive Document Retrieval and Contrastive Learning (Yi-Cheng Wang et al., 2023)

{{<citation>}}

Yi-Cheng Wang, Tzu-Ting Yang, Hsin-Wei Wang, Bi-Cheng Yan, Berlin Chen. (2023)  
**AVATAR: Robust Voice Search Engine Leveraging Autoregressive Document Retrieval and Contrastive Learning**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: Contrastive Learning, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2309.01395v1)  

---


**ABSTRACT**  
Voice, as input, has progressively become popular on mobiles and seems to transcend almost entirely text input. Through voice, the voice search (VS) system can provide a more natural way to meet user's information needs. However, errors from the automatic speech recognition (ASR) system can be catastrophic to the VS system. Building on the recent advanced lightweight autoregressive retrieval model, which has the potential to be deployed on mobiles, leading to a more secure and personal VS assistant. This paper presents a novel study of VS leveraging autoregressive retrieval and tackles the crucial problems facing VS, viz. the performance drop caused by ASR noise, via data augmentations and contrastive learning, showing how explicit and implicit modeling the noise patterns can alleviate the problems. A series of experiments conducted on the Open-Domain Question Answering (ODSQA) confirm our approach's effectiveness and robustness in relation to some strong baseline systems.

{{</citation>}}


## q-bio.GN (1)



### (81/98) Blind Biological Sequence Denoising with Self-Supervised Set Learning (Nathan Ng et al., 2023)

{{<citation>}}

Nathan Ng, Ji Won Park, Jae Hyeon Lee, Ryan Lewis Kelly, Stephen Ra, Kyunghyun Cho. (2023)  
**Blind Biological Sequence Denoising with Self-Supervised Set Learning**  

---
Primary Category: q-bio.GN  
Categories: cs-LG, q-bio-GN, q-bio.GN  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2309.01670v1)  

---


**ABSTRACT**  
Biological sequence analysis relies on the ability to denoise the imprecise output of sequencing platforms. We consider a common setting where a short sequence is read out repeatedly using a high-throughput long-read platform to generate multiple subreads, or noisy observations of the same sequence. Denoising these subreads with alignment-based approaches often fails when too few subreads are available or error rates are too high. In this paper, we propose a novel method for blindly denoising sets of sequences without directly observing clean source sequence labels. Our method, Self-Supervised Set Learning (SSSL), gathers subreads together in an embedding space and estimates a single set embedding as the midpoint of the subreads in both the latent and sequence spaces. This set embedding represents the "average" of the subreads and can be decoded into a prediction of the clean sequence. In experiments on simulated long-read DNA data, SSSL methods denoise small reads of $\leq 6$ subreads with 17% fewer errors and large reads of $>6$ subreads with 8% fewer errors compared to the best baseline. On a real dataset of antibody sequences, SSSL improves over baselines on two self-supervised metrics, with a significant improvement on difficult small reads that comprise over 60% of the test set. By accurately denoising these reads, SSSL promises to better realize the potential of high-throughput DNA sequencing data for downstream scientific applications.

{{</citation>}}


## cs.DC (2)



### (82/98) Towards Persistent Memory based Stateful Serverless Computing for Big Data Applications (Yuze Li et al., 2023)

{{<citation>}}

Yuze Li, Kevin Assogba, Abhijit Tripathy, Moiz Arif, M. Mustafa Rafique, Ali R. Butt, Dimitrios Nikolopoulos. (2023)  
**Towards Persistent Memory based Stateful Serverless Computing for Big Data Applications**  

---
Primary Category: cs.DC  
Categories: cs-DC, cs-PF, cs.DC  
Keywords: AWS  
[Paper Link](http://arxiv.org/abs/2309.01662v1)  

---


**ABSTRACT**  
The Function-as-a-service (FaaS) computing model has recently seen significant growth especially for highly scalable, event-driven applications. The easy-to-deploy and cost-efficient fine-grained billing of FaaS is highly attractive to big data applications. However, the stateless nature of serverless platforms poses major challenges when supporting stateful I/O intensive workloads such as a lack of native support for stateful execution, state sharing, and inter-function communication. In this paper, we explore the feasibility of performing stateful big data analytics on serverless platforms and improving I/O throughput of functions by using modern storage technologies such as Intel Optane DC Persistent Memory (PMEM). To this end, we propose Marvel, an end-to-end architecture built on top of the popular serverless platform, Apache OpenWhisk and Apache Hadoop. Marvel makes two main contributions: (1) enable stateful function execution on OpenWhisk by maintaining state information in an in-memory caching layer; and (2) provide access to PMEM backed HDFS storage for faster I/O performance. Our evaluation shows that Marvel reduces the overall execution time of big data applications by up to 86.6% compared to current MapReduce implementations on AWS Lambda.

{{</citation>}}


### (83/98) Objcache: An Elastic Filesystem over External Persistent Storage for Container Clusters (Takeshi Yoshimura et al., 2023)

{{<citation>}}

Takeshi Yoshimura, Tatsuhiro Chiba, Sunyanan Choochotkaew, Seetharami Seelam, Hui-fang Wen, Jonas Pfefferle. (2023)  
**Objcache: An Elastic Filesystem over External Persistent Storage for Container Clusters**  

---
Primary Category: cs.DC  
Categories: cs-DC, cs.DC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01399v1)  

---


**ABSTRACT**  
Container virtualization enables emerging AI workloads such as model serving, highly parallelized training, machine learning pipelines, and so on, to be easily scaled on demand on the elastic cloud infrastructure. Particularly, AI workloads require persistent storage to store data such as training inputs, models, and checkpoints. An external storage system like cloud object storage is a common choice because of its elasticity and scalability. To mitigate access latency to external storage, caching at a local filesystem is an essential technique. However, building local caches on scaling clusters must cope with explosive disk usage, redundant networking, and unexpected failures. We propose objcache, an elastic filesystem over external storage. Objcache introduces an internal transaction protocol over Raft logging to enable atomic updates of distributed persistent states with consistent hashing. The proposed transaction protocol can also manage inode dirtiness by maintaining the consistency between the local cache and external storage. Objcache supports scaling down to zero by automatically evicting dirty files to external storage. Our evaluation reports that objcache speeded up model serving startup by 98.9% compared to direct copies via S3 interfaces. Scaling up with dirty files completed from 2 to 14 seconds with 1024 dirty files.

{{</citation>}}


## cs.SI (1)



### (84/98) Evolving linguistic divergence on polarizing social media (Andres Karjus et al., 2023)

{{<citation>}}

Andres Karjus, Christine Cuskley. (2023)  
**Evolving linguistic divergence on polarizing social media**  

---
Primary Category: cs.SI  
Categories: cs-CL, cs-SI, cs.SI  
Keywords: Twitter  
[Paper Link](http://arxiv.org/abs/2309.01659v1)  

---


**ABSTRACT**  
Language change is influenced by many factors, but often starts from synchronic variation, where multiple linguistic patterns or forms coexist, or where different speech communities use language in increasingly different ways. Besides regional or economic reasons, communities may form and segregate based on political alignment. The latter, referred to as political polarization, is of growing societal concern across the world. Here we map and quantify linguistic divergence across the partisan left-right divide in the United States, using social media data. We develop a general methodology to delineate (social) media users by their political preference, based on which (potentially biased) news media accounts they do and do not follow on a given platform. Our data consists of 1.5M short posts by 10k users (about 20M words) from the social media platform Twitter (now "X"). Delineating this sample involved mining the platform for the lists of followers (n=422M) of 72 large news media accounts. We quantify divergence in topics of conversation and word frequencies, messaging sentiment, and lexical semantics of words and emoji. We find signs of linguistic divergence across all these aspects, especially in topics and themes of conversation, in line with previous research. While US American English remains largely intelligible within its large speech community, our findings point at areas where miscommunication may eventually arise given ongoing polarization and therefore potential linguistic divergence. Our methodology - combining data mining, lexicostatistics, machine learning, large language models and a systematic human annotation approach - is largely language and platform agnostic. In other words, while we focus here on US political divides and US English, the same approach is applicable to other countries, languages, and social media platforms.

{{</citation>}}


## cs.AI (4)



### (85/98) Concepts is All You Need: A More Direct Path to AGI (Peter Voss et al., 2023)

{{<citation>}}

Peter Voss, Mladjan Jovanovic. (2023)  
**Concepts is All You Need: A More Direct Path to AGI**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2309.01622v1)  

---


**ABSTRACT**  
Little demonstrable progress has been made toward AGI (Artificial General Intelligence) since the term was coined some 20 years ago. In spite of the fantastic breakthroughs in Statistical AI such as AlphaZero, ChatGPT, and Stable Diffusion none of these projects have, or claim to have, a clear path to AGI. In order to expedite the development of AGI it is crucial to understand and identify the core requirements of human-like intelligence as it pertains to AGI. From that one can distill which particular development steps are necessary to achieve AGI, and which are a distraction. Such analysis highlights the need for a Cognitive AI approach rather than the currently favored statistical and generative efforts. More specifically it identifies the central role of concepts in human-like cognition. Here we outline an architecture and development plan, together with some preliminary results, that offers a much more direct path to full Human-Level AI (HLAI)/ AGI.

{{</citation>}}


### (86/98) ChatRule: Mining Logical Rules with Large Language Models for Knowledge Graph Reasoning (Linhao Luo et al., 2023)

{{<citation>}}

Linhao Luo, Jiaxin Ju, Bo Xiong, Yuan-Fang Li, Gholamreza Haffari, Shirui Pan. (2023)  
**ChatRule: Mining Logical Rules with Large Language Models for Knowledge Graph Reasoning**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: Knowledge Graph, Language Model, Reasoning  
[Paper Link](http://arxiv.org/abs/2309.01538v1)  

---


**ABSTRACT**  
Logical rules are essential for uncovering the logical connections between relations, which could improve the reasoning performance and provide interpretable results on knowledge graphs (KGs). Although there have been many efforts to mine meaningful logical rules over KGs, existing methods suffer from the computationally intensive searches over the rule space and a lack of scalability for large-scale KGs. Besides, they often ignore the semantics of relations which is crucial for uncovering logical connections. Recently, large language models (LLMs) have shown impressive performance in the field of natural language processing and various applications, owing to their emergent ability and generalizability. In this paper, we propose a novel framework, ChatRule, unleashing the power of large language models for mining logical rules over knowledge graphs. Specifically, the framework is initiated with an LLM-based rule generator, leveraging both the semantic and structural information of KGs to prompt LLMs to generate logical rules. To refine the generated rules, a rule ranking module estimates the rule quality by incorporating facts from existing KGs. Last, a rule validator harnesses the reasoning ability of LLMs to validate the logical correctness of ranked rules through chain-of-thought reasoning. ChatRule is evaluated on four large-scale KGs, w.r.t. different rule quality metrics and downstream tasks, showing the effectiveness and scalability of our method.

{{</citation>}}


### (87/98) Learning a Patent-Informed Biomedical Knowledge Graph Reveals Technological Potential of Drug Repositioning Candidates (Yongseung Jegal et al., 2023)

{{<citation>}}

Yongseung Jegal, Jaewoong Choi, Jiho Lee, Ki-Su Park, Seyoung Lee, Janghyeok Yoon. (2023)  
**Learning a Patent-Informed Biomedical Knowledge Graph Reveals Technological Potential of Drug Repositioning Candidates**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-LG, cs.AI, q-bio-QM  
Keywords: Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2309.03227v1)  

---


**ABSTRACT**  
Drug repositioning-a promising strategy for discovering new therapeutic uses for existing drugs-has been increasingly explored in the computational science literature using biomedical databases. However, the technological potential of drug repositioning candidates has often been overlooked. This study presents a novel protocol to comprehensively analyse various sources such as pharmaceutical patents and biomedical databases, and identify drug repositioning candidates with both technological potential and scientific evidence. To this end, first, we constructed a scientific biomedical knowledge graph (s-BKG) comprising relationships between drugs, diseases, and genes derived from biomedical databases. Our protocol involves identifying drugs that exhibit limited association with the target disease but are closely located in the s-BKG, as potential drug candidates. We constructed a patent-informed biomedical knowledge graph (p-BKG) by adding pharmaceutical patent information. Finally, we developed a graph embedding protocol to ascertain the structure of the p-BKG, thereby calculating the relevance scores of those candidates with target disease-related patents to evaluate their technological potential. Our case study on Alzheimer's disease demonstrates its efficacy and feasibility, while the quantitative outcomes and systematic methods are expected to bridge the gap between computational discoveries and successful market applications in drug repositioning research.

{{</citation>}}


### (88/98) AlphaZero Gomoku (Wen Liang et al., 2023)

{{<citation>}}

Wen Liang, Chao Yu, Brian Whiteaker, Inyoung Huh, Hua Shao, Youzhi Liang. (2023)  
**AlphaZero Gomoku**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.01294v1)  

---


**ABSTRACT**  
In the past few years, AlphaZero's exceptional capability in mastering intricate board games has garnered considerable interest. Initially designed for the game of Go, this revolutionary algorithm merges deep learning techniques with the Monte Carlo tree search (MCTS) to surpass earlier top-tier methods. In our study, we broaden the use of AlphaZero to Gomoku, an age-old tactical board game also referred to as "Five in a Row." Intriguingly, Gomoku has innate challenges due to a bias towards the initial player, who has a theoretical advantage. To add value, we strive for a balanced game-play. Our tests demonstrate AlphaZero's versatility in adapting to games other than Go. MCTS has become a predominant algorithm for decision processes in intricate scenarios, especially board games. MCTS creates a search tree by examining potential future actions and uses random sampling to predict possible results. By leveraging the best of both worlds, the AlphaZero technique fuses deep learning from Reinforcement Learning with the balancing act of MCTS, establishing a fresh standard in game-playing AI. Its triumph is notably evident in board games such as Go, chess, and shogi.

{{</citation>}}


## cs.AR (1)



### (89/98) SATAY: A Streaming Architecture Toolflow for Accelerating YOLO Models on FPGA Devices (Alexander Montgomerie-Corcoran et al., 2023)

{{<citation>}}

Alexander Montgomerie-Corcoran, Petros Toupas, Zhewen Yu, Christos-Savvas Bouganis. (2023)  
**SATAY: A Streaming Architecture Toolflow for Accelerating YOLO Models on FPGA Devices**  

---
Primary Category: cs.AR  
Categories: cs-AR, cs-CV, cs-LG, cs.AR  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01587v1)  

---


**ABSTRACT**  
AI has led to significant advancements in computer vision and image processing tasks, enabling a wide range of applications in real-life scenarios, from autonomous vehicles to medical imaging. Many of those applications require efficient object detection algorithms and complementary real-time, low latency hardware to perform inference of these algorithms. The YOLO family of models is considered the most efficient for object detection, having only a single model pass. Despite this, the complexity and size of YOLO models can be too computationally demanding for current edge-based platforms. To address this, we present SATAY: a Streaming Architecture Toolflow for Accelerating YOLO. This work tackles the challenges of deploying stateof-the-art object detection models onto FPGA devices for ultralow latency applications, enabling real-time, edge-based object detection. We employ a streaming architecture design for our YOLO accelerators, implementing the complete model on-chip in a deeply pipelined fashion. These accelerators are generated using an automated toolflow, and can target a range of suitable FPGA devices. We introduce novel hardware components to support the operations of YOLO models in a dataflow manner, and off-chip memory buffering to address the limited on-chip memory resources. Our toolflow is able to generate accelerator designs which demonstrate competitive performance and energy characteristics to GPU devices, and which outperform current state-of-the-art FPGA accelerators.

{{</citation>}}


## cs.RO (1)



### (90/98) Recognition of Heat-Induced Food State Changes by Time-Series Use of Vision-Language Model for Cooking Robot (Naoaki Kanazawa et al., 2023)

{{<citation>}}

Naoaki Kanazawa, Kento Kawaharazuka, Yoshiki Obinata, Kei Okada, Masayuki Inaba. (2023)  
**Recognition of Heat-Induced Food State Changes by Time-Series Use of Vision-Language Model for Cooking Robot**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.01528v2)  

---


**ABSTRACT**  
Cooking tasks are characterized by large changes in the state of the food, which is one of the major challenges in robot execution of cooking tasks. In particular, cooking using a stove to apply heat to the foodstuff causes many special state changes that are not seen in other tasks, making it difficult to design a recognizer. In this study, we propose a unified method for recognizing changes in the cooking state of robots by using the vision-language model that can discriminate open-vocabulary objects in a time-series manner. We collected data on four typical state changes in cooking using a real robot and confirmed the effectiveness of the proposed method. We also compared the conditions and discussed the types of natural language prompts and the image regions that are suitable for recognizing the state changes.

{{</citation>}}


## cs.SD (3)



### (91/98) BadSQA: Stealthy Backdoor Attacks Using Presence Events as Triggers in Non-Intrusive Speech Quality Assessment (Ying Ren et al., 2023)

{{<citation>}}

Ying Ren, Kailai Shen, Zhe Ye, Diqun Yan. (2023)  
**BadSQA: Stealthy Backdoor Attacks Using Presence Events as Triggers in Non-Intrusive Speech Quality Assessment**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-SD, cs.SD, eess-AS  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2309.01480v1)  

---


**ABSTRACT**  
Non-Intrusive speech quality assessment (NISQA) has gained significant attention for predicting the mean opinion score (MOS) of speech without requiring the reference speech. In practical NISQA scenarios, untrusted third-party resources are often employed during deep neural network training to reduce costs. However, it would introduce a potential security vulnerability as specially designed untrusted resources can launch backdoor attacks against NISQA systems. Existing backdoor attacks primarily focus on classification tasks and are not directly applicable to NISQA which is a regression task. In this paper, we propose a novel backdoor attack on NISQA tasks, leveraging presence events as triggers to achieving highly stealthy attacks. To evaluate the effectiveness of our proposed approach, we conducted experiments on four benchmark datasets and employed two state-of-the-art NISQA models. The results demonstrate that the proposed backdoor attack achieved an average attack success rate of up to 99% with a poisoning rate of only 3%.

{{</citation>}}


### (92/98) Text-Only Domain Adaptation for End-to-End Speech Recognition through Down-Sampling Acoustic Representation (Jiaxu Zhu et al., 2023)

{{<citation>}}

Jiaxu Zhu, Weinan Tong, Yaoxun Xu, Changhe Song, Zhiyong Wu, Zhao You, Dan Su, Dong Yu, Helen Meng. (2023)  
**Text-Only Domain Adaptation for End-to-End Speech Recognition through Down-Sampling Acoustic Representation**  

---
Primary Category: cs.SD  
Categories: cs-CL, cs-SD, cs.SD, eess-AS  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2309.02459v1)  

---


**ABSTRACT**  
Mapping two modalities, speech and text, into a shared representation space, is a research topic of using text-only data to improve end-to-end automatic speech recognition (ASR) performance in new domains. However, the length of speech representation and text representation is inconsistent. Although the previous method up-samples the text representation to align with acoustic modality, it may not match the expected actual duration. In this paper, we proposed novel representations match strategy through down-sampling acoustic representation to align with text modality. By introducing a continuous integrate-and-fire (CIF) module generating acoustic representations consistent with token length, our ASR model can learn unified representations from both modalities better, allowing for domain adaptation using text-only data of the target domain. Experiment results of new domain data demonstrate the effectiveness of the proposed method.

{{</citation>}}


### (93/98) SememeASR: Boosting Performance of End-to-End Speech Recognition against Domain and Long-Tailed Data Shift with Sememe Semantic Knowledge (Jiaxu Zhu et al., 2023)

{{<citation>}}

Jiaxu Zhu, Changhe Song, Zhiyong Wu, Helen Meng. (2023)  
**SememeASR: Boosting Performance of End-to-End Speech Recognition against Domain and Long-Tailed Data Shift with Sememe Semantic Knowledge**  

---
Primary Category: cs.SD  
Categories: cs-CL, cs-SD, cs.SD, eess-AS  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2309.01437v1)  

---


**ABSTRACT**  
Recently, excellent progress has been made in speech recognition. However, pure data-driven approaches have struggled to solve the problem in domain-mismatch and long-tailed data. Considering that knowledge-driven approaches can help data-driven approaches alleviate their flaws, we introduce sememe-based semantic knowledge information to speech recognition (SememeASR). Sememe, according to the linguistic definition, is the minimum semantic unit in a language and is able to represent the implicit semantic information behind each word very well. Our experiments show that the introduction of sememe information can improve the effectiveness of speech recognition. In addition, our further experiments show that sememe knowledge can improve the model's recognition of long-tailed data and enhance the model's domain generalization ability.

{{</citation>}}


## cs.LO (1)



### (94/98) Lifting the Reasoning Level in Generic Weak Memory Verification (Extended Version) (Lara Bargmann et al., 2023)

{{<citation>}}

Lara Bargmann, Heike Wehrheim. (2023)  
**Lifting the Reasoning Level in Generic Weak Memory Verification (Extended Version)**  

---
Primary Category: cs.LO  
Categories: cs-LO, cs-PL, cs.LO  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2309.01433v1)  

---


**ABSTRACT**  
Weak memory models specify the semantics of concurrent programs on multi-core architectures. Reasoning techniques for weak memory models are often specialized to one fixed model and verification results are hence not transferable to other memory models. A recent proposal of a generic verification technique based on axioms on program behaviour expressed via weakest preconditions aims at overcoming this specialization to dedicated models. Due to the usage of weakest preconditions, reasoning however takes place on a very low level requiring the application of numerous axioms for deriving program properties, even for a single statement. In this paper, we lift reasoning in this generic verification approach to a more abstract level. Based on a view-based assertion language, we provide a number of novel proof rules for directly reasoning on the level of program constructs. We prove soundness of our proof rules and exemplify them on the write-to-read causality (WRC) litmus test. A comparison to the axiom-based low-level proof reveals a significant reduction in the number of required proof steps.

{{</citation>}}


## cs.NI (1)



### (95/98) A Unified Framework for Guiding Generative AI with Wireless Perception in Resource Constrained Mobile Edge Networks (Jiacheng Wang et al., 2023)

{{<citation>}}

Jiacheng Wang, Hongyang Du, Dusit Niyato, Jiawen Kang, Zehui Xiong, Deepu Rajan, Shiwen Mao, Xuemin, Shen. (2023)  
**A Unified Framework for Guiding Generative AI with Wireless Perception in Resource Constrained Mobile Edge Networks**  

---
Primary Category: cs.NI  
Categories: cs-NI, cs.NI, eess-SP  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2309.01426v1)  

---


**ABSTRACT**  
With the significant advancements in artificial intelligence (AI) technologies and powerful computational capabilities, generative AI (GAI) has become a pivotal digital content generation technique for offering superior digital services. However, directing GAI towards desired outputs still suffer the inherent instability of the AI model. In this paper, we design a novel framework that utilizes wireless perception to guide GAI (WiPe-GAI) for providing digital content generation service, i.e., AI-generated content (AIGC), in resource-constrained mobile edge networks. Specifically, we first propose a new sequential multi-scale perception (SMSP) algorithm to predict user skeleton based on the channel state information (CSI) extracted from wireless signals. This prediction then guides GAI to provide users with AIGC, such as virtual character generation. To ensure the efficient operation of the proposed framework in resource constrained networks, we further design a pricing-based incentive mechanism and introduce a diffusion model based approach to generate an optimal pricing strategy for the service provisioning. The strategy maximizes the user's utility while enhancing the participation of the virtual service provider (VSP) in AIGC provision. The experimental results demonstrate the effectiveness of the designed framework in terms of skeleton prediction and optimal pricing strategy generation comparing with other existing solutions.

{{</citation>}}


## math.OC (1)



### (96/98) Finite/fixed-time Stabilization of Linear Systems with States Quantization (Yu Zhou et al., 2023)

{{<citation>}}

Yu Zhou, Andrey Polyakov, Gang Zheng. (2023)  
**Finite/fixed-time Stabilization of Linear Systems with States Quantization**  

---
Primary Category: math.OC  
Categories: cs-SY, eess-SY, math-OC, math.OC  
Keywords: Quantization  
[Paper Link](http://arxiv.org/abs/2309.01412v2)  

---


**ABSTRACT**  
This paper develops a homogeneity-based approach to finite/fixed-time stabilization of linear time-invariant (LTI) system with quantized measurements. A sufficient condition for finite/fixed-time stabilization of multi-input LTI system under states quantization is derived. It is shown that a homogeneous quantized state feedback with logarithmic quantizer can guarantee finite/fixed-time stability of the closed-loop system provided that the quantization is sufficiently dense. Theoretical results are supported with numerical simulations.

{{</citation>}}


## cs.HC (1)



### (97/98) A Survey for Graphic Design Intelligence (Danqing Huang et al., 2023)

{{<citation>}}

Danqing Huang, Jiaqi Guo, Shizhao Sun, Hanling Tian, Jieru Lin, Zheng Hu, Chin-Yew Lin, Jian-Guang Lou, Dongmei Zhang. (2023)  
**A Survey for Graphic Design Intelligence**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01371v1)  

---


**ABSTRACT**  
Graphic design is an effective language for visual communication. Using complex composition of visual elements (e.g., shape, color, font) guided by design principles and aesthetics, design helps produce more visually-appealing content. The creation of a harmonious design requires carefully selecting and combining different visual elements, which can be challenging and time-consuming. To expedite the design process, emerging AI techniques have been proposed to automatize tedious tasks and facilitate human creativity. However, most current works only focus on specific tasks targeting at different scenarios without a high-level abstraction. This paper aims to provide a systematic overview of graphic design intelligence and summarize literature in the taxonomy of representation, understanding and generation. Specifically we consider related works for individual visual elements as well as the overall design composition. Furthermore, we highlight some of the potential directions for future explorations.

{{</citation>}}


## cs.SC (1)



### (98/98) Partial Proof of a Conjecture with Implications for Spectral Majorization (Jeffrey Uhlmann, 2023)

{{<citation>}}

Jeffrey Uhlmann. (2023)  
**Partial Proof of a Conjecture with Implications for Spectral Majorization**  

---
Primary Category: cs.SC  
Categories: cs-AI, cs-SC, cs.SC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.01302v1)  

---


**ABSTRACT**  
In this paper we report on new results relating to a conjecture regarding properties of $n\times n$, $n\leq 6$, positive definite matrices. The conjecture has been proven for $n\leq 4$ using computer-assisted sum of squares (SoS) methods for proving polynomial nonnegativity. Based on these proven cases, we report on the recent identification of a new family of matrices with the property that their diagonals majorize their spectrum. We then present new results showing that this family can extended via Kronecker composition to $n>6$ while retaining the special majorization property. We conclude with general considerations on the future of computer-assisted and AI-based proofs.

{{</citation>}}
