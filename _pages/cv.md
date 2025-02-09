---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[PDF version](../files/CV.pdf)

Work experience
======
* **Postdoctoral Researcher**, 2022 - 2024
  * Hosted by [GeomeriX](https://team.inria.fr/geomerix/), [LIX](https://www.lix.polytechnique.fr/), École Polytechnique, supervised by [Maks Ovsjanikov](https://www.lix.polytechnique.fr/~maks/).
  * Ongoing project about end-to-end lightweight probabilistic hierarchical point cloud diffusion model.
  * Ongoing project about a novel Neural Radiance Field (NeRF) representation suitable for 3D shape reconstruction and NeRF editing currently under review).
  * [VoroMesh](https://nissmar.github.io/voromesh.github.io/): developed a deep learning model for a novel 3D shape representation, capable of producing watertight meshes from input SDF grids. Managed a PhD student over the course of the project.
  * [Self-supervised Dual Contouring](https://arxiv.org/abs/2405.18131): worked in a team with a PhD student on a project about a novel differentiable mesh reconstruction model based on Deep Learining and Dual Contouring. Explored probabilistic modifications of the proposed model.

* **Ph.D. Student**, 2017 - 2021
  * Hosted by [Thoth](https://team.inria.fr/thoth/) and [Morpheo](https://team.inria.fr/morpheo/), Inria Grenoble, supevised by [Jakob Verbeek](https://scholar.google.com/citations?user=oZGA-rAAAAAJ) and [Edmond Boyer](https://scholar.google.com/citations?user=bxcnXn8AAAAJ).
  * [Discrete Point Flow Networks](https://github.com/Regenerator/dpf-nets): developed a probabilistic generative model for point clouds based on invertible normalizing flows. Achieved comparable to state-of-the-art performance while reducing the computational load by magnitudes.
  * [Probabilistic Reconstruction Networks](https://github.com/Regenerator/prns): developed a probabilistic framework for inference-based 3D shape reconstruction models from image inputs. Best science paper honorable mention at British Machine Vision Conference 2019.

* **Research Intern**, 2016 - 2017
  * Hosted by Skoltech Computer Vision Group, supervised by [Victor Lempitsky](https://scholar.google.com/citations?user=gYYVokYAAAAJ).
  * Research projects on CNN compression and 3D point cloud recognition.
  * [Escape From Cells: Kd-Network for 3D Shape Recognition](https://arxiv.org/abs/1704.01222): developed a novel feature extraction neural network model for classification, segmentation and retrieval tasks for point clouds based on construction of noisy kd-trees.

Education
======
* **Ph.D. in Mathematics and Informatics**, Université Grenoble Alpes, 2021
* **M.S. in Data Science with Honors**, Skolkovo Institute of Science and Technology, 2017
* **B.S. in Applied Mathematics and Physics**, Moscow Institute of Physics and Technology, 2015

Additional Experience and Awards
======
* Regular reviewer for CVPR, NeurIPS, ICLR, ICCV, ECCV, ICML, TPAMI, etc.
* Organization of weekly laboratory seminars among the members of Maks Ovsjanikov team.
* Best Science Paper Honorable Mention Award at British Machine Vision Conference, 2019.
* Summer School [PAISS 2018](https://project.inria.fr/paiss/program-2018/).
* 2nd place in [ShapeNet Point Cloud Segmentation Challenge](https://arxiv.org/pdf/1710.06104) held at the International Conference on Computer Vision 2017.
* Teaching for a summer school on introductory machine learning for high school students.
* Organization of career fair days for university students in MIPT.
  
Skills, Activities, Interests
======
* **Scientific expertise**: Computer Vision, Deep Learning, Probabilistic Modeling, 3D Shape Recognition, 3D Shape Generation, Surface Reconstruction, Differentiable 3D Shape Representations, Differentiable Rendering.
* **Recent technical experience**: Python, PyTorch, Nerfstudio, HDF5, Numpy, Scipy.
* **Previous technical experience**: TensorFlow, MongoDB, C++.
* **Languages**: English (fluent), French (intermediate), Russian (native).
* **Hobbies**: Running, Weight Lifting, Skiing, World of Warcraft competitive group activities (reached top 0.1% of players).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
