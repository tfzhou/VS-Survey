## 2. Deep Learning-based Video Object Segmentation

### 2.1 Automatic Video Object Segmentation (AVOS)

#### 2.1.1 Deep Learning Module based

| Year | Publication | Paper Title                                                                                                                                                                                     |                                                               Project                                                               |
|------|:-----------:|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------:|
| 2015 |    CVPR     | [Learning to segment moving objects in videos](https://www.cs.cmu.edu/~katef/papers/CVPR2015_LearnVideoSegment.pdf)                                                                             |                                                                 --                                                                  |
| 2016 |    CVPR     | [Video segmentation via object flow](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Tsai_Video_Segmentation_via_CVPR_2016_paper.pdf)                                         | [Code](https://github.com/wasidennis/ObjectFlow), [Project](https://sites.google.com/site/yihsuantsai/research/cvpr16-segmentation) |
| 2017 |    CVPR     | [Learning motion patterns in videos](https://openaccess.thecvf.com/content_cvpr_2017/papers/Tokmakov_Learning_Motion_Patterns_CVPR_2017_paper.pdf)                                              |                                        [Project](http://thoth.inrialpes.fr/research/mpnet/)                                         |
| 2017 |    ICCV     | [Primary video object segmentation via complementary cnns and neighborhood reversible flow](https://openaccess.thecvf.com/content_ICCV_2017/papers/Li_Primary_Video_Object_ICCV_2017_paper.pdf) |                                                                 --                                                                  |
| 2018 |     TIP     | [Video salient object detection via fully convolutional networks](https://arxiv.org/pdf/1702.00871.pdf)                                                                                                                             |                                                              [Code](https://github.com/wenguanwang/ViSalientObject)                                                               |

#### 2.1.2 Pixel Instance Embedding based

| Year | Publication | Paper Title                                                  | Project |
| ---- |:-----------:| ------------------------------------------------------------ |:-------:|
| 2017 |    arXiv    | [Semantic instance segmentation via deep metric learning](https://arxiv.org/pdf/1703.10277.pdf) |   --    |
| 2018 |    CVPR     | [Instance embedding transfer to unsupervised video object segmentation](https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Instance_Embedding_Transfer_CVPR_2018_paper.pdf) |   --    |
| 2018 |    ECCV     | [video object segmentation with motion-based bilateral networks](https://openaccess.thecvf.com/content_ECCV_2018/papers/Siyang_Li_Unsupervised_Video_Object_ECCV_2018_paper.pdf) |   --    |

#### 2.1.3 Short-term Information Encoding

| Year | Publication | Paper Title                                                  |                           Project                            |
| ---- | :---------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| 2017 |    CVPR     | [Fusionseg: Learning to combine motion and appearance for fully automatic segmention of generic objects in videos](https://openaccess.thecvf.com/content_cvpr_2017/papers/Jain_FusionSeg_Learning_to_CVPR_2017_paper.pdf) | [Code](https://github.com/suyogduttjain/fusionseg), [Project](https://vision.cs.utexas.edu/projects/fusionseg/) |
| 2017 |    ICCV     | [Segflow: Joint learning for video object segmentation and optical flow](https://openaccess.thecvf.com/content_ICCV_2017/papers/Cheng_SegFlow_Joint_Learning_ICCV_2017_paper.pdf) | [Code](https://github.com/JingchunCheng/SegFlow), [Project](https://sites.google.com/site/yihsuantsai/research/iccv17-segflow) |
| 2017 |    ICCV     | [Learning video object segmentation with visual memory](http://openaccess.thecvf.com/content_ICCV_2017/papers/Tokmakov_Learning_Video_Object_ICCV_2017_paper.pdf) |                              --                              |
| 2018 |    ECCV     | [Pyramid dilated deeper convlstm for video salient object detection](https://openaccess.thecvf.com/content_ECCV_2018/papers/Hongmei_Song_Pseudo_Pyramid_Deeper_ECCV_2018_paper.pdf) |     [Code](https://github.com/shenjianbing/PDB-ConvLSTM)     |
| 2018 |    CVPR     | [Flow guided recurrent neural encoder for video salient object detection](https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Flow_Guided_Recurrent_CVPR_2018_paper.pdf) |                              --                              |
| 2019 |    ICCV     | [Zero-shot video object segmentation via attentive graph neural networks](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Zero-Shot_Video_Object_Segmentation_via_Attentive_Graph_Neural_Networks_ICCV_2019_paper.pdf) |          [Code](https://github.com/carrierlxk/AGNN)          |
| 2019 |    ICCV     | [Motion guided attention for video salient object detection](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Motion_Guided_Attention_for_Video_Salient_Object_Detection_ICCV_2019_paper.pdf) |   [Code](https://github.com/lhaof/Motion-Guided-Attention)   |
| 2019 |    IJCV     | [Learning to segment moving objects](https://arxiv.org/pdf/1712.01127.pdf) |                              --                              |
| 2020 |    AAAI     | [Motion attentive transition for zero-shot video object segmentation](https://ojs.aaai.org/index.php/AAAI/article/download/7008/6862) |           [Code](https://github.com/tfzhou/MATNet)           |

#### 2.1.4 Long-term Context Encoding

| Year | Publication | Paper Title                                                  |                                                            Project                                                             |
| ---- | :---------: | ------------------------------------------------------------ |:------------------------------------------------------------------------------------------------------------------------------:|
| 2019 |    CVPR     | [See more, know more: Unsupervised video object segmentation with co-attention siamese networks](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lu_See_More_Know_More_Unsupervised_Video_Object_Segmentation_With_Co-Attention_CVPR_2019_paper.pdf) |        [Code](https://github.com/carrierlxk/COSNet)  |
| 2019 |    ICCV     | [Anchor diffusion for unsupervised video object segmentation](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yang_Anchor_Diffusion_for_Unsupervised_Video_Object_Segmentation_ICCV_2019_paper.pdf) | [Code](https://github.com/yz93/anchor-diff-VOS)|
| 2019 |    ICCV     | [Zero-shot video object segmentation via attentive graph neural networks](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Zero-Shot_Video_Object_Segmentation_via_Attentive_Graph_Neural_Networks_ICCV_2019_paper.pdf)| [Code](https://github.com/carrierlxk/AGNN)|
| 2020 |    AAAI     | [Pyramid constrained network for fast video salient object detection](https://ojs.aaai.org/index.php/AAAI/article/view/6718)|[Code](https://github.com/guyuchao/PyramidCSA)|
| 2020 |    ECCV     | [Unsupervised video object segmentation with joint hotspot tracking](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590477.pdf) |    [Code](https://github.com/luzhangada/code-for-WCS-Net)                                                                                                           |
| 2020 |    ECCV     | [Learning discriminative feature with crf for unsupervised video object segmentation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720443.pdf)|--|
| 2020 |    TPAMI    | [Zero-Shot Video Object Segmentation with Co-Attention Siamese Networks](https://ieeexplore.ieee.org/abstract/document/9268466/) | [Code](https://github.com/carrierlxk/COSNet)|
| 2021 |    AAAI     | [F2net: Learning to focus on the foreground for unsupervised video object segmentation](https://ojs.aaai.org/index.php/AAAI/article/view/16308)| --|
| 2021 |    CVPR     | [Reciprocal transformations for unsupervised video object segmentation](https://openaccess.thecvf.com/content/CVPR2021/papers/Ren_Reciprocal_Transformations_for_Unsupervised_Video_Object_Segmentation_CVPR_2021_paper.pdf)| [Code](https://github.com/OliverRensu/RTNet)|
| 2021 |    TPAMI    | [Segmenting objects from relational visual data](https://ieeexplore.ieee.org/document/9551804/) | [Code](https://github.com/carrierlxk/AGNN) |

#### 2.1.5 Un-/Weakly-supervised based
| Year | Publication | Paper Title                                                  |                                                            Project                                                             |
| ---- | :---------: | ------------------------------------------------------------ |:------------------------------------------------------------------------------------------------------------------------------:|
| 2019 |    CVPR     | [Learning unsupervised video object segmentation through visual attention](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Unsupervised_Video_Object_Segmentation_Through_Visual_Attention_CVPR_2019_paper.pdf) |        [Code](https://github.com/wenguanwang/AGS)  |
| 2019 |    CVPR     | [Unsupervised moving object detection via contextual information separation](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yang_Unsupervised_Moving_Object_Detection_via_Contextual_Information_Separation_CVPR_2019_paper.pdf) | [Code](https://github.com/antonilo/unsupervised_detection), [Project](http://rpg.ifi.uzh.ch/unsupervised_detection.html)|
| 2020 |    CVPR     | [Learning video object segmentation from unlabeled videos](http://openaccess.thecvf.com/content_CVPR_2020/papers/Lu_Learning_Video_Object_Segmentation_From_Unlabeled_Videos_CVPR_2020_paper.pdf)| [Code](https://github.com/carrierlxk/MuG) |
| 2021 |    CVPR     | [Dystab: Unsupervised object segmentation via dynamic-static bootstrapping](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_DyStaB_Unsupervised_Object_Segmentation_via_Dynamic-Static_Bootstrapping_CVPR_2021_paper.pdf)|[Code](https://github.com/blai88/dystab)|

#### 2.1.6 Instance-level AVOS
| Year | Publication | Paper Title                                                  |                                                            Project                                                             |
| ---- | :---------: | ------------------------------------------------------------ |:------------------------------------------------------------------------------------------------------------------------------:|
| 2019 |    CVPR     | [See more, know more: Unsupervised video object segmentation with co-attention siamese networks](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lu_See_More_Know_More_Unsupervised_Video_Object_Segmentation_With_Co-Attention_CVPR_2019_paper.pdf) |        [Code](https://github.com/carrierlxk/COSNet)  |
| 2019 |    CVPR     | [Rvos: End-to-end recurrent network for video object segmentation](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ventura_RVOS_End-To-End_Recurrent_Network_for_Video_Object_Segmentation_CVPR_2019_paper.pdf) |        [Code](https://github.com/imatge-upc/rvos)，[Project](https://imatge-upc.github.io/rvos/)  |
| 2019 |    ICCV     | [Zero-shot video object segmentation via attentive graph neural networks](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Zero-Shot_Video_Object_Segmentation_via_Attentive_Graph_Neural_Networks_ICCV_2019_paper.pdf) |                                           [Code](https://github.com/carrierlxk/AGNN)                                           |
| 2020 |    TPAMI    | [Zero-Shot Video Object Segmentation with Co-Attention Siamese Networks](https://ieeexplore.ieee.org/abstract/document/9268466/) | [Code](https://github.com/carrierlxk/COSNet)|
| 2020 |    WACV     | [Unovost: Unsupervised offline video object segmentation and tracking](https://openaccess.thecvf.com/content_WACV_2020/papers/Luiten_UnOVOST_Unsupervised_Offline_Video_Object_Segmentation_and_Tracking_WACV_2020_paper.pdf)| --|
| 2021 |    CVPR     | [Target-aware object discovery and association for unsupervised video multi-object segmentation](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhou_Target-Aware_Object_Discovery_and_Association_for_Unsupervised_Video_Multi-Object_Segmentation_CVPR_2021_paper.pdf)|--|
| 2021 |    TPAMI    | [Paying attention to video object pattern understanding](https://ieeexplore.ieee.org/document/8957473)|[Code](https://github.com/wenguanwang/AGS)|

### 2.2 Semi-automatic Video Object Segmentation (SVOS)

#### 2.2.1 Online Fine-tuning based 
| Year | Publication | Paper Title                                                  |                        Project                        |
| ---- | :---------: | ------------------------------------------------------------ | :---------------------------------------------------: |
| 2017 |    CVPR     | [One-shot video object segmentation](https://arxiv.org/pdf/1611.05198.pdf) |   [Code](https://github.com/kmaninis/OSVOS-PyTorch)   |
| 2017 |    BMVC     | [Online adaptation of convolutional neural networks for video object segmentation](https://arxiv.org/pdf/1706.09364.pdf) |     [Code](https://github.com/Stocastico/OnAVOS)      |
| 2018 |    CVPR     | [Monet: Deep motion exploitation for video object segmentation](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xiao_MoNet_Deep_Motion_CVPR_2018_paper.pdf) |                          --                           |
| 2018 |    CVPR     | [Efficient video object segmentation via network modulation](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_Efficient_Video_Object_CVPR_2018_paper.pdf) |   [Code](https://github.com/linjieyangsc/video_seg)   |
| 2018 |    TPAMI    | [Video object segmentation without temporal information](https://arxiv.org/pdf/1709.06031.pdf) | [Project](https://cvlsegmentation.github.io/osvos-s/) |
| 2019 |    TPAMI    | [Online meta adaptation for fast video object segmentation](https://ieeexplore.ieee.org/document/8611188) |     [Code](https://github.com/huaxinxiao/MVOS-OL)     |
| 2020 |   NeurIPS   | [Make one-shot video object segmentation efficient again](https://proceedings.neurips.cc//paper/2020/file/781397bc0630d47ab531ea850bddcf63-Paper.pdf) |      [Code](https://github.com/dvl-tum/e-osvos)       |

#### 2.2.2 Propagation-based 
| Year | Publication | Paper Title                                                  |                           Project                            |
| ---- | :---------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| 2017 |    CVPR     | [Learning video object segmentation from static images](https://openaccess.thecvf.com/content_cvpr_2017/papers/Perazzi_Learning_Video_Object_CVPR_2017_paper.pdf) |                              --                              |
| 2017 |    CVPR     | [Online video object segmentation via convolutional trident network](https://openaccess.thecvf.com/content_cvpr_2017/papers/Jang_Online_Video_Object_CVPR_2017_paper.pdf) |                              --                              |
| 2017 |    CVPR     | [Video propagation networks](https://openaccess.thecvf.com/content_cvpr_2017/papers/Jampani_Video_Propagation_Networks_CVPR_2017_paper.pdf) | [Code](https://github.com/varunjampani/video_prop_networks)  |
| 2018 |    CVPR     | [Motion-guided cascaded refinement network for video object segmentation](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0391.pdf) |                              --                              |
| 2018 |    CVPR     | [Reinforcement cutting-agent learning for video object segmentation](https://openaccess.thecvf.com/content_cvpr_2018/papers/Han_Reinforcement_Cutting-Agent_Learning_CVPR_2018_paper.pdf) |                              --                              |
| 2018 |    CVPR     | [CNN in MRF: Video object segmentation via inference in a CNN-based higher-order spatio-temporal MRF](https://openaccess.thecvf.com/content_cvpr_2018/papers/Bao_CNN_in_MRF_CVPR_2018_paper.pdf) |                              --                              |
| 2018 |    CVPR     | [Fast and accurate online video object segmentation via tracking parts](https://arxiv.org/pdf/1806.02323.pdf) |        [Code](https://github.com/JingchunCheng/FAVOS)        |
| 2018 |    CVPR     | [Fast video object segmentation by reference-guided mask propagation](https://openaccess.thecvf.com/content_cvpr_2018/papers/Oh_Fast_Video_Object_CVPR_2018_paper.pdf) |                              --                              |
| 2018 |    ECCV     | [Video object segmentation with joint reidentification and attention-aware mask propagation](https://openaccess.thecvf.com/content_ECCV_2018/papers/Xiaoxiao_Li_Video_Object_Segmentation_ECCV_2018_paper.pdf) |   [Project](http://mmlab.ie.cuhk.edu.hk/projects/DyeNet/)    |
| 2018 |    ECCV     | [Video object segmentation by learning location-sensitive embeddings](https://openaccess.thecvf.com/content_ECCV_2018/papers/Hai_Ci_Video_Object_Segmentation_ECCV_2018_paper.pdf) |                              --                              |
| 2018 |    arXiv    | [Youtube-vos: A large-scale video object segmentation benchmark](https://arxiv.org/pdf/1809.03327.pdf) |             [Project](https://youtube-vos.org/)              |
| 2019 |    IJCV     | [Lucid data dreaming for video object segmentation](https://arxiv.org/pdf/1703.09554.pdf) | [Code](https://github.com/ankhoreva/LucidDataDreaming), [Project](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/weakly-supervised-learning/lucid-data-dreaming-for-object-tracking) |
| 2019 |    CVPR     | [Mhp-vos: Multiple hypotheses propagation for video object segmentation](https://arxiv.org/pdf/1904.08141.pdf) |        [Code](https://github.com/shuangjiexu/MHP-VOS)        |
| 2019 |    CVPR     | [A generative appearance model for end-to-end video object segmentation](https://openaccess.thecvf.com/content_CVPR_2019/papers/Johnander_A_Generative_Appearance_Model_for_End-To-End_Video_Object_Segmentation_CVPR_2019_paper.pdf) |     [Code](https://github.com/joakimjohnander/agame-vos)     |
| 2019 |    ICCV     | [Fast video object segmentation via dynamic targeting network](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Fast_Video_Object_Segmentation_via_Dynamic_Targeting_Network_ICCV_2019_paper.pdf) |                              --                              |
| 2019 |    ICCV     | [Agss-vos: Attention guided single-shot video object segmentation](https://openaccess.thecvf.com/content_ICCV_2019/papers/Lin_AGSS-VOS_Attention_Guided_Single-Shot_Video_Object_Segmentation_ICCV_2019_paper.pdf) |      [Code](https://github.com/dvlab-research/AGSS-VOS)      |
| 2020 |    CVPR     | [State-aware tracker for real-time video object segmentation](https://arxiv.org/pdf/2003.00482.pdf) |   [Code](https://github.com/MegviiDetection/video_analyst)   |
| 2020 |    CVPR     | [Fast video object segmentation with temporal aggregation network and dynamic template matching](https://openaccess.thecvf.com/content_CVPR_2020/papers/Huang_Fast_Video_Object_Segmentation_With_Temporal_Aggregation_Network_and_Dynamic_CVPR_2020_paper.pdf) |  [Project](https://xuhuaking.github.io/Fast-VOS-DTTM-TAN/)   |
| 2022 |    AAAI     | [Reliable Propagation-Correction Modulation for Video Object Segmentation](https://arxiv.org/pdf/2112.02853.pdf) |  [Code](https://github.com/JerryX1110/RPCMVOS)   |

#### 2.2.3 Matching-based 
| Year | Publication | Paper Title                                                  |                           Project                            |
| ---- | :---------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| 2015 |    ICCV     | [Visual tracking with fully convolutional networks](https://wlouyang.github.io/Papers/Wang_Visual_Tracking_With_ICCV_2015_paper.pdf) |                              --                              |
| 2017 |    ICCV     | [Pixel-level matching for video object segmentation using convolutional neural networks](https://openaccess.thecvf.com/content_ICCV_2017/papers/Yoon_Pixel-Level_Matching_for_ICCV_2017_paper.pdf) |                              --                              |
| 2017 |    CVPR     | [Learning video object segmentation from static images](https://openaccess.thecvf.com/content_cvpr_2017/papers/Perazzi_Learning_Video_Object_CVPR_2017_paper.pdf) |                              --                              |
| 2018 |    CVPR     | [Fast and accurate online video object segmentation via tracking parts](https://arxiv.org/pdf/1806.02323.pdf) |        [Code](https://github.com/JingchunCheng/FAVOS)        |
| 2018 |    CVPR     | [CNN in MRF: Video object segmentation via inference in a CNN-based higher-order spatio-temporal MRF](https://openaccess.thecvf.com/content_cvpr_2018/papers/Bao_CNN_in_MRF_CVPR_2018_paper.pdf) |                              --                              |
| 2018 |    CVPR     | [Motion-guided cascaded refinement network for video object segmentation](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0391.pdf) |                              --                              |
| 2018 |    ECCV     | [Video object segmentation with joint reidentification and attention-aware mask propagation](https://openaccess.thecvf.com/content_ECCV_2018/papers/Xiaoxiao_Li_Video_Object_Segmentation_ECCV_2018_paper.pdf) |   [Project](http://mmlab.ie.cuhk.edu.hk/projects/DyeNet/)    |
| 2018 |    ECCV     | [Videomatch: Matching based video object segmentation](https://arxiv.org/pdf/1809.01123.pdf) |                              --                              |
| 2018 |    arXiv    | [Youtube-vos: A large-scale video object segmentation benchmark](https://arxiv.org/pdf/1809.03327.pdf) |             [Project](https://youtube-vos.org/)              |
| 2019 |    CVPR     | [Feelvos: Fast end-to-end embedding learning for video object segmentation](https://arxiv.org/pdf/1902.09513.pdf) |                              --                              |
| 2019 |    CVPR     | [Mhp-vos: Multiple hypotheses propagation for video object segmentation](https://arxiv.org/pdf/1904.08141.pdf) |        [Code](https://github.com/shuangjiexu/MHP-VOS)        |
| 2019 |    ICCV     | [Ranet: Ranking attention network for fast video object segmentation](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_RANet_Ranking_Attention_Network_for_Fast_Video_Object_Segmentation_ICCV_2019_paper.pdf) |           [Code](https://github.com/Storife/RANet)           |
| 2019 |    ICCV     | [Video object segmentation using space-time memory networks](https://openaccess.thecvf.com/content_ICCV_2019/papers/Oh_Video_Object_Segmentation_Using_Space-Time_Memory_Networks_ICCV_2019_paper.pdf) |                              --                              |
| 2019 |    ICCV     | [Capsulevos: Semisupervised video object segmentation using capsule routing](https://openaccess.thecvf.com/content_ICCV_2019/papers/Duarte_CapsuleVOS_Semi-Supervised_Video_Object_Segmentation_Using_Capsule_Routing_ICCV_2019_paper.pdf) |      [Code](https://github.com/KevinDuarte/CapsuleVOS)       |
| 2020 |    CVPR     | [A transductive approach for video object segmentation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_A_Transductive_Approach_for_Video_Object_Segmentation_CVPR_2020_paper.pdf) | [Code](https://github.com/microsoft/transductive-vos.pytorch) |
| 2020 |    CVPR     | [Learning fast and robust target models for video object segmentation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Robinson_Learning_Fast_and_Robust_Target_Models_for_Video_Object_Segmentation_CVPR_2020_paper.pdf) |         [Code](https://github.com/andr345/frtm-vos)          |
| 2020 |    ECCV     | [Collaborative video object segmentation by foreground-background integration](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500324.pdf) |           [Code](https://github.com/z-x-yang/CFBI)           |
| 2020 |    ECCV     | [Video object segmentation with episodic graph memory networks](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480664.pdf) |      [Code](https://github.com/carrierlxk/GraphMemVOS)       |
| 2020 |    ECCV     | [Learning what to learn for video object segmentation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470766.pdf) |        [Code](https://github.com/visionml/pytracking)        |
| 2020 |    ECCV     | [Kernelized memory network for video object segmentation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670630.pdf) |                              --                              |
| 2020 |    ECCV     | [Fast video object segmentation using the global context module](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123550732.pdf) |                              --                              |
| 2020 |    ECCV     | [Memory selection network for video propagation](https://jiaya.me/papers/video_prop_eccv20.pdf) |                              --                              |
| 2020 |   NeurIPS   | [Video object segmentation with adaptive feature bank and uncertain-region refinement](https://proceedings.neurips.cc/paper/2020/file/234833147b97bb6aed53a8f4f1c7a7d8-Paper.pdf) |        [Code](https://github.com/xmlyqing00/AFB-URR)         |
| 2021 |    CVPR     | [Learning position and target consistency for memory-based video object segmentation]() |                              --                              |
| 2021 |    CVPR     | [Efficient regional memory network for video object segmentation](https://arxiv.org/pdf/2103.12934.pdf) | [Code](https://github.com/hzxie/RMNet), [Project](https://infinitescript.com/project/rmnet/) |
| 2021 |    CVPR     | [Video object segmentation using global and instance embedding learning](https://openaccess.thecvf.com/content/CVPR2021/papers/Ge_Video_Object_Segmentation_Using_Global_and_Instance_Embedding_Learning_CVPR_2021_paper.pdf) |                              --                              |
| 2021 |    CVPR     | [Sstvos: Sparse spatiotemporal transformers for video object segmentation](https://openaccess.thecvf.com/content/CVPR2021/papers/Duke_SSTVOS_Sparse_Spatiotemporal_Transformers_for_Video_Object_Segmentation_CVPR_2021_paper.pdf) |           [Code](https://github.com/dukebw/SSTVOS)           |
| 2021 |    CVPR     | [Swiftnet: Realtime video object segmentation](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_SwiftNet_Real-Time_Video_Object_Segmentation_CVPR_2021_paper.pdf) |      [Code](https://github.com/haochenheheda/SwiftNet)       |

#### 2.2.4 Box-initialization based 
| Year | Publication | Paper Title                                                  |                                                            Project                                                             |
| ---- | :---------: | ------------------------------------------------------------ |:------------------------------------------------------------------------------------------------------------------------------:|
| 2019 |    CVPR     | [Fast online object tracking and segmentation: A unifying approach](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Fast_Online_Object_Tracking_and_Segmentation_A_Unifying_Approach_CVPR_2019_paper.pdf) |        [Code](https://github.com/foolwood/SiamMask), [Project](https://www.robots.ox.ac.uk/~qwang/SiamMask/)  |
| 2020 |    CVPR     | [Fast template matching and update for video object tracking and segmentation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Fast_Template_Matching_and_Update_for_Video_Object_Tracking_and_CVPR_2020_paper.pdf)| [Code](https://github.com/insomnia94/FTMU)|
| 2021 |    AAAI     | [Query-memory reaggregation for weakly-supervised video object segmentation](https://www.aaai.org/AAAI21Papers/AAAI-3972.LinF.pdf)| --|

#### 2.2.5  Un-/Weakly-supervised based
| Year | Publication | Paper Title                                                  |                                                            Project                                                             |
| ---- | :---------: | ------------------------------------------------------------ |:------------------------------------------------------------------------------------------------------------------------------:|
| 2018 |    ECCV     | [Tracking emerges by colorizing videos](https://openaccess.thecvf.com/content_ECCV_2018/papers/Carl_Vondrick_Self-supervised_Tracking_by_ECCV_2018_paper.pdf) |        -- |
| 2019 |    CVPR     | [Learning correspondence from the cycle-consistency of time](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Correspondence_From_the_Cycle-Consistency_of_Time_CVPR_2019_paper.pdf)|[Code](https://github.com/xiaolonw/TimeCycle), [Project](https://ajabri.github.io/timecycle/)|
| 2019 |    NeurIPS  | [Joint-task self-supervised learning for temporal correspondence](https://proceedings.neurips.cc/paper/2019/file/140f6969d5213fd0ece03148e62e461e-Paper.pdf)|[Code](https://github.com/Liusifei/UVC), [Project](https://sites.google.com/view/uvc2019/)|
| 2020 |    CVPR     | [Mast: A memory-augmented selfsupervised tracker](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lai_MAST_A_Memory-Augmented_Self-Supervised_Tracker_CVPR_2020_paper.pdf)|[Code](https://github.com/zlai0/MAST)|
| 2020 |    CVPR     | [Learning video object segmentation from unlabeled videos](http://openaccess.thecvf.com/content_CVPR_2020/papers/Lu_Learning_Video_Object_Segmentation_From_Unlabeled_Videos_CVPR_2020_paper.pdf)| [Code](https://github.com/carrierlxk/MuG) |
| 2020 |    NeurIPS  | [Space-time correspondence as a contrastive random walk](https://arxiv.org/pdf/2006.14613) |[Code](https://github.com/ajabri/videowalk), [Project](https://ajabri.github.io/videowalk/)|

#### 2.2.6 Other Specific Methods
| Year | Publication | Paper Title                                                  |                                                            Project                                                             |
| ---- | :---------: | ------------------------------------------------------------ |:------------------------------------------------------------------------------------------------------------------------------:|
| 2019 |    ICCV     | [Dmm-net: Differentiable mask-matching network for video object segmentation](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zeng_DMM-Net_Differentiable_Mask-Matching_Network_for_Video_Object_Segmentation_ICCV_2019_paper.pdf) |        [Code](https://github.com/ZENGXH/DMM_Net) |
| 2019 |    CVPR     | [Bubblenets: Learning to select the guidance frame in video object segmentation by deep sorting frames](https://openaccess.thecvf.com/content_CVPR_2019/papers/Griffin_BubbleNets_Learning_to_Select_the_Guidance_Frame_in_Video_Object_CVPR_2019_paper.pdf)|[Code](https://github.com/griffbr/BubbleNets)|
| 2020 |    NeurIPS  | [Delving into the cyclic mechanism in semi-supervised video object segmentation](https://proceedings.neurips.cc/paper/2020/file/0d5bd023a3ee11c7abca5b42a93c4866-Paper.pdf) | --|
| 2021 |    CVPR     | [Learning dynamic network using a reuse gate function in semi-supervised video object segmentation](https://openaccess.thecvf.com/content/CVPR2021/papers/Park_Learning_Dynamic_Network_Using_a_Reuse_Gate_Function_in_Semi-Supervised_CVPR_2021_paper.pdf)| [Code](https://github.com/HYOJINPARK/Reuse_VOS)|

### 2.3 Interactive Video Object Segmentation (IVOS)

#### 2.3.1 Interaction-propagation based 

| Year | Publication | Paper Title                                                  |                           Project                            |
| ---- | :---------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| 2016 |    CVPR     | [Deep interactive object selection](https://openaccess.thecvf.com/content_cvpr_2016/papers/Xu_Deep_Interactive_Object_CVPR_2016_paper.pdf) |                              --                              |
| 2017 |    CVPR     | [One-shot video object segmentation](https://arxiv.org/pdf/1611.05198.pdf) |      [Code](https://github.com/kmaninis/OSVOS-PyTorch)       |
| 2017 |    arXiv    | [Interactive video object segmentation in the wild](https://arxiv.org/pdf/1801.00269.pdf) |                              --                              |
| 2019 |    CVPR     | [Fast user-guided video object segmentation by interaction-and-propagation networks](https://arxiv.org/pdf/1904.09791.pdf) |                              --                              |
| 2020 |    CVPR     | [Memory aggregation networks for efficient interactive video object segmentation](https://arxiv.org/pdf/2003.13246.pdf) |      [Code](https://github.com/lightas/CVPR2020_MANet)       |
| 2020 |    ECCV     | [Interactive video object segmentation using global and local transfer modules](https://arxiv.org/pdf/2007.08139.pdf) | [Code](https://github.com/yuk6heo/IVOS-ATNet), [Project](http://mcl.korea.ac.kr/yukheo_eccv2020/) |
| 2021 |    CVPR     | [Guided interactive video object segmentation using reliability-based attention maps](https://openaccess.thecvf.com/content/CVPR2021/papers/Heo_Guided_Interactive_Video_Object_Segmentation_Using_Reliability-Based_Attention_Maps_CVPR_2021_paper.pdf) |         [Code](https://github.com/yuk6heo/GIS-RAmap)         |
| 2021 |    CVPR     | [Modular interactive video object segmentation: Interaction-to-mask, propagation and difference-aware fusion](https://arxiv.org/pdf/2103.07941.pdf) | [Code](https://github.com/hkchengrex/MiVOS), [Project](https://hkchengrex.github.io/MiVOS/) |

#### 2.3.2 Other Methods

| Year | Publication | Paper Title                                                  |                           Project                           |
| ---- | :---------: | ------------------------------------------------------------ | :---------------------------------------------------------: |
| 2018 |    CVPR     | [Blazingly fast video object segmentation with pixel-wise metric learning](https://arxiv.org/pdf/1804.03131.pdf) |         [Code](https://github.com/yuhuayc/fast-vos)         |
| 2018 |    CVPR     | [Fast and accurate online video object segmentation via tracking parts](https://arxiv.org/pdf/1806.02323.pdf) |       [Code](https://github.com/JingchunCheng/FAVOS)        |
| 2020 |    ECCV     | [Scribblebox: Interactive annotation framework for video object segmentation](https://arxiv.org/pdf/2008.09721.pdf) | [Project](http://www.cs.toronto.edu/~linghuan/scribblebox/) |
| 2021 |    CVPR     | [Learning to recommend frame for interactive video object segmentation in the wild](https://arxiv.org/pdf/2103.10391.pdf) |         [Code](https://github.com/svip-lab/IVOS-W)          |

### 2.4 Language-guided Video Object Segmentation (LVOS)

#### 2.4.1 Dynamic Convolution-based 

| Year | Publication | Paper Title                                                  |                           Project                            |
| ---- | :---------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| 2017 |    CVPR     | [Tracking by natural language specification](https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Tracking_by_Natural_CVPR_2017_paper.pdf) |     [Project](https://github.com/QUVA-Lab/lang-tracker)      |
| 2018 |    CVPR     | [Actor and action video segmentation from a sentence](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gavrilyuk_Actor_and_Action_CVPR_2018_paper.pdf) | [Project](https://kgavrilyuk.github.io/publication/actor_action/) |
| 2019 |    ICCV     | [Asymmetric cross-guided attention network for actor and action video segmentation from natural language query](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Asymmetric_Cross-Guided_Attention_Network_for_Actor_and_Action_Video_Segmentation_ICCV_2019_paper.pdf) |                              --                              |
| 2020 |    AAAI     | [Context modulated dynamic networks for actor and action video segmentation with language queries](https://ojs.aaai.org/index.php/AAAI/article/view/6895/6749) |                              --                              |
| 2020 |    IJCAI    | [Polar relative positional encoding for video-language segmentation](https://www.ijcai.org/proceedings/2020/0132.pdf) |                              --                              |

#### 2.4.2 Capsule Routing-based 

| Year | Publication | Paper Title                                                  |                           Project                            |
| ---- | :---------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| 2018 |    ICLR     | [Matrix capsules with em routing](https://openreview.net/pdf?id=HJWLfGWRb) | [Code](https://github.com/IBM/matrix-capsules-with-em-routing) |
| 2020 |    CVPR     | [Visual-textual capsule routing for text-based video segmentation](https://openaccess.thecvf.com/content_CVPR_2020/papers/McIntosh_Visual-Textual_Capsule_Routing_for_Text-Based_Video_Segmentation_CVPR_2020_paper.pdf) |                              --                              |

#### 2.4.3 Attention-based 

| Year | Publication | Paper Title                                                  |                       Project                       |
| ---- | :---------: | ------------------------------------------------------------ | :-------------------------------------------------: |
| 2018 |    ACCV     | [Video object segmentation with language referring expressions](https://arxiv.org/pdf/1803.08006.pdf) |                         --                          |
| 2019 |    ICCV     | [Asymmetric cross-guided attention network for actor and action video segmentation from natural language query](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Asymmetric_Cross-Guided_Attention_Network_for_Actor_and_Action_Video_Segmentation_ICCV_2019_paper.pdf) |                         --                          |
| 2020 |    ECCV     | [Urvos: Unified referring video object segmentation network with a large-scale benchmark](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600205.pdf) | [Code](https://github.com/skynbe/Refer-Youtube-VOS) |
| 2021 |    CVPR     | [Collaborative spatial-temporal modeling for language-queried video actor segmentation](https://arxiv.org/pdf/2105.06818.pdf) |                         --                          |
| 2021 |    TPAMI    | [Referring segmentation in images and videos with cross-modal self-attention network](https://arxiv.org/pdf/2102.04762.pdf) |                         --                          |
| 2021 |    TPAMI    | [Cross-modal progressive comprehension for referring segmentation](https://ieeexplore.ieee.org/document/9430750) |  [Code](https://github.com/spyflying/CMPC-Refseg)   |

####  
