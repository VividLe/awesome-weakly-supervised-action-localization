# Action Detection Benchmarks
Papers and Results of Temporal Action Localization

## Temporal Action Localization

**Performance on THUMOS'14 dataset.**

- The detectors are ordered by the mAP with threshold 0.5.
- `Deep Learning`: deep learning related method.

|  Detector   |   0.1   |    0.2  |    0.3  |    0.4  |   0.5   |    0.6  |    0.7   |Deep Learning|Comment      |
| :---------: | :-----: |:-------:|:-------:|:-------:|:-------:|:-------:| :------: | :--------:  | :--:      |
|     TGM     |    -  	|    -  	|    -  	|    -  	|   53.5 	|    -  	|    -     |      Y      |     -     |
|   C-TCN     |   72.2 	|   71.4 	|   68.0 	|   62.3 	|   52.1 	|    -   	|    -   	 |      Y      |     -     |
|   RTD-Net     |    -   	|    -  	|   68.3 	|   62.3  	|   51.9 	|   38.8   	|    23.7 	 |      Y      |  based on P-GCN    |
|   PGC-TAL     |   71.2  	|   68.9 	|   65.1 	|   59.5 	|   51.2 	|    -   	|    -   	 |      Y      |  based on P-GCN    |
|    DPP      |   69.5 	|   67.8 	|   63.6 	|   57.8 	|   49.1 	|    -   	|    -   	 |      Y      |     -     |
|    PGCN     |   69.5 	|   67.8 	|   63.6 	|   57.8 	|   49.1 	|    -   	|    -   	 |      Y      |     -     |
|     BMN     |    -  	|    -  	|   56.0 	|   47.4 	|   38.8 	|   29.7 	|   20.5   |      Y      |     -     |
|   D-SSAD    |    -  	|    -  	|   60.2 	|   54.1 	|   44.2 	|   32.3 	|   19.1   |      Y      |     -     |
|   TAL-Net   |   59.8 	|   57.1 	|   53.2 	|   48.5 	|   42.8 	|   33.8 	|   20.8   |      Y      |     -     |
|    FRTS     |    -  	|    -  	|   53.5 	|   50.2 	|   44.2 	|   33.9 	|   22.7   |      Y      |     -     |
|    GTAN     |   69.1 	|   63.7 	|   57.8 	|   47.2 	|   38.8 	|    -   	|    -     |      Y      |     -     |
|    AGCN     |   59.3 	|   59.6 	|   57.1 	|   51.6 	|   38.6 	|    28.9 	|   17.0   |      Y      |     -     |
|    MGG      |    -  	|    -  	|   53.9 	|   46.8 	|   37.4 	|   29.5 	|   21.3   |      Y      |     -     |
|    BSN      |    -  	|    -  	|   53.5 	|   45.0 	|   36.9 	|   28.4 	|   20.0   |      Y      |     -     |
|    FSN      |    -  	|    -  	|   51.8 	|   41.5 	|   32.1 	|   22.9 	|   14.7   |      Y      |     -     |
|    CBR      |   60.1 	|   56.7 	|   50.1 	|   41.3 	|   31.0 	|   19.1 	|   9.9    |      Y      |     -     |
|   ASSA*     |    -  	|    -  	|   51.8 	|   42.4 	|   30.8 	|   20.2 	|   11.1   |      Y      |     -     |
|   CTAP      |    -  	|    -  	|    -  	|    -  	|   29.9 	|    -  	|    -     |      Y      |     -     |
|  SS-TAD     |    -  	|    -  	|   45.7 	|    -  	|   29.2 	|    -  	|   9.6    |      Y      |701 fps(GTX Titan X (Maxwell))|
|    SSN      |   60.3 	|   56.2 	|   50.6 	|   40.8 	|   29.1 	|    -  	|    -     |      Y      |     -     |
|   R-C3D     |   54.5 	|   51.5 	|   44.8 	|   35.6 	|   28.9 	|    -  	|    -     |      Y      |569 fps|
|    TAG      |   64.1 	|   57.7 	|   48.7 	|   39.8 	|   28.2 	|    -  	|    -     |      Y      |     -     |
|    TPC      |    -  	|    -  	|   44.1 	|   37.1 	|   28.2 	|   20.6 	|   12.7   |      Y      |250 fps (GTX Titan X)|
|   TURN      |   54.0 	|   50.9 	|   44.1 	|   34.9 	|   25.6 	|    -  	|    -     |      Y      |129.4 fps (GTX Titan X)|
|   SSAD      |   50.1 	|   47.8 	|   43.0 	|   35.0 	|   24.6 	|    -  	|    -     |      Y      |     -     |
|    CDC      |    -  	|    -  	|   40.1 	|   29.4 	|   23.3 	|   13.1 	|   7.9    |      Y      |500 fps (GTX Titan X)|
|    SST      |    -  	|    -  	|   37.8 	|    -  	|   23.0 	|    -  	|    -     |      Y      |308 fps Titan-X|
|   S-CNN     |   47.7 	|   43.5 	|   36.3 	|   28.7 	|   19.0 	|   10.3 	|   5.3    |      Y      |60 fps(GeForce GTX 980)|
|   PSDF*     |   51.4 	|   42.6 	|   33.6 	|   26.1 	|   18.8 	|    -  	|    -     |      Y      |     -     |
|   SMS*      |   51.0 	|   45.2 	|   36.5 	|   27.8 	|   17.8 	|    -  	|    -     |      N      |     -     |
|   ADFG*     |   48.9 	|   44.0 	|   36.0 	|   26.4 	|   17.1 	|    -  	|    -     |      Y      |     -     |
|    TCN      |    -  	|    -  	|   33.3 	|   25.6 	|   15.9 	|   9.0 	|    -     |      Y      |     -     |
|    DAP      |    -  	|    -  	|    -  	|    -  	|   13.9 	|    -  	|    -     |      Y      |134.1 fps Titan-X|
|  G-TAD      |   -   	|    -   	|   54.5	|    47.6	|   40.2 	|   30.8 	|   23.4   |      Y      |     -     |
|  PTAL-ETP   |   -   	|    -   	|   48.2	|    42.4	|   34.2 	|   23.4 	|   13.9   |      Y      |     -     |
|  CTR_AL     |   -   	|    -   	|   53.9	|    50.7	|   45.4 	|   38.0 	|   28.5   |      Y      |     -     |
| LS-TD       | arXiv  |-|63.5 |61.0 |56.7 |50.6 |42.6 |32.5 |21.4 |-    |-    |-    |    -     |
| SRG         | arXiv  |-|-    |-    |54.5 |46.9 |39.1 |31.4 |22.2 |-    |-    |-    |    -     |
| IDU         | arXiv  |-|-    |-    |- |- |- |- |- |-    |-    |Under a different metric    |    -     |


**Performance on ActivityNet v1.3 dataset.**
- The left half is score on ActivityNet v1.3 validation dataset. The right half is score on ActivityNet v1.3 testing dataset. 
- `Deep Learning`: deep learning related method.

|  Detector   |   0.50  |    0.75   |    0.95   |    @Avg   |   0.50    |   0.75    |   0.95    |    @Avg   |Deep Learning|Speed  |
| :---------: | :-----: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :------:  | :--------:  | :--:  |
|     BMN     |	50.07 	|	   34.78 	|	8.29 	    |	33.85 	  |	 -      	|	 -  	    |	 -       	|	36.42	    |      Y      | -     |
|    GTAN     |	52.61 	|	   34.14 	|	8.91 	    |	34.31 	  |	 -      	|	 -  	    |	 -  	    |	35.54	    |      Y      | -     |
|    PGCN     |	48.26 	|	  33.16 	|	3.27 	    |	31.11   	|	 -      	|	 -  	    |	 -      	|	  -  	    |      Y      | -     |
|   RTD-Net   |	46.43 	|	  30.45  	|	8.64      |	30.46   	|	 -      	|	 -  	    |	 -      	|	  -  	    |      Y      | -     |
|   BSN_ori   |	46.45 	|	  29.96 	|	8.02    	|	30.03   	|	 -      	|	 -      	|	 -      	|	32.84    	|      Y      | -     |
|   BSN_new   |	52.50 	|	  33.53 	|	8.85 	    |	33.72   	|	 -      	|	 -      	|	 -      	|	34.42	    |      Y      | -     |
|    C-TCN    |	 47.6 	|  	31.9  	|	6.2      	|	 31.1   	|	 -      	|	 -  	    |	 -      	|	  -     	|      Y      | -     |
|    PGC-TAL    |	44.31 	|  	29.85  	|	5.47  	|	 28.85   	|	 -      	|	 -  	    |	 -      	|	  -     	|      Y      | based on P-GCN  |
|    SSN      |	 -    	|	    -   	|	 -  	    |	 -  	    |	43.26    	|	28.70    	|	5.63     	|	28.28	    |      Y      | -     |
|    TAG      |	39.12 	| 	23.48 	|	5.49    	|	23.98    	|	40.69 	  |	26.02   	|	6.67 	    |	26.05	    |      Y      | -     |
|    CDC      |	45.30 	|	  26.00 	|	0.20 	    |	23.80   	|	 -      	|	 -      	|	 -      	|	 -  	    |      Y      |500 fps (GTX Titan X)|
|    TCN      |	36.44 	|	  21.15 	|	3.90 	    |	 -  	    |	37.49   	|	23.47   	|	4.47    	|	23.58	    |      Y      | -     |
|   TAL-Net   |	38.23 	|	  18.30 	|	1.30 	    |	20.22   	|	 -  	    |	 -  	    |	 -  	    |	 -  	    |      Y      | -     |
|   AGCN   |	30.4 	|	   -  		|	 -  	    |	 -  	   	|	 -  	    |	 -  	    |	 -  	    |	 -  	    |      Y      | -     |
|    SCC      |	   -  	|	 -      	|	 -  	    |	 -  	    |	39.90    	|	18.70   	|	4.70    	|	19.30	    |      Y      |  35.9 fps  |
|   R-C3D     |	26.80 	|	 -      	|	 -  	    |	12.70   	|	 -  	    |	 -  	    |	 -      	|	13.10    	|      Y      |569 fps (GTX Titan X (Maxwell))  <br>1030 fps (Titan X Pascal)|
| G-TAD       |  50.36  |   34.6    |  9.02     |  34.09    |  -        |     -     |	 -      	|	-         |      Y      | -     |
| CTR_AL      |  43.47  |   33.91   |  9.21     |  30.12    |  -        |     -     |	 -      	|	-         |      Y      | -     |
| SRG         |  46.53  |    -    |    -    |    -     |    -    |  29.98 |    -    |    -    |   -    |  4.83 |  29.72 |  -    |     -    |


**Performance on ActivityNet v1.2 dataset.**
|   LS-TD     |  50.4   | -       |   -     |  -       |    -    |  34.9  |  -      |   -     |  -     |   8.0 |  33.6  | -     |     -    |

### Temporal Action Localization
* **TGM:** AJ Piergiovanni, Michael S. Ryoo.<br />
  "Temporal Gaussian Mixture Layer for Videos." ICML (2019). 
  [[paper](https://arxiv.org/pdf/1803.06316.pdf)]
  [[code](https://github.com/piergiaj/tgm-icml19)]
  
* **RTD-Net:** Jing Tan, Jiaqi Tang, Limin Wang, Gangshan Wu.<br />
  "Relaxed Transformer Decoders for Direct Action Prop." arXiv 2102.01894. 
  [[paper](https://arxiv.org/pdf/2102.01894.pdf)]

* **DPP:** Luxuan Li, Tao Kong, Fuchun Sun, Huaping Liu.<br />
  "Deep Point-wise Prediction for Action Temporal Proposal." ArXiv 1909.07725. 
  [[paper](https://arxiv.org/pdf/1909.07725.pdf)]
  [[code](https://github.com/liluxuan1997/DPP)]
  
* **C-TCN:** Xin Li, Tianwei Lin, Xiao Liu, Chuang Gan, Wangmeng Zuo, Chao Li.<br />
  "Deep Concept-wise Temporal Convolutional Networks for Action Localization." ArXiv 1908.09442.
  [[paper](https://arxiv.org/pdf/1908.09442.pdf)]
  [[code](https://github.com/PaddlePaddle/models/blob/develop/PaddleCV/PaddleVideo/models/ctcn/README.md)]

* **PGC-TAL:** Rui Su, Dong Xu, Lu Sheng, Wangli Ouyang.<br />
  "PCG-TAL: Progressive Cross-granularity Cooperation for Temporal Action Localization." TIP 2020.
  [[paper](https://ieeexplore.ieee.org/document/9298475)]]

* **BMN:** Tianwei Lin, Xiao Liu, Xin Li, Errui Ding, Shilei Wen.<br />
  "BMN : Boundary-Matching Network for Temporal Action Proposal Generation." ICCV (2019). 
  [[paper](https://arxiv.org/pdf/1907.09702.pdf)]

* **PGCN:** Runhao Zeng, Wenbing Huang, Mingkui Tan, Yu Rong, Peilin Zhao, Junzhou Huang, Chuang Gan.<br />
  "Graph Convolutional Networks for Temporal Action Localization." ICCV (2019). 
  [[paper](https://arxiv.org/pdf/1909.03252.pdf)]
  [[code](https://github.com/Alvin-Zeng/PGCN)]

* **GTAN:** Fuchen Long, Ting Yao, Zhaofan Qiu, Xinmei Tian, Jiebo Luo, Tao Mei.<br />
  "Gaussian Temporal Awareness Networks for Action Localization." CVPR (2019 **oral**). 
  [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Long_Gaussian_Temporal_Awareness_Networks_for_Action_Localization_CVPR_2019_paper.pdf)]

* **AGCN:** Jun Li, Xianglong Liu, Zhuofan Zong, Wanru Zhao, Mingyuan Zhang, Jingkuan Song.<br />
  "Graph Attention based Proposal 3D ConvNets for Action Detection." AAAI (2020).
  [[paper](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-LiJ.1424.pdf)]

* **MGG:** Yuan Liu, Lin Ma, Yifeng Zhang, Wei Liu, Shih-Fu Chang.<br />
  "Multi-granularity Generator for Temporal Action Proposal." CVPR (2019). 
  [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Multi-Granularity_Generator_for_Temporal_Action_Proposal_CVPR_2019_paper.pdf)]

* **D-SSAD:** Yupan Huang, Qi Dai, Yutong Lu.<br />
  "Decoupling Localization and Classification in Single Shot Temporal Action Detection." ICME (2019). 
  [[paper](https://arxiv.org/pdf/1904.07442.pdf)]
  [[code](https://github.com/HYPJUDY/Decouple-SSAD)]

* **TAL-Net:** Yu-Wei Chao, Sudheendra Vijayanarasimhan, Bryan Seybold, David A. Ross, Jia Deng, Rahul Sukthankar.<br />
  "Rethinking the Faster R-CNN Architecture for Temporal Action Localization." CVPR (2018). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chao_Rethinking_the_Faster_CVPR_2018_paper.pdf)]
  
 * **FRTS:** Tingting Xie, Xiaoshan Yang, Tianzhu Zhang, Changsheng Xu, Ioannis Patras.<br />
    "Exploring Feature Representation and Training strategies in Temporal Action Localization." ICIP (2019). 
    [[paper](https://arxiv.org/pdf/1905.10608.pdf)]

* **BSN:** Tianwei Lin, Xu Zhao, Haisheng Su, Chongjing Wang, Ming Yang.<br />
  "BSN: Boundary Sensitive Network for Temporal Action Proposal Generation." ECCV (2018). 
  [[paper](https://arxiv.org/pdf/1806.02964.pdf)]
  [[code](https://github.com/wzmsltw/BSN-boundary-sensitive-network)]

* **FSN:** Ke Yang, Xiaolong Shen, Peng Qiao, Shijie Li, Dongsheng Li, Yong Dou.<br />
  "Exploring frame segmentation networks for temporal action localization." ECCV (2018). 
  [[paper](https://arxiv.org/pdf/1902.05488.pdf)]

* **CBR:** Jiyang Gao, Zhenheng Yang, Ram Nevatia.<br />
  "Cascaded Boundary Regression for Temporal Action Detection." BMVC (2017). 
  [[paper](https://arxiv.org/pdf/1705.01180.pdf)]
  [[code](https://github.com/jiyanggao/CBR)]

* **ASSA*:** Humam Alwassel, Fabian Caba Heilbron, Bernard Ghanem.<br />
  "Action Search: Spotting Actions in Videos and Its Application to Temporal Action Localization." ECCV (2018). 
  [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Humam_Alwassel_Action_Search_Spotting_ECCV_2018_paper.pdf)]

* **CTAP:** Jiyang Gao, Kan Chen, Ram Nevatia.<br />
  "CTAP: Complementary Temporal Action Proposal Generation." ECCV (2018). 
  [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Jiyang_Gao_CTAP_Complementary_Temporal_ECCV_2018_paper.pdf)]
  [[code](https://github.com/jiyanggao/CTAP)]

* **SS-TAD:** Shyamal Buch, Victor Escorcia, Bernard Ghanem, Li Fei-Fei, Juan Carlos Niebles.<br />
  "End-to-end, single-stream temporal action detection in untrimmed videos." BMVC (2017). 
  [[paper](http://vision.stanford.edu/pdf/buch2017bmvc.pdf)]
  [[code](https://github.com/shyamal-b/ss-tad)]

* **SSN:** Yue Zhao, Yuanjun Xiong, Limin Wang, Zhirong Wu, Xiaoou Tang, Dahua Lin.<br />
  "Temporal Action Detection with Structured Segment Networks." ICCV (2017). 
  [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhao_Temporal_Action_Detection_ICCV_2017_paper.pdf)]
  [[code](https://github.com/yjxiong/action-detection)]

* **R-C3D:** Huijuan Xu, Abir Das, Kate Saenko.<br />
  "R-C3D: Region Convolutional 3D Network for Temporal Activity Detection." ICCV (2017). 
  [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Xu_R-C3D_Region_Convolutional_ICCV_2017_paper.pdf)]
  [[code](https://github.com/VisionLearningGroup/R-C3D)]

* **TAG:** Yuanjun Xiong, Yue Zhao, Limin Wang, Dahua Lin, Xiaoou Tang.<br />
  "A Pursuit of Temporal Accuracy in General Activity Detection." arXiv (1703). 
  [[paper](https://arxiv.org/pdf/1703.02716.pdf)]

* **TPC:** Ke Yang, Peng Qiao, Dongsheng Li, Shaohe Lv, Yong Dou.<br />
  "Exploring Temporal Preservation Networks for Precise Temporal Action Localization." AAAI (2018). 
  [[paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16164/16347)]

* **TURN:** Jiyang Gao, Zhenheng Yang, Chen Sun, Kan Chen, Ram Nevatia.<br />
  "TURN TAP : Temporal Unit Regression Network for Temporal Action Proposals." ICCV (2017). 
  [[paper](https://arxiv.org/pdf/1703.06189.pdf)]
  [[code](https://github.com/jiyanggao/TURN-TAP)]

* **SSAD:** Tianwei Lin, Xu Zhao, Zheng Shou.<br />
  "Single shot temporal action detection." ACM MM (2017). 
  [[paper](https://arxiv.org/pdf/1710.06236.pdf)]

* **CDC:** Zheng Shou, Jonathan Chan, Alireza Zareian, Kazuyuki Miyazawa, Shih-Fu Chang.<br />
  "CDC Convolutional-De-Convolutional Networks for Precise Temporal Action Localization in Untrimmed Videos." CVPR (2017). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Shou_CDC_Convolutional-De-Convolutional_Networks_CVPR_2017_paper.pdf)]
  [[code](https://github.com/ColumbiaDVMM/CDC)]
  [[project](http://www.ee.columbia.edu/ln/dvmm/researchProjects/cdc/)]

* **SST:** Shyamal Buch, Victor Escorcia, Chuanqi Shen, Bernard Ghanem, Juan Carlos Niebles.<br />
  "Single-stream temporal action proposals." CVPR (2017). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Buch_SST_Single-Stream_Temporal_CVPR_2017_paper.pdf)]
  [[code](https://github.com/shyamal-b/sst)]

* **SCC:** Fabian Caba Heilbron, Wayner Barrios, Victor Escorcia, Bernard Ghanem.<br />
  "SCC: Semantic context cascade for efficient action detection." CVPR (2017). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Heilbron_SCC_Semantic_Context_CVPR_2017_paper.pdf)]
  [[project](https://ivul.kaust.edu.sa/Pages/pub-scc-efficient-action-detection.aspx)]

* **S-CNN:** Zheng Shou, Dongang Wang, Shih-Fu Chang.<br />
  "Temporal Action Localization in Untrimmed Videos via Multi-stage CNNs." CVPR (2016). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2016/papers/Shou_Temporal_Action_Localization_CVPR_2016_paper.pdf)]
  [[code](https://github.com/zhengshou/scnn)]

* **PSDF*:** Jun Yuan, Bingbing Ni, Xiaokang Yang, Ashraf A. Kassim.<br />
  "Temporal Action Localization with Pyramid of Score Distribution Features." CVPR (2016). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2016/papers/Yuan_Temporal_Action_Localization_CVPR_2016_paper.pdf)]

* **SMS*:** Zehuan Yuan, Jonathan C. Stroud, Tong Lu, Jia Deng.<br />
  "Temporal Action Localization by Structured Maximal Sums." CVPR (2017). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yuan_Temporal_Action_Localization_CVPR_2017_paper.pdf)]

* **ADFG*:** Serena Yeung, Olga Russakovsky, Greg Mori, Li Fei-Fei.<br />
  "End-to-end Learning of Action Detection from Frame Glimpses in Videos." CVPR (2016). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2016/papers/Yeung_End-To-End_Learning_of_CVPR_2016_paper.pdf)]
  [[code](https://github.com/syyeung/frameglimpses)]

* **TCN:** Xiyang Dai, Bharat Singh, Guyue Zhang, Larry S. Davis, Yan Qiu Chen.<br />
  "Temporal Context Network for Activity Localization in Videos." ICCV (2017). 
  [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Dai_Temporal_Context_Network_ICCV_2017_paper.pdf)]
  [[code](https://github.com/vdavid70619/TCN)]
  
 * **DAP:** Victor Escorcia, Fabian Caba Heilbron, Juan Carlos Niebles, Bernard Ghanem.<br />
    "DAPs: Deep Action Proposals for Action Understanding." ECCV (2016). 
    [[paper](https://ivul.kaust.edu.sa/Documents/Publications/2016/DAPs%20Deep%20Action%20Proposals%20for%20Action%20Understanding.pdf)]
    [[code](https://github.com/escorciav/daps)] 

* **G-TAD**Mengmeng Xu, Chen Zhao, David S. Rojas, Ali Thabet, Bernard Ghanem Visual Computing Center.<br />
  "G-TAD: Sub-Graph Localization for Temporal Action Detection" ArXiv(2019)
  [[paper](https://arxiv.org/pdf/1911.11462.pdf)]

* **PTAL-ETP**Haonan Qiu, Yingbin Zheng, Hao Ye, Yao Lu, Feng Wang, Liang He.<br />
  "Precise Temporal Action Localization by Evolving Temporal Proposals"ArXiv(2019)
  [[paper](https://arxiv.org/pdf/1804.04803.pdf)]

* **CTR_AL**Peisen Zhao1, Lingxi Xie2, Chen Ju1, Ya Zhang1, Qi Tian.<br />
  "Constraining Temporal Relationship for Action Localization"ArXiv(2019)
  [[paper](https://arxiv.org/pdf/2002.07358.pdf)]

* **SRG**Hyunjun Eun, Sumin Lee, Jinyoung Moon, Jongyoul Park, Chanho Jung, Changick Kim.<br />
  "SRG: Snippet Relatedness-based Temporal Action Proposal Generator"Arxiv(2019)
  [[paper](https://arxiv.org/pdf/1911.11306.pdf)]

* **LS-TD**Yuan Zhou, Hongru Li, Sun-Yuan Kung, Life Fellow.<br />
  "Temporal Action Localization using Long Short-Term Dependency"Arxiv(2019)
  [[paper](https://arxiv.org/pdf/1911.01060.pdf)]

* **IDU** Eun, Hyunjun and Moon, Jinyoung and Park, Jongyoul and Jung, Chanho and Kim, Changick.<br />
  "Learning to Discriminate Information for Online Action Detection" CVPR(2020)
  [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Eun_Learning_to_Discriminate_Information_for_Online_Action_Detection_CVPR_2020_paper.pdf)]
