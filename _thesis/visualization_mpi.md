---
layout: page
title: "🎥 Dynamic Visualization of MPI Traces"
description: 
img: https://images.unsplash.com/photo-1639322537228-f710d846310a?q=80&w=2532&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
importance: 1
category: Available Thesis
---

Understanding the communication patterns in MPI applications is crucial for diagnosing performance bottlenecks and optimizing execution. However, static visualization methods often fail to capture the dynamic nature of communication, especially in large-scale systems. A more interactive and dynamic approach to visualizing MPI traces can provide deeper insights into communication behavior.

In this thesis, the student will design and implement a dynamic visualization tool for MPI communication traces. Each MPI rank will be represented as a node in a fully connected graph, and the edges (links) will change color dynamically over time based on the communication intensity between two ranks. The color scale will reflect the traffic volume (e.g., bytes sent/received), providing a real-time view of communication hotspots and imbalances. This work will build upon an existing tool for visualizing dynamic data traffic [2] and adapt it to the specific requirements of MPI applications. The tool will be evaluated on a variety of MPI applications and traces (bot publicly available and gathered during the internship), with a focus on its ability to identify communication hotspots and provide actionable insights.

**Skills required**:
- Knowledge of MPI, C/C++, and Python


[1] <a href="https://images.unsplash.com/photo-1639322537228-f710d846310a?q=80&w=2532&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">Intel MPI Tools</a><br>
[2] <a href="https://github.com/FrancescoPannozzo/network_traffic_visualizer"> Network Traffic Visualizer</a><br>

<b>Approximate composition:</b> 20% State of the art analysis, 30% Design/Development, 50% Implementation/Experiments  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="https://images.unsplash.com/photo-1519389950473-47ba0277781c?q=80&w=1930&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
