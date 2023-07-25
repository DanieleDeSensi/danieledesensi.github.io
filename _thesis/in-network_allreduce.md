---
layout: page
title: "➕ In-network Allreduce"
description: 
img: https://images.unsplash.com/photo-1506399309177-3b43e99fead2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1468&q=80
importance: 1
category: Available Thesis
related_publications: flare, hxmesh
---

The allreduce operation is one of the most commonly used communication routines in distributed applications. In this operation, vectors coming from different nodes need to be aggregated element-wise (e.g., by summing elements), and the result distributed back to all the nodes. Estimations show up to 40% of the time spent in the training of large-scale machine learnign models is spent performing this operation [1]. To improve its bandwidth and the performance of applications using it, this operation can be accelerated by offloading it to network switches. Instead of sending data back-and-forth between nodes, data is aggregated directly inside the network switches. It has been shown that by doing so, performance of the allreduce can be improved by up to 2x.

In this thesis the student will design more efficient in-network allreduce solutions, and implement/evaluate them on a simulator (to be evaluated together, some possibilities are: NS-3 [2], htsim [3], AstraSim [4]). The thesis will be tailored on the student’s expertise, skills, and preferences.

[1] <a href="https://www.usenix.org/conference/nsdi23/presentation/wang-weiyang">Weiyang Wang et al. "TopoOpt: Co-optimizing Network Topology and Parallelization Strategy for Distributed Training Jobs"</a><br>
[2] <a href="https://www.nsnam.org/">NS-3</a><br>
[3] <a href="https://github.com/kellianhunt/htsim">htsim</a><br>
[4] <a href="https://github.com/astra-sim/astra-sim">AstraSim</a><br>
 
<b>Approximate composition:</b> 10% State of the art analysis, 30% Theory/Design, 60% Implementation/Experiments

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1506399309177-3b43e99fead2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1468&q=80" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>