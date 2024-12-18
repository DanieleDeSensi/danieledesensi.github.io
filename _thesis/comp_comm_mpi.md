---
layout: page
title: "⚡ Benchmarking Computation-Communication Overlap in MPI"
description: 
img: https://images.unsplash.com/photo-1533749047139-189de3cf06d3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8Y2xvY2t8ZW58MHx8MHx8fDI%3D
importance: 1
category: Available Thesis
---

In high-performance computing (HPC) applications, overlapping computation with communication is a critical optimization technique that can significantly improve performance, especially when using the Message Passing Interface (MPI) for distributed computing. However, achieving effective overlap between computation and communication in MPI applications is challenging due to the intricacies of hardware, network latencies, and MPI implementations.

This thesis will focus on benchmarking and analyzing the potential of computation-communication overlap in MPI applications. The student will design experiments to evaluate how well computation can overlap with communication for different MPI communication patterns (e.g., point-to-point, collective operations) across various network configurations. The student will explore optimization techniques, such as non-blocking communication, advanced MPI features, and network optimizations, and assess their impact on the overall application performance.

The work will involve running MPI applications on multiple testbed systems, including both smaller clusters and large-scale HPC environments, and measuring the performance improvements (in terms of execution time, bandwidth utilization, and scaling). The student will also explore the impact of different interconnects (e.g., InfiniBand, Ethernet) and their role in enabling or limiting effective overlap.

**Skills required**:
- Strong understanding of MPI programming and parallel computing
- Proficiency in C/C++ programming

<b>Approximate composition:</b> 25% State of the art analysis, 25% Theory/Design, 50% Implementation/Experiments  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1533749047139-189de3cf06d3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8Y2xvY2t8ZW58MHx8MHx8fDI%3D" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
