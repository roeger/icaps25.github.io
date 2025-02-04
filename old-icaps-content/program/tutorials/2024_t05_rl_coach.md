---
title: "Tutorial 05 - Orchestrating autonomous agents: Reinforcement Learning To Hierarchical Planning with COACH"
date: 2024-04-16
draft: false
---
# Tutorial 05 - Orchestrating Autonomous Agents: Reinforcement Learning for Hierarchical Planning with COACH

## Abstract

This tutorial will provide an introduction to [COACH](https://github.com/act3-ace/coach) - a suite of Python tools for 
recasting [Gymnasium](https://gymnasium.farama.org/index.html) and 
[PettingZoo](https://pettingzoo.farama.org/index.html)-compatible Multi-Agent Reinforcement Learning (MARL) problems as 
orchestration-style planning problems. Traditional Reinforcement Learning (RL) focuses on training low level agents to
interact with an environment in a high frequency feedback loop. Once policies have been trained, human direction becomes 
an orchestration problem, especially with large numbers of agents. COACH provides tools for researchers to bridge this 
gap: given any simulation compatible with Gymnasium or PettingZoo, trained agents can be set up to interface with a 
director agent who tackles high level scheduling, policy selection, or coordination for generating autonomously executed 
plans. COACH was created in association with the US Air Force Research Laboratory’s Autonomy Capability Team (ACT3).

## Resources

- [Tutorial Website](https://github.com/act3-ace/coach/blob/main/docs/icaps.md)

## About the authors

**Nate Bade** is an award-winning educator and former teaching professor and program director of the MS in Applied 
Mathematics (MSAM) program at Northeastern University. He specialized in project based education and designed the
MSAM’s graduate machine learning program. He is currently a Senior Data Scientist at Mobius Logic and works in 
coordination with ACT3 on hierarchical methods in multi-agent reinforcement learning and automated planning.
