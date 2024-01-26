---
layout: page
title: "➕ Implementation of the Swing allreduce algorithm in OpenMPI"
description: 
img: https://images.unsplash.com/photo-1625459201773-9b2386f53ca2?q=80&w=1930&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
importance: 1
category: Available Thesis
related_publications: swing
---

The allreduce operation is one of the most commonly used communication routines in distributed applications. In this operation, vectors coming from different nodes need to be aggregated element-wise (e.g., by summing elements), and the result distributed back to all the nodes. Estimations show up to 40% of the time spent in the training of large-scale machine learning models is spent performing this operation [1]. To improve its bandwidth and the performance of applications using it, the Swing algorithm has been recently proposed [2], which can improve the performance of the allreduce by up to 3x. 

In this thesis the student will implement the Swing algorithm in OpenMPI [3], one of the most commonly used communication libraries for distributed applications. The implementation will then be evaluated through a set of experiments to be performed on a 50-nodes cluster, as well as on the LUMI and Leonardo supercomputers (currently the 5th and 6th fastest supercomputers in the world). A good knowledge of the C programming language is required. If time allows, the algorithm could also be integrated into PyTorch and/or TensorFlow and evaluated on a set of machine learning applications.

[1] <a href="https://www.usenix.org/conference/nsdi23/presentation/wang-weiyang">Weiyang Wang et al. "TopoOpt: Co-optimizing Network Topology and Parallelization Strategy for Distributed Training Jobs"</a><br>
[2] <a href="https://arxiv.org/abs/2401.09356">Swing: Short-cutting Rings for Higher Bandwidth Allreduce - Daniele De Sensi, Tommaso Bonato, David Saam, Torsten Hoefler</a><br>
[3] <a href="https://www.open-mpi.org/">OpenMPI</a><br>
 
<b>Approximate composition:</b> 10% State of the art analysis, 10% Theory/Design, 80% Implementation/Experiments

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1625459201773-9b2386f53ca2?q=80&w=1930&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>