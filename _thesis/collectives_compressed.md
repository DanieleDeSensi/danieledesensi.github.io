---
layout: page
title: "🗜️ GPU-Accelerated Compressed Collective Operations"
description: 
img: https://images.unsplash.com/photo-1558494949-ef010cbdcc31?q=80&w=3734&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
importance: 1
category: Available Thesis
---

Collective operations are essential building blocks in distributed applications, enabling efficient aggregation, distribution, or collection of data among multiple nodes. While these operations are critical for many applications, including machine learning and scientific computing, their performance can be heavily impacted by the large data volumes exchanged between nodes. One way to alleviate this bottleneck is by compressing the data before transmission, reducing communication overhead without compromising accuracy.  

Recent works have explored compression techniques such as quantization, sparsification, and error-bounded lossy compression [1], but their integration into collective operations remains an open challenge. Further acceleration can be achieved by leveraging GPUs, which are already heavily used in many distributed workloads.  

In this thesis, the student will design and implement GPU-accelerated compressed collective operations. The work will explore various compression approaches, including quantization, sparsification, and advanced techniques like error-bounded compression [1]. The implementation will be evaluated on a GPU cluster and compared against uncompressed collective operations to quantify the performance gains and trade-offs.  

[1] <a href="https://arxiv.org/abs/2308.05199">gZCCL: Compression-Accelerated Collective Communication Framework for GPU Clusters - J. Huang et al.</a><br>

<b>Approximate composition:</b> 20% State of the art analysis, 30% Theory/Design, 50% Implementation/Experiments  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?q=80&w=3734&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
