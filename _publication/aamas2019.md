---
layout: page_publication
name: Dynamic Particle Allocation to Solve Interactive POMDP Models for Social Decision Making
type: paper
authors: Rohith D Vallam, Sarthak Ahuja, Surya Shravan Kumar Sajja, Ritwik Chaudhuri, Rakesh R Pimplikar, Kushal Mukherjee, Gyana Parija, Ramasuri Narayanam
track: Research Track
submission: Full Research Paper
acceptance: Published
_url: http://aamas2019.encs.concordia.ca/
project_url: 
thumbnail_url: thumbnail_aamas2019.png
type: conference
conference_url: http://aamas2019.encs.concordia.ca/
venue: AAMAS
projectimage: sample.png
weight: 1
reference: 
code:
slides: 
poster: 
database: 
demo: 
special: 
year: 2019
excerpt: Additional content
---
In repeated social dilemma settings, such as repeated Public Goods Games (PGG), humans often come across a dilemma whether to contribute or not based on past contributions from others. In such settings, the decision taken by an agent/human actually depends not only on the belief the agent has about other agents and the environment, but also on their beliefs about others’ beliefs. To factor in these aspects, we propose a novel formulation of computational theory of mind (ToM) to model human behavior in a repeated PGG using interactive partially observable Markov decision processes (I-POMDPs). Interactive particle filter (IPF) is a well known algorithm used to approximately solve I-POMDP models for the agents to find their optimal contributions. Number of particles assigned to an agent in IPF can be translated into time and computational resources. Solving I-POMDPs in a time-memory efficient manner even in the case of small state spaces is a largely intractable problem. Also, maintaining a fixed number of particles assigned to each agent, over time, will be highly inefficient in terms of resource utilization. To address this problem, we propose a dynamic particle allocation algorithm for different agents based on how well they could predict. We validate our proposed algorithm through real experiments involving human agents. Our results suggest that dynamic particle allocation based IPF for I-POMDPs is effective in modelling human behaviours in repeated social dilemma setting while utilizing computational resources in an effective manner.
