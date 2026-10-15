# Awesome Image Quality Assessment (IQA)
A comprehensive collection of IQA papers, datasets and codes. We also provide PyTorch implementations of mainstream metrics in [IQA-PyTorch](https://github.com/chaofengc/IQA-PyTorch) 

[![toolbox](https://img.shields.io/badge/Toolbox-IQA--PyTorch-critical)](https://github.com/chaofengc/IQA-PyTorch) [![PyPI](https://img.shields.io/pypi/v/pyiqa)](https://pypi.org/project/pyiqa/) ![visitors](https://visitor-badge.laobi.icu/badge?page_id=chaofengc/Awesome-Image-Quality-Assessment) 

> [!TIP]  
> 📚✍️ Feel free to submit a pull request to add a paper you think deserves to be featured in this repository! Your contributions are incredibly appreciated 🙌 and will help make this project even better for everyone!  
> Thank you for your support! 🫶🤗🎉  

- [Papers](#papers)
  - [Agentic IQA](#agentic-iqa)
  - [Spatial-Aware IQA](#spatial-aware-iqa)
  - [Unified IQA](#unified-iqa)
  - [Explainable IQA](#explainable-iqa)
  - [AIGC IQA](#aigc-iqa)
  - [Image Aesthetic Assessment](#image-aesthetic-assessment)
  - [No Reference (NR)](#no-reference-nr)
  - [Full Reference (FR)](#full-reference-fr)
  - [Others](#others)
- [Datasets](#datasets)
  - [IQA datasets](#iqa-datasets)
  - [Perceptual similarity datasets](#perceptual-similarity-datasets)
  
Related Resources:
- [Awesome Image Aesthetic Assessment and Cropping](https://github.com/bcmi/Awesome-Aesthetic-Evaluation-and-Cropping). A curated list of resources including papers, datasets, and relevant links to aesthetic evaluation and cropping.
- [Image Quality Assessment Benchmark](https://github.com/weizhou-geek/Image-Quality-Assessment-Benchmark). Benchmark datasets and evaluation code for IQA.
- [Recent Image Quality Related Papers](https://github.com/weizhou-geek/Recent-Image-Quality-Related-Papers). A collection of recent papers related to image quality.
- [Awesome Evaluation of Visual Generation](https://github.com/ziqihuangg/Awesome-Evaluation-of-Visual-Generation). A curated list of resources for evaluation of visual generation.

## Papers

### Agentic IQA
> Agentic methods that use visual evidence and specialist tools for image and video quality assessment

- `[Arxiv 2026]` [PACE: An Evolutionary Agentic Approach for Open-ended Image Quality Perception](https://arxiv.org/abs/2609.22942), Tang et al. [Github](https://github.com/2kxx/PACE) | [Bibtex](./iqa_ref.bib#L1359-L1367)
- `[CVPR 2026]` [RL-ScanIQA: Reinforcement-Learned Scanpaths for Blind 360° Image Quality Assessment](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_RL-ScanIQA_Reinforcement-Learned_Scanpaths_for_Blind_360deg_Image_Quality_Assessment_CVPR_2026_paper.html), Wang et al. [Github (coming soon)](https://github.com/wangyuji1/RLScanIQA) | [Bibtex](./iqa_ref.bib#L1369-L1375)
- `[Arxiv 2025]` [Q-Router: Agentic Video Quality Assessment with Expert Model Routing and Artifact Localization](https://arxiv.org/abs/2510.08789), Xing et al. | [Bibtex](./iqa_ref.bib#L1377-L1385)
- `[ICLR 2026]` [AgenticIQA: An Agentic Framework for Adaptive and Interpretable Image Quality Assessment](https://arxiv.org/abs/2509.26006), Zhu et al. [Project](https://agenticiqa.github.io/) | [Bibtex](./iqa_ref.bib#L1334-L1339)
- `[NeurIPS 2026]` [Q-Probe: Scaling Image Quality Assessment to High Resolution via Context-Aware Agentic Probing](https://arxiv.org/abs/2601.15356), Li et al. | [Bibtex](./iqa_ref.bib#L1341-L1346)
- `[NeurIPS 2026]` [Tool-IQA: Augmenting Image Quality Assessment with Simple Tools](https://arxiv.org/abs/2606.16082), Qin et al. [Github (inference code and weights; training pending)](https://github.com/narthchin/Tool-IQA) | [Bibtex](./iqa_ref.bib#L1348-L1357)
- `[ECCV 2026]` [IQA-T1: Tool-based Visual Evidence Reasoning for Image Quality Assessment](https://arxiv.org/abs/2607.12375), Wu et al. [Github](https://github.com/zibuyu-02/IQA-T1) | [Bibtex](./iqa_ref.bib#L1327-L1332)
- `[ECCV 2026]` [Zoom-IQA: Image Quality Assessment with Reliable Region-Aware Reasoning](https://arxiv.org/abs/2601.02918), Liang et al. [Github](https://github.com/EthanLiang99/Zoom-IQA) | [Bibtex](./iqa_ref.bib#L1192-L1197)

### Spatial-Aware IQA
> Quality assessment with spatial context and local structures 

- `[Arxiv 2026]` [Where, What, Why, and Importance: Structured Defect Grounding for Text-to-Image Feedback](https://arxiv.org/abs/2606.06113), Zhang et al. [Github](https://github.com/nianbai006/SDG) | [Bibtex](./iqa_ref.bib#L1403-L1411)
- `[ICLR 2026]` [Grounding-IQA: Grounding Multimodal Language Model for Image Quality Assessment](https://arxiv.org/abs/2411.17237), Chen et al. [Github](https://github.com/zhengchen1999/Grounding-IQA) (partial release) | [Bibtex](./iqa_ref.bib#L1168-L1175)
- `[Eurographics 2024]` [Enhancing image quality prediction with self-supervised visual masking](https://arxiv.org/abs/2305.19858), Uğur et al. [Github](https://github.com/ugurcogalan06/Enhanced-IQM/) | [Project](https://enhancediqm.mpi-inf.mpg.de/) | [Bibtex](./iqa_ref.bib#L1154-L1159)
- `[Arxiv 2024]` [SEAGULL: No-reference Image Quality Assessment for Regions of Interest via Vision-Language Instruction Tuning](https://arxiv.org/abs/2411.10161), Chen et al. [Github](https://github.com/chencn2020/SEAGULL) | [Bibtex](./iqa_ref.bib#L1112-L1120)
- `[ACM MM 2024 (Oral)]` [Q-Ground: Image Quality Grounding with Large Multi-modality Models](https://arxiv.org/abs/2407.17035), Chen et al. [Bibtex](./iqa_ref.bib#L1026-L1033) | [Github](https://github.com/Q-Future/Q-Ground)
 
### Unified IQA
> All IQA types unified in a single model

- `[Arxiv 2025]` [UniPercept: Towards Unified Perceptual-Level Image Understanding across Aesthetics, Quality, Structure, and Texture](https://arxiv.org/abs/2512.21675), et al. [Github](https://github.com/thunderbolt215/UniPercept) | [Bibtex](./iqa_ref.bib#L1177-L1182)
- `[ECCV 2024]` [PromptIQA: Boosting the Performance and Generalization for No-Reference Image Quality Assessment via Prompts](https://arxiv.org/abs/2403.04993), Chen et al. [Github](https://github.com/chencn2020/PromptIQA) | [Bibtex](./iqa_ref.bib#L948-L954)
- `[ICML 2024]` [Q-Align: Teaching LMMs for Visual Scoring via Discrete Text-Defined Levels](https://arxiv.org/abs/2312.17090), Wu et al. [Github](https://github.com/Q-Future/Q-Align) | [Bibtex](./iqa_ref.bib#L871-L876)

### Explainable IQA 
> Human readable IQA, mostly with large language models

- ✨`[CVPR 2026]` [Seeing Beyond 8bits: Subjective and Objective Quality Assessment of HDR-UGC Videos](https://arxiv.org/abs/2603.00938), Saini et al. [Github](https://github.com/shreshthsaini/Beyond8Bits) | [Bibtex](./iqa_ref.bib#L1396-L1401)
- ✨`[ICLR 2026]` [Panoptic Pairwise Distortion Graph](https://arxiv.org/pdf/2604.11004), Janjua et al. [Github](https://github.com/AISmartPerception/distortion-graphs) | [Bibtex](./iqa_ref.bib#L1310-L1315)
- `[Arxiv 2026]` [MR-IQA: A Unified Margin View of Regression and Ranking for Blind Image Quality Assessment](https://arxiv.org/abs/2606.29760), Li et al. [Github](https://github.com/RobinY99/MR-IQA) | [Bibtex](./iqa_ref.bib#L1317-L1325)
- `[Arxiv 2026]` [Q-Hawkeye: Reliable Visual Policy Optimization for Image Quality Assessment](https://arxiv.org/abs/2601.22920), Xie et al. [Github (training code; inference pending)](https://github.com/aba122/Q-Hawkeye) | [Bibtex](./iqa_ref.bib#L1199-L1204)
- `[Arxiv 2026]` [QualiRAG: Retrieval-Augmented Generation for Visual Quality Understanding](https://arxiv.org/abs/2601.18195), Cao et al. [Github](https://github.com/clh124/QualiRAG) | [Bibtex](./iqa_ref.bib#L1206-L1211)
- ✨`[ICLR 2026 (Oral)]` [Reasoning as Representation: Rethinking Visual Reinforcement Learning in Image Quality Assessment](https://arxiv.org/abs/2510.11369), Zhao et al. [Github](https://github.com/xuanyuzhang21/RALI) | [Bibtex](./iqa_ref.bib#L1303-L1308)
- ✨`[NeurIPS 2025 (Spotlight)]` [VisualQuality-R1: Reasoning-Induced Image Quality Assessment via Reinforcement Learning to Rank](https://arxiv.org/abs/2505.14460), Wu et al. [Github](https://github.com/TianheWu/VisualQuality-R1) | [Bibtex](./iqa_ref.bib#L1285-L1290)
- `[ICLR 2026]` [Self-Evolving Vision-Language Models for Image Quality Assessment via Voting and Ranking](https://arxiv.org/abs/2509.25787), Wen et al. [Github](https://github.com/bytedance/EvoQuality) | [Bibtex](./iqa_ref.bib#L1220-L1227)
- `[Arxiv 2025]` [Next Token Is Enough: Realistic Image Quality and Aesthetic Scoring with Multimodal Large Language Model](https://arxiv.org/pdf/2503.06141), Li et al. [Github](https://github.com/AMAP-ML/RealQA) | [Bibtex](./iqa_ref.bib#L1161-L1166)
- `[Arxiv 2025]` [Q-Insight: Understanding Image Quality via Visual Reinforcement Learning](https://arxiv.org/abs/2503.22679), Li et al. [Github](https://github.com/bytedance/Q-Insight) | [Bibtex](./iqa_ref.bib#L1139-L1144)
- `[TPAMI 2024]` [Q-BENCH: A Benchmark for Multi-modal Foundation Models on Low-level Vision from Single Images to Pairs](https://arxiv.org/abs/2402.07116), Zhang et al. [Github](https://github.com/Q-Future/Q-Bench) | [Bibtex](./iqa_ref.bib#L1071-L1080)
- `[Arxiv 2024]` [VisualCritic: Making LMMs Perceive Visual Quality Like Humans](https://arxiv.org/abs/2403.12806), Huang et al. [Bibtex](./iqa_ref.bib#L956-L963)
- `[ECCV 2024]` [A Comprehensive Study of Multimodal Large Language Models for Image Quality Assessment](https://arxiv.org/abs/2403.10854), Wu et al. [Github](https://github.com/TianheWu/MLLMs-for-IQA) | [Bibtex](./iqa_ref.bib#L939-L946)
- `[ECCV 2024]` [Towards Open-ended Visual Quality Comparison](https://arxiv.org/abs/2402.16641), Wu et al. [Github](https://github.com/Q-Future/Co-Instruct) | [Bibtex](./iqa_ref.bib#L922-L929)
- `[ECCV 2024]` [Depicting Beyond Scores: Advancing Image Quality Assessment through Multi-modal Language Models](https://arxiv.org/abs/2312.08962), You et al. [Github](https://github.com/XPixelGroup/DepictQA) | [Project](https://depictqa.github.io/) | [Bibtex](./iqa_ref.bib#L886-L894)
- `[TIP 2025]` [Enhancing Descriptive Image Quality Assessment with A Large-scale Multi-modal Dataset](https://arxiv.org/abs/2405.18842), You et al. [Github](https://github.com/XPixelGroup/DepictQA) | [Project](https://depictqa.github.io/depictqa-wild/) | [Bibtex](./iqa_ref.bib#L896-L906)
- `[CVPR 2024]` [Q-Instruct: Improving Low-level Visual Abilities for Multi-modality Foundation Models](https://arxiv.org/abs/2311.06783), Wu et al. [Github](https://github.com/Q-Future/Q-Instruct) | [Bibtex](./iqa_ref.bib#L878-L884)

### AIGC IQA

- `[Website 2026]` [ImageBench V1: Text-to-Image Benchmark with VLM Judges](https://imagebench.ai/imagebench-v1), imagebench.ai. [Project](https://imagebench.ai) | [Methodology](https://imagebench.ai/methodology-v1)
- `[Arxiv 2026]` [ELIQ: A Label-Free Framework for Quality Assessment of Evolving AI-Generated Images](https://arxiv.org/abs/2602.03558), Li et al. [Bibtex](./iqa_ref.bib#L1236-L1241)
- `[Arxiv 2026]` [EduVQA: Benchmarking AI-Generated Video Quality Assessment for Education](https://arxiv.org/abs/2603.03066), Chen et al. [Bibtex](./iqa_ref.bib#L1243-L1248)
- ✨`[CVPR 2024 (Best Paper)]` [Rich Human Feedback for Text-to-Image Generation](https://arxiv.org/abs/2312.10240), Liang et al. [Github](https://github.com/google-research-datasets/richhf-18k) | [Bibtex](./iqa_ref.bib#L1098-L1103)
- `[ICLR 2024 (Spotlight)]` [Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-level Vision](https://arxiv.org/abs/2309.14181), Wu et al. [Github](https://github.com/Q-Future/Q-Bench) | [Bibtex](./iqa_ref.bib#L837-L844)
- `[ICCV 2023]` [TIFA: Accurate and Interpretable Text-to-Image Faithfulness Evaluation with Question Answering](https://arxiv.org/abs/2303.11897), Hu et al. [Github](https://github.com/Yushi-Hu/tifa) | [Bibtex](./iqa_ref.bib#L846-L851) | [Project](https://tifa-benchmark.github.io/)
- `[NeurIPS 2023]` [ImageReward: Learning and Evaluating Human Preferences for Text-to-image Generation](https://arxiv.org/abs/2304.05977), Xu et al. [Github](https://github.com/THUDM/ImageReward) | [Bibtex](./iqa_ref.bib#L819-L824)
- `[ICCV 2023]` [Better Aligning Text-to-Image Models with Human Preference](https://arxiv.org/abs/2303.14420), Wu et al. [Github](https://github.com/tgxs002/align_sd) | [Github(HPSv2)](https://github.com/tgxs002/HPSv2) | [Bibtex](./iqa_ref.bib#L806-L811)
- `[NeurIPS 2023]` [Pick-a-Pic: An Open Dataset of User Preferences for Text-to-Image Generation](https://arxiv.org/abs/2305.01569), Yuval et al. [Github](https://github.com/yuvalkirstain/PickScore) | [Bibtex](./iqa_ref.bib#L813-L817)
- `[TCSVT 2024]` [AGIQA-3K: An Open Database for AI-Generated Image Quality Assessment](https://arxiv.org/abs/2306.04717), Li et al. [Github](https://github.com/lcysyzxdxc/AGIQA-3k-Database) | [Bibtex](./iqa_ref.bib#L826-L835)

### Image Aesthetic Assessment 

- `[CVPR 2026]` [Venus: Benchmarking and Empowering Multimodal Large Language Models for Aesthetic Guidance and Cropping](https://arxiv.org/abs/2602.23980), Du et al. [Github](https://github.com/PKU-ICST-MIPL/Venus_CVPR2026) | [Bibtex](./iqa_ref.bib#L1278-L1283)
- `[CVPR 2026 (Oral)]` [Fine-grained Image Aesthetic Assessment: Learning Discriminative Scores from Relative Ranks](https://arxiv.org/abs/2603.03907), Yang et al. [Github](https://github.com/yzc-ippl/FG-IAA) | [Bibtex](./iqa_ref.bib#L1257-L1262)
- `[AAAI 2026]` [Bridging Cognitive Gap: Hierarchical Description Learning for Artistic Image Aesthetics Assessment](https://arxiv.org/abs/2512.23413), Liu et al. [Github](https://github.com/Henglin-Liu/ArtQuant) | [Bibtex](./iqa_ref.bib#L1250-L1255)
- `[Arxiv 2026]` [VideoAesBench: Benchmarking the Video Aesthetics Perception Capabilities of Large Multimodal Models](https://arxiv.org/abs/2601.21915), Li et al. [Github](https://github.com/michaelliyunhao/VideoAesBench) | [Bibtex](./iqa_ref.bib#L1264-L1269)
- `[Arxiv 2026]` [Aesthetic Camera Viewpoint Suggestion with 3D Aesthetic Field](https://arxiv.org/abs/2602.20363), Tang et al. [Bibtex](./iqa_ref.bib#L1271-L1276)
- `[CVPR 2026]` [ArtiMuse: Fine-Grained Image Aesthetics Assessment with Joint Scoring and Expert-Level Understanding](https://arxiv.org/abs/2507.14533), Cao et al. [Project](https://thunderbolt215.github.io/ArtiMuse-project/) | [Github](https://github.com/thunderbolt215/ArtiMuse) | [Bibtex](./iqa_ref.bib#L1184-L1190)
- `[CVPR 2025]` [Charm: The Missing Piece in ViT Fine-Tuning for Image Aesthetic Assessment](https://arxiv.org/abs/2504.02522), Behrad et al. [Github](https://github.com/FBehrad/Charm) | [Bibtex](./iqa_ref.bib#L1146-L1152)
- `[ACM MM 2024]` [AesExpert: Towards Multi-modality Foundation Model for Image Aesthetics Perception](https://arxiv.org/abs/2404.09624), Huang et al. [Project](https://yipoh.github.io/aes-expert/) | [Github](https://github.com/yipoh/AesExpert) | [Bibtex](./iqa_ref.bib#L1063-L1069)
- `[Arxiv 2024]` [AesBench: An Expert Benchmark for Multimodal Large Language Models on Image Aesthetics Perception](https://arxiv.org/abs/2401.08276), Huang et al. [Github](https://github.com/yipoh/AesBench) | [Bibtex](./iqa_ref.bib#L915-L920)
- `[ECCV 2024]` [Scaling Up Personalized Image Aesthetic Assessment via Task Vector Customization](https://arxiv.org/abs/2407.07176), Yun et al. [Bibtex](./iqa_ref.bib#L1011-L1017) | [Project](https://yeolj00.github.io/personal-projects/personalized-aesthetics/)
- `[CVPR 2023]` [VILA: Learning Image Aesthetics from User Comments with Vision-Language Pretraining](https://arxiv.org/abs/2303.14302), Ke et al. [Bibtex](./iqa_ref.bib#L785-L790)
- `[CVPR 2023]` [Towards Artistic Image Aesthetics Assessment: a Large-scale Dataset and a New Method](https://arxiv.org/abs/2303.14968), Yi et al. [Github](https://github.com/Dreemurr-T/BAID) | [Bibtex](./iqa_ref.bib#L778-L783)

### No Reference (NR)
- `[AAAI 2026]` [Fine-grained Image Quality Assessment for Perceptual Image Restoration](https://arxiv.org/abs/2508.14475), Sheng et al. [Bibtex](./iqa_ref.bib#L1293-L1301) | [HomePage](https://sxfly99.github.io/FGResQ-Home/) | [Github](https://github.com/sxfly99/FGResQ)
- `[Arxiv 2026]` [Decoupling Perception and Calibration: Label-Efficient Image Quality Assessment Framework](https://arxiv.org/abs/2601.20689), Li et al. [Bibtex](./iqa_ref.bib#L1213-L1218)
- `[Arxiv 2026]` [SIQA: Toward Reliable Scientific Image Quality Assessment](https://arxiv.org/abs/2603.06700), Li et al. [Bibtex](./iqa_ref.bib#L1229-L1234)
- `[ICML 2025]` [QMamba: On First Exploration of Vision Mamba for Image Quality Assessment](https://arxiv.org/abs/2406.09546), Guan et al. [Github](https://github.com/bingo-G/QMamba) | [Bibtex](./iqa_ref.bib#L1000-L1009)
- `[NeurIPS 2024]` [Adaptive Image Quality Assessment via Teaching Large Multimodal Model to Compare](https://arxiv.org/abs/2405.19298), Zhu et al. [Project](https://compare2score.github.io/) | [Bibtex](./iqa_ref.bib#L981-L990)
- `[Arxiv 2024]` [Quality-Aware Image-Text Alignment for Real-World Image Quality Assessment](https://arxiv.org/abs/2403.11176), Agnolucci et al. [Github](https://github.com/miccunifi/QualiCLIP) | [Bibtex](./iqa_ref.bib#L965-L971)
- `[ACCV 2024]` [ATTIQA: Generalizable Image Quality Feature Extractor using Attribute-aware Pretraining](https://arxiv.org/abs/2406.01020), Kwon et al. [Bibtex](./iqa_ref.bib#L1122-L1129)
- `[CVPR 2024]` [Blind Image Quality Assessment Based On Geometric Order Learning](https://openaccess.thecvf.com/content/CVPR2024/papers/Shin_Blind_Image_Quality_Assessment_Based_on_Geometric_Order_Learning_CVPR_2024_paper.pdf), Shin et al. [Github](https://github.com/nhshin-mcl/QCN?tab=readme-ov-file) | [Bibtex](./iqa_ref.bib#L1105-L1110)
- `[CVPR 2024]` [Bridging the Synthetic-to-Authentic Gap: Distortion-Guided Unsupervised Domain Adaptation for Blind Image Quality Assessment](https://arxiv.org/abs/2405.04167), Li et al. [Bibtex](./iqa_ref.bib#L973-L979)
- `[CVPR 2024]` [Boosting Image Quality Assessment through Efficient Transformer Adaptation with Local Feature Enhancement](https://arxiv.org/abs/2308.12001), Xu et al. [Github](https://github.com/NeosXu/LoDa) | [Bibtex](./iqa_ref.bib#L931-L937)
- `[WACV 2024 (Oral)]` [ARNIQA: Learning Distortion Manifold for Image Quality Assessment](https://arxiv.org/abs/2310.14918), Agnolucci et al. [Github](https://github.com/miccunifi/ARNIQA) | [Bibtex](./iqa_ref.bib#L863-L869)
- `[TIP 2023]` [TOPIQ: A Top-down Approach from Semantics to Distortions for Image Quality Assessment](https://arxiv.org/abs/2308.03060), Chen et al. [Github](https://github.com/chaofengc/IQA-PyTorch) | [Bibtex](./iqa_ref.bib#L908-L913)
- `[ICCV 2023]` [Test Time Adaptation for Blind Image Quality Assessment](https://arxiv.org/abs/2307.14735), Roy et al. [Github](https://github.com/Shankhanil006/TTA-IQA) | [Bibtex](./iqa_ref.bib#L799-L804)
- `[CVPR 2023]` [Re-IQA: Unsupervised Learning for Image Quality Assessment in the Wild](https://arxiv.org/abs/2304.00451), Saha et al. [Bibtex](./iqa_ref.bib#L1388-L1394) | [Github](https://github.com/avinabsaha/ReIQA)
- `[CVPR 2023]` [Blind Image Quality Assessment via Vision-Language Correspondence: A Multitask Learning Perspective](https://arxiv.org/abs/2303.14968), Zhang et al. [Github](https://github.com/zwx8981/LIQE) | [Bibtex](./iqa_ref.bib#L771-L776)
- `[CVPR 2023]` [Quality-aware Pre-trained Models for Blind Image Quality Assessment](https://arxiv.org/abs/2303.00521), Zhao et al. [Bibtex](./iqa_ref.bib#L764-L769)

- `[AAAI2023]` [Exploring CLIP for Assessing the Look and Feel of Images](https://arxiv.org/abs/2207.12396), Wang et al. [Github](https://github.com/IceClear/CLIP-IQA) | [Bibtex](./iqa_ref.bib#L746-L751)
- `[AAAI 2023]` [Data-Efficient Image Quality Assessment with Attention-Panel Decoder](https://arxiv.org/abs/2304.04952), Qin et al. [Github](https://github.com/narthchin/DEIQT) | [Bibtex](./iqa_ref.bib#L792-L797)
- `[TPAMI2022]` [Continual Learning for Blind Image Quality Assessment
](https://arxiv.org/abs/2102.09717), Zhang et al. [Github](https://github.com/zwx8981/BIQA_CL) | [Bibtex](./iqa_ref.bib#L739-L744)
- `[TIP2022]` [No-Reference Image Quality Assessment by Hallucinating Pristine Features](https://arxiv.org/abs/2108.04165), Chen et al. [Github](https://github.com/Baoliang93/FPR) | [Bibtex](./iqa_ref.bib#L853-L861)
- `[TIP2022]` [VCRNet: Visual Compensation Restoration Network for No-Reference Image Quality Assessment](https://ieeexplore.ieee.org/document/9694502), Pan et al. [Github](https://github.com/NUIST-Videocoding/VCRNet) | [Bibtex](./iqa_ref.bib#L753-L762)
- `[TMM2022]` [GraphIQA: Learning Distortion Graph Representations for Blind Image Quality Assessment](https://arxiv.org/abs/2103.07666), Sun et al. [Github](https://github.com/geekyutao/GraphIQA) | [Bibtex](./iqa_ref.bib#L702-L708)
- `[CVPR2021]` [Troubleshooting Blind Image Quality Models in the Wild](https://arxiv.org/abs/2105.06747), Wang et al. [Github](https://github.com/wangzhihua520/troubleshooting_BIQA) | [Bibtex](./iqa_ref.bib#L717-L723)

- `[CVPRW 2022]` [MANIQA: Multi-dimension Attention Network for No-Reference Image Quality Assessment](https://arxiv.org/abs/2204.08958), NR. [Github](https://github.com/IIGROUP/MANIQA) | Transformer, multi-dimension attention, dual branch
- `[WACV 2022]` [No-Reference Image Quality Assessment via Transformers, Relative Ranking, and Self-Consistency](https://arxiv.org/abs/2108.06858), TReS, NR. [Github](https://github.com/isalirezag/TReS) | Transformer, relative ranking, self-consistency
- `[BMVC 2021]` [KonIQ++: Boosting No-Reference Image Quality Assessment in the Wild by Jointly Predicting Image Quality and Defects](https://www.bmvc2021-virtualconference.com/assets/papers/0868.pdf), NR. [Github](https://github.com/SSL92/koniqplusplus) | Multi-task with distortion prediction
- `[ICCV 2021]` [MUSIQ: Multi-scale Image Quality Transformer](https://arxiv.org/abs/2108.05997), NR. [Github](https://github.com/google-research/google-research/tree/master/musiq) / [Github](https://github.com/anse3832/MUSIQ) | Multi-scale, transformer, Aspect Ratio Preserved (ARP) resizing
- `[ICCV 2021]` [Learning Conditional Knowledge Distillation for Degraded-Reference Image Quality Assessment](https://arxiv.org/abs/2108.07948), CKDN, NR. [Github](https://github.com/researchmm/CKDN) | Degraded reference, Conditional knowledge distillation (related to HIQA)
- `[CVPR 2020]` [Blindly Assess Image Quality in the Wild Guided by a Self-Adaptive Hyper Network](https://openaccess.thecvf.com/content_CVPR_2020/papers/Su_Blindly_Assess_Image_Quality_in_the_Wild_Guided_by_a_CVPR_2020_paper.pdf), HyperIQA, NR. [Github](https://github.com/SSL92/hyperIQA) | Content-aware hyper network
- `[CVPR 2020]` [MetaIQA: Deep Meta-learning for No-Reference Image Quality Assessment](https://arxiv.org/abs/2004.05508), NR. [Github](https://github.com/zhuhancheng/MetaIQA) | Meta-learning
- `[ECCV 2020]` [GIQA: Generated Image Quality Assessment](https://arxiv.org/abs/2003.08932), NR. [Github](https://github.com/cientgu/GIQA) | Generated image
- `[PIRM Challenge 2018]` [The 2018 PIRM Challenge on Perceptual Image Super-resolution](https://arxiv.org/abs/1809.07517), PI, NR. [Github](https://github.com/roimehrez/PIRM2018) | 1/2 * (NIQE + (10 - NRQM)).
- `[CVPR 2018]` [Hallucinated-IQA: No-Reference Image Quality Assessment via Adversarial Learning](https://arxiv.org/abs/1804.01681), HIQA, NR. [Project](https://kwanyeelin.github.io/projects/HIQA/HIQA.html) | Hallucinated reference
- `[CVPR 2018]` [Blind Predicting Similar Quality Map for Image Quality Assessment](https://arxiv.org/pdf/1805.08493v1.pdf), BPSQM, NR. | Pixel-wise quality map
- `[ICCV 2017]` [RankIQA: Learning from Rankings for No-reference Image Quality Assessment](https://arxiv.org/abs/1707.08347), NR. [Github](https://github.com/xialeiliu/RankIQA) | Pretrain on synthetically ranked data
- `[CVPR 2014]` [Convolutional Neural Networks for No-Reference Image Quality Assessment](https://openaccess.thecvf.com/content_cvpr_2014/papers/Kang_Convolutional_Neural_Networks_2014_CVPR_paper.pdf), CNNIQA, NR. [Github](https://github.com/lidq92/CNNIQA) | First CNN-based NR-IQA
- `[TIP 2021]` [Uncertainty-Aware Blind Image Quality Assessment in the Laboratory and Wild](https://arxiv.org/abs/2005.13983), UNIQUE, NR. [Github](https://github.com/zwx8981/UNIQUE) | Combine synthetic and authentic image pairs
- `[TCSVT 2020]` [Blind Image Quality Assessment Using A Deep Bilinear Convolutional Neural Network](https://arxiv.org/pdf/1907.02665.pdf), DBCNN, NR. [Github](https://github.com/zwx8981/DBCNN-PyTorch) | Two branches for synthetic and authentic distortions
- `[TMM 2019]` [Which Has Better Visual Quality: The Clear Blue Sky or a Blurry Animal?](http://www.jdl.link/doc/2011/20191226_08489929.pdf), SFA, NR. [Github](https://github.com/lidq92/SFA) | Aggregate ResNet50 features of multiple cropped patches
- `[TIP 2019]` [A Probabilistic Quality Representation Approach to Deep Blind Image Quality Prediction](https://drive.google.com/file/d/1tMjcllKP8SzTn-dWVmogxaCLpzL1L7nO/view), PQR, NR/Aesthetic. [Github](https://github.com/HuiZeng/Unified_IAA)/[Github](https://github.com/HuiZeng/BIQA_Toolbox) | Unify different type of aesthetic labels
- `[TIP 2018]` [Deep Neural Networks for No-Reference and Full-Reference Image Quality Assessment](https://arxiv.org/abs/1612.01697), WaDIQaM, NR/FR. [Github](https://github.com/lidq92/WaDIQaM) | Weighted average of patch qualities, shared FR/NR models
- `[TIP 2018]` [NIMA: Neural Image Assessment](https://ieeexplore.ieee.org/ielx7/83/8347140/08352823.pdf), NR. [Github](https://github.com/kentsyx/Neural-IMage-Assessment)/[Github](https://github.com/idealo/image-quality-assessment) | Squared EMD loss
- `[TIP 2017]` [End-to-End Blind Image Quality Assessment Using Deep Neural Networks](https://ece.uwaterloo.ca/~z70wang/publications/TIP_E2E_BIQA.pdf), MEON, NR. | Multi-task: distortion learning and quality prediction
- `[TIP 2017]` [dipIQ: Blind Image Quality Assessment by Learning-to-Rank Discriminable Image Pairs](https://arxiv.org/abs/1904.06505), NR. [Download](https://ece.uwaterloo.ca/~k29ma/codes/dipIQ.rar) | Similar to RankIQA
- `[CVIU 2017]` [Learning a No-Reference Quality Metric for Single-Image Super-Resolution (NRQM)](https://arxiv.org/abs/1612.05890), NR. [Project](https://sites.google.com/site/chaoma99/sr-metric) | Traditional, Super resolution
- `[JoV 2017]` [Perceptual Quality Prediction on Authentically Distorted Images Using a Bag of Features Approach](https://arxiv.org/abs/1609.04757), FRIQUEE, NR. [Github](https://github.com/utlive/FRIQUEE) | Authentically Distorted, Bag of Features
- `[TIP 2016]` [Blind Image Quality Assessment Based on High Order Statistics Aggregation](https://ieeexplore.ieee.org/document/7501619), HOSA, NR. [Matlab download](https://ieeexplore.ieee.org/document/7501619) | Traditional
- `[TIP 2015]` [A Feature-Enriched Completely Blind Image Quality Evaluator](https://live.ece.utexas.edu/publications/2015/zhang2015feature.pdf), ILNIQE, NR. [Project](http://www4.comp.polyu.edu.hk/~cslzhang/IQA/ILNIQE/ILNIQE.htm) | Traditional
- `[TIP 2012]` [No-reference Image Quality Assessment in the Spatial Domain](https://live.ece.utexas.edu/publications/2012/TIP%20BRISQUE.pdf), BRISQUE, NR. [Github](https://github.com/utlive/BRISQUE) | Traditional
- `[TIP 2012]` [Blind Image Quality Assessment: A Natural Scene Statistics Approach in the DCT Domain](https://live.ece.utexas.edu/publications/2012/saad_2012_tip.pdf), BLIINDS-II, NR. [Github](https://github.com/utlive/BLIINDS2)
- `[CVPR 2012]` [Unsupervised Feature Learning Framework for No-reference Image Quality Assessment](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.359.7510&rep=rep1&type=pdf), CORNIA, NR. [Github](https://github.com/HuiZeng/BIQA_Toolbox) | Codebook Representation
- `[SPL 2012]` [Making a “Completely Blind” Image Quality Analyzer](https://live.ece.utexas.edu/publications/2013/mittal2013.pdf), NIQE, NR. [Github](https://github.com/utlive/niqe) | Traditional
- `[TIP 2011]` [Blind Image Quality Assessment: From Natural Scene Statistics to Perceptual Quality](https://www.imaging.utk.edu/research/wcho/references/2011%20TIP%20BLINDS2.pdf), DIIVINE, NR. [Github](https://github.com/utlive/DIIVINE)

### Full Reference (FR)

- `[Arxiv 2026]` [JLD: Perceptual Distance Through A Jacobian Lens](https://arxiv.org/abs/2610.05967), Saini et al., FR. Frozen vision encoder with a Jacobian lens. [Github](https://github.com/shreshthsaini/jld) | [Project](https://shreshthsaini.github.io/jld/) | [Bibtex](./iqa_ref.bib#L1413-L1421)

- `[ECCV2022]` [Shift-tolerant Perceptual Similarity Metric](https://arxiv.org/abs/2211.052152207.13686), Ghildyal et al. [Github](https://github.com/abhijay9/ShiftTolerant-LPIPS) | [Bibtex](./iqa_ref.bib#L732-L737)
- `[BMVC2022]` [Content-Diverse Comparisons improve IQA](https://arxiv.org/abs/2211.05215), Thong et al. [Bibtex](./iqa_ref.bib#L725-L730)
- `[ACM MM2022]` [Quality Assessment of Image Super-Resolution: Balancing Deterministic and Statistical Fidelity](https://arxiv.org/abs/2207.08689), Zhou et al. [Github](https://github.com/weizhou-geek/SRIF) | [Bibtex](./iqa_ref.bib#L710-L715)

- `[CVPR 2022 NTIRE workshop]` [Attentions Help CNNs See Better: Attention-based Hybrid Image Quality Assessment Network](https://arxiv.org/abs/2204.10485), AHIQ, FR. [Github](https://github.com/IIGROUP/AHIQ) | Attention, Transformer
- `[CVPR 2022]` [Incorporating Semi-Supervised and Positive-Unlabeled Learning for Boosting Full Reference Image Quality Assessment](https://arxiv.org/abs/2204.08763), JSPL, FR. [Github](https://github.com/happycaoyue/JSPL) | semi-supervised and positive-unlabeled (PU) learning
- `[AAAI 2022]` [Content-Variant Reference Image Quality Assessment via Knowledge Distillation](https://arxiv.org/abs/2202.13123), CVRKD, NAR. [Github](https://github.com/guanghaoyin/CVRKD-IQA) | Non-Aligned content reference, knowledge distillation
- `[CVPRW 2021]` [Perceptual Image Quality Assessment with Transformers](https://arxiv.org/abs/2104.14730), IQT, FR. [Github](https://github.com/anse3832/IQT) | Transformer
- `[ACMM 2021]` [Locally Adaptive Structure and Texture Similarity for Image Quality Assessment](https://arxiv.org/abs/2110.08521), A-DISTS, FR. [Github](https://github.com/dingkeyan93/A-DISTS)
- `[TPAMI 2021]` [Image Quality Assessment: Unifying Structure and Texture Similarity](https://arxiv.org/abs/2004.07728), DISTS, FR. [Github](https://github.com/dingkeyan93/DISTS)
- `[CVPR 2018]` [The Unreasonable Effectiveness of Deep Features as a Perceptual Metric](https://arxiv.org/abs/1801.03924), LPIPS, FR. [Project](https://richzhang.github.io/PerceptualSimilarity/) | Perceptual similarity, Pairwise Preference
- `[CVPR 2018]` [PieAPP: Perceptual Image-Error Assessment through Pairwise Preference](https://arxiv.org/abs/1806.02067), FR. [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | Perceptual similarity, Pairwise Preference
- `[TIP 2018]` [Deep Neural Networks for No-Reference and Full-Reference Image Quality Assessment](https://arxiv.org/abs/1612.01697), WaDIQaM, NR/FR. [Github](https://github.com/lidq92/WaDIQaM)
- `[TCSVT 2020]` [A Novel Just-Noticeable-Difference-based Saliency-Channel Attention Residual Network for Full-Reference Image Quality Predictions](https://arxiv.org/abs/1902.05316), JND-SalCAR, FR. | JND (Just-Noticeable-Difference)
- `[TIP 2019]` [Visual Quality Assessment for Super-resolved Images: Database and Method](https://nottingham-repository.worktribe.com/preview/1589753/Visual%20IEEE-TIP-2019.pdf), QADS, FR. [Project](http://www.vista.ac.cn/super-resolution/) | Super-resolution
- `[TIP 2011]` [FSIM: A Feature Similarity Index for Image Quality Assessment](https://sse.tongji.edu.cn/linzhang/IQA/FSIM/Files/Fsim%20a%20feature%20similarity%20index%20for%20image%20quality%20assessment.pdf), FR. [Project](https://www4.comp.polyu.edu.hk/~cslzhang/IQA/FSIM/FSIM.htm) | Traditional
- `[TIP 2005]` [An information fidelity criterion for image quality assessment using natural scene statistics](https://doi.org/10.1109/TIP.2005.859389) (IFC), FR. | Traditional
- `[TIP 2006]` [Image Information and Visual Quality](https://live.ece.utexas.edu/publications/2004/hrs_ieeetip_2004_imginfo.pdf) (VIF), FR. [Project](https://live.ece.utexas.edu/research/Quality/VIF.htm) | Traditional
- [FR] [Multiscale Structural Similarity for Image Quality Assessment (MS-SSIM)](https://ece.uwaterloo.ca/~z70wang/publications/msssim.pdf) [Project](https://ece.uwaterloo.ca/~z70wang/research/ssim/) | Traditional
- `[TIP 2004]` [Image Quality Assessment: From Error Visibility to Structural Similarity](https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf), SSIM, FR. [Project](https://ece.uwaterloo.ca/~z70wang/research/ssim/) | Traditional

### Others 

#### Image Intrinsic Scale Assessment (IISA)
> Aims to predict the Image Intrinsic Scale, _i.e._ the scale at which an image shows the best quality

- `[ICCV 2025]` [Image Intrinsic Scale Assessment: Bridging the Gap Between Quality and Resolution](https://arxiv.org/abs/2502.06476), Hosu et al. [Bibtex](./iqa_ref.bib#L1131-L1137) | [Github](https://github.com/SonyResearch/IISA)

#### Color IQA

- `[ECCV 2024]` [Multiscale Sliced Wasserstein Distances as Perceptual Color Difference Measures](https://arxiv.org/abs/2407.10181), He et al. [Github](https://github.com/real-hjq/MS-SWD) | [Bibtex](./iqa_ref.bib#L1082-L1089)
- `[CVPR 2023]` [Learning a Deep Color Difference Metric for Photographic Images](https://arxiv.org/abs/2303.14964), Chen et al. [Github](https://github.com/haoychen3/CD-Flow) | [Bibtex](./iqa_ref.bib#L1091-L1096)

#### Face IQA

- `[CVPR 2024]` [DSL-FIQA: Assessing Facial Image Quality via Dual-Set Degradation Learning and Landmark-Guided Transformer](https://arxiv.org/abs/2406.09622), Chen et al. [Bibtex](./iqa_ref.bib#L992-L998) | [Project](https://dsl-fiqa.github.io/)

#### 360° Image (Omnidirectional Image) IQA
- `[NeurIPS 2023]` [Assessor360: Multi-sequence Network for Blind Omnidirectional Image Quality Assessment
](https://arxiv.org/abs/2305.10983), Wu et al. [Bibtex](./iqa_ref.bib#L1019-L1024) | [Github](https://github.com/TianheWu/Assessor360)

#### Egocentric Spatial Images (Apple Vision Pro)

- `[Arxiv 2024]` [ESIQA: Perceptual Quality Assessment of Vision-Pro-based
Egocentric Spatial Images](https://arxiv.org/abs/2407.21363), Zhu et al. [Bibtex](./iqa_ref.bib#L1035-L1042) | [Github](https://github.com/IntMeGroup/ESIQA)

#### Adversarial Attack on IQA

- `[Arxiv 2024]` [Guardians of Image Quality: Benchmarking Defenses Against Adversarial Attacks on Image Quality Metrics](https://arxiv.org/abs/2408.01541), Gushchin et al. [Bibtex](./iqa_ref.bib#L1053-L1061) | [Github](https://github.com/msu-video-group/adversarial-defenses-for-iqa) | [Project](https://videoprocessing.ai/benchmarks/iqa-defenses.html)
- `[NeurIPS 2022]` [Perceptual Attacks of No-Reference Image Quality Models with Human-in-the-Loop](https://arxiv.org/abs/2210.00933), Zhang et al. [Bibtex](./iqa_ref.bib#L1044-L1051) | [Github](https://github.com/zwx8981/PerceptualAttack_BIQA)

#### IQA Losses

- `[ACMM2020]` [Norm-in-Norm Loss with Faster Convergence and Better Performance for Image Quality Assessment](https://arxiv.org/abs/2008.03889) [Github](https://github.com/lidq92/LinearityIQA) | Norm-in-Norm Loss

## Datasets 

### IQA datasets

| Paper Link | Dataset Name | Type | Published | Website | Images | Annotations
| ----------- | ---------- | ------------| ---------- | ------ | ------ |------ |
| [arXiv](https://arxiv.org/abs/2508.14475) | FGRestore | NR | AAAI2026 | [Project](https://sxfly99.github.io/FGResQ-Home/) | 18,408(30,886 pairs)| 45,318 |
| [arXiv](https://arxiv.org/abs/2603.00938) | Beyond8Bits | NR | CVPR2026 | [Project](https://shreshthsaini.github.io/Beyond8Bits/) | 44k videos from 6.5k sources | 1.5M+ ratings |
| [arXiv](https://arxiv.org/abs/2605.01272) | GameScope | NR | ICIP2026 | [Project](https://rajeshsureddi.github.io/GameScope/) | 4,048 gaming videos (H.264/H.265/AV1, UGC + PGC) | ~37 MOS per video + quality attributes |
| [arXiv](https://arxiv.org/abs/2406.17472) | UHD-IQA | NR | ECCVW2024 | [Project](https://database.mmsp-kn.de/uhd-iqa-benchmark-database.html) | 6k (~3840x2160) | 20 ratings per image |
| [arXiv](https://arxiv.org/abs/1912.10088) | PaQ-2-PiQ | NR | CVPR2020 | [Official github](https://github.com/baidut/PaQ-2-PiQ) | 40k, 120k patches | 4M |
| [CVF](https://openaccess.thecvf.com/content_CVPR_2020/html/Fang_Perceptual_Quality_Assessment_of_Smartphone_Photography_CVPR_2020_paper.html)  | SPAQ | NR | CVPR2020 | [Offical github](https://github.com/h4nwei/SPAQ) | 11k (smartphone) | |  
| [arXiv](https://arxiv.org/abs/1910.06180) | KonIQ-10k | NR | TIP2020 | [Project](http://database.mmsp-kn.de/koniq-10k-database.html) | 10k from [YFCC100M](http://projects.dfki.uni-kl.de/yfcc100m/) | 1.2M | 
| [arXiv](https://arxiv.org/abs/1606.01621v2) | AADB | NR/Aesthentic | ECCV2016 | [Official github](https://github.com/aimerykong/deepImageAestheticsAnalysis) | 10k images (8500/500/1000), 11 attributes 
| [arXiv](https://arxiv.org/abs/1511.02919) | CLIVE | NR | TIP2016 | [Project](https://live.ece.utexas.edu/research/ChallengeDB/index.html) | 1200 | 350k |
| [pdf](http://refbase.cvc.uab.es/files/MMP2012a.pdf) | AVA | NR / Aesthentic | CVPR2012 | [Github](https://github.com/mtobeiyf/ava_downloader)/[Project](http://www.lucamarchesotti.com/) | 250k (60 categories) | | 
| [arXiv](https://arxiv.org/abs/2007.12142) | PIPAL | FR | ECCV2020 | [Project](https://www.jasongt.com/projectpages/pipal.html) | 250 | 1.13M |
| [arXiv](https://arxiv.org/abs/2001.08113) | KADIS-700k | FR | arXiv | [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | 140k pristine / 700k distorted | 30 ratings (DCRs) per image. | 
| [IEEE](https://ieeexplore.ieee.org/document/8743252) | KADID-10k | FR | QoMEX2019 | [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | 81 | 10k distortions |
| [pdf](https://ece.uwaterloo.ca/~k29ma/papers/17_TIP_EXPLORATION.pdf) | Waterloo-Exp | FR | TIP2017 | [Project](https://ece.uwaterloo.ca/~k29ma/exploration/) | 4744 | 94k distortions | 
| [pdf](https://daneshyari.com/article/preview/533080.pdf) | MDID | FR | PR2017 | --- | 20 | 1600 distortions  |
| [pdf](http://www.ponomarenko.info/papers/euvip_tid2013.pdf) | TID2013 | FR | SP2015 | [Project](http://www.ponomarenko.info/tid2013.htm) | 25 | 3000 distortions |
| [pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.298.9133&rep=rep1&type=pdf)  | LIVEMD | FR | ACSSC2012 | [Project](https://live.ece.utexas.edu/research/Quality/live_multidistortedimage.html) | 15 pristine images | two successive distortions |
| [pdf](https://www.researchgate.net/profile/Damon-Chandler/publication/220050520_Most_apparent_distortion_Full-reference_image_quality_assessment_and_the_role_of_strategy/links/5629cd1c08ae518e347e1445/Most-apparent-distortion-Full-reference-image-quality-assessment-and-the-role-of-strategy.pdf)  | CSIQ | FR | Journal of Electronic Imaging 2010 | --- | 30 | 866 distortions |
| [pdf](http://www.ponomarenko.info/papers/mre2009tid.pdf) | TID2008 | FR | 2009 | [Project](http://www.ponomarenko.info/tid2008.htm) | 25 | 1700 distortions |
| [pdf](https://live.ece.utexas.edu/publications/2006/hrs-transIP-06.pdf) | LIVE IQA | FR | TIP2006 | [Project](https://live.ece.utexas.edu/research/Quality/subjective.htm) | 29 images, 780 synthetic distortions 
| [link](http://hal.univ-nantes.fr/hal-00580755/) | IVC | FR | 2005 | --- | 10 | 185 distortions |

### Perceptual similarity datasets

| Paper Title | Dataset Name | Type | Published | Website | Images | Annotations |  
| ----------- | ---------- | ------------| ---------- | ------ | ------ | ----- |
| [arXiv](https://arxiv.org/abs/1801.03924) | BAPPS(LPIPS) | FR | CVPR2018 | [Project](https://richzhang.github.io/PerceptualSimilarity/) | 187.7k  | 484k 
| [arXiv](https://arxiv.org/abs/1806.02067) | PieAPP | FR | CVPR2018 | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | 200 images | 2.3M 
| [arXiv](https://arxiv.org/pdf/2604.11004) | Panda  | FR | ICLR2026 | [Project](https://aismartperception.github.io/distortion-graph/) | 2200 images | >500k
