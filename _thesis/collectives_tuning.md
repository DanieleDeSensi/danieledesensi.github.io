---
layout: page
title: "⚙️ Collectives Tuning in Open MPI/MPICH"
description: 
img: https://images.unsplash.com/photo-1600521158202-f64be2d4e7b1?q=80&w=1930&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
importance: 1
category: Available Thesis
related_publications: collectives-tuning
---

Collective operations, such as allreduce, broadcast, and gather, are essential for parallel applications that require communication and data sharing across distributed systems. Optimizing these operations is crucial for improving the overall performance of high-performance computing (HPC) systems, particularly in the context of modern architectures with heterogeneous hardware (e.g., CPUs, GPUs, and specialized accelerators). Open MPI and MPICH are two of the most widely used MPI (Message Passing Interface) libraries for parallel programming, and they both offer various tunable parameters and algorithms to optimize collective operations.

In this thesis, the student will focus on tuning collective operations in Open MPI and MPICH. This includes selecting or developing optimal algorithms for different collective operations, configuring library parameters (e.g., thresholds for algorithm switching, buffer sizes, etc.), and evaluating the impact of these optimizations on application performance.

The student will work on designing and implementing improvements in collective communication routines, such as experimenting with different algorithms or applying performance tuning techniques (e.g., pipelining, topology-aware scheduling). The thesis will also involve benchmarking the performance of collective operations on different hardware setups (e.g., multi-core, multi-node systems) and evaluating their efficiency in a variety of real-world applications.

**Skills required**:
- Familiarity with MPI and parallel programming concepts
- Experience with performance profiling and tuning of HPC systems

[1] <a href="https://www.open-mpi.org/">Open MPI</a><br>
[2] <a href="https://www.mpich.org/">MPICH</a><br>

<b>Approximate composition:</b> 20% State of the art analysis, 30% Theory/Design, 50% Implementation/Experiments  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1600521158202-f64be2d4e7b1?q=80&w=1930&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
