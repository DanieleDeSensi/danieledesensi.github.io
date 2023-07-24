---
layout: page
title: "🗜️ Compressed Collectives on NVIDIA BlueField NICs"
description: 
img: https://images.unsplash.com/photo-1558494949-ef010cbdcc31?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1934&q=80
importance: 2
category: Available Thesis
related_publications: 
---

Collective operations are a fundamental building blocks of distributed applications. They are used to aggregate, distribute, or collect data from multiple nodes, and are used in many applications, including machine learning, graph analytics, and distributed storage systems. To improve the performance of such critical operations, one possibiliy is to offload their processing to Smart Network Interface Card (SmartNICs). SmartNICs are network devices that allow to run user-defined programs directly on the network card, and are becoming increasingly popular in datacenters [1]. The most widely used commercial SmartNIC is the NVIDIA BlueField [2]. 

In this thesis, the student will design and implement a new collective operation library for NVIDIA BlueField NICs. The library will be designed to support different compression techniques (e.g., quantization and sparsification), and will be evaluated on a real testbed. Experiments will be carried on to compare the performance with host-based solutions.
The thesis will be tailored on the student’s expertise, skills, and preferences. Depending on the thesis direction and on preliminary results, part of the work and/or its follow-ups can be done in collaboration with NVIDIA.

<b>Approximate composition:</b> 20% State of the art analysis, 20% Theory/Design, 60% Implementation/Experiments

[1] <a href="https://arxiv.org/abs/2212.07868">Characterizing Off-path SmartNIC for Accelerating Distributed Systems</a><br>
[1] <a href="https://www.nvidia.com/en-us/networking/products/data-processing-unit/">NVIDIA BlueField Data Processing Units</a><br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1934&q=80" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


