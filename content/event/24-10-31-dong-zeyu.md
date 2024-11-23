---
title: Generalizing End-To-End Autonomous Driving In Real-World Environments Using Zero-Shot LLMs

summary: Zeyu Dong  (Stony Brook University)
location: 203 of Busch Campus of Rutgers & Zoom
abstract: ''

date: '2024-10-31T13:00:00Z'
date_end: '2024-10-31T14:00:00Z'

##### this gives the sort order
publishDate: '2024-10-31T12:00:00Z'

authors: []
tags: []
---

The talk was on Zoom: Recording [link here](https://rutgers.zoom.us/rec/share/cGH77gJCjE0dKtWsXWrjpOhLgfkTmGgOr0RVp-qydOuKRdeFKTF10jz7TW349csC.KHdJBAXBneSg5tju?startTime=1730394399000). Passcode: 7W2IN^J0

**Abstract:** Traditional autonomous driving methods adopt a modular design, decomposing tasks into sub-tasks, including perception, prediction, planning, and control. In contrast, end-to-end autonomous driving directly outputs actions from raw sensor data, avoiding error accumulation. However, training an end-to-end model requires a comprehensive dataset. Without adequate data, the end-to-end model exhibits poor generalization capabilities. Recently, large language models (LLMs) have been applied to enhance the generalization capabilities of end-to- end driving models. Most studies explore LLMs in an open-loop manner, where the output actions are compared to those of experts without direct activation in the real world. Other studies in closed-loop settings examine their results in simulated environments. In comparison, this paper proposes an efficient architecture that integrates multimodal LLMs into end-to-end real-world driving models in a closed-loop setting. The LLM periodically takes raw sensor data to generate high-level driving instructions. In our architecture, LLMs can effectively guide the end-to-end model, even at a slower rate than the raw sensor data, because updates aren’t needed every time frame. This architecture relaxes the trade-off between the latency and inference quality of the LLM. It also allows us to choose from a wide variety of LLMs to improve high-level driving instructions and minimize fine-tuning costs. Consequently, our architecture reduces the data collection requirements because the LLMs do not directly output actions, and we only need to train a simple imitation learning model to output actions. In our experiments, the training data for the end-to-end model in a real-world environment consists of only simple obstacle configurations with one traffic cone, while the test environment is more complex and contains multiple obstacles placed in various positions. Experiments show that the proposed architecture enhances the generalization capabilities of the end-to-end model even without fine-tuning the LLM.
**Short Bio:** 
Zeyu Dong is a PhD candidate in Applied Math & Statistics at Stony Brook University, advised by Prof. Dantong Yu. His research centers on deep learning and computer vision method in robotics and control. Particularly, he focuses on generalization and domain adaptation in end-to-end autonomous driving. Zeyu has published in top-tier conferences, including CoRL 2024. He also serves on the review boards of ICLR 2025, IEEE BigData 2024, and IIKI 2024. Prior to his PhD, he earned his B.S. in Mathematics from the Southern University of Science and Technology (SUSTech) in 2020.
