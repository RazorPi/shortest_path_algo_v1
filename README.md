# shortest_path_algo
Module 2 / Problem 2: Learn Regular algorithm design by creating a shortest path algo. This is part of the Scientific Computing with Python by Free Code Camp.

**Personal note:** __This is one of the most, if not the most, challenging problems to solve. It has the challenge of solving the code and adds the complexity of understanding algorithms. It's crazy! Sometimes, I felt some of the questions made no sense at all, and somehow, I was expected to read between the lines and come up with a mathematical solution to something I still couldn't understand. Thankfully, I figured out most of the answers by following the comments in the 'help' section._ 


----
### ABOUT:

Graphs are data structures representing relations between pairs of elements. These elements, called nodes, can be real-life objects, entities, points in space, or others. The connections between the nodes are called the edges.
Here's a visual representation of a graph:


![graph1-example](https://github.com/user-attachments/assets/3e26a2a0-ef52-49ea-900d-4b1e857b3cdf)

A graph is called a __weighted_ graph when its edges are associated with weights, representing a distance, time, or other quantitative value.
In this case, these weights will be the distances between each **node** or point in space. To represent a weighted graph, you can modify your dictionary using a list of tuples for each value.

The first element in the tuple will be the connected node, and the second element will be an integer number indicating the distance.

### For example: 
**my_dict = {'A': ('B', 5)}**   where **A** is the _NODE_ and **5** is the distance from A to B.

