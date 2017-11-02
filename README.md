# structural-information-minimisation and modularity-maximisation
greedy algorithm for structure information minimisation and modularity maximisation
example
java -jar structureinfo.jar xxx/xxx/xxx/graph

graph is the input of this algorithm. The format is
3
1 2 1.0
1 3 2.0
2 3 3.0
The first line is the number of nodes of the graph
The second line is the edge: first_node_id second_node_id weight, splitted by space. The node_id start from 1.

resultfile (graph.Ecommunity or graph.Mcommunity or graph.Qcommunity) is the result of communities found by algorithm Dedoc(E), Dedoc(M) or CNM. Each line is a community.

The same to modularity maximisation algorithm
java -jar modularity.jar xxx/xxx/xxx/graph

first of all, you need to change the name of file structureinfo.jar.txt and modularity.jar.txt to structureinfo.jar and modularity.jar.
