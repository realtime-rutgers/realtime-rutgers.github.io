---
title: Bayes-Optimal, Robust, and Distributionally Robust Policies for Uncertain MDPs

summary: Jack Yansong Li  (University of Illinois Chicago)
location: 203 of Busch Campus of Rutgers & Zoom
abstract: ''

date: '2024-08-22T13:00:00Z'
date_end: '2024-08-22T14:00:00Z'

##### this gives the sort order
publishDate: '2024-08-13T12:00:00Z'

authors: []
tags: []
---

The talk will be on Zoom: [link here](https://rutgers.zoom.us/j/91620503329?pwd=Wm1GVFQvMlNsQjJGVkc2a0QyVVRKZz09).

**Abstract:** We explore the performance of different policy-making strategies within the frame work of uncertain Markov decision processes (uMDPs). In an uMDP, the agent interacts with an MDP that is sampled from the uncertainty set based on a distribution, referred to as the true prior distribution. We analyze the performance of Bayes-optimal, robust, and distributionally robust policies. Bayes-optimal policies aim to maximize expected rewards based on a given subjective prior distribution over the uncertainty set. Robust policies are designed to perform well under the worst-case scenarios across all possible MDPs. Distributionally robust policies combine elements of Bayes-optimal policies and robust policies, seeking to perform optimally across a neighborhood of a given subjective prior distribution. We test these policies in scenarios where the subjective prior is either an estimate of the true prior or manually chosen, such as uniform or Dirichlet distributions. Our findings indicate that no subjective prior can guarantee that a Bayes-optimal policy under that subjective prior will consistently outperform robust policies. Thus, manually choosing a subjective prior, such as a uniform distribution commonly used in many applications, may result in poor performance for Bayes-optimal policies compared to robust policies. Furthermore, we show that, for any estimated subjective prior with a non-zero estimation error, robust policies can still outperform Bayes-optimal policies under certain uMDPs. Additionally, we find that distributionally robust policies, which integrate the advantages of both robust and Bayes-optimal approaches, typically yield superior performance, particularly when the subjective prior closely approximates the true prior distribution. These theories are empirically validated through experiments conducted in a simulated highway driving environment.
**Short Bio:** 
[Jack Yansong Li](https://jackyansongli.github.io/docs/main.html) is a Ph.D. candidate in the [Electrical and Computer Engineering Department at the University of Illinois Chicago](https://ece.uic.edu). He is very fortunate to be advised by Prof. Shuo Han. He received my bachelors in [Department of Mathematics at the Southern University of Science and Technology](https://math.sustech.edu.cn/?lang=en). His primary research interests lie in reinforcement learning and game theory. Currently, he is working on combining model-based RL with model-free RL. Previously, I have worked on projects that examines optimization techniques for Stackelberg games.
