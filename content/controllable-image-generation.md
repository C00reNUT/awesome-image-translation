
# Controllable Image Generation

This repository is about *Controllable and Interpretable Image Generation* or *intelligent image manipulation*, which is a collection of papers on image generation and manipulation with the guidance by text, audio, camera pose or other information.  The Controlable Parameters can be Camera, Pose, Lighting, Color, Texture, Semantics, Expression, Speech.

## Table of Contents
- [Interactive and Controllable Image Manipulation](#interactive-and-controllable-image-manipulation)
- [Individual Object Manipulation](#individual-object-manipulation)
- [Guided Image-to-image translation](#guided-image-to-image-translation)
- [Image-Based Virtual Try-On](#image-based-virtual-try-on)
- [Attribute Editing and Makeup Transfer](#attribute-editing-and-makeup-transfer)
- [Texture and Surface Mapping](#texture-and-surface-mapping)
- [Novel-View Synthesis](#novel-view-synthesis)
- [Motion Transfer, Retargeting, Reenactment, Dubbing and Animation](#motion-transfer--retargeting--reenactment--dubbing-and-animation)
- [3D Pose Transfer](#3d-pose-transfer)
- [Grounded Image Captioning](#grounded-image-captioning)
- [Pose and Music](#pose-and-music)
- [Multi-Modality Translations](#multi-modality-translations)
- [Automatic Human-Centric Application](#automatic-human-centric-application)
- [Image Sentiment Transfer](#image-sentiment-transfer)
- [Gaze Estimation, Tracking, Redirection, Correction and Blink Detection](#gaze-estimation--tracking--redirection--correction-and-blink-detection)

## Interactive and Controllable Image Manipulation

**Dual In-painting Model for Unsupervised Gaze Correction and Animation in the Wild.**<br>
*Jichao Zhang, Jingjing Chen, Hao Tang, Wei Wang, Yan Yan, Enver Sangineto, Nicu Sebe.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.03834)]

**Describe What to Change: A Text-guided Unsupervised Image-to-Image Translation Approach.**<br>
*Yahui Liu, Marco De Nadai, Deng Cai, Huayang Li, Xavier Alameda-Pineda, Nicu Sebe, Bruno Lepri.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.04200)]

**Open-Edit: Open-Domain Image Manipulation with Open-Vocabulary Instructions.**<br>
*[Xihui Liu](https://xh-liu.github.io/), Zhe Lin, Jianming Zhang, Handong Zhao, Quan Tran, Xiaogang Wang, and Hongsheng Li.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01576v1)] [[Github](https://github.com/xh-liu/Open-Edit)]

**Describing Textures using Natural Language.**<br>
*Chenyun Wu, Mikayla Timm, Subhransu Maji.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01180)] [[Project](https://people.cs.umass.edu/~chenyun/texture)]

**Controllable Image Synthesis via SegVAE.**<br>
*Yen-Chi Cheng, Hsin-Ying Lee, Min Sun, Ming-Hsuan Yang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08397)] [[Project](https://yccyenchicheng.github.io/SegVAE/)] [[Github](https://github.com/yccyenchicheng/SegVAE)]

**Few-shot Knowledge Transfer for Fine-grained Cartoon Face Generation.**<br>
*Nan Zhuang, Cheng Yang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.13332)] [[Github](https://github.com/minivision-ai/photo2cartoon)]

**CONFIG: Controllable Neural Face Image Generation.**<br>
*Marek Kowalski, Stephan J. Garbin, Virginia Estellers, Tadas Baltrušaitis, Matthew Johnson, Jamie Shotton.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2005.02671)]

**Controlling Style and Semantics in Weakly-Supervised Image Generation.**<br>
*Dario Pavllo, Aurelien Lucchi, and Thomas Hofmann.*<br>
ECCV 2020. [[PDF](https://dariopavllo.github.io/papers/style-semantics.pdf)] [[Github](https://github.com/dariopavllo/style-semantics)]

**Unselfie: Translating Selfies to Neutral-pose Portraits in the Wild.**<br>
*[Liqian Ma](https://homes.esat.kuleuven.be/~liqianma), Zhe Lin, Connelly Barnes, Alexei A. Efros, Jingwan Lu.*<br>
ECCV 2020. [[PDF](https://homes.esat.kuleuven.be/~liqianma/pdf/ECCV20_Unselfie.pdf)]

**Translate the Facial Regions You Like Using Region-Wise Normalization.**<br>
*Wenshuang Liu, Wenting Chen, Linlin Shen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.14615)]

**ArtEditing: Modeling Artistic Workflows for Image Generation and Editing.**<br>
*[Hung-Yu Tseng](https://sites.google.com/site/hytseng0509/), [Matt Fisher](https://techmatt.github.io/), [Jingwan (Cynthia) Lu](https://research.adobe.com/person/jingwan-lu/), [Yijun Li](https://yijunmaverick.github.io/), [Vladimir (Vova) Kim](http://www.vovakim.com/), [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/).*<br>
ECCV 2020. [[Github](https://github.com/hytseng0509/ArtEditing)]

**Task-agnostic Temporally Consistent Facial Video Editing.**<br>
*Meng Cao, Haozhi Huang, Hao Wang, Xuan Wang, Li Shen, Sheng Wang, Linchao Bao, Zhifeng Li, Jiebo Luo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01466)]

**XingGAN for Person Image Generation.**<br>
*[Hao Tang](http://disi.unitn.it/~hao.tang/), Song Bai, Li Zhang, Philip H. S. Torr, Nicu Sebe.*<br>
ECCV 2020.  [[Github](https://github.com/Ha0Tang/XingGAN)]

**DEEPSim: Deep Single Image Manipulation.**<br>
*[Yael Vinker](https://www.linkedin.com/in/yael-vinker-a91a00157/), [Eliahu Horwitz](https://www.linkedin.com/in/eliahu-horwitz), [Nir Zabari](), [Yedid Hoshen](http://www.cs.huji.ac.il/~ydidh).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01289)] [[Project](http://www.vision.huji.ac.il/deepsim/)] [[Github](https://github.com/eliahuhorwitz/DeepSIM)]

**High-Resolution Neural Face Swapping for Visual Effects.**<br>
*Jacek Naruniec, Leonhard Helminger, Christopher Schroers, Romann M. Weber.*<br>
Eurographics Symposium on Rendering 2020. [[PDF](https://s3.amazonaws.com/disney-research-data/wp-content/uploads/2020/06/18013325/High-Resolution-Neural-Face-Swapping-for-Visual-Effects.pdf)] [[Project](http://studios.disneyresearch.com/2020/06/29/high-resolution-neural-face-swapping-for-visual-effects/)]

**Attentive Normalization for Conditional Image Generation.**<br>
*Yi Wang, Ying-Cong Chen, Xiangyu Zhang, Jian Sun, Jiaya Jia.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.03828)]

**Diverse Image Generation via Self-Conditioned GANs.**<br>
*Steven Liu, Tongzhou Wang, David Bau, Jun-Yan Zhu, Antonio Torralba.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2006.10728)] [[Project](http://selfcondgan.csail.mit.edu/)] [[Github](https://github.com/stevliu/self-conditioned-gan)] 

**Facial Expression Editing with Continuous Emotion Labels.**<br>
*Alexandra Lindt, Pablo Barros, Henrique Siqueira, Stefan Wermter.*<br>
FG 2019. [[PDF](https://arxiv.org/abs/2006.12210)]

**Neural Graphics Pipeline for Controllable Image Generation.**<br>
*Xuelin Chen, Daniel Cohen-Or, Baoquan Chen, Niloy J. Mitra.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.10569)]

**CONFIG: Controllable Neural Face Image Generation.**<br>
*Marek Kowalski, Stephan J. Garbin, Virginia Estellers, Tadas Baltrušaitis, Matthew Johnson, Jamie Shotton.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.02671)]

**Interactive Video Stylization Using Few-Shot Patch-Based Training.**<br>
*[Ondřej Texler](https://ondrejtexler.github.io/), David Futschik, Michal Kučera, Ondřej Jamriška, Šárka Sochorová, Menglei Chai, Sergey Tulyakov, Daniel Sýkora.*<br>
TOG 2020 (SIGGRAPH 2020) [[PDF](https://ondrejtexler.github.io/res/Texler20-SIG_patch-based_training_main.pdf)] [[Project](https://ondrejtexler.github.io/patch-based_training/)]

**Disentangled and Controllable Face Image Generation via 3D Imitative-Contrastive Learning.**<br>
*Yu Deng, Jiaolong Yang, Dong Chen, Fang Wen, Xin Tong.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.11660)]

**MichiGAN: Multi-Input-Conditioned Hair Image Generation for Portrait Editing.**<br>
*Zhentao Tan, [Menglei Chai](https://mlchai.com/), Dongdong Chen, Jing Liao, Qi Chu, Lu Yuan, Sergey Tulyakov, Nenghai Yu.*
SIGGRAPH 2020. [[PDF](https://mlchai.com/files/tan2020michigan.pdf)]

**Interactive Sketch & Fill: Multiclass Sketch-to-Image Translation.**<br>
*[Arnab Ghosh](https://arnabgho.github.io/), [Richard Zhang](https://richzhang.github.io/), [Puneet K. Dokania](https://puneetkdokania.github.io/), [Oliver Wang](http://www.oliverwang.info/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/), [Philip H.S. Torr](http://www.robots.ox.ac.uk/~tvg/index.php), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1909.11081v2)] [[Github](https://arnabgho.github.io/iSketchNFill/)]

**SMIS: Semantically Multi-modal Image Synthesis.**<br> 
*[Zhen Zhu](https://zzhu.vision/), Zhiliang Xu, Ansheng You, [Xiang Bai](http://cloud.eic.hust.edu.cn:8071/~xbai/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.12697)] [[Project](http://seanseattle.github.io/SMIS)] [[Github](https://github.com/Seanseattle/SMIS)]

**SEAN: Image Synthesis with Semantic Region-Adaptive Normalization.**</br>
*Peihao Zhu, Rameen Abdal, Yipeng Qin, Peter Wonka.*<br> 
CVPR 2020. [[PDF](https://arxiv.org/abs/1911.12861)] [[Video](https://youtu.be/0Vbj9xFgoUw)] [[Github](https://github.com/ZPdesu/SEAN)]

**MichiGAN: Multi-Input-Conditioned Hair Image Generation for Portrait Editing.**<br>
*Zhentao Tan, Menglei Chai, Dongdong Chen, Jing Liao, Qi Chu, Lu Yuan, Sergey Tulyakov, Nenghai Yu.*<br>
SIGGRAPH 2020. [[PDF](https://mlchai.com/files/tan2020michigan.pdf)]

## Individual Object Manipulation

**SESAME: Semantic Editing of Scenes by Adding, Manipulating or Erasing Objects.**<br>
*Evangelos Ntavelis, Andrés Romero, Iason Kastanis, Luc Van Gool, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.04977)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), Xingang Pan, Bo Dai, Ziwei Liu, Dahua Lin, and Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Github](https://github.com/XiaohangZhan/deocclusion)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Demo](https://www.youtube.com/watch?v=xIHCyyaB5gU)]

**3DLSN: End-to-End Optimization of Scene Layout.**<br>
*Andrew Luo, Zhoutong Zhang, Jiajun Wu, Joshua B. Tenenbaum.*<br>
CVPR 2020. [[PDF](https://jiajunwu.com/papers/3dsln_cvpr.pdf)] [[Project](http://3dsln.csail.mit.edu/)]

**DJRN: Detailed 2D-3D Joint Representation for Human-Object Interaction.**<br>
*Yong-Lu Li, Xinpeng Liu, Han Lu, Shiyi Wang, Junqi Liu, Jiefeng Li, Cewu Lu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.08154)] [[Github](https://github.com/DirtyHarryLYL/DJ-RN)]

**Learning to Manipulate Individual Objects in an Image.**<br>
*Yanchao Yang, Yutong Chen, Stefano Soatto.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.05495)]

**AutoSweep: Recovering 3D Editable Objectsfrom a Single Photograph.**<br>
*Xin Chen, Yuwei Li, Xi Luo, Tianjia Shao, Jingyi Yu, Kun Zhou, Youyi Zheng.*<br>
IVCJ 2018. [[PDF](https://arxiv.org/abs/2005.13312)] [[Project](https://chenxin.tech/files/Paper/TVCG2018_AutoSweep/AutoSweep.html)]

**Intrinsic Autoencoders for Joint Neural Rendering and Intrinsic Image Decomposition.**<br>
*Hassan Abu Alhaija, Siva Karthik Mustikovela, Justus Thies, Matthias Nießner, Andreas Geiger, Carsten Rother.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16011)]

**Conditional Image Generation and Manipulation for User-Specified Content.**<br>
*David Stap, Maurits Bleeker, Sarah Ibrahimi, Maartje ter Hoeve.*<br>
AI for content creation workshop at CVPR 2020. [[PDF](https://arxiv.org/abs/2005.04909)]

**Context-Aware Synthesis and Placement ofObject Instances.**<br>
*Donghoon Lee, Sifei Liu, Jinwei Gu, Ming-Yu Liu, Ming-Hsuan Yang, Jan Kautz.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1812.02350v1)] [[Project](https://research.nvidia.com/publication/2018-10_Context-aware-Synthesis-and)]

## Guided Image-to-image translation
Part of this repository is about *Guided Image-to-image translation* which can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/README_.md#guided-image-to-image-translation).

**Graph2Plan: Learning Floorplan Generation from Layout Graphs.**<br>
*Ruizhen Hu, Zeyu Huang, Yuhan Tang, Oliver van Kaick, Hao Zhang, Hui Huang.*<br>
ACM Transactions on Graphics 2020. [[PDF](https://arxiv.org/abs/2004.13204)]

## Image-Based Virtual Try-On
*Image-Based Virtual Try-On* can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/clothed-human.md#image-based-virtual-try-on).

## Attribute Editing and Makeup Transfer
*Attribute Editing and Makeup Transfer* can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/README_.md#attribute-editing).

## Texture and Surface Mapping
*Texture and Surface Mapping* can be found [here](https://github.com/xiaweihao/awesome-neural-rendering/blob/master/README.md#texture-and-surface-mapping).

## Novel-View Synthesis
*Novel-View Synthesis* can be found [here](https://github.com/xiaweihao/awesome-neural-rendering/blob/master/README.md#novel-view-synthesis).

## Motion Transfer, Retargeting, Reenactment, Dubbing and Animation
*Motion Transfer, Retargeting, Reenactment, Dubbing and Animation* can be found [here](https://github.com/xiaweihao/awesome-neural-rendering/blob/master/README.md#motion-transfer--retargeting--reenactment--dubbing-and-animation).

## 3D Pose Transfer
*3D Pose Transfer* can be found [here](https://github.com/xiaweihao/awesome-neural-rendering/blob/master/README.md#attribute-editing).

## Generating Accurate Descriptions

**Fashion Captioning: Towards Generating Accurate Descriptions with Semantic Rewards.**<br>
*Xuewen Yang, Heming Zhang, Di Jin, Yingru Liu, Chi-Hao Wu, Jianchao Tan, Dongliang Xie, Jue Wang, Xin Wang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.02693)]

**POS-SCAN: More Grounded Image Captioning by Distilling Image-Text Matching Model.**<br>
*Yuanen Zhou, Meng Wang, Daqing Liu, Zhenzhen Hu, Hanwang Zhang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00390v1)] [[Github](https://github.com/YuanEZhou/Grounded-Image-Captioning)]

**Spatio-Temporal Graph for Video Captioning with Knowledge Distillation.**<br>
*Boxiao Pan, Haoye Cai, De-An Huang, Kuan-Hui Lee, Adrien Gaidon, Ehsan Adeli, Juan Carlos Niebles.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13942)]

## Pose and Music
**Music Gesture for Visual Sound Separation.**<br>
*Chuang Gan, Deng Huang, Hang Zhao, Joshua B. Tenenbaum, Antonio Torralba.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.09476)] [[Project](http://music-gesture.csail.mit.edu/)]

**Vector Quantized Contrastive Predictive Coding for Template-based Music Generation.**<br>
*Gaëtan Hadjeres, Léopold Crestel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.10120)] [[Github](https://github.com/SonyCSLParis/vqcpc-bach)]

## Multi-Modality Translations
[[Eurus-Holmes/Awesome-Multimodal-Research](https://github.com/Eurus-Holmes/Awesome-Multimodal-Research)]</br>
[[pliang279/awesome-multimodal-ml](https://github.com/pliang279/awesome-multimodal-ml)]</br>

### Voice-to-Image
**Attention-based Residual Speech Portrait Model for Speech to Face Generation.**<br>
*Jianrong Wang, Xiaosheng Hu, Li Liu, Wei Liu, Mei Yu, Tianyi Xu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.04536)]

**Speech2Face: Learning the Face Behind a Voice.**<br>
*Tae-Hyun Oh, Tali Dekel, Changil Kim, Inbar Mosseri, William T. Freeman, Michael Rubinstein, Wojciech Matusik.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1905.09773)] [[project](https://speech2face.github.io/)] [[Related Work](https://speech2face.github.io/)]

### Image-to-Voice

**Learning Individual Speaking Styles for Accurate Lip to Speech Synthesis.**<br>
*K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.08209)] [[Github](https://github.com/Rudrabha/Lip2Wav)]

### Voice-to-Voice
**REMI: Pop Music Transformer: Generating Music with Rhythm and Harmony.**<br>
*Yu-Siang Huang, Yi-Hsuan Yang.*<br>
arxiv, 1 Feb 2020. [[PDF](https://arxiv.org/abs/2002.00212)] [[Github](https://github.com/YatingMusic/remi)] [[Demo](http://vibertthio.com/transformer/)]

**Speech-to-Singing Conversion in an Encoder-Decoder Framework.**<br>
*Jayneel Parekh, Preeti Rao, Yi-Hsuan Yang.*<br>
ICASSP 2020. 
[[PDF](https://arxiv.org/abs/2002.06595)] [[Github](https://github.com/jayneelparekh/sp2si-code)] 
[[Project](https://jayneelparekh.github.io/icassp20/)]
[[NUS-48E dataset](https://smcnus.comp.nus.edu.sg/nus-48e-sung-and-spoken-lyrics-corpus/)]

### Voice-to-Speech

**GAN-TTS: High Fidelity Speech Synthesis with Adversarial Networks.**<br>
*Mikołaj Bińkowski, Jeff Donahue, Sander Dieleman, Aidan Clark, Erich Elsen, Norman Casagrande, Luis C. Cobo, Karen Simonyan.*<br>
ICASSP 2020. [[PDF](https://arxiv.org/abs/1909.11646)]

### Image-to-Text

**Decomposed Generation Networks with Structure Prediction for Recipe Generation from Food Images.**<br>
*Hao Wang, Guosheng Lin, Steven C. H. Hoi, Chunyan Miao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13374)]

**Inverse Cooking: Recipe Generation from Food Images.**<br>
*Amaia Salvador, Michal Drozdzal, Xavier Giro-i-Nieto, Adriana Romero.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1812.06164)]

### Text-to-Image

**CVSE: Consensus-Aware Visual-Semantic Embedding for Image-Text Matching.**<br>
*Haoran Wang, Ying Zhang, Zhong Ji, Yanwei Pang, Lin Ma.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08883)] [[Gtihub](https://github.com/BruceW91/CVSE)]

**CPGAN: Content-Parsing Generative Adversarial Networks for Text-to-Image Synthesis.**<br>
*Jiadong Liang, Wenjie Pei, Feng Lu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.08562)]

**TIME: Text and Image Mutual-Translation Adversarial Networks.**<br>
*Bingchen Liu, Kunpeng Song, Yizhe Zhu, Gerard de Melo, Ahmed Elgammal.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.13192)]

**S2IGAN: Speech-to-Image Generation via Adversarial Learning.**<br>
*Xinsheng Wang, Tingting Qiao, Jihua Zhu, Alan Hanjalic, Odette Scharenborg.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.06968)]

**3DLSN: End-to-End Optimization of Scene Layout.**<br>
*Andrew Luo, Zhoutong Zhang, Jiajun Wu, Joshua B. Tenenbaum.*<br>
CVPR 2020. [[PDF](https://jiajunwu.com/papers/3dsln_cvpr.pdf)] [[Project](http://3dsln.csail.mit.edu/)]

**CookGAN: Meal Image Synthesis from Ingredients.**<br>
*Fangda Han, Ricardo Guerrero, Vladimir Pavlovic.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/2002.11493)]

**ControlGAN: Controllable Text-to-Image Generation.**<br>
*Bowen Li, Xiaojuan Qi, Thomas Lukasiewicz, Philip H. S. Torr.*<br>
NeurIPS 2019. [[PDF](https://papers.nips.cc/paper/8480-controllable-text-to-image-generation.pdf)] [[Github](https://github.com/mrlibw/ControlGAN)]

**Object-driven Text-to-Image Synthesis via Adversarial Training.**<br>
*Wenbo Li, Pengchuan Zhang, Lei Zhang, Qiuyuan Huang, Xiaodong He, Siwei Lyu, Jianfeng Gao.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1902.10740)]

**SwapText: Image Based Texts Transfer in Scenes.**<br>
*Qiangpeng Yang, Hongsheng Jin, Jun Huang, Wei Lin.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.08152)]

**Local-Global Video-Text Interactions for Temporal Grounding.**<br>
*[Jonghwan Mun](http://cvlab.postech.ac.kr/~jonghwan/), [Minsu Cho](http://cvlab.postech.ac.kr/~mcho/), [Bohyung Han](https://cv.snu.ac.kr/index.php/bhhan/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.07514)] [[Github](https://github.com/JonghwanMun/LGI4temporalgrounding)]

**Image-to-Image Translation with Text Guidance.**<br>
*Bowen Li, Xiaojuan Qi, Philip H. S. Torr, Thomas Lukasiewicz.*<br>
arxiv, 12 Feb 2020. [[PDF](https://arxiv.org/abs/2002.05235)]

**Neural Image Inpainting Guided with Descriptive Text.**<br>
*Lisai Zhang, Qingcai Chen, Baotian Hu, Shuoran Jiang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.03212)]

**Cycle Text-To-Image GAN with BERT.**<br>
*Trevor Tsue, Samir Sen, Jason Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.12137)] [Github](https://github.com/suetAndTie/cycle-image-gan)]

**ManiGAN: Text-Guided Image Manipulation.**<br>
*[Bowen Li](https://mrlibw.github.io/), [Xiaojuan Qi](https://xjqi.github.io/), Thomas Lukasiewicz, Philip H. S. Torr.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.06203)] [[Github](https://github.com/mrlibw/ManiGAN)]

**Controllable Text-to-Image Generation.**<br>
*Bowen Li, [Xiaojuan Qi](https://xjqi.github.io/), Thomas Lukasiewicz, Philip H. S. Torr.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1909.07083)]

**MirrorGAN: Learning Text-to-image Generation by Redescription.**<br>
*Tingting Qiao, Jing Zhang, Duanqing Xu, Dacheng Tao.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.05854)] [[Unofficial TensorFlow](https://github.com/taki0112/MirrorGAN-Tensorflow)]

**AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks.**<br>
*Tao Xu, Pengchuan Zhang, Qiuyuan Huang, Han Zhang, Zhe Gan, Xiaolei Huang, Xiaodong He.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1711.10485)] [[Github](https://github.com/taoxugit/AttnGAN)]

**StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks.**<br>
*Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas.*<br>
TPAMI 2018. [[PDF](https://arxiv.org/abs/1710.10916)] [[Github](https://github.com/hanzhanggit/StackGAN-v2)]

**StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks.**<br>
*Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas.*<br>
ICCV 2017. [[PDF](https://arxiv.org/abs/1612.03242v2)] [[Github](https://github.com/hanzhanggit/StackGAN-Pytorch)]

**Generative Adversarial Text to Image Synthesis.**<br>
*Scott Reed, Zeynep Akata, Xinchen Yan, Lajanugen Logeswaran, Bernt Schiele, Honglak Lee.*<br>
ICML 2016. [[PDF](https://arxiv.org/abs/1605.05396)] [[Github](https://github.com/reedscot/icml2016)]

**Learning Deep Representations of Fine-grained Visual Descriptions.**<br>
*Scott Reed, Zeynep Akata, Bernt Schiele, Honglak Lee.*<br>
CVPR 2016. [[PDF](https://arxiv.org/abs/1605.05395)] [[Github](https://github.com/reedscot/cvpr2016)]

### Speech-to-Text
**Synchronous Speech Recognition and Speech-to-Text Translation with Interactive Decoding.**<br>
*Yuchen Liu, Jiajun Zhang, Hao Xiong, Long Zhou, Zhongjun He, Hua Wu, Haifeng Wang, Chengqing Zong.*<br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1912.07240)]

### Text-to-speech
**Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis.**<br>
*Ye Jia, Yu Zhang, Ron J. Weiss, Quan Wang, Jonathan Shen, Fei Ren, Zhifeng Chen, Patrick Nguyen, Ruoming Pang, Ignacio Lopez Moreno, Yonghui Wu.*<br>
eurIPS 2018. [[PDF](https://arxiv.org/abs/1806.04558v4)] [[Github](https://github.com/CorentinJ/Real-Time-Voice-Cloning)] [[Github](https://github.com/Suhee05/Text-Independent-Speaker-Verification)]

**In Other News: a Bi-style Text-to-speech Model for Synthesizing Newscaster Voice with Limited Data.**<br>
*Nishant Prateek, Mateusz Łajszczak, Roberto Barra-Chicote, Thomas Drugman, Jaime Lorenzo-Trueba, Thomas Merritt, Srikanth Ronanki, Trevor Wood.*<br>
NAACL. [[PDF](https://www.aclweb.org/anthology/N19-2026/)]

**The Theory behind Controllable Expressive Speech Synthesis: a Cross-disciplinary Approach.**<br>
*Noé Tits, Kevin El Haddad, Thierry Dutoit.*<br>
arxiv, 14 Oct 2019. IntechOpen. [[PDF](https://arxiv.org/abs/1910.06234v1)]

**Token-Level Ensemble Distillation for Grapheme-to-Phoneme Conversion.**<br>
*Hao Sun, Xu Tan, Jun-Wei Gan, Hongzhi Liu, Sheng Zhao, Tao Qin, Tie-Yan Liu.*<br>
interspeech 2019. [[PDF](https://arxiv.org/abs/1911.06573v1)] 

**Independent and Automatic Evaluation of Acoustic-to-Articulatory Inversion Models.**<br>
*Maud Parrot, Juliette Millet, Ewan Dunbar.*<br>
arxiv, 15 Nov 2019. [[PDF](https://arxiv.org/pdf/1911.06573v1.pdf)]

**Using VAEs and Normalizing Flows for One-shot Text-To-Speech Synthesis of Expressive Speech.**<br>
*Vatsal Aggarwal, Marius Cotescu, Nishant Prateek, Jaime Lorenzo-Trueba, Roberto Barra-Chicote.*<br>
arxiv, 20 Nov 2019. [[PDF](https://arxiv.org/abs/1911.12760v1)] 

## Automatic Human-Centric Application

**Zoom in to the details of human-centric videos.**<br>
*Guanghan Li, Yaping Zhao, Mengqi Ji, Xiaoyun Yuan, Lu Fang.*<br>
ICIP 2020. [[PDF](https://arxiv.org/abs/2005.13222)]

## Image Sentiment Transfer

**Image Sentiment Transfer.**<br>
*Tianlang Chen, Wei Xiong, Haitian Zheng, [Jiebo Luo](https://www.cs.rochester.edu/u/jluo/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.11337)]

**Global Image Sentiment Transfer.**<br>
*Jie An, Tianlang Chen, Songyang Zhang, [Jiebo Luo](https://www.cs.rochester.edu/u/jluo/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.11989)]

## Gaze Estimation, Tracking, Redirection, Correction and Blink Detection

[[Awesome Work on Gaze Estimation.](https://github.com/cvlab-uob/Awesome-Gaze-Estimation)]

ICCV 2019 WorkShop: [Gaze Estimation and Prediction in the Wild](http://openaccess.thecvf.com/ICCV2019_workshops/ICCV2019_GAZE.py) [[Homepage](http://gazeworkshop.github.io/)]

* A Generalized and Robust Method Towards Practical Gaze Estimation on Smart Phone. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/Guo_A_Generalized_and_Robust_Method_Towards_Practical_Gaze_Estimation_on_ICCVW_2019_paper.pdf)
Tianchu Guo, Yongchao Liu, Hui Zhang, Xiabing Liu, Youngjun Kwak, Byung In Yoo, Jae-Joon Han, Changkyu Choi.

* Learning to Personalize in Appearance-Based Gaze Tracking. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/Linden_Learning_to_Personalize_in_Appearance-Based_Gaze_Tracking_ICCVW_2019_paper.pdf)
Erik Linden, Jonas Sjostrand, Alexandre Proutiere.

* On-Device Few-Shot Personalization for Real-Time Gaze Estimation. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/He_On-Device_Few-Shot_Personalization_for_Real-Time_Gaze_Estimation_ICCVW_2019_paper.pdf)
Junfeng He, Khoi Pham, Nachiappan Valliappan, Pingmei Xu, Chase Roberts, Dmitry Lagun, Vidhya Navalpakkam.

* RT-BENE: A Dataset and Baselines for Real-Time Blink Estimation in Natural Environments. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/Cortacero_RT-BENE_A_Dataset_and_Baselines_for_Real-Time_Blink_Estimation_in_ICCVW_2019_paper.pdf)
Kevin Cortacero, Tobias Fischer, Yiannis Demiris.

* SalGaze: Personalizing Gaze Estimation using Visual Saliency. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/Chang_SalGaze_Personalizing_Gaze_Estimation_using_Visual_Saliency_ICCVW_2019_paper.pdf)
Zhuoqing Chang, J. Matias Di Martino, Qiang Qiu, Steven Espinosa, Guillermo Sapiro.

### Gaze Dataset

**ETH-XGaze: A Large Scale Dataset for Gaze Estimation under Extreme Head Pose and Gaze Variation.**<br>
*Xucong Zhang, Seonwook Park, Thabo Beeler, Derek Bradley, Siyu Tang, Otmar Hilliges.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.15837)] [[ETH-XGaze](https://ait.ethz.ch/projects/2020/ETH-XGaze)]

**Columbia Gaze Data Set: Gaze Locking: Passive Eye Contact Detection for Human–Object Interaction.**<br>
*Brian A. Smith,  Qi Yin,  Steven K. Feiner,  Shree K. Nayar.*<br>
ACM Symposium on User Interface Software and Technology (UIST), 2013. [[PDF](http://www.cs.columbia.edu/~brian/publications/gaze_locking.html)] [[Columbia Gaze Data Set](http://www.cs.columbia.edu/CAVE/databases/columbia_gaze/)]

**GazeCapture: Eye Tracking for Everyone.**<br>
*Kyle Krafka*, Aditya Khosla*, Petr Kellnhofer, Harini Kannan, Suchendra Bhandarkar, Wojciech Matusik, Antonio Torralba.*<br>
CVPR 2016. [[PDF](https://gazecapture.csail.mit.edu/)] [[GazeCapture](https://gazecapture.csail.mit.edu/)] [[Github](https://github.com/CSAILVision/GazeCapture)]

**MPIIGaze: Appearance-based Gaze Estimation in the Wild.**<br>
*Xucong Zhang, Yusuke Sugano, Mario Fritz, Andreas Bulling.*<br>
CVPR 2015. [[PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Zhang_Appearance-Based_Gaze_Estimation_2015_CVPR_paper.pdf)] [[MPIIGaze Dataset](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/gaze-based-human-computer-interaction/appearance-based-gaze-estimation-in-the-wild/)] [[Max Planck Institute for Informatics](www.mpi-inf.mpg.de/)]

**MPIIFaceGaze: It’s Written All Over Your Face: Full-Face Appearance-Based Gaze Estimation.**<br>
*X. Zhang, Y. Sugano, M. Fritz and A. Bulling.*<br>
CVPR Workshop, 2017. [[PDF]](https://perceptual.mpi-inf.mpg.de/files/2017/05/zhang_cvprw2017.pdf) [[Homepage]](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/gaze-based-human-computer-interaction/its-written-all-over-your-face-full-face-appearance-based-gaze-estimation/) [MPIIFaceGaze [Original](http://datasets.d2.mpi-inf.mpg.de/MPIIGaze/MPIIFaceGaze.zip) or [Normalized](http://datasets.d2.mpi-inf.mpg.de/MPIIGaze/MPIIFaceGaze_normalized.zip)]

**UT: Learning by Synthesis for Appearance-based 3D Gaze Estimation.**<br>
*Yusuke Sugano, Yasuyuki Matsushita, Yoichi Sato.*<br>
CVPR 2014. [[PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Sugano_Learning-by-Synthesis_for_Appearance-based_2014_CVPR_paper.pdf)] [[UT Dataset](www.hci.iis.u-Tokyo.ac.jp/datasets)]

**Monocular Free-head 3D Gaze Tracking with Deep Learning and Geometry Constraints.**
*Haoping Deng, Wangjiang Zhu.*
ICCV 2017. [[PDF](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_Monocular_Free-Head_3D_ICCV_2017_paper.pdf)]

### Gaze Redirection and Correction

**MGGR: MultiModal-Guided Gaze Redirection with Coarse-to-Fine Learning.**<br> 
*Jingjing Chen, Jichao Zhang, Jiayuan Fan, Tao Chen, Enver Sangineto, Nicu Sebe.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.03064)]

**GazeCorrection: Self-Guided Eye Manipulation in the wild using Self-Supervised Generative Adversarial Networks.**<br> 
*Jichao Zhang, Meng Sun, Jingjing Chen, Hao Tang, Yan Yan, Xueying Qin, Nicu Sebe.*<br> 
arxiv, 2019. [[PDF](https://arxiv.org/abs/1906.00805)] [[Github](https://github.com/zhangqianhui/GazeCorrection)]

**Look at Me! Correcting Eye Gaze in Live Video Communication.**<br> 
*Chih-Fan Hsu, Yushuen  Wang, C.-L Lei, Kuan-Ta Chen.*<br> 
TOMM (ACM Transactions on Multimedia Computing, Communications, and Applications). [[PDF](https://dl.acm.org/doi/10.1145/3311784)] [[Github](https://github.com/chihfanhsu/gaze_correction)]

**Photo-Realistic Monocular Gaze Redirection Using Generative Adversarial Networks.**<br>
*Zhe He, Adrian Spurr, Xucong Zhang, Otmar Hilliges ([AIT Lab, ETH Zurich](https://ait.ethz.ch/)).*<br> 
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/He_Photo-Realistic_Monocular_Gaze_Redirection_Using_Generative_Adversarial_Networks_ICCV_2019_paper.pdf)] [[Github](https://github.com/HzDmS/gaze_redirection)] [[Columbia Gaze Dataset](http://www.cs.columbia.edu/~brian/projects/columbia_gaze.html)] [[Processed](https://drive.google.com/file/d/1tE3QfFjxtRco4ruLZwYyUhjyYSp2QIJL/view?usp=sharing)]

**Improving Few-Shot User-Specific Gaze Adaptation via Gaze Redirection Synthesis.**<br>
*Yu Yu, Gang Liu, Jean-Marc Odobez.*<br>
CVPR 2019. [[PDF](http://www.idiap.ch/~odobez/publications/YuLiuOdobez-CVPR2019.pdf)]

**GazeDirector: Fully Articulated Eye Gaze Redirection in Video.**<br>
*Erroll Wood, Tadas Baltrusaitis, Louis-Philippe Morency, Peter Robinson, Andreas Bulling.*<br>
Eurographics 2018 (Best Paper Honourable Mention Award). [[PDF](https://perceptual.mpi-inf.mpg.de/files/2018/03/wood18_eg.pdf)] 

**GazeGAN: Unpaired Adversarial Image Generation for Gaze Estimation.**<br>
*Matan Sela, Pingmei Xu, Junfeng He, Vidhya Navalpakkam, Dmitry Lagun.*<br>
2017. [[PDF](https://arxiv.org/abs/1711.09767)]

**DeepWarp: Photorealistic Image Resynthesis for Gaze Manipulation.**<br>
*Yaroslav Ganin, Daniil Kononenko, Diana Sungatullina, Victor Lempitsky.*<br>
ECCV 2016. [[PDF](http://sites.skoltech.ru/compvision/projects/deepwarp/files/deepwarp_eccv2016.pdf)] [[Project](http://sites.skoltech.ru/compvision/projects/deepwarp/)]

**Learning to look up: Realtime Monocular Gaze Correction using Machine Learning.**<br>
CVPR 2015. [[PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Kononenko_Learning_To_Look_2015_CVPR_paper.pdf)] 

**Gaze Correction for Home Video Conferencing.**<br>
*C. Kuster, T. Popa, J.C. Bazin, C. Gotsman, M. Gross.*<br>
ACM TOG 2012.  [[PDF](https://cgl.ethz.ch/disclaimer.php?dlurl=/Downloads/Publications/Papers/2012/Kus12/Kus12.pdf)] [[CGL ETHZ](https://cgl.ethz.ch/publications/papers/paperKus12.php)]

**An Eye For An Eye: A Single Camera Gaze-Replacement Method.**<br>
*[Lior Wolf](http://www.cs.tau.ac.il/~wolf/), Ziv Freund, Shai Avidan.*<br>
CVPR 2010. [[PDF](http://www.cs.tau.ac.il/~wolf/papers/eyes_cameraready.pdf)] 

**Eye Gaze Correction with Stereovision For Video-teleconferencing.**<br>
*Ruigang Yang, Zhengyou Zhang.*<br>
ECCV 2004. [[PDF](https://www.microsoft.com/en-us/research/publication/eye-gaze-correction-with-stereovision-for-video-teleconferencing/)]

### Gaze Estimation

**Learning to Detect Head Movement in Unconstrained Remote Gaze Estimation in the Wild.**<br>
*Zhecan Wang, Jian Zhao, Cheng Lu, Han Huang, Fan Yang, Lianji Li, Yandong Guo.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/2004.03737)]

**FAZE: Few-Shot Adaptive Gaze Estimation.**<br>
*Seonwook Park, Shalini De Mello, Pavlo Molchanov, Umar Iqbal, Otmar Hilliges, Jan Kautz.*<br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Park_Few-Shot_Adaptive_Gaze_Estimation_ICCV_2019_paper.pdf)] [[Preprocess](github.com/swook/faze_preprocess)] [[Github](https://github.com/NVlabs/few_shot_gaze)] [[ETH Zurich](https://ait.ethz.ch/projects/2019/faze/)] [[Nvidia](https://research.nvidia.com/publication/2019-10_Few-Shot-Adaptive-Gaze)]

**Gaze360: Physically Unconstrained Gaze Estimation in the Wild.**<br>
*Petr Kellnhofer*, Adrià Recasens*, Simon Stent, Wojciech Matusik, Antonio Torralba.*<br>
ICCV 2019. [[PDF](http://gaze360.csail.mit.edu/iccv2019_gaze360.pdf)] [[Github](https://github.com/Erkil1452/gaze360)] [[Project](http://gaze360.csail.mit.edu)] [[Dataset](http://gaze360.csail.mit.edu/download.php)]

**Mixed Effects Neural Networks (MeNets) With Applications to Gaze Estimation.**<br>
*Yunyang Xiong, Hyunwoo J. Kim, Vikas Singh.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Xiong_Mixed_Effects_Neural_Networks_MeNets_With_Applications_to_Gaze_Estimation_CVPR_2019_paper.pdf)]

**Deep Pictorial Gaze Estimation.**<br>
*Seonwook Park, Adrian Spurr, Otmar Hilliges.*<br>
ECCV 2018. [[PDF](http://openaccess.thecvf.com/content_ECCV_2018/papers/Seonwook_Park_Deep_Pictorial_Gaze_ECCV_2018_paper.pdf)] 

**RTGENE: Real-Time Gaze Estimation in Natural Environments.**<br>
*Tobias Fischer, Hyung Jin Chang,Yiannis Demiris.*<br>
ECCV 2018. [[PDF](http://openaccess.thecvf.com/content_ECCV_2018/papers/Tobias_Fischer_RT-GENE_Real-Time_Eye_ECCV_2018_paper.pdf)]
[[Github](https://github.com/Tobias-Fischer/rt_gene)]

### Eye Tracking

**EVE: Towards End-to-end Video-based Eye-Tracking.**<br>
*Seonwook Park, Emre Aksan, Xucong Zhang, Otmar Hilliges.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13120)] [[Project](https://ait.ethz.ch/projects/2020/EVE)]

**Neuro-Inspired Eye Tracking With Eye Movement Dynamics.**<br>
*Kang Wang, Hui Su, Qiang Ji.*<br>
CVPR 2019. [[PDF](http://homepages.rpi.edu/~wangk10/papers/wang2019neural.pdf)]

**Generalizing Eye Tracking With Bayesian Adversarial Learning.**<br>
*Kang Wang, Rui Zhao, Hui Su, Qiang Ji.*<br>
CVPR 2019. [[PDF](https://www.semanticscholar.org/paper/Generalizing-Eye-Tracking-with-Bayesian-Adversarial-Wang-Zhao/77b9b6786699a236aad0c3fa3734730ece4a780f)]

**EyeDiap: A Database For the Development and Evaluation of Gaze Estimation Algorithms from RGB and RGBD Cameras.**<br>
*Kenneth Alberto Funes Mora, Florent Monay, Jeanmarc Odobez.*<br>
ETRA 2014. [[PDF](http://www.idiap.ch/~odobez/publications/FunesMonayOdobez-ETRA2014.pdf)] [[Idiap Research Institute](https://www.idiap.ch)]