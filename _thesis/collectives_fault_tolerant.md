---
layout: page
title: "🔧 Fault-Tolerant Collective Operations"
description: 
img: https://images.unsplash.com/photo-1610056494085-05e9fb6673ee?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8ZGlzY29ubmVjdHxlbnwwfHwwfHx8Mg%3D%3D
importance: 1
category: Available Thesis
---

In distributed systems, collective operations are essential for communication and data aggregation across multiple nodes, such as in applications like machine learning, scientific simulations, and distributed databases. However, as systems scale up to accommodate larger workloads, the frequency of faults—such as node crashes or communication link failures—inevitably increases. This can disrupt the consistency and reliability of the entire system, making it crucial to ensure that collective operations remain robust even in the presence of failures.

In this thesis, the student will explore fault-tolerant strategies for collective operations in large-scale distributed systems. The thesis will focus on designing, implementing, and evaluating fault-tolerant algorithms for collective operations such as allreduce, broadcast, and gather. As systems scale, the risk of failures increases, and the ability to recover efficiently becomes even more important. The proposed solutions could leverage techniques such as redundancy, checkpointing, and recovery mechanisms to handle failures during collective communication and ensure system resilience.

The student will implement these fault-tolerant collective operations in an MPI-based system (e.g., MPICH or OpenMPI), and evaluate them in terms of performance, fault recovery time, and overall system resilience. The work will also include analysis of how the frequency and impact of failures scale with system size, as well as the trade-offs between fault tolerance and performance in large-scale environments.

**Skills required**:
- Knowledge of MPI or other distributed communication libraries
- Basic understanding of high-performance computing (HPC)

[1] <a href="https://www.sciencedirect.com/science/article/pii/S1877050920302130">Fault Tolerant Collective Communication in Distributed Systems</a><br>
[2] <a href="https://www.open-mpi.org/">Open MPI</a><br>

<b>Approximate composition:</b> 20% State of the art analysis, 30% Theory/Design, 50% Implementation/Experiments  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1610056494085-05e9fb6673ee?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8ZGlzY29ubmVjdHxlbnwwfHwwfHx8Mg%3D%3D" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
