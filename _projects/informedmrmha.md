---
layout: page_project
name: Informed Multi-Heuristic Multi-Representation A-Star
intro: Planning
teamsize: 4
teammembers: Aditya Agarwal, Shivam Vats, Jay Patrikar
guide:
course:
_url: 
projectimage: informedmrmha.png
weight: 0.6
category: Research
reference: http://sarthakahuja.org/public/docs/report_informedmrmha.pdf
code:
database: 
slides: 
poster: 
demo: https://www.youtube.com/watch?v=1qIXPbPmPNw&feature=youtu.be
special:
technology: Multi-Heuristic Multi-Representation A-Star, Learning Methods for Planning, Conditional Variational Auto-Encoders
period: Aug'19 - Dec'19
excerpt:
published:
patented: 
---
Generating motion plans for robots, like humanoids, with many degrees of freedom is a challenging
problem because of the high-dimensionality of the resulting search space. To circumvent this, many researchers have made the observation that large parts of the solution plan are often much lower dimensional in nature. Some recent algorithms exploit this by either planning on a graph with adaptive dimensionality or leveraging a decoupling in the robot’s action space. Often, it is possible to gain more fine-grained information about the local dimensionality of the plan from any robot state to the goal which can then be used to inform search. In this work, we present a heuristic-search-based planning algorithm that admits such information as a prior in the form of lower dimensional manifolds (called representations) and a probabilistic mapping (conditioned on the world and the goal) from robot states to these representations. We train a Conditioned Variational Autoencoder (CVAE) for every representation and use them to compute the required probabilitic mapping. Using this additional domain knowledge, our motion planner is able to generate high quality bounded-suboptimal plans. Experimentally, we validate the practicability and efficiency of our approach on the challenging 10 degree-of-freedom mobile manipulation domain.