---
title: Timely Offloading of Inferences in Mobile Edge Cloud Systems
date: 2024-03-23
show_date: false
authors: ["sathyavageeswaran","sarwate",
yates"]
---

**Researchers:** Nitya Sathyavageeswaran, Anand D. Sarwate, Narayan B. Mandayam, Roy D. Yates

Future real-time applications like smart cities will use complex Machine Learning (ML) models for a variety of tasks. Timely status information is required for these applications to be reliable. Offloading computation to a mobile edge cloud (MEC) can reduce the completion time of these tasks. However, using the MEC may come at a cost such as related to use of a cloud service or privacy.
<!-- more -->

We consider a source that generates time-stamped status updates for delivery to a monitor after processing by the mobile device or MEC. We study how a scheduler must forward these updates to achieve timely updates at the monitor but also limit MEC usage. We measure timeliness at the monitor using the age of information (AoI) metric. We formulate this problem as an infinite horizon Markov decision process (MDP) with an average cost criterion. We prove that an optimal scheduling policy has an age-threshold structure that depends on how long an update has been in service.

