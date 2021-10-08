# <p align=center>`Awesome Text_to_Image papers`</p>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of resources on general text-to-image synthesis task.

## <span id="head-content"> *Content* </span>
* - [x] [1. Description](#head1)

* - [x] [2. Quantitative Evaluation Metrics](#head2)
  * [Inception Score (IS)](#head-IS)
  * [Fréchet Inception Distance (FID)](#head-FID)  
  * [R-precision](#head-R)
  * [L<sub>2</sub> error](#head-L2)
  
* - [x] [3. Datasets](#head3)  
  * [Caltech-UCSD Bird (CUB)](#head-CUB)
  * [Oxford-102 Flower](#head-Flower)
  * [MS-COCO](#head-COCO)
  * [Multi-Modal-CelebA-HQ](#head-Multi-Modal-CelebA-HQ)
  
* - [ ] [4. Paper With Code](#head4)
  
* - [ ] [5. Other Related Works](#head5)
  * - [ ] [Text+Image → Image](#head-TI2I)
  * - [ ] [Text → Video](#head-T2V)


 ## <span id="head1"> *1.Description* </span>

* In the last few decades, the fields of Computer Vision (CV) and Natural Language Processing (NLP) have been made several major technological breakthroughs in deep learning research. Recently, researchers appear interested in combining semantic information and visual information in these traditionally independent fields. 
A number of studies have been conducted on the text-to-image synthesis techniques that transfer input textual description (keywords or sentences) into realistic images.

* Papers, codes and datasets for the text-to-image task are available here.

 ## <span id="head2"> *2.Quantitative Evaluation Metrics* </span>

* <span id="head-IS"> Inception Score (IS) </span> [[Paper](https://arxiv.org/pdf/1606.03498.pdf)] [[Python Code (Pytorch)](https://github.com/sbarratt/inception-score-pytorch)] [[Python Code (Tensorflow)](https://github.com/taki0112/GAN_Metrics-Tensorflow)][[code(attgan)]](https://github.com/taoxugit/AttnGAN)

* <span id="head-FID"> Fréchet Inception Distance (FID) </span> [[Paper](https://papers.nips.cc/paper/7240-gans-trained-by-a-two-time-scale-update-rule-converge-to-a-local-nash-equilibrium.pdf)] [[Python Code (Pytorch)](https://github.com/mseitzer/pytorch-fid)] [[Python Code (Tensorflow)](https://github.com/taki0112/GAN_Metrics-Tensorflow)][[code(DM_GAN)]](https://github.com/MinfengZhu/DM-GAN)

* <span id="head-R"> R-precision </span> [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_AttnGAN_Fine-Grained_Text_CVPR_2018_paper.pdf)][[code(CPGAN)]](https://github.com/dongdongdong666/CPGAN)

* <span id="head-L2"> L<sub>2</sub> error </span> [[Paper](https://papers.nips.cc/paper/7290-text-adaptive-generative-adversarial-networks-manipulating-images-with-natural-language.pdf)]

## <span id="head3"> *3.Datasets* </span>

* <span id="head-CUB"> **Caltech-UCSD Bird(CUB)** </span>

  Caltech-UCSD Birds-200-2011 (CUB-200-2011) is an extended version of the CUB-200 dataset, with roughly double the number of images per class and new part location annotations.
  * **Detailed information (Images):**  ⇒ [[Paper](http://www.vision.caltech.edu/visipedia/papers/CUB_200_2011.pdf)] [[Website](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html)]
    * Number of different categories: 200 (**Training**: 150 categories. **Testing**: 50 categories.)
    * Number of bird images: 11,788
    * Annotations per image: 15 Part Locations, 312 Binary Attributes, 1 Bounding Box, Ground-truth Segmentation
  * **Detailed information (Text Descriptions):**  ⇒ [[Paper](https://openaccess.thecvf.com/content_cvpr_2016/papers/Reed_Learning_Deep_Representations_CVPR_2016_paper.pdf)] [[Website](https://drive.google.com/file/d/0B0ywwgffWnLLZW9uVHNjb2JmNlE/view)]
    * Descriptions per image: 10 Captions
    
* <span id="head-Flower"> **Oxford-102 Flower** </span>

  Oxford-102 Flower is a 102 category dataset, consisting of 102 flower categories. The flowers are chosen to be flower commonly occurring in the United Kingdom. The images have large scale, pose and light variations. 
  * **Detailed information (Images):**  ⇒ [[Paper](http://www.robots.ox.ac.uk/~vgg/publications/2008/Nilsback08/nilsback08.pdf)] [[Website](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html)]
    * Number of different categories: 102 (**Training**: 82 categories. **Testing**: 20 categories.)
    * Number of flower images: 8,189
  * **Detailed information (Text Descriptions):**  ⇒ [[Paper](https://openaccess.thecvf.com/content_cvpr_2016/papers/Reed_Learning_Deep_Representations_CVPR_2016_paper.pdf)] [[Website](https://drive.google.com/file/d/0B0ywwgffWnLLcms2WWJQRFNSWXM/view)]
    * Descriptions per image: 10 Captions
    
* <span id="head-COCO"> **MS-COCO** </span>

  COCO is a large-scale object detection, segmentation, and captioning dataset.
  * **Detailed information (Images & Text Descriptions):**  ⇒ [[Paper](https://arxiv.org/pdf/1405.0312.pdf)] [[Website](https://cocodataset.org/#overview)]
    * Number of images: 120k (**Training**: 80k. **Testing**: 40k.)
    * Descriptions per image: 5 Captions
    
* <span id="head-Multi-Modal-CelebA-HQ"> **Multi-Modal-CelebA-HQ** </span>

  Multi-Modal-CelebA-HQ is a large-scale face image dataset for text-to-image-generation, text-guided image manipulation, sketch-to-image generation, GANs for face generation and editing, image caption, and VQA.
  * **Detailed information (Images & Text Descriptions):**  ⇒ [[Paper](https://arxiv.org/pdf/2012.03308.pdf)] [[Website](https://github.com/weihaox/Multi-Modal-CelebA-HQ-Dataset)] [[Download](https://drive.google.com/drive/folders/1eVrGKfkbw7bh9xPcX8HJa-qWQTD9aWvf)]
    * Number of images (from Celeba-HQ): 30,000 (**Training**: 24,000. **Testing**: 6,000.)
    * Descriptions per image: 10 Captions
  * **Detailed information (Masks):** 
    * Number of masks (from Celeba-Mask-HQ): 30,000 (512 x 512)
  * **Detailed information (Sketches):** 
    * Number of Sketches: 30,000 (512 x 512)
  * **Detailed information (Image with transparent background):** 
    * Not fully uploaded

## <span id="head4"> *4.Paper With Code* </span>

* <span id="head-Survey"> **Survey**  </span>
    * (2021) **Adversarial Text-to-Image Synthesis: A Review**, Stanislav Frolov et al. [[Paper](https://arxiv.org/pdf/2101.09983.pdf)] 
    * (2019) **A Survey and Taxonomy of Adversarial Neural Networks for Text-to-Image Synthesis**, Jorge Agnese et al. [[Paper](https://arxiv.org/pdf/1910.09399.pdf)] 
    
* <span id="head-2021"> **2021**  </span>
    * (ICCV 2021) **DAE-GAN: Dynamic Aspect-aware GAN for Text-to-Image Synthesis**, Shulan Ruan et al. [[Paper](https://arxiv.org/abs/2108.12141)][[code](https://github.com/hiarsal/DAE-GAN/)]
    * (CVPR 2021) **Cross-Modal Contrastive Learning for Text-to-Image Generation**, Han Zhang et al. [[Paper](https://arxiv.org/pdf/2101.04702.pdf)]  
    * (TMM 2021) **Modality Disentangled Discriminator for Text-to-Image Synthesis**, Fangxiang Feng et al. [[paper](https://ieeexplore.ieee.org/abstract/document/9417738)][[code](https://github.com/FangxiangFeng/DM-GAN-MDD)]
    * (axXiv 2021) **Text to Image Generation with Semantic-Spatial Aware GAN**,Kai Hu et al. [[paper](https://arxiv.org/abs/2104.00567)][[code](https://github.com/wtliao/text2image)]
     
    
* <span id="head-2020"> **2020**  </span>
    * (ECCV 2020) **CPGAN: Content-Parsing Generative Adversarial Networks for Text-to-Image Synthesis**, Jiadong Liang et al. [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-58548-8_29)] [[Code](https://github.com/dongdongdong666/CPGAN)]
    * (CVPR 2020) **RiFeGAN: Rich Feature Generation for Text-to-Image Synthesis From Prior Knowledge**, Jun Cheng et al. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cheng_RiFeGAN_Rich_Feature_Generation_for_Text-to-Image_Synthesis_From_Prior_Knowledge_CVPR_2020_paper.pdf)] 
    * (CVPR 2020) **CookGAN: Causality based Text-to-Image Synthesis**, Bin Zhu et al. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhu_CookGAN_Causality_Based_Text-to-Image_Synthesis_CVPR_2020_paper.pdf)]
    * (TIP 2020) **KT-GAN: Knowledge-Transfer Generative Adversarial Network for Text-to-Image Synthesis**, Hongchen Tan et al. [[paper](https://ieeexplore.ieee.org/document/9210842)]
    
* <span id="head-2019"> **2019**  </span>
    * (NIPS 2019) **Learn, Imagine and Create: Text-to-Image Generation from Prior Knowledge**, Tingting Qiao et al. [[Paper](https://papers.nips.cc/paper/8375-learn-imagine-and-create-text-to-image-generation-from-prior-knowledge.pdf)] [[Code](https://github.com/qiaott/LeicaGAN)]
    * (NIPS 2019) **Controllable Text-to-Image Generation**, Bowen Li et al. [[Paper](https://papers.nips.cc/paper/2019/file/1d72310edc006dadf2190caad5802983-Paper.pdf)] [[Code](https://github.com/mrlibw/ControlGAN)]
    * (CVPR 2019) **DM-GAN: Dynamic Memory Generative Adversarial Networks for Text-to-Image Synthesis**, Minfeng Zhu et al. [[Paper](https://arxiv.org/pdf/1904.01310.pdf)] [[Code](https://github.com/MinfengZhu/DM-GAN)]
    * (CVPR 2019) **Object-driven Text-to-Image Synthesis via Adversarial Training**, Wenbo Li et al. [[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Object-Driven_Text-To-Image_Synthesis_via_Adversarial_Training_CVPR_2019_paper.pdf)] [[Code](https://github.com/jamesli1618/Obj-GAN)]
    * (CVPR 2019) **MirrorGAN: Learning Text-to-image Generation by Redescription**, Tingting Qiao et al. [[Paper](https://arxiv.org/pdf/1903.05854.pdf)] [[Code](https://github.com/qiaott/MirrorGAN)]
    * (CVPR 2019) **Semantics Disentangling for Text-to-Image Generation**, Guojun Yin et al. [[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yin_Semantics_Disentangling_for_Text-To-Image_Generation_CVPR_2019_paper.pdf)] [[Website](https://gjyin91.github.io/projects/sdgan.html)]
    * (ICCV 2019) **Semantics-Enhanced Adversarial Nets for Text-to-Image Synthesis**, Hongchen Tan et al. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tan_Semantics-Enhanced_Adversarial_Nets_for_Text-to-Image_Synthesis_ICCV_2019_paper.pdf)] 
    * (ICCV 2019) **Dual Adversarial Inference for Text-to-Image Synthesis**, Qicheng Lao et al. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Lao_Dual_Adversarial_Inference_for_Text-to-Image_Synthesis_ICCV_2019_paper.pdf)] 
    * (ICCV 2019) **Tell, Draw, and Repeat: Generating and Modifying Images Based on Continual Linguistic Instruction**, Alaaeldin El-Nouby et al. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/El-Nouby_Tell_Draw_and_Repeat_Generating_and_Modifying_Images_Based_on_ICCV_2019_paper.pdf)] [[Code](https://github.com/Maluuba/GeNeVA)]
    * (TCSVT 2019)**Bridge-GAN: Interpretable Representation Learning for Text-to-image Synthesis** Mingkuan Yuan et al. [[paper](https://ieeexplore.ieee.org/abstract/document/8902154)]
    * （ICLR 2019）**GENERATING MULTIPLE OBJECTS AT SPATIALLY DISTINCT LOCATIONS** Tobias Hinz et al. [[paper](https://openreview.net/forum?id=H1edIiA9KQ)][[code](https://github.com/tohinz/multiple-objects-gan)]
    
* <span id="head-2018"> **2018**  </span>
    * (CVPR 2018) **AttnGAN: Fine-grained text to image generation with attentional generative adversarial networks**, Tao Xu et al. [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_AttnGAN_Fine-Grained_Text_CVPR_2018_paper.pdf)] [[Code](https://github.com/taoxugit/AttnGAN)]
    * (CVPR 2018) **Photographic Text-to-Image Synthesis with a Hierarchically-nested Adversarial Network**, Zizhao Zhang et al. [[Paper](https://arxiv.org/pdf/1802.09178.pdf)] [[Code](https://github.com/ypxie/HDGan)]
    * (NIPS 2018) **Text-adaptive generative adversarial networks: Manipulating images with natural language**, Seonghyeon Nam et al. [[Paper](http://papers.nips.cc/paper/7290-text-adaptive-generative-adversarial-networks-manipulating-images-with-natural-language.pdf)] [[Code](https://github.com/woozzu/tagan)]
    
* <span id="head-2017"> **2017**  </span>
    * (ICCV 2017) **StackGAN: Text to photo-realistic image synthesis with stacked generative adversarial networks**, Han Zhang et al. [[Paper](https://arxiv.org/pdf/1612.03242.pdf)] [[Code](https://github.com/hanzhanggit/StackGAN)]
    * （arXiv 2017）**TAC-GAN – Text Conditioned Auxiliary Classifier Generative Adversarial Network**, Ayushman Dash et al. [[paper](https://arxiv.org/pdf/1703.06412.pdf)]
    * (ICIP 2017) **I2T2I: LEARNING TEXT TO IMAGE SYNTHESIS WITH TEXTUAL DATA AUGMENTATION**, Hao Dong et al. [[paper](https://arxiv.org/pdf/1703.06676.pdf)]
    

* <span id="head-2016"> **2016**  </span>
    * (ICML 2016) **Generative Adversarial Text to Image Synthesis**, Scott Reed et al. [[Paper](http://proceedings.mlr.press/v48/reed16.pdf)] [[Code](https://github.com/reedscot/icml2016)]
    * (NIPS 2016) **Learning What and Where to Draw**, Scott Reed et al. [[Paper](https://arxiv.org/pdf/1610.02454.pdf)] [[Code](https://github.com/reedscot/nips2016)]

