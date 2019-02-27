1. Select all the true statements below.
> Weighted networks are used to describe networks with unequal relationships between nodes.
> When there are only two opposite relationships between nodes, a signed network is a good representation.

2. A network that has parallel edges (a pair of nodes with different types of concurrent relationships) is called a ________.
> Multigraph

3. Suppose we want to plot a network representing a small food web for students in a biology class. In order to give them a better understanding of the network, we want to show who is the predator and who is the prey. For those predators who have multiple options for prey, we also want to represent the predator’s preferences (i.e. which prey it likes most or second most). Choose the most appropriate type of network.
> Directed Weighted Network

4. Select all true statements:
> Edges can carry many labels or attributes.
> Suppose we have created a nx.Graph()object G with some nodes and edges. The statement G.nodes(data=True) will return a list of tuples.
> Accessing node or edge attributes in NetworkX is the same as accessing values in a Python dictionary

5. Based on the following lines of code, what is the type of G.edge['A']['C']?
> Dictionary

6.Based on the following lines of code, what's the correct statement to access the edge attribute "friend"?
> G.edge['A']['B'][0]['relation']

7. After all lines of code below are executed, what is(are) the role(s) of node A?
> Team member

8. Based on the bipartite network below, select all the edges you can add to the network while maintaining its bipartite structure.
> (1, B)
> (3, E)

9. Based on the bipartite network below, which of the following is the bipartite projection of the graph onto the set of circle nodes?
> D

10. Based on this bipartite network, suppose you create a weighted bipartite projection of the graph onto the set of square nodes.
What is the weight of edge AC in the projection graph?
> 3