# Awesome Image Quality Assessment(IQA)
A collection of IQA (image quality assessment) related papers, data and repositories

## Papers

<!-- ### 2021 -->

### No Reference (NR)

| Paper Link | Model | Type | Published | Code | Keywords | 
| ----------- | ---------- | ------------| ---------- | ------ | ------ |
| [arXiv](https://arxiv.org/abs/2108.05997) | MUSIQ | NR | ICCV 2021 | [Official](https://github.com/google-research/google-research/tree/master/musiq) / [Pytorch](https://github.com/anse3832/MUSIQ) | Multi-scale, transformer

### Full Reference (FR)

| Title | Model | Type | Published | Code | Keywords | 
| ----------- | ---------- | ------------| ---------- | ------ | ------ |
| [arXiv](https://arxiv.org/abs/1801.03924) | LPIPS | FR | CVPR2018 | [Project](https://richzhang.github.io/PerceptualSimilarity/) | Perceptual similarity 
| [arXiv](https://arxiv.org/abs/1806.02067) | PieAPP | FR | CVPR2018 | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | Perceptual similarity 

## Datasets 

### IQA datasets

| Paper Link | Dataset Name | Type | Published | Website | Images | Annotations
| ----------- | ---------- | ------------| ---------- | ------ | ------ |------ |
| [arXiv](https://arxiv.org/abs/1912.10088) | PaQ-2-PiQ | NR | CVPR2020 | [Official github](https://github.com/baidut/PaQ-2-PiQ) | 40k, 120k patches | 4M |
| [CVF](https://openaccess.thecvf.com/content_CVPR_2020/html/Fang_Perceptual_Quality_Assessment_of_Smartphone_Photography_CVPR_2020_paper.html)  | SPAQ | NR | CVPR2020 | [Offical github](https://github.com/h4nwei/SPAQ) | 11k (smartphone) | |  
| [arXiv](https://arxiv.org/abs/1910.06180) | KonIQ-10k | NR | TIP2020 | [Project](http://database.mmsp-kn.de/koniq-10k-database.html) | 10k from [YFCC100M](http://projects.dfki.uni-kl.de/yfcc100m/) | 1.2M | 
| [arXiv](https://arxiv.org/abs/1511.02919) | CLIVE | NR | TIP2016 | [Project](https://live.ece.utexas.edu/research/ChallengeDB/index.html) | 1200 | 350k |
| [pdf](http://refbase.cvc.uab.es/files/MMP2012a.pdf) | AVA | NR / Aesthentic | CVPR2012 | [Github](https://github.com/mtobeiyf/ava_downloader)/[Project](http://www.lucamarchesotti.com/) | 250k (60 categories) | | 
| [arXiv](https://arxiv.org/abs/2007.12142) | PIPAL | FR | ECCV2020 | [Project](https://www.jasongt.com/projectpages/pipal.html) | 250 | 1.13 M annotations |
| [pdf](https://ece.uwaterloo.ca/~k29ma/papers/17_TIP_EXPLORATION.pdf) | Waterloo-Exp | FR | TIP2017 | [Project](https://ece.uwaterloo.ca/~k29ma/exploration/) | 4744 | 94k distortions | 
| [IEEE](https://ieeexplore.ieee.org/document/8743252) | KADID-10k | FR | QoMEX2019 | [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | 81 | 10k distortions |
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