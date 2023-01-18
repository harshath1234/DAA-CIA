# DAA-CIAPRIMS ALGORTIHM

The given problem cannot be solved using prims algorithm because it is a directed graph.
In Prims algorithm we consider graphs in which traversal from one node to any other node is possible in order to find the minimum spanning tree, ie, 
the graph should be connected  In the given graph we can observe that it is not possible to traverse from node D to any other node. 
Therefore prims algorithms cannot be used to solve directed graphs.

KRUSKALS ALGORTIHM

For each step in kruskals algorithm we check if the minimum spanning forms a cycle or not. 
in directed graph only closed loops are said to form cycles but the kruskals algorithm assumes the MST to form cycles even if the loops aren’t closed.

