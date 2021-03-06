---
layout: post
title: "My Ph.D. defense presentation"
date: 2017-04-13
---

<h2>Biologically Inspired Adaptive Optimal Control and Learning</h2>

#### Background: Reinforcement learning (RL) and adaptive dynamic programming (ADP)

- What is RL?

<p align="center">
<img src="/images/RL.pdf" width="60%">
</p>

> "Reinforcement" is a form of learning in which "an element, $$X$$, of the behavior" of an object, $$M$$, is caused to become more (or less!) "prominent" in the future behavior of $$M$$ as a result of the "activation" of a special entity or process, $$Z$$, called the "reinforcement operator !") within a (relatively) short time after an occurrence of $$X$$. 
>
> -- <cite> Minsky. Theory of neural-analog reinforcement systems and its application to the brain model problem, 1954. </cite>

> Reinforcement learning is learning what to do--how to map situations to actions--so as to maximize a numerical reward signal. 
>  
> -- <cite> Sutton and Barto. Reinforcement Learning: An Introduction, 1998. </cite>

- From RL to ADP

  Drawbacks of RL:

  -   Not applicable to dynamical systems (continuous-state-action space).

  -   The stability issue is usually overlooked.

  A solution:

  <p align="center">
  <img src="/images/ADP.pdf" width="40%">
  </p>

  Adaptive dynamic programming (ADP) aims at finding a stabilizing optimal control policy for dynamical systems via online learning.





For more details, see my Ph.D. defense presentation [here](/images/PhD_defense_Tao_Bian.pdf)
