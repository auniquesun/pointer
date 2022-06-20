## Introduction
Since the Transformer architecture and self-supervised learning have witnessed the overwhelming applications 
in natural language processing, 
and recently, the vision community also embraces this trend. 
In 3D, actually there have been number of relevant attempts but lack of summary. 
Therefore, this repository provides a paper collection of point cloud processing focusing on the following 2 aspects: 

* unsupervised and self-supervised methods 
* Transformer-based models

`Venue` and `Code` are attached to each paper. Following the `Paper` link, you can also find its `.bib` file. 
We will supplement new paper regularly. If you find some related and important paper absent in this collection, 
feel free to raise a pull request, or contact Mr.sunhy@outlook.com. 

Welcome your contributions! :smiley:

## Basics
| Paper      | Venue | Year | Code |
| :----------- | :----------- | :-----------: | :-----------: |
| [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://openaccess.thecvf.com/content_cvpr_2017/html/Qi_PointNet_Deep_Learning_CVPR_2017_paper.html) | CVPR | 2017 | [link](https://github.com/yanx27/Pointnet_Pointnet2_pytorch) |
| [PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space](https://papers.nips.cc/paper/2017/hash/d8bf84be3800d12f74d8b05e9b89836f-Abstract.html) | NeurIPS | 2017 | [link](https://github.com/yanx27/Pointnet_Pointnet2_pytorch) |
| [DGCNN: Dynamic Graph CNN for Learning on Point Clouds](https://dl.acm.org/doi/10.1145/3326362) | TOG | 2019 | [link](https://github.com/WangYueFt/dgcnn) |
| [KPConv: Flexible and Deformable Convolution for Point Clouds](https://openaccess.thecvf.com/content_ICCV_2019/html/Thomas_KPConv_Flexible_and_Deformable_Convolution_for_Point_Clouds_ICCV_2019_paper.html) | ICCV | 2019 | [link](https://github.com/HuguesTHOMAS/KPConv) |
| [Walk in the Cloud: Learning Curves for Point Clouds Shape Analysis](https://openaccess.thecvf.com/content/ICCV2021/html/Xiang_Walk_in_the_Cloud_Learning_Curves_for_Point_Clouds_Shape_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/tiangexiang/CurveNet) |
| [Rethinking Network Design and Local Geometry in Point Cloud: A Simple Residual MLP Framework](https://openreview.net/forum?id=3Pbra-_u76D) | ICLR | 2022 | [link](https://github.com/ma-xu/pointMLP-pytorch) |

## Unsupervised and Self-supervised Learning for Point Cloud Understanding
| Paper      | Venue | Year | Code |
| :----------- | :----------- | :-----------: | :-----------: |
| [Point-Bert: Pre-training 3D Point Cloud Transformers with Masked Point Modeling](https://openaccess.thecvf.com/content/CVPR2022/papers/Yu_Point-BERT_Pre-Training_3D_Point_Cloud_Transformers_With_Masked_Point_Modeling_CVPR_2022_paper.pdf) | CVPR | 2022 | [link](https://github.com/lulutang0608/Point-BERT) |
| [CrossPoint: Self-Supervised Cross-Modal Contrastive Learning for 3D Point Cloud Understanding](https://openaccess.thecvf.com/content/CVPR2022/papers/Afham_CrossPoint_Self-Supervised_Cross-Modal_Contrastive_Learning_for_3D_Point_Cloud_Understanding_CVPR_2022_paper.pdf) | CVPR | 2022 | [link](https://github.com/MohamedAfham/CrossPoint) |
| [Contrastive Boundary Learning for Point Cloud Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Tang_Contrastive_Boundary_Learning_for_Point_Cloud_Segmentation_CVPR_2022_paper.pdf) | CVPR | 2022 | [link](https://github.com/LiyaoTang/contrastBoundary) |
| [SegContrast: 3D Point Cloud Feature Representation Learning Through Self-Supervised Segment Discrimination](https://ieeexplore.ieee.org/document/9681336/) | RAL | 2022 | [link](https://github.com/PRBonn/segcontrast) |
| [Exploring Data-Efficient 3D Scene Understanding with Contrastive Scene Contexts](https://openaccess.thecvf.com/content/CVPR2021/html/Hou_Exploring_Data-Efficient_3D_Scene_Understanding_With_Contrastive_Scene_Contexts_CVPR_2021_paper.html) | CVPR | 2021 | [link](https://github.com/facebookresearch/ContrastiveSceneContexts) |
| [Self-Supervised Learning on 3D Point Clouds by Learning Discrete Generative Models](https://openaccess.thecvf.com/content/CVPR2021/html/Eckart_Self-Supervised_Learning_on_3D_Point_Clouds_by_Learning_Discrete_Generative_CVPR_2021_paper.html) | CVPR | 2021 | [link]() |
| [PoinTr: Diverse Point Cloud Completion with Geometry-Aware Transformers](https://openaccess.thecvf.com/content/ICCV2021/html/Yu_PoinTr_Diverse_Point_Cloud_Completion_With_Geometry-Aware_Transformers_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/yuxumin/PoinTr) |
| [Self-Supervised Pretraining of 3D Features on any Point-Cloud](https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_Self-Supervised_Pretraining_of_3D_Features_on_Any_Point-Cloud_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/facebookresearch/DepthContrast) |
| [Unsupervised Point Cloud Pre-training via Occlusion Completion](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Unsupervised_Point_Cloud_Pre-Training_via_Occlusion_Completion_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/hansen7/OcCo) |
| [PointContrast: Unsupervised Pre-training for 3D Point Cloud Understanding](https://link.springer.com/chapter/10.1007/978-3-030-58580-8_34) | ECCV | 2020 | [link](https://github.com/facebookresearch/PointContrast) |
| [Self-Supervised Few-Shot Learning on Point Clouds](https://proceedings.neurips.cc/paper/2020/hash/50c1f44e426560f3f2cdcb3e19e39903-Abstract.html) | NeurIPS | 2020 | [link](https://github.com/charusharma1991/SSL_PointClouds) |
| [Self-Supervised Deep Learning on Point Clouds by Reconstructing Space](https://papers.nips.cc/paper/2019/hash/993edc98ca87f7e08494eec37fa836f7-Abstract.html) | NeurIPS | 2019 | [link]() |
| [FoldingNet: Point Cloud Auto-encoder via Deep Grid Deformation](https://openaccess.thecvf.com/content_cvpr_2018/html/Yang_FoldingNet_Point_Cloud_CVPR_2018_paper.html) | CVPR | 2018 | [link](https://github.com/AnTao97/UnsupervisedPointCloudReconstruction) |
| [Learning a Probabilistic Latent Space of Object Shapes via 3D Generative-Adversarial Modeling](https://papers.nips.cc/paper/2016/hash/44f683a84163b3523afe57c2e008bc8c-Abstract.html) | NIPS | 2016 | [link](https://github.com/black0017/3D-GAN-pytorch) |
| [Learning Representations and Generative Models for 3D Point Clouds](http://proceedings.mlr.press/v80/achlioptas18a.html) | ICML | 2018 | [link](https://github.com/optas/latent_3d_points) |
| [View inter-prediction GAN: unsupervised representation learning for 3D shapes by learning global shape memories to support local view predictions](https://dl.acm.org/doi/10.1609/aaai.v33i01.33018376) | AAAI | 2019 | None |


## Transformer for Point Cloud Processing
| Paper      | Venue | Year | Code |
| :----------- | :----------- | :-----------: | :-----------: |
| [Embracing Single Stride 3D Object Detector with Sparse Transformer](https://openaccess.thecvf.com/content/CVPR2022/papers/Fan_Embracing_Single_Stride_3D_Object_Detector_With_Sparse_Transformer_CVPR_2022_paper.pdf) | CVPR | 2022 | [link](https://github.com/TuSimple/SST) |
| [Fast Point Transformer](https://arxiv.org/abs/2112.04702) | CVPR | 2022 | [link](https://github.com/POSTECH-CVLab/FastPointTransformer) |
| [PVT: Point-Voxel Transformer for Point Cloud Learning](https://openaccess.thecvf.com/content/CVPR2022/papers/Park_Fast_Point_Transformer_CVPR_2022_paper.pdf) | ArXiv | 2022 | [link](https://github.com/HaochengWan/PVThttps://github.com/HaochengWan/PVT) |
| [An End-to-End Transformer Model for 3D Object Detection](https://openaccess.thecvf.com/content/ICCV2021/html/Misra_An_End-to-End_Transformer_Model_for_3D_Object_Detection_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/facebookresearch/3detr) |
| [Point Transformer](https://openaccess.thecvf.com/content/ICCV2021/html/Zhao_Point_Transformer_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/qq456cvb/Point-Transformers) |
| [Voxel Transformer for 3D Object Detection](https://openaccess.thecvf.com/content/ICCV2021/html/Mao_Voxel_Transformer_for_3D_Object_Detection_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/PointsCoder/VOTR) |
| [3D Object Detection with Pointformer](https://openaccess.thecvf.com/content/CVPR2021/html/Pan_3D_Object_Detection_With_Pointformer_CVPR_2021_paper.html) | CVPR | 2021 | [link](https://github.com/Vladimir2506/Pointformer) |
| [Improving 3D Object Detection with Channel-wise Transformer](https://openaccess.thecvf.com/content/ICCV2021/html/Sheng_Improving_3D_Object_Detection_With_Channel-Wise_Transformer_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/hlsheng1/CT3D) |
| [Group-Free 3D Object Detection via Transformers](https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Group-Free_3D_Object_Detection_via_Transformers_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/zeliu98/Group-Free-3D) |
| [Cloud Transformers: A Universal Approach To Point Cloud Processing Tasks](https://openaccess.thecvf.com/content/ICCV2021/html/Mazur_Cloud_Transformers_A_Universal_Approach_to_Point_Cloud_Processing_Tasks_ICCV_2021_paper.html) | ICCV | 2021 | [link](https://github.com/saic-vul/cloud_transformers) |
| [PCT: Point cloud transformer](https://link.springer.com/article/10.1007/s41095-021-0229-5) | CVM | 2021 | [link](https://github.com/Strawberry-Eat-Mango/PCT_Pytorch) |
| [Perceiver: General Perception with Iterative Attention](http://proceedings.mlr.press/v139/jaegle21a.html) | ICML | 2021 | [link](https://github.com/deepmind/deepmind-research) |
| [Perceiver IO: A General Architecture for Structured Inputs & Outputs](https://openreview.net/forum?id=fILj7WpI-g) | ICLR | 2022 | [link](https://github.com/krasserm/perceiver-io) |