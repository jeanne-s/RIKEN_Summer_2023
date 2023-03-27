# Image-to-image translation to transform brain images from one modality to another

### RIKEN Center for Brain Science Summer Internship 2023





## Reviews and General Papers

**Diffusion Models for Medical Image Analysis: A Comprehensive Survey**\
Amirhossein Kazerouni, Ehsan Khodapanah Aghdam, Moein Heidari, Reza Azad, Mohsen Fayyaz, Ilker Hacihaliloglu, Dorit Merhof\
[14th Nov., 2022] [arXiv, 2022]\
[[Paper](https://arxiv.org/abs/2211.07804)] [[GitHub](https://github.com/amirhossein-kz/Awesome-Diffusion-Models-in-Medical-Imaging#image-to-image-translation)]





## Image-to-Image Translation Papers

**[MT-Diffusion] Conversion Between CT and MRI Images Using Diffusion and Score-Matching Models**\
Qing Lyu, Ge Wang\
[24th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.12104)]


**[UMM-CSGM] A Novel Unified Conditional Score-based Generative Framework for Multi-modal Medical Image Completion**\
Xiangxi Meng, Yuning Gu, Yongsheng Pan, Nizhuan Wang, Peng Xue, Mengkang Lu, Xuming He, Yiqiang Zhan, Dinggang Shen\
[7th Jul., 2022] [arXiv, 2022]\
[[Paper](https://arxiv.org/abs/2207.03430)]


**[SynDiff] Unsupervised Medical Image Translation with Adversarial Diffusion Models**\
Muzaffer Özbey, Salman UH Dar, Hasan A Bedel, Onat Dalmaz, Şaban Özturk, Alper Güngör, Tolga Çukur\
[17th Jul., 2022] [arXiv, 2022]\
[[Paper](https://arxiv.org/abs/2207.08208)] [[GitHub](https://github.com/icon-lab/SynDiff)]
> SynDiff is the ﬁrst adversarial diffusion model for medical image synthesis, and the ﬁrst unsupervised diffusion model for medical image translation
in the literature. It performs unsupervised diffusion-based translation in multi-contrast MRI and multi-modal MRI-CT. It leverages a diffusion model with an adversarial projector for efﬁcient and accurate image sampling over few large diffusion steps. Furthermore, it introduces a novel cycle-consistent architecture combining diffusive and non-diffusive modules to enable unsupervised training.

**[UNIT-DDPM] UNIT-DDPM: UNpaired Image Translation with Denoising Diffusion Probabilistic Models**\
Hiroshi Sasaki, Chris G. Willcocks, Toby P. Breckon\
[12th Apr., 2021] [arXiv, 2021]\
[[Paper](https://arxiv.org/abs/2104.05358)]




## Datasets

**[Marmoset Gene Atlas]**
> **Digital gene atlas of neonate common marmoset brain**\
Shimogori T et al.\
[[Paper](https://pubmed.ncbi.nlm.nih.gov/29111135/)]\
> **Cellular-resolution gene expression profiling in the neonatal marmoset brain reveals dynamic species and region-specific differences**\
Kita et al.\
[[Paper](https://www.pnas.org/doi/10.1073/pnas.2020125118)]

[[Download](https://gene-atlas.brainminds.jp/)]

**[Ixi Dataset]**\
[[Download](https://brain-development.org/ixi-dataset/)]\
600 MR images from healthy subjects : T1, T2 and PD-weighted images, MRA images, diffusion-weighted images (15 directions). Used in SynDiff paper.

**[BRATS Dataset] The Multimodal Brain Tumor Image Segmentation Benchmark (BRATS)**\
Menze BH at al.\
[[Paper](https://pubmed.ncbi.nlm.nih.gov/25494501/)] [[Download](https://www.kaggle.com/datasets/awsaf49/brats2020-training-data)]\
T1, T2, Fluid Attenuation Inversion Recovery (FLAIR) weighted brain MR images. Used in SynDiff paper.

**[Gold Atlas Male Pelvis] MR and CT Data with Multi Observer Delineations of Organs in the Pelvic Area - Part of the Gold Atlas Project**\
Nyholm, Tufve, Stina Svensson, Sebastian Andersson, Joakim Jonsson, Maja Sohlin, Christian Gustafsson, Elisabeth Kjellén, et al.\
[[Paper](https://aapm.onlinelibrary.wiley.com/doi/full/10.1002/mp.12748)] [[Download](https://zenodo.org/record/583096#.ZBtiLxyZNH4)]\
MRI (T1w and T2w) with flat table top, and CT images of 19 male patients for MRI to CT translation. Used in SynDiff paper.

