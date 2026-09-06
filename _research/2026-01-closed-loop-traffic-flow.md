---
title: "PACT: Prediction--Action Coupled Traffic Coordination for Lifelong Multi-Robot Systems"
collection: research
permalink: /research/closed-loop-traffic-flow-action-aware-replanning/
period: "2026.01 - 2026.06"
status: "First-author manuscript submitted to IEEE Transactions on Systems, Man, and Cybernetics: Systems"
excerpt: "Closed-loop traffic-flow learning and action-aware replanning for scalable multi-robot path planning under distribution shift.<br/><img src='/images/pact.png'>"
---
### Abstract

Large-scale lifelong multi-robot systems require sustained throughput under evolving tasks, delays, and robot interactions. Existing congestion-aware methods commonly predict traffic before planning, although the selected actions subsequently reshape the predicted traffic. This paper presents Prediction--Action Coupled Traffic Coordination (PACT), a closed-loop framework that explicitly estimates post-decision traffic. PACT uses HimNetPro to provide a reliable nominal forecast and applies reference-policy differential refinement to obtain candidate-dependent post-decision traffic rollouts. It then approximates the dominant next-sector congestion coupling through increasing marginal slots and optimizes the resulting structured objective using minimum-cost flow. The optimized guidance is executed by H-PIBT, while traffic states and inter-sector travel times are fed back to subsequent decisions. Across 100--1000 robots, PACT improves throughput over the strongest external planning baseline by 5.2\%--9.7\% on den520d and 5.9\%--9.1\% on warehouse. Differential refinement consistently reduces post-decision prediction errors, demonstrating the value of coupling traffic prediction with candidate actions for long-term coordination at scale.
