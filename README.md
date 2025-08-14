# Awesome Image Quality Assessment (IQA)
A comprehensive collection of IQA papers, datasets and codes. We also provide PyTorch implementations of mainstream metrics in [IQA-PyTorch](https://github.com/chaofengc/IQA-PyTorch) 

[![toolbox](https://img.shields.io/badge/Toolbox-IQA--PyTorch-critical)](https://github.com/chaofengc/IQA-PyTorch) [![PyPI](https://img.shields.io/pypi/v/pyiqa)](https://pypi.org/project/pyiqa/) ![visitors](https://visitor-badge.laobi.icu/badge?page_id=chaofengc/Awesome-Image-Quality-Assessment) 

> [!TIP]  
> 📚✍️ Feel free to submit a pull request to add a paper you think deserves to be featured in this repository! Your contributions are incredibly appreciated 🙌 and will help make this project even better for everyone!  
> Thank you for your support! 🫶🤗🎉  

- [Awesome Image Quality Assessment (IQA)](#awesome-image-quality-assessment-iqa)
  - [Papers](#papers)
    - [Spatial-Aware IQA](#spatial-aware-iqa)
    - [Unified IQA](#unified-iqa)
    - [Explainable IQA](#explainable-iqa)
    - [AIGC IQA](#aigc-iqa)
    - [No Reference (NR)](#no-reference-nr)
    - [Full Reference (FR)](#full-reference-fr)
    - [Image Aesthetic Assessment](#image-aesthetic-assessment)
    - [Others](#others)
  - [Datasets](#datasets)
    - [IQA datasets](#iqa-datasets)
    - [Perceptual similarity datasets](#perceptual-similarity-datasets)
  
Related Resources:
- [Awesome Image Aesthetic Assessment and Cropping](https://github.com/bcmi/Awesome-Aesthetic-Evaluation-and-Cropping). A curated list of resources including papers, datasets, and relevant links to aesthetic evaluation and cropping.

## Papers

### Spatial-Aware IQA
> Quality assessment with spatial context and local structures 

- `[Eurographics 2024]` [Enhancing image quality prediction with self-supervised visual masking](https://arxiv.org/abs/2305.19858), Uğur et al. [Github](https://github.com/ugurcogalan06/Enhanced-IQM/) | [Project](https://enhancediqm.mpi-inf.mpg.de/) | [Bibtex](./iqa_ref.bib#L1059-L1065)
- `[Arxiv 2024]` [SEAGULL: No-reference Image Quality Assessment for Regions of Interest via Vision-Language Instruction Tuning](https://arxiv.org/abs/2411.10161), Chen et al. [Github](https://github.com/chencn2020/SEAGULL) | [Bibtex](./iqa_ref.bib#L1081-L1089)
- `[ACM MM2024]` [Q-Ground: Image Quality Grounding with Large Multi-modality Models](https://arxiv.org/abs/2407.17035), Chen et al. [Bibtex](./iqa_ref.bib#L1002-L1007) | [Github](https://github.com/Q-Future/Q-Ground)
 
### Unified IQA
> All IQA types unified in a single model

- `[ECCV 2024]` [PromptIQA: Boosting the Performance and Generalization for No-Reference Image Quality Assessment via Prompts](https://arxiv.org/abs/2403.04993), Chen et al. [Bibtex](./iqa_ref.bib#L931-L938)
- `[ICML 2024]` [Q-Align: Teaching LMMs for Visual Scoring via Discrete Text-Defined Levels](https://arxiv.org/abs/2312.17090), Wu et al. [Github](https://github.com/TianheWu/MLLMs-for-IQA) | [Bibtex](./iqa_ref.bib#L867-L874)

### Explainable IQA 
> Human readable IQA, mostly with large language models

- `[Arxiv 2025]` [Q-Insight: Understanding Image Quality via Visual Reinforcement Learning](https://arxiv.org/pdf/2503.22679), Li et al. [Github](https://github.com/lwq20020127/Q-Insight) | [Bibtex](./iqa_ref.bib#L1107-L1112)
- `[TPAMI 2024]` [Q-Bench+: A Benchmark for Multi-modal Foundation Models on Low-level Vision from Single Images to Pairs](https://arxiv.org/abs/2402.07116), Zhang et al. [Github](https://github.com/Q-Future/Q-Bench) | [Bibtex](./iqa_ref.bib#L1044-L1049)
- `[Arxiv 2024]` [VisualCritic: Making LMMs Perceive Visual Quality Like Humans](https://arxiv.org/abs/2403.12806), Huang et al. [Bibtex](./iqa_ref.bib#L940-L947)
- `[ECCV 2024]` [A Comprehensive Study of Multimodal Large Language Models for Image Quality Assessment](https://arxiv.org/abs/2403.10854), Wu et al. [Github]() | [Bibtex](./iqa_ref.bib#L922-L929)
- `[ECCV 2024]` [Towards Open-ended Visual Quality Comparison](https://arxiv.org/abs/2402.16641), Wu et al. [Github](https://github.com/Q-Future/Co-Instruct) | [Bibtex](./iqa_ref.bib#L906-L913)
- `[ECCV 2024]` [Depicting Beyond Scores: Advancing Image Quality Assessment through Multi-modal Language Models](https://arxiv.org/abs/2312.08962), You et al. [Project](https://depictqa.github.io/) | [Bibtex](./iqa_ref.bib#L885-L890)
- `[CVPR 2024]` [Q-Instruct: Improving Low-level Visual Abilities for Multi-modality Foundation Models](https://arxiv.org/abs/2311.06783), Wu et al. [Github](https://github.com/Q-Future/Q-Instruct) | [Bibtex](./iqa_ref.bib#L876-L883)

### AIGC IQA

- ✨`[CVPR 2024 (best paper)]` [Rich Human Feedback for Text-to-Image Generation](https://arxiv.org/abs/2312.10240), Liang et al. [Github](https://github.com/google-research-datasets/richhf-18k) | [Bibtex](./iqa_ref.bib#L1067-L1072)
- `[ICLR 2024]` [Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-level Vision](https://arxiv.org/abs/2309.14181), Wu et al. [Github](https://github.com/Q-Future/Q-Bench) | [Bibtex](./iqa_ref.bib#L833-L838)
- `[ICCV 2023]` [TIFA: Text-to-Image Faithfulness Evaluation with Question Answering](https://arxiv.org/abs/2303.11897), Hu et al. [Github](https://github.com/Yushi-Hu/tifa) | [Bibtex](./iqa_ref.bib#L840-L846) | [Project](https://tifa-benchmark.github.io/)
- `[NeurIPS 2023]` [ImageReward: Learning and Evaluating Human Preferences for Text-to-image Generation](https://arxiv.org/abs/2304.05977), Xu et al. [Github](https://github.com/THUDM/ImageReward) | [Bibtex](./iqa_ref.bib#L817-L822)
- `[ICCV2023]` [Better Aligning Text-to-Image Models with Human Preference](https://arxiv.org/abs/2303.14420), Wu et al. [Github](https://github.com/tgxs002/align_sd) | [Github(HPSv2)](https://github.com/tgxs002/HPSv2) | [Bibtex](./iqa_ref.bib#L804-L809)
- `[NeurIPS 2023]` [Pick-a-Pic: An Open Dataset of User Preferences for Text-to-Image Generation](https://arxiv.org/abs/2305.01569), Yuval et al. [Github](https://github.com/yuvalkirstain/PickScore) | [Bibtex](./iqa_ref.bib#L811-L815)
- `[TCSVT2023]` [A Fine-grained Subjective Perception & Alignment Database for AI Generated Image Quality Assessment](https://arxiv.org/abs/2306.04717), Li et al. [Github](https://github.com/lcysyzxdxc/AGIQA-3k-Database) | [Bibtex](./iqa_ref.bib#L824-L831)

### No Reference (NR)
- `[Arxiv 2024]` [Q-Mamba: On First Exploration of Vision Mamba for Image Quality Assessment](https://arxiv.org/abs/2406.09546), Guan et al. [Bibtex](./iqa_ref.bib#L980-L986)
- `[Arxiv 2024]` [Adaptive Image Quality Assessment via Teaching Large Multimodal Model to Compare](https://arxiv.org/abs/2405.19298), Zhe et al. [Bibtex](./iqa_ref.bib#L964-L971)
- `[Arxiv 2024]` [Quality-aware Image-Text Alignment for Opinion-Unaware Image Quality Assessment](https://arxiv.org/abs/2403.11176), Agnolucci et al. [Github](https://github.com/miccunifi/QualiCLIP) | [Bibtex](./iqa_ref.bib#L950-L955)
- `[ACCV 2024]` [ATTIQA: Generalizable Image Quality Feature Extractor using Attribute-aware Pretraining](https://arxiv.org/abs/2406.01020), Kwon et al. [Bibtex](./iqa_ref.bib#L1091-L1098)
- `[CVPR 2024]` [Blind Image Quality Assessment Based On Geometric Order Learning](https://openaccess.thecvf.com/content/CVPR2024/papers/Shin_Blind_Image_Quality_Assessment_Based_on_Geometric_Order_Learning_CVPR_2024_paper.pdf), Shin et al. [Github](https://github.com/nhshin-mcl/QCN?tab=readme-ov-file) | [Bibtex](./iqa_ref.bib#L1074-L1079)
- `[CVPR 2024]` [Bridging the Synthetic-to-Authentic Gap: Distortion-Guided Unsupervised Domain Adaptation for Blind Image Quality Assessment](https://arxiv.org/abs/2405.04167), Li et al. [Bibtex](./iqa_ref.bib#L956-L961)
- `[CVPR 2024]` [Boosting Image Quality Assessment through Efficient Transformer Adaptation with Local Feature Enhancement
](https://arxiv.org/abs/2308.12001), Xu et al. | [Bibtex](./iqa_ref.bib#L915-L920)
- `[WACV2024]` [ARNIQA: Learning Distortion Manifold for Image Quality Assessment](https://arxiv.org/abs/2310.14918), Agnolucci et al. [Github](https://github.com/miccunifi/ARNIQA) | [Bibtex](./iqa_ref.bib#L858-L865)
- `[TIP2023]` [TOPIQ: A Top-down Approach from Semantics to Distortions for Image Quality Assessment](https://arxiv.org/abs/2308.03060), Chen et al. [Github](https://github.com/chaofengc/IQA-PyTorch) | [Bibtex](./iqa_ref.bib#L892-L897)
- `[ICCV2023]` [Test Time Adaptation for Blind Image Quality Assessment](https://arxiv.org/abs/2307.14735), Roy et al. [Github](https://github.com/Shankhanil006/TTA-IQA) | [Bibtex](./iqa_ref.bib#L798-L804)
- `[CVPR2023]` [Re-IQA: Unsupervised Learning for Image Quality Assessment in the Wild](https://arxiv.org/abs/2304.00451), Saha et al. [Bibtex](./iqa_ref.bib#L791-L796) | [Github](https://github.com/avinabsaha/ReIQA)
- `[CVPR2023]` [Blind Image Quality Assessment via Vision-Language Correspondence: A Multitask Learning Perspective](https://arxiv.org/abs/2303.14968), Zhang et al. [Github](https://github.com/zwx8981/LIQE) | [Bibtex](./iqa_ref.bib#L770-L775)
- `[CVPR2023]` [Quality-aware Pre-trained Models for Blind Image Quality Assessment](https://arxiv.org/abs/2303.00521), Zhao et al. [Bibtex](./iqa_ref.bib#L763-L768)

- `[AAAI2023]` [Exploring CLIP for Assessing the Look and Feel of Images](https://arxiv.org/abs/2207.12396), Wang et al. [Github](https://github.com/IceClear/CLIP-IQA) | [Bibtex](./iqa_ref.bib#L745-L750)
- `[AAAI2023]` [Data-Efficient Image Quality Assessment with Attention-Panel Decoder](https://arxiv.org/abs/2304.04952), Qin et al. [Github](https://github.com/narthchin/DEIQT) | [Bibtex](./iqa_ref.bib#L745-L750)
- `[TPAMI2022]` [Continual Learning for Blind Image Quality Assessment
](https://arxiv.org/abs/2102.09717), Zhang et al. [Github](https://github.com/zwx8981/BIQA_CL) | [Bibtex](./iqa_ref.bib#L738-L743)
- `[TIP2022]` [No-Reference Image Quality Assessment by Hallucinating Pristine Features](https://arxiv.org/abs/2108.04165), Chen et al. [Github](https://github.com/Baoliang93/FPR) | [Bibtex](./iqa_ref.bib#L848-L856)
- `[TIP2022]` [VCRNet: Visual Compensation Restoration Network for No-Reference Image Quality Assessment](https://ieeexplore.ieee.org/document/9694502), Pan et al. [Github](https://github.com/NUIST-Videocoding/VCRNet) | [Bibtex](./iqa_ref.bib#L752-L761)
- `[TMM2022]` [GraphIQA: Learning Distortion Graph Representations for Blind Image Quality Assessment](https://arxiv.org/abs/2103.07666), Sun et al. [Github](https://github.com/geekyutao/GraphIQA) | [Bibtex](./iqa_ref.bib#L701-L707)
- `[CVPR2021]` [Troubleshooting Blind Image Quality Models in the Wild](https://arxiv.org/abs/2105.06747), Wang et al. [Github](https://github.com/wangzhihua520/troubleshooting_BIQA) | [Bibtex](./iqa_ref.bib#L716-L722)

- `[CVPRW2022]` [MANIQA](https://arxiv.org/abs/2204.08958), Yang et al. [Github](https://github.com/IIGROUP/MANIQA) | [Bibtex](./iqa_ref.bib#L1-L1) | Transformer, multi-dimension attention, dual branch
- `[WACV2022]` [TReS](https://arxiv.org/abs/2108.06858), Golestaneh et al. [Github](https://github.com/isalirezag/TReS) | [Bibtex](./iqa_ref.bib#L1-L1) | Transformer, relative ranking, self-consistency
- `[BMVC2021]` [KonIQ++](https://www.bmvc2021-virtualconference.com/assets/papers/0868.pdf), Hosu et al. [Github](https://github.com/SSL92/koniqplusplus) | [Bibtex](./iqa_ref.bib#L1-L1) | Multi-task with distortion prediction
- `[ICCV2021]` [MUSIQ](https://arxiv.org/abs/2108.05997), Ke et al. [Github](https://github.com/google-research/google-research/tree/master/musiq) | [Bibtex](./iqa_ref.bib#L1-L1) | Multi-scale, transformer, Aspect Ratio Preserved (ARP) resizing
- `[ICCV2021]` [CKDN](https://arxiv.org/abs/2108.07948), Zhang et al. [Github](https://github.com/researchmm/CKDN) | [Bibtex](./iqa_ref.bib#L1-L1) | Degraded reference, Conditional knowledge distillation
- `[CVPR2020]` [HyperIQA](https://openaccess.thecvf.com/content_CVPR_2020/papers/Su_Blindly_Assess_Image_Quality_in_the_Wild_Guided_by_a_CVPR_2020_paper.pdf), Su et al. [Github](https://github.com/SSL92/hyperIQA) | [Bibtex](./iqa_ref.bib#L1-L1) | Content-aware hyper network
- `[CVPR2020]` [Meta-IQA](https://arxiv.org/abs/2004.05508), Zhu et al. [Github](https://github.com/zhuhancheng/MetaIQA) | [Bibtex](./iqa_ref.bib#L1-L1) | Meta-learning
- `[ECCV2020]` [GIQA](https://arxiv.org/abs/2003.08932), Gu et al. [Github](https://github.com/cientgu/GIQA) | [Bibtex](./iqa_ref.bib#L1-L1) | Generated image
- `[2018 PIRM Challenge]` [PI](https://arxiv.org/abs/1809.07517), Blau et al. [Github](https://github.com/roimehrez/PIRM2018) | [Bibtex](./iqa_ref.bib#L1-L1) | 1/2 * (NIQE + (10 - NRQM))
- `[CVPR2018]` [HIQA](https://arxiv.org/abs/1804.01681), Lin et al. [Project](https://kwanyeelin.github.io/projects/HIQA/HIQA.html) | [Bibtex](./iqa_ref.bib#L1-L1) | Hallucinated reference
- `[CVPR2018]` [BPSQM](https://arxiv.org/pdf/1805.08493v1.pdf), Ying et al. [Bibtex](./iqa_ref.bib#L1-L1) | Pixel-wise quality map
- `[ICCV2017]` [RankIQA](https://arxiv.org/abs/1707.08347), Liu et al. [Github](https://github.com/xialeiliu/RankIQA) | [Bibtex](./iqa_ref.bib#L1-L1) | Pretrain on synthetically ranked data
- `[CVPR2014]` [CNNIQA](https://openaccess.thecvf.com/content_cvpr_2014/papers/Kang_Convolutional_Neural_Networks_2014_CVPR_paper.pdf), Kang et al. [Github](https://github.com/lidq92/CNNIQA) | [Bibtex](./iqa_ref.bib#L1-L1) | First CNN-based NR-IQA
- `[TIP2021]` [UNIQUE](https://arxiv.org/abs/2005.13983), Zhang et al. [Github](https://github.com/zwx8981/UNIQUE) | [Bibtex](./iqa_ref.bib#L1-L1) | Combine synthetic and authentic image pairs
- `[TCSVT2020]` [DBCNN](https://arxiv.org/pdf/1907.02665.pdf), Zhang et al. [Github](https://github.com/zwx8981/DBCNN-PyTorch) | [Bibtex](./iqa_ref.bib#L1-L1) | Two branches for synthetic and authentic distortions
- `[TMM2019]` [SFA](http://www.jdl.link/doc/2011/20191226_08489929.pdf), Li et al. [Github](https://github.com/lidq92/SFA) | [Bibtex](./iqa_ref.bib#L1-L1) | Aggregate ResNet50 features of multiple cropped patches
- `[TIP2019]` [PQR](https://arxiv.org/abs/1708.08190), Zeng et al. [Github](https://github.com/HuiZeng/Unified_IAA) | [Bibtex](./iqa_ref.bib#L1-L1) | Unify different type of aesthetic labels
- `[TIP2018]` [WaDIQaM (deepIQA)](https://arxiv.org/abs/1612.01697), Bosse et al. [Github](https://github.com/lidq92/WaDIQaM) | [Bibtex](./iqa_ref.bib#L1-L1) | Weighted average of patch qualities, shared FR/NR models
- `[TIP2018]` [NIMA](https://ieeexplore.ieee.org/ielx7/83/8347140/08352823.pdf), Talebi et al. [Github](https://github.com/kentsyx/Neural-IMage-Assessment) | [Bibtex](./iqa_ref.bib#L1-L1) | Squared EMD loss
- `[TIP2017]` [MEON](https://ece.uwaterloo.ca/~z70wang/publications/TIP_E2E_BIQA.pdf), Ma et al. [Bibtex](./iqa_ref.bib#L1-L1) | Multi-task: distortion learning and quality prediction
- `[TIP2017]` [dipIQ](https://arxiv.org/abs/1904.06505), Ma et al. [Project](https://ece.uwaterloo.ca/~k29ma/codes/dipIQ.rar) | [Bibtex](./iqa_ref.bib#L1-L1) | Similar to RankIQA
- `[CVIU2017]` [NRQM (Ma)](https://arxiv.org/abs/1612.05890), Ma et al. [Project](https://sites.google.com/site/chaoma99/sr-metric) | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional, Super resolution
- `[JoV2017]` [FRIQUEE](https://arxiv.org/abs/1609.04757), Ghadiyaram et al. [Github](https://github.com/utlive/FRIQUEE) | [Bibtex](./iqa_ref.bib#L1-L1) | Authentically Distorted, Bag of Features
- `[TIP2016]` [HOSA](https://ieeexplore.ieee.org/document/7501619), Xu et al. [Project](https://ieeexplore.ieee.org/document/7501619) | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional
- `[TIP2015]` [ILNIQE](https://live.ece.utexas.edu/publications/2015/zhang2015feature.pdf), Zhang et al. [Project](http://www4.comp.polyu.edu.hk/~cslzhang/IQA/ILNIQE/ILNIQE.htm) | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional
- `[TIP2012]` [BRISQUE](https://live.ece.utexas.edu/publications/2012/TIP%20BRISQUE.pdf), Mittal et al. [Github](https://github.com/utlive/BRISQUE) | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional
- `[TIP2012]` [BLIINDS-II](https://live.ece.utexas.edu/publications/2012/saad_2012_tip.pdf), Saad et al. [Github](https://github.com/utlive/BLIINDS2) | [Bibtex](./iqa_ref.bib#L1-L1)
- `[CVPR2012]` [CORNIA](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.359.7510&rep=rep1&type=pdf), Ye et al. [Project](https://github.com/HuiZeng/BIQA_Toolbox) | [Bibtex](./iqa_ref.bib#L1-L1) | Codebook Representation
- `[SPL2012]` [NIQE](https://live.ece.utexas.edu/publications/2013/mittal2013.pdf), Mittal et al. [Github](https://github.com/utlive/niqe) | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional
- `[TIP2011]` [DIIVINE](https://www.imaging.utk.edu/research/wcho/references/2011%20TIP%20BLINDS2.pdf), Moorthy et al. [Github](https://github.com/utlive/DIIVINE) | [Bibtex](./iqa_ref.bib#L1-L1)

### Full Reference (FR)


- `[ECCV2022]` [Shift-tolerant Perceptual Similarity Metric](https://arxiv.org/abs/2211.052152207.13686), Ghildyal et al. [Github](https://github.com/abhijay9/ShiftTolerant-LPIPS) | [Bibtex](./iqa_ref.bib#L731-L736)
- `[BMVC2022]` [Content-Diverse Comparisons improve IQA](https://arxiv.org/abs/2211.05215), Thong et al. [Bibtex](./iqa_ref.bib#L724-L729)
- `[ACM MM2022]` [Quality Assessment of Image Super-Resolution: Balancing Deterministic and Statistical Fidelity](https://arxiv.org/abs/2207.08689), Zhou et al. [Github](https://github.com/weizhou-geek/SRIF) | [Bibtex](./iqa_ref.bib#L709-L714)

- `[CVPR2022 NTIRE workshop]` [AHIQ](https://arxiv.org/abs/2204.10485), Lao et al. [Github](https://github.com/IIGROUP/AHIQ) | [Bibtex](./iqa_ref.bib#L1-L1) | Attention, Transformer
- `[CVPR2022]` [JSPL](https://arxiv.org/abs/2204.08763), Cao et al. [Github](https://github.com/happycaoyue/JSPL) | [Bibtex](./iqa_ref.bib#L1-L1) | semi-supervised and positive-unlabeled (PU) learning
- `[AAAI2022]` [CVRKD](https://arxiv.org/abs/2202.13123), Yin et al. [Github](https://github.com/guanghaoyin/CVRKD-IQA) | [Bibtex](./iqa_ref.bib#L1-L1) | Non-Aligned content reference, knowledge distillation
- `[CVPRW2021]` [IQT](https://arxiv.org/abs/2104.14730), Cheon et al. [Github](https://github.com/anse3832/IQT) | [Bibtex](./iqa_ref.bib#L1-L1) | Transformer
- `[ACMM2021]` [A-DISTS](https://arxiv.org/abs/2110.08521), Ding et al. [Github](https://github.com/dingkeyan93/A-DISTS) | [Bibtex](./iqa_ref.bib#L1-L1)
- `[TPAMI2021]` [DISTS](https://arxiv.org/abs/2004.07728), Ding et al. [Github](https://github.com/dingkeyan93/DISTS) | [Bibtex](./iqa_ref.bib#L1-L1)
- `[CVPR2018]` [LPIPS](https://arxiv.org/abs/1801.03924), Zhang et al. [Project](https://richzhang.github.io/PerceptualSimilarity/) | [Bibtex](./iqa_ref.bib#L1-L1) | Perceptual similarity, Pairwise Preference
- `[CVPR2018]` [PieAPP](https://arxiv.org/abs/1806.02067), Prashnani et al. [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | [Bibtex](./iqa_ref.bib#L1-L1) | Perceptual similarity, Pairwise Preference
- `[TIP2018]` [WaDIQaM](https://arxiv.org/abs/1612.01697), Bosse et al. [Github](https://github.com/lidq92/WaDIQaM) | [Bibtex](./iqa_ref.bib#L1-L1)
- `[TCSVT2020]` [JND-SalCAR](https://arxiv.org/abs/1902.05316), Seo et al. [Bibtex](./iqa_ref.bib#L1-L1) | JND (Just-Noticeable-Difference)
- `[TIP2019]` [QADS](https://nottingham-repository.worktribe.com/preview/1589753/Visual%20IEEE-TIP-2019.pdf), Min et al. [Project](http://www.vista.ac.cn/super-resolution/) | [Bibtex](./iqa_ref.bib#L1-L1) | Super-resolution
- `[TIP2011]` [FSIM](https://sse.tongji.edu.cn/linzhang/IQA/FSIM/Files/Fsim%20a%20feature%20similarity%20index%20for%20image%20quality%20assessment.pdf), Zhang et al. [Project](https://www4.comp.polyu.edu.hk/~cslzhang/IQA/FSIM/FSIM.htm) | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional
- `[TIP2006]` [VIF/IFC](https://live.ece.utexas.edu/publications/2004/hrs_ieeetip_2004_imginfo.pdf), Sheikh et al. [Project](https://live.ece.utexas.edu/research/Quality/VIF.htm) | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional
- `[MS-SSIM]` [MS-SSIM](https://ece.uwaterloo.ca/~z70wang/publications/msssim.pdf), Wang et al. [Project](https://ece.uwaterloo.ca/~z70wang/research/ssim/) | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional
- `[TIP2004]` [SSIM](https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf), Wang et al. [Project](https://ece.uwaterloo.ca/~z70wang/research/ssim/) | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional
- `[Traditional]` PSNR | [Bibtex](./iqa_ref.bib#L1-L1) | Traditional

### Image Aesthetic Assessment 

- `[CVPR2025]` [Charm: The Missing Piece in ViT fine-tuning for Image Aesthetic Assessment](https://arxiv.org/abs/2504.02522), Behrad et al. [Github](https://github.com/FBehrad/Charm) | [Bibtex](./iqa_ref.bib#L1114-L1119)
- `[ACMMM 2024]` [AesExpert: Towards Multi-modality Foundation Model for Image Aesthetics Perception](https://arxiv.org/abs/2404.09624), Huang et al. [Project](https://yipoh.github.io/aes-expert/) | [Github](https://github.com/yipoh/AesExpert) | [Bibtex](./iqa_ref.bib#L1037-L1042)
- `[Arxiv 2024]` [AesBench: An Expert Benchmark for Multimodal Large Language Models on Image Aesthetics Perception](https://arxiv.org/abs/2401.08276), Huang et al. [Github](https://github.com/yipoh/AesBench) | [Bibtex](./iqa_ref.bib#L899-L904)
- `[ECCV2024]` [Scaling Up Personalized Aesthetic Assessment via Task Vector Arithmetic](https://arxiv.org/abs/2407.07176), Yun et al. [Bibtex](./iqa_ref.bib#L988-L993) | [Project](https://yeolj00.github.io/personal-projects/personalized-aesthetics/)
- `[CVPR2023]` [VILA: Learning Image Aesthetics from User Comments with Vision-Language Pretraining](https://arxiv.org/abs/2303.14302), Ke et al. [Bibtex](./iqa_ref.bib#L784-L789)
- `[CVPR2023]` [Towards Artistic Image Aesthetics Assessment: a Large-scale Dataset and a New Method](https://arxiv.org/abs/2303.14968), Yi et al. [Github](https://github.com/Dreemurr-T/BAID) | [Bibtex](./iqa_ref.bib#L777-L782)

### Others 

#### Image Intrinsic Scale Assessment (IISA)
> Aims to predict the Image Intrinsic Scale, _i.e._ the scale at which an image shows the best quality

- `[ICCV 2025]` [Image Intrinsoc Scale Assessment: Bridging the Gap Between Quality and Resolution](https://arxiv.org/abs/2502.06476), Hosu et al. [Bibtex](./iqa_ref.bib#L1100-L1105) | [Github](https://github.com/SonyResearch/IISA)

#### Color IQA

- `[ECCV 2024]` [Multiscale Sliced Wasserstein Distances as Perceptual Color Difference Measures](https://arxiv.org/abs/2407.10181), He et al. [Github](https://github.com/real-hjq/MS-SWD) | [Bibtex](./iqa_ref.bib#L1051-L1058)
- `[CVPR 2023]` [Learning a Deep Color Difference Metric for Photographic Images](https://arxiv.org/abs/2303.14964), Chen et al. [Github](https://github.com/haoychen3/CD-Flow) | [Bibtex](./iqa_ref.bib#L1060-L1065)

#### Face IQA

- `[CVPR2024]` [DSL-FIQA: Assessing Facial Image Quality via Dual-Set Degradation Learning and Landmark-Guided Transformer](https://arxiv.org/abs/2406.09622), Chen et al. [Bibtex](./iqa_ref.bib#L973-L978) | [Project](https://dsl-fiqa.github.io/)

#### 360° Image (Omnidirectional Image) IQA
- `[NeurIPS 2023]` [Assessor360: Multi-sequence Network for Blind Omnidirectional Image Quality Assessment
](https://arxiv.org/abs/2305.10983), Wu et al. [Bibtex](./iqa_ref.bib#L995-L1000) | [Github](https://github.com/TianheWu/Assessor360) 

#### Egocentric Spatial Images (Apple Vision Pro)

- `[Arxiv 2024]` [ESIQA: Perceptual Quality Assessment of Vision-Pro-based
Egocentric Spatial Images](https://arxiv.org/abs/2407.21363), Zhu et al. [Bibtex](./iqa_ref.bib#L1009-L1016) | [Github](https://github.com/IntMeGroup/ESIQA)

#### Adversarial Attack on IQA

- `[Arxiv 2024]` [Guardians of Image Quality: Benchmarking Defenses Against Adversarial Attacks on Image Quality Metrics](https://arxiv.org/abs/2408.01541), Gushchin et al. [Bibtex](./iqa_ref.bib#L1027-L1035) | [Github](https://github.com/msu-video-group/adversarial-defenses-for-iqa) | [Project](https://videoprocessing.ai/benchmarks/iqa-defenses.html)
- `[NeurIPS 2022]` [Perceptual Attacks of No-Reference Image Quality Models with Human-in-the-Loop](https://arxiv.org/abs/2210.00933), Zhang et al. [Bibtex](./iqa_ref.bib#L1018-L1025) | [Github](https://github.com/zwx8981/PerceptualAttack_BIQA)

#### IQA Losses

- `[ACMM2020]` [NiNLoss: Norm-in-Norm Loss](https://arxiv.org/abs/2008.03889), Li et al. [Github](https://github.com/lidq92/LinearityIQA) | [Bibtex](./iqa_ref.bib#L1-L1) | Norm-in-Norm Loss

## Datasets 

### IQA datasets

- `[ECCVW2024]` [UHD-IQA](https://arxiv.org/abs/2406.17472), Seitzer et al. [Project](https://database.mmsp-kn.de/uhd-iqa-benchmark-database.html) | [Bibtex](./iqa_ref.bib#L1-L1) | 6k (~3840x2160) images, 20 ratings per image
- `[CVPR2020]` [PaQ-2-PiQ](https://arxiv.org/abs/1912.10088), Ying et al. [Github](https://github.com/baidut/PaQ-2-PiQ) | [Bibtex](./iqa_ref.bib#L1-L1) | 40k images, 120k patches, 4M annotations
- `[CVPR2020]` [SPAQ](https://openaccess.thecvf.com/content_CVPR_2020/html/Fang_Perceptual_Quality_Assessment_of_Smartphone_Photography_CVPR_2020_paper.html), Fang et al. [Github](https://github.com/h4nwei/SPAQ) | [Bibtex](./iqa_ref.bib#L1-L1) | 11k smartphone images
- `[TIP2020]` [KonIQ-10k](https://arxiv.org/abs/1910.06180), Hosu et al. [Project](http://database.mmsp-kn.de/koniq-10k-database.html) | [Bibtex](./iqa_ref.bib#L1-L1) | 10k from YFCC100M, 1.2M annotations
- `[ECCV2016]` [AADB](https://arxiv.org/abs/1606.01621v2), Kong et al. [Github](https://github.com/aimerykong/deepImageAestheticsAnalysis) | [Bibtex](./iqa_ref.bib#L1-L1) | 10k images, 11 attributes
- `[TIP2016]` [CLIVE](https://arxiv.org/abs/1511.02919), Ghadiyaram et al. [Project](https://live.ece.utexas.edu/research/ChallengeDB/index.html) | [Bibtex](./iqa_ref.bib#L1-L1) | 1200 images, 350k annotations
- `[CVPR2012]` [AVA](http://refbase.cvc.uab.es/files/MMP2012a.pdf), Murray et al. [Project](http://www.lucamarchesotti.com/) | [Bibtex](./iqa_ref.bib#L1-L1) | 250k images (60 categories)
- `[ECCV2020]` [PIPAL](https://arxiv.org/abs/2007.12142), Jinjin et al. [Project](https://www.jasongt.com/projectpages/pipal.html) | [Bibtex](./iqa_ref.bib#L1-L1) | 250 images, 1.13M annotations
- `[arXiv]` [KADIS-700k](https://arxiv.org/abs/2001.08113), Lin et al. [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | [Bibtex](./iqa_ref.bib#L1-L1) | 140k pristine / 700k distorted, 30 ratings per image
- `[QoMEX2019]` [KADID-10k](https://ieeexplore.ieee.org/document/8743252), Lin et al. [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | [Bibtex](./iqa_ref.bib#L1-L1) | 81 pristine images, 10k distortions
- `[TIP2017]` [Waterloo-Exp](https://ece.uwaterloo.ca/~k29ma/papers/17_TIP_EXPLORATION.pdf), Ma et al. [Project](https://ece.uwaterloo.ca/~k29ma/exploration/) | [Bibtex](./iqa_ref.bib#L1-L1) | 4744 images, 94k distortions
- `[PR2017]` [MDID](https://daneshyari.com/article/preview/533080.pdf), Sun et al. [Bibtex](./iqa_ref.bib#L1-L1) | 20 pristine images, 1600 distortions
- `[SP2015]` [TID2013](http://www.ponomarenko.info/papers/euvip_tid2013.pdf), Ponomarenko et al. [Project](http://www.ponomarenko.info/tid2013.htm) | [Bibtex](./iqa_ref.bib#L1-L1) | 25 images, 3000 distortions
- `[ACSSC2012]` [LIVEMD](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.298.9133&rep=rep1&type=pdf), Jayaraman et al. [Project](https://live.ece.utexas.edu/research/Quality/live_multidistortedimage.html) | [Bibtex](./iqa_ref.bib#L1-L1) | 15 pristine images with successive distortions
- `[Journal of Electronic Imaging 2010]` [CSIQ](https://www.researchgate.net/profile/Damon-Chandler/publication/220050520_Most_apparent_distortion_Full-reference_image_quality_assessment_and_the_role_of_strategy/links/5629cd1c08ae518e347e1445/Most-apparent-distortion-Full-reference-image-quality-assessment-and-the-role-of-strategy.pdf), Larson et al. [Bibtex](./iqa_ref.bib#L1-L1) | 30 images, 866 distortions
- `[2009]` [TID2008](http://www.ponomarenko.info/papers/mre2009tid.pdf), Ponomarenko et al. [Project](http://www.ponomarenko.info/tid2008.htm) | [Bibtex](./iqa_ref.bib#L1-L1) | 25 images, 1700 distortions
- `[TIP2006]` [LIVE IQA](https://live.ece.utexas.edu/publications/2006/hrs-transIP-06.pdf), Sheikh et al. [Project](https://live.ece.utexas.edu/research/Quality/subjective.htm) | [Bibtex](./iqa_ref.bib#L1-L1) | 29 images, 780 synthetic distortions
- `[2005]` [IVC](http://hal.univ-nantes.fr/hal-00580755/), Le Callet et al. [Bibtex](./iqa_ref.bib#L1-L1) | 10 images, 185 distortions

### Perceptual similarity datasets

- `[CVPR2018]` [BAPPS(LPIPS)](https://arxiv.org/abs/1801.03924), Zhang et al. [Project](https://richzhang.github.io/PerceptualSimilarity/) | [Bibtex](./iqa_ref.bib#L1-L1) | 187.7k images, 484k annotations
- `[CVPR2018]` [PieAPP](https://arxiv.org/abs/1806.02067), Prashnani et al. [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | [Bibtex](./iqa_ref.bib#L1-L1) | 200 images, 2.3M annotations