---
layout: page
title: Scalable Novel-View Synthesis
description: Scalable Indoor Novel-View Synthesis using Drone-Captured 360 Imagery with 3D Gaussian Splatting.
img: 
# redirect: /assets/pdf/DURF_report.pdf
importance: 1
category: Computer Vision
---

April, 2024

<br>

Recent work in indoor novel-view synthesis for room-scale scenes have demonstrated impressive results, but reconstructing complex, multi-story, indoor scenes is a challenging and time-consuming problem. This paper proposes an efficient and scalable pipeline for indoor novel-view synthesis from drone-captured 360° video footage using 3D Gaussian Splatting (3DGS). Most neural rendering methods include 3DGS will not scale to infinitely large number of images. As such it is necessary to devise a divide-and-conquer strategy to automatically split the scene into smaller sub-blocks that reconstructs individually and in parallel. This not only improves the overall pipeline time but also allows our method to easily scale up to large scenes. Our experiments demonstrate marked improvement in both reconstruction quality, i.e. PSNR and SSIM, and reconstruction time compared to prior approaches.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/nvs_pipeline.png" title="pipeline" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Overall pipeline of our method.
</div>

Link to paper is pending.

Thank you!

