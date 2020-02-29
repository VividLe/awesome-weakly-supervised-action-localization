# Spatio-Temporal Action Detection
Papers and Results for Spatio-Temporal Action Detection

## Spatio-Temporal Action Localization

**Performance on AVA v2.1 dataset.**

- Metric: mAP with threshold 0.5.

|  Detector   |   val   |   test    |
| :---------: | :-----: | :-------: |
|    LFB      |	27.70 	|	27.20 	|
|   VATN*     |	25.00 	|	24.93 	|
|   SMAD*     |	22.20 	|	  -  	|
|   STEP      |	18.60 	|	  -  	|
|   ACRN      |	17.40 	|	  -  	|
|    AVA      |	15.80 	|	  -  	|
|  SlowFast   |	27.30 	|	27.10	|

## Spatio-temporal Action Detection

* **PSCS:** Rui Su, Wanli Ouyang, Luping Zhou, Dong Xu.<br />
  "Improving Action Localization by Progressive Cross-stream Cooperation." CVPR (2019).
  [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Su_Improving_Action_Localization_by_Progressive_Cross-Stream_Cooperation_CVPR_2019_paper.pdf)]

* **SlowFast:** Christoph Feichtenhofer, Haoqi Fan, Jitendra Malik, Kaiming He.<br />
  "SlowFast Networks for Video Recognition." arXiv (1812). 
  [[paper](https://arxiv.org/pdf/1812.05038.pdf)]
  [[unofficial_code](https://github.com/r1ch88/SlowFastNetworks)]
  [[unofficial_code](https://github.com/Guocode/SlowFast-Networks)]

* **DwF:** Jiaojiao Zhao, Cees G.M. Snoek.<br />
  "Dance with Flow: Two-in-One Stream Action Detection." CVPR (2019). 
  [[paper](https://arxiv.org/pdf/1904.00696.pdf)]

* **STEP:** Xitong Yang, Xiaodong Yang, Ming-Yu Liu, Fanyi Xiao, Larry Davis, Jan Kautz.<br />
  "STEP: Spatio-Temporal Progressive Learning for Video Action Detection." CVPR (2019 **oral**). 
  [[paper](https://arxiv.org/pdf/1904.09288.pdf)]

* **LFB:** Chao-Yuan Wu, Christoph Feichtenhofer, Haoqi Fan, Kaiming He, Philipp Krähenbühl, Ross Girshick.<br />
  "Long-Term Feature Banks for Detailed Video Understanding." CVPR (2019). 
  [[paper](https://arxiv.org/pdf/1812.05038.pdf)]
  [[project](https://github.com/facebookresearch/video-long-term-feature-banks)]

* **VATN*:** Rohit Girdhar, João Carreira, Carl Doersch, Andrew Zisserman. <br />
  "Video Action Transformer Network." CVPR (2019 **oral**). 
  [[paper](https://arxiv.org/pdf/1812.02707.pdf)]
  [[project](https://rohitgirdhar.github.io/ActionTransformer/)]

* **LAEO:** Manuel J Marin-Jimenez, Vicky Kalogeiton, Pablo Medina-Suarez, Andrew Zisserman. <br />
  "LAEO-Net: revisiting people Looking At Each Other in videos." CVPR (2019). 
  [[paper](http://www.robots.ox.ac.uk/~vgg/research/laeonet/cvpr2019LAEO.pdf)]
  [[code](https://github.com/AVAuco/laeonet/)]
  [[project](http://www.robots.ox.ac.uk/~vgg/research/laeonet/)]

* **SMAD*:** Yubo Zhang, Pavel Tokmakov, Martial Hebert, Cordelia Schmid. <br />
  "A Structured Model For Action Detection." CVPR (2019). 
  [[paper](https://arxiv.org/pdf/1812.03544.pdf)]

* **TACNet:** Lin Song, Shiwei Zhang, Gang Yu, Hongbin Sun. <br />
  "TACNet: Transition-Aware Context Network for Spatio-Temporal Action Detection." CVPR (2019). 
  [[paper](http://www.skicyyu.org/Paper/CVPR2019_TACNET.pdf)]

* **AVA:** Chunhui Gu, Chen Sun, David A. Ross, Carl Vondrick, Caroline Pantofaru, Yeqing Li, Sudheendra Vijayanarasimhan, George Toderici, Susanna Ricco, Rahul Sukthankar, Cordelia Schmid, Jitendra Malik. <br />
  "AVA: A Video Dataset of Spatio-Temporally Localized Atomic Visual Actions." CVPR (2018). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gu_AVA_A_Video_CVPR_2018_paper.pdf)]
  [[project](https://research.google.com/ava/)]

* **ACRN:** Chen Sun, Abhinav Shrivastava, Carl Vondrick, Kevin Murphy, Rahul Sukthankar, Cordelia Schmid. <br />
  "Actor-Centric Relation Network." ECCV (2018). 
  [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Chen_Sun_Actor-centric_Relation_Network_ECCV_2018_paper.pdf)]

* **T-CNN:** Rui Hou, Chen Chen, Mubarak Shah. <br />
  "Tube Convolutional Neural Network (T-CNN) for Action Detection in Videos." ICCV (2017). 
  [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Hou_Tube_Convolutional_Neural_ICCV_2017_paper.pdf)]
  [[code](https://www.crcv.ucf.edu/projects/TCNN/#Code)]
  [[project](https://www.crcv.ucf.edu/projects/TCNN/)]


## Dataset
* **YouTube-8M-Segments:** Ke Chen, Julia Elliott, Nisarg Kothari, Hanhan Li, et.al.<br />
  "YouTube-8M Segments Dataset" 
  [[project](https://research.google.com/youtube8m/)]
  

## Distinguished Researchers & Teams
[WILLOW](https://www.di.ens.fr/willow/publications/YearOnly/publications.html)
[Ivan Laptev](https://www.di.ens.fr/~laptev/#Publications)
[Christoph Feichtenhofer](https://feichtenhofer.github.io/)
