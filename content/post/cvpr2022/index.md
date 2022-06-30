---
title: CVPR 2022 papers on HCI/Visualization
subtitle: papers

# Summary for listings and search engines
summary: For a long time, computer vision and human-computer interaction communities have been collaborating in many fields, e.g., explainable AI, data annotation, etc. In this year's CVPR, we find many exciting papers addressing the HCI topics in the computer vision scenarios. 

# Link this post with a project
projects: []

# Date published
date: "2022-06-30T00:00:00Z"

# Date updated
lastmod: "2022-06-30T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- Guande Wu

tags:
- Academic
- HCI

categories:
- Conference
---

# The Collaboration between HCI and CV
For a long time, computer vision and human-computer interaction communities have been collaborating in many fields, e.g., explainable AI, data annotation, etc. In this year's CVPR, we find many exciting papers addressing the HCI topics in the computer vision scenarios. We group them into two categories, i.e., HCI helps CV and CV helps HCI.

# HCI Helps CV

## Explainable AI
### VL-InterpreT: An Interactive Visualization Tool for Interpreting Vision-Language Transformers
Breakthroughs in transformer-based models have revo- lutionized not only the NLP field, but also vision and mul- timodal systems. However, although visualization and in- terpretability tools have become available for NLP models, internal mechanisms of vision and multimodal transform- ers remain largely opaque. With the success of these trans- formers, it is increasingly critical to understand their inner workings, as unraveling these black-boxes will lead to more capable and trustworthy models. To contribute to this quest, we propose VL-InterpreT, which provides novel interactive visualizations for interpreting the attentions and hidden representations in multimodal transformers. VL-InterpreT is a task agnostic and integrated tool that (1) tracks a vari- ety of statistics in attention heads throughout all layers for both vision and language components, (2) visualizes cross- modal and intra-modal attentions through easily readable heatmaps, and (3) plots the hidden representations of vision and language tokens as they pass through the transformer layers. In this paper, we demonstrate the functionalities of VL-InterpreT through the analysis of KD-VLP, an end-to- end pretraining vision-language multimodal transformer- based model, in the tasks of Visual Commonsense Rea- soning (VCR) and WebQA, two visual question answering benchmarks. Furthermore, we also present a few interest- ing findings about multimodal transformer behaviors that were learned through our tool.

### Query and Attention Augmentation for Knowledge-Based Explainable Reasoning
[link](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Query_and_Attention_Augmentation_for_Knowledge-Based_Explainable_Reasoning_CVPR_2022_paper.pdf)
Explainable visual question answering (VQA) models have been developed with neural modules and query-based knowledge incorporation to answer knowledge-requiring questions. Yet, most reasoning methods cannot effectively generate queries or incorporate external knowledge during the reasoning process, which may lead to suboptimal re- sults. To bridge this research gap, we present Query and Attention Augmentation, a general approach that augments neural module networks to jointly reason about visual and external knowledge. To take both knowledge sources into account during reasoning, it parses the input question into a functional program with queries augmented through a novel reinforcement learning method, and jointly directs aug- mented attention to visual and external knowledge based on intermediate reasoning results. With extensive experi- ments on multiple VQA datasets, our method demonstrates significant performance, explainability, and generalizabil- ity over state-of-the-art models in answering questions re- quiring different extents of knowledge. Our source code is available at https://github.com/SuperJohnZhang/QAA.

## Data Annotation
### FocusCut: Diving into a Focus View in Interactive Segmentation
[link](https://openaccess.thecvf.com/content/CVPR2022/papers/Lin_FocusCut_Diving_Into_a_Focus_View_in_Interactive_Segmentation_CVPR_2022_paper.pdf)
Interactive image segmentation is an essential tool in pixel-level annotation and image editing. To obtain a high- precision binary segmentation mask, users tend to add in- teraction clicks around the object details, such as edges and holes, for efficient refinement. Current methods regard these repair clicks as the guidance to jointly determine the global prediction. However, the global view makes the model lose focus from later clicks, and is not in line with user inten- tions. In this paper, we dive into the view of clicks’ eyes to endow them with the decisive role in object details again. To verify the necessity of focus view, we design a simple yet effective pipeline, named FocusCut, which integrates the functions of object segmentation and local refinement. Af- ter obtaining the global prediction, it crops click-centered patches from the original image with adaptive scopes to re- fine the local predictions progressively. Without user per- ception and parameters increase, our method has achieved state-of-the-art results. Extensive experiments and visual- ized results demonstrate that FocusCut makes hyper-fine segmentation possible for interactive image segmentation.

## Human-in-the-loop ML
### Interactive Disentanglement: Learning Concepts by Interacting with their Prototype Representations
[link](https://arxiv.org/pdf/2112.02290.pdf)
Learning visual concepts from raw images without strong supervision is a challenging task. In this work, we show the advantages of prototype representations for un- derstanding and revising the latent space of neural concept learners. For this purpose, we introduce interactive Con- cept Swapping Networks (iCSNs), a novel framework for learning concept-grounded representations via weak super- vision and implicit prototype representations. iCSNs learn to bind conceptual information to specific prototype slots by swapping the latent representations of paired images. This semantically grounded and discrete latent space facilitates human understanding and human-machine interaction. We support this claim by conducting experiments on our novel data set “Elementary Concept Reasoning” (ECR), focusing on visual concepts shared by geometric objects.

### Interactive Segmentation and Visualization for Tiny Objects in Multi-megapixel Images
[link](https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Interactive_Segmentation_and_Visualization_for_Tiny_Objects_in_Multi-Megapixel_Images_CVPR_2022_paper.pdf)
We introduce an interactive image segmentation and vi- sualization framework for identifying, inspecting, and edit- ing tiny objects (just a few pixels wide) in large multi- megapixel high-dynamic-range (HDR) images. Detecting cosmic rays (CRs) in astronomical observations is a cum- bersome workflow that requires multiple tools, so we de- veloped an interactive toolkit that unifies model inference, HDR image visualization, segmentation mask inspection and editing into a single graphical user interface. The fea- ture set, initially designed for astronomical data, makes this work a useful research-supporting tool for human-in- the-loop tiny-object segmentation in scientific areas like biomedicine, materials science, remote sensing, etc., as well as computer vision. Our interface features mouse- controlled, synchronized, dual-window visualization of the image and the segmentation mask, a critical feature for lo- cating tiny objects in multi-megapixel images. The browser- based tool can be readily hosted on the web to provide multi-user access and GPU acceleration for any device. The toolkit can also be used as a high-precision annota- tion tool, or adapted as the frontend for an interactive ma- chine learning framework. Our open-source dataset, CR detection model, and visualization toolkit are available at https://github.com/cy-xu/cosmic-conn.

# CV helps HCI
## Intelligent Design/Layout
### iPLAN: Interactive and Procedural Layout Planning
[link](https://openaccess.thecvf.com/content/CVPR2022/papers/He_iPLAN_Interactive_and_Procedural_Layout_Planning_CVPR_2022_paper.pdf)
Layout design is ubiquitous in many applications, e.g. architecture/urban planning, etc, which involves a lengthy iterative design process. Recently, deep learning has been leveraged to automatically generate layouts via image gen- eration, showing a huge potential to free designers from la- borious routines. While automatic generation can greatly boost productivity, designer input is undoubtedly crucial. An ideal AI-aided design tool should automate repetitive routines, and meanwhile accept human guidance and pro- vide smart/proactive suggestions. However, the capabil- ity of involving humans into the loop has been largely ig- nored in existing methods which are mostly end-to-end ap- proaches. To this end, we propose a new human-in-the-loop generative model, iPLAN, which is capable of automati- cally generating layouts, but also interacting with designers throughout the whole procedure, enabling humans and AI to co-evolve a sketchy idea gradually into the final design. iPLAN is evaluated on diverse datasets and compared with existing methods. The results show that iPLAN has high fidelity in producing similar layouts to those from human designers, great flexibility in accepting designer inputs and providing design suggestions accordingly, and strong gen- eralizability when facing unseen design tasks and limited training data. 

## AR/VR
### Robust Egocentric Photo-realistic Facial Expression Transfer for Virtual Reality
[link](https://openaccess.thecvf.com/content/CVPR2022/papers/Jourabloo_Robust_Egocentric_Photo-Realistic_Facial_Expression_Transfer_for_Virtual_Reality_CVPR_2022_paper.pdf)
Social presence, the feeling of being there with a “real” person, will fuel the next generation of communication sys- tems driven by digital humans in virtual reality (VR). The best 3D video-realistic VR avatars that minimize the un- canny effect rely on person-specific (PS) models. However, these PS models are time-consuming to build and are typi- cally trained with limited data variability, which results in poor generalization and robustness. Major sources of vari- ability that affects the accuracy of facial expression transfer algorithms include using different VR headsets (e.g., cam- era configuration, slop of the headset), facial appearance changes over time (e.g., beard, make-up), and environmen- tal factors (e.g., lighting, backgrounds). This is a major drawback for the scalability of these models in VR. This paper makes progress in overcoming these limita- tions by proposing an end-to-end multi-identity architec- ture (MIA) trained with specialized augmentation strate- gies. MIA drives the shape component of the avatar from three cameras in the VR headset (two eyes, one mouth), in untrained subjects, using minimal personalized information (i.e., neutral 3D mesh shape). Similarly, if the PS texture decoder is available, MIA is able to drive the full avatar (shape+texture) robustly outperforming PS models in chal- lenging scenarios. Our key contribution to improve ro- bustness and generalization, is that our method implic- itly decouples, in an unsupervised manner, the facial ex- pression from nuisance factors (e.g., headset, environ- ment, facial appearance). We demonstrate the superior performance and robustness of the proposed method versus state-of-the-art PS approaches in a variety of experiments.

### Episodic Memory Question Answering
[link](https://openaccess.thecvf.com/content/CVPR2022/papers/Datta_Episodic_Memory_Question_Answering_CVPR_2022_paper.pdf)
Egocentric augmented reality devices such as wearable glasses passively capture visual data as a human wearer tours a home environment. We envision a scenario wherein the human communicates with an AI agent powering such a device by asking questions (e.g., “where did you last see my keys?”). In order to succeed at this task, the egocen- tric AI assistant must (1) construct semantically rich and efficient scene memories that encode spatio-temporal infor- mation about objects seen during the tour and (2) possess the ability to understand the question and ground its answer into the semantic memory representation. Towards that end, we introduce (1) a new task — Episodic Memory Question Answering (EMQA) wherein an egocentric AI assistant is provided with a video sequence (the tour) and a question as an input and is asked to localize its answer to the ques- tion within the tour, (2) a dataset of grounded questions de- signed to probe the agent’s spatio-temporal understanding of the tour, and (3) a model for the task that encodes the scene as an allocentric, top-down semantic feature map and grounds the question into the map to localize the answer. We show that our choice of episodic scene memory outperforms naive, off-the-shelf solutions for the task as well as a host of very competitive baselines and is robust to noise in depth, pose as well as camera jitter.

