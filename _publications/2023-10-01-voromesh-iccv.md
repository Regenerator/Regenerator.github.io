---
title: "VoroMesh: Learning Watertight Surface Meshes with Voronoi Diagrams"
collection: publications
category: conferences
permalink: /publication/2023-10-01-voromesh-iccv
excerpt: 'The paper proposes a novel differentiable resperentation for surfaces based on Voronoi diagrams with direct access to watertight mesh extraction. VoroMesh is verified in two settings: direct per-object optimization (overfitting), and infernce-based mesh reconstuction from low-resolution grids of signed distance function values.'
date: 2023-10-01
venue: 'International Conference on Computer Vision'
codeurl: 'https://github.com/nissmar/VoroMesh'
paperurl: 'https://arxiv.org/pdf/2308.14616'
citation: 'N. Maruani, R. Klokov, M. Ovsjanikov, P. Alliez and M. Desbrun. &quot;VoroMesh: Learning Watertight Surface Meshes with Voronoi Diagrams.&quot; In <i>ICCV</i>&apos;23.'
---

![VoroMesh](../images/voromesh.png)

In stark contrast to the case of images, finding a concise, learnable discrete representation of 3D surfaces remains a challenge. In particular, while polygon meshes are arguably the most common surface representation used in geometry processing, their irregular and combinatorial structure often make them unsuitable for learning-based applications. In this work, we present VoroMesh, a novel and differentiable Voronoi-based representation of watertight 3D shape surfaces. From a set of 3D points (called generators) and their associated occupancy, we define our boundary representation through the Voronoi diagram of the generators as the subset of Voronoi faces whose two associated (equidistant) generators are of opposite occupancy: the resulting polygon mesh forms a watertight approximation of the target shape’s boundary. To learn the position of the generators, we propose a novel loss function, dubbed VoroLoss, that minimizes the distance from ground truth surface samples to the closest faces of the Voronoi diagram which does not require an explicit construction of the entire Voronoi diagram. A direct optimization of the Voroloss to obtain generators on the Thingi32 dataset demonstrates the geometric efficiency of our representation compared to axiomatic meshing algorithms and recent learning-based mesh representations. We further use VoroMesh in a learning-based mesh prediction task from input SDF grids on the ABC dataset, and show comparable performance to state-of-the-art methods while guaranteeing closed output surfaces free of self-intersections.
