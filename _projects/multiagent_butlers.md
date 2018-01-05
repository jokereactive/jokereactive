---
layout: page_project
name: Multi-Agent Path Planning in Warehouse Butlers
intro: Artificial Intelligence
teamsize: 2
teammembers: Anchita Goel
guide: Dr. Sandip Aine
course: Artificial Intelligence
projectimage: mapp.png
weight: 6
reference: http://sarthakahuja.org/public/docs/report_multiagent.pdf
category: Research
code: https://github.com/jokereactive/MAPP-Warehouse-Butlers
database: 
demo:
slides: 
poster: 
special:
technology: Java AWT, Java Graphix, Multi-Agent A Star, 
period: Aug'15-Dec'15
excerpt: 
---
The boom in the e-commerce industry has lead to the cropping up of a large number of
warehouses all over the globe. Automating the delivery processes in these warehouses is a growing
requirement to achieve a reduced cost in terms of manpower and increased efficiency in terms
of time taken. Multi-agent path planning is a crucial aspect of this challenge.
Naive approaches such as a complete A* over all combination of butlers and targets do not
work in this case due to the huge statespace and neither does Local Repair A*
where each butler selfishly moves toward the target and replans only on collision in a
blindfolded manner. In this project we have implemented the MAPP algorithm and prepared a Simulation
bench to run any placement of walls, butlers and items, by hacking an opensource version of pacman.
We evaluate multiple simulations of butlers and warehouse architectures, and detail our observations on the same.