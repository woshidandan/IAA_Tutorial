实验室内部美学课题组入门学习材料
===============================

前言：为了帮助已经加入、有意向加入我们美学组的同学，更快的融入课题，找到属于自己的研究方向，特拟该资料。如你现在尚未确定是否加入我们美学组，可以先看第三部分的调研报告和计算机美学的发展，初步了解美学相关的概念。

## 项目组成员
------------------
| 方向       | 描述     | 可能技术 | 目前人员     |
| :-----------: | :--------: | :--------: | :--------: |
| 图像整体美学评估    |    对图像整体美感进行评分，属于基础研究    |     图像处理、自监督学习、多任务等     |      何帅（博士生），刘立敏&谢睿（组内本科生），李珺玥&王乾凱&孙津硕（组外本科生）     |
| 对焦评估    |    对图像对焦进行评分，能用于智能对焦    |     图像处理、显著性检测等     |      张永昌（博士生）     |
| 构图评估    |    对图像构图进行评分，能用于自动裁剪和构图    |     图像处理、图像增强、显著性检测等     |      高有江（硕士生）     |
| 色彩评估    |    对图像色彩进行评分，评估色彩的和谐性    |     图像处理、多任务等     |      李嘉龙（硕士生）     |
| 曝光评估    |    对图像曝光进行评分，能用于曝光纠正    |     图像处理、GAN等     |      张志宇（硕士生）     |
| 噪声评估    |    对图像噪声进行评分，能用于去噪    |     图像处理、去噪、自监督等     |      肖鹏翔（硕士生）     |
| 伪像评估    |    对图像伪像进行评分   |     图像处理、图像增强等     |      衡德康（硕士生）     |
| 清晰度评估    |    对图像清晰度进行评分   |     图像处理、图像增强等     |      姜东翔（硕士生）     |

## 核心文章
#### 推荐阅读
+ "*图像美学质量评价调研报告.*" 知乎 [[link]](https://zhuanlan.zhihu.com/p/3730767)
+ "*这些年，计算机美学的发展.*" 知乎 [[link]](https://zhuanlan.zhihu.com/p/91516029)
+ Naila Murray, Luca Marchesotti, Florent Perronnin: "*AVA: A large-scale database for aesthetic visual analysis.*" CVPR (2012) [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6247954)
+ Hossein Talebi and Peyman Milanfar: "*NIMA: Neural image assessment.*" TIP (2018) [[pdf]](https://ieeexplore.ieee.org/abstract/document/8352823) [[code]](https://paperswithcode.com/paper/nima-neural-image-assessment#code)
+ Aydın, Tunç Ozan, Aljoscha Smolic, and Markus Gross: "*Automated aesthetic analysis of photographic images.*" IEEE T VIS COMPUT GR (2014) [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.675.3491&rep=rep1&type=pdf).
#### 可选
+ Dongyu She, Yu-Kun Lai, Gaoxiong Yi, Kun Xu: "*Hierarchical layout-Aware graph convolutional network for unified aesthetics assessment.*" CVPR (2021) [[pdf]](https://openaccess.thecvf.com/content/CVPR2021/papers/She_Hierarchical_Layout-Aware_Graph_Convolutional_Network_for_Unified_Aesthetics_Assessment_CVPR_2021_paper.pdf) 
+ Jingwen Hou, Sheng Yang, Weisi Lin:"*Object-level attention for aesthetic rating distribution prediction.*" ACM MM (2020) [[pdf]](https://dr.ntu.edu.sg/bitstream/10356/144332/2/Object-level%20attention%20for%20aesthetic%20rating%20distribution%20prediction.pdf)
+ Kekai Sheng, Weiming Dong, Menglei Chai, Guohui Wang, Peng Zhou, Feiyue Huang, Bao-Gang Hu, Rongrong Ji, Chongyang Ma: "*Revisiting image aesthetic assessment via self-supervised feature learning.*" AAAI (2020) [[pdf]](https://arxiv.org/pdf/1911.11419.pdf)
+ Qiuyu Chen, Wei Zhang, Ning Zhou, Peng Lei, Yi Xu, Yu Zheng, Jianping Fan: "*Adaptive fractional dilated convolution network for image aesthetics assessment.*" CVPR (2020) [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_Adaptive_Fractional_Dilated_Convolution_Network_for_Image_Aesthetics_Assessment_CVPR_2020_paper.pdf)
+ Hui Zeng, Zisheng Cao, Lei Zhang, Alan C. Bovik: "*A unified probabilistic formulation of image aesthetic assessment.*" TIP (2020) [[pdf]](https://ieeexplore.ieee.org/abstract/document/8846580) [[code]](https://github.com/HuiZeng/Unified_IAA)
+ Dong Liu, Rohit Puri, Nagendra Kamath, Subhabrata Bhattacharya: "*Composition-aware image aesthetics assessment.*" WACV(2020) [[pdf]](https://openaccess.thecvf.com/content_WACV_2020/papers/Liu_Composition-Aware_Image_Aesthetics_Assessment_WACV_2020_paper.pdf)
+ Weining Wang, Rui Deng: "*Modeling human perception for image aesthetic assessme.*" ICIP (2019) [[pdf]](https://ieeexplore.ieee.org/document/8803749)
+ Vlad Hosu, Bastian Goldlucke, Dietmar Saupe: "*Effective aesthetics prediction with multi-level spatially pooled features.*" CVPR (2019) [[pdf]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Hosu_Effective_Aesthetics_Prediction_With_Multi-Level_Spatially_Pooled_Features_CVPR_2019_paper.pdf) [[code]](https://github.com/subpic/ava-mlsp)
+ Xin Jin, Le Wu, Geng Zhao, Xiaodong Li, Xiaokun Zhang, Shiming Ge, Dongqing Zou, Bin Zhou, Xinghui Zhou: "*Aesthetic attributes assessment of images.*" ACM MM (2019) [[pdf]](https://arxiv.org/pdf/1907.04983.pdf) [[project]](https://github.com/BestiVictory/DPC-Captions)
+ Leida Li, Hancheng Zhu, Sicheng Zhao, Guiguang Ding, Hongyan Jiang, Allen Tan: "*Personality driven multi-task learning for image aesthetic assessment.*" ICME (2019) [[pdf]](https://ieeexplore.ieee.org/abstract/document/8784759)
+ Ning Ma, Alexey Volkov, Aleksandr Livshits, Pawel Pietrusinski, Houdong Hu, Mark Bolin: "*An universal image attractiveness ranking framework.*" WACV (2019) [[pdf]](https://arxiv.org/pdf/1805.00309.pdf)
+ Jun-Tae Lee, Han-Ul Kim, Chul Lee, Chang-Su Kim: "*Photographic composition classification and dominant geometric element detection for outdoor scenes.*" JVCIR (2018) [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S1047320318301147) [[code]](http://mcl.korea.ac.kr/research/Submitted/jtlee_JVCIR2018/code.zip)
+ Katja Thömmes* and Ronald Hübner: "*Instagram likes for architectural photos can be predicted by quantitative balance measures and curvature.*" Front Psychol (2018) [[pdf]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6024014/)
+ Kekai Sheng, Weiming Dong, Chongyang Ma, Xing Mei, Feiyue Huang, Bao-Gang Hu: "*Attention-based multi-patch aggregation for image aesthetic assessment.*" ACM MM (2018) [[pdf]](https://openreview.net/pdf/1cc851d9d7bfc5ec17eedc6498b1601fcb84a40b.pdf) [[code]](https://github.com/Openning07/MPADA)
+ Ning Yu, Xiaohui Shen, Zhe Lin, Radomir Mech, Connelly Barnes: "*Learning to detect multiple photographic defects.*" WACV (2018) [[pdf]](https://arxiv.org/pdf/1612.01635.pdf)
+ Keunsoo Ko, Jun Tae Lee, Chang-Su Kim: "*PAC-Net: Pairwise aesthetic comparison network for image aesthetic assessment.*" ICIP (2018) [[pdf]](https://ieeexplore.ieee.org/abstract/document/8451621)
+ Katharina Schwarz, Patrick Wieschollek, Hendrik P. A. Lensch: "*Will people like your image? Learning the aesthetic space.*" WACV (2018) [[pdf]](https://arxiv.org/pdf/1611.05203.pdf) [[code]](https://github.com/cgtuebingen/will-people-like-your-image)
+ Guolong Wang, Junchi Yan, Zheng Qin: "*Collaborative and attentive learning for personalized image aesthetic assessment.*" IJCAI (2018) [[pdf]](https://www.ijcai.org/Proceedings/2018/0133.pdf)
+ Shuang Ma, Jing Liu, Chang Wen Chen: "*A-Lamp: Adaptive layout-aware multi-patch deep convolutional neural network for photo aesthetic assessment.*" CVPR (2017) [[pdf]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Ma_A-Lamp_Adaptive_Layout-Aware_CVPR_2017_paper.pdf) [[code]](https://github.com/GuillaumeBalezo/A-Lamp) 
+ Jian Ren, Xiaohui Shen, Zhe Lin, Radomir Mech, David J. Foran: "*Personalized image aesthetics.*" ICCV (2017) [[pdf]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Ren_Personalized_Image_Aesthetics_ICCV_2017_paper.pdf) [[code]](https://github.com/alanspike/personalizedImageAesthetics)
+ Anselm Brachmann and Christoph Redies: "*Computational and experimental approaches to visual aesthetics.*"  Front Hum Neurosci (2017) [[pdf]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5694465/)
+ Anselm Brachmann, Erhardt Barth, Christoph Redies: "*Using CNN features to better understand what makes visual artworks special.*" Front Psychol (2017) [[pdf]](https://pubmed.ncbi.nlm.nih.gov/28588537/)
+ Deng Yubin, Chen Change Loy, Xiaoou Tang: "*Image aesthetic assessment: An experimental survey.*" IEEE Signal Processing Magazine (2017) [[pdf]](https://arxiv.org/pdf/1610.00838.pdf) 
+ Long Mai, Hailin Jin, Feng Liu: "*Composition-preserving deep photo aesthetics assessment.*" CVPR (2016) [[pdf]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Mai_Composition-Preserving_Deep_Photo_CVPR_2016_paper.pdf)
+ Shu Kong, Xiaohui Shen, Zhe L. Lin, Radomír Mech, Charless C. Fowlkes: "*Photo aesthetics ranking network with attributes and content adaptation.*" ECCV (2016) [[pdf]](https://arxiv.org/pdf/1606.01621.pdf) [[code]](https://github.com/aimerykong/deepImageAestheticsAnalysis)
+ Xin Lu, Zhe Lin, Xiaohui Shen, Radomir Mech, James Z. Wang: "*Deep multi-patch aggregation network for image style, aesthetics, and quality estimation.*" ICCV (2015) [[pdf]](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Lu_Deep_Multi-Patch_Aggregation_ICCV_2015_paper.pdf)
+ Xin Lu, Zhe Lin, Hailin Jin, Jianchao Yang, James Z. Wang: "*Rapid: Rating pictorial aesthetics using deep learning.*" ACM MM (2014) [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.710.1251&rep=rep1&type=pdf) [[code]](https://github.com/paramoecium/RAPID)
+ Luca Marchesotti, Florent Perronnin, Diane Larlus, Gabriela Csurka: "*Assessing the aesthetic quality of photographs using generic image descriptors.*" ICCV (2011) [[pdf]](https://ieeexplore.ieee.org/document/6126444)
+ Sagnik Dhar, Vicente Ordonez, Tamara L Berg: "*High level describable attributes for predicting aesthetics and interestingness.*" CVPR (2011) [[pdf]](https://bvisionweb1.cs.unc.edu/home/publications/aesthetics_cvpr11.pdf)
+ Ritendra Datta, Jia Li, and James Z. Wang: "*Algorithmic inferencing of aesthetics and emotion in natural images: An exposition.*" ICIP (2008) [[pdf]](https://www.ri.cmu.edu/pub_files/pub4/datta_ritendra_2008_2/datta_ritendra_2008_2.pdf)

## Datasets

### Aesthetic Assessment Datasets

images with aesthetic score/attribute

+ Photo.net (2006) [[Dataset Description]](http://wang.ist.psu.edu/~datta/photonet_dataset_description.txt) [[Annotation]](http://wang.ist.psu.edu/~datta/photonet_dataset.txt)
+ DPChallenge (2008) [[Dataset Description]](http://wang.ist.psu.edu/~datta/dpchallenge_dataset_description.txt) [[Annotation]](http://wang.ist.psu.edu/~datta/dpchallenge_dataset.txt)
+ CUHK-PQ (2011) [[link]](http://mmlab.ie.cuhk.edu.hk/archive/CUHKPQ/Dataset.htm)
+ AVA (2012) [[link]](https://academictorrents.com/details/71631f83b11d3d79d8f84efe0a7e12f0ac001460)
+ AADB (2016) [[link]](https://github.com/aimerykong/deepImageAestheticsAnalysis)
+ FLICKER-AES and REAL-CUR (2017) [[link]](https://github.com/alanspike/personalizedImageAesthetics)
+ PCCD (2017) [[link]](https://github.com/kunghunglu/DeepPhotoCritic-ICCV17)
+ AROD (2018) [[link]](https://github.com/cgtuebingen/will-people-like-your-image)

images with aesthetic caption

+ AVA-Comments (2016) [[paper]](https://dl.acm.org/doi/pdf/10.1145/2964284.2967223)
+ PCCD (2017) [[GoogleDrive]](https://drive.google.com/file/d/1hap2UGI9XV5XmxKOo54wZW30OXbqNyo8/view?usp=sharing) 
+ AVA-Reviews (2018) [[paper]](https://arxiv.org/pdf/1802.10240.pdf)
+ DPC-Captions (2019) [[link]](https://github.com/BestiVictory/DPC-Captions) (not available)

image with composition score/label
+ KU-PCP (2018) [[Download Dataset]](http://mcl.korea.ac.kr/research/Submitted/jtlee_JVCIR2018/KU_PCP_Dataset.zip)
+ CADB (2021) [[link]](https://github.com/bcmi/Image-Composition-Assessment-Dataset-CADB)

### Image Cropping Datasets
densely annotated (multiple crops in each image are annotated)

+ CPC (2018) [[link]](https://github.com/zijunwei/ViewEvaluationNet)
+ GAICD (2019) [[link]](https://github.com/HuiZeng/Grid-Anchor-based-Image-Cropping)

sparsely annotated (only the best crop in each image is annotated)

+ ICDB/MSR-ICD (2013) [[link]](https://personal.ie.cuhk.edu.hk/~ccloy/downloads_cuhk_crop_dataset.html)
+ FLMS/HCDB (2014) [[Download Images]](http://fangchen.org/proj_page/FLMS_mm14/data/radomir500_image/image.tar) [[Download Crops]](http://fangchen.org/proj_page/FLMS_mm14/data/radomir500_gt/release_data.tar)
+ FCDB (2017) [[link]](https://github.com/yiling-chen/flickr-cropping-dataset)

## 深度学习基础知识
### 理论知识
+ "*李宏毅机器学习课程.*" 哔哩哔哩 [[link]](https://www.bilibili.com/video/BV1JE411g7XF?from=search&seid=16114573361443816126)
### 动手实践
+ "*动手学深度学习(PyTorch版).*" GitHub [[link]](https://tangshusen.me/Dive-into-DL-PyTorch/#/)
+ "*深度学习框架PyTorch：入门与实践.*" GitHub [[link]](https://github.com/chenyuntc/pytorch-book)

## 其它工具
+ "*Mendeley.*" 论文整理工具 [[link]](https://zhuanlan.zhihu.com/p/28762628)
+ "*connectedpapers.*" 论文追溯工具 [[link]](https://www.connectedpapers.com/)
+ "*Paperswithcode.*" 论文代码查找工具 [[link]](https://paperswithcode.com/)
+ "*Google colab.*" 免费GPU平台，如额外需服务器资源，请联系我本人 [[link]](https://colab.research.google.com/notebooks/intro.ipynb)




可选
-------------------------
如你希望与我们的交流更紧密，请加入我们内部的企业微信，每周提交一次周报，企业微信【邀请码】可以联系我本人获取，提交周报流程如下：
<div align=center>
<img width="500" src="Co_IAA1.png" alt="封面"/>
</div>
<div align=center>
<img width="500" src="Co_IAA3.png" alt="封面"/>
</div>
<div align=center>
<img width="500" src="Co_IAA4.png" alt="封面"/>
</div>


