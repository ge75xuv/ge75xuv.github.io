---
layout: page
title: Reinforcement Learning for Drone Racing
description: My colleague and I developed two different approaches for a drone racing challenge, where the drone needs to go through the gates and avoid obstacles. He focused on automatic and smart ways to generate a drone trajectory, where I tried to improve the performance under unknown dynamics or noise using a shared control approach. I trained an RL agent using the progress reward for path planning and used the convex combination of the precalculated trajectory and RL agent.
img: assets/img/Figure_wp.png
importance: 1
category: work
related_publications: false
---

[GitHub Repository](https://github.com/ge75xuv/lsy_drone_racing)

This project explores robust drone racing under uncertain dynamics by combining trajectory priors with reinforcement learning.
The figures below summarize the approach and results.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Figure_wp.png" title="Drone racing method overview" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Figure_wp2.png" title="Training and control pipeline" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Figure_wp3.png" title="Qualitative and quantitative results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The drone trajectory from different perspectives under modelling mismatch and measurement noise.
</div>
