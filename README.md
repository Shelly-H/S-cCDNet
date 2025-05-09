# S-cCDNet
Semantic-centric change detection framework

# Abstract
The semantic change detection (SCD) task aims to detect “from-to” change types of land cover occurring over time in registered multi-temporal remote sensing images. The spatiotemporal heterogeneity of land cover introduces significant intra-class variance, while the spatiotemporal correlation provides a reference for land cover change. Current multi-task SCD methods achieve encouraging results by enforcing consistency between the semantic segmentation and binary change detection, yet fall short in exploring the geological priors of land cover. In this paper, we propose a Semantic-centric Change Detection framework (S-cCDNet) to model “from-to” semantic changes by considering two geographical priors: spatiotemporal heterogeneity and spatiotemporal correlation. To overcome spatiotemporal heterogeneity, we designed an intra-temporal Pixel-to-Prototype (Pix2Pro) and inter-temporal Prototype-to-Prototype (Pro2Pro) contrast strategy to promote intra-class compactness and inter-class separability. To enhance spatiotemporal correlation, we introduced a Spatiotemporal Correlation Transformer (STCformer) to progressively model the spatiotemporal dependencies of semantic changes from scene level to pixel level in a semantic-aware manner. In addition, a direction-agnostic SCD loss is proposed as a regularization term to prevent overfitting of semantic change directions. Comprehensive experiments conducted on two large-scale SCD datasets with different scales and scenes have demonstrated the superiority of the proposed S-cCDNet.

# Datasets
Please download the preprocessed Landsat-SCD dataset from: https://pan.baidu.com/s/1UTOwgmXV2uYajm5JmJJSsQ?pwd=8djp

Extraction code：8djp 

Please download the SECOND dataset from: https://pan.baidu.com/s/14An5X_Ewu38TNy2j3WtYPg?pwd=ansr

Extraction code：ansr 

# Code
The code will be released after the paper is accepted.
