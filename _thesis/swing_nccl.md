---
layout: page
title: "➕ Implementation of the Swing Algorithm on NCCL/RCCL"
description: 
img: https://images.unsplash.com/photo-1625459201773-9b2386f53ca2?q=80&w=1930&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
importance: 1
category: Available Thesis
related_publications: swing
---

The allreduce operation is one of the most widely used communication primitives in distributed applications, enabling element-wise aggregation of vectors across multiple nodes, with the result distributed back to all nodes. Up to 40% of the time spent training large-scale machine learning models is attributed to this operation [1].  

To improve the bandwidth and performance of the allreduce operation, the Swing algorithm has been proposed [2], which leverages optimized communication patterns to achieve up to a 3x speedup on blocking networks. While Swing has been simulated its integration into GPU-centric libraries such as NCCL [3] and RCCL [4]—the most widely used communication libraries for GPU-based distributed applications—remains unexplored.  

In this thesis, the student will implement the Swing algorithm on NCCL/RCCL to enable highly efficient GPU-based collective operations. The implementation will be evaluated on multiple testbeds, including a multi-node GPU cluster and, if available, on supercomputers like LUMI or Leonardo. Experiments will compare the performance of the new implementation with existing algorithms. A solid understanding of GPU programming (CUDA) and parallel programming is required.  

[1] <a href="https://www.usenix.org/conference/nsdi23/presentation/wang-weiyang">Weiyang Wang et al. "TopoOpt: Co-optimizing Network Topology and Parallelization Strategy for Distributed Training Jobs"</a><br>
[2] <a href="https://arxiv.org/abs/2401.09356">Swing: Short-cutting Rings for Higher Bandwidth Allreduce - Daniele De Sensi, Tommaso Bonato, David Saam, Torsten Hoefler</a><br>
[3] <a href="https://developer.nvidia.com/nccl">NVIDIA NCCL</a><br>
[4] <a href="https://github.com/ROCmSoftwarePlatform/rccl">AMD RCCL</a><br>

<b>Approximate composition:</b> 10% State of the art analysis, 20% Theory/Design, 70% Implementation/Experiments  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1625459201773-9b2386f53ca2?q=80&w=1930&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
