---
layout: page_project
name: Dynamic Particle Allocation to Solve Interactive POMDP Models for Social Decision Making 
intro: Collaborative Cognition
teamsize: 7
teammembers: Ramasuri Narayanam, Surya Shravan Kumar Sajja, Ritwik Chaudhuri, Rohith Vallam, Kushal Mukherjee, Gyana Parija
guide:
course:
_url: 
projectimage: cc.png
weight: 0.2
category: Research
reference: http://www.ifaamas.org/Proceedings/aamas2019/pdfs/p674.pdf
code:
database: 
slides: 
poster: 
demo: 
special: Work published at at AAMAS 2019. Multiple invention disclosures filed at USPTO.
technology: I-POMDPs, Interactive Particle Filters, SOAR, AnyLogic
period: July'16-July'18
excerpt:
published: 
 - Dynamic Particle Allocation to Solve Interactive POMDP Models for Social Decision Making (AAMAS 2019)
patented: 
 - SIdeal - System and Method for Attribute Weight Induction in a Multiple Recruiter Setting Exploiting Public Goods Games Framework
---
In repeated social dilemma settings, such as repeated Public Goods Games (PGG), humans often come across a dilemma whether to contribute or not based on past contributions from others. In such settings, the decision taken by an agent/human actually depends not only on the belief the agent has about other agents and the environment, but also on their beliefs about others’ beliefs. To factor in these aspects, we propose a novel formulation of computational theory of mind (ToM) to model human behavior in a repeated PGG using interactive partially observable Markov decision processes (I-POMDPs). Interactive particle filter (IPF) is a well known algorithm used to approximately solve I-POMDP models for the agents to find their optimal contributions. Number of particles assigned to an agent in IPF can be translated into time and computational resources. Solving I-POMDPs in a time-memory efficient manner even in the case of small state spaces is a largely intractable problem. Also, maintaining a fixed number of particles assigned to each agent, over time, will be highly inefficient in terms of resource utilization. To address this problem, we propose a dynamic particle allocation algorithm for different agents based on how well they could predict. We validate our proposed algorithm through real experiments involving human agents. Our results suggest that dynamic particle allocation based IPF for I-POMDPs is effective in modelling human behaviours in repeated social dilemma setting while utilizing computational resources in an effective manner.
