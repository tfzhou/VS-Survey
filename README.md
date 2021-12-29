# A Survey on Deep Learning Technique for Video Segmentation

> [A Survey on Deep Learning Technique for Video Segmentation](https://arxiv.org/abs/2107.01153) <br>
> [Wenguan Wang](https://sites.google.com/view/wenguanwang), [Tianfei Zhou](https://www.tfzhou.com/), [Fatih Porikli](http://www.porikli.com/), [David Crandall](https://homes.luddy.indiana.edu/djcran/), and [Luc Van Gool](https://scholar.google.com/citations?user=TwMib_QAAAAJ). <br>
> [![paper](https://img.shields.io/badge/Paper-arxiv-b31b1b)](https://arxiv.org/abs/2107.01153)

## 1. Introduction
Video segmentation, i.e., partitioning video frames into multiple segments or objects, plays a critical role in a broad range of practical applications, from enhancing visual effects in movie, to understanding scenes in autonomous driving, to virtual background creation in video conferencing. In this survey, we comprehensively review two basic lines of research — **video object segmentation** and **video semantic segmentation** — by introducing their respective task settings, background concepts, perceived need, development history, and main challenges. In particular, we review **eight** sub-fields as given in the following figure:

<p align="center">
  <img src="overview.png" width="500">
</p>


## 2. Deep Learning-based Video Object Segmentation

- [2.1 Automatic Video Object Segmentation (AVOS)](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#21-automatic-video-object-segmentation-avos)
  - [2.1.1 Deep Learning Module based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#211-deep-learning-module-based)
  - [2.1.2 Pixel Instance Embedding based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#212-pixel-instance-embedding-based)
  - [2.1.3 Short-term Information Encoding](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#213-short-term-information-encoding)
  - [2.1.4 Long-term Context Encoding](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#214-long-term-context-encoding)
  - [2.1.5 Un-/Weakly-supervised based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#215-un/weakly-supervised-based)
  - [2.1.6 Instance-level AVOS](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#216-instance-level-AVOS)
- [2.2 Semi-automatic Video Object Segmentation (SVOS)](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#22-semi-automatic-video-object-segmentation-svos)
  - [2.2.1 Online Fine-tuning based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#221-online-fine-tuning-based)
  - [2.2.2 Propagation based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#222-propagation-based)
  - [2.2.3 Matching based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#223-matching-based)
  - [2.2.4 Box-initialization based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#224-box-initialization-based)
  - [2.2.5  Un-/Weakly-supervised based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#225-un-/weakly-supervised-based)
  - [2.2.6  Other Specific Methods](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#226-other-specific-methods)
- [2.3 Interactive Video Object Segmentation (IVOS)](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#23-interactive-video-object-segmentation-ivos)
  - [2.3.1 Interaction-propagation based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#231-interaction-propagation-based)
  - [2.3.2 Other Methods](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#232-other-methods)
- [2.4 Language-guided Video Object Segmentation (LVOS)](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#24-language-guided-video-object-segmentation-lvos)
  - [2.4.1 Dynamic Convolution based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#241-dynamic-convolution-based)
  - [2.4.2 Capsule Routing based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#242-capsule-routing-based)
  - [2.4.3 Attention based](https://github.com/tfzhou/VS-Survey/blob/main/2-VOS.md#243-attention-based)
## 3. Deep Learning-based Video Semantic Segmentation
- [3.1 (Instance-agnostic) Video Semantic Segmentation (VSS)](https://github.com/tfzhou/VS-Survey/blob/main/3-VSS.md#31-instance-agnostic-video-semantic-segmentation-vss)
  - [3.1.1 Efforts towards More Accurate Segmentation](https://github.com/tfzhou/VS-Survey/blob/main/3-VSS.md#311-efforts-toward-more-accurate-segmentation)
  - [3.1.2 Efforts towards Faster Segmentation](https://github.com/tfzhou/VS-Survey/blob/main/3-VSS.md#312-efforts-towards-faster-segmentation)
  - [3.1.3 Semi-/Weakly-supervised based](https://github.com/tfzhou/VS-Survey/blob/main/3-VSS.md#313-semi/weakly-supervised-based)
- [3.2 Video Instance Segmentation (VIS)](https://github.com/tfzhou/VS-Survey/blob/main/3-VSS.md#32-video-instance-segmentation-vis)
- [3.3 Video Panoptic Segmentation (VPS)](https://github.com/tfzhou/VS-Survey/blob/main/3-VSS.md#33-video-panoptic-segmentation-vps)

## 4. Datasets
- [Popular Datasets in VOS and VSS](https://github.com/tfzhou/VS-Survey/blob/main/4-Datasets.md)

![](dataset.png)

## Citation

If you find our survey and repository useful for your research, please consider citing our paper:
```bibtex
@article{wang2021survey,
  title={A survey on deep learning technique for video segmentation},
  author={Wang, Wenguan and Zhou, Tianfei and Porikli, Fatih and Crandall, David and Van Gool, Luc},
  journal={arXiv preprint arXiv:2107.01153},
  year={2021}
}
```
