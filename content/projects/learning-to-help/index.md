---
title: Learning To Help - Training Models to Assist Legacy Devices
date: 2024-03-23
show_date: false
authors: ["wu","sarwate"]
---

**Researchers:** Yu Wu, Anand D. Sarwate 

Machine learning models implemented in hardware on physical devices may be deployed for a long time. The computational abilities of the device may be limited and become outdated with respect to newer improvements. Because of the size of ML models, offloading some computation (e.g. to a edge cloud) can help such legacy devices. We cast this problem in the framework of learning with abstention (LWA) in which the expert (edge) must be trained to assist the client (device).

<!-- more -->

Prior work on LWA trains the client assuming the edge is either an oracle or a human expert.
In this work, we formalize the reverse problem of training the expert for a fixed (legacy) client. As in LWA, the client uses a rejection rule to decide when to offload inference to the expert (at a cost).

We find the Bayes-optimal rule, prove a generalization bound, and find a consistent surrogate loss function. Empirical results show that our framework outperforms confidence-based rejection rules.
