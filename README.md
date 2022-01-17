# Awesome Image Quality Assessment (IQA)
A collection of IQA papers (mainly deep learning methods), datasets and codes. 

- [Awesome Image Quality Assessment (IQA)](#awesome-image-quality-assessment-iqa)
  - [Papers](#papers)
    - [No Reference (NR)](#no-reference-nr)
    - [Full Reference (FR)](#full-reference-fr)
  - [Datasets](#datasets)
    - [IQA datasets](#iqa-datasets)
    - [Perceptual similarity datasets](#perceptual-similarity-datasets)

## Papers

### No Reference (NR)

| Paper Link | Method | Type | Published | Code | Keywords | 
| ----------- | ---------- | ------------| ---------- | ------ | ------ |
| [arXiv](https://arxiv.org/abs/2108.05997) | MUSIQ | NR | ICCV2021 | [Official](https://github.com/google-research/google-research/tree/master/musiq) / [Pytorch](https://github.com/anse3832/MUSIQ) | Multi-scale, transformer, Aspect Ratio Preserved (ARP) resizing
| [arXiv](https://arxiv.org/abs/2108.07948) | CKDN | NR | ICCV2021 | [Official](https://github.com/researchmm/CKDN) | Degraded reference, Conditional knowledge distillation (related to HIQA)
| [pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Su_Blindly_Assess_Image_Quality_in_the_Wild_Guided_by_a_CVPR_2020_paper.pdf) | HyperIQA | NR | CVPR2020 | [Official](https://github.com/SSL92/hyperIQA) | Content-aware hyper network 
| [arXiv](https://arxiv.org/abs/2004.05508) | Meta-IQA | NR | CVPR2020 | [Official](https://github.com/zhuhancheng/MetaIQA) | Meta-learning 
| [arXiv](https://arxiv.org/abs/2003.08932) | GIQA | NR | ECCV2020 | [Official](https://github.com/cientgu/GIQA) | Generated image 
| [arXiv](https://arxiv.org/abs/1804.01681) | HIQA | NR | CVPR2018 | [Project](https://kwanyeelin.github.io/projects/HIQA/HIQA.html) | Hallucinated reference 
| [arXiv](https://arxiv.org/pdf/1805.08493v1.pdf) | BPSQM | NR | CVPR2018 | []() | Pixel-wise quality map 
| [arXiv](https://arxiv.org/abs/1707.08347) | RankIQA | NR | ICCV2017 | [Github](https://github.com/xialeiliu/RankIQA) | Pretrain on synthetically ranked data 
| [pdf](https://openaccess.thecvf.com/content_cvpr_2014/papers/Kang_Convolutional_Neural_Networks_2014_CVPR_paper.pdf) | CNNIQA | NR | CVPR2014 | [PyTorch](https://github.com/lidq92/CNNIQA) | First CNN-based NR-IQA 
| []() | | | | []() | 
| [arXiv](https://arxiv.org/abs/2005.13983) | UNIQUE | NR | TIP2021 | [Github](https://github.com/zwx8981/UNIQUE) | Combine synthetic and authentic image pairs 
| [arXiv](https://arxiv.org/pdf/1907.02665.pdf) | DBCNN | NR | TCSVT2020 | [Official](https://github.com/zwx8981/DBCNN-PyTorch) | Two branches for synthetic and authentic distortions 
| [pdf](http://www.jdl.link/doc/2011/20191226_08489929.pdf) | SFA | NR | TMM2019 | [Official](https://github.com/lidq92/SFA) | Aggregate ResNet50 features of multiple cropped patches
| [pdf](https://drive.google.com/file/d/1tMjcllKP8SzTn-dWVmogxaCLpzL1L7nO/view)/[arXiv](https://arxiv.org/abs/1708.08190) | PQR | NR/Aesthetic | TIP2019 | [Official1](https://github.com/HuiZeng/Unified_IAA)/[Official2](https://github.com/HuiZeng/BIQA_Toolbox) | Unify different type of aesthetic labels 
| [arXiv](https://arxiv.org/abs/1612.01697) | WaDIQaM (deepIQA) | NR/FR | TIP2018 | [PyTorch](https://github.com/lidq92/WaDIQaM) | Weighted average of patch qualities, shared FR/NR models 
| [pdf](https://ieeexplore.ieee.org/ielx7/83/8347140/08352823.pdf) | NIMA | NR | TIP2018 | [PyTorch](https://github.com/kentsyx/Neural-IMage-Assessment) | Squared EMD loss 
| [pdf](https://ece.uwaterloo.ca/~z70wang/publications/TIP_E2E_BIQA.pdf) | MEON | NR | TIP2017 | | Multi-task: distortion learning and quality prediction
| [arXiv](https://arxiv.org/abs/1904.06505) | dipIQ | NR | TIP2017 | [download](https://ece.uwaterloo.ca/~k29ma/codes/dipIQ.rar) | Similar to RankIQA
| []() | | | | []() | 
| [arXiv](https://arxiv.org/abs/1612.05890) | NRQM (Ma) | NR | CVIU2017 | [Project](https://sites.google.com/site/chaoma99/sr-metric) | Traditional, Super resolution 
| [IEEE](https://ieeexplore.ieee.org.remotexs.ntu.edu.sg/stamp/stamp.jsp?tp=&arnumber=7501619) | HOSA | NR | TIP2016 | []() | Traditional 
| [pdf](https://live.ece.utexas.edu/publications/2015/zhang2015feature.pdf) | ILNIQE | NR | TIP2015 | []() | Traditional 
| [pdf](https://live.ece.utexas.edu/publications/2012/TIP%20BRISQUE.pdf) | BRISQUE | NR | TIP2012 | []() | Traditional 
| [pdf](https://live.ece.utexas.edu/publications/2013/mittal2013.pdf) | NIQE | NR | SPL2012 | []() | Traditional 
<!-- | []() | | NR | | []() |  -->

Others
- Perceptual Index (PI, [2018 PIRM Challenge](https://arxiv.org/abs/1809.07517)): 1/2 * (NIQE + (10 - NRQM)). 

### Full Reference (FR)

| Title | Method | Type | Published | Code | Keywords | 
| ----------- | ---------- | ------------| ---------- | ------ | ------ |
| [arXiv](https://arxiv.org/abs/2110.08521) | A-DISTS | FR | ACMM2021 | [Official](https://github.com/dingkeyan93/A-DISTS) | 
| [arXiv](https://arxiv.org/abs/2004.07728) | DISTS | FR | TPAMI2021 | [Official](https://github.com/dingkeyan93/DISTS) | 
| [arXiv](https://arxiv.org/abs/1801.03924) | LPIPS | FR | CVPR2018 | [Project](https://richzhang.github.io/PerceptualSimilarity/) | Perceptual similarity, Pairwise Preference 
| [arXiv](https://arxiv.org/abs/1806.02067) | PieAPP | FR | CVPR2018 | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | Perceptual similarity, Pairwise Preference 
| [arXiv](https://arxiv.org/abs/1612.01697) | WaDIQaM | NR/FR | TIP2018 | [Official](https://github.com/lidq92/WaDIQaM) | 
| [arXiv](https://arxiv.org/abs/1902.05316) | JND-SalCAR | FR| TCSVT2020 | []() | JND (Just-Noticeable-Difference) 
| []() | | | | []() | 
| [pdf](https://nottingham-repository.worktribe.com/preview/1589753/Visual%20IEEE-TIP-2019.pdf) | QADS | FR | TIP2019 | [Project](http://www.vista.ac.cn/super-resolution/) | Super-resolution 
| [pdf](https://sse.tongji.edu.cn/linzhang/IQA/FSIM/Files/Fsim%20a%20feature%20similarity%20index%20for%20image%20quality%20assessment.pdf) | FSIM | FR | TIP2011 | [Project](https://sse.tongji.edu.cn/linzhang/IQA/FSIM/FSIM.htm) | Traditional 
| [pdf](https://live.ece.utexas.edu/publications/2004/hrs_ieeetip_2004_imginfo.pdf) | VIF/IFC | FR | TIP2006 | [Project](https://live.ece.utexas.edu/research/Quality/VIF.htm) | Traditional 
| [pdf](https://ece.uwaterloo.ca/~z70wang/publications/msssim.pdf) | MS-SSIM | FR | | [Project](https://ece.uwaterloo.ca/~z70wang/research/ssim/) | Traditional 
| [pdf](https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf) | SSIM | FR | TIP2004 | [Project](https://ece.uwaterloo.ca/~z70wang/research/ssim/) | Traditional 
| []() | PSNR | FR | | []() | Traditional 
<!-- | []() | | FR | | []() |  -->

## Datasets 

### IQA datasets

| Paper Link | Dataset Name | Type | Published | Website | Images | Annotations
| ----------- | ---------- | ------------| ---------- | ------ | ------ |------ |
| [arXiv](https://arxiv.org/abs/1912.10088) | PaQ-2-PiQ | NR | CVPR2020 | [Official github](https://github.com/baidut/PaQ-2-PiQ) | 40k, 120k patches | 4M |
| [CVF](https://openaccess.thecvf.com/content_CVPR_2020/html/Fang_Perceptual_Quality_Assessment_of_Smartphone_Photography_CVPR_2020_paper.html)  | SPAQ | NR | CVPR2020 | [Offical github](https://github.com/h4nwei/SPAQ) | 11k (smartphone) | |  
| [arXiv](https://arxiv.org/abs/1910.06180) | KonIQ-10k | NR | TIP2020 | [Project](http://database.mmsp-kn.de/koniq-10k-database.html) | 10k from [YFCC100M](http://projects.dfki.uni-kl.de/yfcc100m/) | 1.2M | 
| [arXiv](https://arxiv.org/abs/1511.02919) | CLIVE | NR | TIP2016 | [Project](https://live.ece.utexas.edu/research/ChallengeDB/index.html) | 1200 | 350k |
| [pdf](http://refbase.cvc.uab.es/files/MMP2012a.pdf) | AVA | NR / Aesthentic | CVPR2012 | [Github](https://github.com/mtobeiyf/ava_downloader)/[Project](http://www.lucamarchesotti.com/) | 250k (60 categories) | | 
| [arXiv](https://arxiv.org/abs/2007.12142) | PIPAL | FR | ECCV2020 | [Project](https://www.jasongt.com/projectpages/pipal.html) | 250 | 1.13M |
| [arXiv](https://arxiv.org/abs/2001.08113) | KADIS-700k | FR | arXiv | [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | 140k pristine / 700k distorted | 30 ratings (DCRs) per image. | 
| [IEEE](https://ieeexplore.ieee.org/document/8743252) | KADID-10k | FR | QoMEX2019 | [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | 81 | 10k distortions |
| [pdf](https://ece.uwaterloo.ca/~k29ma/papers/17_TIP_EXPLORATION.pdf) | Waterloo-Exp | FR | TIP2017 | [Project](https://ece.uwaterloo.ca/~k29ma/exploration/) | 4744 | 94k distortions | 
| [pdf](https://daneshyari.com/article/preview/533080.pdf) | MDID | FR | PR2017 | --- | 20 | 1600 distortions  |
| [pdf](http://www.ponomarenko.info/papers/euvip_tid2013.pdf) | TID2013 | FR | SP2015 | [Project](http://www.ponomarenko.info/tid2013.htm) | 25 | 3000 distortions |
| [pdf](https://www.researchgate.net/profile/Damon-Chandler/publication/220050520_Most_apparent_distortion_Full-reference_image_quality_assessment_and_the_role_of_strategy/links/5629cd1c08ae518e347e1445/Most-apparent-distortion-Full-reference-image-quality-assessment-and-the-role-of-strategy.pdf)  | CSIQ | FR | Journal of Electronic Imaging 2010 | --- | 30 | 866 distortions |
| [pdf](http://www.ponomarenko.info/papers/mre2009tid.pdf) | TID2008 | FR | 2009 | [Project](http://www.ponomarenko.info/tid2008.htm) | 25 | 1700 distortions |
| [pdf](https://live.ece.utexas.edu/publications/2006/hrs-transIP-06.pdf) | LIVE IQA | FR | TIP2006 | [Project](https://live.ece.utexas.edu/research/Quality/subjective.htm) | 29 images, 780 synthetic distortions 
| [link](http://hal.univ-nantes.fr/hal-00580755/) | IVC | FR | 2005 | --- | 10 | 185 distortions |

### Perceptual similarity datasets

| Paper Title | Dataset Name | Type | Published | Website | Images | Annotations |  
| ----------- | ---------- | ------------| ---------- | ------ | ------ | ----- |
| [arXiv](https://arxiv.org/abs/1801.03924) | BAPPS(LPIPS) | FR | CVPR2018 | [Project](https://richzhang.github.io/PerceptualSimilarity/) | 187.7k  | 484k 
| [arXiv](https://arxiv.org/abs/1806.02067) | PieAPP | FR | CVPR2018 | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | 200 images | 2.3M 