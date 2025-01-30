---
title: 'Timely and Energy-Efficient Multi-Step Update Processing'
authors:
- Vishakha Ramani
- Ivan Seskar
- Roy D. Yates

date: '2024-11-29'
publishDate: '2024-11-29T17:10:02.240565Z'
publication_types:
- paper-conference
publication: '*(ACSSC 2024) 2024 Asilomar Conference on Signals, Systems, and Computers*'

abstract: This work explores systems where source updates require multiple sequential processing steps. We model and analyze the Age of Information (AoI) performance of various system designs under both parallel and series server setups. In parallel setups, each processor executes all computation steps with multiple processors working in parallel, while in series setups, each processor performs a specific step in sequence. In practice, processing faster is better in terms of age but it also consumes more power. We identify the occurrence of wasted power in these setups, which arises when processing efforts do not lead to a reduction in age. This happens when a fresher update finishes first in parallel servers or when a server preempts processing due to a fresher update from preceding server in series setups. To address this age-power trade-off, we formulate and solve an optimization problem to determine the optimal service rates for each processing step under a given power budget. We focus on a special case where updates require two computational steps.
tags:
- information thoery
links:
- name: URL
  url: https://arxiv.org/abs/2411.19854
---
