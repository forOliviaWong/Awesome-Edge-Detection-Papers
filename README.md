# Awesome-Edge-Detection-Papers

A collection of edge detection papers (*a.k.a.* contour detection or boundary detection).

> Feel free to create a PR or an issue.

**Outline**

- [Deep-learning based approaches](#deep-learning-based-approaches)
  - [General edge detection](#general-edge-detection)
  - [Object contour detection](#object-contour-detection)
  - [Semantic edge detection](#semantic-edge-detection)
  - [Occlusion boundary detection](#occlusion-boundary-detection)
  - [Edge detection from frames](#edge-detection-from-frames)
- [Traditional approaches](#traditional-approaches)


## Deep-learning based approaches

### General edge detection

| Short name | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
| BDCN | [Bi-Directional Cascade Network for Perceptual Edge Detection](https://arxiv.org/pdf/1902.10903.pdf) | CVPR 2019 | [[code]](https://github.com/pkuCactus/BDCN) |
|  | [Learning to Predict Crisp Boundaries](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ruoxi_Deng_Learning_to_Predict_ECCV_2018_paper.pdf) | ECCV 2018 |  |
| RCF | [Richer Convolutional Features for Edge Detection](http://openaccess.thecvf.com/content_cvpr_2017/papers/Liu_Richer_Convolutional_Features_CVPR_2017_paper.pdf) | CVPR 2017 | [[code-caffe]](https://github.com/yun-liu/rcf) [[code-pytorch]](https://github.com/meteorshowers/RCF-pytorch) [[project]](https://mmcheng.net/zh/rcfEdge/) |
| CED | [Deep Crisp Boundaries](http://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_Deep_Crisp_Boundaries_CVPR_2017_paper.pdf) | CVPR 2017 | [[code]](https://github.com/Wangyupei/CED) |
| RDS | [Learning Relaxed Deep Supervision for Better Edge Detection](http://openaccess.thecvf.com/content_cvpr_2016/papers/Liu_Learning_Relaxed_Deep_CVPR_2016_paper.pdf) | CVPR 2016 |  |
| HFL | [High-for-Low and Low-for-High: Efficient Boundary Detection from Deep Object Features and its Applications to High-Level Vision](http://openaccess.thecvf.com/content_iccv_2015/papers/Bertasius_High-for-Low_and_Low-for-High_ICCV_2015_paper.pdf) | ICCV 2015 |  |
| HED | [Holistically-Nested Edge Detection](http://openaccess.thecvf.com/content_iccv_2015/papers/Xie_Holistically-Nested_Edge_Detection_ICCV_2015_paper.pdf) | ICCV 2015 | [[code]](https://github.com/s9xie/hed) |
| DeepEdge | [DeepEdge: A Multi-Scale Bifurcated Deep Network for Top-Down Contour Detection](http://openaccess.thecvf.com/content_cvpr_2015/papers/Bertasius_DeepEdge_A_Multi-Scale_2015_CVPR_paper.pdf) | CVPR 2015 |  |
| DeepContour | [DeepContour: A Deep Convolutional Feature Learned by Positive-sharing Loss for Contour Detection](http://openaccess.thecvf.com/content_cvpr_2015/papers/Shen_DeepContour_A_Deep_2015_CVPR_paper.pdf) | CVPR 2015 |  |

### Object contour detection

| Short name | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
| CEDN | [Object Contour Detection with a Fully Convolutional Encoder-Decoder Network](http://openaccess.thecvf.com/content_cvpr_2016/papers/Yang_Object_Contour_Detection_CVPR_2016_paper.pdf) | CVPR 2016 | [[code-caffe]](https://github.com/jimeiyang/objectContourDetector) [[code-TF]](https://github.com/Raj-08/tensorflow-object-contour-detection) |
|  | [Weakly Supervised Object Boundaries](http://openaccess.thecvf.com/content_cvpr_2016/papers/Khoreva_Weakly_Supervised_Object_CVPR_2016_paper.pdf) | CVPR 2016 |  |


### Semantic edge detection

| Short name | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
| DFF | [Dynamic Feature Fusion for Semantic Edge Detection](https://arxiv.org/pdf/1902.09104.pdf) | 1902.09104 |  |
| SEAL | [Simultaneous Edge Alignment and Learning](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zhiding_Yu_SEAL_A_Framework_ECCV_2018_paper.pdf) | ECCV 2018 | [[code]](https://github.com/Chrisding/seal) |
| CASENet | [CASENet: Deep Category-Aware Semantic Edge Detection](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yu_CASENet_Deep_Category-Aware_CVPR_2017_paper.pdf) | CVPR 2017 | [[code]](http://www.merl.com/research/license#CASENet) |
| `dataset` | [Semantic Contours from Inverse Detectors](https://www.robots.ox.ac.uk/~vgg/rg/papers/BharathICCV2011.pdf) | ICCV 2011 | [[code]](https://github.com/bharath272/semantic_contours) |


### Occlusion boundary detection

| Short name | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
|  | [Occlusion Boundary Detection via Deep Exploration of Context](http://openaccess.thecvf.com/content_cvpr_2016/papers/Fu_Occlusion_Boundary_Detection_CVPR_2016_paper.pdf) | CVPR 2016 |  |


### Edge detection from frames

| Short name | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
| Boundary Flow | [Boundary Flow: A Siamese Network that Predicts Boundary Motion without Training on Motion](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lei_Boundary_Flow_A_CVPR_2018_paper.pdf) | CVPR 2018 |  |
| LEGO | [LEGO: Learning Edge with Geometry all at Once by Watching Videos](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_LEGO_Learning_Edge_CVPR_2018_paper.pdf) | CVPR 2018 | [[code]](https://github.com/zhenheny/LEGO) |
|  | [Unsupervised Learning of Edges](http://openaccess.thecvf.com/content_cvpr_2016/papers/Li_Unsupervised_Learning_of_CVPR_2016_paper.pdf) | CVPR 2016 | [[code]](https://github.com/happyharrycn/unsupervised_edges) |


---


## Traditional approaches

| Short name | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
| SemiContour | [SemiContour: A Semi-supervised Learning Approach for Contour Detection](http://openaccess.thecvf.com/content_cvpr_2016/papers/Zhang_SemiContour_A_Semi-Supervised_CVPR_2016_paper.pdf) | CVPR 2016 |  |
| OEF | [Oriented Edge Forests for Boundary Detection](http://openaccess.thecvf.com/content_cvpr_2015/papers/Hallman_Oriented_Edge_Forests_2015_CVPR_paper.pdf) |  CVPR 2015 | [[code]](https://github.com/samhallman/oef) |
| SE | [Fast edge detection using structured forests](https://arxiv.org/pdf/1406.5549.pdf) | TPAMI 2015 | [[code]](https://github.com/pdollar/edges) |
| Edge Boxes | [Edge Boxes: Locating Object Proposals from Edges](https://www.microsoft.com/en-us/research/wp-content/uploads/2014/09/ZitnickDollarECCV14edgeBoxes.pdf) | ECCV 2014 | [[code]](https://github.com/pdollar/edges) |
| PMI | [Crisp Boundary Detection Using Pointwise Mutual Information](https://link.springer.com/chapter/10.1007/978-3-319-10578-9_52) | ECCV 2014 | [[code]](https://github.com/phillipi/crisp-boundaries) |
| Sketch Tokens | [Sketch tokens: A learned mid-level representation for contour and object detection](http://openaccess.thecvf.com/content_cvpr_2013/papers/Lim_Sketch_Tokens_A_2013_CVPR_paper.pdf) | CVPR 2013 |  |
| SCG | [Discriminatively Trained Sparse Code Gradients for Contour Detection](http://papers.nips.cc/paper/4787-discriminatively-trained-sparse-code-gradients-for-contour-detection.pdf) | NIPS 2012 |  |
| gPb-owt-ucm | [Contour Detection and Hierarchical Image Segmentation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.374.3367&rep=rep1&type=pdf) | TPAMI 2011 |  |
| Canny | [A Computational Approach to Edge Detection](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.420.3300&rep=rep1&type=pdf) | TPAMI 1986 |  |

