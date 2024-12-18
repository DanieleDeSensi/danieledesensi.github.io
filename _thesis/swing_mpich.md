---
layout: page
title: "➕ Implementation of the Swing Algorithm on MPICH"
description: 
img: https://images.unsplash.com/photo-1625459201773-9b2386f53ca2?q=80&w=1930&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
importance: 1
category: Available Thesis
related_publications: swing
---

The allreduce operation is widely used in distributed computing for aggregating data across multiple nodes. This operation is crucial in high-performance applications, such as large-scale machine learning, scientific simulations, and data analytics. Despite its importance, it can become a bottleneck due to communication delays. To optimize this, the Swing algorithm was introduced, achieving up to a 3x performance improvement over traditional allreduce methods by leveraging more efficient communication patterns [1].

MPICH [2], a widely used MPI implementation for parallel computing, is commonly employed in high-performance computing (HPC) environments. However, the integration of the Swing algorithm into MPICH is still under-explored. This thesis aims to implement the Swing algorithm within MPICH, enhancing the efficiency of collective operations, particularly allreduce. The implementation will be evaluated on a high-performance cluster, with experiments comparing the performance of the Swing-based solution to traditional methods.

The thesis will include a detailed analysis of MPICH's existing allreduce implementation, followed by the design and integration of the Swing algorithm. If time permits, the solution may also be tested on a real-world application such as machine learning or scientific simulations.

**Skills required**:  
- Proficiency in C programming and MPI  
- Basic understanding of parallel computing concepts  
- Experiences with GPU programming

[1] <a href="https://arxiv.org/abs/2401.09356">Swing: Short-cutting Rings for Higher Bandwidth Allreduce - Daniele De Sensi, Tommaso Bonato, David Saam, Torsten Hoefler</a><br>
[2] <a href="https://www.mpich.org/">MPICH</a><br>

<b>Approximate composition:</b> 10% State of the art analysis, 20% Theory/Design, 70% Implementation/Experiments  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1625459201773-9b2386f53ca2?q=80&w=1930&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
