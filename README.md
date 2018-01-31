# structural-entropy-minimisation and modularity-maximisation
greedy algorithm for structure information minimisation and modularity maximisation
example
java -jar structureinfo.jar xxx/xxx/xxx/graph

graph is the input of this algorithm. The format is
3
1 2 1.0
1 3 2.0
2 3 3.0
The first line is the number of nodes of the graph
The second line is the edge: first_node_id second_node_id weight
.splitted by space. The node_id start from 1.

resultfile (graph.deDoc(E)community or graph.deDoc(M)community) is the result of communities found by algorithm deDoc(E) or deDoc(M). Each line is a community.


first of all, you need to change the name of file structureinfo.jar.txt and modularity.jar.txt to structureinfo.jar and modularity.jar.
