
# Subtopic: Bangla handwriting-OCR dataset gap-check




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






