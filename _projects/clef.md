---
layout: page
title: ICCV2023
description: 
img: assets/img/12.jpg
importance: 1
category: work
---

<div class="jumbotron" >
    <div class="container">
      <div class="row">
        <div class="col-12">
            <h5 class="text-center">ICCV 2023</h5>
            <h2 class="text-center">Weakly-Supervised Text-driven Contrastive Learning for Facial Behavior Understanding</h2>
            <p class="text-center">&nbsp;</p>
            <h6 class="text-center"><a href="https://www.xianng.com/">Xiang Zhang</a>, Taoyue Wang, Xiaotian Li, <a href="https://hyang428.github.io">Huiyuan Yang</a> and <a href="https://www.cs.binghamton.edu/~lijun">Lijun Yin</a></h6>
            <p class="text-center">State University of New York at Binghamton</p>
            <hr>
            <p class="text-center" style="font-size:20px">
            <span class="link-block">
                <a href="https://openaccess.thecvf.com/ICCV2023/.pdf" target="_blank"
                    class="external-link button is-normal is-rounded is-dark">
                    <span class="icon">
                        <i class="fa-regular fa-file-pdf"></i>
                    </span>
                    <span>Paper</span>
                </a>
            </span>
            <!-- ArXiv abstract Link -->
            <span class="link-block">
                <a href="https://arxiv.org/abs/2304.00058" target="_blank"
                    class="external-link button is-normal is-rounded is-dark">
                    <span class="icon">
                        <i class="ai ai-arxiv"></i>
                    </span>
                    <span>arXiv</span>
                </a>
            </span>
            <!-- code Link -->
            <span class="link-block">
                <a href="https://github.com/LizhenWangT/FaceVerse" target="_blank"
                    class="external-link button is-normal is-rounded is-dark">
                    <span class="icon">
                    <i class="fab fa-github"></i>
                    </span>
                <span>Code</span>
                </a>
            </span>  
            <!-- poster Link -->
            <span class="link-block">
                <a href="{{site.url}}/assets/pdf/clef/poster.pdf" target="_blank"
                    class="external-link button is-normal is-rounded is-dark">
                    <span class="icon">
                    <i class="fa-regular fa-images"></i>
                    </span>
                <span>Poster</span>
                </a>
            </span>  
            </p>
        </div>
      </div>
    </div>
</div>

<div class="container">
    <p>&nbsp;</p>
    <div class="row">
      <div class="col-lg-12 col-md-12 col-sm-12 col-xl-12 text-center">
        <h2>Abstract</h2>
      </div>
        <p class="text-left"><em>Contrastive learning has shown promising potential for learning robust representations by utilizing unlabeled data. However, constructing effective positive-negative pairs for contrastive learning on facial behavior datasets remains challenging. This is because such pairs inevitably encode the subject-ID information, and the randomly constructed pairs may push similar facial images away due to the limited number of subjects in facial behavior datasets. To address this issue, we propose to utilize activity descriptions, coarse-grained information provided in some datasets, which can provide high-level semantic information about the image sequences but is often neglected in previous studies. More specifically, we introduce a two-stage Contrastive Learning with Text-Embeded framework for Facial behavior understanding (CLEF). The first stage is a weakly-supervised contrastive learning method that learns representations from positive-negative pairs constructed using coarse-grained activity information. The second stage aims to train the recognition of facial expressions or facial action units by maximizing the similarity between image and the corresponding text label names. The proposed CLEF achieves state-of-the-art performance on three in-the-lab datasets for AU recognition and three in-the-wild datasets for facial expression recognition.</em>
        </p>
    </div>
    <div class="row">
        <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/clef/1.png" title="example image" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="caption">
        The overview of our proposed method.
    </div>
</div>


{% raw %}
```bibtex
@InProceedings{Zhang_2023_ICCV,
    author    = {Zhang, Xiang and Wang, Taoyue and Li, Xiaotian and Yang, Huiyuan and Yin, Lijun},
    title     = {Weakly-Supervised Text-driven Contrastive Learning for Facial Behavior Understanding},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2023}
}
```
{% endraw %}



