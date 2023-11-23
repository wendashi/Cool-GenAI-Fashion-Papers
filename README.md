# Cool-GenAI-Fashion-Papers

🕶️ Cool resources about GenAI-Fashion! (papers, workshops, companies, ...) (constantly updating)

All the listed GenAI-Fashion papers have been published from 2022 onwards (including 2022).

For resources before 2022, please refer to [Other FashionAI Resources](#other-fashionai-resources).

Feel free to send a PR or open an issue.
<details>
  <summary>Table Of Content</summary>
  
  * [Papers](#papers)
     * [Synthesis](#synthesis)
        * [2D Synthesis](#2D-synthesis)
          * [Try-On](#try-on)
        * [3D Synthesis](#3D-synthesis)
     * [Agent](#agent)
     * [Understanding](#understanding)
        * [Vision Language](#vision-language)
        * [Segmentation, Recognition](#segmentation-recognition)
        * [Trend Analysis](#trend-analysis)
        * [Retrieval](#retrieval)
        * [Fashion Compatibility](#fashion-compatibility)
      
  * [Related Events](#related-events)
  * [Companies](#companies)
  * [Researchers](#researchers)
  * [Industry Reports](#industry-reports)
  * [Other Useful Resources](#other-useful-resources)
  
</details>


## Papers
### Synthesis
#### 2D Synthesis
| Model | Title | Publication | Paper | Link |
| ----- | ----- | ----------- | ----- | ---- |
| FashionTex | FashionTex: Controllable Virtual Try-on with Text and Texture. | SIGGRAPH 2023 | [2305.04451](https://arxiv.org/abs/2305.04451) | [code](https://github.com/picksh/FashionTex)|
| Patternshop | Patternshop: Editing Point Patterns by Image Manipulation | SIGGRAPH 2023 | -> | [project](https://xchhuang.github.io/patternshop/index.html) |
| MGD | Multimodal Garment Designer: Human-Centric Latent Diffusion Models for Fashion Image Editing | ICCV2023 | [2304.02051](https://arxiv.org/abs/2304.02051) | [code](https://github.com/aimagelab/multimodal-garment-designer) |
| FreeDoM | FreeDoM: Training-Free Energy-Guided Conditional Diffusion Model | ICCV2023 | [2303.09833](https://arxiv.org/abs/2303.09833) | [code](https://github.com/vvictoryuki/FreeDoM) |
| BoxDiff | BoxDiff: Text-to-Image Synthesis with Training-Free Box-Constrained Diffusion | ICCV2023 | [2307.10816](https://arxiv.org/abs/2307.10816) | [code](https://github.com/showlab/BoxDiff) |
| ControlNet | Adding Conditional Control to Text-to-Image Diffusion Models | ICCV2023 | [2302.05543](https://arxiv.org/abs/2302.05543) | [code](https://github.com/lllyasviel/ControlNet) |
| PromptStyler | PromptStyler: Prompt-driven Style Generation for Source-free Domain Generalization | ICCV2023 | -> | [project](https://promptstyler.github.io/) |
| VectorFusion | VectorFusion: Text-to-SVG by Abstracting Pixel-Based Diffusion Models | CVPR2023 | -> | [project](https://ajayj.com/vectorfusion),[unofficial code](https://github.com/ximinng/VectorFusion-pytorch) |
| DiffSketcher | DiffSketcher: Text Guided Vector Sketch Synthesis through Latent Diffusion Models | NIPS 2023 | -> | [project](https://ximinng.github.io/DiffSketcher-project/) |
| - | - | - | - | project |

##### Try-On
| Model | Title | Publication | Paper | Link |
| ----- | ----- | ----------- | ----- | ---- |
| wFlow | Dressing in the Wild by Watching Dance Videos | CVPR2022 | -> | [project](https://awesome-wflow.github.io/) |
| ClothFormer | ClothFormer: Taming Video Virtual Try-on in All Module | CVPR2022 | -> | [project](https://cloth-former.github.io/) |
| Flow-Style-VTON | Style-Based Global Appearance Flow for Virtual Try-On | CVPR2022 | -> | [project](https://github.com/SenHe/Flow-Style-VTON/) |
| RT-VTON | Full-Range Virtual Try-On with Recurrent Tri-Level Transform | CVPR2022 | -> | [project](https://lzqhardworker.github.io/RT-VTON/) |
| DGP | Weakly Supervised High-Fidelity Clothing Model Generation | CVPR2022 | [2112.07200](https://arxiv.org/abs/2112.07200) | - |
| - | - | CVPR2022 | - | project |
| - | - | CVPR2022 | - | project |
| - | - | - | - | project |


#### 3D Synthesis
| Model | Title | Publication | Paper | Link |
| ----- | ----- | ----------- | ----- | ---- |
| ReFU | A Repulsive Force Unit for Garment Collision Handling in Neural Networks | ECCV2022 | -> | [project](https://gamma.umd.edu/researchdirections/mlphysics/refu/) |
| ReEF | Registering Explicit to Implicit: Towards High-Fidelity Garment mesh Reconstruction from Single Images | CVPR 2022 | -> | [project](https://kv2000.github.io/2022/03/28/reef/) |
| SNUG | SNUG: Self-Supervised Neural Dynamic Garments | CVPR2022 | -> | [project](https://mslab.es/projects/SNUG/) |
| ICON | ICON: Implicit Clothed humans Obtained from Normals | CVPR 2022 | -> | [project](https://github.com/YuliangXiu/ICON) |
| TemporalUV | TemporalUV: Capturing Loose Clothing with Temporally Coherent UV Coordinates | CVPR 2022 | [2204.03671](https://arxiv.org/abs/2204.03671) | - |
| True Seams | True Seams:Modeling Seams in Digital Garments | SIGGRAPH 2022 | -> | [project](https://gabrielcirio.gitlab.io/projects/trueseams/trueseams.html) |
| NeuralTailor | NeuralTailor: Reconstructing Sewing Pattern Structures from 3D Point Clouds of Garments | SIGGRAPH 2022 | [2201.13063](https://arxiv.org/abs/2201.13063) | - |
| VirtualBones | Predicting Loose-Fitting Garment Deformations Using Bone-Driven Motion Networks | SIGGRAPH 2022 | -> | [project](http://www.cad.zju.edu.cn/home/jin/SigCloth2022/SigCloth2022.htm) |
| REC-MV | REC-MV: REconstructing 3D Dynamic Cloth from Monocular Videos | CVPR 2023 | -> | [project](https://lingtengqiu.github.io/2023/REC-MV/) |
| HairStep | HairStep: Transfer Synthetic to Real Using Strand and Depth Maps for Single-View 3D Hair Modeling | CVPR 2023 | -> | [project](https://paulyzheng.github.io/research/hairstep/) |
| Get3DHuman | Get3DHuman: Lifting StyleGAN-Human into a 3D Generative Model using Pixel-aligned Reconstruction Priors |ICCV2023| -> |[project](https://x-zhangyang.github.io/2023_Get3DHuman/) |
| ECON | ECON: Explicit Clothed humans Optimized via Normal integration | CVPR 2023 | -> | [project](https://github.com/YuliangXiu/ECON) |
| - | - | - | - | project |
| - | - | - | - | project |
| - | - | - | - | project |


### Agent
| Model | Title | Publication | Paper | Link |
| ----- | ----- | ----------- | ----- | ---- |
| FashionMatrix | Fashion Matrix: Editing Photos by Just Talking | arXiv | -> | [project](https://zheng-chong.github.io/FashionMatrix/) |
| - | - | - | - | project |

### Understanding
#### Vision Language
| Model | Title | Publication | Paper | Link |
| ----- | ----- | ----------- | ----- | ---- |
| FashionViL | Fashion-Focused Vision-and-Language Representation Learning | ECCV2022 | -> | [project](https://github.com/BrandonHanx/mmf) |
| - | - | - | - | project |

#### Segmentation, Recognition
| Model | Title | Publication | Paper | Link |
| ----- | ----- | ----------- | ----- | ---- |
| Fashionformer | Fashionformer: A Simple, Effective and Unified Baseline for Human Fashion Segmentation and Recognition | ECCV2022 | -> | [project](https://github.com/xushilin1/FashionFormer) |
| - | - | - | - | project |

#### Trend Analysis
| Model | Title | Publication | Paper | Link |
| ----- | ----- | ----------- | ----- | ---- |
| POP | POP: Mining POtential Performance of new fashion products via webly cross-modal query expansion | ECCV2022 | -> | [project](https://github.com/HumaticsLAB/POP-Mining-POtential-Performance) |
| - | - | - | - | project |

#### Retrieval
| Model | Title | Publication | Paper | Link |
| ----- | ----- | ----------- | ----- | ---- |
| MODC | Fine-grained Fashion Representation Learning by Online Deep Clustering| ECCV2022 | [paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870019.pdf) | - |
| FashionVLP | FashionVLP: Vision Language Transformer for Fashion Retrieval with Feedback | CVPR2022 | [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Goenka_FashionVLP_Vision_Language_Transformer_for_Fashion_Retrieval_With_Feedback_CVPR_2022_paper.pdf) | - |
| EI-CLIP | EI-CLIP: Entity-aware Interventional Contrastive Learning for E-commerce Cross-modal Retrieval | CVPR2022 | [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_EI-CLIP_Entity-Aware_Interventional_Contrastive_Learning_for_E-Commerce_Cross-Modal_Retrieval_CVPR_2022_paper.pdf) | - |
| - | - | - | - | project |

#### Fashion Compatibility
| Model | Title | Publication | Paper | Link |
| ----- | ----- | ----------- | ----- | ---- |
| Aesthetic 100 (Evaluation Protocol) | How Good Is Aesthetic Ability of a Fashion Model? | CVPR2022 | [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zou_How_Good_Is_Aesthetic_Ability_of_a_Fashion_Model_CVPR_2022_paper.pdf) | [dataset](https://github.com/AemikaChow/AiDLab-fAshIon-Data) |
| - | - | - | - | project |


## Related Events
1. Workshop on Computer Vision for Fashion, Art, and Design [CVFAD 2023](https://sites.google.com/view/cvfad2023/home) [CVFAD 2022](https://sites.google.com/view/cvfad2022/home)
2. Workshop on Multimedia Computing towards Fashion Recommendation [MCFR 22](https://dl.acm.org/doi/abs/10.1145/3503161.3554765)


## Companies
| Name                                                         | Found | Info                                        | News                                                         |
| ------------------------------------------------------------ | ----- | ------------------------------------------- | ------------------------------------------------------------ |
| [CALA](https://ca.la/) | 2016 | fashion supply chain interface that unifies design, development, production, and logistics | [2022.11](https://mp.weixin.qq.com/s/INLwwAqkHzQ2iLq-Oj7ZjA) |
| [Zalando Research](https://research.zalando.com/)            | 2016  | Research                                    | [2023.04 fashion assistant powered by ChatGPT](https://corporate.zalando.com/en/technology/zalando-launch-fashion-assistant-powered-chatgpt) |
| [Vue.ai](https://vue.ai/) | 2016 | Retail AI analysis, AI avatar | - |
| [极睿 infimind](http://infimind.com/)| 2017  | Fashion Product Content           | [2023.11 interview in mandarin](https://www.bilibili.com/video/BV1iu4y1879i/?spm_id_from=333.337.search-card.all.click&vd_source=32f6f61e74ca115cbaca6bd6bb144662)  |
| [知衣 zhiyi](https://www.zhiyitech.cn/)| 2018  | Fashion Design Collaboration, AIGC collaborate with [西湖辰心Scietrain](https://xinchenai.com/)          | [2023.08 Fashion Diffusion](https://mp.weixin.qq.com/s/TnYEc0bl0IasEdHsYmACOA) |
| [LALALAND](https://lalaland.ai/) | 2019 | AI avatar, Fashion Product Content | [2023.08 collaborate with Browzwear-VStitcher](https://mp.weixin.qq.com/s/ZPGR9UhlcaGIeRFUhiG4fA) |
| [PatternedAi](https://www.patterned.ai/) | - | Pattern Design | - |
| [Dsign.Ai](https://app.dsign.ai/) | - | Prints and Patterns Design | - |
| [AIMDE-Symmpix](https://aimde.design/en) | 2023 | Fashion Pattern, 3D | [2023.11 new feature](https://mp.weixin.qq.com/s/priz3aVNByLW40hk2AdxSA) |
| [Weshop](https://www.weshop.com/) | - | AI model & Fashion Product Content | a subsidiary of [MOGU](https://www.mogu.com/)  |
| [Wondershare VirtuLook](https://virtulook.wondershare.com/) | - | AI model & Fashion Product Content | a subsidiary of [wondershare](https://www.wondershare.com/)|
| [Pixelcut](https://www.pixelcut.ai/) | - | AI-powered editing tools(Product Content) | - |
| [CreatorKit](https://creatorkit.com/) | - | AI Product Content, Videos | - |
| [DeepImage](https://deep-image.ai/) | - | AI Product Content | - |
| [Unbound](https://www.unboundml.com/) | - | personal AI business assistant | - |
| [Zeg AI](https://www.zeg.ai/)| - | AI Product Content, Videos, 3D Render | - |
| - | - | - | - |


## Researchers

| Group/Lab/Univ                                              |Researchers |
| ------------------------------------------------------------| -----------|
| [GAP Lab-CUHKSZ](https://gaplab.cuhk.edu.cn/pages/publications) | [Xiaoguang Han](https://scholar.google.com/citations?user=z-rqsR4AAAAJ&hl=en)|
| [HCP-I2 Lab-SYSU](https://www.sysu-hcp.net/publications/index.html) | [Xiaodan Liang](https://scholar.google.com/citations?user=voxznZAAAAAJ&hl=en),[Zhenyu Xie](https://xiezhy6.github.io/)|
| HIT SZ|[Haijun Zhang](https://dl2link.com/#)|
| [AiDlab-PolyU+RCA](https://www.aidlab.hk/en/)|[Calvin WONG](https://research.polyu.edu.hk/en/persons/wai-keung-wong-2),[Xingxing Zou](https://scholar.google.com/citations?user=UhnQA3UAAAAJ&hl=zh-CN)|
| [MMLab-NTU](https://www.mmlab-ntu.com/index.html)|[Ziwei Liu](https://liuziwei7.github.io/index.html)|
| UIUC | [Ranjitha Kumar](http://ranjithakumar.net/)|
| [AImageLab](https://aimagelab.ing.unimore.it/imagelab/)|[Rita Cucchiara](https://scholar.google.com/citations?user=OM3sZEoAAAAJ&hl=en)|
| The University of Utah|[Ziad Al-Halah](https://users.cs.utah.edu/~ziad/)|
| Georgia Tech|[Devi Parikh](https://faculty.cc.gatech.edu/~parikh/)|
| UT Austin|[Kristen Grauman](https://www.cs.utexas.edu/users/grauman/)|
| Cornell|[Kavita Bala](https://www.cs.cornell.edu/~kb/)|

## Industry Reports
| Reports                                              |Consulting Organization | Time |
| ------------------------------------------------------------| -----------| -----------|
| [Outlook for the Global and Chinese Fashion Industry in 2035](https://www.rolandberger.com/zh/Insights/Publications/2035%E5%85%A8%E7%90%83%E5%8F%8A%E4%B8%AD%E5%9B%BD%E6%97%B6%E5%B0%9A%E4%BA%A7%E4%B8%9A%E5%B1%95%E6%9C%9B.html)|Roland Berger|2023.08|
| [The Complete Playbook for Generative AI in Fashion](https://www.businessoffashion.com/case-studies/technology/generative-ai-playbook-machine-learning-emerging-technology/)|Bof|2023.06|
| [Generative AI: Unlocking the future of fashion](https://www.mckinsey.com/industries/retail/our-insights/generative-ai-unlocking-the-future-of-fashion) |McKinsey|2023.03|

## Other FashionAI Resources
1.  [Fashion Datasets](https://github.com/AemikaChow/DATASOURCE)
2. [Cool Fashion Papers](https://github.com/lzhbrian/Cool-Fashion-Papers)
3. [awesome-fashion-ai](https://github.com/ayushidalmia/awesome-fashion-ai)
4. [image-to-image-papers](https://github.com/lzhbrian/image-to-image-papers)
5. [Awesome Virtual Try-on (VTON) Research](https://github.com/minar09/awesome-virtual-try-on#non-clothing-virtual-try-on)
6. [Awesome-pose-transfer](https://github.com/Zhangjinso/Awesome-pose-transfer)
7. [Human Body Reconstruction](https://github.com/chenweikai/Body_Reconstruction_References)

## Other GenAI Resources
1. [Awesome GenAI Tech](https://github.com/hollobit/Awesome-GenAITech#table-of-content)
2. [GAN-Inversion Survey](https://github.com/weihaox/GAN-Inversion#gan-inversion-a-survey)
3. [The Roadmap of Generative AI](https://github.com/SeedV/generative-ai-roadmap)
4. [Multimodal Image Synthesis and Editing: The Generative AI Era](https://github.com/fnzhan/Generative-AI)
5. [awesome-Ai-tools](https://github.com/TRA-Tech/awesome-artificial-intelligence-tools)
