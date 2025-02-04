---
title: "Tutorial 03 - A Hands-On Tutorial on scikit-decide, the Open-Source C++ and Python Library for Planning, Scheduling and Reinforcement Learning"
date: 2024-04-16
draft: false
---

# Tutorial 03 - A Hands-On Tutorial on scikit-decide, the Open-Source C++ and Python Library for Planning, Scheduling and Reinforcement Learning 

## Abstract

Scikit-decide is an open-source library for modeling and solving planning, scheduling and
reinforcement learning problems within a common API which helps break technical silos between different
decision-making communities and enables seamless benchmarking of different approaches. For instance,
one can solve PDDL problems with both classical planning (via a bridge to Unified Planning) and reinforcement
learning (via a bridge to RLlib) solvers with very few lines of code, and compare the different
solutions. Thinking of both algorithm providers and solver users, the library’s class hierarchy has been
designed to ease the integration of new domains and algorithms depending on their distinctive features
(e.g. partially vs fully observable states, deterministic vs probabilistic state transitions, single vs multi
agents, simulation-based vs formal transition models, etc.). With more than 125k total downloads and
200 downloads per day on PyPi, the library is gaining traction in the global sequential decision-making
landscape, including practitioners and researchers. It is officially sponsored by ANITI (the Artifical and
Natural Intelligence Toulouse Institute) and is the main host for the research algorithms produced in the
Horizon Europe’s TUPLES project (Trustworthy Planning and Scheduling with Learning and Explanations).
The half-day tutorial will show how to model and solve the same problems using algorithms from
different communities, and how to extend the libraries with new domains and solvers in a few lines of
code. It will alternate presentations and live Python coding sessions

## Official Website and Auxiliary Materials

- [Tutorial Website](https://fteicht.github.io/icaps24-skdecide-tutorial/)

## About the authors

**Florent Teichteil-K&ouml;nigsbuch** is an expert in AI Decision-Making and Combinatorial Optimization
in Airbus Central Research and Technology. After graduating as a PhD in Artificial
Intelligence from the University of Toulouse and SUPAERO in 2005, he worked in ONERA as
a research scientist in Robotics and Artificial Intelligence from 2005 to 2015. He then joined
Airbus as a senior data scientist and research project leader working on bringing decisionmaking
research to various industrial aerospace use cases. He has published several conference
and journal papers on AI decision-making and autonomous robotics. He is collaborating with
ANITI on combinatorial optimization topics, and is also coordinating the industrial integration
of the research conducted in the European Project TUPLES on Trustworthy Decision-Making.
Florent is one of the main constributors of the scikit-decide library, especially working on the
C++ core functions and on the classical planning and search engines.

[Link to DBLP profile](https://dblp.org/pid/70/1418.html)

**Alexandre Arnold** is an AI Senior Research Scientist working at Airbus Central Research
and Technology in the Artificial Intelligence domain. He is an expert in Reinforcement Learning
(an Automated Decision Making technique) and has also been involved in multiple projects
related to Natural Language Processing, including as research project leader for LEA (LEarning
Assistant) to ease the creation of customized chatbots. Today he is interested in pushing
RL and NLP beyond state of the art and finding synergies across these fields, typically towards
training adaptive and communicative robots. He is collaborating on such topics with other
researchers from academia and industry in the frame of ANITI (Artificial and Natural Intelligence
Toulouse Institute), specialized in mobility/transport and robotic/cobotic applications.
Alexandre is one of the main contributors to the core of the scikit-decide library and to the
RL interfaces.

[Link to DBLP profile](https://dblp.org/pid/137/8257.html)

**Guillaume Pov&eacute;da** is a research engineer in Airbus Central Research and Technology. After
an aerospace engineering school, and a research degree in operational research, Guillaume has
been working for Airbus in various topics involving sequential decision-making and scheduling
topics. Guillaume has used a wide range of techniques to solve complex problems, from classical
optimization techniques to more learning approaches, which have been published in the ICAPS
and CP conferences. Guillaume is involved in 2 open source libraries developed by Airbus:
scikit-decide as an active contributor and discrete-optimization as main developer, the latter
being used as the core scheduling engine in scikit-decide.

[Link to DBLP profile](https://dblp.org/pid/244/0529.html)

**Sylvie Thi&eacute;baux** is a professor of computer science at the Australian National University
and a directrice de recherche at the University of Toulouse. Her research interests are in
artificial intelligence, in particular automated planning, scheduling, diagnosis, and search, their
integration with optimisation, machine learning, and verification, as well as their applications
to energy and transport. She is the coordinator of the European Project TUPLES whose aim
is to facilitate the construction of trustworthy planning and scheduling systems, which are safe,
robust, explainable and scalable. Sylvie is a fellow of the Association for the Advancement
of Artificial Intelligence (AAAI) and a co-editor in chief of the Artificial Intelligence journal.
She is a former councilor of AAAI, co-chair and president of the International Conference on
Automated Planning and Scheduling (ICAPS).

[Link to DBLP profile](https://dblp.org/pid/64/3102.html)
