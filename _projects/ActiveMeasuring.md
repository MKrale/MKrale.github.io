---
layout: page
title: Active Measuring
description: Solving partially observable environments with measuring actions
img: assets/img/Magnified.jpg
importance: 1
category: work
---

Ever wondered how often the engine of your car should really be checked on defects?
Or how often an electicity provider should check their cables to minimize both the chance of outages and their maintenance costs?
Or how often a drone should use it's battery-draining GPS-system to keep an accurate idea of it's positions?

All these questions can be formulated as *active measure* problems, or AM problems for short, in which agents need to determine whether the value of taking a measurement is worth it's cost.
Problems that contain partial observability, as is the case here, are often modeled as *partially observable Markov decision processes* (POMDPs), but these are generally hard to solve for larger real-life problems.
For this reason, we are interested in ways of moddeling AM problems in a way that makes solving them easier.

I currently have two papers related to active measuring:

* In our ICAPS 2023 paper, we propose the **act-then-measure** heuristic for finding (suboptimal) solutions for ACNO-MDPs, a subset of active measuring problems where measurements yield full state information. Based on this heuristic, we define a reinforcement learning method that outperforms existing methods.
* In our AAAI 2024 paper (as based on my master thesis), we consider active measuring in a setting with model uncertainty. We extend the act-then-measure heuristic to this environment, and investigate the effect misspecification of the model uncertainty on the performance of our policy.