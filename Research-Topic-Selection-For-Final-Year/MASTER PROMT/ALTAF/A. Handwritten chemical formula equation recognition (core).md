
# Subtopic: Handwritten chemical formula/equation -recognition (core)



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


