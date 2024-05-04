---
title: Timeliness in shared-memory updating systems
date: 2024-03-23
show_date: false
authors: ["ramani","yates"]
---

**Researchers:** Vishakha Ramani, Roy D. Yates

We consider systems in which source updates require multiple sequential processing stages. We identify, model, and analyze various system designs for processing source updates, considering factors such as the number of processors deployed, communication mechanisms between processors, and energy consumption constraints.

<!-- more -->

These designs fall into two main categories: parallel processors, where multiple processors execute all computation steps in parallel, and pipeline configurations, where each processor performs a step in the update processing. In both setups, wasted power can occur when processing updates that don't reduce age. This happens when a fresher update finishes first in parallel servers or when a server preempts processing due to a fresher update in pipeline setups. Each scheduling strategy presents an age/power trade-off, which we analyze for average age at the monitor versus power consumed by the processors.

