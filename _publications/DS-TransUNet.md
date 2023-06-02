---
title: "DS-TransUNet: Dual Swin Transformer U-Net for Medical Image Segmentation"
collection: publications
permalink: /publications/DS-TransUNet
venue: "IEEE Transactions on Instrumentation and Measurement (TIM)"
date: 2022-5-30
citation: '<b>Ailiang Lin</b>, Bingzhi Chen, Jiayu Xu, ZhengZhang, Guangming Lu and David Zhang.'
---

[[PDF]](https://ieeexplore.ieee.org/abstract/document/9785614)[[Code]](https://github.com/TianBaoGe/DS-TransUNet)

## Abstract
Automatic medical image segmentation has made great progress owing to powerful deep representation learning. Inspired by the success of self-attention mechanism in transformer, considerable efforts are devoted to designing the robust variants of the encoder–decoder architecture with transformer. However, the patch division used in the existing transformer-based models usually ignores the pixel-level intrinsic structural features inside each patch. In this article, we propose a novel deep medical image segmentation framework called dual swin transformer U-Net (DS-TransUNet), which aims to incorporate the hierarchical swin transformer into both the encoder and the decoder of the standard U-shaped architecture. Our DS-TransUNet benefits from the self-attention computation in swin transformer and the designed dual-scale encoding, which can effectively model the non-local dependencies and multiscale contexts for enhancing the semantic segmentation quality of varying medical images. Unlike many prior transformer-based solutions, the proposed DS-TransUNet adopts a well-established dual-scale encoding mechanism that uses dual-scale encoders based on swin transformer to extract the coarse and fine-grained feature representations of different semantic scales. Meanwhile, a well-designed transformer interactive fusion (TIF) module is proposed to effectively perform multiscale information fusion through the self-attention mechanism. Furthermore, we introduce the swin transformer block into the decoder to further explore the long-range contextual information during the up-sampling process. Extensive experiments across four typical tasks for medical image segmentation demonstrate the effectiveness of DS-TransUNet, and our approach significantly outperforms the state-of-the-art methods.