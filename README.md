实验室内部美学课题组入门学习材料
===============================
前言：为了帮助同学，更快的了解和融入图像美学课题，找到属于自己的研究方向，特拟该资料。

## 该课题成立时间
2020年11月~至今

## 项目组成员（一些最新的研究因保密原因，不便展示）

| 方向       | 描述     | 可能技术 | 目前人员     |
| :-----------: | :--------: | :--------: | :--------: |
| 图像整体美学评估    |    对图像整体美感进行评分，属于基础研究    |     图像处理、自监督学习、多任务等     |      何帅（博三，带队），刘立敏&谢睿（研一），张顺天（大三）     |
| 对焦评估    |    对图像对焦进行评分，能用于智能对焦    |     图像处理、显著性检测等     |      张永昌（博二）     |
| 构图评估    |    对图像构图进行评分，能用于自动裁剪和构图    |     图像处理、图像增强、显著性检测等     |      高有江（已毕业）     |
| 色彩评估    |    对图像色彩进行评分，评估色彩的和谐性    |     图像处理、多任务等     |      李嘉龙（已毕业），李雅琪（大四）     |
| 曝光评估    |    对图像曝光进行评分，能用于曝光纠正    |     图像处理、GAN等     |      张志宇（研三）     |
| 噪声评估    |    对图像噪声进行评分，能用于去噪    |     图像处理、去噪等     |      肖鹏翔（研三）     |
| 伪像评估    |    对图像伪像进行评分   |     图像处理、图像增强等     |      衡德康（研二）     |
| 清晰度评估    |    对图像清晰度进行评分   |     图像处理、图像增强等     |      姜东翔（研二）     |

## 入门文章
组内已投中顶会顶刊：
+ Shuai He, Yongchang Zhang, Dongxiang Jiang, Rui Xie, Anlong Ming*: "Rethinking Image Aesthetics Assessment: Models, Datasets and Benchmarks.", [[pdf]](https://www.ijcai.org/proceedings/2022/0132.pdf) [[code]](https://github.com/woshidandan/TANet) IJCAI 2022, 人工智能领域顶会.
+ 在投4篇

其它资料：
+ "*图像美学质量评价调研报告.*" 知乎 [[link]](https://zhuanlan.zhihu.com/p/37307679)
+ "*这些年，计算机美学的发展.*" 知乎 [[link]](https://zhuanlan.zhihu.com/p/91516029)
+ Naila Murray, Luca Marchesotti, Florent Perronnin: "*AVA: A large-scale database for aesthetic visual analysis.*" CVPR (2012) [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6247954)
+ Hossein Talebi and Peyman Milanfar: "*NIMA: Neural image assessment.*" TIP (2018) [[pdf]](https://ieeexplore.ieee.org/abstract/document/8352823) [[code]](https://paperswithcode.com/paper/nima-neural-image-assessment#code)
+ Aydın, Tunç Ozan, Aljoscha Smolic, and Markus Gross: "*Automated aesthetic analysis of photographic images.*" IEEE T VIS COMPUT GR (2014) [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.675.3491&rep=rep1&type=pdf).


可用数据集
--------------
各类美学数据集大全，[点击链接](https://grappaproject.eu/databases/image_datasets/)

| 数据集名称  | 数据集描述  | 数据集规模    |   作用   | 链接|
| :-----------: | :--------: | :--------: | :--------: | :--------: |
| AVA★★★★★     |     人类对于图片进行1-10分的打分      |      255,500张图像    |      训练基础的美学模型     |     [链接](https://github.com/mtobeiyf/ava_downloader?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| DPChallenge.com     |     人类对于图片进行1-10分的打分      |      16,509张图像    |      训练基础的美学模型     |      [链接](https://ritendra.weebly.com/aesthetics-datasets.html?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| photo.net     |     人类对于图片进行1-10分的打分      |      20,278张图像    |      训练基础的美学模型     |      [链接](https://ritendra.weebly.com/aesthetics-datasets.html?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| TID2013★★★★★     |     人类对于多种处理后的失真图片进行1-10打分      |      25×24张照片，25张参考图像，24个失真类型    |      美学因素，图像质量客观评价因素     |      [链接 提取码: 9oc4](https://pan.baidu.com/s/1oj7tRDppmHV8DeCEuJNcJg)     |
| LIVE 提取码: g2sh  解压密码为：livedatabase2005  |     人类对于多种处理后的失真图片进行1-10打分      |      29×5张照片，29张参考图像，5个失真类型    |      美学因素，图像质量客观评价因素     |      [链接](https://pan.baidu.com/s/1gVcaWpIX9m8zER4XeWow9g)     |
| MLIVE     |     人类对于多种处理后的失真图片进行1-10打分      |      15×15张照片，15张参考图像，15个失真类型    |      美学因素，图像质量客观评价因素     |      [链接](http://live.ece.utexas.edu/research/quality/live_multidistortedimage.html?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| WATERLOO     |     人类对于多种处理后的失真图片进行1-10打分      |      4744张参考图像, 20个失真类型    |      美学因素，图像质量客观评价因素     |      [链接](https://ece.uwaterloo.ca/~k29ma/exploration/?spm=a2c6h.12873639.0.0.7707199420mLYv)     |
| flickr★★★★★     |     很多摄像师拍的照片，还附有相机参数和一些关键字评论      |      无数张？可以自己爬下来    |      美学因素，图像质量客观评价因素     |      [链接](https://www.flickr.com/)     |
| AADB★★★ | 包含11种摄影属性,5个人的平均评分 | 10000张图像 ,  8500 张训练，500 验证，1000 测试 | 评价美学维度 | [链接](https://drive.google.com/open?id=1Viswtzb77vqqaaICAQz9iuZ8OEYCu6-_) |
| PCCD | 有人对图像的评论和7个维度的评分 | 4,235张照片，29,645评论 | 评价美学维度、美学因素 | 链接？ |
| DPC- Captions | 5个维度的评分 | 154,384 images and 2,427,483 comments | 评价美学维度、美学因素 | 链接？ |
| KonIQ-10k★★★ | 包含总分、Brightness、Colorfulness、Contrast、Sharpness | 10,073张图像 | 评价美学维度 | [链接](http://database.mmsp-kn.de/koniq-10k-database.html) |
| CUHKPQ | 只包含好照片和不好照片，但是细分为动物，建筑等很多类 | 28,410张图像 | 评价美学维度 | [链接](http://mmlab.ie.cuhk.edu.hk/archive/CUHKPQ/Dataset.htm) |
| TAD66K | 自建数据集，按主题标注，分为47个主题 | 66,000张左右的图像 | 整体美学评分 | [链接](https://drive.google.com/drive/folders/1b2D9LeeG5XZzhEa8ldnIZjGh0IHadHhU) |

## 理论知识
+ "*李宏毅机器学习课程.*" 哔哩哔哩 [[link]](https://www.bilibili.com/video/BV1JE411g7XF?from=search&seid=16114573361443816126)

## 动手实践
+ "*动手学深度学习(PyTorch版).*" GitHub [[link]](https://tangshusen.me/Dive-into-DL-PyTorch/#/)
+ "*深度学习框架PyTorch：入门与实践.*" GitHub [[link]](https://github.com/chenyuntc/pytorch-book)

## 其它工具
+ "*Zotero.*" 论文整理工具 [[link]](https://www.zotero.org/)
+ "*connectedpapers.*" 论文追溯工具 [[link]](https://www.connectedpapers.com/)
+ "*Paperswithcode.*" 论文代码查找工具 [[link]](https://paperswithcode.com/)
+ "*Google colab.*" 免费线上GPU平台，如额外需要线下服务器资源，请联系我本人 [[link]](https://colab.research.google.com/notebooks/intro.ipynb)

## 组会和学习时间安排
+ 每周组会安排：一次小组会，一次大组会。小组会无老师参加，博士师兄带队，主要分享上一周科研进度和论文阅读情况，准备两三页的PPT即可。大组会一般在周五，有老师参加，汇报当前的科研进度，每次由一位同学汇报，一般最多一个月轮一次，基本无压力。
+ 组内同学学习时间要求：周一至周五白天，9:00-11:30，2:30-5:30，周日至周四晚上，7:30-10:00，该时间为组内成员正常在实验室学习时间，其余时间不做要求



https://user-images.githubusercontent.com/15050507/161776631-2b5948f3-97b6-4419-b0b3-efa5308eb116.mp4

https://user-images.githubusercontent.com/15050507/161776648-11426f17-8ef1-43ac-9a8a-5782cb32b2e2.mp4

