
# Subtopic: Handwritten Mathematical Expression Recognition (closest cousin)


# Enhanced handwritten mathematical expression recognition via wavelet feature integration


## Abstract

Handwritten mathematical expression recognition (HMER) plays a crucial role in intelligent education and document automation. However, existing methods often struggle with symbol ambiguities, stroke irregularities, and visually similar patterns. To overcome these challenges, we introduce WaveMER, a novel framework that leverages discrete wavelet transform (DWT) to explicitly introduce frequency-domain information into the recognition pipeline. WaveMER couples a DenseNet-based spatial encoder with a DWT-derived frequency pathway, in which FERB produces frequency features and WFA highlights salient channels. An adaptive cross-domain fusion block then aligns and fuses the spatial and frequency streams, enabling the model to capture both global structural patterns and fine-grained frequency cues. Comprehensive experiments on the CROHME 2014, 2016, and 2019 benchmarks demonstrate the superiority of WaveMER, achieving expression recognition rates of 60.55%, 60.68%, and 62.38%, respectively. Here, we show that incorporating frequency-domain information significantly enhances HMER performance, offering a robust solution for accurate mathematical expression recognition. The source code is available at  [https://github.com/Ethereal-dot/WaveMER](https://github.com/Ethereal-dot/WaveMER).

# STAF: Symbol-Targeted Adversarial Flow for Handwritten Mathematical Expression Recognition


## Abstract

Targeted adversarial robustness in handwritten mathematical expression recognition (HMER) systems remains a critical yet underexplored problem. We propose STAF, a novel flow-based framework for targeted attacks that performs fine-grained, symbol-level manipulations through differentiable geometric perturbations while preserving high visual fidelity. Instead of injecting pixel-level noise, our method learns a sparse flow field to induce localized structural deformations that align with the desired target expression. To guide perturbations toward the intended symbol without manual supervision, we leverage the cross-modal attention of the HMER model during optimization. Furthermore, we incorporate a composite loss function combining weighted adversarial loss, total variation, Laplacian regularization, and flow sparsity to ensure spatial continuity and perceptual naturalness. Extensive experiments on the CROHME benchmark demonstrate the superiority of our approach over existing baselines in both attack success rate and visual quality. Flow field visualizations reveal strong spatial alignment between perturbation and target symbols, highlighting the interpretability of our strategy. This study exposes critical vulnerabilities in sequence recognition models and provides new insights into building more robust HMER systems. The source code of this work is available at:  [https://github.com/givesoftware/STAF/tree/main](https://github.com/givesoftware/STAF/tree/main).


# Refined and Locality-Enhanced Feature for Handwritten Mathematical Expression Recognition

## Abstract

Many studies have been conducted on handwritten mathematical expression recognition (HMER) based on encoder-decoder architecture. However, the previous methods fail to predict accurate results due to low-quality images such as blur, complex background and distortion. In addition, ambiguous or subtle symbols caused by different handwriting styles are often recognized incorrectly. In this paper, we propose an efficient method for HMER to deal with the above issues. Specifically, we propose a Dual-branch Refinement Module (DRM) to deal with the challenging disturbances. In terms of ambiguous or subtle symbols, we believe that the combination of local and global information is beneficial to recognizing these symbols. Therefore, we design a Local Feature Enhancement Module (LFEM) to enhance local features, which can cooperate with global information extracted by the following transformer decoder. Extensive experimental results on CROHME and HME100K datasets verify the effectiveness of our method.




# PosFormer: Recognizing Complex Handwritten Mathematical Expression with Position Forest Transformer

## Abstract

Handwritten Mathematical Expression Recognition (HMER) has wide applications in human-machine interaction scenarios, such as digitized education and automated offices. Recently, sequence-based models with encoder-decoder architectures have been commonly adopted to address this task by directly predicting LaTeX sequences of expression images. However, these methods only implicitly learn the syntax rules provided by LaTeX, which may fail to describe the position and hierarchical relationship between symbols due to complex structural relations and diverse handwriting styles. To overcome this challenge, we propose a  position  forest transformer  (PosFormer) for HMER, which jointly optimizes two tasks: expression recognition and position recognition, to explicitly enable position-aware symbol feature representation learning. Specifically, we first design a position forest that models the mathematical expression as a forest structure and parses the relative position relationships between symbols. Without requiring extra annotations, each symbol is assigned a position identifier in the forest to denote its relative spatial position. Second, we propose an implicit attention correction module to accurately capture attention for HMER in the sequence-based decoder architecture. Extensive experiments validate the superiority of PosFormer, which consistently outperforms the state-of-the-art methods 2.03%/1.22%/2.00%, 1.83%, and 4.62% gains on the single-line CROHME 2014/2016/2019, multi-line ME, and complex MNE datasets, respectively, with no additional latency or computational cost.

# MFH: Marrying Frequency Domain with Handwritten Mathematical Expression Recognition
## Abstract

Handwritten mathematical expression recognition (HMER) suffers from complex formula structures and character layouts in sequence prediction. In this paper, we incorporate frequency domain analysis into HMER and propose a method that  **m**arries  **f**requency domain with  **H**MER (MFH), leveraging the discrete cosine transform (DCT). We emphasize the structural analysis assistance of frequency information for recognizing mathematical formulas. When implemented on various baseline models, our network exhibits a consistent performance enhancement, demonstrating the efficacy of frequency domain information. Experiments show that our MFH-CoMER achieves noteworthy accuracy rates of 61.66%/62.07%/63.72% on the CROHME 2014/2016/2019 test sets. The source code is available at  [https://github.com/Hryxyhe/MFH](https://github.com/Hryxyhe/MFH).



# NAMER: Non-autoregressive Modeling for Handwritten Mathematical Expression Recognition

## Abstract

Recently, Handwritten Mathematical Expression Recognition (HMER) has gained considerable attention in pattern recognition for its diverse applications in document understanding. Current methods typically approach HMER as an image-to-sequence generation task within an autoregressive (AR) encoder-decoder framework. However, these approaches suffer from several drawbacks: 1) a lack of overall language context, limiting information utilization beyond the current decoding step; 2) error accumulation during AR decoding; and 3) slow decoding speed. To tackle these problems, this paper makes the first attempt to build a novel bottom-up  **N**on-**A**utoRegressive  **M**odeling approach for H**MER**, called NAMER. NAMER comprises a Visual Aware Tokenizer (VAT) and a Parallel Graph Decoder (PGD). Initially, the VAT tokenizes visible symbols and local relations at a coarse level. Subsequently, the PGD refines all tokens and establishes connectivities in parallel, leveraging comprehensive visual and linguistic contexts. Experiments on CROHME 2014/2016/2019 and HME100K datasets demonstrate that NAMER not only outperforms the current state-of-the-art (SOTA) methods on ExpRate by 1.93%/2.35%/1.49%/0.62%, but also achieves significant speedups of 13.7  and 6.7  faster in decoding time and overall FPS, proving the effectiveness and efficiency of NAMER.



# Offline handwritten mathematical recognition using adversarial learning and transformers

## Abstract

Offline handwritten mathematical expression recognition (HMER) is a significant area in mathematical expression recognition. However, offline HMER is often viewed as a much more complex problem than online HMER due to a lack of temporal information and variability in writing style. This paper proposes an encoder–decoder model that uses paired adversarial learning. Semantic-invariant features are extracted from handwritten mathematical expression images and their printed mathematical expression counterpart in the encoder. Learning semantic-invariant features combined with the DenseNet encoder and transformer decoder helped us to improve the expression rate from previous studies. Evaluated on the CROHME dataset, we have improved the latest CROHME 2019 test set results by 4% approx.



# CoMER: Modeling Coverage for Transformer-Based Handwritten Mathematical Expression Recognition


## Abstract

The Transformer-based encoder-decoder architecture has recently made significant advances in recognizing handwritten mathematical expressions. However, the transformer model still suffers from the lack of coverage problem, making its expression recognition rate (ExpRate) inferior to its RNN counterpart. Coverage information, which records the alignment information of the past steps, has proven effective in the RNN models. In this paper, we propose CoMER, a model that adopts the coverage information in the transformer decoder. Specifically, we propose a novel Attention Refinement Module (ARM) to refine the attention weights with past alignment information without hurting its parallelism. Furthermore, we take coverage information to the extreme by proposing self-coverage and cross-coverage, which utilize the past alignment information from the current and previous layers. Experiments show that CoMER improves the ExpRate by 0.61%/2.09%/1.59% compared to the current state-of-the-art model, and reaches 59.33%/59.81%/62.97% on the CROHME 2014/2016/2019 test sets. (Source code is available at  [https://github.com/Green-Wood/CoMER](https://github.com/Green-Wood/CoMER))



# AutoScaler: Self scale alignment for handwritten mathematical expression recognition


## Abstract

Handwritten mathematical expression recognition (HMER) remains a challenging task in computer vision due to the complex spatial structures and diverse handwriting styles of mathematical expressions. While current approaches focus heavily on decoder modeling, the critical influence of input scale variations on recognition accuracy has been largely overlooked. This paper introduces AutoScaler, a novel scale-adaptive framework that addresses the issue of scale misalignment between input images and decoders for the first time in HMER. Our method comprises two novel components: (1) Stochastic Scale Training, a training strategy that enhances the model’s robustness to scale variations by enabling it to perceive mathematical expressions across diverse scales; (2) Optimal Scale Estimation, an inference technique that identifies the most suitable scale for each input image, ensuring proper alignment of visual features with decoder. Additionally, we propose Cross-scale Joint Approximation, which leverages complementary information between optimal and sub-optimal scales to further improve recognition performance. Extensive experiments on real-world datasets show our method achieves state-of-the-art results for both single-line and multi-line expressions, underscoring its effectiveness in advancing HMER. The code and model are available at  [https://github.com/SCUT-DLVCLab/AutoScaler](https://github.com/SCUT-DLVCLab/AutoScaler).


# Improving Handwritten Mathematical Expression Recognition via Similar Symbol Distinguishing

## Abstract:

Handwritten mathematical expression recognition (HMER) is an essential task in the OCR community, which consists of two sub-tasks, i.e., symbol recognition and structure parsing. Modern literature treats HMER as a LaTeX sequence predicting problem that simultaneously recognizes symbols and parses the structures of MEs. Although deep learning-based HMER methods have been achieving promising results on public benchmarks, it is admitted that the misclassification error between visually similar symbols still prevents these approaches from more generalized scenes. In this paper, we try to solve this issue from three aspects. 1) We enhanced the feature extraction progress by introducing path signature features, which incorporates local writing details and global spatial information. 2) We developed a language model that uses contextual information to correct the symbols misclassified by vision-only-based recognition models. 3) We solved the misalignment problem in existing ensemble method by designing a dynamic time warping (DTW) based algorithm. By combining the above improvements, our method achieved state-of-the-art results on three CROHME benchmarks, outperforming previous methods by a large margin.



# When Counting Meets HMER: Counting-Aware Network for Handwritten Mathematical Expression Recognition


## Abstract

Recently, most handwritten mathematical expression recognition (HMER) methods adopt the encoder-decoder networks, which directly predict the markup sequences from formula images with the attention mechanism. However, such methods may fail to accurately read formulas with complicated structure or generate long markup sequences, as the attention results are often inaccurate due to the large variance of writing styles or spatial layouts. To alleviate this problem, we propose an unconventional network for HMER named Counting-Aware Network (CAN), which jointly optimizes two tasks: HMER and symbol counting. Specifically, we design a weakly-supervised counting module that can predict the number of each symbol class without the symbol-level position annotations, and then plug it into a typical attention-based encoder-decoder model for HMER. Experiments on the benchmark datasets for HMER validate that both joint optimization and counting results are beneficial for correcting the prediction errors of encoder-decoder models, and CAN consistently outperforms the state-of-the-art methods. In particular, compared with an encoder-decoder model for HMER, the extra time cost caused by the proposed counting module is marginal. The source code is available at  [https://github.com/LBH1024/CAN](https://github.com/LBH1024/CAN).



# TST: Tree Structured Transformer for Handwritten Mathematical Expression Recognition

## Abstract

Handwritten Mathematical Expression Recognition (HMER) is a challenging task due to the complexity of mathematical symbols and the variability of handwriting styles. Tree Structured Transformer (TST) is proposed to recognize handwritten mathematical expressions by predicting the Symbol Layout Tree (SLT) of the expression. The proposed method is based on an Encoder-Decoder architecture, where the Decoder is designed to predict the tree structure of the expression, which predicts the node labels, edge labels, and parent index of each node. This TST Decoder can be combined with different Encoder to handle both online or offline handwritten mathematical expressions with CNN-based Encoder for offline HMER and Graph-based Encoder for online HMER. Both the online and offline systems are evaluated on the CROHME 2023 dataset, and evaluated by the standard evaluation tools, achieving competitive results compared to the state-of-the-art methods.




# Hybrid Neural Network for Handwritten Mathematical Expression Recognition system

## Abstract:

The mathematical expression is an essential part of every domain they provide the mathematical explanation for one’s theory. The technological advancement in the domain of artificial intelligence has aided in various handwritten recognition systems such as handwritten mathematical expression recognition. Symbol recognition and structural analysis are two major obstacles in handwritten mathematical expression recognition. In this paper, we propose a hybrid neural network algorithm called validator, tracker, attention, and parser (VTAP). The hybrid neural network algorithms like CRNN is a blend of recurrent neural network (RNN) and convolutional neural network (CNN). It has shown better and more accurate outputs than the native CNN and RNN algorithms alone. CROHME dataset is used, which is the most widely used dataset. The recognition is divided into 4 parts validator, tracker, attention, and parser (VTAP). A tracker is equipped with a group of Bi-Directional Recurrent Network (BRNN) with the Gated Recurrent Unit (GRU). Succeeded by a tracker, the parser uses a GRU lead by guided hybrid attention. The accuracy and the time complexity of VTAP is compared with existing work Tracker, Attention and Parser (TAP), VTAP shows up to 92.2% of accuracy while TAP shows an accuracy of 89%.





# La-Math-ex: LaTeX Code Generation for Handwritten Mathematical Expressions

## Abstract:

We present a novel approach to offline handwritten mathematical expression (HME) recognition and LaTeX code generation by fine-tuning Microsoft's TrOCR-Base vision-language Transformer on the MathWriting dataset. The TrOCR architecture couples a BEiT-initialized image Transformer encoder processing inputs as sequences of  16×16  pixel patches augmented with absolute positional embeddings with a RoBERTa initialized text Transformer decoder that autoregressively emits LaTeX tokens. Each sample comprises a handwritten formula paired with both raw and normalized LaTeX annotations to facilitate learning of structural conventions. Training was conducted using the Hugging Face Seq2Seq Trainer with cross-entropy loss and teacher-forcing. Our model achieves a character error rate (CER) of 4.72% and an exact-match formula accuracy of 75.0% on held-out test data, representing a significant improvement over traditional OCR engines (CER  ≈12%) and CTC-based Transformer baselines (exact-match  ≈58%). We analyze error patterns highlighting challenges in nested superscripting and ambiguous stroke segmentation and demonstrate that large pre-trained vision-language models can be effectively specialized for two-dimensional notation.



# Handwritten Mathematical Expression Recognition with Bidirectionally Trained Transformer

## Abstract

Encoder-decoder models have made great progress on handwritten mathematical expression recognition recently. However, it is still a challenge for existing methods to assign attention to image features accurately. Moreover, those encoder-decoder models usually adopt RNN-based models in their decoder part, which makes them inefficient in processing long  ![](https://media.springernature.com/lw48/springer-static/image/chp%3A10.1007%2F978-3-030-86331-9_37/MediaObjects/520871_1_En_37_Figa_HTML.gif)  sequences. In this paper, a transformer-based decoder is employed to replace RNN-based ones, which makes the whole model architecture very concise. Furthermore, a novel training strategy is introduced to fully exploit the potential of the transformer in bidirectional language modeling. Compared to several methods that do not use data augmentation, experiments demonstrate that our model improves the ExpRate of current state-of-the-art methods on CROHME 2014 by 2.23%. Similarly, on CROHME 2016 and CROHME 2019, we improve

# TAMER: Tree-Aware Transformer for Handwritten Mathematical Expression Recognition

## Abstract

Handwritten Mathematical Expression Recognition (HMER) has extensive applications in automated grading and office automation. However, existing sequence-based decoding methods, which directly predict LaTeX sequences, struggle to understand and model the inherent tree structure of LaTeX and often fail to ensure syntactic correctness in the decoded results. To address these challenges, we propose a novel model named TAMER (Tree-Aware Transformer) for handwritten mathematical expression recognition. TAMER introduces an innovative Tree-aware Module while maintaining the flexibility and efficient training of Transformer. TAMER combines the advantages of both sequence decoding and tree decoding models by jointly optimizing sequence prediction and tree structure prediction tasks, which enhances the model's understanding and generalization of complex mathematical expression structures. During inference, TAMER employs a Tree Structure Prediction Scoring Mechanism to improve the structural validity of the generated LaTeX sequences. Experimental results on CROHME datasets demonstrate that TAMER outperforms traditional sequence decoding and tree decoding models, especially in handling complex mathematical structures, achieving state-of-the-art (SOTA) performance.
