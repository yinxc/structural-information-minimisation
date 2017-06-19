# structural-information-minimisation
greedy algorithm for two dimensional structural information minimisation
example
java -jar sim.jar inputgraph outputfile

inputgraph is the input of this algorithm. The format is
3
1 2 1
1 3 2
2 3 3
The first line is the number of nodes of the graph
The second line is the edge: first_node_id second_node_id weight, splitted by space. The node_id start from 1.

outputfile is the result of communities found by this algorithm. Each line is a community
