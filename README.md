---
description: Deep learning papers notes sharing
---

# 😀 Overview

### Related

* [Datasets Resources](related/datasets.md)
* [Nice Expression](related/nice-expressions.md)
* [Research Methods](related/howtodoresearch.md) (*public information summery*)
* [Paper Resource Links](related/papersource.md)

### Basics

* [图像处理基础知识](basic-knowledge/image-processing.md)

### Backbone

**骨干网络**，多为图像分类的网络。

* [x] [Attention Is All You Need](backbone/transformer.md) (_NeurIPS '17_) **[[Paper](https://proceedings.neurips.cc/paper/7181-attention-is-all)]** **[[Code_official](https://github.com/tensorflow/tensor2tensor/blob/master/tensor2tensor/models/transformer.py)]** **[[Code_community](https://github.com/jadore801120/attention-is-all-you-need-pytorch)]**
* [x] [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](backbone/efficientnet.md) (_ICML '19_) **[[Paper](https://arxiv.org/abs/1905.11946)]** **[[Code](https://github.com/tensorflow/tpu/tree/master/models/official/efficientnet)]**
* [x] [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](backbone/vit.md) (_ICLR '21_) **[[Paper](https://arxiv.org/abs/2010.11929)]** **[[Code](https://github.com/google-research/vision_transformer)]**
* [x] [Multi-Dimensional Model Compression of Vision Transformer](backbone/multi-dimensional-compression-vit.md) (_ICME '22_) **[[Paper](https://arxiv.org/abs/2201.00043)]**
* [x] Deep Residual Learning for Image Recognition (_CVPR '16_) **[[Paper](https://arxiv.org/abs/1512.03385)]**
* [ ] Generative Adversarial Networks (_NeurIPS '14_) **[[Paper](https://papers.nips.cc/paper/2014/hash/5ca3e9b122f61f8f06494c97b1afccf3-Abstract.html)]**
* [ ] Masked Auto-Encoders Meet Generative Adversarial Networks and Beyond (_CVPR '23_) **[[Paper](https://feizc.github.io/resume/ganmae.pdf)]**
* [ ] A Kernel Perspective of Skip Connections in Convolutional Networks (_ICLR '23_) **[[Paper](https://arxiv.org/abs/2211.14810)]**
* [ ] EfficientViT: Memory Efficient Vision Transformer with Cascaded Group Attention (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2305.07027)]** **[[Code](https://github.com/microsoft/Cream/tree/main/EfficientViT)]** **[[Note_community](https://blog.csdn.net/P_LarT/article/details/130687567)]**

### Image Tampering

**图像篡改检测定位**

#### Image Editing

<details><summary>2020 and before</summary>
<p>

* [ ] LSTM and encoder–decoder architecture for detection of image forgeries (_TIP '19_) **[[Paper](https://arxiv.org/abs/1903.02495)]** **[[Code](https://github.com/jawadbappy/forgery_localization_HLED)]**
* [ ] ManTra-Net: Manipulation Tracing Network for Detection and Localization of Image Forgeries With Anomalous Features (_CVPR '19_) **[[Paper](https://ieeexplore.ieee.org/document/8953774)]** **[[Code](https://github.com/ISICV/ManTraNet)]** 
* [ ] A Full-Image Full-Resolution End-to-EndTrainable CNN Framework for Image Forgery Detection (_IEEE Access '20_) **[[Paper]()]
* [ ] Constrained R-CNN: A general image manipulation detection model (_ICME '20_) **[[Paper](https://arxiv.org/abs/1911.08217)]** **[[Code](https://github.com/VedantWani/Constrained-R-CNN)]**
* [ ] A CNNBased Camera Model Fingerprint (_TIFS '20_) **[[Paper]()]
* [ ] An Adaptive Neural Network for Unsupervised Mosaic Consistency Analysis in Image Forensics (_CVPR '20_) **[[Paper]()]
* [ ] A dense u-net with cross-layer intersection for detection and localization of image forgery (_ICASSP '20_) **[[Paper](https://ieeexplore.ieee.org/document/9054068)]** **[[Note_unofficial](https://blog.csdn.net/weixin_45366180/article/details/128413821)]**
* [x] [Generate, Segment, and Refine: Towards Generic Manipulation Segmentation](image-forgery/gsrnet.md)  (_AAAI '20_) **[[Paper](https://arxiv.org/abs/1811.09729)]** **[[Code](https://github.com/pengzhou1108/GSRNet)]** (*GSRNet*)
* [ ] SPAN: Spatial Pyramid Attention Network for Image Manipulation Localization  (*ECCV '20*) **[[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660307.pdf)]** **[[Project](http://media.ee.ntu.edu.tw/research/SPAN/)]** **[[Code](https://github.com/tsaishien-chen/SPAN)]**

</p>
</details>

<details><summary>2021</summary>
<p>

* [ ] MSTA-Net: Forgery Detection by Generating Manipulation Trace Based on Multi-Scale Self-Texture Attention (_TCSVT '21_) **[[Paper](https://ieeexplore.ieee.org/document/9643421)]**
* [ ] Image Manipulation Detection by Multi-View Multi-Scale Supervision (_ICCV '21_)  **[[Paper](https://arxiv.org/abs/2104.06832)]** **[[Code](https://github.com/dong03/MVSS-Net)]**
* [x] [TransForensics: Image Forgery Localization with Dense Self-Attention](image-forgery/transforensics.md) (_ICCV '21_) **[[Paper](https://arxiv.org/abs/2108.03871)]**
* [ ] Self-supervised Domain Adaptation for Forgery Localization of JPEG Compressed Images (_ICCV '21_) **[[Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Rao_Self-Supervised_Domain_Adaptation_for_Forgery_Localization_of_JPEG_Compressed_Images_ICCV_2021_paper.html)]** 
* [ ] Image Tampering Localization Using a Dense Fully Convolutional Network (_TIFS '21_) **[[Paper](https://ieeexplore.ieee.org/document/9393396)]** **[[Code](https://github.com/ZhuangPeiyu/Dense-FCN-for-tampering-localization)]** (*DenseFCN*)
* [ ] Image Manipulation Localization Using Attentional Cross-Domain CNN Features (_TNNLS '21_) **[[Paper](https://doi.org/10.1109/TNNLS.2021.3130168)]**

</p>
</details>

<details open><summary>2022</summary>
<p>

* [ ] MSMG-Net: Multi-scale Multi-grained Supervised Metworks for Multi-task Image Manipulation Detection and Localization (_ArXiv '22_) **[[Paper](https://arxiv.org/abs/2211.03140)]**
* [ ] Towards JPEG-Resistant Image Forgery Detection and Localization Via Self-Supervised Domain Adaptation (_TPAMI '22_) **[[Paper](https://ieeexplore.ieee.org/document/9904872)]** 
* [ ] ESRNet: Efficient Search and Recognition Network for Image Manipulation Detection (_TOMCCAP '22_) **[[Paper](https://doi.org/10.1145/3506853)]** **[[Tool](https://github.com/tampered816/rrr)]**
* [ ] Learning to localize image forgery using end-to-end attention network (_Neurocomputing '22_) **[[Paper](https://www.sciencedirect.com/science/article/pii/S0925231222011274)]** **[[Code](https://github.com/sadaf-ali/-Learning-to-Localize-Image-Forgery-Using-End-to-End-Attention-Network)]**
* [ ] MVSS-Net: Multi-View Multi-Scale Supervised Networks for Image Manipulation Detection (_TPAMI '22_) **[[Paper](https://arxiv.org/abs/2112.08935)]** **[[Code](https://github.com/dong03/MVSS-Net)]**
* [ ] [Robust Image Forgery Detection Over Online Social Network Shared Images](image-forgery/ifosn.md) (_CVPR '22_) **[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_Robust_Image_Forgery_Detection_Over_Online_Social_Network_Shared_Images_CVPR_2022_paper.pdf)]** **[[Code](https://github.com/HighwayWu/ImageForensicsOSN)]**
* [x] [ObjectFormer for Image Manipulation Detection and Localization](image-forgery/objectformer.md) (_CVPR '22_) **\[**[**Paper**](https://arxiv.org/abs/2203.14681)**]**
* [ ] GCA-Net: Utilizing Gated Context Attention for Improving Image Forgery Localization and Detection (_CVPRW '22_) **[[Paper](https://arxiv.org/abs/2112.04298)]** 
* [ ] Non-Semantic Evaluation of Image Forensics Tools: Methodology and Database (_WACV '22_) **[[Paper](https://arxiv.org/abs/2105.02700)]** **[[Code](https://github.com/qbammey/trace)]**
* [ ] [JPEG Compression-aware Image Forgery Localization](caifl.md) (_MM '22_) **[[Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3547749)]**
* [ ] [Image Manipulation Localization Using Multi-Scale Feature Fusion and Adaptive Edge Supervision](image-forgery/msff.md) (_TMM '22_) **[[Paper](https://ieeexplore.ieee.org/document/9996125/)]** 
* [ ] [ReLoc: A Restoration-Assisted Framework for Robust Image Tampering Localization](image-forgery/reloc.md) (_ArXiv '22_) **[[Paper](https://arxiv.org/abs/2211.03930)]** **[[Code](https://github.com/ZhuangPeiyu/ReLoc)]**
* [x] [PSCC-Net: Progressive Spatio-Channel Correlation Network for Image Manipulation Detection and Localization](image-forgery/pscc-net.md) (_TCSVT '22_) **[[Paper](https://arxiv.org/abs/2103.10596)]** **[[Code](https://github.com/proteus1991/PSCC-Net)]**
* [x] [Self-Adversarial Training incorporating Forgery Attention for Image Forgery Localization](image-forgery/satfl.md) (_TIFS '22_) **[[Paper](https://arxiv.org/abs/2107.02434)]** **[[Code](https://github.com/tansq/SATFL)]** (*LocateNet / SATFL*)
* [ ] M2TR: Multi-modal Multi-scale Transformers for Deepfake Detection (_ICMR '22_) **[[Paper](https://arxiv.org/abs/2104.09770)]** **[[Code](https://github.com/wangjk666/M2TR-Multi-modal-Multi-scale-Transformers-for-Deepfake-Detection)]**
* [ ] A Principled Design of Image Representation: Towards Forensic Tasks (_TPAMI '22_) **[[Paper](https://arxiv.org/abs/2203.00913)]** **[[Code](https://github.com/ShurenQi/DIR)]**
* [ ] [TBNet: A Two-stream Boundary-aware Network for Generic Image Manipulation Localization](image-forgery/tbanet.md) (_KDE '22_) **[[Paper](https://arxiv.org/abs/2108.04508)]**
* [ ] [Learning JPEG Compression Artifacts for Image Manipulation Detection and Localization](image-forgery/catnetv2.md) (_IJCV '22_) **[[Paper](https://arxiv.org/abs/2108.12947)]** **[[Code](https://github.com/mjkwon2021/CAT-Net)]**

</p>
</details>

<details open><summary>2023 This year</summary>
<p>

* [ ] Image manipulation detection by multiple tampering traces and edge artifact enhancement (_PR '23_) **[[Paper](https://www.sciencedirect.com/science/article/pii/S0031320322005064)]** (*EMT-Net*)
* [x] [CFL-Net: Image Forgery Localization Using Contrastive Learning](image-forgery/cfl-net.md) (_WACV '23_) **[[Paper](https://arxiv.org/abs/2210.02182)]** **[[Code](https://github.com/niloy193/CFLNet)]**
* [x] [TruFor: Leveraging all-round clues for trustworthy image forgery detection and localization](image-forgery/trufor.md) (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2212.10957)]** **[[Project](https://grip-unina.github.io/TruFor/)]** **[[Code](https://github.com/grip-unina/TruFor)]**
* [x] [TBFormer: Two-Branch Transformer for Image Forgery Localization](image-forgery/tbformer.md)  (_SPL '23_) **[[Paper](https://arxiv.org/abs/2302.13004)]**  **[[Code](https://github.com/free1dom1/tbformer)]**
* [ ] [Detecting and Grounding Multi-Modal Media Manipulation](image-forgery/dgm4.md) (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2304.02556)]**  **[[Code](https://github.com/rshaojimmy/MultiModal-DeepFake)]** **[[Project](https://rshaojimmy.github.io/Projects/MultiModal-DeepFake)]**
* [x] [Hierarchical Fine-Grained Image Forgery Detection and Localization](image-forgery/hifi_ifdl.md) (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2303.17111)]**  **[[Code](https://github.com/CHELSEA234/HiFi_IFDL)]**
* [ ] [Edge-aware Regional Message Passing Controller for Image Forgery Localization](image-forgery/ermpc.md) (_CVPR '23_) **[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Edge-Aware_Regional_Message_Passing_Controller_for_Image_Forgery_Localization_CVPR_2023_paper.pdf)]** **[[Video](https://youtu.be/2pDR-hOFcQw)]**
* [ ] AutoSplice: A Text-prompt Manipulated Image Dataset for Media Forensics (_CVPRW '23_) **[[Paper](https://arxiv.org/abs/2304.06870)]** **[[Dataset](https://github.com/shanface33/autosplice_dataset)]**
* [ ] CTP-Net: Character Texture Perception Network for Document Image Forgery Localization (_arXiv '23_) **[[Paper](https://arxiv.org/abs/2308.02158v1)]** 
* [ ] IML-ViT: Image Manipulation Localization by Vision Transformer (_arXiv '23_) **[[Paper](https://arxiv.org/abs/2307.14863)]** **[[Code](https://github.com/SunnyHaze/IML-ViT)]**

</p>
</details>

#### CNN-synthesized

*Some of the above papers also contain methods to detect tampered images generated by GANs or DMs for synthetic images*

* [ ] MaLP: Manipulation Localization Using a Proactive Scheme (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2303.16976)]**  **[[Code](https://github.com/vishal3477/pro_loc)]**
* [ ] Discrepancy-Guided Reconstruction Learning for Image Forgery Detection (_IJCAI '23_) **[[Paper](https://arxiv.org/abs/2304.13349)]** **[[Code](https://github.com/znshi/DisGRL)]**
* [ ] Generalizable Synthetic Image Detection via Language-guided Contrastive Learning (_ArXiv '23_) **[[Paper](https://arxiv.org/abs/2305.13800)]** **[[Code](https://github.com/HighwayWu/LASTED)]**
* [ ] Detect Any Deepfakes: Segment Anything Meets Face Forgery Detection and Localization (_ArXiv '23_) **[[Paper](https://arxiv.org/abs/2306.17075)]** **[[Code](https://github.com/laiyingxin2/DADF)]**
* [ ] Discrepancy-Guided Reconstruction Learning for Image Forgery Detection (_ArXiv '23_) **[[Paper](https://arxiv.org/abs/2304.13349)]** 
* [ ] Masked Relation Learning for DeepFake Detection (_TIFS '23_) **[[Paper](https://doi.org/10.1109/TIFS.2023.3249566)]**  

### Image Splicing

**图像的拼接篡改检测定位**

<details><summary>2020 and before</summary>
<p>

* [ ] Deep matching and validation network: An end-to-end solution to constrained image splicing localization and detection (_MM '17_) **[[Paper](https://arxiv.org/abs/1705.09765)]**

* [ ] Image Splicing Localization via Semi-global Network and Fully Connected Conditional Random Fields (_ECCV '18_)

* [ ] Image splicing localization using a multi-task fully convolutional network (mfcn) (_JVCIR '18_) **[[Paper](https://arxiv.org/abs/1709.02016)]** **[[Code](https://github.com/namtpham/image_tampering_detection_references.git)]**

* [x] [Fighting Fake News: Image Splice Detection via Learned Self-Consistency](image-splicing/self-consistency.md) (_ECCV '18_) **[[Paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Jacob_Huh_Fighting_Fake_News_ECCV_2018_paper.html)]** **[[Code](https://github.com/minyoungg/selfconsistency)]**

* [ ] Deep Fusion Network for Splicing Forgery Localization (_ECCV '18_)

* [ ] Adversarial Learning for Constrained Image Splicing Detection and Localization Based on Atrous Convolution (_TIFS '19_) **[[Paper](https://ieeexplore.ieee.org/document/8658131)]** **[[Code](https://github.com/yaqiliu-cs/CISDL-DMAC)]**

* [ ] [RRU-Net: The Ringed Residual U-Net for Image Splicing Forgery Detection](image-splicing/rru-net.md) (_CVPRW' 19_) **[[Paper](http://openaccess.thecvf.com/content_CVPRW_2019/html/CV-COPS/Bi_RRU-Net_The_Ringed_Residual_U-Net_for_Image_Splicing_Forgery_Detection_CVPRW_2019_paper.html?ref=https://githubhelp.com)]** **[[Code](https://github.com/yelusaleng/RRU-Net)]**

* [ ] Mixed adversarial generators for image splice detection (_NeuIPS '19_) **[[Paper](https://papers.nips.cc/paper/8315-the-point-where-reality-meets-fantasy-mixed-adversarial-generators-for-image-splice-detection)]** **[[Code](https://github.com/vlkniaz/MAGritte)]** 

* [ ] Exposing splicing forgery in realistic scenes using deep fusion network (_InfoS '20_) **[[Paper](https://www.sciencedirect.com/science/article/pii/S0020025520302796)]**

* [ ] Locating splicing forgery by adaptive-SVD noise estimation and vicinity noise descriptor (_Neurocomputing '20_)

</p>
</details>

<details open><summary>Since 2021</summary>
<p>

* [x] [CAT-Net: Compression Artifact Tracing Network for Detection and Localization of Image Splicing](image-splicing/cat-net.md) (_WACV '21_) **[[Paper](https://ieeexplore.ieee.org/document/9423390)]** **[[Code](https://github.com/mjkwon2021/CAT-Net)]**
* [ ] Image Splicing Detection, Localization and Attribution via JPEG Primary Quantization Matrix Estimation and Clustering (_TIFS '21_) **[[Paper](https://ieeexplore.ieee.org/document/9622213)]** **[[Code](https://github.com/andreacos/CnnJpegPrimaryQuantizationEstimation)]**
* [ ] Multiple Image Splicing Dataset (MISD): A Dataset for Multiple Splicing (_Data, MDPI '21_) **[[Paper](https://arxiv.org/abs/2108.09674)]** 
* [ ] Reality Transform Adversarial Generators for Image Splicing Forgery Detection and Localization (_ICCV '21_) **[[Paper](http://openaccess.thecvf.com/content/ICCV2021/html/Bi_Reality_Transform_Adversarial_Generators_for_Image_Splicing_Forgery_Detection_and_ICCV_2021_paper.html)]** 
* [x] [Multi-Task Wavelet Corrected Network for Image Splicing Forgery Detection and Localization](image-splicing/mwc-net.md) (_ICME '21_) **[[Paper](https://ieeexplore.ieee.org/abstract/document/9428466/)]** 
* [ ] Detection and Localization of Multiple Image Splicing Using MobileNet V1 (_IEEE Access '21_) **[[Paper](https://arxiv.org/abs/2108.09674)]**
* [x] [Multi-Task SE-Network for Image Splicing Localization](image-splicing/multi-task-se-network.md) (_TCSVT '22_) **[[Paper](https://ieeexplore.ieee.org/document/9591639)]** **[[Code](https://github.com/YulansZhang/Multi-task-SE-Network-for-Image-Splicing-Localization)]**
* [x] [ET: Edge-Enhanced Transformer for Image Splicing Detection](image-splicing/et.md) (_SPL '22_) **[[Paper](https://ieeexplore.ieee.org/document/9769936)]**
* [x] [Image splicing forgery detection by combining synthetic adversarial networks and hybrid dense U-net based on multiple spaces](image-splicing/san-and-hdu-net.md) (_IJIS '22_) **[[Paper](https://doi.org/10.1002/int.22939)]** **[[Code](https://github.com/yelusaleng/SAN_and_HDU-Net)]**
* [x] [SISL:Self-Supervised Image Signature Learning for Splicing Detection & Localization](image-splicing/sisl.md) (_CVPRW '22_) **[[Paper](https://arxiv.org/abs/2203.07824)]**
* [ ] Deep Metric Color Embeddings for Splicing Localization in Severely Degraded Images (_TIFS '22_) **[[Paper](https://arxiv.org/abs/2206.10737)]**
* [ ] Coarse-to-fine-grained method for image splicing region detection (_PR '22_) **[[Paper](https://doi.org/10.1016/j.patcog.2021.108347)]**
* [ ] A New Method to Detect Splicing Image Forgery Using Convolutional Neural Network (_Applied Science (IM: 2.8, not included in CCFs), MDPI, '23_) **[[Paper](https://www.mdpi.com/2076-3417/13/3/1272)]**

</p>
</details>

### Image Harmonization

**图像协调化**

* [ ] Toward Realistic Image Compositing with Adversarial Learning (_CVPR '19_) **[[Paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Toward_Realistic_Image_Compositing_With_Adversarial_Learning_CVPR_2019_paper.html)]** **[[Code_unofficial](https://github.com/SuhyeonHa/GCC-GANs)]**
* [x] [Image Harmonization with Transformer](image-harmonization/ht-d-ht.md) (_ICCV '21_) **[[Paper](http://openaccess.thecvf.com/content/ICCV2021/html/Guo_Image_Harmonization_With_Transformer_ICCV_2021_paper.html)]** 
* [ ] SSH: A Self-Supervised Framework for Image Harmonization (_ICCV '21_) **[[Paper](https://arxiv.org/abs/2108.06805)]** **[[Code](https://github.com/VITA-Group/SSHarmonization)]**
* [ ] Image Harmonization with Region-wise Contrastive Learning (_ArXiv '22_) **[[Paper](https://arxiv.org/abs/2205.14058)]**
* [ ] [Harmonizer: Learning to Perform White-Box Image and Video Harmonization](image-harmonization/harmonizer.md) (_ECCV '22_) **[[Paper](https://arxiv.org/abs/2207.01322)]** **[[Code](https://github.com/ZHKKKe/Harmonizer)]**
* [ ] Spatial-Separated Curve Rendering Network for Efficient and High-Resolution Image Harmonization (_ECCV '22_) **[[Paper](https://arxiv.org/abs/2109.05750)]** **[[Code](https://github.com/stefanLeong/S2CRNet)]**
* [ ] High-Resolution Image Harmonization via Collaborative Dual Transformations (_CVPR '22_) **[[Paper](https://arxiv.org/abs/2109.06671)]** **[[Code_unofficial](https://github.com/SuhyeonHa/CDTNet-PyTorch)]**
* [ ] [SCS-Co: Self-Consistent Style Contrastive Learning for Image Harmonization](image-harmonization/scs-co.md) (_CVPR '22_) **[[Paper](https://arxiv.org/abs/2204.13962)]** **[[Code](https://github.com/YCHang686/SCS-Co-CVPR2022)]**
* [ ] PCT-Net: Full Resolution Image Harmonization Using Pixel-Wise Color Transformations (_CVPR '23_)
* [ ] Semi-supervised Parametric Real-world Image Harmonization (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2303.00157)]** **[[Code](https://people.eecs.berkeley.edu/~kewang/)]** **[[Project](https://people.eecs.berkeley.edu/~kewang/sprih/)]**
* [ ] LEMaRT: Label-Efficient Masked Region Transform for Image Harmonization(_CVPR '23_) **[[Paper](https://arxiv.org/abs/2304.13166)]**
* [ ] Burstormer: Burst Image Restoration and Enhancement Transformer (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2304.01194)] [[Code](https://github.com/akshaydudhane16/Burstormer.git)]**

###  Face Forgery

**人脸篡改**，篡改方法以及检测问题

* [ ] SSTNet: Detecting Manipulated Faces Through Spatial, Steganalysis and Temporal Features (_ICASSP '20_) **[[Paper](https://ieeexplore.ieee.org/abstract/document/9053969/)]**
* [x] Portrait shadow manipulation (_ACM MM / TOG '20_) **[[Paper](https://arxiv.org/abs/2005.08925)]** **[[Code](https://github.com/google/portrait-shadow-manipulation)]**
* [x] [MC-LCR: Multi-modal contrastive classification by locally correlated representations for effective face forgery detection](face-forgery/mc-lcr.md) (_KBS '22_) **[[Paper](https://arxiv.org/abs/2110.03290)]** 
* [x] [Multi-Scale Wavelet Transformer for Face Forgery Detection](face-forgery/multi-scale-wavelettransformer.md) (_ACCV '22_) **[[Paper](https://arxiv.org/abs/2210.03899)]**
* [ ] Leveraging Real Talking Faces via Self-Supervision for Robust Forgery Detection (_CVPR '22_) **[[Paper](https://arxiv.org/abs/2201.07131)]** **[[Code](https://github.com/ahaliassos/RealForensics)]**
* [ ] AUNet: Learning Relations Between Action Units for Face Forgery Detection (_CVPR '23_)
* [ ] AltFreezing for More General Face Forgery Detection (_CVPR '23_)
* [ ] $F^2$Trans: High-Frequency Fine-Grained Transformer for Face Forgery Detection (_TIFS '23_) **[[Paper](https://ieeexplore.ieee.org/document/10004978)]**
* [ ] On the Security of the One-and-a-Half-Class Classifier for SPAM Feature-Based Image Forensics (_TIFS '23_) **[[Paper](https://ieeexplore.ieee.org/document/10098583)]**
* [ ] Multimodaltrace: Deepfake Detection Using Audiovisual Representation Learning (_CVPRW '23_) **[[Paper](https://openaccess.thecvf.com/content/CVPR2023W/WMF/html/Raza_Multimodaltrace_Deepfake_Detection_Using_Audiovisual_Representation_Learning_CVPRW_2023_paper.html)]**
* [ ] Two-in-one Knowledge Distillation for Efficient Facial Forgery Detection _(arXiv '23')_ **[[Paper](https://arxiv.org/abs/2302.10437)]**
* [ ] Contrastive Multi-FaceForensics: An End-to-end Bi-grained Contrastive Learning Approach for Multi-face Forgery Detection _(arXiv '23')_ **[[Paper](https://arxiv.org/abs/2308.01520v1)]**
* [ ] Learning Patch-Channel Correspondence for Interpretable Face Forgery Detection (_TIP '23_) **[[Paper](https://doi.org/10.1109/TIP.2023.3246793)]** **[[Code](https://github.com/Jae35/IFFD)]**

### Copy Move

**复制移动篡改定位**问题

* [x] [BusterNet: Detecting Copy-Move Image Forgery with Source/Target Localization](copy-move/busternet.md) (_ECCV '18_) **[[Paper](http://openaccess.thecvf.com/content_ECCV_2018/html/Rex_Yue_Wu_BusterNet_Detecting_Copy-Move_ECCV_2018_paper.html)]** **[[Code](https://github.com/isi-vista/BusterNet)]**
* [x] [A Serial Image Copy-Move Forgery Localization Scheme With Source/Target Distinguishment](copy-move/cmsdnet.md) (_TMM '20_) **[[Paper](https://ieeexplore.ieee.org/abstract/document/9207851/)]** **[[Code](https://github.com/imagecbj/A-serial-image-copy-move-forgery-localization-scheme-with-source-target-distinguishment)]**
* [x] [DOA-GAN: Dual-Order Attentive Generative Adversarial Network for Image Copy-Move Forgery Detection and Localization](copy-move/doa-gan.md) (_CVPR '20_) **[[Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Islam_DOA-GAN_Dual-Order_Attentive_Generative_Adversarial_Network_for_Image_Copy-Move_Forgery_CVPR_2020_paper.html)]** **[[Code](https://github.com/asrafulashiq/doagan_clean)]**
* [x] [Two-Stage Copy-Move Forgery Detection with Self Deep Matching and Proposal SuperGlue](copy-move/selfdm-ps.md) (_TIP '22_) **[[Paper](https://arxiv.org/abs/2012.08697)]**
* [ ] QDL-CMFD: A Quality-independent and deep Learning-based Copy-Move image forgery detection method (_Neurocomputing '22_) **[[Paper](https://www.sciencedirect.com/science/article/pii/S0925231222011031)]** **[[Code](https://github.com/MehradAria/QDL-CMFD)]**
* [ ] [Shrinking the Semantic Gap: Spatial Pooling of Local Moment Invariants for Copy-Move Forgery Detection](copy-move/word2phrasecmfd.md) _(TIFS '23)_ **[[Paper](https://arxiv.org/abs/2207.09135)]** **[[Code](https://github.com/ChaoWang1016/word2phraseCMFD)]**

### Image Matching

**特征匹配**，图像匹配问题。

* [x] [LoFTR: Detector-Free Local Matching with Transformers](image-matching/loftr.md) (_CVPR '21_) **[[Paper](https://arxiv.org/abs/2104.00680)]** **[[Code](https://github.com/zju3dv/LoFTR)]**
* [ ] PATS: Patch Area Transportation with Subdivision for Local Feature Matching (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2303.07700)]** **[[Code](https://github.com/zju3dv/pats)]** **[[Project](https://zju3dv.github.io/pats/)]**
* [ ] Adaptive Spot-Guided Transformer for Consistent Local Feature Matching (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2303.16624)]** **[[Code](https://github.com/ASTR2023/ASTR)]** **[[Project](https://astr2023.github.io/)]**
* [ ] ObjectMatch: Robust Registration using Canonical Object Correspondences (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2212.01985)]** **[[Code](https://github.com/cangumeli/ObjectMatch)]** **[[Project](https://cangumeli.github.io/ObjectMatch/)]**

### Object Detection

**目标检测**，包括伪装物体目标检测和突出目标检测，COD以及SOD。

* [ ] OTA: Optimal Transport Assignment for Object Detection (_CVPR '21_) **[[Paper](https://arxiv.org/abs/2103.14259)]** **[[Code](https://github.com/Megvii-BaseDetection/OTA)]**
* [ ] Consistency-basd Active Learning for Object Detection (_CVPRW '22_) **[[Paper](http://128.84.21.203/abs/2103.10374)]** **[[Code](https://github.com/we1pingyu/CALD)]**
* [ ] [Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection](object-dection/zoomnet-cod.md) (_CVPR '22_) **[[Paper](https://arxiv.org/abs/2203.02688)]** **[[Code](https://github.com/lartpang/ZoomNet)]**
* [ ] Unsupervised Object Localization: Observing the Background to Discover Objects (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2212.07834)]** **[[Code](https://github.com/valeoai/FOUND)]**
* [ ] Camouflaged Object Detection with Feature Decomposition and Edge Reconstruction (_CVPR '23_) **[[Paper](https://openreview.net/pdf?id=lin5jPqCQ6)]** **[[Code](https://github.com/ChunmingHe/FEDER)]**
* [ ] Feature Shrinkage Pyramid for Camouflaged Object Detection with Transformers  (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2303.14816)]** **[[Code](https://github.com/ZhouHuang23/FSPNet)]**
* [ ] Locate, Refine and Restore: A Progressive Enhancement Network for Camouflaged Object Detection (_IJCAI '23_)

### Semantic Segmentation

语义分割，将图片中完整语义（具有标签或者类别）的部分分割出来。不仅要进行目标检测检测到图像中的物体，还需要对每个像素分类。

* [ ] [Generative Semantic Segmentation](semantic-segmentation/gss.md) (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2303.11316)]** **[[Code](https://github.com/fudan-zvg/GSS)]**
* [ ] EfficientViT: Lightweight Multi-Scale Attention for On-Device Semantic Segmentation **[[Paper](https://arxiv.org/abs/2205.14756)]** **[[Code](https://github.com/mit-han-lab/efficientvit)]**
* [ ] CAT-Seg: Cost Aggregation for Open-Vocabulary Semantic Segmentation **[[Paper](https://arxiv.org/abs/2303.11797)]** **[[Code](https://github.com/KU-CVLAB/CAT-Seg)]** **[[Project](https://ku-cvlab.github.io/CAT-Seg/)]** **[[Note_community](https://blog.csdn.net/P_LarT/article/details/131083586)]**

### Low Level Vision

Related resources: [https://github.com/Kobaayyy/Awesome-ICCV2021-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-ICCV2021-Low-Level-Vision) 

Low-level tasks include super-resolution, denoise, dehze, low-light enhancement, etc. High-level tasks include classification, detection, segmentation, etc. segmentation, and so on. However, the ones I have listed here are probably still mainly related to tampering detection.

* [ ] (**EVP**) Explicit Visual Prompting for Low-Level Structure Segmentations   (_CVPR '23_) **[[Paper](https://arxiv.org/abs/2303.10883)]** **[[Code](https://github.com/NiFangBaAGe/Explicit-Visual-Prompt)]** (_including defocus blur, shadow, forgery, camouflaged dection_)

### Useful Links

1. ICLR 2023 Papers List https://openreview.net/group?id=ICLR.cc/2023/Conference
2. CVPR 2023 Accepted Papers https://cvpr2023.thecvf.com/Conferences/2023/AcceptedPapers
2. CVPR 2023 Workshops https://openaccess.thecvf.com/CVPR2023_workshops/menu
3. WACV 2023 Papers https://openaccess.thecvf.com/WACV2023
4. IJCAI 2023 Accepted Papers List https://ijcai-23.org/main-track-accepted-papers/
5. ECCV 2022 Accepted papers https://eccv2022.ecva.net/program/accepted-papers/
6. MM 2022 Proceedings https://dl.acm.org/doi/proceedings/10.1145/3503161
7. SIGGRAPH *unofficial* https://kesen.realtimerendering.com/ eg SIGGRAPH 2023 https://kesen.realtimerendering.com/sig2023.html
8. ICML 2022 https://dblp.org/db/conf/icml/icml2022.html
9. AAAI 2022 https://dblp.org/db/conf/aaai/aaai2022.html
10. TIFS https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206
10. [More...](related/papersource.md)


### [Back to Home](https://zihol.gitbook.io/)
