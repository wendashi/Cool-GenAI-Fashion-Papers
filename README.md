# 🕶️ Cool-GenAI-Fashion-Papers

[![Cool](https://awesome.re/badge.svg)](https://awesome.re) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
 ![visitors](https://visitor-badge.laobi.icu/badge?page_id=wendashi/Cool-GenAI-Fashion-Papers) 

🧢🕶️🥼👖👟🧳 A curated list of cool resources about GenAI-Fashion, including 📝papers, 👀workshops, 🚀companies & products, ...

Feel free to send a PR or open an issue.


## Table Of Content

The structure of the category follows [fAshIon after fashion: A Report of AI in Fashion](https://arXiv.org/abs/2105.03050)

- [📝Papers](#papers)

| Type | Category | Subcategory |
|----------|-------------|-----------------|
| [Overview](#overview)  | - | - |
| [Evaluation](#evaluation)  | - | - |
| [Basic Tech](#basic-tech)  | [Vision Language](#vision-language) | - |
| [Basic Tech](#basic-tech)  | [Parsing](#parsing) | - |
| [Basic Tech](#basic-tech)   | [Segmentation, Recognition, Tracking](#segmentation-recognition-tracking) | - |
| [Basic Tech](#basic-tech)  | [Detection](#detection) | - |
| [Selling](#selling)  | [Retrieval](#retrieval) | - |
| [Selling](#selling)  | [Selling Agent](#selling-agent) | - |
| [Styling](#styling)  | [Compatibility Learning](#compatibility-learning) | - |
| [Styling](#styling) | [Outfit Recommendation](#outfit-recommendation) | - |
| [Design](#design) | [2D Synthesis](#2d-synthesis)| - |
| [Design](#design) | [Try-On](#try-on)| - |
| [Design](#design) | [Editing](#editing)| - |
| [Design](#design) | [Design Agent](#design-agent) | - |
| [Design](#design) | [Video Generation](#video-generation)  | - |
| [Design](#design) | [UV Generation](#uv-generation)  | - |
| [Design](#design) | [3D Synthesis](#3d-synthesis) | - |
| [Design](#design) | [3D Reconstruction](#3d-reconstruction) | - |
| [Buying](#buying) | [Trend Analysis](#trend-analysis) | - |

```mermaid
graph LR
  GenAIFashion[GenAI-Fashion]
  GenAIFashion --> Overview[Overview]
  GenAIFashion --> Evaluation[Evaluation]
  GenAIFashion --> BasicTech[Basic Tech]
  GenAIFashion --> Selling[Selling]
  GenAIFashion --> Styling[Styling]
  GenAIFashion --> Design[Design]
  GenAIFashion --> Buying[Buying]

  BasicTech --> VisionLanguage[Vision Language]
  BasicTech --> Parsing[Parsing]
  BasicTech --> SegmentationRecognitionTracking[Segmentation, Recognition, Tracking]
  BasicTech --> Detection[Detection]

  Selling --> Retrieval[Retrieval]
  Selling --> SellingAgent[Selling Agent]

  Styling --> CompatibilityLearning[Compatibility Learning]
  Styling --> OutfitRecommendation[Outfit Recommendation]

  Design --> 2DSynthesis[2D Synthesis]
  Design --> TryOn[Try-On]
  Design --> Editing[Editing]
  Design --> DesignAgent[Design Agent]
  Design --> VideoGeneration[Video Generation]
  Design --> UVGeneration[UV Generation]
  Design --> 3DSynthesis[3D Synthesis]
  Design --> 3DReconstruction[3D Reconstruction]
  
  Buying --> TrendAnalysis[Trend Analysis]
  
```

- [👀Workshops](#workshops)
- [🚀Companies, Products](#companies-products)
- [Researchers](#researchers)
- [Industry Reports](#industry-reports)
- [Other FashionAI Resources](#other-fashionai-resources)
- [Other GenAI Resources](#other-genai-resources)



## 📝Papers
### Overview

Summary developments of technology

| Title | Publication | Paper | Type | Region | 
| ----- | ----------- | ----- | ---- | ------------ |
| A Survey of Artificial Intelligence in Fashion | IEEE Signal Process. Mag. 2023 | [paper](https://ieeexplore.ieee.org/document/10113373) | Overview | Taiwan (China) |
| AI Assisted Fashion Design: A Review | IEEE Access 2023 | [paper](https://ieeexplore.ieee.org/document/10223039) | Fashion Design | China |
| Computational Technologies for Fashion Recommendation: A Survey | ACM Comput. Surv. 2023 | [paper](https://dl.acm.org/doi/10.1145/3627100) | Fashion Recommendation | Hong Kong (China) |
| A Review of Modern Fashion Recommender Systems | ACM Comput. Surv. 2023 | [paper](https://dl.acm.org/doi/10.1145/3624733) | Fashion Recommendation | Italy |
| A survey on Fashion Image Retrieval | ACM Comput. Surv. 2023 | [paper](https://dl.acm.org/doi/10.1145/3636552) | Fashion Retrieval | India |
| Appearance and Pose-Guided Human Generation: A Survey | ACM Comput. Surv. 2023 | [paper](https://dl.acm.org/doi/10.1145/3637060) | Fashion Generation | Hong Kong (China) |
| Analytics Applications in Fashion Supply Chain Management—A Review of Literature and Practice | IEEE Trans Eng Manag 2023 | [paper](https://ieeexplore.ieee.org/document/9461179/authors) | Fashion Supply Chain | Germany |
| Deep Learning Approaches for Fashion Knowledge Extraction From Social Media: A Review. | IEEE Access 2022 | [paper](https://ieeexplore.ieee.org/document/9661397) | Fashion Knowledge Extraction | Italy |
| Defining digital fashion: Reshaping the field via a systematic review | Comput. Hum. Behav. 2022 | [paper](https://www.sciencedirect.com/science/article/pii/S0747563222002291?via=ihub) | Digital Fashion | South Korea |
| A Review of AI (Artificial Intelligence) Tools and Customer Experience in Online Fashion Retail | Int. J. E Bus. Res. 2022 | [paper](https://www.igi-global.com/gateway/article/294111) | Fashion Retail | India |
| Fashion Meets Computer Vision: A Survey. | ACM Comput. Surv. 2021 | [paper](https://dl.acm.org/doi/10.1145/3447239) | Overview | Taiwan (China)  |
| Smart Fashion: A Review of AI Applications in the Fashion & Apparel Industry | Preprint 2021 | [paper](https://arXiv.org/pdf/2111.00905) | Overview | Iran |
| fAshIon after fashion: A Report of AI in Fashion | Preprint 2021 | [paper](https://arXiv.org/abs/2105.03050) | Overview | Hong Kong(China) |
| Aesthetics, Personalization and Recommendation: A survey on Deep Learning in Fashion | Preprint 2021 | [paper](https://arXiv.org/abs/2101.08301) | Overview | China |
| Fashion Recommendation Systems, Models and Methods: A Review | Informatics 2021 | [paper](https://www.mdpi.com/2227-9709/8/3/49#:~:text=Fashion%20Recommendation%20Systems%2C%20Models%20and%20Methods%3A%20A%20Review,Metrics%20Used%20in%20Fashion%20Recommendation%20System%20Evaluation%20) | Fashion Recommendation | USA  |
| A Detailed Review of Artificial Intelligence Applied in the Fashion and Apparel Industry | IEEE Access 2019 | [paper](https://ieeexplore.ieee.org/document/8763948) | Overview | France  |
| An Overview of Image Recognition and Retrieval of Clothing items | RICE 2018 | [paper](https://ieeexplore.ieee.org/document/8763948) | Fashion Retrieval | India |
| When Multimedia Meets Fashion | IEEE MultiMedia 2018 | [paper](https://ieeexplore.ieee.org/document/8589035) | Overview | China |
| Fashion Analysis: Current Techniques and Future Directions | IEEE MultiMedia 2014 | [paper](https://ieeexplore.ieee.org/abstract/document/6818912) | Overview | Singapore  |

### Evaluation

Evaluation protocols for specific tasks

| Title | Publication | Paper | Link | Region |
| ----- | ----------- | ----- | ---- | ------------ |
| How Good Is Aesthetic Ability of a Fashion Model? | CVPR 2022 | [paper](https://openaccess.thecvf.com/content/CVPR2022/html/Zou_How_Good_Is_Aesthetic_Ability_of_a_Fashion_Model_CVPR_2022_paper.html) | [dataset](https://github.com/AemikaChow/AiDLab-fAshIon-Data) | Hong Kong (China) |
| An Evaluation of Artificial Intelligence Components in E-Commerce Fashion Platforms | WorldCIST 2022 | [paper](https://link.springer.com/chapter/10.1007/978-3-031-04826-5_27) | - | Portugal |
| Where are my clothes? A multi-level approach for evaluating deep instance segmentation architectures on fashion images | 4th CVFAD (CVPR 2021 workshop)  | [paper](https://openaccess.thecvf.com/content/CVPR2021W/CVFAD/papers/Jouanneau_Where_Are_My_Clothes_A_Multi-Level_Approach_for_Evaluating_Deep_CVPRW_2021_paper.pdf) | - | France |
| Assessing Fashion Recommendations: A Multifaceted Offline Evaluation Approach | recsysXfashion 2019 (RecSys 2019 workshop) | [paper](https://arxiv.org/abs/1909.04496) | - | USA |


### Basic Tech

Understanding of fashion images

#### Vision Language
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| FashionCLIP | Contrastive language and vision learning of general fashion concepts | Scientific Reports (2022) | [paper](https://www.nature.com/articles/s41598-022-23052-9) | [code](https://github.com/patrickjohncyh/fashion-clip) | Canada |
| GradREC | “Does it come in black?” CLIP-like models are zero-shot recommenders | ECNLP 5(ACL 2022 workshop) | [paper](https://aclanthology.org/2022.ecnlp-1.22/) | [code](https://github.com/patrickjohncyh/gradient-recs) | Milan |
| FashionViL | Fashion-Focused Vision-and-Language Representation Learning | ECCV 2022 | -> | [project](https://github.com/BrandonHanx/mmf) | UK |
| FAME-ViL | FAME-ViL: Multi-Tasking Vision-Language Model for Heterogeneous Fashion Tasks | CVPR 2023 | -> | [project](https://github.com/BrandonHanx/FAME-ViL) | UK |
| FashionSAP | FashionSAP: Symbols and Attributes Prompt for Fine-grained Fashion Vision-Language Pre-training | CVPR 2023 | -> | [project](https://github.com/hssip/FashionSAP) | China |
| FashionVQA | FashionVQA: A Domain-Specific Visual Question Answering System | 6th CVFAD (CVPR 2023 workshop) | [paper](https://drive.google.com/file/d/1o110CVrktV3lYDH-VG7-gnI9jlrjpun_/view) | - | USA |
| VSE | Fashion-Specific Ambiguous Expression Interpretation with Partial Visual-Semantic Embedding | 6th CVFAD (CVPR 2023 workshop) | [paper](https://drive.google.com/file/d/1mTI2QvV42Cb4X2jd76y2CVerF6zCLAJ_/view) | - | Japan |
| SkiLL | SkiLL: Skipping Color and Label Landscape: Self Supervised Design Representations for Products in E-commerce | 6th CVFAD (CVPR 2023 workshop) | [paper](https://drive.google.com/file/d/13qSrQjvfrZmcMFjwtfb_3luQUdxJctaz/view) | - | USA |

#### Parsing
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| - | Parsing clothing in fashion photographs  | CVPR 2012 | [paper](https://ieeexplore.ieee.org/abstract/document/6248101) | - | USA |
| - | Paper Doll Parsing: Retrieving Similar Styles to Parse Clothing Items  | ICCV 2013 | [paper](https://www.cv-foundation.org/openaccess/content_iccv_2013/html/Yamaguchi_Paper_Doll_Parsing_2013_ICCV_paper.html) | - | USA |
| - | Fashion Parsing With Weak Color-Category Labels  | TMM 2013 | [paper](https://ieeexplore.ieee.org/abstract/document/6630093) | - | Singapore |
| - | Retrieving Similar Styles to Parse Clothing  | TPAMI 2014 | [paper](https://ieeexplore.ieee.org/abstract/document/6888484) | - | Japan |
| - | Fashion Parsing with Video Context | MM 2014 | [paper](https://dl.acm.org/doi/abs/10.1145/2647868.2654932) | - | Singapore |
| - | Parsing Based on Parselets: A Unified Deformable Mixture Model for Human Parsing | TPAMI 2015 | [paper](https://ieeexplore.ieee.org/abstract/document/7080924) | - | Singapore |
| - | Holistic, Instance-Level Human Parsing | BMVC 2017 | [paper](https://arxiv.org/abs/1709.03612)| - | UK |
| Look into Person | Look into Person: Joint Body Parsing & Pose Estimation Network and a New Benchmark | TPAMI 2019 | [paper](https://ieeexplore.ieee.org/abstract/document/8327922) | - | China |
| - | Looking at Outfit to Parse Clothing | Preprint 2017 | [paper](https://arxiv.org/abs/1703.01386) | - | Japan |
| - | Surveillance Video Parsing With Single Frame Supervision | CVPR 2017 | [paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Liu_Surveillance_Video_Parsing_CVPR_2017_paper.html) | - | China |
| - | Clothes Co-Parsing Via Joint Image Segmentation and Labeling With Application to Clothing Retrieval | TMM 2016 | [paper](https://ieeexplore.ieee.org/abstract/document/7434660) | - | China |
| - | Enhanced Reweighted MRFs for Efficient Fashion Image Parsing | TOMM 2016 | [paper](https://dl.acm.org/doi/abs/10.1145/2890104) | - | Canada |


#### Segmentation, Recognition, Tracking
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ---- |
| - | Who Blocks Who: Simultaneous clothing segmentation for grouping images | ICCV 2011 | [paper](https://ieeexplore.ieee.org/abstract/document/6126412) | - | China |
| - | Joint Multi-Person Pose Estimation and Semantic Part Segmentation | CVPR 2017 | [paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Xia_Joint_Multi-Person_Pose_CVPR_2017_paper.html)| - | USA |
| Fashionformer | Fashionformer: A Simple, Effective and Unified Baseline for Human Fashion Segmentation and Recognition | ECCV 2022 | -> | [project](https://github.com/xushilin1/FashionFormer) | China |
| GarmentTracking | GarmentTracking: Category-Level Garment Pose Tracking  | CVPR 2023 | -> | [project](https://garment-tracking.robotflow.ai/) | China |
| - | DETR-based Layered Clothing Segmentation and Fine-Grained Attribute Recognition  | 6th CVFAD (CVPR 2023 workshop) | [paper](https://drive.google.com/file/d/1q89zKZ7bobBpUqkBCDypn44B1EvxnHBA/view) | - | Hong Kong (China) |


#### Detection
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| - | Fashion Landmark Detection in the Wild | ECCV 2016 | [paper](https://link.springer.com/chapter/10.1007/978-3-319-46475-6_15) | - | Hong Kong(China) |
| - | Unconstrained Fashion Landmark Detection via Hierarchical Recurrent Transformer Networks | MM 2017 | [paper](https://dl.acm.org/doi/abs/10.1145/3123266.3123276) | - | Hong Kong (China) |
| - |  Spatial-aware non-local attention for fashion landmark detection | ICME 2019 | [paper](https://ieeexplore.ieee.org/abstract/document/8784817) | - | China |
| - | Layout-Graph Reasoning for Fashion Landmark Detection | CVPR 2019 | [paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Yu_Layout-Graph_Reasoning_for_Fashion_Landmark_Detection_CVPR_2019_paper.html) | - | China |
| DeepFashion2 | DeepFashion2: A Versatile Benchmark for Detection, Pose Estimation, Segmentation and Re-Identification of Clothing Images | CVPR 2019 | [paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Ge_DeepFashion2_A_Versatile_Benchmark_for_Detection_Pose_Estimation_Segmentation_and_CVPR_2019_paper.html)| - | China |
| - | A global-local embedding module for fashion landmark detection | 2nd CVFAD (ICCV 2019 workshop) | [paper](https://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Lee_A_Global-Local_Embedding_Module_for_Fashion_Landmark_Detection_ICCVW_2019_paper.html) | - | Korea |
| Fashionpedia | Fashionpedia: Ontology, Segmentation, and an Attribute Localization Dataset | ECCV 2020 | [paper](https://link.springer.com/chapter/10.1007/978-3-030-58452-8_19) | - | USA |
| - |  Fashion landmark detection and category classification for robotics | ICARSC 2020  | [paper](https://ieeexplore.ieee.org/abstract/document/9096071) | - | Switzerland |
| - | Segmentation task for fashion and apparel | Preprint 2020  | [paper](https://arxiv.org/abs/2006.11375) | - | USA |
| - | Aggregation and Finetuning for Clothes Landmark Detection | Preprint 2020 | [paper](https://arxiv.org/abs/2005.00419) | [code](https://github.com/lzhbrian/deepfashion2-kps-agg-finetune) | China |
| - | Improving apparel detection with category grouping and multi-grained branches | Multimedia Tools and Applications 2022  | [paper](https://link.springer.com/article/10.1007/s11042-022-13424-8) | - | USA |
| CoRe | CoRe: Color Regression for Multicolor Fashion Garments | 5th CVFAD (CVPR 2022 workshop)  | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Rame_CoRe_Color_Regression_for_Multicolor_Fashion_Garments_CVPRW_2022_paper.pdf) | - | France |


### Selling

Online selling

#### Retrieval
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| MODC | Fine-grained Fashion Representation Learning by Online Deep Clustering| ECCV 2022 | [paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870019.pdf) | - | USA |
| FashionVLP | FashionVLP: Vision Language Transformer for Fashion Retrieval with Feedback | CVPR 2022 | [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Goenka_FashionVLP_Vision_Language_Transformer_for_Fashion_Retrieval_With_Feedback_CVPR_2022_paper.pdf) | - | USA |
| EI-CLIP | EI-CLIP: Entity-aware Interventional Contrastive Learning for E-commerce Cross-modal Retrieval | CVPR 2022 | [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_EI-CLIP_Entity-Aware_Interventional_Contrastive_Learning_for_E-Commerce_Cross-Modal_Retrieval_CVPR_2022_paper.pdf) | - | USA |
| DAtRNet | DAtRNet: Disentangling Fashion Attribute Embedding for Substitute Item Retrieval | 5th CVFAD (CVPR 2022 workshop)  | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Bhattacharya_DAtRNet_Disentangling_Fashion_Attribute_Embedding_for_Substitute_Item_Retrieval_CVPRW_2022_paper.pdf) | - | India |
| UIGR | UIGR: Unified Interactive Garment Retrieval | 5th CVFAD (CVPR 2022 workshop)  | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Han_UIGR_Unified_Interactive_Garment_Retrieval_CVPRW_2022_paper.pdf) | [code](https://github.com/brandonhanx/compfashion) | UK |
| M3-Net | Learning Attribute and Class-Specific Representation Duet for Fine-grained Fashion Analysis | CVPR 2023 | [paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiao_Learning_Attribute_and_Class-Specific_Representation_Duet_for_Fine-Grained_Fashion_Analysis_CVPR_2023_paper.pdf) | - | USA |
| - | Dynamic Network for Language-based Fashion Retrieval | MMIR ’23 (MM 2023 workshop)  | [paper](https://dl.acm.org/doi/10.1145/3606040.3617438) | - | China |


#### Selling Agent
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- |  ---- |
| - | A Conversational Shopping Assistant for Online Virtual Stores | MM 2022 | [paper](https://dl.acm.org/doi/10.1145/3503161.3547738) | - | Portugal |
| Fashion-GPT | Fashion-GPT: Integrating LLMs with Fashion Retrieval System | LGM3A '23 (MM 2023 workshop) | [paper](https://dl.acm.org/doi/10.1145/3607827.3616844) | - | Singapore |

### Styling

Personal Styling

#### Compatibility Learning
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ---- |
| FCBoost-Net | FCBoost-Net: A Generative Network for Synthesizing Multiple Collocated Outfits via Fashion Compatibility Boosting | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612036) | - | China |

#### Outfit Recommendation
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ---- |
| BiHGH | Bi-directional Heterogeneous Graph Hashing towards Efficient Outfit Recommendation | MM 2022 | [paper](https://dl.acm.org/doi/10.1145/3503161.3548020) | - | Australia |
| OutfitTransformer | OutfitTransformer: Outfit Representations for Fashion Recommendation | 5th CVFAD (CVPR 2022 workshop) | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Sarkar_OutfitTransformer_Outfit_Representations_for_Fashion_Recommendation_CVPRW_2022_paper.pdf) | - | USA |
| OutfitGAN | OutfitGAN: Learning Compatible Items for Generative Fashion Outfits | 5th CVFAD (CVPR 2022 workshop) | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Moosaei_OutfitGAN_Learning_Compatible_Items_for_Generative_Fashion_Outfits_CVPRW_2022_paper.pdf) | - | USA |
| CP-TransMatch | Modeling Multi-Relational Connectivity for Personalized Fashion Matching | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612583) | - | Hong Kong (China) |
| SHIFT15M | SHIFT15M: Fashion-specific dataset for set-to-set matching with several distribution shifts | 6th CVFAD (CVPR 2023 workshop) | [paper](https://drive.google.com/file/d/11SUgNGdCjx7Z0rMX2VdFp-vQJuJPR5bD/view) | [code](https://github.com/st-tech/zozo-shift15m) | Japan |

### Design
#### 2D Synthesis

| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| ARMANI | ARMANI: Part-level Garment-Text Alignment for Unified Cross-Modal Fashion Design | MM 2022 | [paper](https://dl.acm.org/doi/10.1145/3503161.3548230) | - | China |
| AI Carpet | AI Carpet: Automatic Generation of Aesthetic Carpet Pattern | MM 2022 | [paper](https://dl.acm.org/doi/10.1145/3503161.3547734) | - | China |
| VolumeGAN | 3D-aware Image Synthesis via Learning Structural and Textural Representations | CVPR 2022 | -> | [project](https://genforce.github.io/volumegan/) | China |
| Wearable ImageNet | Wearable ImageNet: Synthesizing Tileable Textures via Dataset Distillation | 5th CVFAD (CVPR 2022 workshop | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Cazenavette_Wearable_ImageNet_Synthesizing_Tileable_Textures_via_Dataset_Distillation_CVPRW_2022_paper.pdf) | [project](https://georgecazenavette.github.io/mtt-distillation/) | USA |
| Rank in Style | Rank in Style: A Ranking-based Approach to Find Interpretable Directions | 5th CVFAD (CVPR 2022 workshop | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Kocasari_Rank_in_Style_A_Ranking-Based_Approach_To_Find_Interpretable_Directions_CVPRW_2022_paper.pdf) | - | Turkey |
| StyleMe | StyleMe: Towards Intelligent Fashion Generation with Designer Style | CHI 2023 | [paper](https://dl.acm.org/doi/fullHtml/10.1145/3544548.3581377) | [code](https://github.com/ExponentiAI/StyleMe) | China |
| generative.fashion | Fashioning the Future: Unlocking the Creative Potential of Deep Generative Models for Design Space Exploration | CHI EA 2023 | [paper](https://dl.acm.org/doi/abs/10.1145/3544549.3585644) | [project](https://generative.fashion/) | Switzerland |
| AI Archive | Generative AI for Concept Creation in Footwear Design | INVITED-TALK (SIGGRAPH 2023) | [paper](https://dl.acm.org/doi/10.1145/3587421.3595416) | - | Germany |
| UnitedHuman | UnitedHuman: Harnessing Multi-Source Data for High-Resolution Human Generation | ICCV 2023 | -> | [project](https://unitedhuman.github.io/) | China |
| FreeDoM | FreeDoM: Training-Free Energy-Guided Conditional Diffusion Model | ICCV 2023 | [paper](https://arXiv.org/abs/2303.09833) | [code](https://github.com/vvictoryuki/FreeDoM) | China |
| BoxDiff | BoxDiff: Text-to-Image Synthesis with Training-Free Box-Constrained Diffusion | ICCV 2023 | [paper](https://arXiv.org/abs/2307.10816) | [code](https://github.com/showlab/BoxDiff) | Singapore |
| ControlNet | Adding Conditional Control to Text-to-Image Diffusion Models | ICCV2023 | [paper](https://arXiv.org/abs/2302.05543) | [code](https://github.com/lllyasviel/ControlNet) | USA |
| PromptStyler | PromptStyler: Prompt-driven Style Generation for Source-free Domain Generalization | ICCV 2023 | -> | [project](https://promptstyler.github.io/) | South Korea |
| Diffusart | Diffusart: Enhancing Line Art Colorization with Conditional Diffusion Models | 6th CVFAD (CVPR 2023 workshop | [paper](https://drive.google.com/file/d/1yShjhoGVYavSab5iRwvUD9hpVGGk8wfE/view) | - | France |
| Gatha | Gatha: Relational Loss for enhancing text-based style transfer | 6th CVFAD (CVPR 2023 workshop | [paper](https://drive.google.com/file/d/13yCg7QDeMM7lKyl4ApMSpMYFr6WDkSe3/view) | - | USA |
| DiffFashion | Image Reference-guided Fashion Design with Structure-aware Transfer by Diffusion Models | 6th CVFAD (CVPR 2023 workshop | [paper](https://drive.google.com/file/d/1hWy4CFdN0rqluvyXevfp0OZTt8zAYvvk/view) | [code](https://github.com/Rem105-210/DiffFashion) | China |
| VectorFusion | VectorFusion: Text-to-SVG by Abstracting Pixel-Based Diffusion Models | CVPR 2023 | -> | [project](https://ajayj.com/vectorfusion), [unofficial code](https://github.com/ximinng/VectorFusion-pytorch) | USA |
| DiffSketcher | DiffSketcher: Text Guided Vector Sketch Synthesis through Latent Diffusion Models | NIPS 2023 | -> | [project](https://ximinng.github.io/DiffSketcher-project/) | China |
| SGDiff | SGDiff: A Style Guided Diffusion Model for Fashion Synthesis | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3613806) | [code](https://github.com/taited/SGDiff) | Hong Kong (China) |
| FashionDiff | FashionDiff: A Controllable Diffusion Model Using Pairwise Fashion Elements for Intelligent Design | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612127) | - | China |
| InspirNET | InspirNET: An Unsupervised Generative Adversarial Network with Controllable Fine-grained Texture Disentanglement for Fashion Generation | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612130) | - | China |
| - | Toward Intelligent Interactive Design: A Generation Framework Based on Cross-domain Fashion Elements | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612376) | - | China |


#### Try-On
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| - | A High-resolution Image-based Virtual Try-on System in Taobao E-commerce Scenario | MM 2022 | [paper](https://dl.acm.org/doi/10.1145/3503161.3547740) | - | China |
| GT-MUST | GT-MUST: Gated Try-on by Learning the Mannequin-Specific Transformation | MM 2022 | [paper](https://dl.acm.org/doi/10.1145/3503161.3547775) | - | China |
| PL-VTON | Progressive Limb-Aware Virtual Try-On | MM 2022 | [paper](https://dl.acm.org/doi/10.1145/3503161.3547999) | - | China |
| Dress Code | Dress Code: High-Resolution Multi-Category Virtual Try-On| 5th CVFAD (CVPR 2022 workshop) | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Morelli_Dress_Code_High-Resolution_Multi-Category_Virtual_Try-On_CVPRW_2022_paper.pdf) | [project](https://github.com/aimagelab/dress-code) | Italy |
| DBCT | Dual-Branch Collaborative Transformer for Virtual Try-On | 5th CVFAD (CVPR 2022 workshop) | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Fenocchi_Dual-Branch_Collaborative_Transformer_for_Virtual_Try-On_CVPRW_2022_paper.pdf) | - | Italy |
| DP-VTON | Towards Detailed Characteristic-Preserving Virtual Try-On | 5th CVFAD (CVPR 2022 workshop) | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Lee_Towards_Detailed_Characteristic-Preserving_Virtual_Try-On_CVPRW_2022_paper.pdf) | - | South Korea |
| Flow-Style-VTON | Style-Based Global Appearance Flow for Virtual Try-On | CVPR 2022 | -> | [project](https://github.com/SenHe/Flow-Style-VTON/) | UK |
| RT-VTON | Full-Range Virtual Try-On with Recurrent Tri-Level Transform | CVPR 2022 | -> | [project](https://lzqhardworker.github.io/RT-VTON/) | China, Singapore |
| DGP | Weakly Supervised High-Fidelity Clothing Model Generation | CVPR 2022 | [paper](https://arXiv.org/abs/2112.07200) | - | China |
| FashionTex | FashionTex: Controllable Virtual Try-on with Text and Texture. | SIGGRAPH 2023 | [paper](https://arXiv.org/abs/2305.04451) | [code](https://github.com/picksh/FashionTex) | China |
| FreqHPT | FreqHPT: Frequency-aware attention and flow fusion for Human Pose Transfer | 6th CVFAD (CVPR 2023 workshop) | [paper](https://drive.google.com/file/d/1N-GINjfBo9YoNmuE0CKjGyrbE1uHWx-i/view) | - | China |
|  SAL-VTON | Linking Garment with Person via Semantically Associated Landmarks for Virtual Try-On | CVPR 2023 | [paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Yan_Linking_Garment_With_Person_via_Semantically_Associated_Landmarks_for_Virtual_CVPR_2023_paper.pdf) | [project](https://modelscope.cn/datasets/damo/SAL-HG/summary) | China |
| TryOnDiffusion | TryOnDiffusion: A Tale of Two UNets | CVPR 2023 | -> | [project](https://tryondiffusion.github.io/) | USA |
| GP-VTON | GP-VTON: Towards General Purpose Virtual Try-on via Collaborative Local-Flow Global-Parsing Learning | CVPR 2023 | -> | [project](https://github.com/xiezhy6/GP-VTON) | China |
| LaDI-VTON | LaDI-VTON:Latent Diffusion Textual-Inversion Enhanced Virtual Try-On | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612137) | [code](https://github.com/miccunifi/ladi-vton) | Italy |
| DCI-VTON | Taming the Power of Diffusion Models for High-Quality Virtual Try-On with Appearance Flow | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612255) | [code](https://github.com/bcmi/DCI-VTON-Virtual-Try-On) | China |
| PG-VTON | PG-VTON: A Novel Image-Based Virtual Try-On Method via Progressive Inference Paradigm | TMM 2023 | [paper](https://arXiv.org/abs/2304.08956) | [code](https://github.com/NerdFNY/PGVTON) | China |
| DOC-VTON | OccluMix: Towards De-Occlusion Virtual Try-on by Semantically-Guided Mixup | TMM 2023 | [paper](https://arXiv.org/abs/2301.00965) | [code](https://github.com/JyChen9811/DOC-VTON) | China |
| StableVITON | StableVITON: Learning Semantic Correspondence with Latent Diffusion Model for Virtual Try-On | Preprint 2023 | -> | [project](https://rlawjdghek.github.io/StableVITON/) | South Korea |

#### Editing
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| SketchEdit | SketchEdit: Mask-Free Local Image Manipulation with Partial Sketches | CVPR 2022 | -> | [project](https://zengxianyu.github.io/sketchedit/) | USA |
| Patternshop | Patternshop: Editing Point Patterns by Image Manipulation | SIGGRAPH 2023 | -> | [project](https://xchhuang.github.io/patternshop/index.html) | Germany |
| MGD | Multimodal Garment Designer: Human-Centric Latent Diffusion Models for Fashion Image Editing | ICCV 2023 | [paper](https://arXiv.org/abs/2304.02051) | [code](https://github.com/aimagelab/multimodal-garment-designer) | Italy |
| EditAnything | EditAnything: Empowering Unparalleled Flexibility in Image Editing and Generation | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612680) | [project](https://github.com/sail-sg/EditAnything) | China |

#### Design Agent
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| FashionMatrix | Fashion Matrix: Editing Photos by Just Talking | Preprint 2023 | -> | [project](https://zheng-chong.github.io/FashionMatrix/) | China |

#### Video Generation
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| wFlow | Dressing in the Wild by Watching Dance Videos | CVPR 2022 | -> | [project](https://awesome-wflow.github.io/) | China |
| ClothFormer | ClothFormer: Taming Video Virtual Try-on in All Module | CVPR 2022 | -> | [project](https://cloth-former.github.io/) | China |
| GPT4Motion | GPT4Motion: Scripting Physical Motions in Text-to-Video Generation via Blender-Oriented GPT Planning | Preprint 2023 | -> | [project](https://gpt4motion.github.io/) | China |
| Animate Anyone | Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation | Preprint 2023 | -> | [project](https://humanaigc.github.io/animate-anyone/) | China |

#### UV Generation
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| TemporalUV | TemporalUV: Capturing Loose Clothing with Temporally Coherent UV Coordinates | CVPR 2022 | [paper](https://arXiv.org/abs/2204.03671) | - | Germany |
| - | Normal-guided Garment UV Prediction for Human Re-texturing | CVPR 2023 | [paper](https://arXiv.org/abs/2303.06504) | - | USA |

#### 3D Synthesis
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| ReFU | A Repulsive Force Unit for Garment Collision Handling in Neural Networks | ECCV 2022 | -> | [project](https://gamma.umd.edu/researchdirections/mlphysics/refu/) | USA |
| SNUG | SNUG: Self-Supervised Neural Dynamic Garments | CVPR 2022 | -> | [project](https://mslab.es/projects/SNUG/) | Spain |
| ICON | ICON: Implicit Clothed humans Obtained from Normals | CVPR 2022 | -> | [project](https://github.com/YuliangXiu/ICON) | Germany |
| True Seams | True Seams:Modeling Seams in Digital Garments | SIGGRAPH 2022 | -> | [project](https://gabrielcirio.gitlab.io/projects/trueseams/trueseams.html) | USA |
| VirtualBones | Predicting Loose-Fitting Garment Deformations Using Bone-Driven Motion Networks | SIGGRAPH 2022 | -> | [project](http://www.cad.zju.edu.cn/home/jin/SigCloth2022/SigCloth2022.htm) | China |
| HairStep | HairStep: Transfer Synthetic to Real Using Strand and Depth Maps for Single-View 3D Hair Modeling | CVPR 2023 | -> | [project](https://paulyzheng.github.io/research/hairstep/) | China |
| ECON | ECON: Explicit Clothed humans Optimized via Normal integration | CVPR 2023 | -> | [project](https://github.com/YuliangXiu/ECON) | Germany |
| DrapeNet | DrapeNet: Garment Generation and Self-Supervised Draping | CVPR 2023 | -> | [project](https://github.com/liren2515/DrapeNet) | Switzerland |
| AnchorDEF | Learning Anchor Transformations for 3D Garment Animation | CVPR 2023 | -> | [project](https://semanticdh.github.io/AnchorDEF/) | China |
| CloSET | CloSET: Modeling Clothed Humans on Continuous Surface with Explicit Template Decomposition | CVPR 2023 | -> | [project](https://www.liuyebin.com/closet/) | China |
| - | Clothed Human Performance Capture with a Double-layer Neural Radiance Fields | CVPR 2023 | [paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Clothed_Human_Performance_Capture_With_a_Double-Layer_Neural_Radiance_Fields_CVPR_2023_paper.pdf) | - | China |
| HOOD | HOOD: Hierarchical Graphs for Generalized Modelling of Clothing Dynamics | CVPR 2023 | -> | [project](https://dolorousrtur.github.io/hood/) | Switzerland |
| xCloth | xCloth: Extracting Template-free Textured 3D Clothes from a Monocular Image | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3503161.3548419) | - | India |
| AvatarFusion | AvatarFusion: Zero-shot Generation of Clothing-Decoupled 3D Avatars Using 2D Diffusion | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612022) | [project](https://hansenhuang0823.github.io/AvatarFusion/) | China |
| Control3D | Control3D: Towards Controllable Text-to-3D Generation | MM 2023 | [paper](https://dl.acm.org/doi/10.1145/3581783.3612489) | - | China |
| SynBody | SynBody: Synthetic Dataset with Layered Human Models for 3D Human Perception and Modeling | ICCV 2023 | -> | [project](https://synbody.github.io/) | China |
| EVA3D | EVA3D: Compositional 3D Human Generation from 2D Image Collections | ICLR 2023 | -> | [project](https://hongfz16.github.io/projects/EVA3D.html) | Singapore |
| En3D | En3D: An Enhanced Generative Model for Sculpting 3D Humans from 2D Synthetic Data | Preprint 2024 | -> | [project](https://menyifang.github.io/projects/En3D/index.html) | China |

#### 3D Reconstruction
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ------------ |
| CrossHuman | CrossHuman: Learning Cross-guidance from Multi-frame Images for Human Reconstruction | MM 2022 | [paper](https://dl.acm.org/doi/10.1145/3503161.3548351) | - | China |
| ReEF | Registering Explicit to Implicit: Towards High-Fidelity Garment mesh Reconstruction from Single Images | CVPR 2022 | -> | [project](https://kv2000.github.io/2022/03/28/reef/) | China |
| PHORHUM | Photorealistic Monocular 3D Reconstruction of Humans Wearing Clothing | CVPR 2022 | -> | [project](https://phorhum.github.io/) | USA |
| NeuralTailor | NeuralTailor: Reconstructing Sewing Pattern Structures from 3D Point Clouds of Garments | SIGGRAPH 2022 | [paper](https://arXiv.org/abs/2201.13063) | - | South Korea |
| SewFormer | Towards Garment Sewing Pattern Reconstruction from a Single Image | TOG (SIGGRAPH Asia 2023) | -> | [project](https://sewformer.github.io/) | Singapore |
| GTA | Global-correlated 3D-decoupling Transformer for Clothed Avatar Reconstruction | NIPS 2023 | -> | [project](https://river-zhang.github.io/GTA-projectpage/) | China |
| SeSDF | SeSDF: Self-evolved Signed Distance Field for Implicit 3D Clothed Human Reconstruction | CVPR 2023 | [paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Cao_SeSDF_Self-Evolved_Signed_Distance_Field_for_Implicit_3D_Clothed_Human_CVPR_2023_paper.pdf) | - | Hong Kong (China) |
| SoY | Shape of You: Precise 3D shape estimations for diverse body types | 6th CVFAD (CVPR 2023 workshop) | [paper](https://drive.google.com/file/d/1JqymSHzRtx0aaZquzQxkvJVdvsPsQn1G/view) | - | USA |
| KBody | KBody: Balanced monocular whole-body estimation | 6th CVFAD (CVPR 2023 workshop) | [paper](https://drive.google.com/file/d/1q-KuXsB1r6iFoKcPRsh5AdWjo1IE2Ezs/view) | [project](https://klothed.github.io/KBody/) | USA |
| CAR | High-Fidelity Clothed Avatar Reconstruction from a Single Image | CVPR 2023 | -> | [project](https://github.com/TingtingLiao/CAR) | China |
| DIFu | DIFu: Depth-Guided Implicit Function for Clothed Human Reconstruction | CVPR 2023 | -> | [project](https://eadcat.github.io/DIFu/) | South Korea |
| NeuralUDF | NeuralUDF: Learning Unsigned Distance Fields for Multi-view Reconstruction of Surfaces with Arbitrary Topologies | CVPR 2023 | -> | [project](https://www.xxlong.site/NeuralUDF/) | Hong Kong (China) |
| CLOTH4D | CLOTH4D: A Dataset for Clothed Human Reconstruction | CVPR 2023 | -> | [project](https://github.com/AemikaChow/CLOTH4D) | Hong Kong (China) |
| REC-MV | REC-MV: REconstructing 3D Dynamic Cloth from Monocular Videos | CVPR 2023 | -> | [project](https://lingtengqiu.github.io/2023/REC-MV/) | China |
| Get3DHuman | Get3DHuman: Lifting StyleGAN-Human into a 3D Generative Model using Pixel-aligned Reconstruction Priors |ICCV2023| -> |[project](https://x-zhangyang.github.io/2023_Get3DHuman/) | China |

### Buying

#### Trend Analysis
| Model | Title | Publication | Paper | Link | Region |
| ----- | ----- | ----------- | ----- | ---- | ---- |
| POP | POP: Mining POtential Performance of new fashion products via webly cross-modal query expansion | ECCV 2022 | -> | [project](https://github.com/HumaticsLAB/POP-Mining-POtential-Performance) | Italy |
| Visuelle 2.0 | The multi-modal universe of fast-fashion: the Visuelle 2.0 benchmark | 5th CVFAD (CVPR 2022 workshop) | [paper](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Skenderi_The_Multi-Modal_Universe_of_Fast-Fashion_The_Visuelle_2.0_Benchmark_CVPRW_2022_paper.pdf) | [project](https://humaticslab.github.io/forecasting/visuelle) | Italy |


## 👀Workshops
1. Computer Vision for Fashion, Art, and Design (CVPR Workshop): [CVFAD 2023](https://sites.google.com/view/cvfad2023/home), [CVFAD 2022](https://sites.google.com/view/cvfad2022/home)
2. Multimedia Computing towards Fashion Recommendation (ACM MM Workshop): [MCFR 2022](https://dl.acm.org/doi/abs/10.1145/3503161.3554765)
3. Machine Learning for Creativity and Design (NeurIPS Workshop): [ML4CD 2023](https://neuripscreativityworkshop.github.io/2023/), [ML4CD 2022](https://neuripscreativityworkshop.github.io/2022/)
4. Creative AI Across Modalities (AAAI Workshop): [creativeAI 2023](https://creativeai-ws.github.io/#cfp)
5. recsysXfashion (RecSys Workshop): [recsysXfashion 2022](https://recsys.acm.org/recsys22/fashionxrecsys/), [recsysXfashion 2021](https://recsys.acm.org/recsys21/fashionxrecsys/)


## 🚀Companies, Products
| Name                                                         | Found | Info                                        | News                                                         |
| ------------------------------------------------------------ | ----- | ------------------------------------------- | ------------------------------------------------------------ |
| [CALA](https://ca.la/) | 2016 | fashion supply chain interface that unifies design, development, production, and logistics | [2022.11](https://mp.weixin.qq.com/s/INLwwAqkHzQ2iLq-Oj7ZjA) |
| [Zalando Research](https://research.zalando.com/)            | 2016  | Research                                    | [2023.04 fashion assistant powered by ChatGPT](https://corporate.zalando.com/en/technology/zalando-launch-fashion-assistant-powered-chatgpt) |
| [Vue.ai](https://vue.ai/) | 2016 | Retail AI analysis, AI avatar | - |
| [极睿 infimind](http://infimind.com/)| 2017  | Fashion Product Content           | [2023.11 interview in mandarin](https://www.bilibili.com/video/BV1iu4y1879i/?spm_id_from=333.337.search-card.all.click&vd_source=32f6f61e74ca115cbaca6bd6bb144662)  |
| [知衣 zhiyi](https://www.zhiyitech.cn/)| 2018  | Fashion Design Collaboration         | [2023.08 Fashion Diffusion](https://mp.weixin.qq.com/s/TnYEc0bl0IasEdHsYmACOA) |
| [LALALAND](https://lalaland.ai/) | 2019 | AI avatar, Fashion Product Content | [2023.08 collaborate with Browzwear-VStitcher](https://mp.weixin.qq.com/s/ZPGR9UhlcaGIeRFUhiG4fA) |
| [PatternedAi](https://www.patterned.ai/) | 2021 | Pattern Design | - |
| [Dsign.Ai](https://app.dsign.ai/) | - | Prints and Patterns Design | - |
| [AIMDE-Symmpix](https://aimde.design/en) | 2023 | Fashion Pattern, 3D | [2023.11 new feature](https://mp.weixin.qq.com/s/priz3aVNByLW40hk2AdxSA) |
| [Weshop](https://www.weshop.com/) | 2023 | AI avatar & Fashion Product Content | a subsidiary of [MOGU](https://www.mogu.com/)  |
| [Wondershare VirtuLook](https://virtulook.wondershare.com/) | 2023 | AI avatar & Fashion Product Content | a subsidiary of [wondershare](https://www.wondershare.com/)|
| [Pixelcut](https://www.pixelcut.ai/) | 2022 | AI-powered editing tools(Product Content) | - |
| [CreatorKit](https://creatorkit.com/) | 2020 | AI Product Content, Videos | - |
| [DeepImage](https://deep-image.ai/) | 2022 | AI Product Content | - |
| [Unbound](https://www.unboundml.com/) | - | personal AI business assistant | - |
| [Zeg AI](https://www.zeg.ai/)| 2018 | AI Product Content, Videos, 3D Render | - |
| - | - | - | - |


## Researchers

| Group/Lab/Univ                                              |Researchers |
| ------------------------------------------------------------| -----------|
| [GAP Lab-CUHKSZ](https://gaplab.cuhk.edu.cn/pages/publications) | [Xiaoguang Han](https://scholar.google.com/citations?user=z-rqsR4AAAAJ&hl=en)|
| [HCP-I2 Lab-SYSU](https://www.sysu-hcp.net/publications/index.html) | [Xiaodan Liang](https://scholar.google.com/citations?user=voxznZAAAAAJ&hl=en),[Zhenyu Xie](https://xiezhy6.github.io/)|
| HIT SZ|[Haijun Zhang](https://dl2link.com/#)|
| [AiDlab-PolyU+RCA](https://www.aidlab.hk/en/)|[Calvin WONG](https://research.polyu.edu.hk/en/persons/wai-keung-wong-2),[Xingxing Zou](https://scholar.google.com/citations?user=UhnQA3UAAAAJ&hl=zh-CN),[P.Y.Mok](https://scholar.google.com.hk/citations?user=-83FFXcAAAAJ&hl=en)|
| [MMLab-NTU](https://www.mmlab-ntu.com/index.html)|[Ziwei Liu](https://liuziwei7.github.io/index.html)|
| UIUC | [Ranjitha Kumar](http://ranjithakumar.net/)|
| [AImageLab](https://aimagelab.ing.unimore.it/imagelab/)|[Rita Cucchiara](https://scholar.google.com/citations?user=OM3sZEoAAAAJ&hl=en)|
| The University of Utah |[Ziad Al-Halah](https://users.cs.utah.edu/~ziad/)|
| Georgia Tech | [Devi Parikh](https://faculty.cc.gatech.edu/~parikh/)|
| UT Austin | [Kristen Grauman](https://www.cs.utexas.edu/users/grauman/)|
| Cornell | [Kavita Bala](https://www.cs.cornell.edu/~kb/)|
| [MPI-IS](https://ps.is.mpg.de/) | [Michael Black](https://ps.is.mpg.de/person/black)|

## Industry Reports
| Reports                                              |Organization | Time |
| ------------------------------------------------------------| -----------| -----------|
| [Generative AI’s Act Two](https://www.sequoiacap.com/article/generative-ai-act-two/) | SEQUOIA | 2023.09 |
| [How Are Consumers Using Generative AI?](https://a16z.com/how-are-consumers-using-generative-ai/)| A16Z | 2023.09 |
| [Outlook for the Global and Chinese Fashion Industry in 2035](https://www.rolandberger.com/zh/Insights/Publications/2035%E5%85%A8%E7%90%83%E5%8F%8A%E4%B8%AD%E5%9B%BD%E6%97%B6%E5%B0%9A%E4%BA%A7%E4%B8%9A%E5%B1%95%E6%9C%9B.html)|Roland Berger|2023.08|
| [The Complete Playbook for Generative AI in Fashion](https://www.businessoffashion.com/case-studies/technology/generative-ai-playbook-machine-learning-emerging-technology/)|Bof|2023.06|
| [Generative AI: Unlocking the future of fashion](https://www.mckinsey.com/industries/retail/our-insights/generative-ai-unlocking-the-future-of-fashion) |McKinsey|2023.03|

## Other FashionAI Resources
1. [Fashion Datasets](https://github.com/AemikaChow/DATASOURCE)
2. [Cool Fashion Papers(Before 2022)](https://github.com/lzhbrian/Cool-Fashion-Papers)
3. [awesome-fashion-ai](https://github.com/ayushidalmia/awesome-fashion-ai)
4. [AI4Design Survey](https://idvxlab.com/ai4design/#)
5. [image-to-image-papers](https://github.com/lzhbrian/image-to-image-papers)
6. [Awesome Virtual Try-on (VTON) Research](https://github.com/minar09/awesome-virtual-try-on#non-clothing-virtual-try-on)
7. [Awesome-pose-transfer](https://github.com/Zhangjinso/Awesome-pose-transfer)
8. [Human Body Reconstruction](https://github.com/chenweikai/Body_Reconstruction_References)

## Other GenAI Resources
1. [The Roadmap of Generative AI](https://github.com/SeedV/generative-ai-roadmap)
2. [awesome-Ai-tools](https://github.com/TRA-Tech/awesome-artificial-intelligence-tools)
3. [LLM Survey](https://github.com/RUCAIBox/LLMSurvey)
4. [LLM-Agent-Paper-List](https://github.com/WooooDyy/LLM-Agent-Paper-List)
5. [Awesome-diffusion-model-for-image-processing](https://github.com/lixinustc/Awesome-diffusion-model-for-image-processing/tree/main)
6. [Multimodal Image Synthesis and Editing: The Generative AI Era](https://github.com/fnzhan/Generative-AI)
7. [GAN-Inversion Survey](https://github.com/weihaox/GAN-Inversion#gan-inversion-a-survey)
8. [A Survey on Deep Generative 3D-aware Image Synthesis](https://weihaox.github.io/3D-aware-Gen/)
9. [Awesome 3D Generation](https://github.com/justimyhxu/awesome-3D-generation)
10. [Generative AI meets 3D: A Survey on Text-to-3D in AIGC Era](https://arXiv.org/abs/2305.06131)
11. [Awesome GenAI Tech](https://github.com/hollobit/Awesome-GenAITech)
