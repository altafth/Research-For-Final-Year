# Main Topic:  ChemAssist-BD: A Primary Dataset and Deep Learning Framework for Handwritten Chemistry Formula Recognition and Error Localization


## Subtopics(A,B,C,D,E) and related paper  with abstractions are belows: 

# A. Handwritten chemical formula/equation -recognition (core)



# A Unified Framework for Recognizing Handwritten Chemical Expressions

## Abstract:

Chemical expressions have more variant structures in 2-D space than that in math equations. In this paper we propose a unified framework for recognizing handwritten chemical expressions including both inorganic and organic expressions. A set of novel statistical algorithms is presented in two key components of this framework: symbol grouping and structure analysis. Non-symbol modeling and inter-group modeling are proposed to achieve better grouping result, and bond modeling is proposed to group the special bond symbols in the unified framework. A graph-based representation (CESG) is defined for representing generic chemical expressions, and the structure analysis problem is formulated as a search problem for CESG over a weighted direction graph. Experiments on a database of more than 35,000 expressions were conducted and results are presented.







# The Understanding and Structure Analyzing for Online Handwritten Chemical Formulas

## Abstract:

In this paper, we propose a novel approach for understanding and analyzing the online handwritten chemical formulas. With the structural characteristics, semantic rules, and more importantly grammatical rules, the analyzing process is divided into 3 levels: formula level, molecule level, and text level. A formal description of the chemical formula based-on the grammatical rules is summed up and applied to the analyzing process which generates grammar spanning graphs from the analyzed result step-by-step, and that is used for the further structure representation and data retrieval. Our work, as an important component of applying mobile computing research in education, is proved effective and promising.





# Automatic reading of handwritten chemical formulas from a structural representation of the image

## Abstract:

This paper presents a new strategy for localization and recognition of graphical entities in handwritten chemical formulas. Our system includes a first phase of global perception of the document followed by a phase of incremental extraction of the graphical entities. The phase of global perception constructs a structural representation of the drawing and provides a precise description of all the shapes present in the initial image. Thereafter this representation constitutes the main resource that will be used by different processes achieving the interpretation of the drawing. The knowledge extracted from the representation (a structural graph) is used instead of the bitmap image material to drive the interpretation process.


# A study of on-line handwritten chemical expressions recognition

## Abstract:
In this paper, we study the major modules of on-line handwritten chemical expressions recognition. We propose a novel two-level algorithm to recognize expressions. In the first level, structural information is used to distinguish different parts and recognize substances. Then the algorithm segments expressions fatherly and recognizes isolated symbols. To meet the demand of actual applications, the paper also designs an XML-based system to help users save, modify and search the recognition result. The experiment shows that the presented algorithm is reliable.


# Recognition of on-line handwritten chemical expressions

## Abstract:

In this paper, we study the major modules of on-line handwritten chemical expressions recognition. We propose a novel algorithm that combines two separate methods to segment expressions, one of which is based on structural information and the other on partial recognition. The algorithm improves the traditional algorithm at the stage of recognition, which consists of a substance recognizer and a character recognizer. To meet the demand of actual applications, the paper also designs a standard feature set to deal with the related issues and presents a flexible process of human-computer interaction to help users modify the recognition result. The experimental results show that the presented algorithm is reliable.


# Online chemical symbol recognition for handwritten chemical expression recognition

## Abstract:

With the growing popularity of pen-based and touch-based devices such as Apple's iPad and Samsung's Galaxy Tablet, handwriting has become an important input method. Although handwriting recognition for text contents and mathematical formulae are well-supported in these devices, recognizing handwritten chemical expressions is still very challenging due to its complex spatial structure. In this research, we focus on chemical symbol recognition which is essential for accurate handwritten chemical expression recognition. In particular, we propose an online hybrid Support Vector Machine - Elastic Matching (SVM-EM) approach for handwritten chemical symbol recognition. Based on the proposed chemical symbol recognition approach and an online structural analysis, we have implemented an online handwritten chemical expression recognition system on Apple's iOS platform. In this paper, we present our proposed SVM-EM approach for handwritten chemical symbol recognition and evaluate it with several users to verify its promising performance as a real application.





# An End-to-End Trainable System for Offline Handwritten Chemical Formulae Recognition

## Abstract:

In this paper, we propose an end-to-end trainable system for recognizing handwritten chemical formulae. This system recognize once a time a chemical formula, instead of one chemical symbol or a whole chemical equation, which is in line with people's writing habits, at the same time could help to develop methods for the complicated chemical equations recognition. The proposed system adopts the CNN+RNN+CTC framework, which is one of state of the art methods in imagebased sequence labelling tasks. We extend the capability of the CNN+RNN+CTC framework to interpret 2D spatial relationships (such as 'subscript' existing in chemical formula) by introducing additional labels to represent them. The system evaluated on a self-collected data set of 12,224 samples, achieves the recognition rate of 94.98% at the chemical formula level.


# Handwritten Chemical Formulas Classification Model Using Deep Transfer Convolutional Neural Networks

## Abstract:

With the spread of the COVID19 pandemic, blended learning has become one of the most used methods in educational organizations such as universities, community colleges, and schools. In blended learning, the students' practical activities are done in more than one way, including simulation software and the place of study. For chemical experiment programs, the classification of handwritten chemical formulas plays an important role in determining the simulation software's efficiency. Accordingly, in this study, we propose a model for handwritten chemical formula classification. First, this paper describes a handwritten chemical formulas dataset that contains eight classes (HCFD8). Second, convolutional neural networks (CNNs) with pre-trained weights are used as a deep feature extractor to extract features from the images. Third, due to limited training images per class, the proposed model uses data augmentation techniques to expand the training images. Then, an enhanced multilayer perceptron (EMLP) strategy is used to classify the image. Finally, we provide a performance analysis of typical deep learning approaches on HCFD8, which shows that the proposed model performs good accuracy results.



# The Understanding and Structure Analyzing for Online Handwritten Chemical Formulas

## Abstract:

In this paper, we propose a novel approach for understanding and analyzing the online handwritten chemical formulas. With the structural characteristics, semantic rules, and more importantly grammatical rules, the analyzing process is divided into 3 levels: formula level, molecule level, and text level. A formal description of the chemical formula based-on the grammatical rules is summed up and applied to the analyzing process which generates grammar spanning graphs from the analyzed result step-by-step, and that is used for the further structure representation and data retrieval. Our work, as an important component of applying mobile computing research in education, is proved effective and promising.




# Recognition of on-line handwritten chemical expressions

## Abstract:

In this paper, we study the major modules of on-line handwritten chemical expressions recognition. We propose a novel algorithm that combines two separate methods to segment expressions, one of which is based on structural information and the other on partial recognition. The algorithm improves the traditional algorithm at the stage of recognition, which consists of a substance recognizer and a character recognizer. To meet the demand of actual applications, the paper also designs a standard feature set to deal with the related issues and presents a flexible process of human-computer interaction to help users modify the recognition result. The experimental results show that the presented algorithm is reliable.


# The Understanding and Structure Analyzing for Online Handwritten Chemical Formulas

## Abstract:

In this paper, we propose a novel approach for understanding and analyzing the online handwritten chemical formulas. With the structural characteristics, semantic rules, and more importantly grammatical rules, the analyzing process is divided into 3 levels: formula level, molecule level, and text level. A formal description of the chemical formula based-on the grammatical rules is summed up and applied to the analyzing process which generates grammar spanning graphs from the analyzed result step-by-step, and that is used for the further structure representation and data retrieval. Our work, as an important component of applying mobile computing research in education, is proved effective and promising.


# A Multi-level Synthesis Strategy for Online Handwritten Chemical Equation Recognition

## Abstract

Handwritten chemical equation recognition is an appealing task, but its development is hampered by the lack of publicly available datasets. To this end, we propose a multi-level synthesis strategy to synthesize the corresponding handwritten equations from LaTeX expressions and regard the chemical equation recognition as an image-to-markup task. In particular, our approach first decomposes the LaTeX expression into a symbol layout tree (SLT) and obtains different multi-level components in stages by traversing the SLT. Then, online isolated symbols are placed in appropriate locations consistent with handwritten habits through a baseline-based layout strategy. Furthermore, expression patterns are enhanced at the local, component, and global levels to increase the diversity of synthesized data. It is worth noting that our synthesis strategy is theoretically applicable to any LaTeX-based expression. We also collected a real dataset containing 1595 handwritten chemical equations, and the experimental results confirm that our proposed method can effectively improve the performance of handwritten chemical equation recognition systems. The dataset we generated will be released.


# Handwritten Chemical Equations Recognition Based on Lightweight Networks


## Abstract

Handwritten chemical equations recognition is one of the important research directions of optical character recognition (OCR) and text recognition technology, which is widely used in life. Although the mainstream deep learning text recognition model can get good recognition results, the number of parameters of the model is too large to be carried on some portable devices. We develop a new lightweight network model (LCRNN) based on the CRNN model for handwritten chemical equations recognition. Firstly, in the convolutional layer of the LCRNN model, we propose a new MobileNetV3 (MobileNetV3M) to reduce number of the model parameters. The MobileNetV3M changed the original down-sampling method to max-pooling, so it can extract more critical information. Secondly, we use the BiGRU model in the recurrent layer. Finally, a new chemical equations encoding method is proposed, which can change the two-dimensional chemical equation into one-dimensional chemical equation encoding, so as to facilitate handwritten chemical equations recognition. The experiments demonstrate that the character precision of the LCRNN model is 2.1% lower than the CRNN model, but the number of parameters is significantly reduced.



# B. Handwritten Mathematical Expression Recognition (closest cousin)


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





# C. Error detection/localization


# Convolutional Neural Network Model for Syntax Error Detection in Language Learning Environments

## Abstract:

Existing models have difficulties in identifying complicated grammatical patterns and generalizing to various types of learner inputs, which is a significant obstacle for the improvement of computer-assisted language learning. Automatic syntax mistake detection is essential for this improvement. This research presents GED-HCA, which stands for "Grammatical Error Detection with Hierarchical Convolutional Attention"a novel CNN-based model that combines multiple change filters with attention mechanisms. To capture local and universal syntax, the model processes the input text through parallel writing and word-state embeddings. By using shallow convolutions, the model can capture localized syntax, and by utilizing deep convolutional branching, it can generalize across more extensive language forms. Writing patterns and word-state data are both captured simultaneously by the GED-HCA algorithm, which may assist it in identifying regions of student-generated text that are prone to include mistakes. The GED-HCA gets an F1 score of 87.3% by preserving its efficiency for real-time feedback. This score is higher than the baselines based on traditional CRF, BiLSTM, and Transformer on the FCE dataset by a margin of up to 4.1% compared to the baselines. These findings suggest that it is suitable for use with AI-driven grammar learning systems that prioritize precision and clarity.




# A Study on Handwritten Text Recognition and Post-OCR Error Correction Techniques

## Abstract:

Optical Character Recognition (OCR) of handwritten Telugu text remains a challenging task due to complex characters in the Telugu script and variable handwriting styles. Traditional OCR systems that use handcrafted features have shown limited performance on such data. Deep learning methods outperform traditional OCR methods because they learn patterns directly from images instead of depending on fixed rules. These methods also produce errors due to the visual similarity between the intra-class characters, variations in handwriting styles, and image quality. The introduction of post-OCR error correction techniques helped to eliminate these issues. In this post-OCR approach, the text which contains errors is generated by deep learning–based OCR models, is given as input to a post-OCR model that processes and corrects the incorrect text to produce a final corrected output. This survey focuses on OCR and post-OCR error correction methods and discusses their evaluated performance. The study is mainly towards Indic languages, and it shows that post-OCR models help improve performance.


# Neural Machine Translation with BERT for Post-OCR Error Detection and Correction

## Abstract

The quality of OCR has a direct impact on information access, and an indirect impact on the performance of natural language processing applications, making fine-grained (e.g., semantic) information access even harder. This work proposes a novel post-OCR approach based on a contextual language model and neural machine translation, aiming to improve the quality of OCRed text by detecting and rectifying erroneous tokens. This new technique obtains results comparable to the best-performing approaches on English datasets of the competition on post-OCR text correction in ICDAR 2017/2019.



# OCR Error Correction for Unconstrained Vietnamese Handwritten Text

## Abstract

Post-processing is an essential step in detecting and correcting errors in OCR-generated texts. In this paper, we present an automatic OCR post-processing model which comprises both error detection and error correction phases for OCR output texts of unconstrained Vietnamese handwriting. We propose a hybrid approach of generating and scoring correction candidates for both non-syllable and real-syllable errors based on the linguistic features as well as the error characteristics of OCR outputs. We evaluate our proposed model on a Vietnamese benchmark database at the line level. The experimental results show that our model achieves 4.17% of character error rate (CER) and 9.82% of word error rate (WER), which helps improve both CER and WER of an attention-based encoder-decoder approach by 0.5% and 3.5% respectively on the VNOnDB-Line dataset of the Vietnamese online handwritten text recognition competition (VOHTR2018). These results outperform those obtained by various recognition systems in the VOHTR2018 competition.



# An Efficient Unsupervised Approach for OCR Error Correction of Vietnamese OCR Text

## Abstract:

Different types of OCR errors often occur in OCR texts due to the low quality of scanned document images or limitations in OCR software. In this paper, we propose a novel unsupervised approach for OCR error correction. Correction candidates for OCR errors are generated and explored in their neighborhoods using correction character edits controlled by an adapted hill-climbing algorithm. Correction characters are extracted from only original ground truth texts, which do not depend on OCR texts in training data. A weighted objective function used to score and rank correction candidates is heuristically tested to find optimal weight combinations. The proposed model is evaluated on an OCR text dataset originating from the Vietnamese handwritten database in the ICFHR 2018 Vietnamese online handwritten text recognition competition. The proposed model is also verified concerning its stability and complexity. The experimental results show that our model achieves competitive performance compared to the other models in the ICFHR 2018 competition.







# Automated Grading of Handwritten Mathematics Using Vision-Capable LLMs

## Abstract

Automated grading systems have enabled scalable assessment for many response types, but handwritten mathematics remains a barrier due to the complexity of multi-step solutions. Vision-capable large language models (LLMs) offer new opportunities here, yet their reliability in authentic instructional settings remains poorly understood. We present an empirical evaluation of an LLM-based grader for handwritten mathematical work using instructor-defined rubrics. Extending a prior pipeline for typed responses, we integrate transcription and rubric-based evaluation of photographic submissions within a single LLM call, evaluating on student work from two university STEM courses. Comparing AI grading decisions against human-assigned ground truth at the rubric-item level, we observe high overall accuracy, with most errors -- 87\% in the best model -- attributable to transcription failures rather than rubric misapplication. We categorize common error modes, including image quality issues, hallucinated content, and incorrect handling of equivalent expressions. These findings highlight both the promise and limitations of LLM-based grading for handwritten mathematics, providing guidance for system design, prompt refinement, and deployment in educational settings.





# D. Chemical Structure Recognition 




# MolScribe: Robust Molecular Structure Recognition with Image-to-Graph Generation

## Abstract

Molecular structure recognition is the task of translating a molecular image into its graph structure. Significant variation in drawing styles and conventions exhibited in chemical literature poses a significant challenge for automating this task. In this paper, we propose MolScribe, a novel image-to-graph generation model that explicitly predicts atoms and bonds, along with their geometric layouts, to construct the molecular structure. Our model flexibly incorporates symbolic chemistry constraints to recognize chirality and expand abbreviated structures. We further develop data augmentation strategies to enhance the model robustness against domain shifts. In experiments on both synthetic and realistic molecular images, MolScribe significantly outperforms previous models, achieving 76–93% accuracy on public benchmarks. Chemists can also easily verify MolScribe’s prediction, informed by its confidence estimation and atom-level alignment with the input image. MolScribe is publicly available through Python and web interfaces:








# Image-to-Graph Transformers for Chemical Structure Recognition

## Abstract:

For several decades, chemical knowledge has been published in written text, and there have been many attempts to make it accessible, for example, by transforming such natural language text to a structured format. Although the discovered chemical itself commonly represented in an image is the most important part, the correct recognition of the molecular structure from the image in literature still remains a hard problem since they are often abbreviated to reduce the complexity and drawn in many different styles. In this paper, we present a deep learning model to extract molecular structures from images. The proposed model is designed to transform the molecular image directly into the corresponding graph, which makes it capable of handling non-atomic symbols for abbreviations. Also, by end-to-end learning approach it can fully utilize many open image-molecule pair data from various sources, and hence it is more robust to image style variation than other tools. The experimental results show that the proposed model outperforms the existing models with 17.1 % and 12.8 % relative improvement for well-known benchmark datasets and large molecular images that we collected from literature, respectively.

# Performance of chemical structure string representations for chemical image recognition using transformers


## Abstract

The use of molecular string representations for deep learning in chemistry has been steadily increasing in recent years. The complexity of existing string representations, and the difficulty in creating meaningful tokens from them, lead to the development of new string representations for chemical structures. In this study, the translation of chemical structure depictions in the form of bitmap images to corresponding molecular string representations was examined. An analysis of the recently developed DeepSMILES and SELFIES representations in comparison with the most commonly used SMILES representation is presented where the ability to translate image features into string representations with transformer models was specifically tested. The SMILES representation exhibits the best overall performance whereas SELFIES guarantee valid chemical structures. DeepSMILES perform in between SMILES and SELFIES, InChIs are not appropriate for the learning task. All investigations were performed using publicly available datasets and the code used to train and evaluate the models has been made available to the public.



# MolNexTR: a generalized deep learning model for molecular image recognition

## Abstract

In the field of chemical structure recognition, the task of converting molecular images into machine-readable data formats such as SMILES string stands as a significant challenge, primarily due to the varied drawing styles and conventions prevalent in chemical literature. To bridge this gap, we proposed MolNexTR, a novel image-to-graph deep learning model that collaborates to fuse the strengths of ConvNext, a powerful Convolutional Neural Network variant, and Vision-TRansformer. This integration facilitates a more detailed extraction of both local and global features from molecular images. MolNexTR can predict atoms and bonds simultaneously and understand their layout rules. It also excels at flexibly integrating symbolic chemistry principles to discern chirality and decipher abbreviated structures. We further incorporate a series of advanced algorithms, including an improved data augmentation module, an image contamination module, and a post-processing module for getting the final SMILES output. These modules cooperate to enhance the model’s robustness to diverse styles of molecular images found in real literature. In our test sets, MolNexTR has demonstrated superior performance, achieving an accuracy rate of 81–97%, marking a significant advancement in the domain of molecular structure recognition.

# Review of techniques and models used in optical chemical structure recognition in images and scanned documents

## Abstract

Extraction of chemical formulas from images was not in the top priority of Computer Vision tasks for a while. The complexity both on the input and prediction sides has made this task challenging for the conventional Artificial Intelligence and Machine Learning problems. A binary input image which might seem trivial for convolutional analysis was not easy to classify, since the provided sample was not representative of the given molecule: to describe the same formula, a variety of graphical representations which do not resemble each other can be used. Considering the variety of molecules, the problem shifted from classification to that of formula generation, which makes Natural Language Processing (NLP) a good candidate for an effective solution. This paper describes the evolution of approaches from rule-based structure analyses to complex statistical models, and compares the efficiency of models and methodologies used in the recent years. Although the latest achievements deliver ideal results on particular datasets, the authors mention possible problems for various scenarios and provide suggestions for further development.



# Deep Learning based Hand-Drawn Molecular Structure Recognition and 3D Visualisation using Augmented Reality

## Abstract:

Due to both false-positive structure identification and flaws in the predicted structures, chemical structure identification from documents remains a complex challenge. Current techniques rely on customized rules and subroutines that, although usually effective, recognition rates are insufficient and systematic improvement is difficult at certain times. Especially when it comes to the identification of hand-drawn Lewis Structures of molecules, most of these existing methodologies fail. Therefore, through this research, we present a system to identify a camera-captured, hand-drawn Lewis structure of a molecule using Machine Learning and Deep Learning concepts. Due to less availability of hand-drawn Lewis structures, we had to make our own dataset and therefore the project was limited to 15 different hydro carbons. Moreover, we provide the users with a mobile application that can visualize the identified molecule in a 3-D space using Augmented Reality. Our machine learning model details are available on the Github (https://github.com/MZJGroup/MoleAR)

# MolParser: End-to-end Visual Recognition of Molecule Structures in the Wild

**Abstract**  
  

In recent decades, chemistry publications and patents have increased rapidly. A significant portion of key information is embedded in molecular structure figures, complicating large-scale literature searches and limiting the application of large language models in fields such as biology, chemistry, and pharmaceuticals. The automatic extraction of precise chemical structures is of critical importance. However, the presence of numerous Markush structures in real-world documents, along with variations in molecular image quality, drawing styles, and noise, significantly limits the performance of existing optical chemical structure recognition (OCSR) methods. We present MolParser, a novel end-to-end OCSR method that efficiently and accurately recognizes chemical structures from real-world documents, including difficult Markush structure. We use a extended SMILES encoding rule to annotate our training dataset. Under this rule, we build MolParser-7M, the largest annotated molecular image dataset to our knowledge. While utilizing a large amount of synthetic data, we employed active learning methods to incorporate substantial in-the-wild data, specifically samples cropped from real patents and scientific literature, into the training process. We trained an end-to-end molecular image captioning model, MolParser, using a curriculum learning approach. MolParser significantly outperforms classical and learning-based methods across most scenarios, with potential for broader downstream applications. The dataset is publicly available in huggingface.



# MPOCSR: optical chemical structure recognition based on multi-path Vision Transformer

## Abstract

Optical chemical structure recognition (OCSR) is a fundamental and crucial task in the field of chemistry, which aims at transforming intricate chemical structure images into machine-readable formats. Current deep learning-based OCSR methods typically use image feature extractors to extract visual features and employ encoder-decoder architectures for chemical structure recognition. However, the performance of these methods is limited by their image feature extractors and the class imbalance of elements in chemical structure representation. This paper proposes MPOCSR (multi-path optical chemical structure recognition), which introduces the multi-path Vision Transformer (MPViT) and the class-balanced (CB) loss function to address these two challenges. MPOCSR uses MPViT as an image feature extractor, combining the advantages of convolutional neural networks and Vision Transformers. This strategy enables the provision of richer visual information for subsequent decoding processes. Furthermore, MPOCSR incorporates CB loss function to rebalance the loss weights among different categories. For training and validation of our method, we constructed a dataset that includes both Markush and non-Markush structures. Experimental results show that MPOCSR achieves an accuracy of 90.95% on the test set, surpassing other existing methods.



# A Large-Scale Database for Chemical Structure Recognition and Preliminary Evaluation

## Abstract:

Chemical structure recognition (CSR), transforming chemical structure images into formulas in character strings (such as SMILES), is a challenging problem due to the complex 2D structures and relationships. For this research, there is not a database of sufficient scale and diversity for model design and fair evaluation. In this paper, we present a large-scale chemical structure database named CASIA-CSDB, containing 480,668 samples (images corresponding to SMILES strings). To construct the database, we select chemical structures from the ChEMBL, a well-known bioactive molecules database, and use the RDKit tool to generate images according to the chemical format SMILES strings. The selected structures represent the major types of chemical compounds covering eight weight partitions. We also select a subset of 97,309 samples of the database to form the Mini-CASIA-CSDB database. To provide a benchmark, we evaluate three state-of-the-art image-to-markup recognition methods on the database. The results demonstrate the challenge of the database. The database with its annotation is available at http://www.nlpr.ia.ac.cn/databases/CASIA-CSDB/index.html.


# MolSight: Optical Chemical Structure Recognition with SMILES Pretraining, Multi-Granularity Learning and Reinforcement Learning

## Abstract

Optical Chemical Structure Recognition (OCSR) plays a pivotal role in modern chemical informatics, enabling the automated conversion of chemical structure images from scientific literature, patents, and educational materials into machine-readable molecular representations. This capability is essential for large-scale chemical data mining, drug discovery pipelines, and Large Language Model (LLM) applications in related domains. However, existing OCSR systems face significant challenges in accurately recognizing stereochemical information due to the subtle visual cues that distinguish stereoisomers, such as wedge and dash bonds, ring conformations, and spatial arrangements. To address these challenges, we propose MolSight, a comprehensive learning framework for OCSR that employs a three-stage training paradigm. In the first stage, we conduct pre-training on large-scale but noisy datasets to endow the model with fundamental perception capabilities for chemical structure images. In the second stage, we perform multi-granularity fine-tuning using datasets with richer supervisory signals, systematically exploring how auxiliary tasks—specifically chemical bond classification and atom localization—contribute to molecular formula recognition. Finally, we employ reinforcement learning for post-training optimization and introduce a novel stereochemical structure dataset. Remarkably, we find that even with MolSight's relatively compact parameter size, the Group Relative Policy Optimization (GRPO) algorithm can further enhance the model's performance on stereomolecular. Through extensive experiments across diverse datasets, our results demonstrate that MolSight achieves state-of-the-art performance in (stereo)chemical optical structure recognition.


# Comparing software tools for optical chemical structure recognition

## Abstract

The extraction of chemical information from images, also known as Optical Chemical Structure Recognition (OCSR) has recently gained new attention. This new interest is ignited by various machine learning methods introduced over the last years and the new possibilities to train image models for specific tasks such as OCSR. In the present paper, we have compared 8 open access OCSR methods (DECIMER, ReactionDataExtractor, MolScribe, RxnScribe, SwinOCSR, OCMR, MolVec, and OSRA) using an independent test set of images from patents and patent applications as this is an application area of general interest – precision and recall are highly desired by those who are analysing the intellectual property of chemistry patents. As a result, the used methods have shown different strengths when predicting structures from different images containing different modalities and chemistry categories. These existing methodologies for image extraction overall remain unsatisfactory, indicating a need for further advancements in the field. Further, we have created a machine learning image classifier, classifying images into one out of four image categories and applying the best performing OCSR method for each category. This classifier, the image comparator tools, and datasets have been made available to the public as open access tools.

# Advancements in hand-drawn chemical structure recognition through an enhanced DECIMER architecture

Accurate recognition of hand-drawn chemical structures is crucial for digitising hand-written chemical information in traditional laboratory notebooks or facilitating stylus-based structure entry on tablets or smartphones. However, the inherent variability in hand-drawn structures poses challenges for existing Optical Chemical Structure Recognition (OCSR) software. To address this, we present an enhanced Deep lEarning for Chemical ImagE Recognition (DECIMER) architecture that leverages a combination of Convolutional Neural Networks (CNNs) and Transformers to improve the recognition of hand-drawn chemical structures. The model incorporates an EfficientNetV2 CNN encoder that extracts features from hand-drawn images, followed by a Transformer decoder that converts the extracted features into Simplified Molecular Input Line Entry System (SMILES) strings. Our models were trained using synthetic hand-drawn images generated by RanDepict, a tool for depicting chemical structures with different style elements. A benchmark was performed using a real-world dataset of hand-drawn chemical structures to evaluate the model's performance. The results indicate that our improved DECIMER architecture exhibits a significantly enhanced recognition accuracy compared to other approaches.



# A Benchmark Evaluation of Chemical Structure Extraction from Patents: Insights and Challenges in Chemical Structure Recognition

## Abstract
Early warning systems (EWSs) are currently being developed by various authorities aiming at identifying potentially hazardous chemicals before they become a threat to the environment and human health. In this context, patents provide an excellent data source for exploring novel chemistry or the use of chemicals in materials and products. However, analysis of patents is challenging, including unraveling molecular structures presented as graphics depicting various elements, functional groups, and molecular bonds. Our study aims to improve EWS using automated artificial intelligence-based molecular structure recognition methods for encoding these for further hazard analysis. Current structure extraction tools are primarily trained on chemical structures collected from publicly available data sets, and the application of these tools to patent-specific chemical data has received little attention. This paper presents a field study utilizing the three tools Decimer, Molscribe, and Mathpix and assesses their performance in recognizing chemical structures in patents. Two data sets were compiled and curated including (1) diverse organic chemicals and (2) per- and polyfluoroalkyl substances (PFAS). It was revealed that these tools perform well on simpler molecular structures, whereas they struggle with more complex structural features, including repetitive units, cross-bonding, and Markush structures. Furthermore, it was discovered that these tools are extremely sensitive to image artifacts such as noise from lines and dots or distortions. Overcoming these challenges will be critical before implementation in automated EWS and thereby enable screening of patents for rapid and effective identification of potentially hazardous emerging chemicals.

# MolMiner: You Only Look Once for Chemical Structure Recognition

## Abstract
Molecular structures are commonly depicted in 2D printed forms in scientific documents such as journal papers and patents. However, these 2D depictions are not machine readable. Due to a backlog of decades and an increasing amount of printed literatures, there is a high demand for translating printed depictions into machine-readable formats, which is known as Optical Chemical Structure Recognition (OCSR). Most OCSR systems developed over the last three decades use a rule-based approach, which vectorizes the depiction based on the interpretation of vectors and nodes as bonds and atoms. Here, we present a practical software called MolMiner, which is primarily built using deep neural networks originally developed for semantic segmentation and object detection to recognize atom and bond elements from documents. These recognized elements can be easily connected as a molecular graph with a distance-based construction algorithm. MolMiner gave state-of-the-art performance on four benchmark data sets and a self-collected external data set from scientific papers. As MolMiner performed similarly well in real-world OCSR tasks with a user-friendly interface, it is a useful and valuable tool for daily applications. The free download links of Mac and Windows versions are available at [https://github.com/iipharma/pharmamind-molminer](https://github.com/iipharma/pharmamind-molminer).

# MARCUS: molecular annotation and recognition for curating unravelled structures

## Abstract

The exponential growth of chemical literature necessitates the development of automated tools for extracting and curating molecular information from unstructured scientific publications into open-access chemical databases. Current optical chemical structure recognition (OCSR) and named entity recognition solutions operate in isolation, which limits their scalability for comprehensive literature curation. Here we present MARCUS (Molecular Annotation and Recognition for Curating Unravelled Structures), a tool designed for natural product literature curation that integrates COCONUT-aware schema mapping, CIP-based stereochemical validation, and human-in-the-loop structure refinement. This integrated web-based platform combines automated text annotation, multi-engine OCSR, and direct submission capabilities to the COCONUT database. MARCUS employs a fine-tuned GPT-4 model to extract chemical entities and utilises a Human-in-the-loop ensemble approach integrating DECIMER, MolNexTR, and MolScribe for structure recognition. The platform aims to streamline the data extraction workflow from PDF upload to database submission, significantly reducing curation time. MARCUS bridges the gap between unstructured chemical literature and machine-actionable databases, enabling FAIR data principles and facilitating AI-driven chemical discovery. Through open-source code, accessible models, and comprehensive documentation, the web application enhances accessibility and promotes community-driven development. This approach facilitates unrestricted use and encourages the collaborative advancement of automated chemical literature curation tools.





# E. Bangla handwriting-OCR dataset gap-check




# Handwritten Bengali Alphabets, Compound Characters and Numerals Recognition Using CNN-based Approach

## Abstract

 Accurately classifying user-independent handwritten Bengali characters and numerals presents a formidable challenge in their recognition. This task becomes more complicated due to the inclusion of numerous complex-shaped compound characters and the fact that different authors employ diverse writing styles. Researchers have recently conducted significant researches using individual approaches to recognize handwritten Bangla digits, alphabets, and slightly compound characters. To address this, we propose a straightforward and lightweight convolutional neural network (CNN) framework to accurately categorize handwritten Bangla simple characters, compound characters, and numerals. The suggested approach exhibits outperformance in terms of performance when compared too many previously developed procedures, with faster execution times and requiring fewer epochs. Furthermore, this model applies to more than three datasets. Our proposed CNN-based model has achieved impressive validation accuracies on three datasets. Specifically, for the BanglaLekha isolated dataset, which includes 84-character classes, the validation accuracy was 92.48%. On the Ekush dataset, which includes 60-character classes, the model achieved a validation accuracy of 97.24%, while on the customized dataset, which includes 50- character classes, the validation accuracy was 97.03%. Our model has demonstrated high accuracy and outperformed several prominent existing frameworks.


# BnGraphemizer: A Grapheme-based Tokenizer for Bengali Handwritten Text Recognition

## Abstract:

Bengali Handwritten Text Recognition (HTR) is a challenging task due to the text's cursive disposition and significant variations in the graphemic unit, the smallest written unit in alphasyllabary languages. These graphemic units, or simply graphemes, may consist of multiple characters and diacritics, and the order of characters or diacritics between textual and visual representations is only sometimes preserved. Moreover, Bengali conjunct characters, a subset of the graphemes, often have unique visual representations vastly different from the characters they comprise. Because of these inherent characteristics, a character-based tokenizer fails to tokenize the label text appropriately for BHTR in a supervised setting, making it challenging to adapt the existing sequence-to-sequence frameworks often used for Handwritten Text Recog-nition (HTR). To address this, this paper proposes a trie- based text tokenizer (called BnGraphemizer) that allows one to tokenize text into a set of graphemes instead of characters. Experimental investigations show that the BnGraphemizer-based BHTR system performs better regarding higher Word Recognition Rate (WRR) than its character-based counterpart in two of three Bengali handwritten datasets.


# A CNN Framework for Real-Time and Edge Deployment with High Accuracy for Lightweight Deep Learning for Bengali OCR

## Abstract

The Bengali script, like other Indic scripts, has a large character set, complex conjunct characters, and varying handwriting styles, making optical character recognition (OCR) a complex task. Although convolutional neural networks (CNNs), ensemble techniques, and CNN-Transformer models have shown high accuracy, their high computational complexity and large input size make them unsuitable for mobile and embedded systems. To make the processing cost-effective and improve the accuracy of handwritten Bengali character recognition, this paper proposes a light-weight CNN with optimized filters and a 40 × 40 input size. Compared to the existing deep learning and hybrid approaches, the proposed approach has shown 98.29\% top-1 accuracy on a 50-class dataset with 12,000 training samples and 2,997 testing samples, reducing the parameter size and computational complexity. A brief literature review is also presented to discuss the evolution of real-time and large-scale Bengali OCR systems and the challenges involved in compound character recognition, efficiency, and system-level validation.


# An Automated Approach to Recognize Handwritten Text

## Abstract:

Optical Character Recognition for handwritten text represents a fundamental challenge in computer vision and natural language processing, particularly for morphologically complex scripts like Bangla. Bangla handwritten text recognition remains significantly challenging due to the script's intricate structure comprising 39 consonants, 11 vowels, 10 modifiers, and over 300 compound characters that exhibit cursive connectivity and complex spatial relationships. Traditional character-level recognition approaches suffer from segmentation difficulties and error propagation through multi-stage pipelines, while existing deep learning solutions have not adequately addressed the end-to-end processing requirements for practical deployment. This paper presents an enhanced two-stage pipeline that combines word segmentation with transformer-based optical character recognition, employing ResNet-18 feature extraction coupled with a transformer decoder specifically optimized for Bangla script characteristics. Experimental evaluation on the BanglaWriting dataset containing 21,234 words from 260 individuals demonstrates competitive performance with Character Error Rate (CER) of 13.16 % and Word Error Rate (WER) of 31.05 %, while the segmentation for word detection. The proposed system eliminates manual preprocessing requirements and achieves processing efficiency of 0.5 seconds per word, establishing a foundation for practical deployment in document digitization applications across educational and administrative sectors.

# LILA-BOTI : Leveraging Isolated Letter Accumulations By Ordering Teacher Insights for Bangla Handwriting Recognition


## Abstract:

Word-level handwritten optical character recognition (OCR) remains a challenge for morphologically rich languages like Bangla. The complexity arises from the existence of a large number of alphabets, the presence of several diacritic forms, and the appearance of complex conjuncts. The difficulty is exacerbated by the fact that some graphemes occur infrequently but remain indispensable, so addressing the class imbalance is required for satisfactory results. This paper addresses this issue by introducing two knowledge distillation methods: Leveraging Isolated Letter Accumulations By Ordering Teacher Insights (LILA-BOTI) and Super Teacher LILA-BOTI. In both cases, a Convolutional Recurrent Neural Network (CRNN) student model is trained with the dark knowledge gained from a printed isolated character recognition teacher model. We conducted inter-dataset testing on BN-HTRd and BanglaWriting as our evaluation protocol, thus setting up a challenging problem where the results would better reflect the performance on unseen data. Our evaluations achieved up to a 3.5% increase in the F1-Macro score for the minor classes and up to 4.5% increase in our overall word recognition rate when compared with the base model (No KD) and conventional KD.


# BanGaNet: A Lightweight Deep Learning Framework for Bangla Handwritten Text Recognition


## Abstract:

Bangla Handwritten Text Recognition (BHTR) presents a significant challenge in Optical Character Recognition (OCR) owing to the script's complex structure, extensive set of compound characters, and high variability in handwriting styles. Addressing this issue is critical for applications including document digitalization, postal automation, and mobile text input in Bangla, the world's seventh most spoken language. Existing deep learning algorithms, such as CNN, CRNN, and Gated-CNN based models, achieve high accuracy but are computationally expensive and inappropriate for resource-constrained devices. To address these limitations, we present BanGaNet, a lightweight end-to-end architecture that integrates gated CNN blocks, batch normalization, and stacked bidirectional LSTMs trained with Connectionist Temporal Classification (CTC) loss for alignmentfree sequence modeling. When tested on the BanglaWriting dataset, BanGaNet achieves state-of-the-art performance with 12.37% Character Error Rate and 34.16% Word Error Rate while requiring only 1.32M parameters. These contributions demonstrate BanGaNet's effectiveness and resource efficiency, with prospective applications in real-time mobile OCR, lowpower embedded devices, and large-scale Bangla document digitization.

# Handwritten Word Recognition using Deep Learning Approach: A Novel Way of Generating Handwritten Words

## Abstract:

A handwritten word recognition system comes with issues such as-lack of large and diverse datasets. It is necessary to resolve such issues since millions of official documents can be digitized by training deep learning models using a large and diverse dataset. Due to the lack of data availability, the trained model does not give the expected result. Thus, it has a high chance of showing poor results. This paper proposes a novel way of generating diverse handwritten word images using handwritten characters. The idea of our project is to train the BiLSTM-CTC architecture with generated synthetic handwritten words. The whole approach shows the process of generating two types of large and diverse handwritten word datasets: overlapped and non-overlapped. Since handwritten words also have issues like overlapping between two characters, we have tried to put it into our experimental part. We have also demonstrated the process of recognizing handwritten documents using the deep learning model. For the experiments, we have targeted the Bangla language, which lacks the handwritten word dataset, and can be followed for any language. Our approach is less complex and less costly than traditional GAN models. Finally, we have evaluated our model using Word Error Rate (WER), accuracy, f1-score, precision, and recall metrics. The model gives 39% WER score, 92% percent accuracy, and 92% percent f1 scores using non-overlapped data and 63% percent WER score, 83% percent accuracy, and 85% percent f1 scores using overlapped data.

title
ChemAssist-BD: A Primary Dataset and Deep Learning Framework for Handwritten Chemistry Formula Recognition and Error Localization

1. ChemAssist-BD (Altaf)
A. Handwritten chemical formula/equation recognition (core)
•	("chemical formula" OR "chemical equation") AND ("handwriting recognition" OR recognition OR OCR)
•	("handwritten" OR "handwriting") AND ("chemical structure" OR "chemical formula" OR "chemical notation") AND (recognition OR OCR OR "deep learning")
•	(chemistry OR chemical) AND ("answer script" OR "exam paper" OR "student handwriting") AND recognition
B. Handwritten Mathematical Expression Recognition (closest cousin)
•	(HMER OR "handwritten mathematical expression") AND recognition AND ("deep learning" OR CNN OR transformer)
•	("math OCR" OR "formula recognition" OR "equation recognition") AND (LaTeX OR symbol OR handwritten)
•	("sequence-to-sequence" OR encoder-decoder) AND ("math expression" OR formula) AND recognition
C. Error detection/localization
•	("error detection" OR "error localization") AND (OCR OR handwriting OR "handwritten text")
•	("automated grading" OR "automated assessment") AND (handwritten OR "answer script")
•	("mistake detection" OR "error identification") AND (student OR exam OR answer) AND ("deep learning" OR AI)
D. Chemical Structure Recognition (⚠️ check carefully)
•	("chemical structure recognition" OR "molecule recognition") AND image AND ("deep learning" OR CNN)
•	(DECIMER OR MolScribe OR OSRA) AND "structure recognition"
•	(SMILES OR "molecular formula") AND (image OR "optical recognition") AND extraction
E. Bangla handwriting-OCR dataset gap-check
•	(Bangla OR Bengali) AND ("handwriting recognition" OR OCR) AND dataset
•	(Bangla OR Bengali) AND (chemistry OR "scientific notation" OR STEM) AND dataset
•	(Bangla OR Bengali) AND ("answer script" OR "exam evaluation") AND AI
F. Subscript/superscript segmentation — ⚠️ Type 2 (method-inspiration, intentionally broad — handwriting/chemistry domain না থাকলেও segmentation technique-এর জন্য কাজে লাগবে)
•	(subscript OR superscript) AND (segmentation OR recognition) AND ("deep learning" OR CNN)
•	("symbol segmentation" OR "symbol recognition") AND (handwritten OR formula OR chemistry) (এই দ্বিতীয়টাতে anchor আছে, এটা Type 1)
G. Explainability/error visualization — ⚠️ Type 2 (method-inspiration, broad — grading/assessment-domain থেকে XAI-technique ধার করার জন্য)
•	("explainable AI" OR XAI OR "Grad-CAM") AND (grading OR assessment OR "error analysis")

---
Here are the abstracts of all the literature I've collected on this topic,
organized by sub-section. Please look at all of them carefully and help me
refine my research goals and title.

Tell me:
- what type of data I should collect, gather, or modify
- how I should conduct the research
- a final research title, clear goals, and a dataset description
- the baseline(s) I should aim to match or beat
