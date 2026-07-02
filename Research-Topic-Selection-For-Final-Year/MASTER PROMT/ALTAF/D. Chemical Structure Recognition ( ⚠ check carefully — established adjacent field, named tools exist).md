
# Subtopic: Chemical Structure Recognition 




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





