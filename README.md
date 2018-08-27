Prim's algorithm is a greedy algorithm that finds a minimum spanning tree for a weighted undirected graph. This means it finds a subset of the edges that forms a tree that includes every vertex,
where the total weight of all the edges in the tree is minimized(https://en.wikipedia.org/wiki/Prim%27s_algorithm)

here is the implantation of this algortihm in java.
I have written it in NetBeans IDE as you can see the packages. 

when you run the program you will be asked to enter the number of vertexes, edges, and also the value of on each edge.
lets say you have a graph like this :

![Alt text](https://github.com/Hazel1994/Prims_algorithm/blob/master/images/graph.png)

to create a the above graph you should enter the following numbers:

number of vertexes : 4
number of edges: 5

Enter the number of first and second vertex and also the value of  their edge 1 2 3

Enter the number of first and second vertex and also the value of  their edge 1 3 6

Enter the number of first and second vertex and also the value of  their edge 1 4 9

Enter the number of first and second vertex and also the value of  their edge 2 4 6

Enter the number of first and second vertex and also the value of  their edge 3 4 2

here is an example of running the program :
![Alt text](https://github.com/Hazel1994/Prims_algorithm/blob/master/images/p1.png)

i will print out the minimum cost and also specify linked vertexes.
it will also plot an ugly graph of the optimal solution as follows:

![Alt text](https://github.com/Hazel1994/Prims_algorithm/blob/master/images/p2.png)
please note that the plot does not work for big graphs.

I would explain the details but i dont remember anything because i wrote it a few years a go. i hope its useful.
