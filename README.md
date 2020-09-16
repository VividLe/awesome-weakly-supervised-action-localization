# Action Localization Benchmarks
Papers and Results of Temporal Action Localization

**Weakly Supervised Performance on THUMOS'14 dataset.**

- The detectors are sorted by the mAP with threshold 0.5.
- "c" indicates whether release code, yes (Y) or no (N).
- "e" indicates the evaluation code, THUMOS (T), ActivityNet (A) or implemented by themselves.


|  Detector   |   Pub  |c|e| 0.1 | 0.2 | 0.3 |0.4  | 0.5 | 0.6 | 0.7 | 0.8 | 0.9 |avg  |   info   |
| :---------: |:------:|-|-|:---:|:----|:----|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :------: |
| EM-MIL  | ECCV20 |N|A|59.1 |52.7 |45.5 |36.8 |30.5 | 22.7 | 16.4 | - | - | -   | Use existing classifiation results |
| ACL  | CVPR20 |N|A| - | - |46.9 |38.9 |30.1 |19.8 |10.4 | -  | -  | -   | Report unsupervised performance as well |
| WSTAL       | WACV20  |-| |62.3 |-    |46.8 |-    |29.6 |-    |9.7  |-    |-    |-    |    -     |
| ActionBytes  | CVPR20 |N|A| - | - |43.0 |37.5 |29.0 | - |9.5 | -  | -  | -   | - |
| DGAM  | CVPR20 |Y|A| 60.0|54.2 |46.8 |38.2 |28.8 |19.8 |11.4 |3.6  |0.4  | -   |    -     |
| BaSNet-I3D  | AAAI20 |Y|A| 58.2|52.3 |44.6 |36.0 |27.0 |18.6 |10.4 |3.9  |0.5  | -   |    -     |
| BaSNet-UNT  | AAAI20 |Y|A| 56.2|50.3 |42.8 |34.7 |25.1 |17.1 |9.3  |3.7  |0.5  | -   |    -     |
|   WSBM      | ICCV19 |N|A| 60.4|56.0 |46.6 |37.5 |26.8 |17.6 |9.0  |3.3  |0.4  | -   |    -     |
|   3C-Net    | ICCV19 |Y|I| 59.1|53.5 |44.2 |34.1 |26.6 |  -  |8.1  |  -  | -   | -   |    -     |
|    ASSG     | ACM 19 |N| | 65.6|59.4 |50.4 |38.7 |25.4 |15.0 |6.6  |  -  |  -  | -   |    -     |
|    TSM      | ICCV19 |N|T|  -  | -   |39.5 |31.9 |24.5 |13.8 |7.1  |  -  |  -  |23.4 |    -     |
|  CleanNet   | ICCV19 |N|T|  -  | -   |37.0 |30.9 |23.9 |13.9 |7.1  |  -  |  -  | -   |    -     |
|  CMCS-I3D   | CVPR19 |Y|T| 57.4|50.8 |41.2 |32.1 |23.1 |15.0 |7.0  |  -  | -   | -   |report avg-mAP|
|  CMCS-UNT   | CVPR19 |Y|T| 53.5|46.8 |37.5 |29.1 |19.9 |12.3 |6.0  |  -  | -   | -   |    -     |
|  STARNet    | AAAI19 |N|A|68.8 |60.0 |48.7 |34.7 |23.0 |-    |-    |  -  |  -  |-    |    -     |
|  W-TALC     | ECCV18 |Y|I|55.2 |49.6 |40.1 |31.1 |22.8 |-    |-    |  -  |  -  |7.6  |    -     |
|  AutoLoc    | ECCV18 |Y|T|-    |-    |35.8 |29.0 |21.2 |13.4 |5.8  |  -  |  -  |-    |    -     |
|  MAAN       | ICLR19 |Y|A|59.8 |50.8 |41.1 |30.6 |20.3 |12.0 |6.9  |2.6  |0.2  |94.1 |    -     |
|  LTSR       | AAAI19 |N|T|55.9 |46.9 |38.3 |28.1 |18.6 |11.0 |5.59 |2.19 |0.29 |-    |    -     |
| WSGN        | WACV20 |-|T|51.1 |44.4 |34.9 |26.3 |18.1 |11.6 |6.5  |-    |-    |-    |    -     |
|  STPN       | CVPR18 |I|A|52.0 |44.7 |35.5 |25.8 |16.9 |9.9  |4.3  |1.2  |0.1  |-    |    -     |
|  CPMN       | ACCV18 |N|T|47.1 |41.6 |32.8 |24.7 |16.1 |10.1 |5.5  |-    |-    |-    |    -     |
|  S-O-C      | ACM18  |N|T|45.8 |39.0 |31.1 |22.5 |15.9 |-    |-    |-    |-    |-    |    -     |
|UntrimmedNets| CVPR17 |Y|T|44.4 |37.7 |28.2 |21.1 |13.7 |-    |-    |-    |-    |-    |    -     |
|  H&S        | ICCV17 |Y|T|36.44|27.84|19.49|12.66|6.84 |-    |-    |-    |-    |-    |    -     |
|LPAT-I3D+TEM | arXiv  |-| |-    |-    |46.9 |37.4 |28.0 |16.6 |9.2  |-    |-    |27.6 |    -     |
| LPAT-I3D    | arXiv  |-| |-    |-    |46.7 |37.5 |27.9 |17.6 |9.2  |-    |-    |27.6 |    -     |
| LPAT-U      | arXiv  |-| |-    |-    |39.9 |31.5 |22.6 |14.2 |7.9  |-    |-    |27.6 |    -     |
|RefineLoc-I3D| arXiv  |-|T|-    |-    |40.8 |-    |23.1 |-    |5.3  |-    |-    |-    |    -     |
|RefineLoc-TSN| arXiv  |-|T|-    |-    |36.1 |-    |22.6 |-    |5.8  |-    |-    |-    |    -     |



**Weakly Supervised Performance on ActivityNet v1.2 dataset.**
|  Detector   |  Pub   |c| 0.5 | 0.55|0.60 | 0.65|0.70 |0.75 | 0.80|0.85 |0.90 |0.95 | avg |test |   info   |
| :---------: |:------:|-|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :------: |
| BaSNet-I3D  | AAAI20 |Y|38.5 |   - | -   |  -  | -   |24.2 |  -  | -   | -   | 5.6 | 24.3|   - |     -    |
| CMCS        | CVPR19 |Y|36.8 |-    |-    |-    | -   |22.0 |-    |-    |-    | 5.6 | 22.4|   - |     -    |
| 3C-Net      | ICCV19 |Y|35.4 |   - | -   |  -  | -   |22.9 |  -  | -   | -   | 8.5 | 21.1|   - |     -    |
| TSM         | ICCV19 |N|28.3 |26.0 |23.6 |21.2 | 18.9|17.0 |14.0 |11.1 |7.5  | 3.5 | -   |   - |     -    |
| CleanNet    | ICCV19 |N|37.1 |33.4 |29.9 |26.7 | 23.4|20.3 |17.2 |13.9 |9.2  | 5.0 | 21.6|   - |     -    |
| W-TALC      | ECCV18 |Y|37.0 |-    |-    |-    | 14.6|-    |-    |-    |-    | -   | 18.0|   - |     -    |
| AutoLoc     | ECCV18 |Y|27.3 |24.9 |22.5 |19.9 | 17.5|15.1 |13.0 |10.0 |6.8  | 3.3 | 16.0| -   |     -    |
|RefineLoc-I3D| arXiv  |-|38.7 |-    |-    |-    | -   |22.6 |-    |-    |-    | 5.5 | 23.2| -   |     -    |
|RefineLoc-TSN| arXiv  |-|38.8 |-    |-    |-    | -   |22.2 |-    |-    |-    | 5.3 | 23.2| -   |     -    |
| LPAT        | arXiv  |-|37.6 |34.6 |31.6 |28.7 | 25.6|22.6 |19.6 |15.3 |10.9 | 4.9 | 23.1| -   |     -    |
|   WSTAL     | arXiv  |-|35.2 |-    |-    |-    | 16.3|-    |-    |-    |-    | -   | -   | -   |     -    |


**Weakly Supervised Performance on ActivityNet v1.3 dataset.**
|  Detector   |  Pub   |c| 0.5 |0.75 |0.95 |avg  |test |   info   |
| :---------: |:------:|-|:---:|:---:|:---:|:---:|:---:| :------: |
| BaSNet-I3D  | AAAI20 |Y|34.5 |22.5 |4.9  |22.2 | -   |     -    |
| WSBM        | ICCV19 |N|36.4 |19.2 | 2.9 |-    | -   |     -    |
| ASSG        | ACM 19 |N|32.3 |20.1 | 4.0 |-    | -   |     -    |
| TSM         | ICCV19 |N|30.0 |19.0 | 4.5 |-    | -   |     -    |
| CMCS        | CVPR19 |Y|34.0 |20.9 | 5.7 |21.2 | -   |     -    |
| STARNet     | AAAI19 |N|31.1 |18.8 | 4.7 |-    | -   |     -    |
| MAAN        | ICLR19 |Y|33.7 |21.9 | 5.5 |-    |-    |     -    |
| LTSR        | AAAI19 |N|33.1 |18.7 |3.32 |21.78|-    |     -    |
| STPN        | CVPR18 |I|29.3 |16.9 |2.6  |-    |-    |     -    |
| CPMN        | ACCV18 |N|39.29|24.09|6.71 |24.42|-    |     -    |
| S-O-C       | ACM18  |N|27.3 |14.7 |2.9  |15.6 |-    |     -    |



### Weakly Supervised Temporal Action Localization
* **EM-MIL**Zhekun Luo, Devin Guillory, Baifeng Shi, Wei Ke, Fang Wan, Trevor Darrell, Huijuan Xu.<br />
  "Weakly-Supervised Action Localization with Expectation-Maximization Multi-Instance Learning" ECCV 2020.
  [[paper](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740715.pdf)]
* **A2CL-PT:** Kyle Min, Jason J. Corso.<br />
  "Adversarial Background-Aware Loss for Weakly-supervised Temporal Activity Localization." ECCV 2020. 
  [[paper](https://arxiv.org/pdf/2007.06643.pdf)]
  [[code](https://github.com/MichiganCOG/A2CL-PT)]
* **ACL:** Guoqiang Gong, Xinghan Wang, Yadong Mu, Qi Tian.<br />
  "Learning Temporal Co-Attention Models for Unsupervised Video Action Localization." CVPR 2020, oral. 
  [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Gong_Learning_Temporal_Co-Attention_Models_for_Unsupervised_Video_Action_Localization_CVPR_2020_paper.pdf)]
* **WSTAL**Ashraful Islam, Richard J. Radke.<br />
  "Weakly Supervised Temporal Action Localization Using Deep Metric Learning" WACV 2020.
  [[paper](https://arxiv.org/pdf/2001.07793.pdf)]
  [[code](https://github.com/asrafulashiq/wsad)]
* **ActoinBytes:** Mihir Jain1, Amir Ghodrati, Cees G. M. Snoek.<br />
  "ActionBytes: Learning from Trimmed Videos to Localize Actions." CVPR 2020. 
  [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Jain_ActionBytes_Learning_From_Trimmed_Videos_to_Localize_Actions_CVPR_2020_paper.pdf)]
* **DGAM:** Baifeng Shi, Qi Dai, Yadong Mu, Jingdong Wang.<br />
  "Weakly-Supervised Action Localization by Generative Attention Modeling." CVPR 2020. 
  [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Shi_Weakly-Supervised_Action_Localization_by_Generative_Attention_Modeling_CVPR_2020_paper.pdf)]
  [[code](https://github.com/bfshi/DGAM-Weakly-Supervised-Action-Localization)]
* **BaSNet:** Pilhyeon Lee, Youngjung Uh, Hyeran Byun.<br />
  "Background Suppression Networks for Weakly-supervised Temporal Action Localization." AAAI 2020. 
  [[paper](https://arxiv.org/pdf/1911.09963.pdf)]
  [[code](https://github.com/Pilhyeon/BaSNet-pytorch)]
* **3C-Net:** Sanath Narayan, Hisham Cholakkal, Fahad Shabaz Khan, Ling Shao.<br />
  "3C-Net : Category Count and Center Loss for Weakly-Supervised Action Localization." ICCV 2019. 
  [[paper](https://arxiv.org/pdf/1908.08216.pdf)]
  [[code](https://github.com/naraysa/3c-net)]
* **CMCS:** Daochang Liu, Tingting Jiang, Yizhou Wang.<br />
  "Completeness Modeling and Context Separation for Weakly Supervised Temporal Action Localization." CVPR 2019. 
  [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Completeness_Modeling_and_Context_Separation_for_Weakly_Supervised_Temporal_Action_CVPR_2019_paper.pdf)]
  [[code](https://github.com/Finspire13/CMCS-Temporal-Action-Localization)]
* **ASSG:** Chengwei Zhang, Yunlu Xu, Zhanzhan Cheng, Yi Niu, Shiliang, Pu Fei Wu, Futai Zou.<br />
  "Adversarial Seeded Sequence Growing for Weakly-Supervised Temporal Action Localization" ACM MM 2019. 
  [[paper](https://arxiv.org/pdf/1908.02422.pdf)]
* **AutoLoc:**Zheng Shou, Hang Gao, Lei Zhang, KazuyukiMiyazawa, Shih-Fu Chang.<br />
  "AutoLoc Weakly-supervised Temporal Action Localization in Untrimmed Videos"ECCV 2018.
  [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zheng_Shou_AutoLoc_Weakly-supervised_Temporal_ECCV_2018_paper.pdf)]
  [[code](https://github.com/zhengshou/AutoLoc)]
* **CPMN:**Haisheng Su, Xu Zhao, Tianwei Lin.<br />
  "Cascaded Pyramid Mining Network for Weakly Supervised Temporal Action Localization"ACCV 2018.
  [[paper](https://arxiv.org/pdf/1810.11794.pdf)]
* **H&S:**Krishna Kumar Singh, Yong Jae Lee.<br />
  "Hide-and-Seek: Forcing a Network to be Meticulous for Weakly-supervised Object and Action Localization"ICCV 2017.
  [[paper](https://arxiv.org/pdf/1704.04232.pdf)]
  [[code](https://github.com/goddoe/hide-and-seek)]
* **LTSR:**Xiao-Yu Zhang, Haichao Shi, Changsheng Li, Kai Zheng, Xiaobin Zhu, Lixin Duan.<br />
  "Learning Transferable Self-Attentive Representations for Action Recognition in Untrimmed Videos with Weak Supervision"AAAI 2019.
  [[paper](https://www.aaai.org/ojs/index.php/AAAI/article/download/4958/4831)]
* **WSGN:**Basura Fernando, Cheston Tan Yin Chet.<br />
  "Weakly Supervised Gaussian Networks for Action Detection" WACV(2020)
* **MAAN:**Yuan Yuan, Yueming Lyu, Xi Shen, Ivor W. Tsang, Dit-Yan Yeung.<br />
  "MARGINALIZED AVERAGE ATTENTIONAL NETWORK FOR WEAKLY-SUPERVISED LEARNING"ICLR 2019.
  [[paper](https://arxiv.org/pdf/1905.08586.pdf)]
  [[code](https://github.com/yyuanad/MAAN)]
* **S-O-C:**Jia-Xing Zhong, Nannan Li, Weijie Kong, Tao Zhang, Thomas H. Li, Ge Li.<br />
  " Step-by-step Erasion, One-by-one Collection: A Weakly Supervised Temporal Action Detector"ACM MM 2018.
  [[paper](https://arxiv.org/pdf/1807.02929.pdf)]
* **STARNet:**Yunlu Xu, Chengwei Zhang, Zhanzhan Cheng, Jianwen Xie, Yi Niu, Shiliang Pu, Fei Wu.<br />
  "Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection"AAAI 2019.
  [[paper](https://www.aaai.org/ojs/index.php/AAAI/article/download/4939/4812)]
* **TSM:**Tan Yu, Zhou Ren, Yuncheng Li, Enxu Yan, Ning Xu, Junsong Yuan.<br />
  "Temporal Structure Mining for Weakly Supervised Action Detection"ICCV(2019).
  [[paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Temporal_Structure_Mining_for_Weakly_Supervised_Action_Detection_ICCV_2019_paper.pdf)]
* **UntrimmedNets:**Limin Wang, Yuanjun Xiong, Dahua Lin, Luc Van Gool.<br />
  "UntrimmedNets for Weakly Supervised Action Recognition and Detection"CVPR 2017.
  [[paper](https://wanglimin.github.io/papers/WangXLV_CVPR17.pdf)]
  [[code](https://github.com/wanglimin/UntrimmedNet)]
* **WSBM:**Phuc Xuan Nguyen, Deva Ramanan, Charless C. Fowlkes.<br />
  "Weakly-supervised Action Localization with Background Modeling"ICCV 2019.
  [[paper](https://arxiv.org/pdf/1908.06552.pdf)]
* **CleanNet:**Ziyi Liu, Le Wang1∗ Qilin Zhang, Zhanning Gao, Zhenxing Niu, Nanning Zheng, Gang Hua.<br />
  "Weakly Supervised Temporal Action Localization through Contrast based Evaluation Networks"ICCV 2019.
  [[paper](https://qilin-zhang.github.io/_pages/pdfs/Weakly_Supervised_Temporal_Action_Localization_through_Contrast_based_Evaluation_Networks.pdf)]
* **STPN**Phuc Nguyen, Ting Liu, Gautam Prasad, Bohyung Han.<br />
  "Weakly Supervised Action Localization by Sparse Temporal Pooling Network" CVPR 2018.
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Nguyen_Weakly_Supervised_Action_CVPR_2018_paper.pdf)]
  [[code](https://github.com/bellos1203/STPN)]
* **W-TALC**Sujoy Paul, Sourya Roy, Amit K Roy-Chowdhury.<br />
  "W-TALC: Weakly-supervised Temporal Activity Localization and Classification" ECCV 2018.
  [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Sujoy_Paul_W-TALC_Weakly-supervised_Temporal_ECCV_2018_paper.pdf)]
  [[code](https://github.com/sujoyp/wtalc-pytorch)]
* **LPAT**Xudong, Lin Zheng, Shou Shih-Fu Chang.<br />
  "LPAT: Learning to Predict Adaptive Threshold for Weakly-supervised Temporal Action Localization" arXiv 2019.
  [[paper](https://arxiv.org/pdf/1910.11285.pdf)]
* **RefineLoc:**Humam Alwassel1, Alejandro Pardo1, Fabian Caba Heilbron,  Ali Thabet1 Bernard Ghanem1.<br />
  "RefineLoc: Iterative Refinement for Weakly-Supervised Action Localization"Arxiv(2019)
  [[paper](https://arxiv.org/pdf/1904.00227.pdf)]
  [[paper](https://basurafernando.github.io/papers/wacv2020_wsgn.pdf)]


### Expecting for paper
* **lvr:** Xingyu Liu, Joon-Young Lee, Hailin Jin.<br />
  "Learning Video Representations from Correspondence Proposals." CVPR 2019 **oral**.


## Dataset
* **THUMOS'14:** Yu-Gang Jiang, Jingen Liu, Amir R. Zamir, George Toderici.<br />
  "THUMOS Challenge 2014" 
  [[project](https://www.crcv.ucf.edu/THUMOS14/home.html)]

* **Activity:** Bernard Ghanem, Juan Carlos Niebles, Cees Snoek, Fabian Caba Heilbron, Humam Alwassel, Victor Escorcia.<br />
  "A Large-Scale Video Benchmark for Human Activity Understanding" 
  [[project](http://activity-net.org/index.html)]
  
* **THUMOS'15:** Alexander Gorban, Haroon Idrees, Yu-Gang Jiang, Amir R. Zamir.<br />
  "THUMOS Challenge 2015" 
  [[project](http://www.thumos.info/)]

* **COIN:** Yansong Tang, Dajun Ding, Yongming Rao, Yu Zheng, Danyang Zhang, Lili Zhao, Jiwen Lu, Jie Zhou.<br />
  "COIN: A Large-scale Dataset for Comprehensive Instructional Video Analysis." CVPR 2019. 
  [[paper](https://arxiv.org/pdf/1903.02874.pdf)]
  [[project](https://coin-dataset.github.io/)]

