---
layout: page
title: "📊 Analysis of Root Causes of Performance Differences Between MPI and NCCL"
description: 
img: https://images.unsplash.com/photo-1516382799247-87df95d790b7?q=80&w=2674&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
importance: 1
category: Available Thesis
related_publication: gpugpuinterconnect
---

MPI (Message Passing Interface) [1] and NCCL (NVIDIA Collective Communications Library) [2] are two widely used libraries for distributed computing, often employed in high-performance computing and deep learning applications, respectively. While both libraries support collective operations, significant performance differences are often observed depending on the workload, network configuration, and hardware platform. Understanding these differences is critical for optimizing distributed applications and selecting the appropriate library for a given use case.

This thesis will focus on identifying and analyzing the root causes of performance differences between MPI and NCCL. Specifically, the project will:
- Compare the implementations of key collective operations (e.g., allreduce, allgather) in MPI and NCCL.
- Analyze protocol-level optimizations in NCCL, such as ring-based algorithms, and contrast them with MPI’s general-purpose algorithms.
- Perform controlled experiments on a variety of systems (e.g., clusters with InfiniBand or Ethernet interconnects, GPU vs. CPU-based collectives) to isolate performance factors.

The student will run benchmarks on real-world applications and synthetic workloads, using several benchmarking tools. The results will provide actionable insights into where and why one library outperforms the other, potentially leading to suggestions for improving the libraries themselves.

**Skills required**:
- Familiarity with MPI
- Knowledge of collective communication operations
- Programming proficiency in C/C++ and Python

[1] <a href="https://www.mpi-forum.org/">MPI Standard</a><br>
[2] <a href="https://developer.nvidia.com/nccl">NVIDIA NCCL</a><br>

<b>Approximate composition:</b> 20% State of the art analysis, 30% Experimental Design, 50% Benchmarking and Analysis  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1516382799247-87df95d790b7?q=80&w=2674&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
