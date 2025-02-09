---
title: "Escape from Cells: Deep Kd-Networks for the Recognition of 3D Point Cloud Models"
collection: publications
category: conferences
permalink: /publication/2017-10-01-kd-networks-iccv
excerpt: 'The paper presents a novel neural architecture for feature extraction from point clouds based on hierarchical feature pooling from kd-trees constructed on the input point clouds. The architecture is evaluated in several point cloud recognition applications including classification, segmentation and retrieval.'
date: 2017-10-01
venue: 'International Conference on Computer Vision'
codeurl: 'https://github.com/Regenerator/kdnets'
paperurl: 'https://arxiv.org/pdf/1704.01222'
citation: 'R. Klokov and V. Lempitsky. &quot;Escape from cells: Deep kd-networks for the recognition of 3d point cloud models.&quot; In <i>ICCV</i>&apos;17.'
---

![Kd-Network](../images/kd-network.png)

We present a new deep learning architecture (called Kd-network) that is designed for 3D model recognition tasks and works with unstructured point clouds. The new architecture performs multiplicative transformations and shares parameters of these transformations according to the subdivisions of the point clouds imposed onto them by kd-trees. Unlike the currently dominant convolutional architectures that usually require rasterization on uniform two-dimensional or three-dimensional grids, Kd-networks do not rely on such grids in any way and therefore avoid poor scaling behavior. In a series of experiments with popular shape recognition benchmarks, Kd-networks demonstrate competitive performance in a number of shape recognition tasks such as shape classification, shape retrieval and shape part segmentation.
