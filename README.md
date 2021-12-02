# Awesome Image Quality Assessment(IQA)
A collection of IQA (image quality assessment) related papers, data and repositories

## Papers

<!-- ### 2021 -->

### No Reference (NR)

| Title | Model | Type | Published | Code | Keywords | 
| ----------- | ---------- | ------------| ---------- | ------ | ------ |
| MUSIQ: Multi-Scale Image Quality Transformer | MUSIQ | NR | ICCV 2021 | [Official github](https://github.com/google-research/google-research/tree/master/musiq) / [Pytorch Implementation](https://github.com/anse3832/MUSIQ) | Multi-scale, transformer

### Full Reference (FR)

| Title | Model | Type | Published | Code | Keywords | 
| ----------- | ---------- | ------------| ---------- | ------ | ------ |
| The Unreasonable Effectiveness of Deep Features as a Perceptual Metric | LPIPS | FR | CVPR2018 | [Project](https://richzhang.github.io/PerceptualSimilarity/) | Perceptual similarity 
| PieAPP: Perceptual Image-Error Assessment through Pairwise Preference | PieAPP | FR | CVPR2018 | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | Perceptual similarity 

## Datasets 

### IQA datasets

| Paper Title | Dataset Name | Type | Published | Website | Images | Annotations
| ----------- | ---------- | ------------| ---------- | ------ | ------ |------ |
| From Patches to Pictures (PaQ-2-PiQ): Mapping the Perceptual Space of Picture Quality | PaQ-2-PiQ | NR | CVPR2020 | [Official github](https://github.com/baidut/PaQ-2-PiQ) | 40k, 120k patches | 4M |
| Perceptual quality assessment of smartphone photography | SPAQ | NR | CVPR2020 | [Offical github](https://github.com/h4nwei/SPAQ) | 11k (smartphone) | |  
| KonIQ-10k: An ecologically valid database for deep learning of blind image quality assessment | KonIQ-10k | NR | TIP2020 | [Project](http://database.mmsp-kn.de/koniq-10k-database.html) | 10k from [YFCC100M](http://projects.dfki.uni-kl.de/yfcc100m/) | 1.2M | 
| Massive online crowd-sourced study of subjective and objective picture quality | CLIVE | NR | TIP2016 | [Project](https://live.ece.utexas.edu/research/ChallengeDB/index.html) | 1200 | 350k |
| A Large-Scale Database for Aesthetic Visual Analysis | AVA | NR / Aesthentic | CVPR2012 | [Github](https://github.com/mtobeiyf/ava_downloader)/[Project](http://www.lucamarchesotti.com/) | 250k (60 categories) | | 
| PIPAL: A large-scale image quality assessment dataset for perceptual image restoration | PIPAL | FR | ECCV2020 | [Project](https://www.jasongt.com/projectpages/pipal.html) | 250 | 1.13 M annotations |
| Waterloo exploration database: New challenges for image quality assessment models | Waterloo-Exp | FR | TIP2017 | [Project](https://ece.uwaterloo.ca/~k29ma/exploration/) | 4744 | 94k distortions | 
| KADID-10k: A large-scale artificially distorted IQA database | KADID-10k | FR | QoMEX2019 | [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | 81 | 10k distortions |
| MDID: A multiply distorted image database for image quality assessment | MDID | FR | PR2017 | --- | 20 | 1600 distortions  |
| Color image database TID2013: Peculiari- ties and preliminary results | TID2013 | FR | SP2015 | [Project](http://www.ponomarenko.info/tid2013.htm) | 25 | 3000 distortions |
| Most apparent distortion: full-reference image quality assessment and the role of strategy | CSIQ | FR | Journal of Electronic Imaging 2010 | --- | 30 | 866 distortions |
| TID2008: A Database for Evaluation of FullReference Visual Quality Assessment Metrics | TID2008 | FR | 2009 | [Project](http://www.ponomarenko.info/tid2008.htm) | 25 | 1700 distortions |
| A statistical evaluation of recent full reference image quality assessment algorithms | LIVE IQA | FR | TIP2006 | [Project](https://live.ece.utexas.edu/research/Quality/subjective.htm) | 29 images, 780 synthetic distortions 
| Subjective quality assessment irccyn/ivc database | IVC | FR | 2005 | --- | 10 | 185 distortions |

### Perceptual similarity datasets

| Paper Title | Dataset Name | Type | Published | Website | Images | Annotations |  
| ----------- | ---------- | ------------| ---------- | ------ | ------ | ----- |
| The Unreasonable Effectiveness of Deep Features as a Perceptual Metric | BAPPS | FR | CVPR2018 | [Project](https://richzhang.github.io/PerceptualSimilarity/) | 187.7k  | 484k 
| PieAPP: Perceptual Image-Error Assessment through Pairwise Preference | PieAPP | FR | CVPR2018 | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | 200 images | 2.3M 