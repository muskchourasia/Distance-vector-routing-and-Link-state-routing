# Distance-vector-routing-and-Link-state-routing
Problem Statement
Write a program which will differentiate between distance vector routing and link state routing.
Consider 'n' number of nodes/routes in a network. Make sure that number of links are greater than 
n.Randomly initialize weights for each link. For any source and destination find the shortest path
chosen by DVR and LSR.

In the given problem the user has to enter the number of nodes and the links and their weights .
once the weights are entered distance vectorrouting algorithm send the distance from starting 
node to all other nodes to it's neighbours.The distance vector algorithm uses Bellman-Ford 
algorithm.It requires that a router inform its neighbors of topology changes periodically.
On the other hand in link state routing protocol each router shares the knowledge of its 
neighborhood with every other router in the internetwork.It used Dijstra algorithm for 
computing the shortest path.
