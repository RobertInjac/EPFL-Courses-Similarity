## Calculating similarity between EPFL courses and using it to build a graph
__Master's project at École Polytechnique Fédérale de Lausanne (EPFL)__

__Author: Robert Injac__

__Supervisors: [Francisco Pinto](https://people.epfl.ch/francisco.pinto) and [Patrick Jermann](https://people.epfl.ch/patrick.jermann)__

---

In this project, I developed a method for establishing similarity/relatedness between two EPFL courses. I use this method to construct a graph of related EPFL courses. In the graph, the nodes are the courses, and there is an edge between two nodes if those courses are related. The details of the similarity method used and graph construction are :
1. __similarity_method.ipynb__: pre-processing, establishing the similarity method, evaluation of the method
2. __creating_graph.ipynb__: using the method, graph creation

The notebooks contain descriptions, explanations and comments along with the code.

### Visualization

Visualization of the graph is available [here](https://rinjac.github.io/EPFL-courses-similarity/).

The code I used to make the visualization, which can be found in the _docs_ folder, __is not mine.__ It is a work of another EPFL student, Raphaël Steinmann, who had a project in graph visualization. His original code is available [here](https://github.com/rbsteinm/EPFL-Courses-Graph-Representation). I only tweaked a few things to fit in my graph.
