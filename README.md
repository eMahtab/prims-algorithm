# Prim's Algorithm
Prim's algorithm is used to find the Minimum Spanning Tree of a graph.

## Algorithm :
1. Take a `Priority queue pq` and pass the comparator to return the minimum cost vertex, add the startingVertex with cost 0 to pq.
2. While pq is not empty remove the vertex from the priority queue, if this vertex is not already visited then visit this vertex and add its `unvisited neighbors` to pq.
3. Sum the cost while visiting an unvisited node, and also mark this node to be visited, so that we don't visit this vertex again.

## Note : Prim's algorithm is similar to Dijkstra's algorithm but we don't relax the neighboring vertices of vertex in Prim's algorithm.

# References :
https://www.youtube.com/watch?v=Vw-sktU1zmc

# Problems :
https://leetcode.com/problems/connecting-cities-with-minimum-cost


